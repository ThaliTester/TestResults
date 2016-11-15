#### Test 937391739bc1cf0_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-15 14:03:46.608  3994  4242 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-15 14:03:46.682  3994  4242 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-15 14:03:47.090  5577  5577 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-15 14:03:47.095  5577  5577 D AndroidRuntime: CheckJNI is OFF
11-15 14:03:47.123  5577  5577 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-15 14:03:47.166  5577  5577 I Radio-JNI: register_android_hardware_Radio DONE
11-15 14:03:47.181  5577  5577 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-15 14:03:47.191   926  3786 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-15 14:03:47.211  5577  5577 D AndroidRuntime: Shutting down VM
11-15 14:03:47.217  3979  3989 W SearchService: Abort, client detached.
11-15 14:03:47.229  3979  4234 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@9370bb9
11-15 14:03:47.230  3979  4239 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-15 14:03:47.229  3979  3979 I HotwordDetector: Closing mic
11-15 14:03:47.244   926  3789 I ActivityManager: Start proc 5586:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-15 14:03:47.301   513  4241 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-15 14:03:47.302   513  4241 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-15 14:03:47.310   513  4241 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-15 14:03:47.310   513  4241 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-15 14:03:47.311   513  3001 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-15 14:03:47.313  3979  4238 I MicroRecognitionRnrImpl: Detection finished
11-15 14:03:47.313  3979  4235 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-15 14:03:47.350  5586  5586 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-15 14:03:47.373  5586  5586 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-15 14:03:47.434  5586  5586 I LibraryLoader: Time to load native libraries: 57 ms (timestamps 8793-8850)
11-15 14:03:47.434  5586  5586 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-15 14:03:47.473  5586  5586 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c47884e}
,11-15 14:03:47.473  5586  5586 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-15 14:03:47.474  5586  5586 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-15 14:03:47.477  5586  5586 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-15 14:03:47.477  5586  5586 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-15 14:03:47.525  5586  5586 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-15 14:03:47.533  5586  5586 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-15 14:03:47.533  5586  5586 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-15 14:03:47.533  5586  5586 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-15 14:03:47.533  5586  5586 I Adreno  : Build Date                       : 12/06/15
11-15 14:03:47.533  5586  5586 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-15 14:03:47.533  5586  5586 I Adreno  : Local Branch                     : mybranch17112971
11-15 14:03:47.533  5586  5586 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-15 14:03:47.533  5586  5586 I Adreno  : Remote Branch                    : NONE
11-15 14:03:47.533  5586  5586 I Adreno  : Reconstruct Branch               : NOTHING
,11-15 14:03:47.581   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@853f919:true
,11-15 14:03:47.618   857   857 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[22245]" dev="sockfs" ino=22245 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 14:03:47.618   857   857 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22245]" dev="sockfs" ino=22245 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 14:03:47.631  5586  5586 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-15 14:03:47.639  5586  5586 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-15 14:03:47.762   857   857 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32506]" dev="sockfs" ino=32506 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 14:03:47.762   857   857 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32506]" dev="sockfs" ino=32506 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 14:03:47.767  5586  5623 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-15 14:03:47.772  3580  3580 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[22249]" dev="sockfs" ino=22249 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 14:03:47.772  3580  3580 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22249]" dev="sockfs" ino=22249 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 14:03:47.776  5586  5610 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-15 14:03:47.810  5586  5623 I OpenGLRenderer: Initialized EGL, version 1.4
,11-15 14:03:47.879   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +659ms
11-15 14:03:47.875  3844  3844 W Binder_C: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32514]" dev="sockfs" ino=32514 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 14:03:47.875  3844  3844 W Binder_C: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32514]" dev="sockfs" ino=32514 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 14:03:47.884  3661  3661 I Keyboard.Facilitator: onFinishInput()
,11-15 14:03:47.878  3129  3129 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32513]" dev="sockfs" ino=32513 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 14:03:47.878  3129  3129 W Binder_3: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32513]" dev="sockfs" ino=32513 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 14:03:47.917  5586  5586 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5586
,11-15 14:03:48.025  5586  5586 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-15 14:03:48.243  5586  5625 D jxcore_app_log: JniHelper::setJavaVM(0xf4efc000), pthread_self() = -604243664
,11-15 14:03:48.249  5586  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-15 14:03:48.249  5586  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-15 14:03:48.249  5586  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-15 14:03:48.249  5586  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-15 14:03:48.249  5586  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-15 14:03:48.250  5586  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6e90b7d added. We now have 1 listener(s)
,11-15 14:03:48.255  5586  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-15 14:03:48.263  5586  5625 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 14:03:48.263  5586  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 14:03:48.264  5586  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-15 14:03:48.266  5586  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a421340 added. We now have 1 listener(s)
11-15 14:03:48.266  5586  5625 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 14:03:48.272   926  2977 D WifiService: New client listening to asynchronous messages
11-15 14:03:48.274  5586  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 14:03:48.274  5586  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-15 14:03:48.274  5586  5625 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-15 14:03:48.275  5586  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-15 14:03:48.275  5586  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-15 14:03:48.275  5586  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-15 14:03:48.275  5586  5625 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-15 14:03:48.277  5586  5625 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-15 14:03:48.407  5586  5586 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-15 14:03:48.776  5586  5595 I art     : Background sticky concurrent mark sweep GC freed 76886(7MB) AllocSpace objects, 16(1076KB) LOS objects, 25% free, 24MB/32MB, paused 1.391ms total 294.528ms
,11-15 14:03:49.115   926  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 14:03:49.767  5586  5633 W jxcore-log: Initializing JXcore engine
11-15 14:03:49.767  5586  5633 W jxcore-log: JXcore engine is ready
,11-15 14:03:49.788  5633  5633 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12997 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-15 14:03:49.788  5633  5633 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13351]" dev="sockfs" ino=13351 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-15 14:03:49.788  5633  5633 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-15 14:03:49.788  5633  5633 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32479]" dev="sockfs" ino=32479 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-15 14:03:49.799  5586  5633 W jxcore-log: Starting JXcore engine
,11-15 14:03:49.847  5586  5633 W jxcore-log: Platform android
11-15 14:03:49.847  5586  5633 W jxcore-log: 
11-15 14:03:49.847  5586  5633 W jxcore-log: Process ARCH arm
11-15 14:03:49.847  5586  5633 W jxcore-log: 
,11-15 14:03:50.022  5586  5633 I jxcore-log: JXcore Cordova bridge is ready!
11-15 14:03:50.022  5586  5633 I jxcore-log: 
,11-15 14:03:50.022  5586  5633 W jxcore-log: JXcore engine is started
,11-15 14:03:50.035  5586  5625 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-15 14:03:50.040  5586  5586 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-15 14:03:50.749  3585  3585 I ConfigService: onDestroy
,11-15 14:03:52.204   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:03:52.232   926  3844 I ActivityManager: Killing 5143:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-15 14:03:52.309   926  3789 I ActivityManager: Killing 5232:org.codeaurora.ims/1001 (adj 15): empty #17
,11-15 14:03:53.204   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:03:54.205   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:03:55.206   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:03:56.207   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:03:57.208   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-15 14:03:59.893  5586  5633 I jxcore-log: 2016-11-15 13:03:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-15 14:03:59.893  5586  5633 I jxcore-log: 
,11-15 14:03:59.895  5586  5633 I jxcore-log: 2016-11-15 13:03:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-15 14:03:59.895  5586  5633 I jxcore-log: 
,11-15 14:03:59.900  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-15 14:03:59.900  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 14:03:59.900  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:03:59.900  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:03:59.900  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:03:59.900  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:03:59.900  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 14:03:59.900  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 14:03:59.900  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 14:03:59.900  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 14:03:59.901  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 14:03:59.904  5586  5633 I jxcore-log: 2016-11-15 13:03:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-15 14:03:59.904  5586  5633 I jxcore-log: 
,11-15 14:03:59.905  5586  5633 I jxcore-log: 2016-11-15 13:03:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-15 14:03:59.905  5586  5633 I jxcore-log: 
,11-15 14:04:00.153  5586  5633 I jxcore-log: 2016-11-15 13:04:00 - DEBUG UnitTest_app: 'Running unit tests'
11-15 14:04:00.153  5586  5633 I jxcore-log: 
11-15 14:04:00.153  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 14:04:00.154  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4004c69 added. We now have 2 listener(s)
11-15 14:04:00.154  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 14:04:00.154  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 14:04:00.154  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-15 14:04:00.155  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:04:00.155  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9eb6ee added. We now have 2 listener(s)
11-15 14:04:00.155  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 14:04:00.155  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 14:04:00.156  5586  5633 D executeNativeTests: Running unit tests
,11-15 14:04:00.196  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 14:04:00.197  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f added. We now have 3 listener(s)
11-15 14:04:00.197  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 14:04:00.197  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 14:04:00.197  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 14:04:00.198  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:04:00.198  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c added. We now have 3 listener(s)
11-15 14:04:00.198  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 14:04:00.198  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 14:04:00.201  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 14:04:00.201  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-15 14:04:00.201  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:04:00.201  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:04:00.202  5586  5633 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,11-15 14:04:00.202  5586  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-15 14:04:00.202  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 14:04:00.202  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 14:04:00.202  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-15 14:04:00.202  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 14:04:00.202  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:00.203  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-15 14:04:00.203  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:00.203  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:00.203  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:00.203  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 14:04:00.203  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f removed from the list
11-15 14:04:00.203  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:00.203  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c removed from the list
11-15 14:04:00.204  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:00.204  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.205  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:00.205  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.205  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.205  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:00.205  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:00.205  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:00.205  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:00.206  5586  5633 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-15 14:04:00.206  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:00.206  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:00.206  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:00.206  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:00.206  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:00.206  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:00.206  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 14:04:00.207  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:00.207  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:00.207  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.208  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.208  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:00.208  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.208  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:00.208  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:00.208  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:00.208  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:00.210  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-15 14:04:00.211  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-15 14:04:00.212  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-15 14:04:00.212  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-15 14:04:00.212  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-15 14:04:00.212  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:00.212  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:00.212  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:00.212  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:00.212  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:00.212  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:00.212  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:00.212  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:00.212  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:00.212  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.213  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.213  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.213  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.213  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:00.213  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:00.213  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:00.213  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:00.213  5586  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-15 14:04:00.215  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:04:00.215  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-15 14:04:00.222  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 14:04:00.222  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:04:00.222  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:04:00.222  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:04:00.222  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:04:00.222  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 14:04:00.222  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 14:04:00.222  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 14:04:00.222  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 14:04:00.223  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-15 14:04:00.223  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
11-15 14:04:00.223  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 14:04:00.223  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-15 14:04:00.223  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-15 14:04:00.223  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:04:00.223  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 14:04:00.225  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:00.226  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 14:04:00.226  5586  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 14:04:00.226  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 14:04:00.226  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:00.229  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.229  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 14:04:00.230  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 14:04:00.230  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 14:04:00.230  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-15 14:04:00.231  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-15 14:04:00.232  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-15 14:04:00.232  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.232  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 14:04:00.233  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 14:04:00.233  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 14:04:00.233  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 14:04:00.233  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.233  5586  5633 D BluetoothAdapter: STATE_ON
11-15 14:04:00.235  4664  4896 D BtGatt.GattService: registerClient() - UUID=77e4d218-0a8f-4c20-9a13-4be61cbf3075
11-15 14:04:00.236  4664  4736 D BtGatt.GattService: onClientRegistered() - UUID=77e4d218-0a8f-4c20-9a13-4be61cbf3075, clientIf=5
11-15 14:04:00.238  5586  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-15 14:04:00.239  4664  4676 D BtGatt.GattService: start scan with filters
11-15 14:04:00.249  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-15 14:04:00.249  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.249  4664  4739 D BtGatt.ScanManager: handling starting scan
11-15 14:04:00.249  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 14:04:00.249  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.250  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 14:04:00.250  5586  5586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 14:04:00.250  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:04:00.250  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 14:04:00.250  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 14:04:00.250  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 14:04:00.250  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.250  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:04:00.251  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-15 14:04:00.251  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-15 14:04:00.251  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.251  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.251  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:00.251  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:04:00.251  5586  5633 I io.jxcore.node.ConnectionHelper: start: OK
11-15 14:04:00.252  4664  4739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
11-15 14:04:00.254  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:04:00.255  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 14:04:00.255  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:04:00.255  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:04:00.255  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:04:00.255  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-15 14:04:00.283  4664  4736 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-15 14:04:00.283  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:00.284  4664  4739 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-15 14:04:00.291  4664  4736 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-15 14:04:00.291  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:00.291  4664  4739 D BtGatt.ScanManager: Starting BLE batch scan
11-15 14:04:00.292  4664  4739 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-15 14:04:00.302  4664  4736 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-15 14:04:00.302  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:00.306  4664  4736 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-15 14:04:00.307  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:04:00.379   926  2977 D WifiService: New client listening to asynchronous messages
,11-15 14:04:00.383  3979  5634 W CronetSyncConnectionRcs: Upload content type not set.
,11-15 14:04:00.455  4901  4931 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-15 14:04:00.456  4901  4901 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-15 14:04:00.756  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-15 14:04:00.757  5586  5586 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-15 14:04:00.757  5586  5586 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 14:04:05.256  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 14:04:05.256  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-15 14:04:05.256  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-15 14:04:05.256  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-15 14:04:05.256  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 14:04:05.256  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 14:04:05.256  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 14:04:05.256  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-15 14:04:05.257  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 14:04:05.257  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-15 14:04:05.258  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.258  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.258  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.258  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-15 14:04:05.258  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.259  5586  5633 D BluetoothAdapter: STATE_ON
11-15 14:04:05.260  4664  4888 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-15 14:04:05.260  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 14:04:05.261  4664  4739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-15 14:04:05.261  5586  5633 D BluetoothAdapter: STATE_ON
11-15 14:04:05.262  4664  4676 D BtGatt.GattService: stopScan() - queue size =1
11-15 14:04:05.263  4664  4677 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 14:04:05.263  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 14:04:05.263  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.264  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-15 14:04:05.264  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:05.264  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.264  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.264  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.264  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 14:04:05.265  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.265  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.265  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.265  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-15 14:04:05.265  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 14:04:05.266  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 14:04:05.266  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.268  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.268  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:04:05.268  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.268  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:05.268  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:05.268  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 14:04:05.269  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 14:04:05.269  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:04:05.269  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:05.269  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:05.269  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:05.269  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:04:05.269  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:05.269  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:05.269  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 14:04:05.269  5586  5586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 14:04:05.269  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:04:05.270  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 14:04:05.270  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 14:04:05.270  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:04:05.270  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 14:04:05.271  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-15 14:04:05.271  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:04:05.273  4664  4664 D BtGatt.ScanManager: awakened up at time 9,6689
11-15 14:04:05.275  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:04:05.275  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:04:05.275  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:04:05.275  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:04:05.276  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 14:04:05.293  4664  4736 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-15 14:04:05.293  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:04:05.293  4664  4736 D BtGatt.GattService: current time is 96709577089
11-15 14:04:05.294  4664  4736 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -87, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, -128, -98, 63, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -93, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -84, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -86, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:04:05.295  4664  4736 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:04:05.296  4664  4736 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:04:05.296  4664  4736 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:04:05.296  4664  4736 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:04:05.296  4664  4736 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:04:05.297  4664  4736 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:04:05.304  4664  4736 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-15 14:04:05.304  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:05.304  4664  4739 D BtGatt.ScanManager: stopping BLe Batch
,11-15 14:04:05.311  4664  4736 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-15 14:04:05.311  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:05.311  4664  4739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:04:05.318  4664  4736 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-15 14:04:05.318  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:04:05.777  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 14:04:10.271  5586  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-15 14:04:10.274  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:04:10.274  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 14:04:10.281  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 14:04:10.281  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:04:10.281  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:04:10.281  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:04:10.281  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:04:10.281  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 14:04:10.281  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 14:04:10.281  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 14:04:10.281  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 14:04:10.286  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-15 14:04:10.286  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
11-15 14:04:10.286  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 14:04:10.287  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-15 14:04:10.287  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-15 14:04:10.287  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:04:10.287  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 14:04:10.292  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 14:04:10.294  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 14:04:10.294  5586  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 14:04:10.294  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-15 14:04:10.301  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:10.302  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:10.302  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-15 14:04:10.303  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 14:04:10.303  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 14:04:10.304  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-15 14:04:10.311  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.311  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 14:04:10.311  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 14:04:10.311  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 14:04:10.311  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 14:04:10.311  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.313  5586  5633 D BluetoothAdapter: STATE_ON
11-15 14:04:10.317  4664  4896 D BtGatt.GattService: registerClient() - UUID=e02b4aba-8dab-4947-b214-c95b85883cbd
,11-15 14:04:10.317  4664  4736 D BtGatt.GattService: onClientRegistered() - UUID=e02b4aba-8dab-4947-b214-c95b85883cbd, clientIf=5
,11-15 14:04:10.318  5586  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-15 14:04:10.318  4664  4676 D BtGatt.GattService: start scan with filters
,11-15 14:04:10.323  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-15 14:04:10.323  4664  4739 D BtGatt.ScanManager: handling starting scan
11-15 14:04:10.323  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.324  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 14:04:10.324  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.324  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 14:04:10.324  5586  5586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 14:04:10.324  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-15 14:04:10.324  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 14:04:10.324  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 14:04:10.325  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.325  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.325  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-15 14:04:10.326  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 14:04:10.327  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.331  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.331  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 14:04:10.331  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.331  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.332  5586  5633 I io.jxcore.node.ConnectionHelper: start: OK
,11-15 14:04:10.335  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:10.339  5586  5633 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-15 14:04:10.339  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:10.339  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 14:04:10.339  4664  4736 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-15 14:04:10.339  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 14:04:10.339  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:10.340  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 14:04:10.340  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 14:04:10.332  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.340  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 14:04:10.340  4664  4739 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-15 14:04:10.344  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.345  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-15 14:04:10.345  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.345  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.345  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 14:04:10.345  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 14:04:10.345  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 14:04:10.345  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-15 14:04:10.345  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.346  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:10.346  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.346  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-15 14:04:10.346  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.347  5586  5633 D BluetoothAdapter: STATE_ON
11-15 14:04:10.348  4664  4897 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-15 14:04:10.348  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-15 14:04:10.349  5586  5633 D BluetoothAdapter: STATE_ON
,11-15 14:04:10.350  4664  4896 D BtGatt.GattService: stopScan() - queue size =1
11-15 14:04:10.350  4664  4736 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-15 14:04:10.351  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:10.351  4664  4739 D BtGatt.ScanManager: Starting BLE batch scan
11-15 14:04:10.351  4664  4739 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-15 14:04:10.352  4664  4676 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 14:04:10.352  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 14:04:10.352  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:10.352  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-15 14:04:10.353  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.353  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.353  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.353  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.353  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 14:04:10.353  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.353  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.353  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.353  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 14:04:10.353  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 14:04:10.358  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 14:04:10.358  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.359  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.359  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:04:10.359  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:10.359  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.359  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:10.359  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:04:10.359  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 14:04:10.360  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 14:04:10.360  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:04:10.360  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:10.360  5586  5586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 14:04:10.360  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:10.360  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.360  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:10.360  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:10.360  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:10.360  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 14:04:10.361  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.363  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.363  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.363  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.363  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:10.363  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:10.363  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:10.363  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:10.360  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 14:04:10.364  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 14:04:10.364  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.364  5586  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-15 14:04:10.364  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.364  5586  5586 I org.th,aliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-15 14:04:10.364  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.364  4664  4736 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-15 14:04:10.365  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:10.366  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.366  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:04:10.366  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.366  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-15 14:04:10.366  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.366  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.366  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:04:10.371  4664  4736 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-15 14:04:10.371  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:04:10.372  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 14:04:10.372  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:04:10.372  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:04:10.372  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:04:10.372  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:04:10.372  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 14:04:10.372  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 14:04:10.372  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 14:04:10.372  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 14:04:10.374  4664  4739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:04:10.374  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 14:04:10.375  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
11-15 14:04:10.375  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 14:04:10.375  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-15 14:04:10.375  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-15 14:04:10.375  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:04:10.375  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 14:04:10.378  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:10.378  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 14:04:10.379  5586  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 14:04:10.379  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 14:04:10.379  4664  4736 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-15 14:04:10.379  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:10.379  4664  4736 E BtGatt.ContextMap: Context not found for ID 5
,11-15 14:04:10.380  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:10.383  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:10.383  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 14:04:10.384  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 14:04:10.384  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 14:04:10.384  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-15 14:04:10.386  4664  4736 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-15 14:04:10.386  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:10.386  4664  4739 D BtGatt.ScanManager: stopping BLe Batch
11-15 14:04:10.388  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.388  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 14:04:10.388  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 14:04:10.388  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 14:04:10.388  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 14:04:10.388  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.389  5586  5633 D BluetoothAdapter: STATE_ON
,11-15 14:04:10.391  4664  4736 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-15 14:04:10.391  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:10.392  4664  4739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:04:10.392  4664  4676 D BtGatt.GattService: registerClient() - UUID=f7d77578-c0c7-4d8c-a8d5-fc91c414b9c6
,11-15 14:04:10.395  4664  4736 D BtGatt.GattService: onClientRegistered() - UUID=f7d77578-c0c7-4d8c-a8d5-fc91c414b9c6, clientIf=5
,11-15 14:04:10.395  5586  5597 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-15 14:04:10.395  4664  4897 D BtGatt.GattService: start scan with filters
,11-15 14:04:10.397  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-15 14:04:10.398  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.398  4664  4736 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-15 14:04:10.398  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:10.398  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 14:04:10.398  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.398  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-15 14:04:10.398  5586  5586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 14:04:10.398  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.398  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 14:04:10.398  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 14:04:10.398  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.398  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.398  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-15 14:04:10.399  4664  4739 D BtGatt.ScanManager: handling starting scan
11-15 14:04:10.399  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 14:04:10.399  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.401  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.402  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 14:04:10.402  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.402  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:10.402  5586  5633 I io.jxcore.node.ConnectionHelper: start: OK
,11-15 14:04:10.402  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-15 14:04:10.404  4664  4736 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-15 14:04:10.404  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:10.404  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.404  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.404  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:04:10.404  4664  4739 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-15 14:04:10.405  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-15 14:04:10.405  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-15 14:04:10.409  4664  4736 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-15 14:04:10.409  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:10.409  4664  4739 D BtGatt.ScanManager: Starting BLE batch scan
11-15 14:04:10.409  4664  4739 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-15 14:04:10.418  4664  4736 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-15 14:04:10.418  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:04:10.423  4664  4736 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-15 14:04:10.423  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:04:10.906  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-15 14:04:10.906  5586  5586 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-15 14:04:10.907  5586  5586 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 14:04:15.402  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:15.403  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:15.403  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-15 14:04:15.403  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 14:04:15.403  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 14:04:15.403  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:15.404  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 14:04:15.404  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 14:04:15.404  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 14:04:15.404  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-15 14:04:15.405  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:15.405  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:15.405  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:15.405  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-15 14:04:15.405  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:15.407  5586  5633 D BluetoothAdapter: STATE_ON
11-15 14:04:15.408  4664  4897 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-15 14:04:15.409  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 14:04:15.410  4664  4739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:04:15.411  5586  5633 D BluetoothAdapter: STATE_ON
11-15 14:04:15.413  4664  4677 D BtGatt.GattService: stopScan() - queue size =1
11-15 14:04:15.414  4664  4888 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 14:04:15.415  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-15 14:04:15.416  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:15.416  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-15 14:04:15.416  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:15.416  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:15.417  4664  4664 D BtGatt.ScanManager: awakened up at time 106833
11-15 14:04:15.417  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:15.417  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:15.417  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 14:04:15.417  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:15.418  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:15.418  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:15.418  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 14:04:15.419   926  3786 I ActivityManager: Killing 5248:com.android.settings/1000 (adj 15): empty #17
11-15 14:04:15.418  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-15 14:04:15.450  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 14:04:15.451  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:15.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:15.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:04:15.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:15.452  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:15.453  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:04:15.453  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-15 14:04:15.453  5586  5586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 14:04:15.453  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:04:15.453  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 14:04:15.453  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 14:04:15.453  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:04:15.453  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 14:04:15.453  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-15 14:04:15.454  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:04:15.455  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:04:15.455  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:04:15.455  5586  5586 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:04:15.455  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:04:15.455  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 14:04:15.462  4664  4736 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 14:04:15.462  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:15.462  4664  4736 D BtGatt.GattService: current time is 106878637082
11-15 14:04:15.462  4664  4736 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -85, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -86, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -93, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:04:15.463  4664  4736 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:04:15.463  4664  4736 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:04:15.463  4664  4736 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:04:15.464  4664  4736 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:04:15.464  4664  4736 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:04:15.465  4664  4736 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:04:15.469  4664  4736 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-15 14:04:15.470  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:15.470  4664  4739 D BtGatt.ScanManager: stopping BLe Batch
,11-15 14:04:15.475  4664  4736 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-15 14:04:15.475  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:04:15.475  4664  4739 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:04:15.480  4664  4736 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-15 14:04:15.480  4664  4736 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:04:15.956  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 14:04:15.957  5586  5586 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:15.957  5586  5586 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 14:04:20.454  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 14:04:20.454  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:20.455  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:20.455  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 14:04:20.455  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 14:04:20.455  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 14:04:20.455  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:20.456  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
,11-15 14:04:20.456  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.456  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
,11-15 14:04:20.456  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:04:20.456  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 14:04:20.461  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.463  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.464  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:20.464  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.464  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:20.464  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:20.464  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 14:04:20.464  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
,11-15 14:04:20.466  5586  5633 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-15 14:04:20.467  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 14:04:20.468  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-15 14:04:20.468  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-15 14:04:20.468  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:20.468  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 14:04:20.468  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:20.469  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 14:04:20.469  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.469  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:04:20.469  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.472  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:20.472  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.472  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.473  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:20.473  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-15 14:04:20.473  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.473  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.474  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-15 14:04:20.474  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:20.474  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:20.474  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:20.474  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:20.475  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:20.475  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
,11-15 14:04:20.475  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.475  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.475  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:20.475  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.477  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.477  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:20.477  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:20.477  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:20.477  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:20.477  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.477  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.478  5586  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-15 14:04:20.478  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:20.478  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:20.479  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:20.479  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:20.479  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 14:04:20.479  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:20.479  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.479  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.479  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:20.479  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.480  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:20.481  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.481  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.481  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:20.481  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:20.481  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.481  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
,11-15 14:04:20.482  5586  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-15 14:04:20.482  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:20.482  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:20.482  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:20.482  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 14:04:20.482  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:20.482  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:20.482  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.483  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.483  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:04:20.483  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.484  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.484  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.484  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.484  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-15 14:04:20.484  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:20.484  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.484  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.485  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 14:04:20.485  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-15 14:04:20.485  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:04:20.486  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 14:04:20.486  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 14:04:20.486  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 14:04:20.486  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 14:04:20.486  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:04:20.486  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:04:20.486  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 14:04:20.486  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:20.486  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:20.486  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:20.486  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:20.486  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
,11-15 14:04:20.486  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.487  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.487  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:20.487  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.488  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:20.488  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.488  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:20.488  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-15 14:04:20.488  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:20.488  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.489  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.489  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 14:04:20.490  5586  5633 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-15 14:04:20.490  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-15 14:04:20.493  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 14:04:20.493  5586  5633 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-15 14:04:20.493  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-15 14:04:20.493  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-15 14:04:20.494  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-15 14:04:20.495  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-15 14:04:20.495  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-15 14:04:20.495  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-15 14:04:20.495  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-15 14:04:20.495  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-15 14:04:20.495  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-15 14:04:20.495  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-15 14:04:20.495  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-15 14:04:20.495  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-15 14:04:20.495  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-15 14:04:20.495  5586  5633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-15 14:04:20.495  5586  5633 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-15 14:04:20.496  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 14:04:20.496  5586  5633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-15 14:04:20.496  5586  5633 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-15 14:04:20.496  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 14:04:20.496  5586  5633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-15 14:04:20.496  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-15 14:04:20.501  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-15 14:04:20.502  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-15 14:04:20.502  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-15 14:04:20.505  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-15 14:04:20.505  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-15 14:04:20.505  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-15 14:04:20.505  5586  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 14:04:20.506  5586  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-15 14:04:20.506  5586  5633 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-15 14:04:20.506  5586  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-15 14:04:20.506  5586  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-15 14:04:20.506  5586  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-15 14:04:20.507  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:20.507  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:20.507  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:20.507  5586  5633 I org.thali,project.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:20.507  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:20.507  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-15 14:04:20.508  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:20.508  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.508  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.508  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:20.509  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.509  5586  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-15 14:04:20.509  5586  5646 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-15 14:04:20.509  5586  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-15 14:04:20.509  5586  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-15 14:04:20.509  5586  5646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:04:20.509  5586  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
11-15 14:04:20.508  4888  4888 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30713]" dev="sockfs" ino=30713 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 14:04:20.508  4888  4888 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[30713]" dev="sockfs" ino=30713 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 14:04:20.510  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.510  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.511  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.511  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:20.511  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:20.511  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.511  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.512  5586  5633 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-15 14:04:20.512  5586  5646 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-15 14:04:20.512  5586  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-15 14:04:20.512  5586  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-15 14:04:20.512  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stoppin,g all activities and killing connections
11-15 14:04:20.512  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:20.512  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:20.513  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:20.513  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:20.513  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:20.513  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.513  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.513  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:20.513  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.515  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.515  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.515  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.515  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:20.515  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:20.515  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.515  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.516  5586  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-15 14:04:20.516  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:20.516  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:20.516  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:20.516  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:20.516  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:20.516  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:20.516  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.516  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.516  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:20.517  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.518  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.518  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.518  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.518  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:20.518  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:20.518  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.518  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.519  5586  5633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-15 14:04:20.519  5586  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-15 14:04:20.519  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 14:04:20.519  5586  5633 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-15 14:04:20.519  5586  5633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-15 14:04:20.519  5586  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-15 14:04:20.519  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 14:04:20.519  5586  5633 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-15 14:04:20.519  5586  5633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-15 14:04:20.519  5586  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-15 14:04:20.519  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 14:04:20.519  5586  5633 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-15 14:04:20.520  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:20.520  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:20.520  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:20.520  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:20.520  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:20.520  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:20.520  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.520  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.520  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:20.520  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.521  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.522  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.522  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:20.522  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:20.522  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:20.522  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.523  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.523  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:20.523  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:20.523  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:20.524  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:20.524  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:20.524  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:04:22.209   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-15 14:04:22.209   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-15 14:04:25.524  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 14:04:25.525  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:25.525  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:25.525  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:25.525  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
,11-15 14:04:25.526  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:25.526  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:25.526  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:25.526  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 14:04:25.526  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:25.527  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:25.527  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:25.527  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
,11-15 14:04:25.527  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:25.528  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:25.531  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.531  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.532  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.532  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-15 14:04:25.532  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:25.532  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:25.532  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
,11-15 14:04:25.537  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-15 14:04:25.538  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:04:25.538  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 14:04:25.543  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-15 14:04:25.545  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-15 14:04:25.545  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 14:04:25.546  5586  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-15 14:04:25.546  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 14:04:25.547  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-15 14:04:25.547  5586  5586 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 14:04:25.547  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 14:04:25.548  5586  5648 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:04:25.548  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:25.548  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-15 14:04:25.549  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 14:04:25.549  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-15 14:04:25.548  4897  4897 W Binder_5: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[30718]" dev="sockfs" ino=30718 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 14:04:25.549  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-15 14:04:25.550  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-15 14:04:25.551  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 14:04:25.551  5586  5586 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 14:04:25.551  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:25.551  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 14:04:25.551  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 14:04:25.548  4897  4897 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[30718]" dev="sockfs" ino=30718 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 14:04:25.552  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 14:04:25.552  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 14:04:25.552  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:25.553  5586  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 14:04:25.553  5586  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 14:04:25.554  5586  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 14:04:25.555  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.555  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 14:04:25.555  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.555  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.556  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:25.556  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:04:25.556  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:25.556  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-15 14:04:25.556  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:25.556  5586  5586 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 14:04:25.556  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:25.556  5586  5586 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:25.556  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:25.556  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:25.556  5586  5586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:04:25.556  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:25.557  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:25.557  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:25.557  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:04:25.557  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.559  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.559  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.560  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.560  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:25.560  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:25.560  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:25.560  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
,11-15 14:04:25.563  5586  5633 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-15 14:04:25.563  5586  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-15 14:04:25.563  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 14:04:25.565  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 14:04:25.565  5586  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-15 14:04:25.565  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:04:25.565  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:25.565  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:25.565  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:25.565  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 14:04:25.566  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:25.566  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:25.566  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:25.566  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:25.566  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.570  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.570  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.571  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:25.571  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:25.572  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:25.572  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:25.572  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
,11-15 14:04:25.578  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 14:04:25.579  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:25.579  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:25.579  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 14:04:25.579  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:25.579  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:25.579  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 14:04:25.579  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:25.579  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:25.580  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:25.582  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.582  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.582  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.582  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:25.582  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-15 14:04:25.582  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:25.582  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
,11-15 14:04:25.586  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 14:04:25.586  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:04:25.586  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:04:25.586  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:04:25.586  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:04:25.586  5586  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360827f not in the list
11-15 14:04:25.586  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 14:04:25.586  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
11-15 14:04:25.586  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:25.586  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:25.588  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:04:25.589  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.589  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:04:25.589  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:04:25.589  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:04:25.589  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:25.589  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@514724c not in the list
,11-15 14:04:25.590  5586  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-15 14:04:25.591  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 14:04:25.591  5586  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-15 14:04:25.591  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-15 14:04:25.591  5586  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-15 14:04:25.591  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-15 14:04:25.594  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-15 14:04:25.595  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-15 14:04:25.595  5586  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-15 14:04:25.595  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-15 14:04:25.595  5586  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-15 14:04:25.595  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-15 14:04:25.595  5586  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-15 14:04:25.595  5586  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-15 14:04:25.596  5586  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-15 14:04:25.596  5586  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-15 14:04:25.596  5586  5633 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-15 14:04:25.596  5586  5633 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-15 14:04:25.597  5586  5633 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-15 14:04:25.597  5586  5633 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-15 14:04:25.598  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:04:25.598  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@837bb05 added. We now have 3 listener(s)
11-15 14:04:25.598  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 14:04:25.602  5586  5633 D BluetoothAdapter: enable(): BT is already enabled..!
,11-15 14:04:25.602   926  3778 D WifiService: setWifiEnabled: true pid=5586, uid=10077
11-15 14:04:25.602   926  3778 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 14:04:25.638  4664  4868 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-15 14:04:25.639  4664  4886 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-15 14:04:26.058  5586  5586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 14:04:27.210   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:28.211   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:29.120   926  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 14:04:29.212   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:30.213   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:30.460   926  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 14:04:30.608  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-15 14:04:30.608  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@594575a added. We now have 4 listener(s)
,11-15 14:04:30.608  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 14:04:30.626  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 14:04:30.626  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@594575a removed from the list
,11-15 14:04:30.626  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:04:30.629  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-15 14:04:30.629  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c62cd8b added. We now have 4 listener(s)
11-15 14:04:30.629  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 14:04:30.633  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 14:04:30.633  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c62cd8b removed from the list
,11-15 14:04:30.633  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:04:30.634  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:04:30.635  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5340e68 added. We now have 4 listener(s)
11-15 14:04:30.635  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 14:04:30.638   926  3160 D WifiService: setWifiEnabled: false pid=5586, uid=10077
11-15 14:04:30.638   926  3160 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-15 14:04:30.643   926  2976 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-15 14:04:30.643   926  2976 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-15 14:04:30.643   926  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 14:04:30.643   926  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 14:04:30.650  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:04:30.650  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-15 14:04:30.651  4664  4732 D BluetoothAdapterState: Current state: ON, message: 23
11-15 14:04:30.651  4664  4732 D BluetoothAdapterProperties: Setting state to 13
11-15 14:04:30.651  4664  4732 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-15 14:04:30.654  4664  4732 D BluetoothAdapterProperties: onBluetoothDisable()
11-15 14:04:30.655  4664  4732 I BluetoothAdapterState: Entering PendingCommandState
11-15 14:04:30.657  4664  4736 D BluetoothAdapterProperties: Scan Mode:20
11-15 14:04:30.658  4664  4732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-15 14:04:30.660  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 14:04:30.660  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 14:04:30.660  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:04:30.660  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:04:30.660  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:04:30.660  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 14:04:30.660  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 14:04:30.660  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 14:04:30.660  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 14:04:30.660  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 14:04:30.662  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 14:04:30.662  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-15 14:04:30.662  5586  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
11-15 14:04:30.663   926  5362 D DhcpClient: Clearing IP address
,11-15 14:04:30.664   508   920 D CommandListener: Clearing all IP addresses on wlan0
,11-15 14:04:30.667  4664  4664 D HeadsetService: Received stop request...Stopping profile...
,11-15 14:04:30.668  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:30.673   508   920 D CommandListener: Setting iface cfg
,11-15 14:04:30.674  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 14:04:30.679   926   939 I ActivityManager: Start proc 5652:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-15 14:04:30.680  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:30.682   926   926 D BluetoothHeadset: Proxy object disconnected
11-15 14:04:30.684  3812  3841 D BluetoothHeadset: Proxy object disconnected
,11-15 14:04:30.684  3133  3145 D BluetoothHeadset: Proxy object disconnected
11-15 14:04:30.684  3133  3133 D HeadsetProfile: Bluetooth service disconnected
11-15 14:04:30.685   926   926 D BluetoothHeadset: Proxy object disconnected
11-15 14:04:30.685   926   926 D BluetoothHeadset: Proxy object disconnected
11-15 14:04:30.685  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 14:04:30.687  3585  5414 V NativeCrypto: Read error: ssl=0x7f6dff1700: I/O error during system call, Connection timed out
11-15 14:04:30.687  4664  4664 D BluetoothMapService: onReceive
11-15 14:04:30.687  4664  4664 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-15 14:04:30.687  4664  4664 D BluetoothMapService: STATE_TURNING_OFF
11-15 14:04:30.689  3585  5414 V NativeCrypto: SSL shutdown failed: ssl=0x7f6dff1700: I/O error during system call, Broken pipe
,11-15 14:04:30.689  4664  4664 D A2dpService: Received stop request...Stopping profile...
,11-15 14:04:30.690  4664  4891 D A2dpStateMachine: Exit Disconnected: -1
,11-15 14:04:30.692   926   926 D BluetoothA2dp: Proxy object disconnected
11-15 14:04:30.692   926  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-15 14:04:30.692   926  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-15 14:04:30.692  4664  4664 V BluetoothAdapterState: isTurningOff()=true
11-15 14:04:30.692  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:30.693  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:30.693  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:30.694  3133  3133 D BluetoothA2dp: Proxy object disconnected
11-15 14:04:30.697   534   534 E Parcel  : Reading a NULL string not supported here.
,11-15 14:04:30.697  4664  4664 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-15 14:04:30.697  4664  4736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-15 14:04:30.698  4664  4664 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-15 14:04:30.698  4664  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:04:30.698  4664  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:04:30.698  4664  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:04:30.698   926   926 D RttService: SCAN_AVAILABLE : 1
11-15 14:04:30.698   926  3085 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-15 14:04:30.699  4664  4736 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-15 14:04:30.700  4664  4664 D HidService: Received stop request...Stopping profile...
11-15 14:04:30.700  4664  4664 D HidService: Stopping Bluetooth HidService
,11-15 14:04:30.702  4664  4664 D HealthService: Received stop request...Stopping profile...
,11-15 14:04:30.703   926  2978 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-15 14:04:30.704  4664  4664 D PanService: Received stop request...Stopping profile...
,11-15 14:04:30.705  4664  4664 D BluetoothMapService: Received stop request...Stopping profile...
,11-15 14:04:30.705  4664  4664 D BluetoothMapService: stop()
,11-15 14:04:30.706  4664  4664 D BluetoothMapAppObserver: deinitObservers()
,11-15 14:04:30.706  4664  4664 D BluetoothMapAppObserver: removeReceiver()
11-15 14:04:30.707   926  5364 D DhcpClient: Receive thread stopped
11-15 14:04:30.707  3767  3890 W QCNEJ   : |CORE| network lost: 100
11-15 14:04:30.708  3767  3890 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-15 14:04:30.710   926  2976 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-15 14:04:30.711  4664  4664 I BtOppRfcommListener: stopping Accept Thread
11-15 14:04:30.711  4664  5279 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-15 14:04:30.713  4664  5279 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-15 14:04:30.714  4664  4664 D SapService: Received stop request...Stopping profile...
11-15 14:04:30.714  4664  4664 V SapService: stop()
11-15 14:04:30.715  4664  4664 V BluetoothAdapterState: isTurningOff()=true
11-15 14:04:30.715  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:30.715  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:30.715  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 14:04:30.716  4664  4664 V BluetoothAdapterState: isTurningOff()=true
11-15 14:04:30.716  4664  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:04:30.716  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:30.716  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:30.716  4664  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:04:30.716  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:30.716  4664  4664 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-15 14:04:30.716  4664  4664 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-15 14:04:30.716  4664  4664 V BluetoothAdapterState: isTurningOff()=true
11-15 14:04:30.717  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:30.717  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 14:04:30.717  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:30.717  4664  4664 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-15 14:04:30.717  4664  4664 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-15 14:04:30.718  4664  4664 V BluetoothAdapterState: isTurningOff()=true
11-15 14:04:30.718  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:30.718  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:30.718  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:30.718  4664  4664 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-15 14:04:30.718  4664  4664 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-15 14:04:30.718  4664  4868 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 14:04:30.718  4664  4868 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 14:04:30.718  4664  4868 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 14:04:30.718  4664  4868 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 14:04:30.719  4664  4736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-15 14:04:30.719  4664  4736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-15 14:04:30.719  4664  4736 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-15 14:04:30.719  4664  4664 D BluetoothMapService: MAP Service closeService in
11-15 14:04:30.719  4664  4664 D BluetoothMapMasInstance0: MAP Service shutdown
11-15 14:04:30.719  4664  4664 D ObexServerSockets0: shutdown(block = true)
11-15 14:04:30.719  4664  4664 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 14:04:30.719  4664  4664 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 14:04:30.720  4664  4886 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-15 14:04:30.720  4664  4900 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-15 14:04:30.720  4664  4899 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-15 14:04:30.720  4664  4664 V BluetoothAdapterState: isTurningOff()=true
11-15 14:04:30.720  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:30.721  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:30.721  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:30.721   926  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 14:04:30.721  4664  4664 D BluetoothMapService: cleanup()
11-15 14:04:30.721  4664  4664 D BluetoothMapService: MAP Service closeService in
11-15 14:04:30.723  4664  4664 V BluetoothAdapterState: isTurningOff()=true
,11-15 14:04:30.723  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:30.723  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:30.723  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:30.724  3133  3133 D BluetoothInputDevice: Proxy object disconnected
11-15 14:04:30.724  3133  3133 D HidProfile: Bluetooth service disconnected
11-15 14:04:30.724  4664  4732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-15 14:04:30.724  4664  4732 D BluetoothAdapterProperties: Setting state to 15
11-15 14:04:30.724  4664  4732 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-15 14:04:30.724  3133  3133 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-15 14:04:30.724  3133  3133 D PanProfile: Bluetooth service disconnected
11-15 14:04:30.724   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:04:30.724  4664  4732 I BluetoothAdapterState: Entering BleOnState
11-15 14:04:30.725  3133  3145 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:04:30.725   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-15 14:04:30.725  3133  4019 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 14:04:30.725  3133  3133 D BluetoothMap: Proxy object disconnected
11-15 14:04:30.725  3133  3133 D MapProfile: Bluetooth service disconnected
11-15 14:04:30.725  3133  3150 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-15 14:04:30.726   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 14:04:30.726  3133  3145 D BluetoothPan: onBluetoothStateChange on: false
11-15 14:04:30.726   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:04:30.727  3812  4039 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:04:30.727  3133  3328 D BluetoothMap: onBluetoothStateChange: up=false
11-15 14:04:30.727  3133  4019 D BluetoothPbap: onBluetoothStateChange: up=false
11-15 14:04:30.730  4664  4732 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-15 14:04:30.731  4664  4732 D BluetoothAdapterProperties: Setting state to 16
11-15 14:04:30.731  4664  4732 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-15 14:04:30.731  4664  4732 D BluetoothAdapterProperties: onBleDisable
11-15 14:04:30.731  4664  4732 I BluetoothAdapterState: Entering PendingCommandState
11-15 14:04:30.731  4664  4733 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-15 14:04:30.732  4664  4736 D BluetoothAdapterProperties: Scan Mode:20
11-15 14:04:30.734  4664  4868 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-15 14:04:30.734  4664  4868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:04:30.734  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 14:04:30.734  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:04:30.734  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:04:30.734  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:04:30.734  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:04:30.734  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 14:04:30.734  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 14:04:30.734  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 14:04:30.734  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 14:04:30.734  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 14:04:30.735  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 14:04:30.736  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-15 14:04:30.737  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 14:04:30.743   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 14:04:30.758  5652  5652 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-15 14:04:30.762   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-15 14:04:30.763   508   920 D CommandListener: Clearing all IP addresses on wlan0
11-15 14:04:30.763   926  2978 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-15 14:04:30.764   926  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-15 14:04:30.764   508   920 D TetherController: Setting IP forward enable = 0
11-15 14:04:30.766   926  2976 D DhcpClient: doQuit
11-15 14:04:30.766   926   943 D Tethering: MasterInitialState.processMessage what=3
11-15 14:04:30.766   926  2976 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-15 14:04:30.766  5266  5266 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7c5721a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-15 14:04:30.767   926  5362 D DhcpClient: onQuitting
11-15 14:04:30.767  3454  3454 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-15 14:04:30.769  3979  3979 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-15 14:04:30.769  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:30.772  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 14:04:30.772  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:04:30.772  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:04:30.772  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:04:30.772  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 14:04:30.772  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 14:04:30.772  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 14:04:30.772  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 14:04:30.772  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 14:04:30.772  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 14:04:30.772  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 14:04:30.773  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 14:04:30.780  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 14:04:30.785   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4d0a44d:true
,11-15 14:04:30.788  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 14:04:30.802  3454  3454 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-15 14:04:30.804  5652  5652 D LocalBluetoothProfileManager: Adding local MAP profile
11-15 14:04:30.806  5652  5652 D BluetoothMap: Create BluetoothMap proxy object
,11-15 14:04:30.806  3454  3454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-15 14:04:30.808   508   913 W SocketClient: write error (Broken pipe)
11-15 14:04:30.808   508   913 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-15 14:04:30.808   508   913 W SocketListener: Error sending broadcast (Broken pipe)
,11-15 14:04:30.813  5652  5652 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-15 14:04:30.819   508   920 E Netd    : netlink response contains error (No such file or directory)
,11-15 14:04:30.820  5652  5652 D DockEventReceiver: finishStartingService: stopping service
11-15 14:04:30.820   508   920 D TetherController: Setting IP forward enable = 0
11-15 14:04:30.821   926  2978 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-15 14:04:30.823  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 14:04:30.828  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 14:04:30.828  5652  5652 D DockEventReceiver: finishStartingService: stopping service
,11-15 14:04:30.832   926  3580 I ActivityManager: Killing 5389:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-15 14:04:30.835  3454  3454 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-15 14:04:30.844  3454  3454 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-15 14:04:30.852  3994  3994 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-15 14:04:30.855  3994  3994 D SystemUpdateService: onCreate
,11-15 14:04:30.858  3994  3994 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-15 14:04:30.862  3994  5687 I SystemUpdateService: active receiver: enabled
,11-15 14:04:30.866  3994  3994 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-15 14:04:30.871  3994  4296 I iu.UploadsManager: num queued entries: 0
,11-15 14:04:30.871  3994  4296 I iu.UploadsManager: num updated entries: 0
11-15 14:04:30.871  3994  4296 I iu.SyncManager: NEXT; no task
,11-15 14:04:30.872  3994  5687 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 14:04:30.874  3994  3994 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-15 14:04:30.875  3994  3994 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-15 14:04:30.877  3994  5687 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-15 14:04:30.877  3994  5687 I SystemUpdateService: now status is 0 (complete)
11-15 14:04:30.877  3994  5687 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-15 14:04:30.877  3994  5687 I SystemUpdateService: file has been verified
11-15 14:04:30.877  3994  5687 I SystemUpdateService: OTA package size = 21989297
,11-15 14:04:30.882  3994  5687 I SystemUpdateService: showing system update notification
,11-15 14:04:30.887   926  3580 I ActivityManager: Start proc 5689:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-15 14:04:30.898   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 14:04:30.901  3994  3994 D SystemUpdateService: onDestroy
,11-15 14:04:30.918  5689  5689 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-15 14:04:30.921  5689  5689 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 14:04:30.928  5689  5689 D SprintDMHelper: simOperator: 
11-15 14:04:30.928  5689  5689 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 14:04:30.938  4664  4736 I bt_hci  : shut_down
,11-15 14:04:30.942  4664  4740 D bt_hwcfg: hw_epilog_process
11-15 14:04:30.942  4664  4740 I bt_vendor: low_power_mode_cb
,11-15 14:04:30.943   926  3786 I ActivityManager: Killing 5266:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-15 14:04:30.946  4664  4740 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-15 14:04:30.946  4664  4740 I bt_vendor: epilog_cb
11-15 14:04:30.946  4664  4740 I bt_hci  : epilog_finished_callback
,11-15 14:04:30.965   926  2976 D wifi    : In wifi stop Hal
,11-15 14:04:30.965   926  2976 D wifi    : halHandle = 0x7f5c451e00, mVM = 0x7f78acd140, mCls = 0x100a02
11-15 14:04:30.966   926  3452 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-15 14:04:30.966   926  3452 D WifiHAL : Got a signal to exit!!!
11-15 14:04:30.966   926  3452 I WifiHAL : Exit wifi_event_loop
11-15 14:04:30.966   926  2976 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-15 14:04:30.966   926  2976 E WifiHAL : Event processing terminated
11-15 14:04:30.967   926  2976 D wifi    : In wifi cleaned up handler
11-15 14:04:30.967   926  2976 I WifiHAL : Internal cleanup completed
11-15 14:04:30.967  4505  4505 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 14:04:30.968  3741  4217 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-15 14:04:30.968  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:30.969  4664  4736 I bt_hci_h4: hal_close
11-15 14:04:30.969  4664  4736 I bt_userial_vendor: device fd = 54 close
,11-15 14:04:30.980   926  3786 I ActivityManager: Start proc 5702:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-15 14:04:30.986   926  3452 D wifi    : set interface wlan0 flags (DOWN)
,11-15 14:04:30.987   926  2976 D WifiNative-HAL: HAL event thread stopped successfully
,11-15 14:04:31.016  5702  5702 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-15 14:04:31.023   926  3789 I ActivityManager: Killing 3902:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-15 14:04:31.079  4664  4733 D bt_stack_manager: event_shut_down_stack finished.
,11-15 14:04:31.080  4664  4732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-15 14:04:31.082  4664  4664 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-15 14:04:31.083  4664  4732 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-15 14:04:31.083  4664  4664 D BtGatt.GattService: Received stop request...Stopping profile...
,11-15 14:04:31.083  4664  4664 D BtGatt.GattService: stop()
11-15 14:04:31.083  4664  4664 D BtGatt.AdvertiseManager: advertise clients cleared
11-15 14:04:31.085  4664  4664 V BluetoothAdapterState: isTurningOff()=false
11-15 14:04:31.085  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:31.085  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 14:04:31.085  4664  4664 V BluetoothAdapterState: isBleTurningOff()=true
,11-15 14:04:31.085  4664  4732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-15 14:04:31.085  4664  4732 D BluetoothAdapterProperties: Setting state to 10
11-15 14:04:31.086  4664  4732 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-15 14:04:31.087  4664  4732 I BluetoothAdapterState: Entering OffState
11-15 14:04:31.088   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-15 14:04:31.093  4664  4664 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-15 14:04:31.093  4664  4664 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-15 14:04:31.093  4664  4664 I BluetoothServiceJni: cleanupNative: return from cleanup
11-15 14:04:31.094  4664  4733 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-15 14:04:31.097  4664  4664 I art     : System.exit called, status: 0
,11-15 14:04:31.098  4664  4664 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-15 14:04:31.119   926  3580 I ActivityManager: Process com.android.bluetooth (pid 4664) has died
,11-15 14:04:31.191   926   943 D Tethering: InitialState.processMessage what=4
,11-15 14:04:31.197   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-15 14:04:31.214   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:32.214   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-15 14:04:35.665   926  3778 D WifiService: setWifiEnabled: true pid=5586, uid=10077
,11-15 14:04:35.666   926  3778 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 14:04:35.676   508   920 D SoftapController: Softap fwReload - Ok
,11-15 14:04:35.681   508   920 D CommandListener: Setting iface cfg
,11-15 14:04:35.681   508   920 D CommandListener: Trying to bring down wlan0
,11-15 14:04:35.685   508   920 D CommandListener: Clearing all IP addresses on wlan0
,11-15 14:04:35.691   926  2976 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-15 14:04:36.280   926  2976 D wifi    : set interface wlan0 flags (UP)
,11-15 14:04:36.283   926  2976 I WifiHAL : Initializing wifi
11-15 14:04:36.283   926  2976 I WifiHAL : Creating socket
,11-15 14:04:36.289   926  2976 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-15 14:04:36.290   926  2976 D wifi    : Did set static halHandle = 0x7f5c451e00
,11-15 14:04:36.290   926  2976 D wifi    : halHandle = 0x7f5c451e00, mVM = 0x7f78acd140, mCls = 0x20198a
,11-15 14:04:36.290   926  2976 D wifi    : array field set
11-15 14:04:36.291   926  2976 I WifiNative-HAL: interface[0] = wlan0
11-15 14:04:36.294   926  5718 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547008880128
11-15 14:04:36.294   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-15 14:04:36.295   926  5718 D wifi    : waitForHalEvents called, vm = 0x7f78acd140, obj = 0x20198a, env = 0x7f5c457700
11-15 14:04:36.298   926  2976 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-15 14:04:36.299   926  2976 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-15 14:04:36.302  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 14:04:36.365  5719  5719 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-15 14:04:36.431  5719  5719 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 14:04:36.502  5719  5719 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-15 14:04:36.502  5719  5719 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-15 14:04:37.215   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:37.316  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 14:04:37.317  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:04:37.317  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:04:37.317  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:04:37.317  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:04:37.317  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 14:04:37.317  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 14:04:37.317  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 14:04:37.317  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 14:04:37.317  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 14:04:37.317  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 14:04:37.317  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 14:04:37.322   926  2976 D WifiConfigStore: Loading config and enabling all networks 
,11-15 14:04:37.361   926  2976 D WifiConfigStore: loaded 0 passpoint configs
,11-15 14:04:37.362   926  2976 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-15 14:04:37.363   926  2976 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-15 14:04:37.364   926  2976 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-15 14:04:37.364   926  2976 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-15 14:04:37.365   926  2976 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-15 14:04:37.366   926  2976 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-15 14:04:37.366   926  2976 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-15 14:04:37.366   926  2976 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-15 14:04:37.366   926  2976 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-15 14:04:37.367   926  2976 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-15 14:04:37.367   926  2976 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-15 14:04:37.367   926  2976 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-15 14:04:37.370   926  2976 D WifiNative-HAL: Setting external_sim to 1
,11-15 14:04:37.371  4505  4505 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 14:04:37.371   926  2976 D wifi    : setting dfs flag to true, 0x7f5a725320
11-15 14:04:37.372   926  2976 D WifiStateMachine: Setting OUI to DA-A1-19
,11-15 14:04:37.372   926  2976 D wifi    : setting scan oui 0x7f5a725320
11-15 14:04:37.372   926  2976 D WifiHAL : Sending mac address OUI
,11-15 14:04:37.377   926  2976 E native  : do suspend false
,11-15 14:04:37.389   926  2976 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-15 14:04:37.389   508   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-15 14:04:37.389   926   926 D RttService: SCAN_AVAILABLE : 3
11-15 14:04:37.390   926  3085 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-15 14:04:37.391   508   920 D CommandListener: Setting iface cfg
,11-15 14:04:37.396   926  2961 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '123 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 123 Failed to set address (No such device)'
,11-15 14:04:37.397   926  2961 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-15 14:04:37.410   926  2961 D WifiNative-HAL: p2pGetDeviceAddress
,11-15 14:04:37.410   926  2961 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-15 14:04:37.417   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128833 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=21 mControllerEnergyUsed=79 }
,11-15 14:04:38.217   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:39.218   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:40.220   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:40.467  5719  5719 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 14:04:40.472  5719  5719 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 14:04:40.476  5719  5719 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 14:04:40.481  5719  5719 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 14:04:40.673   926  3787 D WifiService: setWifiEnabled: false pid=5586, uid=10077
11-15 14:04:40.673   926  3787 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 14:04:40.680   926   926 D RttService: SCAN_AVAILABLE : 1
,11-15 14:04:40.681   926  3085 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-15 14:04:40.699   926  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-15 14:04:40.700   508   920 D CommandListener: Clearing all IP addresses on wlan0
,11-15 14:04:40.710   926  2976 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-15 14:04:40.712  5719  5719 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-15 14:04:40.718  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 14:04:40.718  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:04:40.718  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:04:40.718  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:04:40.718  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 14:04:40.718  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 14:04:40.718  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 14:04:40.718  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 14:04:40.718  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 14:04:40.718  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 14:04:40.719  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 14:04:40.719  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 14:04:40.731  5719  5719 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-15 14:04:40.745  5719  5719 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-15 14:04:40.755  5719  5719 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-15 14:04:40.858   926  2976 D wifi    : In wifi stop Hal
11-15 14:04:40.858   926  2976 D wifi    : halHandle = 0x7f5c451e00, mVM = 0x7f78acd140, mCls = 0x20198a
,11-15 14:04:40.859   926  5718 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-15 14:04:40.859   926  5718 D WifiHAL : Got a signal to exit!!!
11-15 14:04:40.859   926  5718 I WifiHAL : Exit wifi_event_loop
,11-15 14:04:40.866  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:40.860   926  2976 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-15 14:04:40.867   926  2976 E WifiHAL : Event processing terminated
11-15 14:04:40.868  3741  4217 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-15 14:04:40.868   926  2976 D wifi    : In wifi cleaned up handler
11-15 14:04:40.868   926  2976 I WifiHAL : Internal cleanup completed
11-15 14:04:40.868  4505  4505 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 14:04:40.899   926  5718 D wifi    : set interface wlan0 flags (DOWN)
,11-15 14:04:40.899   926  2976 D WifiNative-HAL: HAL event thread stopped successfully
,11-15 14:04:41.106   926   943 D Tethering: InitialState.processMessage what=4
,11-15 14:04:41.113   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-15 14:04:41.221   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:42.222   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-15 14:04:45.715   926   943 I ActivityManager: Start proc 5723:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-15 14:04:45.815  5723  5723 D AdapterServiceConfig: Adding HeadsetService
,11-15 14:04:45.815  5723  5723 D AdapterServiceConfig: Adding A2dpService
11-15 14:04:45.815  5723  5723 D AdapterServiceConfig: Adding HidService
11-15 14:04:45.816  5723  5723 D AdapterServiceConfig: Adding HealthService
11-15 14:04:45.816  5723  5723 D AdapterServiceConfig: Adding PanService
11-15 14:04:45.816  5723  5723 D AdapterServiceConfig: Adding GattService
,11-15 14:04:45.816  5723  5723 D AdapterServiceConfig: Adding BluetoothMapService
11-15 14:04:45.816  5723  5723 D AdapterServiceConfig: Adding SapService
,11-15 14:04:45.826   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a2c4b0:true
,11-15 14:04:45.826  5723  5723 D BluetoothAdapterState: make() - Creating AdapterState
,11-15 14:04:45.829  5723  5723 I bt_bluedroid: init
11-15 14:04:45.829  5723  5735 I BluetoothAdapterState: Entering OffState
,11-15 14:04:45.831  5723  5736 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-15 14:04:45.831  5723  5736 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-15 14:04:45.831  5723  5736 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-15 14:04:45.831  5723  5736 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-15 14:04:45.832  5723  5723 I bt_bluedroid: get_profile_interface socket
,11-15 14:04:45.833  5723  5739 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-15 14:04:45.834  5723  5723 I bt_bluedroid: get_profile_interface sdp
,11-15 14:04:45.835  5723  5739 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 14:04:45.838  5723  5734 I bt_bluedroid: config_hci_snoop_log
,11-15 14:04:45.839   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-15 14:04:45.843  5723  5735 D BluetoothAdapterState: Current state: OFF, message: 0
,11-15 14:04:45.843  5723  5735 D BluetoothAdapterProperties: Setting state to 14
11-15 14:04:45.843  5723  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-15 14:04:45.845  5723  5735 D BluetoothBondStateMachine: make
,11-15 14:04:45.846  5723  5740 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-15 14:04:45.849  5723  5735 I BluetoothAdapterState: Entering PendingCommandState
,11-15 14:04:45.850  5723  5723 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-15 14:04:45.853  5723  5723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
11-15 14:04:45.853  5723  5723 D BtGatt.DebugUtils: handleDebugAction() action=null
11-15 14:04:45.854  5723  5723 D BtGatt.GattService: Received start request. Starting profile...
11-15 14:04:45.854  5723  5723 D BtGatt.GattService: start()
11-15 14:04:45.854  5723  5723 I bt_bluedroid: get_profile_interface gatt
11-15 14:04:45.855  5723  5723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
11-15 14:04:45.855  5723  5723 D BtGatt.AdvertiseManager: advertise manager created
,11-15 14:04:45.859  5723  5723 V BluetoothAdapterState: isTurningOff()=false
,11-15 14:04:45.859  5723  5723 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:45.859  5723  5723 V BluetoothAdapterState: isBleTurningOn()=true
11-15 14:04:45.859  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:45.859  5723  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-15 14:04:45.861  5723  5735 I bt_bluedroid: bt_bluedroid
,11-15 14:04:45.861  5723  5736 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-15 14:04:45.861  5723  5736 I bt_hci  : start_up
,11-15 14:04:45.866  5723  5736 I bt_vendor: alloc value 0xf3bb9871
11-15 14:04:45.866  5723  5736 I bt_vendor: init
11-15 14:04:45.866  5723  5736 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-15 14:04:45.866  5723  5736 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-15 14:04:45.976  5723  5736 D bt_hci  : start_up starting async portion
,11-15 14:04:45.976  5723  5743 I bt_hci  : event_finish_startup
11-15 14:04:45.977  5723  5743 I bt_hci_h4: hal_open
11-15 14:04:45.977  5723  5743 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-15 14:04:45.979  5723  5743 I bt_userial_vendor: device fd = 54 open
,11-15 14:04:45.975  5744  5744 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 14:04:45.992  5723  5743 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 14:04:45.994  5723  5743 D bt_hwcfg: Chipset BCM4358A3
,11-15 14:04:45.994  5723  5743 D bt_hwcfg: Target name = [BCM4358A3]
11-15 14:04:45.994  5723  5743 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-15 14:04:46.375  5723  5743 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-15 14:04:46.375  5723  5743 D bt_hwcfg: Settlement delay -- 100 ms
11-15 14:04:46.375  5723  5743 I bt_hwcfg: Setting fw settlement delay to 100 
,11-15 14:04:46.509  5723  5743 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 14:04:46.509  5723  5743 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-15 14:04:46.510  5723  5743 I bt_hwcfg: vendor lib fwcfg completed
,11-15 14:04:46.511  5723  5743 I bt_vendor: firmware callback
,11-15 14:04:46.511  5723  5743 I bt_hci  : firmware_config_callback
,11-15 14:04:46.521  5723  5746 I bt_btu  : btu_task pending for preload complete event
,11-15 14:04:46.521  5723  5746 I bt_btu_task: Bluetooth chip preload is complete
11-15 14:04:46.521  5723  5746 I bt_btu  : btu_task received preload complete event
,11-15 14:04:46.526  5723  5746 I         : BTE_InitTraceLevels -- TRC_HCI
,11-15 14:04:46.526  5723  5746 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-15 14:04:46.526  5723  5746 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-15 14:04:46.527  5723  5746 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-15 14:04:46.527  5723  5746 I         : BTE_InitTraceLevels -- TRC_AVRC
11-15 14:04:46.527  5723  5746 I         : BTE_InitTraceLevels -- TRC_A2D
,11-15 14:04:46.527  5723  5746 I         : BTE_InitTraceLevels -- TRC_BNEP
11-15 14:04:46.527  5723  5746 I         : BTE_InitTraceLevels -- TRC_BTM
11-15 14:04:46.527  5723  5746 I         : BTE_InitTraceLevels -- TRC_GAP
,11-15 14:04:46.527  5723  5746 I         : BTE_InitTraceLevels -- TRC_PAN
11-15 14:04:46.528  5723  5746 I         : BTE_InitTraceLevels -- TRC_SDP
,11-15 14:04:46.528  5723  5746 I         : BTE_InitTraceLevels -- TRC_GATT
11-15 14:04:46.528  5723  5746 I         : BTE_InitTraceLevels -- TRC_SMP
11-15 14:04:46.528  5723  5746 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-15 14:04:46.528  5723  5746 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-15 14:04:46.611  5723  5746 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b37549
11-15 14:04:46.611  5723  5746 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b37549 
,11-15 14:04:46.626  5723  5739 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-15 14:04:46.628  5723  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-15 14:04:46.629  5723  5739 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-15 14:04:46.631  5723  5739 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 14:04:46.634  5723  5739 D BluetoothAdapterProperties: Scan Mode:20
,11-15 14:04:46.635  5723  5739 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 14:04:46.635  5723  5739 D bt_hci  : do_postload posting postload work item
11-15 14:04:46.635  5723  5743 I bt_hci  : event_postload
11-15 14:04:46.635  5723  5743 I bt_vendor: sco_config_cb
11-15 14:04:46.636  5723  5743 I bt_hci  : sco_config_callback postload finished.
,11-15 14:04:46.639  5723  5739 D bt_bte_conf: Device ID record 1 : primary
11-15 14:04:46.639  5723  5739 D bt_bte_conf:   vendorId            = 000f
,11-15 14:04:46.639  5723  5739 D bt_bte_conf:   vendorIdSource      = 0001
11-15 14:04:46.639  5723  5739 D bt_bte_conf:   product             = 1200
11-15 14:04:46.639  5723  5739 D bt_bte_conf:   version             = 1436
11-15 14:04:46.639  5723  5739 D bt_bte_conf:   clientExecutableURL = 
,11-15 14:04:46.640  5723  5739 D bt_bte_conf:   serviceDescription  = 
11-15 14:04:46.640  5723  5739 D bt_bte_conf:   documentationURL    = 
,11-15 14:04:46.640  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:46.640  5723  5739 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-15 14:04:46.641  5723  5736 D bt_stack_manager: event_start_up_stack finished
11-15 14:04:46.642  5723  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-15 14:04:46.642  5723  5735 D BluetoothAdapterProperties: Setting state to 15
,11-15 14:04:46.642  5723  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-15 14:04:46.644  5723  5735 I BluetoothAdapterState: Entering BleOnState
,11-15 14:04:46.648  5723  5743 I bt_vendor: low_power_mode_cb
11-15 14:04:46.649  5723  5735 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-15 14:04:46.649  5723  5735 D BluetoothAdapterProperties: Setting state to 11
11-15 14:04:46.649  5723  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-15 14:04:46.660  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 14:04:46.660  5723  5723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
,11-15 14:04:46.661  5723  5723 D HeadsetService: Received start request. Starting profile...
11-15 14:04:46.665  5723  5723 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-15 14:04:46.666  5723  5723 D HeadsetStateMachine: make
,11-15 14:04:46.676  5723  5735 I BluetoothAdapterState: Entering PendingCommandState
,11-15 14:04:46.677  5723  5723 D HeadsetStateMachine: max_hf_connections = 1
,11-15 14:04:46.677  5723  5723 I bt_bluedroid: get_profile_interface handsfree
,11-15 14:04:46.677  5723  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-15 14:04:46.680  5723  5739 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-15 14:04:46.683  5723  5723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
,11-15 14:04:46.684  5723  5723 D A2dpService: Received start request. Starting profile...
11-15 14:04:46.685  5723  5723 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-15 14:04:46.685  5723  5723 I bt_bluedroid: get_profile_interface avrcp
,11-15 14:04:46.686  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 14:04:46.693  5723  5723 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-15 14:04:46.693  5723  5723 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-15 14:04:46.693  5723  5723 D A2dpStateMachine: make
,11-15 14:04:46.694  5723  5723 I bt_bluedroid: get_profile_interface a2dp
,11-15 14:04:46.695  5723  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-15 14:04:46.696  5723  5753 D A2dpStateMachine: Enter Disconnected: -2
,11-15 14:04:46.697  5723  5723 I BluetoothHidServiceJni: classInitNative: succeeds
,11-15 14:04:46.698  5723  5723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
,11-15 14:04:46.699  5652  5652 D BluetoothInputDevice: Proxy object connected
11-15 14:04:46.699  5723  5723 D HidService: Received start request. Starting profile...
,11-15 14:04:46.699  5723  5723 I bt_bluedroid: get_profile_interface hidhost
11-15 14:04:46.699  5723  5739 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b1856d
11-15 14:04:46.699  5723  5723 D HidService: setHidService(): set to: null
11-15 14:04:46.699  5723  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-15 14:04:46.699  5652  5652 D HidProfile: Bluetooth service connected
11-15 14:04:46.700  5723  5723 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-15 14:04:46.701  5723  5723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
11-15 14:04:46.701  5723  5723 D HealthService: Received start request. Starting profile...
,11-15 14:04:46.703  5723  5723 I bt_bluedroid: get_profile_interface health
,11-15 14:04:46.703  5723  5723 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-15 14:04:46.704  5723  5723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
,11-15 14:04:46.705  5723  5723 D PanService: Received start request. Starting profile...
11-15 14:04:46.705  5652  5652 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 14:04:46.705  5723  5723 D BluetoothPanServiceJni: initializeNative(L110): pan
11-15 14:04:46.706  5723  5723 I bt_bluedroid: get_profile_interface pan
,11-15 14:04:46.706  5652  5652 D PanProfile: Bluetooth service connected
11-15 14:04:46.706  5723  5739 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-15 14:04:46.709  5723  5723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
,11-15 14:04:46.711  5723  5723 D BluetoothMapService: Received start request. Starting profile...
,11-15 14:04:46.711  5723  5723 D BluetoothMapService: start()
11-15 14:04:46.713  5652  5652 D BluetoothMap: Proxy object connected
,11-15 14:04:46.714  5723  5723 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-15 14:04:46.715  5723  5723 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-15 14:04:46.715  5723  5723 D BluetoothMapAppObserver: createReceiver()
11-15 14:04:46.716  5723  5723 D BluetoothMapAppObserver: initObservers()
11-15 14:04:46.716  5723  5723 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-15 14:04:46.723  5723  5723 V SapService: SapBinder()
,11-15 14:04:46.723  5723  5723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
,11-15 14:04:46.724  5652  5652 D MapProfile: Bluetooth service connected
,11-15 14:04:46.724  5652  5652 D BluetoothMap: getConnectedDevices()
11-15 14:04:46.725  5723  5723 D SapService: Received start request. Starting profile...
11-15 14:04:46.725  5723  5723 V SapService: start()
11-15 14:04:46.727  5723  5723 V BluetoothAdapterState: isTurningOff()=false
11-15 14:04:46.727  5723  5723 V BluetoothAdapterState: isTurningOn()=true
11-15 14:04:46.727  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:46.727  5723  5751 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-15 14:04:46.727  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 14:04:46.727  5723  5723 V BluetoothAdapterState: isTurningOff()=false
11-15 14:04:46.727  5723  5723 V BluetoothAdapterState: isTurningOn()=true
11-15 14:04:46.728  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 14:04:46.728  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:46.728  5723  5723 V BluetoothAdapterState: isTurningOff()=false
11-15 14:04:46.728  5723  5723 V BluetoothAdapterState: isTurningOn()=true
11-15 14:04:46.728  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:46.728  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:46.728  5723  5723 V BluetoothAdapterState: isTurningOff()=false
11-15 14:04:46.728  5723  5723 V BluetoothAdapterState: isTurningOn()=true
11-15 14:04:46.729  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 14:04:46.729  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:46.729  5723  5723 V BluetoothAdapterState: isTurningOff()=false
11-15 14:04:46.729  5723  5723 V BluetoothAdapterState: isTurningOn()=true
11-15 14:04:46.729  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 14:04:46.729  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 14:04:46.729  5723  5723 V BluetoothAdapterState: isTurningOff()=false
,11-15 14:04:46.729  5723  5723 V BluetoothAdapterState: isTurningOn()=true
11-15 14:04:46.729  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:46.729  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:46.730  5723  5723 V BluetoothAdapterState: isTurningOff()=false
,11-15 14:04:46.730  5723  5723 V BluetoothAdapterState: isTurningOn()=true
,11-15 14:04:46.730  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 14:04:46.730  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:46.730  5723  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-15 14:04:46.730  5723  5735 D BluetoothAdapterProperties: ScanMode =  20
11-15 14:04:46.730  5723  5735 D BluetoothAdapterProperties: State =  11
11-15 14:04:46.732  5652  5652 D BluetoothMap: Bluetooth is Not enabled
11-15 14:04:46.733  5723  5739 D BluetoothAdapterProperties: Scan Mode:21
11-15 14:04:46.733  5723  5739 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 14:04:46.733  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-15 14:04:46.733  5723  5735 D BluetoothAdapterProperties: Setting state to 12
,11-15 14:04:46.733  5723  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-15 14:04:46.734   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:04:46.734  5723  5735 I BluetoothAdapterState: Entering OnState
11-15 14:04:46.734  5652  5662 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 14:04:46.736  3133  3328 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:04:46.736  5652  5668 D BluetoothPan: onBluetoothStateChange on: true
,11-15 14:04:46.737   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:04:46.737  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:04:46.737  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:04:46.737  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:04:46.737  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 14:04:46.737  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:04:46.737  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 14:04:46.737  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 14:04:46.737  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 14:04:46.737  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 14:04:46.737  3133  3145 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-15 14:04:46.739  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-15 14:04:46.741  3133  4019 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-15 14:04:46.742  5723  5723 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 14:04:46.742  5723  5723 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-15 14:04:46.742   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 14:04:46.742  3133  3133 D BluetoothInputDevice: Proxy object connected
11-15 14:04:46.742  3133  3133 D HidProfile: Bluetooth service connected
11-15 14:04:46.743  5652  5662 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-15 14:04:46.743  3133  3328 D BluetoothPan: onBluetoothStateChange on: true
11-15 14:04:46.744  5723  5723 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 14:04:46.745  3133  3133 D BluetoothPan: BluetoothPAN Proxy object connected
,11-15 14:04:46.745  3133  3133 D PanProfile: Bluetooth service connected
11-15 14:04:46.745   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:04:46.746  3812  4039 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:04:46.746  5723  5723 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 14:04:46.746  5652  5668 D BluetoothMap: onBluetoothStateChange: up=true
,11-15 14:04:46.747  3133  4019 D BluetoothMap: onBluetoothStateChange: up=true
11-15 14:04:46.747  5723  5723 D ObexServerSockets: Succeed to create listening sockets 
11-15 14:04:46.747  5723  5723 D ObexServerSockets0: startAccept()
11-15 14:04:46.747  5723  5723 D ObexServerSockets0: prepareForNewConnect()
11-15 14:04:46.748  3133  3133 D BluetoothMap: Proxy object connected
11-15 14:04:46.748  3133  3150 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 14:04:46.748  3133  3133 D MapProfile: Bluetooth service connected
11-15 14:04:46.748  3133  3133 D BluetoothMap: getConnectedDevices()
11-15 14:04:46.749  5723  5723 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-15 14:04:46.750  5723  5723 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-15 14:04:46.750  5723  5759 D ObexServerSockets0: Accepting socket connection...
11-15 14:04:46.750  5723  5760 D ObexServerSockets0: Accepting socket connection...
,11-15 14:04:46.751   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
11-15 14:04:46.751  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-15 14:04:46.753  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:46.753   926   926 D BluetoothA2dp: Proxy object connected
11-15 14:04:46.753  3133  3133 D BluetoothA2dp: Proxy object connected
11-15 14:04:46.753  5723  5723 D BluetoothMapService: onReceive
11-15 14:04:46.753  5723  5723 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 14:04:46.753  5723  5723 D BluetoothMapService: STATE_ON
,11-15 14:04:46.756  5652  5652 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-15 14:04:46.757  5723  5762 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:04:46.758  5723  5762 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-15 14:04:46.758  5723  5762 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-15 14:04:46.761  5652  5652 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-15 14:04:46.767  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 14:04:46.769  5652  5652 D BluetoothA2dp: Proxy object connected
,11-15 14:04:46.772  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 14:04:46.779  5723  5723 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-15 14:04:46.779  5723  5723 D ObexServerSockets0: prepareForNewConnect()
,11-15 14:04:46.782  5652  5652 D DockEventReceiver: finishStartingService: stopping service
,11-15 14:04:46.782  5652  5652 D BluetoothPbap: Proxy object connected
11-15 14:04:46.783  5652  5652 D PbapServerProfile: Bluetooth service connected
,11-15 14:04:46.787  3133  3133 D BluetoothPbap: Proxy object connected
,11-15 14:04:46.787  3133  3133 D PbapServerProfile: Bluetooth service connected
,11-15 14:04:46.788  5723  5767 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 14:04:46.802  5723  5771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 14:04:46.803  5723  5771 I BtOppRfcommListener: Accept thread started.
,11-15 14:04:46.835   926   926 D BluetoothHeadset: Proxy object connected
,11-15 14:04:46.835  3812  3841 D BluetoothHeadset: Proxy object connected
11-15 14:04:46.836  3133  3145 D BluetoothHeadset: Proxy object connected
11-15 14:04:46.836  3133  3133 D HeadsetProfile: Bluetooth service connected
,11-15 14:04:46.836   926   926 D BluetoothHeadset: Proxy object connected
11-15 14:04:46.836   926   926 D BluetoothHeadset: Proxy object connected
11-15 14:04:46.837  3133  3150 D BluetoothHeadset: Proxy object connected
11-15 14:04:46.837   926   943 D BluetoothHeadset: Proxy object connected
11-15 14:04:46.838  3133  3133 D HeadsetProfile: Bluetooth service connected
,11-15 14:04:46.845   926   943 D BluetoothHeadset: Proxy object connected
,11-15 14:04:46.846  3812  3839 D BluetoothHeadset: Proxy object connected
,11-15 14:04:46.863  5652  5668 D BluetoothHeadset: Proxy object connected
,11-15 14:04:46.864  5652  5652 D HeadsetProfile: Bluetooth service connected
,11-15 14:04:47.885  3661  3873 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-15 14:04:47.886  3661  3873 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-15 14:04:47.917  3585  3585 I ConfigService: onCreate
,11-15 14:04:50.693  5723  5735 D BluetoothAdapterState: Current state: ON, message: 23
,11-15 14:04:50.693  5723  5735 D BluetoothAdapterProperties: Setting state to 13
,11-15 14:04:50.693  5723  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
,11-15 14:04:50.694  5723  5735 D BluetoothAdapterProperties: onBluetoothDisable()
11-15 14:04:50.696  5723  5735 I BluetoothAdapterState: Entering PendingCommandState
11-15 14:04:50.701  5723  5723 D BluetoothMapService: onReceive
,11-15 14:04:50.702  5723  5723 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 14:04:50.702  5723  5723 D BluetoothMapService: STATE_TURNING_OFF
11-15 14:04:50.703  5723  5723 D BluetoothMapService: MAP Service closeService in
11-15 14:04:50.703  5723  5723 D BluetoothMapMasInstance0: MAP Service shutdown
11-15 14:04:50.703  5723  5723 D ObexServerSockets0: shutdown(block = true)
11-15 14:04:50.704  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 14:04:50.704  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:04:50.704  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:04:50.704  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:04:50.704  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 14:04:50.704  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 14:04:50.704  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 14:04:50.704  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 14:04:50.704  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 14:04:50.704  5586  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 14:04:50.705  5723  5759 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-15 14:04:50.705  5723  5723 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 14:04:50.709  5723  5739 D BluetoothAdapterProperties: Scan Mode:20
11-15 14:04:50.710  5723  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-15 14:04:50.710  5586  5586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 14:04:50.710  5586  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-15 14:04:50.711  5723  5760 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-15 14:04:50.712  5723  5723 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 14:04:50.712  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 14:04:50.712  5723  5723 I BtOppRfcommListener: stopping Accept Thread
11-15 14:04:50.713  5723  5771 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-15 14:04:50.713  5723  5771 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-15 14:04:50.714  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:50.715  5723  5748 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-15 14:04:50.721  5723  5723 D HeadsetService: Received stop request...Stopping profile...
11-15 14:04:50.722  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 14:04:50.723  5652  5652 D DockEventReceiver: finishStartingService: stopping service
,11-15 14:04:50.727   926   926 D BluetoothHeadset: Proxy object disconnected
11-15 14:04:50.728  3812  4039 D BluetoothHeadset: Proxy object disconnected
11-15 14:04:50.728  3133  3150 D BluetoothHeadset: Proxy object disconnected
,11-15 14:04:50.728  3133  3133 D HeadsetProfile: Bluetooth service disconnected
11-15 14:04:50.729  5652  5668 D BluetoothHeadset: Proxy object disconnected
11-15 14:04:50.729  5723  5723 D A2dpService: Received stop request...Stopping profile...
11-15 14:04:50.729   926   926 D BluetoothHeadset: Proxy object disconnected
,11-15 14:04:50.729   926   926 D BluetoothHeadset: Proxy object disconnected
11-15 14:04:50.729  5723  5753 D A2dpStateMachine: Exit Disconnected: -1
,11-15 14:04:50.732  5652  5652 D HeadsetProfile: Bluetooth service disconnected
11-15 14:04:50.732  3133  3133 D BluetoothA2dp: Proxy object disconnected
11-15 14:04:50.733  5652  5652 D BluetoothA2dp: Proxy object disconnected
,11-15 14:04:50.733   926   926 D BluetoothA2dp: Proxy object disconnected
,11-15 14:04:50.734  3133  3133 D BluetoothPbap: Proxy object disconnected
11-15 14:04:50.734  3133  3133 D PbapServerProfile: Bluetooth service disconnected
11-15 14:04:50.734  5652  5652 D BluetoothPbap: Proxy object disconnected
11-15 14:04:50.734  5723  5723 D HidService: Received stop request...Stopping profile...
11-15 14:04:50.735  5652  5652 D PbapServerProfile: Bluetooth service disconnected
11-15 14:04:50.735  5723  5723 D HidService: Stopping Bluetooth HidService
11-15 14:04:50.735  3133  3133 D BluetoothInputDevice: Proxy object disconnected
,11-15 14:04:50.735  5652  5652 D BluetoothInputDevice: Proxy object disconnected
11-15 14:04:50.735  3133  3133 D HidProfile: Bluetooth service disconnected
11-15 14:04:50.735  5652  5652 D HidProfile: Bluetooth service disconnected
11-15 14:04:50.736  5723  5723 D HealthService: Received stop request...Stopping profile...
,11-15 14:04:50.738  5723  5723 V BluetoothAdapterState: isTurningOff()=true
,11-15 14:04:50.738  5723  5723 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:50.738  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:50.738  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:50.739  5723  5723 D PanService: Received stop request...Stopping profile...
11-15 14:04:50.739  3133  3133 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-15 14:04:50.739  3133  3133 D PanProfile: Bluetooth service disconnected
11-15 14:04:50.739  5652  5652 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-15 14:04:50.739  5652  5652 D PanProfile: Bluetooth service disconnected
11-15 14:04:50.740  5723  5723 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-15 14:04:50.741  5723  5723 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-15 14:04:50.741  5723  5746 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:04:50.741  5723  5746 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:04:50.741  5723  5746 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:04:50.741  5723  5723 D BluetoothMapService: Received stop request...Stopping profile...
11-15 14:04:50.741  5723  5723 D BluetoothMapService: stop()
11-15 14:04:50.742  5723  5723 D BluetoothMapAppObserver: deinitObservers()
11-15 14:04:50.742  5723  5723 D BluetoothMapAppObserver: removeReceiver()
,11-15 14:04:50.742  5723  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-15 14:04:50.743  5652  5652 D BluetoothMap: Proxy object disconnected
11-15 14:04:50.743  5652  5652 D MapProfile: Bluetooth service disconnected
11-15 14:04:50.743  5723  5739 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-15 14:04:50.743  5723  5723 V BluetoothAdapterState: isTurningOff()=true
11-15 14:04:50.743  5723  5723 V BluetoothAdapterState: isTurningOn()=false
,11-15 14:04:50.743  3133  3133 D BluetoothMap: Proxy object disconnected
11-15 14:04:50.743  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:50.743  3133  3133 D MapProfile: Bluetooth service disconnected
11-15 14:04:50.743  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:50.743  5723  5723 D SapService: Received stop request...Stopping profile...
11-15 14:04:50.743  5723  5723 V SapService: stop()
11-15 14:04:50.745  5723  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-15 14:04:50.745  5723  5746 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:04:50.745  5723  5723 V BluetoothAdapterState: isTurningOff()=true
11-15 14:04:50.745  5723  5746 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:04:50.746  5723  5723 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:50.746  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:50.746  5723  5746 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 14:04:50.746  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:50.746  5723  5746 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 14:04:50.746  5723  5746 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 14:04:50.746  5723  5746 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 14:04:50.746  5723  5723 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-15 14:04:50.746  5723  5723 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-15 14:04:50.746  5723  5723 V BluetoothAdapterState: isTurningOff()=true
11-15 14:04:50.746  5723  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-15 14:04:50.746  5723  5723 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:50.746  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:50.746  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:50.746  5723  5723 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-15 14:04:50.746  5723  5739 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-15 14:04:50.747  5723  5723 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-15 14:04:50.747  5723  5723 V BluetoothAdapterState: isTurningOff()=true
11-15 14:04:50.747  5723  5723 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:50.747  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:50.747  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:50.748  5723  5723 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-15 14:04:50.748  5723  5723 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-15 14:04:50.753  5723  5723 D BluetoothMapService: MAP Service closeService in
11-15 14:04:50.753  5723  5723 V BluetoothAdapterState: isTurningOff()=true
11-15 14:04:50.754  5723  5723 V BluetoothAdapterState: isTurningOn()=false
,11-15 14:04:50.754  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:50.754  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 14:04:50.754  5723  5723 D BluetoothMapService: cleanup()
11-15 14:04:50.754  5723  5723 D BluetoothMapService: MAP Service closeService in
11-15 14:04:50.754  5723  5723 V BluetoothAdapterState: isTurningOff()=true
11-15 14:04:50.754  5723  5723 V BluetoothAdapterState: isTurningOn()=false
11-15 14:04:50.754  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:50.754  5723  5723 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:04:50.755  5723  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-15 14:04:50.755  5723  5735 D BluetoothAdapterProperties: Setting state to 15
,11-15 14:04:50.755  5723  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-15 14:04:50.755  5723  5735 I BluetoothAdapterState: Entering BleOnState
,11-15 14:04:50.756  5652  5662 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:04:50.756   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:04:50.756  5652  5668 D BluetoothPbap: onBluetoothStateChange: up=false
,11-15 14:04:50.757  3133  3150 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:04:50.758  5652  5662 D BluetoothPan: onBluetoothStateChange on: false
11-15 14:04:50.758   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-15 14:04:50.758  3133  4019 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 14:04:50.759  5652  5668 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 14:04:50.759  3133  3328 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-15 14:04:50.760   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 14:04:50.760  5652  5662 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-15 14:04:50.761  3133  3145 D BluetoothPan: onBluetoothStateChange on: false
11-15 14:04:50.761   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:04:50.761  3812  3841 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:04:50.761  5652  5668 D BluetoothMap: onBluetoothStateChange: up=false
11-15 14:04:50.762  3133  3150 D BluetoothMap: onBluetoothStateChange: up=false
11-15 14:04:50.762  3133  4019 D BluetoothPbap: onBluetoothStateChange: up=false
11-15 14:04:50.763  5723  5735 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-15 14:04:50.763  5723  5735 D BluetoothAdapterProperties: Setting state to 16
11-15 14:04:50.763  5723  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-15 14:04:50.764  5723  5735 D BluetoothAdapterProperties: onBleDisable
11-15 14:04:50.765  5723  5736 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-15 14:04:50.765  5723  5746 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-15 14:04:50.765  5723  5746 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:04:50.765  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:50.766  5723  5735 I BluetoothAdapterState: Entering PendingCommandState
,11-15 14:04:50.766  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 14:04:50.767  5723  5739 D BluetoothAdapterProperties: Scan Mode:20
11-15 14:04:50.771  5586  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:04:50.773  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 14:04:50.774  5652  5652 D DockEventReceiver: finishStartingService: stopping service
,11-15 14:04:50.971  5723  5739 I bt_hci  : shut_down
,11-15 14:04:50.976  5723  5743 D bt_hwcfg: hw_epilog_process
,11-15 14:04:50.977  5723  5743 I bt_vendor: low_power_mode_cb
,11-15 14:04:50.979  5723  5743 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-15 14:04:50.979  5723  5743 I bt_vendor: epilog_cb
11-15 14:04:50.979  5723  5743 I bt_hci  : epilog_finished_callback
,11-15 14:04:50.981  5723  5739 I bt_hci_h4: hal_close
,11-15 14:04:50.981  5723  5739 I bt_userial_vendor: device fd = 54 close
,11-15 14:04:51.091  5723  5736 D bt_stack_manager: event_shut_down_stack finished.
,11-15 14:04:51.091  5723  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-15 14:04:51.095  5723  5735 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-15 14:04:51.095  5723  5723 D BtGatt.DebugUtils: handleDebugAction() action=null
11-15 14:04:51.095  5723  5723 D BtGatt.GattService: Received stop request...Stopping profile...
11-15 14:04:51.096  5723  5723 D BtGatt.GattService: stop()
11-15 14:04:51.096  5723  5723 D BtGatt.AdvertiseManager: advertise clients cleared
,11-15 14:04:51.099  5723  5723 V BluetoothAdapterState: isTurningOff()=false
11-15 14:04:51.099  5723  5723 V BluetoothAdapterState: isTurningOn()=false
,11-15 14:04:51.099  5723  5723 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:04:51.099  5723  5723 V BluetoothAdapterState: isBleTurningOff()=true
,11-15 14:04:51.099  5723  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-15 14:04:51.099  5723  5735 D BluetoothAdapterProperties: Setting state to 10
11-15 14:04:51.099  5723  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-15 14:04:51.100  5723  5735 I BluetoothAdapterState: Entering OffState
11-15 14:04:51.101   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-15 14:04:51.111  5723  5723 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-15 14:04:51.111  5723  5723 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-15 14:04:51.111  5723  5723 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-15 14:04:51.113  5723  5736 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-15 14:04:51.117  5723  5723 I art     : System.exit called, status: 0
,11-15 14:04:51.117  5723  5723 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-15 14:04:51.140   926  3809 I ActivityManager: Process com.android.bluetooth (pid 5723) has died
,11-15 14:04:52.223   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:52.950  3585  3585 I ConfigService: onDestroy
,11-15 14:04:53.224   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:54.225   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:55.226   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:55.690  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:04:55.691  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-15 14:04:55.695  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 14:04:55.696  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5340e68 removed from the list
,11-15 14:04:55.696  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:04:55.701  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-15 14:04:55.701  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@82eb767 added. We now have 4 listener(s)
11-15 14:04:55.701  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 14:04:55.703  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:04:55.703  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@82eb767 removed from the list
,11-15 14:04:55.703  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:04:55.706  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:04:55.706  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@86fa914 added. We now have 4 listener(s)
11-15 14:04:55.707  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 14:04:56.227   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:04:57.227   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-15 14:05:00.032  3160  3160 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32513]" dev="sockfs" ino=32513 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 14:05:00.032   926   946 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-15 14:05:00.037  3661  3661 I Keyboard.Facilitator: onFinishInput()
11-15 14:05:00.035  3160  3160 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32513]" dev="sockfs" ino=32513 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 14:05:00.055   926   946 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-15 14:05:00.055   926   946 I Adreno  : Build Date                       : 12/06/15
11-15 14:05:00.055   926   946 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-15 14:05:00.055   926   946 I Adreno  : Local Branch                     : mybranch17112971
11-15 14:05:00.055   926   946 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-15 14:05:00.055   926   946 I Adreno  : Remote Branch                    : NONE
11-15 14:05:00.055   926   946 I Adreno  : Reconstruct Branch               : NOTHING
,11-15 14:05:00.085   384  2918 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (132 us)
,11-15 14:05:00.718  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 14:05:00.751   926   943 I ActivityManager: Start proc 5781:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-15 14:05:00.787  5586  5586 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-15 14:05:00.787  5586  5586 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-15 14:05:00.815   926   946 I sensors : batch
11-15 14:05:00.816   926   946 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-15 14:05:00.819   926   946 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-15 14:05:00.819   926   946 I sensors : activate
,11-15 14:05:00.820   926   944 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,11-15 14:05:00.822   384   384 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f79d43c00
,11-15 14:05:00.822   384   384 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-15 14:05:00.824   926  2731 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
11-15 14:05:00.825   926  2731 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-15 14:05:00.830  5586  5586 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1b70d14 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@68745bd, 16908290=android.view.AbsSavedState$1@68745bd}, android:focusedViewId=100}]}]
,11-15 14:05:00.830  5586  5586 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-15 14:05:00.830  5586  5586 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-15 14:05:00.830  5586  5586 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,11-15 14:05:00.852  5781  5781 D AdapterServiceConfig: Adding HeadsetService
11-15 14:05:00.852  5781  5781 D AdapterServiceConfig: Adding A2dpService
11-15 14:05:00.852  5781  5781 D AdapterServiceConfig: Adding HidService
,11-15 14:05:00.852  5781  5781 D AdapterServiceConfig: Adding HealthService
11-15 14:05:00.852  5781  5781 D AdapterServiceConfig: Adding PanService
11-15 14:05:00.852  5781  5781 D AdapterServiceConfig: Adding GattService
11-15 14:05:00.852  5781  5781 D AdapterServiceConfig: Adding BluetoothMapService
11-15 14:05:00.852  5781  5781 D AdapterServiceConfig: Adding SapService
,11-15 14:05:00.857  5781  5781 D BluetoothAdapterState: make() - Creating AdapterState
11-15 14:05:00.857   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ecbda2b:true
,11-15 14:05:00.859  5781  5781 I bt_bluedroid: init
,11-15 14:05:00.860  5781  5795 I BluetoothAdapterState: Entering OffState
,11-15 14:05:00.862  5781  5796 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-15 14:05:00.862  5781  5796 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-15 14:05:00.862  5781  5796 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-15 14:05:00.862  5781  5796 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-15 14:05:00.863  5781  5781 I bt_bluedroid: get_profile_interface socket
,11-15 14:05:00.864  5781  5781 I bt_bluedroid: get_profile_interface sdp
,11-15 14:05:00.864  5781  5799 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-15 14:05:00.866  5781  5799 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 14:05:00.866  5781  5792 I bt_bluedroid: config_hci_snoop_log
11-15 14:05:00.867   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-15 14:05:00.870  5781  5795 D BluetoothAdapterState: Current state: OFF, message: 0
,11-15 14:05:00.870  5781  5795 D BluetoothAdapterProperties: Setting state to 14
11-15 14:05:00.870  5781  5795 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-15 14:05:00.872  5781  5795 D BluetoothBondStateMachine: make
,11-15 14:05:00.873  5781  5800 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-15 14:05:00.875  5781  5795 I BluetoothAdapterState: Entering PendingCommandState
,11-15 14:05:00.876  5781  5781 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-15 14:05:00.877  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
11-15 14:05:00.877  5781  5781 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-15 14:05:00.878  5781  5781 D BtGatt.GattService: Received start request. Starting profile...
11-15 14:05:00.878  5781  5781 D BtGatt.GattService: start()
11-15 14:05:00.878  5781  5781 I bt_bluedroid: get_profile_interface gatt
11-15 14:05:00.878  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
11-15 14:05:00.878  5781  5781 D BtGatt.AdvertiseManager: advertise manager created
,11-15 14:05:00.882  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 14:05:00.882  5781  5781 V BluetoothAdapterState: isTurningOn()=false
11-15 14:05:00.882  5781  5781 V BluetoothAdapterState: isBleTurningOn()=true
,11-15 14:05:00.882  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:05:00.883  5781  5795 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-15 14:05:00.884  5781  5795 I bt_bluedroid: bt_bluedroid
11-15 14:05:00.884  5781  5796 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-15 14:05:00.884  5781  5796 I bt_hci  : start_up
,11-15 14:05:00.889  5781  5796 I bt_vendor: alloc value 0xf3bb9871
,11-15 14:05:00.889  5781  5796 I bt_vendor: init
11-15 14:05:00.889  5781  5796 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-15 14:05:00.889  5781  5796 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-15 14:05:01.001  5781  5796 D bt_hci  : start_up starting async portion
11-15 14:05:01.001  5781  5803 I bt_hci  : event_finish_startup
,11-15 14:05:01.002  5781  5803 I bt_hci_h4: hal_open
11-15 14:05:01.002  5781  5803 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-15 14:05:00.998  5804  5804 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 14:05:01.005  5781  5803 I bt_userial_vendor: device fd = 54 open
,11-15 14:05:01.022  5781  5803 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 14:05:01.025  5781  5803 D bt_hwcfg: Chipset BCM4358A3
11-15 14:05:01.025  5781  5803 D bt_hwcfg: Target name = [BCM4358A3]
11-15 14:05:01.026  5781  5803 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-15 14:05:01.135   384   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-15 14:05:01.137   384   384 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-15 14:05:01.138   926  3088 D SurfaceControl: Excessive delay in setPowerMode(): 318ms
,11-15 14:05:01.148   926   946 I DreamManagerService: Entering dreamland.
11-15 14:05:01.149   926   946 I PowerManagerService: Dozing...
,11-15 14:05:01.150   926   941 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-15 14:05:01.178  3844  3844 W Binder_C: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[32956]" dev="sockfs" ino=32956 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 14:05:01.183   926  3855 I sensors : batch
11-15 14:05:01.184   926  3855 I sensors : activate
11-15 14:05:01.178  3844  3844 W Binder_C: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[32956]" dev="sockfs" ino=32956 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 14:05:01.188   926  2731 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-15 14:05:01.188   926  2731 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-15 14:05:01.192   513  3042 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-15 14:05:01.327  3812  4756 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-15 14:05:01.328  3812  4756 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-15 14:05:01.328  3812  4756 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-15 14:05:01.328   526  1212 D         : oem-qmi: Connection accepted
11-15 14:05:01.328   526  1212 D         : oem-qmi: Waiting to accept connection
,11-15 14:05:01.330   926   926 I sensors : activate
,11-15 14:05:01.331   513   513 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-15 14:05:01.333   926  2731 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-15 14:05:01.335  3812  4756 D         : oem_qmi_lib:output 0
11-15 14:05:01.335  3812  4756 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-15 14:05:01.353  3812  4756 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-15 14:05:01.353  3812  4756 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-15 14:05:01.353  3812  4756 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-15 14:05:01.353   526  1212 D         : oem-qmi: Connection accepted
11-15 14:05:01.354   526  1212 D         : oem-qmi: Waiting to accept connection
,11-15 14:05:01.360  3812  4756 D         : oem_qmi_lib:output 0
,11-15 14:05:01.360  3812  4756 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-15 14:05:01.430  5781  5803 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-15 14:05:01.430  5781  5803 D bt_hwcfg: Settlement delay -- 100 ms
11-15 14:05:01.430  5781  5803 I bt_hwcfg: Setting fw settlement delay to 100 
,11-15 14:05:01.566  5781  5803 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 14:05:01.566  5781  5803 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-15 14:05:01.567  5781  5803 I bt_hwcfg: vendor lib fwcfg completed
11-15 14:05:01.568  5781  5803 I bt_vendor: firmware callback
11-15 14:05:01.568  5781  5803 I bt_hci  : firmware_config_callback
,11-15 14:05:01.578  5781  5810 I bt_btu  : btu_task pending for preload complete event
,11-15 14:05:01.578  5781  5810 I bt_btu_task: Bluetooth chip preload is complete
11-15 14:05:01.578  5781  5810 I bt_btu  : btu_task received preload complete event
,11-15 14:05:01.583  5781  5810 I         : BTE_InitTraceLevels -- TRC_HCI
,11-15 14:05:01.584  5781  5810 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-15 14:05:01.584  5781  5810 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-15 14:05:01.584  5781  5810 I         : BTE_InitTraceLevels -- TRC_AVDT
11-15 14:05:01.584  5781  5810 I         : BTE_InitTraceLevels -- TRC_AVRC
11-15 14:05:01.584  5781  5810 I         : BTE_InitTraceLevels -- TRC_A2D
,11-15 14:05:01.584  5781  5810 I         : BTE_InitTraceLevels -- TRC_BNEP
11-15 14:05:01.584  5781  5810 I         : BTE_InitTraceLevels -- TRC_BTM
11-15 14:05:01.584  5781  5810 I         : BTE_InitTraceLevels -- TRC_GAP
11-15 14:05:01.584  5781  5810 I         : BTE_InitTraceLevels -- TRC_PAN
,11-15 14:05:01.585  5781  5810 I         : BTE_InitTraceLevels -- TRC_SDP
11-15 14:05:01.585  5781  5810 I         : BTE_InitTraceLevels -- TRC_GATT
11-15 14:05:01.585  5781  5810 I         : BTE_InitTraceLevels -- TRC_SMP
11-15 14:05:01.585  5781  5810 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-15 14:05:01.585  5781  5810 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-15 14:05:01.668  5781  5810 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b37549
,11-15 14:05:01.668  5781  5810 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b37549 
,11-15 14:05:01.686  5781  5799 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-15 14:05:01.687  5781  5799 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-15 14:05:01.688  5781  5799 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-15 14:05:01.690  5781  5799 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 14:05:01.692  5781  5799 D BluetoothAdapterProperties: Scan Mode:20
,11-15 14:05:01.693  5781  5799 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 14:05:01.693  5781  5799 D bt_hci  : do_postload posting postload work item
11-15 14:05:01.693  5781  5803 I bt_hci  : event_postload
11-15 14:05:01.693  5781  5803 I bt_vendor: sco_config_cb
,11-15 14:05:01.693  5781  5803 I bt_hci  : sco_config_callback postload finished.
11-15 14:05:01.696  5781  5799 D bt_bte_conf: Device ID record 1 : primary
11-15 14:05:01.696  5781  5799 D bt_bte_conf:   vendorId            = 000f
11-15 14:05:01.696  5781  5799 D bt_bte_conf:   vendorIdSource      = 0001
11-15 14:05:01.696  5781  5799 D bt_bte_conf:   product             = 1200
11-15 14:05:01.696  5781  5799 D bt_bte_conf:   version             = 1436
,11-15 14:05:01.696  5781  5799 D bt_bte_conf:   clientExecutableURL = 
11-15 14:05:01.697  5781  5799 D bt_bte_conf:   serviceDescription  = 
11-15 14:05:01.697  5781  5799 D bt_bte_conf:   documentationURL    = 
11-15 14:05:01.697  5781  5799 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-15 14:05:01.697  5781  5796 D bt_stack_manager: event_start_up_stack finished
11-15 14:05:01.698  5781  5795 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-15 14:05:01.699  5781  5795 D BluetoothAdapterProperties: Setting state to 15
11-15 14:05:01.699  5781  5795 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-15 14:05:01.700  5781  5795 I BluetoothAdapterState: Entering BleOnState
,11-15 14:05:01.704  5781  5803 I bt_vendor: low_power_mode_cb
,11-15 14:05:01.706  5781  5795 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-15 14:05:01.706  5781  5795 D BluetoothAdapterProperties: Setting state to 11
11-15 14:05:01.706  5781  5795 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-15 14:05:01.712  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
,11-15 14:05:01.713  5781  5781 D HeadsetService: Received start request. Starting profile...
11-15 14:05:01.716  5781  5781 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-15 14:05:01.716  5781  5781 D HeadsetStateMachine: make
,11-15 14:05:01.726  5781  5795 I BluetoothAdapterState: Entering PendingCommandState
,11-15 14:05:01.727  5781  5781 D HeadsetStateMachine: max_hf_connections = 1
,11-15 14:05:01.727  5781  5781 I bt_bluedroid: get_profile_interface handsfree
11-15 14:05:01.728  5781  5799 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-15 14:05:01.728  5781  5799 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-15 14:05:01.732  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
,11-15 14:05:01.733  5781  5781 D A2dpService: Received start request. Starting profile...
11-15 14:05:01.733  5781  5781 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-15 14:05:01.734  5781  5781 I bt_bluedroid: get_profile_interface avrcp
,11-15 14:05:01.739  5781  5781 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-15 14:05:01.739  5781  5781 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-15 14:05:01.739  5781  5781 D A2dpStateMachine: make
11-15 14:05:01.740  5781  5781 I bt_bluedroid: get_profile_interface a2dp
,11-15 14:05:01.741  5781  5799 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-15 14:05:01.742  5781  5819 D A2dpStateMachine: Enter Disconnected: -2
,11-15 14:05:01.744  5781  5781 I BluetoothHidServiceJni: classInitNative: succeeds
,11-15 14:05:01.745  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
11-15 14:05:01.745  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 14:05:01.746  5781  5781 D HidService: Received start request. Starting profile...
11-15 14:05:01.746  5781  5781 I bt_bluedroid: get_profile_interface hidhost
11-15 14:05:01.746  5781  5781 D HidService: setHidService(): set to: null
11-15 14:05:01.746  5781  5799 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b1856d
,11-15 14:05:01.747  5781  5799 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-15 14:05:01.747  5781  5781 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-15 14:05:01.748  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
11-15 14:05:01.748  5781  5781 D HealthService: Received start request. Starting profile...
,11-15 14:05:01.750  5781  5781 I bt_bluedroid: get_profile_interface health
,11-15 14:05:01.750  5781  5781 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-15 14:05:01.751  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
,11-15 14:05:01.752  5781  5781 D PanService: Received start request. Starting profile...
,11-15 14:05:01.752  5781  5781 D BluetoothPanServiceJni: initializeNative(L110): pan
11-15 14:05:01.752  5781  5781 I bt_bluedroid: get_profile_interface pan
11-15 14:05:01.752  5781  5799 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-15 14:05:01.754  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
11-15 14:05:01.756  5781  5781 D BluetoothMapService: Received start request. Starting profile...
11-15 14:05:01.756  5781  5781 D BluetoothMapService: start()
,11-15 14:05:01.759  5781  5781 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-15 14:05:01.759  5781  5781 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-15 14:05:01.760  5781  5781 D BluetoothMapAppObserver: createReceiver()
11-15 14:05:01.761  5781  5781 D BluetoothMapAppObserver: initObservers()
11-15 14:05:01.761  5781  5781 D BluetoothMapAppObserver: getEnabledAccountItems()
11-15 14:05:01.766  5781  5781 V SapService: SapBinder()
,11-15 14:05:01.767  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
11-15 14:05:01.767  5781  5781 D SapService: Received start request. Starting profile...
11-15 14:05:01.767  5781  5781 V SapService: start()
,11-15 14:05:01.769  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 14:05:01.769  5781  5781 V BluetoothAdapterState: isTurningOn()=true
11-15 14:05:01.769  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:05:01.769  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:05:01.769  5781  5816 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,11-15 14:05:01.769  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 14:05:01.769  5781  5781 V BluetoothAdapterState: isTurningOn()=true
11-15 14:05:01.769  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:05:01.769  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 14:05:01.770  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 14:05:01.770  5781  5781 V BluetoothAdapterState: isTurningOn()=true
11-15 14:05:01.770  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:05:01.770  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:05:01.770  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 14:05:01.770  5781  5781 V BluetoothAdapterState: isTurningOn()=true
11-15 14:05:01.770  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:05:01.770  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:05:01.770  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 14:05:01.770  5781  5781 V BluetoothAdapterState: isTurningOn()=true
11-15 14:05:01.770  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:05:01.770  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:05:01.771  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 14:05:01.771  5781  5781 V BluetoothAdapterState: isTurningOn()=true
11-15 14:05:01.771  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:05:01.771  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:05:01.772  5781  5781 V BluetoothAdapterState: isTurningOff()=false
11-15 14:05:01.772  5781  5781 V BluetoothAdapterState: isTurningOn()=true
,11-15 14:05:01.772  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:05:01.772  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 14:05:01.772  5781  5795 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-15 14:05:01.772  5781  5795 D BluetoothAdapterProperties: ScanMode =  20
,11-15 14:05:01.772  5781  5795 D BluetoothAdapterProperties: State =  11
11-15 14:05:01.773  5781  5795 D BluetoothAdapterProperties: Setting state to 12
11-15 14:05:01.773  5781  5795 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-15 14:05:01.773  5652  5668 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-15 14:05:01.774   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:05:01.774  5781  5799 D BluetoothAdapterProperties: Scan Mode:21
11-15 14:05:01.774  5652  5662 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 14:05:01.774  5781  5799 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 14:05:01.776  5781  5795 I BluetoothAdapterState: Entering OnState
,11-15 14:05:01.777  3133  4019 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:05:01.778  5652  5668 D BluetoothPan: onBluetoothStateChange on: true
11-15 14:05:01.779   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:05:01.779  3133  3150 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-15 14:05:01.780  5652  5652 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 14:05:01.780  5652  5652 D PanProfile: Bluetooth service connected
,11-15 14:05:01.782  5652  5668 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 14:05:01.782  3133  3133 D BluetoothA2dp: Proxy object connected
11-15 14:05:01.784  3133  3145 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-15 14:05:01.785   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 14:05:01.785   926   926 D BluetoothA2dp: Proxy object connected
11-15 14:05:01.786  5652  5662 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-15 14:05:01.786  5781  5781 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 14:05:01.786  5781  5781 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-15 14:05:01.786  5652  5652 D BluetoothA2dp: Proxy object connected
,11-15 14:05:01.788  5781  5781 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:05:01.788  3133  4019 D BluetoothPan: onBluetoothStateChange on: true
11-15 14:05:01.789  5781  5781 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:05:01.789  3133  3133 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 14:05:01.789  3133  3133 D PanProfile: Bluetooth service connected
11-15 14:05:01.789   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:05:01.790  3812  3841 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:05:01.790  5652  5668 D BluetoothMap: onBluetoothStateChange: up=true
11-15 14:05:01.790  5781  5781 D ObexServerSockets: Succeed to create listening sockets 
11-15 14:05:01.790  5781  5781 D ObexServerSockets0: startAccept()
,11-15 14:05:01.790  5781  5781 D ObexServerSockets0: prepareForNewConnect()
11-15 14:05:01.792  3133  3328 D BluetoothMap: onBluetoothStateChange: up=true
11-15 14:05:01.792  5781  5781 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-15 14:05:01.793  5781  5781 D BluetoothSdpJni: SDP Create record success - handle: 0
11-15 14:05:01.793  5781  5825 D ObexServerSockets0: Accepting socket connection...
11-15 14:05:01.793  5781  5826 D ObexServerSockets0: Accepting socket connection...
11-15 14:05:01.794  3133  3133 D BluetoothInputDevice: Proxy object connected
11-15 14:05:01.794  3133  3133 D HidProfile: Bluetooth service connected
11-15 14:05:01.794  3133  4019 D BluetoothPbap: onBluetoothStateChange: up=true
,11-15 14:05:01.796  5652  5652 D BluetoothInputDevice: Proxy object connected
11-15 14:05:01.796  5652  5652 D HidProfile: Bluetooth service connected
11-15 14:05:01.796   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
11-15 14:05:01.797  5781  5781 D BluetoothMapService: onReceive
,11-15 14:05:01.797  5781  5781 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 14:05:01.797  5781  5781 D BluetoothMapService: STATE_ON
11-15 14:05:01.797  3133  3133 D BluetoothMap: Proxy object connected
11-15 14:05:01.797  3133  3133 D MapProfile: Bluetooth service connected
11-15 14:05:01.797  3133  3133 D BluetoothMap: getConnectedDevices()
,11-15 14:05:01.798  5652  5652 D BluetoothMap: Proxy object connected
,11-15 14:05:01.798  5652  5652 D MapProfile: Bluetooth service connected
11-15 14:05:01.798  5652  5652 D BluetoothMap: getConnectedDevices()
11-15 14:05:01.800  5781  5827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:05:01.801  5781  5827 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-15 14:05:01.801  5781  5827 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-15 14:05:01.804  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 14:05:01.810  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 14:05:01.810  5652  5652 D DockEventReceiver: finishStartingService: stopping service
,11-15 14:05:01.817  5652  5652 D BluetoothPbap: Proxy object connected
,11-15 14:05:01.817  5652  5652 D PbapServerProfile: Bluetooth service connected
,11-15 14:05:01.823  5781  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 14:05:01.823  5781  5781 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 14:05:01.823  5781  5781 D ObexServerSockets0: prepareForNewConnect()
11-15 14:05:01.823  3133  3133 D BluetoothPbap: Proxy object connected
11-15 14:05:01.824  3133  3133 D PbapServerProfile: Bluetooth service connected
,11-15 14:05:01.838  5781  5835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 14:05:01.839  5781  5835 I BtOppRfcommListener: Accept thread started.
,11-15 14:05:01.875   926   926 D BluetoothHeadset: Proxy object connected
,11-15 14:05:01.875  3812  3839 D BluetoothHeadset: Proxy object connected
11-15 14:05:01.876  3133  3328 D BluetoothHeadset: Proxy object connected
11-15 14:05:01.876  3133  3133 D HeadsetProfile: Bluetooth service connected
,11-15 14:05:01.876  5652  5824 D BluetoothHeadset: Proxy object connected
,11-15 14:05:01.877   926   926 D BluetoothHeadset: Proxy object connected
11-15 14:05:01.877   926   926 D BluetoothHeadset: Proxy object connected
11-15 14:05:01.879  3133  3145 D BluetoothHeadset: Proxy object connected
11-15 14:05:01.879  3133  3133 D HeadsetProfile: Bluetooth service connected
11-15 14:05:01.879   926   943 D BluetoothHeadset: Proxy object connected
11-15 14:05:01.880  5652  5652 D HeadsetProfile: Bluetooth service connected
,11-15 14:05:01.890   926   943 D BluetoothHeadset: Proxy object connected
,11-15 14:05:01.891  3812  4039 D BluetoothHeadset: Proxy object connected
,11-15 14:05:04.868  3741  4452 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-15 14:05:05.733  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:05:05.733  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:05:05.733  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:05:05.733  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 14:05:05.733  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:05:05.733  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 14:05:05.733  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 14:05:05.733  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 14:05:05.733  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 14:05:05.739  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 14:05:05.739  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:05:05.740  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@86fa914 removed from the list
11-15 14:05:05.740  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:05:05.745  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-15 14:05:05.745  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c0677b2 added. We now have 4 listener(s)
,11-15 14:05:05.745  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 14:05:05.749   926   936 D WifiService: setWifiEnabled: false pid=5586, uid=10077
,11-15 14:05:05.749   926   936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 14:05:10.758  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:05:10.760   926  3786 D WifiService: setWifiEnabled: true pid=5586, uid=10077
,11-15 14:05:10.760   926  3786 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 14:05:10.772   508   920 D SoftapController: Softap fwReload - Ok
,11-15 14:05:10.776   508   920 D CommandListener: Setting iface cfg
11-15 14:05:10.776   508   920 D CommandListener: Trying to bring down wlan0
11-15 14:05:10.778   508   920 D CommandListener: Clearing all IP addresses on wlan0
11-15 14:05:10.781   926  2976 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-15 14:05:11.391   926  2976 D wifi    : set interface wlan0 flags (UP)
,11-15 14:05:11.393   926  2976 I WifiHAL : Initializing wifi
,11-15 14:05:11.393   926  2976 I WifiHAL : Creating socket,
,11-15 14:05:11.400   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-15 14:05:11.402   926  2976 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-15 14:05:11.403   926  2976 D wifi    : Did set static halHandle = 0x7f5c451e00
11-15 14:05:11.403   926  2976 D wifi    : halHandle = 0x7f5c451e00, mVM = 0x7f78acd140, mCls = 0x15de
11-15 14:05:11.403   926  2976 D wifi    : array field set
11-15 14:05:11.403   926  2976 I WifiNative-HAL: interface[0] = wlan0
,11-15 14:05:11.405   926  5840 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547008880128
,11-15 14:05:11.405   926  5840 D wifi    : waitForHalEvents called, vm = 0x7f78acd140, obj = 0x15de, env = 0x7f5c455e40
,11-15 14:05:11.413   926  2976 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-15 14:05:11.415   926  2976 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-15 14:05:11.476  5841  5841 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-15 14:05:11.557  5841  5841 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 14:05:11.639  5841  5841 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-15 14:05:11.639  5841  5841 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-15 14:05:12.229   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:05:12.428   926  2976 D WifiConfigStore: Loading config and enabling all networks 
,11-15 14:05:12.462   926  2976 D WifiConfigStore: loaded 0 passpoint configs
,11-15 14:05:12.463   926  2976 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-15 14:05:12.464   926  2976 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-15 14:05:12.465   926  2976 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-15 14:05:12.465   926  2976 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-15 14:05:12.466   926  2976 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-15 14:05:12.467   926  2976 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-15 14:05:12.468   926  2976 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-15 14:05:12.468   926  2976 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-15 14:05:12.468   926  2976 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-15 14:05:12.468   926  2976 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-15 14:05:12.468   926  2976 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-15 14:05:12.468   926  2976 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-15 14:05:12.472   926  2976 D WifiNative-HAL: Setting external_sim to 1
,11-15 14:05:12.472  4505  4505 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-15 14:05:12.472   926  2976 D wifi    : setting dfs flag to true, 0x7f5c96cbe0
11-15 14:05:12.473   926  2976 D WifiStateMachine: Setting OUI to DA-A1-19
11-15 14:05:12.473   926  2976 D wifi    : setting scan oui 0x7f5c96cbe0
11-15 14:05:12.473   926  2976 D WifiHAL : Sending mac address OUI
,11-15 14:05:12.478   926  2976 E native  : do suspend true
,11-15 14:05:12.486   926  2976 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-15 14:05:12.487   508   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-15 14:05:12.487   926   926 D RttService: SCAN_AVAILABLE : 3
11-15 14:05:12.487   926  3085 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-15 14:05:12.488   508   920 D CommandListener: Setting iface cfg
,11-15 14:05:12.498   926  2961 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '135 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 135 Failed to set address (No such device)'
11-15 14:05:12.498   926  2961 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-15 14:05:12.507   926  2961 D WifiNative-HAL: p2pGetDeviceAddress
11-15 14:05:12.507   926  2961 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-15 14:05:12.514   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=163930 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=9 mControllerEnergyUsed=34 }
,11-15 14:05:13.230   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:05:14.232   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:05:15.233   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:05:15.653  5841  5841 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-15 14:05:15.683   926  2976 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-15 14:05:15.689   926  2976 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
11-15 14:05:15.690   926  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 14:05:15.703   926  2976 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-15 14:05:15.759   926  2976 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-15 14:05:15.775  5586  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:05:15.775  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:05:15.775  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:05:15.775  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:05:15.775  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:05:15.775  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 14:05:15.775  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 14:05:15.775  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 14:05:15.775  5586  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 14:05:15.778  5586  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-15 14:05:15.778  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:05:15.778  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c0677b2 removed from the list
11-15 14:05:15.778  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:05:15.783  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-15 14:05:15.784  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-15 14:05:15.786  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1b70d14 Bundle[{}]
11-15 14:05:15.787  5586  5633 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-15 14:05:15.787  5586  5633 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-15 14:05:15.788  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-15 14:05:15.788  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-15 14:05:15.788  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-15 14:05:15.789  5586  5633 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-15 14:05:15.797  5586  5633 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-15 14:05:15.798  5586  5633 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-15 14:05:15.798  5586  5633 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-15 14:05:15.800  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 14:05:15.800  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce56303 added. We now have 3 listener(s)
,11-15 14:05:15.803  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 14:05:15.803  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 14:05:15.803  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 14:05:15.803  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:05:15.803  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9284280 added. We now have 4 listener(s)
,11-15 14:05:15.803  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 14:05:15.804  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 14:05:15.806  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 14:05:15.806  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96780b9 added. We now have 4 listener(s)
11-15 14:05:15.808  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 14:05:15.808  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 14:05:15.808  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 14:05:15.808  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:05:15.808  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2605cfe added. We now have 5 listener(s)
11-15 14:05:15.808  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 14:05:15.808  5586  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:05:15.808  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-15 14:05:15.809  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:05:15.809  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:05:15.809  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:05:15.809  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 14:05:15.809  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce56303 removed from the list
11-15 14:05:15.809  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:05:15.809  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9284280 removed from the list
11-15 14:05:15.809  5586  5633 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:05:15.809  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:05:15.811  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:05:15.812  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:05:15.812  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:05:15.812  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-15 14:05:15.812  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:05:15.812  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:05:15.812  5586  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9284280 not in the list
11-15 14:05:15.812  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:05:15.814  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:05:15.814  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:05:15.814  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:05:15.814  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-15 14:05:15.814  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-15 14:05:15.814  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:05:15.814  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2605cfe removed from the list
,11-15 14:05:15.815  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:05:15.815  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:05:15.815  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 14:05:15.815  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96780b9 removed from the list
11-15 14:05:15.816  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 14:05:15.816  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d12c5f added. We now have 3 listener(s)
,11-15 14:05:15.817  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 14:05:15.817  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 14:05:15.817  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 14:05:15.818  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:05:15.818  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0f06ac added. We now have 4 listener(s)
11-15 14:05:15.818  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 14:05:15.818  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-15 14:05:15.819  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 14:05:15.819  5586  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1766f75 added. We now have 4 listener(s)
,11-15 14:05:15.821  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 14:05:15.821  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-15 14:05:15.821  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 14:05:15.822  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:05:15.822  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee14b0a added. We now have 5 listener(s)
11-15 14:05:15.822  5586  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 14:05:15.822  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 14:05:15.822  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-15 14:05:15.822  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-15 14:05:15.822  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:05:15.822  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-15 14:05:15.823  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-15 14:05:15.826  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 14:05:15.827  5586  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 14:05:15.827  5586  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 14:05:15.829  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:05:15.829  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 14:05:15.830  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 14:05:15.830  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 14:05:15.830  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-15 14:05:15.832  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:05:15.833  5586  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 14:05:15.833  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 14:05:15.833  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 14:05:15.833  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 14:05:15.833  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:05:15.833  5586  5633 D BluetoothAdapter: STATE_ON
,11-15 14:05:15.836  5781  5815 D BtGatt.GattService: registerClient() - UUID=584c3023-0130-49bb-97a2-623c81a2d4ff
,11-15 14:05:15.837  5781  5799 D BtGatt.GattService: onClientRegistered() - UUID=584c3023-0130-49bb-97a2-623c81a2d4ff, clientIf=5
,11-15 14:05:15.838  5586  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-15 14:05:15.839  5781  5791 D BtGatt.GattService: start scan with filters
,11-15 14:05:15.842  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-15 14:05:15.842  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:05:15.842  5781  5802 D BtGatt.ScanManager: handling starting scan
11-15 14:05:15.842  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 14:05:15.842  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:05:15.842  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 14:05:15.842  5586  5586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 14:05:15.842  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:05:15.842  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 14:05:15.842  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 14:05:15.842  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:05:15.843  5586  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-15 14:05:15.843  5586  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-15 14:05:15.843  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 14:05:15.844  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:05:15.844  5781  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6a5681
,11-15 14:05:15.846  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:05:15.846  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 14:05:15.846  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 14:05:15.846  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 14:05:15.846  5586  5633 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-15 14:05:15.846  5586  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-15 14:05:15.847  5586  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 14:05:15.847  5586  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-15 14:05:15.847  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 14:05:15.847  5586  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:05:15.847  5586  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 14:05:15.847  5586  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 14:05:15.847  5586  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 14:05:15.847  5586  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-15 14:05:15.851  5781  5799 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-15 14:05:15.851  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:05:15.851  5781  5802 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-15 14:05:15.857  5781  5799 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-15 14:05:15.857  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:05:15.857  5781  5802 D BtGatt.ScanManager: Starting BLE batch scan
11-15 14:05:15.857  5781  5802 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-15 14:05:15.867  5781  5799 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-15 14:05:15.867  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:05:15.873  5781  5799 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-15 14:05:15.873  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:05:16.229  5841  5841 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-15 14:05:16.234   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:05:16.259  5841  5841 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-15 14:05:16.260  5841  5841 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-15 14:05:16.270   926  2976 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-15 14:05:16.270   926  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-15 14:05:16.270   926  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-15 14:05:16.287   926  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 14:05:16.298   508   920 D CommandListener: Setting iface cfg
,11-15 14:05:16.303   926  2976 D WifiStateMachine: Start Dhcp Watchdog 2
,11-15 14:05:16.307   926  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-15 14:05:16.312   926  5846 D DhcpClient: Receive thread started
,11-15 14:05:16.383  5781  5781 D BtGatt.ScanManager: awakened up at time 167799
,11-15 14:05:16.384  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:05:16.401   926  2976 E native  : do suspend false
,11-15 14:05:16.404  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-15 14:05:16.405  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:05:16.405  5781  5799 D BtGatt.GattService: current time is 167821533116
,11-15 14:05:16.406  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
,11-15 14:05:16.408  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,11-15 14:05:16.415   926  5845 D DhcpClient: Broadcasting DHCPDISCOVER
,11-15 14:05:16.427   926  5846 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172673, domain null
,11-15 14:05:16.428   926  5845 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172673 seconds
,11-15 14:05:16.429   926  5845 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-15 14:05:16.446   926  5846 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-15 14:05:16.446   926  5845 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-15 14:05:16.449   508   920 D CommandListener: Setting iface cfg
,11-15 14:05:16.451   926  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-15 14:05:16.454   926  2976 E native  : do suspend true
,11-15 14:05:16.454   926  5845 D DhcpClient: Scheduling renewal in 86399s
,11-15 14:05:16.468   926  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-15 14:05:16.468   926  2976 D WifiConfigStore: No blacklist allowed without epno enabled
11-15 14:05:16.469   926  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-15 14:05:16.471   926  2978 D ConnectivityService: Adding iface wlan0 to network 101
11-15 14:05:16.473   926  2976 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-15 14:05:16.517   926  2978 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-15 14:05:16.517   926  2978 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-15 14:05:16.520   926  2978 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-15 14:05:16.522   926  2978 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-15 14:05:16.524   926  2978 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-15 14:05:16.531   926  2978 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 14:05:16.536   926  2978 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-15 14:05:16.537   926  2978 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-15 14:05:16.537   926  2978 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-15 14:05:16.537   926  2978 D ConnectivityService:    accepting network in place of null
11-15 14:05:16.537   926  2976 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-15 14:05:16.537   926  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 14:05:16.538   926  2978 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-15 14:05:16.549   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167964, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-15 14:05:16.568   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 14:05:16.592   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 14:05:16.595   926  2978 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-15 14:05:16.596   926  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-15 14:05:16.596  3767  3890 W QCNEJ   : |CORE| network available: 101
11-15 14:05:16.597   926  2978 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-15 14:05:16.598   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-15 14:05:16.602  3767  3890 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-15 14:05:16.603  3767  3890 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-15 14:05:16.604  3767  3890 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-15 14:05:16.611  3994  3994 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-15 14:05:16.616  3994  3994 D SystemUpdateService: onCreate
,11-15 14:05:16.617  3979  3979 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-15 14:05:16.620  3994  3994 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-15 14:05:16.627  3994  5855 I SystemUpdateService: active receiver: enabled
,11-15 14:05:16.633   926  5843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,11-15 14:05:16.641  3994  3994 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-15 14:05:16.643  3994  4296 I iu.UploadsManager: num queued entries: 0
,11-15 14:05:16.643  3994  4296 I iu.UploadsManager: num updated entries: 0
,11-15 14:05:16.654  3994  5855 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 14:05:16.657  3994  3994 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-15 14:05:16.658  3994  3994 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-15 14:05:16.660  5689  5689 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 14:05:16.668  5689  5689 D SprintDMHelper: simOperator: 
,11-15 14:05:16.668  5689  5689 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 14:05:16.671  3994  4296 I iu.SyncManager: NEXT; no task
,11-15 14:05:16.675  3994  5855 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-15 14:05:16.675  3994  5855 I SystemUpdateService: now status is 0 (complete)
11-15 14:05:16.675  3994  5855 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-15 14:05:16.675  3994  5855 I SystemUpdateService: file has been verified
11-15 14:05:16.675  3994  5855 I SystemUpdateService: OTA package size = 21989297
,11-15 14:05:16.689   926  5843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 15 Nov 2016 13:05:16 GMT], X-Android-Received-Millis=[1479215116688], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479215116657]}
11-15 14:05:16.690   926  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-15 14:05:16.690   926  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-15 14:05:16.690   926  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 14:05:16.691   926  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-15 14:05:16.692  3994  5855 I SystemUpdateService: showing system update notification
,11-15 14:05:16.703   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 14:05:16.723  3585  5862 I VacuumService: Vacuum at: now=1479215116723 tag=VacuumService
,11-15 14:05:16.726  3994  3994 D SystemUpdateService: onDestroy
,11-15 14:05:16.764  3585  5865 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-15 14:05:16.795  3585  5863 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-15 14:05:16.797  3585  5863 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-15 14:05:16.818  3585  5865 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 14:05:17.236   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-15 14:05:17.270  3585  5863 W Uploader:  no longer exists, so no auth token.
,11-15 14:05:17.278  3585  5868 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 14:05:17.380  3585  5865 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 14:05:17.574  3585  5863 W Uploader:  no longer exists, so no auth token.
,11-15 14:05:17.583  3585  5868 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 14:05:17.597   926  2978 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-15 14:05:17.698  3585  5865 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 14:05:17.835  3585  5868 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 14:05:17.981  3585  5865 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 14:05:18.499  3585  5867 I SQLiteConnectionPool: The connection pool for /data/user/0/com.google.android.gms/databases/phenotype.db has been closed but there are still 1 connections in use.  They will be closed as they are released back to the pool.
,11-15 14:05:18.502  3585  5867 E ClearcutLoggerIntentService: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
11-15 14:05:18.502  3585  5867 E ClearcutLoggerIntentService: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
11-15 14:05:18.502  3585  5867 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
11-15 14:05:18.502  3585  5867 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:520)
11-15 14:05:18.502  3585  5867 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:143)
11-15 14:05:18.502  3585  5867 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
11-15 14:05:18.502  3585  5867 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
11-15 14:05:18.502  3585  5867 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
11-15 14:05:18.502  3585  5867 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-15 14:05:18.502  3585  5867 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-15 14:05:18.502  3585  5867 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,11-15 14:05:24.545   926  2978 D ConnectivityService: handlePromptUnvalidated 101
,11-15 14:05:37.238   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:05:38.240   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:05:39.243   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:05:40.244   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:05:41.245   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:05:42.246   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-15 14:05:56.190   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=207605, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-15 14:06:00.039  3661  3873 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-15 14:06:00.039  3661  3873 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-15 14:06:00.076  3585  3585 I ConfigService: onCreate
,11-15 14:06:05.118  3585  3585 I ConfigService: onDestroy
,11-15 14:06:07.247   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-15 14:06:07.247   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-15 14:06:16.687   926   939 W BroadcastQueue: Timeout of broadcast BroadcastRecord{8816ae4 u-1 android.net.conn.CONNECTIVITY_CHANGE} - receiver=android.os.BinderProxy@e042b4d, started 60001ms ago
11-15 14:06:16.688   926   939 W BroadcastQueue: Receiver during timeout: ResolveInfo{7861602 com.test.thalitest/io.jxcore.node.ConnectivityChangeListener m=0x108000}
,11-15 14:06:16.712  5781  5781 D BtGatt.ScanManager: awakened up at time 228129
,11-15 14:06:16.714  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:06:16.743   926   939 I Process : Sending signal. PID: 5586 SIG: 3
,11-15 14:06:16.743  5586  5591 I art     : Thread[2,tid=5591,WaitingInMainSignalCatcherLoop,Thread*=0xeefcb000,peer=0x12c2f0a0,"Signal Catcher"]: reacting to signal 3
,11-15 14:06:16.753  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:06:16.753  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:06:16.753  5781  5799 D BtGatt.GattService: current time is 228169528366
,11-15 14:06:16.753  5781  5799 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -77, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 85, -113, -37, 31, -33, 8, 0, 4, -100, 83, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -78, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -86, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -90, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 100, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:06:16.754  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:06:16.754  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,11-15 14:06:16.754  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:06:16.754  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:06:16.754  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:06:16.754  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:06:16.755  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:06:16.944   926   939 I Process : Sending signal. PID: 926 SIG: 3
,11-15 14:06:16.944   926   930 I art     : Thread[2,tid=930,WaitingInMainSignalCatcherLoop,Thread*=0x7f72943000,peer=0x12c010a0,"Signal Catcher"]: reacting to signal 3
,11-15 14:06:17.144   926   939 I Process : Sending signal. PID: 3812 SIG: 3
,11-15 14:06:17.145  3812  3823 I art     : Thread[2,tid=3823,WaitingInMainSignalCatcherLoop,Thread*=0x7f72943000,peer=0x12c540a0,"Signal Catcher"]: reacting to signal 3
,11-15 14:06:17.200  5586  5591 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-15 14:06:17.200   926   939 I Process : Sending signal. PID: 3791 SIG: 3
11-15 14:06:17.200  3791  3802 I art     : Thread[2,tid=3802,WaitingInMainSignalCatcherLoop,Thread*=0x7f72943000,peer=0x12c530a0,"Signal Catcher"]: reacting to signal 3
,11-15 14:06:17.247  3791  3802 I art     : Wrote stack traces to '/data/anr/traces.txt'
11-15 14:06:17.247   926   939 I Process : Sending signal. PID: 3767 SIG: 3
,11-15 14:06:17.247  3767  3776 I art     : Thread[2,tid=3776,WaitingInMainSignalCatcherLoop,Thread*=0x7f72943000,peer=0x12c520a0,"Signal Catcher"]: reacting to signal 3
,11-15 14:06:17.248   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:17.325  3812  3823 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-15 14:06:17.325   926   939 I Process : Sending signal. PID: 3133 SIG: 3
,11-15 14:06:17.326  3133  3139 I art     : Thread[2,tid=3139,WaitingInMainSignalCatcherLoop,Thread*=0x7f72943000,peer=0x12c3a0a0,"Signal Catcher"]: reacting to signal 3
,11-15 14:06:17.327  3767  3776 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-15 14:06:17.512  3133  3139 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-15 14:06:18.033   926   930 I art     : Wrote stack traces to '/data/anr/traces.txt'
,11-15 14:06:18.249   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:19.250   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:20.251   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:20.548   926   939 E ActivityManager: ANR in com.test.thalitest
11-15 14:06:20.548   926   939 E ActivityManager: PID: 5586
11-15 14:06:20.548   926   939 E ActivityManager: Reason: Broadcast of Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.test.thalitest/io.jxcore.node.ConnectivityChangeListener (has extras) }
11-15 14:06:20.548   926   939 E ActivityManager: Load: 6.37 / 4.07 / 1.73
11-15 14:06:20.548   926   939 E ActivityManager: CPU usage from 55302ms to 0ms ago:
11-15 14:06:20.548   926   939 E ActivityManager:   0.6% 4/kworker/0:0: 0% user + 0.6% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0.6% 926/system_server: 0.1% user + 0.4% kernel / faults: 13 minor
11-15 14:06:20.548   926   939 E ActivityManager:   0.2% 388/msm_irqbalance: 0.1% user + 0.1% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0.1% 33/kworker/u16:1: 0% user + 0.1% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0.1% 45/kworker/u16:2: 0% user + 0.1% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0.1% 519/thermal-engine: 0% user + 0.1% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 292/msm-core:sampli: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 251/mmcqd/0: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 3585/com.google.process.gapps: 0% user + 0% kernel / faults: 296 minor
11-15 14:06:20.548   926   939 E ActivityManager:   0% 450/kworker/0:4: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 3661/com.google.android.inputmethod.latin: 0% user + 0% kernel / faults: 27 minor
11-15 14:06:20.548   926   939 E ActivityManager:   0% 8/rcu_preempt: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 12/ksoftirqd/1: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 30/kworker/1:1H: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 37/kworker/u17:1: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 39/irq/51-cpr: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 214/kworker/3:2: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 242/cfinteractive: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 349/logd: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 438/irq/215-fc38800: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   0% 503/adbd: 0% user + 0% kernel / faults: 8 minor
11-15 14:06:20.548   926   939 E ActivityManager:   0% 536/ATFWD-daemon: 0% user + 0% kernel / faults: 4 minor
11-15 14:06:20.548   926   939 E ActivityManager:   0% 5781/com.android.bluetooth: 0% user + 0% kernel / faults: 1271 minor
11-15 14:06:20.548   926   939 E ActivityManager:   0% 5841/wpa_supplicant: 0% user + 0% kernel
11-15 14:06:20.548   926   939 E ActivityManager: 1.5% TOTAL: 0% user + 0.1% kernel + 0% iowait + 0.3% irq + 0.9% softirq
11-15 14:06:20.548   926   939 E ActivityManager: CPU usage from 3299ms to 3819ms later:
11-15 14:06:20.548   926   939 E ActivityManager:   3.7% 926/system_server: 0% user + 3.7% kernel / faults: 1 minor
11-15 14:06:20.548   926   939 E ActivityManager:     5.6% 939/ActivityManager: 0% user + 5.6% kernel
11-15 14:06:20.548   926   939 E ActivityManager:   1.5% 388/msm_irqbalance: 0% user + 1.5% kernel
11-15 14:06:20.548   926   939 E ActivityManager: 1.2% TOTAL: 0.2% user + 0.9% kernel
,11-15 14:06:20.588   408   408 W Binder_2: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[31586]" dev="sockfs" ino=31586 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 14:06:20.588   408   408 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[31586]" dev="sockfs" ino=31586 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 14:06:20.592   408   408 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33205]" dev="sockfs" ino=33205 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 14:06:20.592   408   408 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33205]" dev="sockfs" ino=33205 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 14:06:20.595   926  5875 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-15 14:06:20.706   926  5875 I OpenGLRenderer: Initialized EGL, version 1.4
,11-15 14:06:21.252   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:21.741   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=233157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-15 14:06:21.786  5781  5781 D BtGatt.ScanManager: awakened up at time 233202
,11-15 14:06:21.787  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:06:21.804  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-15 14:06:21.804  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:06:21.804  5781  5799 D BtGatt.GattService: current time is 233220489267
11-15 14:06:21.804  5781  5799 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -85, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -86, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -91, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -77, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:06:21.804  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:06:21.805  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:06:21.805  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:06:21.805  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:06:21.805  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:06:21.805  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:06:22.252   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-15 14:06:26.809  5781  5781 D BtGatt.ScanManager: awakened up at time 238225
,11-15 14:06:26.811  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:06:26.849  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:06:26.849  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:06:26.849  5781  5799 D BtGatt.GattService: current time is 238265424518
11-15 14:06:26.849  5781  5799 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -80, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -88, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 85, -113, -37, 31, -33, 8, 0, 4, -87, 87, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -91, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -77, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:06:26.849  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:06:26.850  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:06:26.850  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:06:26.850  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:06:26.850  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:06:26.851  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:06:26.851  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:06:27.254   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:28.256   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:29.257   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:30.259   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:31.260   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:31.856  5781  5781 D BtGatt.ScanManager: awakened up at time 243272
,11-15 14:06:31.858  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:06:31.895  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:06:31.895  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:06:31.896  5781  5799 D BtGatt.GattService: current time is 243312188377
,11-15 14:06:31.896  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -96, 76, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -86, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -91, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -78, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -92, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:06:31.896  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:06:31.896  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:06:31.897  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:06:31.897  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:06:31.898  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:06:31.898  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-15 14:06:31.899  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:06:32.261   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-15 14:06:36.906  5781  5781 D BtGatt.ScanManager: awakened up at time 248322
11-15 14:06:36.907  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:06:36.930  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 14:06:36.930  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:06:36.931  5781  5799 D BtGatt.GattService: current time is 248347229914
11-15 14:06:36.931  5781  5799 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -88, 1, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -78, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -85, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -87, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:06:36.931  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:06:36.931  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:06:36.932  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:06:36.932  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:06:36.932  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:06:36.932  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:06:41.974  5781  5781 D BtGatt.ScanManager: awakened up at time 253390
,11-15 14:06:41.975  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:06:42.006  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:06:42.006  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:06:42.007  5781  5799 D BtGatt.GattService: current time is 253423804792
,11-15 14:06:42.008  5781  5799 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -79, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, 4, -87, 81, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 116, -43, -111, -91, -20, -29, 1, -128, -88, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -78, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:06:42.009  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:06:42.009  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:06:42.010  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:06:42.010  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:06:42.010  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:06:42.010  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:06:42.010  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:06:42.263   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:43.264   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:44.265   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:45.267   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:46.268   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:06:47.029  5781  5781 D BtGatt.ScanManager: awakened up at time 258445
,11-15 14:06:47.031  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:06:47.053  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-15 14:06:47.053  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:06:47.053  5781  5799 D BtGatt.GattService: current time is 258470052796
11-15 14:06:47.054  5781  5799 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -77, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -89, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, 4, -98, 6, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -92, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -86, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:06:47.054  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:06:47.054  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:06:47.054  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:06:47.055  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:06:47.055  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:06:47.055  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:06:47.269   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-15 14:06:52.083  5781  5781 D BtGatt.ScanManager: awakened up at time 263499
11-15 14:06:52.085  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:06:52.116  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:06:52.116  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:06:52.116  5781  5799 D BtGatt.GattService: current time is 263532766217
,11-15 14:06:52.117  5781  5799 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -86, 96, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -86, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -93, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -78, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -86, 8, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:06:52.117  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:06:52.118  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:06:52.118  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:06:52.119  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:06:52.119  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:06:52.119  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:06:52.120  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,11-15 14:06:57.142  5781  5781 D BtGatt.ScanManager: awakened up at time 268559
,11-15 14:06:57.145  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:06:57.174  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:06:57.174  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:06:57.174  5781  5799 D BtGatt.GattService: current time is 268590965461
,11-15 14:06:57.175  5781  5799 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -79, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -89, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 85, -113, -37, 31, -33, 8, 0, 4, -87, 87, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -85, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -78, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -80, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:06:57.175  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:06:57.175  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:06:57.175  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:06:57.176  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:06:57.176  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:06:57.176  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:06:57.176  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:06:59.996   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271411, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-15 14:07:02.200  5781  5781 D BtGatt.ScanManager: awakened up at time 273616
,11-15 14:07:02.202  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:07:02.230  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 14:07:02.230  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:07:02.231  5781  5799 D BtGatt.GattService: current time is 273647161019
11-15 14:07:02.231  5781  5799 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -87, 100, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -78, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -91, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -84, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:07:02.231  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:07:02.231  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:07:02.232  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:07:02.232  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:07:02.232  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:07:02.232  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:07:02.270   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:07:03.271   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:07:04.273   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:07:05.274   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:07:06.276   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:07:07.236  5781  5781 D BtGatt.ScanManager: awakened up at time 278652
,11-15 14:07:07.238  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:07:07.277   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-15 14:07:07.284  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:07:07.285  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:07:07.285  5781  5799 D BtGatt.GattService: current time is 278701469473
11-15 14:07:07.286  5781  5799 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -80, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -88, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -91, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -77, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -87, 2, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:07:07.286  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:07:07.287  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:07:07.287  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:07:07.288  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:07:07.288  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:07:07.292  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:07:07.293  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,11-15 14:07:12.291  5781  5781 D BtGatt.ScanManager: awakened up at time 283707
,11-15 14:07:12.293  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:07:12.330  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 14:07:12.330  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:07:12.330  5781  5799 D BtGatt.GattService: current time is 283746963343
,11-15 14:07:12.331  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, 4, -95, 4, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -77, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:07:12.331  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:07:12.332  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:07:12.332  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:07:12.332  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:07:12.333  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:07:12.333  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:07:14.409   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=285825, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-15 14:07:17.346  5781  5781 D BtGatt.ScanManager: awakened up at time 288762
,11-15 14:07:17.348  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:07:17.371  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 14:07:17.371  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:07:17.371  5781  5799 D BtGatt.GattService: current time is 288787957875
11-15 14:07:17.372  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -84, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, -128, -99, 6, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -92, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:07:17.372  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:07:17.372  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:07:17.372  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:07:17.372  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:07:17.373  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:07:17.373  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:07:22.400  5781  5781 D BtGatt.ScanManager: awakened up at time 293816
,11-15 14:07:22.401  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:07:22.430  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:07:22.431  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:07:22.431  5781  5799 D BtGatt.GattService: current time is 293847265026
11-15 14:07:22.431  5781  5799 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -89, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -77, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -91, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -80, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -79, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, 4, -87, 8, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:07:22.431  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:07:22.432  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:07:22.432  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:07:22.432  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:07:22.432  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:07:22.432  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:07:22.432  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:07:27.278   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:07:27.452  5781  5781 D BtGatt.ScanManager: awakened up at time 298868
,11-15 14:07:27.455  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:07:27.483  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:07:27.483  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:07:27.483  5781  5799 D BtGatt.GattService: current time is 298899878831
11-15 14:07:27.484  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, 4, -95, 9, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -78, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -87, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -89, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -77, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:07:27.484  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:07:27.484  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:07:27.484  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:07:27.485  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:07:27.485  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:07:27.485  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:07:27.485  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:07:28.279   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:07:29.281   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:07:30.282   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:07:31.284   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:07:32.285   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-15 14:07:32.510  5781  5781 D BtGatt.ScanManager: awakened up at time 303926
,11-15 14:07:32.513  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:07:32.540  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:07:32.540  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:07:32.541  5781  5799 D BtGatt.GattService: current time is 303957115691
11-15 14:07:32.541  5781  5799 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -99, 99, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, -46, -4, -117, 6, 105, -37, 1, -128, -84, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:07:32.541  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:07:32.541  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:07:32.542  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:07:32.542  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:07:32.542  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:07:32.542  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:07:32.542  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:07:37.569  5781  5781 D BtGatt.ScanManager: awakened up at time 308985
,11-15 14:07:37.570  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:07:37.600  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:07:37.600  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:07:37.600  5781  5799 D BtGatt.GattService: current time is 309016958971
11-15 14:07:37.601  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -91, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, 4, -87, 3, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -89, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -79, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:07:37.601  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:07:37.601  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:07:37.601  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:07:37.602  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:07:37.602  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:07:37.602  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:07:37.602  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:07:42.623  5781  5781 D BtGatt.ScanManager: awakened up at time 314039
,11-15 14:07:42.624  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:07:42.655  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:07:42.655  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:07:42.657  5781  5799 D BtGatt.GattService: current time is 314073517799
,11-15 14:07:42.657  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -97, 16, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -80, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:07:42.658  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:07:42.658  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:07:42.659  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:07:42.659  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:07:42.659  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:07:42.659  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:07:42.659  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:07:47.679  5781  5781 D BtGatt.ScanManager: awakened up at time 319095
,11-15 14:07:47.680  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:07:47.704  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-15 14:07:47.704  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:07:47.704  5781  5799 D BtGatt.GattService: current time is 319120769751
11-15 14:07:47.704  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 100, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -85, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -95, 95, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 37, -47, 14, -113, 116, -46, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:07:47.705  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:07:47.705  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-15 14:07:47.705  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:07:47.705  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:07:47.705  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:07:52.582   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=323997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-15 14:07:52.733  5781  5781 D BtGatt.ScanManager: awakened up at time 324149
11-15 14:07:52.734  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:07:52.760  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-15 14:07:52.760  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:07:52.761  5781  5799 D BtGatt.GattService: current time is 324177148066
,11-15 14:07:52.761  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -77, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -87, 19, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -90, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -89, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:07:52.761  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:07:52.761  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:07:52.762  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:07:52.762  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:07:52.762  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:07:52.762  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:07:57.286   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-15 14:07:57.286   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-15 14:07:57.792  5781  5781 D BtGatt.ScanManager: awakened up at time 329208
,11-15 14:07:57.794  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:07:57.825  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:07:57.825  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:07:57.825  5781  5799 D BtGatt.GattService: current time is 329241571531
,11-15 14:07:57.825  5781  5799 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -87, 98, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -80, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -87, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -77, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:07:57.826  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:07:57.826  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:07:57.826  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:07:57.826  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:07:57.826  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:07:57.826  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:07:57.827  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:08:02.852  5781  5781 D BtGatt.ScanManager: awakened up at time 334268
,11-15 14:08:02.854  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:08:02.879  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-15 14:08:02.879  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:08:02.879  5781  5799 D BtGatt.GattService: current time is 334296067581
,11-15 14:08:02.880  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -92, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -85, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -85, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -86, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:08:02.880  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:08:02.880  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:08:02.880  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:08:02.881  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:08:02.881  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:08:02.881  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:08:05.916   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=337331, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-15 14:08:07.885  5781  5781 D BtGatt.ScanManager: awakened up at time 339301
,11-15 14:08:07.887  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:08:07.915  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 14:08:07.916  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:08:07.916  5781  5799 D BtGatt.GattService: current time is 339332310827
11-15 14:08:07.916  5781  5799 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -86, 3, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -77, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -92, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -89, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:08:07.916  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:08:07.917  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:08:07.917  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:08:07.917  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:08:07.917  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:08:07.918  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:08:12.288   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:12.921  5781  5781 D BtGatt.ScanManager: awakened up at time 344337
,11-15 14:08:12.923  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:08:12.961  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:08:12.962  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:08:12.962  5781  5799 D BtGatt.GattService: current time is 344378400552
11-15 14:08:12.962  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, -128, -98, 16, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 81, 34, 97, 112, -14, -5, 1, -128, -82, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -77, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -89, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -84, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -88, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:08:12.963  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:08:12.963  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:08:12.964  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:08:12.964  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:08:12.965  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:08:12.965  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-15 14:08:12.965  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:08:13.289   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:14.292   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:15.293   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:16.295   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:17.296   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-15 14:08:17.969  5781  5781 D BtGatt.ScanManager: awakened up at time 349385
,11-15 14:08:17.971  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:08:17.994  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-15 14:08:17.994  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:08:17.994  5781  5799 D BtGatt.GattService: current time is 349410574575
11-15 14:08:17.994  5781  5799 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -85, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -85, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -86, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -92, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:08:17.994  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:08:17.995  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:08:17.995  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:08:17.995  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:08:17.995  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:08:17.995  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:08:22.299   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:23.026  5781  5781 D BtGatt.ScanManager: awakened up at time 354442
,11-15 14:08:23.027  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:08:23.051  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-15 14:08:23.051  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:08:23.051  5781  5799 D BtGatt.GattService: current time is 354468076091
11-15 14:08:23.052  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -92, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -87, 9, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -79, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:08:23.052  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:08:23.052  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:08:23.052  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:08:23.053  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:08:23.053  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:08:23.300   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:24.302   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:25.303   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:26.305   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:27.306   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-15 14:08:28.085  5781  5781 D BtGatt.ScanManager: awakened up at time 359501
,11-15 14:08:28.088  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:08:28.110  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:08:28.110  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:08:28.110  5781  5799 D BtGatt.GattService: current time is 359526942757
11-15 14:08:28.111  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -99, 10, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 37, -47, 14, -113, 116, -46, 1, -128, -87, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -77, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -90, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:08:28.111  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:08:28.111  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:08:28.111  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:08:28.112  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:08:28.112  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:08:28.112  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:08:28.112  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:08:33.139  5781  5781 D BtGatt.ScanManager: awakened up at time 364555
,11-15 14:08:33.141  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:08:33.163  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:08:33.163  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:08:33.164  5781  5799 D BtGatt.GattService: current time is 364580178973
,11-15 14:08:33.164  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -93, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -92, 12, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 71, -122, -77, 84, 69, -12, 1, -128, -86, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -86, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:08:33.164  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:08:33.165  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:08:33.165  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:08:33.166  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:08:33.167  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:08:33.168  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:08:33.168  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:08:37.307   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:38.192  5781  5781 D BtGatt.ScanManager: awakened up at time 369608
,11-15 14:08:38.193  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:08:38.218  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:08:38.218  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:08:38.218  5781  5799 D BtGatt.GattService: current time is 369634739993
,11-15 14:08:38.218  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -77, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -78, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -88, 3, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -80, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -91, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -84, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -89, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:08:38.219  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:08:38.219  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:08:38.219  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:08:38.219  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:08:38.220  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:08:38.220  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,11-15 14:08:38.220  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:08:38.308   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:39.310   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:40.311   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:41.313   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:42.314   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-15 14:08:43.248  5781  5781 D BtGatt.ScanManager: awakened up at time 374664
,11-15 14:08:43.250  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:08:43.272  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:08:43.272  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:08:43.273  5781  5799 D BtGatt.GattService: current time is 374689162853
11-15 14:08:43.273  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, -128, -96, 27, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 81, 34, 97, 112, -14, -5, 1, -128, -83, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -86, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -89, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:08:43.273  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:08:43.274  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:08:43.274  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:08:43.274  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:08:43.274  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:08:43.274  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:08:43.274  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:08:44.101   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=375517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-15 14:08:48.307  5781  5781 D BtGatt.ScanManager: awakened up at time 379723
,11-15 14:08:48.308  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:08:48.333  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 14:08:48.334  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:08:48.334  5781  5799 D BtGatt.GattService: current time is 379750338598
11-15 14:08:48.334  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -93, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -84, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:08:48.334  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:08:48.335  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:08:48.335  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:08:48.335  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:08:48.335  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:08:48.335  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:08:53.365  5781  5781 D BtGatt.ScanManager: awakened up at time 384781
,11-15 14:08:53.367  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:08:53.396  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:08:53.397  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:08:53.397  5781  5799 D BtGatt.GattService: current time is 384813291152
11-15 14:08:53.397  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -77, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -88, 9, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -79, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -89, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -80, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -92, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:08:53.397  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:08:53.398  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:08:53.398  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:08:53.398  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:08:53.398  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:08:53.399  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:08:53.399  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:08:57.315   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:58.316   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:08:58.419  5781  5781 D BtGatt.ScanManager: awakened up at time 389835
,11-15 14:08:58.420  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:08:58.444  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:08:58.444  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:08:58.444  5781  5799 D BtGatt.GattService: current time is 389860723589
11-15 14:08:58.444  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -99, 12, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, -46, -4, -117, 6, 105, -37, 1, -128, -78, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -87, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -77, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -89, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:08:58.445  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:08:58.445  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:08:58.445  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:08:58.445  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:08:58.445  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:08:58.446  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:08:58.446  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12,, -74, 71, -122, -77, 84]
,11-15 14:08:59.318   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:09:00.319   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:09:01.321   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:09:02.322   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-15 14:09:03.485  5781  5781 D BtGatt.ScanManager: awakened up at time 394901
,11-15 14:09:03.487  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:09:03.511  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:09:03.512  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:09:03.512  5781  5799 D BtGatt.GattService: current time is 394928336040
11-15 14:09:03.512  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -92, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, -128, -98, 24, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:09:03.512  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:09:03.512  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:09:03.513  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:09:03.513  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:09:03.513  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:09:03.513  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:09:03.513  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -7,4, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:09:08.515  5781  5781 D BtGatt.ScanManager: awakened up at time 399931
,11-15 14:09:08.518  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:09:08.552  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:09:08.552  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:09:08.552  5781  5799 D BtGatt.GattService: current time is 399968594390
,11-15 14:09:08.552  5781  5799 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -89, 15, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -78, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -88, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -80, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -90, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:09:08.553  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:09:08.553  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:09:08.553  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:09:08.553  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:09:08.554  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:09:08.554  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:09:08.554  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:09:13.559  5781  5781 D BtGatt.ScanManager: awakened up at time 404975
11-15 14:09:13.561  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:09:13.597  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:09:13.598  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:09:13.598  5781  5799 D BtGatt.GattService: current time is 405014555514
11-15 14:09:13.599  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, -128, -97, 28, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -90, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:09:13.599  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 14:09:13.600  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:09:13.600  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:09:13.601  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:09:13.601  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:09:13.601  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:09:13.602  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:09:18.603  5781  5781 D BtGatt.ScanManager: awakened up at time 410019
,11-15 14:09:18.605  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:09:18.625  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 14:09:18.625  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:09:18.625  5781  5799 D BtGatt.GattService: current time is 410041840123
11-15 14:09:18.625  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -86, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -99, 30, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 71, -122, -77, 84, 69, -12, 1, -128, -86, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -92, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:09:18.626  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:09:18.626  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:09:18.626  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:09:18.626  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:09:18.626  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:09:18.626  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:09:22.325   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:09:22.715   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=414131, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-15 14:09:23.327   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:09:23.655  5781  5781 D BtGatt.ScanManager: awakened up at time 415071
,11-15 14:09:23.657  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:09:23.680  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:09:23.681  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:09:23.681  5781  5799 D BtGatt.GattService: current time is 415097321244
,11-15 14:09:23.681  5781  5799 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -98, 20, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -90, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -93, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -84, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -89, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -79, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:09:23.681  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:09:23.682  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:09:23.682  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-15 14:09:23.682  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,11-15 14:09:23.682  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:09:23.682  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:09:23.682  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:09:24.328   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:09:25.330   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:09:26.332   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:09:27.333   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-15 14:09:28.709  5781  5781 D BtGatt.ScanManager: awakened up at time 420125
,11-15 14:09:28.712  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:09:28.734  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-15 14:09:28.734  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:09:28.734  5781  5799 D BtGatt.GattService: current time is 420150612665
11-15 14:09:28.734  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -89, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -81, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,11-15 14:09:28.735  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:09:28.735  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:09:28.735  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:09:28.735  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:09:28.735  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,11-15 14:09:33.759  5781  5781 D BtGatt.ScanManager: awakened up at time 425175
,11-15 14:09:33.761  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:09:33.805  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:09:33.805  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:09:33.805  5781  5799 D BtGatt.GattService: current time is 425222023812
11-15 14:09:33.806  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -98, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -86, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -92, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, -128, -99, 25, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0]
,11-15 14:09:33.806  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:09:33.806  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:09:33.806  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:09:33.807  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:09:33.807  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:09:33.807  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:09:33.807  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,11-15 14:09:38.812  5781  5781 D BtGatt.ScanManager: awakened up at time 430228
,11-15 14:09:38.813  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:09:38.837  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-15 14:09:38.837  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:09:38.837  5781  5799 D BtGatt.GattService: current time is 430253653906
11-15 14:09:38.837  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -91, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -79, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -86, 15, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -82, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -83, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:09:38.838  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:09:38.838  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:09:38.838  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:09:38.838  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 14:09:38.838  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:09:43.866  5781  5781 D BtGatt.ScanManager: awakened up at time 435282
,11-15 14:09:43.867  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:09:43.890  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:09:43.891  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:09:43.891  5781  5799 D BtGatt.GattService: current time is 435307414419
11-15 14:09:43.891  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, -128, -97, 18, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 71, -122, -77, 84, 69, -12, 1, -128, -91, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:09:43.891  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:09:43.892  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:09:43.892  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:09:43.892  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:09:43.892  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:09:43.892  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:09:43.892  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:09:48.919  5781  5781 D BtGatt.ScanManager: awakened up at time 440335
,11-15 14:09:48.921  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:09:48.943  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 14:09:48.944  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:09:48.944  5781  5799 D BtGatt.GattService: current time is 440360496668
11-15 14:09:48.944  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -85, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -85, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -86, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -92, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:09:48.944  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:09:48.945  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:09:48.945  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:09:48.945  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:09:48.945  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:09:48.945  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:09:52.334   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-15 14:09:52.334   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-15 14:09:53.972  5781  5781 D BtGatt.ScanManager: awakened up at time 445388
,11-15 14:09:53.973  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:09:54.005  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:09:54.005  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:09:54.006  5781  5799 D BtGatt.GattService: current time is 445422137314
11-15 14:09:54.006  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -77, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -91, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -79, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -85, 22, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -80, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -88, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:09:54.006  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:09:54.006  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:09:54.007  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:09:54.007  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:09:54.007  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:09:54.007  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:09:54.007  5781,  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:09:59.025  5781  5781 D BtGatt.ScanManager: awakened up at time 450441
,11-15 14:09:59.026  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:09:59.050  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:09:59.050  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:09:59.050  5781  5799 D BtGatt.GattService: current time is 450466938975
11-15 14:09:59.051  5781  5799 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -94, 35, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, -46, -4, -117, 6, 105, -37, 1, -128, -78, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -91, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -77, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -87, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -81, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:09:59.051  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:09:59.051  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:09:59.051  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:09:59.052  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:09:59.052  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:09:59.052  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:09:59.052  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:10:00.903   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=452319, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-15 14:10:04.079  5781  5781 D BtGatt.ScanManager: awakened up at time 455495
,11-15 14:10:04.080  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:10:04.104  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 14:10:04.104  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:10:04.104  5781  5799 D BtGatt.GattService: current time is 455520707698
11-15 14:10:04.104  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -92, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -85, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -87, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:10:04.105  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:10:04.105  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:10:04.105  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:10:04.105  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:10:04.105  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:10:04.106  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:10:09.109  5781  5781 D BtGatt.ScanManager: awakened up at time 460525
,11-15 14:10:09.112  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:10:09.154  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:10:09.154  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:10:09.154  5781  5799 D BtGatt.GattService: current time is 460570544209
11-15 14:10:09.154  5781  5799 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -86, 27, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -77, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -91, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -80, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -80, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -89, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:10:09.155  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,11-15 14:10:09.155  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:10:09.156  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:10:09.156  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:10:09.156  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:10:09.157  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:10:09.157  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:10:12.336   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:13.338   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:14.159  5781  5781 D BtGatt.ScanManager: awakened up at time 465575
,11-15 14:10:14.165  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:10:14.214  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:10:14.214  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:10:14.215  5781  5799 D BtGatt.GattService: current time is 465631254061
11-15 14:10:14.215  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -98, 29, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -90, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -77, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -80, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -87, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:10:14.216  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 14:10:14.216  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:10:14.216  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:10:14.217  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:10:14.217  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:10:14.219  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:10:14.222  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:10:14.339   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:15.341   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:16.342   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:17.344   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-15 14:10:19.218  5781  5781 D BtGatt.ScanManager: awakened up at time 470634
,11-15 14:10:19.221  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:10:19.236  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-15 14:10:19.236  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:10:19.236  5781  5799 D BtGatt.GattService: current time is 470653053130
11-15 14:10:19.237  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -93, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:10:19.237  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:10:19.237  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:10:21.701   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=473117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-15 14:10:22.345   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:23.347   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:24.268  5781  5781 D BtGatt.ScanManager: awakened up at time 475684
11-15 14:10:24.269  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:10:24.299  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:10:24.300  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:10:24.300  5781  5799 D BtGatt.GattService: current time is 475716292896
11-15 14:10:24.300  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -77, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -91, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, 4, -86, 34, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -79, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -88, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:10:24.300  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:10:24.301  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:10:24.301  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:10:24.301  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:10:24.301  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:10:24.301  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:10:24.302  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:10:24.348   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:25.349   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:26.351   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:27.352   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-15 14:10:29.322  5781  5781 D BtGatt.ScanManager: awakened up at time 480738
,11-15 14:10:29.323  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:10:29.353  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:10:29.354  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:10:29.354  5781  5799 D BtGatt.GattService: current time is 480770301027
,11-15 14:10:29.355  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -81, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -97, 36, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -87, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -90, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -77, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:10:29.355  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:10:29.356  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:10:29.356  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:10:29.356  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:10:29.356  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:10:29.357  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:10:29.357  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:10:34.375  5781  5781 D BtGatt.ScanManager: awakened up at time 485791
,11-15 14:10:34.376  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:10:34.399  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 14:10:34.399  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:10:34.399  5781  5799 D BtGatt.GattService: current time is 485815667607
11-15 14:10:34.399  5781  5799 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -85, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -94, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -86, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 85, -113, -37, 31, -33, 8, 0, 4, -100, 27, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:10:34.400  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:10:34.400  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:10:34.400  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:10:34.400  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:10:34.401  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,11-15 14:10:34.401  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,11-15 14:10:37.354   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:38.355   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:39.357   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:39.432  5781  5781 D BtGatt.ScanManager: awakened up at time 490848
,11-15 14:10:39.434  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:10:39.460  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:10:39.460  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:10:39.460  5781  5799 D BtGatt.GattService: current time is 490877099434
11-15 14:10:39.461  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -77, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -87, 29, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -79, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -89, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -90, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -84, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:10:39.461  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:10:39.461  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:10:39.462  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:10:39.462  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:10:39.462  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,11-15 14:10:39.462  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:10:39.462  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:10:40.358   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:41.360   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:42.361   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-15 14:10:44.485  5781  5781 D BtGatt.ScanManager: awakened up at time 495902
,11-15 14:10:44.487  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:10:44.519  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:10:44.519  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:10:44.519  5781  5799 D BtGatt.GattService: current time is 495935742336
11-15 14:10:44.520  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, 4, -96, 53, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -78, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -88, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -90, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:10:44.520  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:10:44.520  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:10:44.521  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:10:44.521  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:10:44.521  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:10:44.521  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:10:44.521  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:10:49.545  5781  5781 D BtGatt.ScanManager: awakened up at time 500961
11-15 14:10:49.547  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:10:49.570  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:10:49.570  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:10:49.570  5781  5799 D BtGatt.GattService: current time is 500986605692
11-15 14:10:49.570  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -85, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -92, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, -128, -100, 44, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 71, -122, -77, 84, 69, -12, 1, -128, -86, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -86, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:10:49.571  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:10:49.571  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:10:49.571  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:10:49.571  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:10:49.572  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:10:49.572  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:10:49.572  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:10:54.598  5781  5781 D BtGatt.ScanManager: awakened up at time 506014
,11-15 14:10:54.599  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:10:54.623  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-15 14:10:54.623  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:10:54.623  5781  5799 D BtGatt.GattService: current time is 506039716179
11-15 14:10:54.623  5781  5799 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -92, 35, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -78, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -88, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -79, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:10:54.624  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:10:54.624  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:10:54.624  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:10:54.624  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:10:54.625  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:10:54.625  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:10:57.363   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:58.364   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:59.366   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:10:59.659  5781  5781 D BtGatt.ScanManager: awakened up at time 511075
,11-15 14:10:59.660  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:10:59.683  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:10:59.684  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:10:59.684  5781  5799 D BtGatt.GattService: current time is 511100425351
11-15 14:10:59.684  5781  5799 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, -128, -96, 59, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, -46, -4, -117, 6, 105, -37, 1, -128, -78, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -88, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -77, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -89, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:10:59.684  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:10:59.685  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:10:59.685  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:10:59.685  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:10:59.685  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:10:59.685  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:10:59.685  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:10:59.888   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=511304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-15 14:11:00.368   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:11:01.369   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:11:02.370   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-15 14:11:04.712  5781  5781 D BtGatt.ScanManager: awakened up at time 516128
,11-15 14:11:04.715  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:11:04.738  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:11:04.738  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:11:04.738  5781  5799 D BtGatt.GattService: current time is 516154577265
11-15 14:11:04.738  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -85, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -92, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -86, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -86, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, -128, -96, 51, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:11:04.739  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:11:04.739  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:11:04.739  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:11:04.739  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:11:04.739  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:11:04.740  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:11:04.740  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14,, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:11:09.742  5781  5781 D BtGatt.ScanManager: awakened up at time 521158
,11-15 14:11:09.746  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:11:09.786  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:11:09.786  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:11:09.786  5781  5799 D BtGatt.GattService: current time is 521203042477
11-15 14:11:09.787  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -90, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, 4, -86, 40, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -77, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -88, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -79, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:11:09.787  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:11:09.788  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:11:09.788  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:11:09.788  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:11:09.788  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:11:09.789  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:11:09.789  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:11:14.792  5781  5781 D BtGatt.ScanManager: awakened up at time 526208
,11-15 14:11:14.796  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:11:14.837  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-15 14:11:14.837  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:11:14.837  5781  5799 D BtGatt.GattService: current time is 526253863929
,11-15 14:11:14.838  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -90, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -88, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -77, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:11:14.838  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:11:14.839  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:11:14.839  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:11:14.839  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:11:14.840  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:11:14.840  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:11:18.235   926  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=529651, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-15 14:11:19.842  5781  5781 D BtGatt.ScanManager: awakened up at time 531258
,11-15 14:11:19.843  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:11:19.873  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:11:19.873  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:11:19.873  5781  5799 D BtGatt.GattService: current time is 531289529381
11-15 14:11:19.873  5781  5799 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -95, 44, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -83, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -86, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -92, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:11:19.874  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:11:19.874  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:11:19.874  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:11:19.874  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:11:19.875  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:11:19.875  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:11:19.875  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-15 14:11:22.372   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:11:23.374   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:11:24.375   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:11:24.895  5781  5781 D BtGatt.ScanManager: awakened up at time 536311
,11-15 14:11:24.896  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:11:24.927  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-15 14:11:24.927  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:11:24.927  5781  5799 D BtGatt.GattService: current time is 536343852361
11-15 14:11:24.928  5781  5799 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -90, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -82, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -94, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -84, 46, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -83, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -88, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -80, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:11:24.928  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:11:24.928  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:11:24.928  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:11:24.928  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-15 14:11:24.929  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:11:24.929  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:11:24.929  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-15 14:11:25.377   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:11:26.378   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:11:27.379   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-15 14:11:29.955  5781  5781 D BtGatt.ScanManager: awakened up at time 541371
,11-15 14:11:29.957  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:11:29.980  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-15 14:11:29.981  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:11:29.981  5781  5799 D BtGatt.GattService: current time is 541397262146
11-15 14:11:29.981  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, -128, -93, 48, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 71, -122, -77, 84, 69, -12, 1, -128, -90, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -77, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:11:29.981  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:11:29.982  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:11:29.982  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:11:29.982  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
11-15 14:11:29.982  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:11:29.982  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:11:29.982  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-15 14:11:35.012  5781  5781 D BtGatt.ScanManager: awakened up at time 546428
,11-15 14:11:35.015  5781  5802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:11:35.040  5781  5799 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-15 14:11:35.040  5781  5799 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:11:35.040  5781  5799 D BtGatt.GattService: current time is 546456679477
,11-15 14:11:35.040  5781  5799 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -87, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:11:35.041  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:11:35.041  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 14:11:35.041  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-15 14:11:35.041  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:11:35.041  5781  5799 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]

```
