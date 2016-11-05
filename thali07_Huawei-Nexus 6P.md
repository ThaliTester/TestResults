#### Test 924347211287328_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-05 01:44:19.426  3954  4210 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-05 01:44:19.515  3954  4210 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-05 01:44:19.878  5584  5584 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-05 01:44:19.883  5584  5584 D AndroidRuntime: CheckJNI is OFF
11-05 01:44:19.911  5584  5584 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-05 01:44:19.945  5584  5584 I Radio-JNI: register_android_hardware_Radio DONE
11-05 01:44:19.960  5584  5584 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-05 01:44:19.972   927  3396 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-05 01:44:19.991  5584  5584 D AndroidRuntime: Shutting down VM
11-05 01:44:19.996  3937  3949 W SearchService: Abort, client detached.
11-05 01:44:20.010  3937  3937 I HotwordDetector: Closing mic
11-05 01:44:20.012  3937  4199 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@5d2e7ae
11-05 01:44:20.012  3937  4206 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-05 01:44:20.027   927  3770 I ActivityManager: Start proc 5593:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-05 01:44:20.087   511  4208 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-05 01:44:20.088   511  4208 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-05 01:44:20.093   511  4208 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-05 01:44:20.093   511  4208 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-05 01:44:20.093   511  2999 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-05 01:44:20.096  3937  4202 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-05 01:44:20.096  3937  4205 I MicroRecognitionRnrImpl: Detection finished
11-05 01:44:20.139  5593  5593 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-05 01:44:20.170  5593  5593 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-05 01:44:20.227  5593  5593 I LibraryLoader: Time to load native libraries: 53 ms (timestamps 9433-9486)
,11-05 01:44:20.227  5593  5593 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-05 01:44:20.248  5593  5593 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9a9d7fe}
,11-05 01:44:20.248  5593  5593 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-05 01:44:20.249  5593  5593 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-05 01:44:20.254  5593  5593 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-05 01:44:20.255  5593  5593 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-05 01:44:20.295  5593  5593 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-05 01:44:20.308  5593  5593 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-05 01:44:20.308  5593  5593 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-05 01:44:20.308  5593  5593 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-05 01:44:20.308  5593  5593 I Adreno  : Build Date                       : 12/06/15
11-05 01:44:20.308  5593  5593 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-05 01:44:20.308  5593  5593 I Adreno  : Local Branch                     : mybranch17112971
11-05 01:44:20.308  5593  5593 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-05 01:44:20.308  5593  5593 I Adreno  : Remote Branch                    : NONE
11-05 01:44:20.308  5593  5593 I Adreno  : Reconstruct Branch               : NOTHING
,11-05 01:44:20.368   927   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@145e054:true
,11-05 01:44:20.406   408   408 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[31013]" dev="sockfs" ino=31013 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-05 01:44:20.406   408   408 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[31013]" dev="sockfs" ino=31013 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-05 01:44:20.418  5593  5593 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-05 01:44:20.427  5593  5593 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-05 01:44:20.452   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[30656]" dev="sockfs" ino=30656 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-05 01:44:20.452   408   408 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30656]" dev="sockfs" ino=30656 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-05 01:44:20.455  5593  5630 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-05 01:44:20.456  3770  3770 W Binder_7: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32804]" dev="sockfs" ino=32804 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-05 01:44:20.456  3770  3770 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32804]" dev="sockfs" ino=32804 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-05 01:44:20.460  5593  5617 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-05 01:44:20.486  5593  5630 I OpenGLRenderer: Initialized EGL, version 1.4
,11-05 01:44:20.566  3395  3395 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32459]" dev="sockfs" ino=32459 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-05 01:44:20.566  3395  3395 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32459]" dev="sockfs" ino=32459 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-05 01:44:20.571   927   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +570ms
11-05 01:44:20.569  3790  3790 W Binder_8: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32458]" dev="sockfs" ino=32458 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-05 01:44:20.569  3790  3790 W Binder_8: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32458]" dev="sockfs" ino=32458 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-05 01:44:20.572  3621  3621 I Keyboard.Facilitator: onFinishInput()
,11-05 01:44:20.599  5593  5593 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5593
,11-05 01:44:20.689  5593  5593 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-05 01:44:20.927  5593  5633 D jxcore_app_log: JniHelper::setJavaVM(0xf53fc000), pthread_self() = -584054480
,11-05 01:44:20.931  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-05 01:44:20.931  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-05 01:44:20.931  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-05 01:44:20.931  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-05 01:44:20.931  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-05 01:44:20.931  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63910ed added. We now have 1 listener(s)
,11-05 01:44:20.934  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-05 01:44:20.934  5593  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-05 01:44:20.935  5593  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-05 01:44:20.935  5593  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-05 01:44:20.937  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9842b70 added. We now have 1 listener(s)
11-05 01:44:20.937  5593  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-05 01:44:20.942   927  2953 D WifiService: New client listening to asynchronous messages
,11-05 01:44:20.947  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-05 01:44:20.947  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-05 01:44:20.947  5593  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-05 01:44:20.947  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-05 01:44:20.947  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-05 01:44:20.947  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-05 01:44:20.947  5593  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-05 01:44:20.949  5593  5633 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-05 01:44:21.072  5593  5593 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-05 01:44:21.422  5593  5602 I art     : Background sticky concurrent mark sweep GC freed 74710(7MB) AllocSpace objects, 16(1076KB) LOS objects, 24% free, 24MB/32MB, paused 2.055ms total 269.949ms
,11-05 01:44:22.792   927  2952 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-05 01:44:22.812  5593  5602 I art     : Background partial concurrent mark sweep GC freed 54591(6MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 1.335ms total 371.715ms
,11-05 01:44:23.451  5593  5640 W jxcore-log: Initializing JXcore engine
,11-05 01:44:23.452  5593  5640 W jxcore-log: JXcore engine is ready
,11-05 01:44:23.486  5640  5640 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11774 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-05 01:44:23.489  5640  5640 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13375]" dev="sockfs" ino=13375 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-05 01:44:23.489  5640  5640 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-05 01:44:23.489  5640  5640 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30632]" dev="sockfs" ino=30632 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-05 01:44:23.498  5593  5640 W jxcore-log: Starting JXcore engine
,11-05 01:44:23.533  3561  3561 I ConfigService: onDestroy
,11-05 01:44:23.550  5593  5640 W jxcore-log: Platform android
11-05 01:44:23.550  5593  5640 W jxcore-log: 
,11-05 01:44:23.550  5593  5640 W jxcore-log: Process ARCH arm
11-05 01:44:23.550  5593  5640 W jxcore-log: 
,11-05 01:44:23.731  5593  5640 I jxcore-log: JXcore Cordova bridge is ready!
11-05 01:44:23.731  5593  5640 I jxcore-log: 
,11-05 01:44:23.731  5593  5640 W jxcore-log: JXcore engine is started
,11-05 01:44:23.745  5593  5633 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
11-05 01:44:23.752  5593  5593 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-05 01:44:24.859   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:44:25.012   927  3770 I ActivityManager: Killing 5036:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-05 01:44:25.860   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:44:26.861   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:44:27.862   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:44:28.863   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:44:29.864   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-05 01:44:33.178  3937  5642 W CronetSyncConnectionRcs: Upload content type not set.
,11-05 01:44:33.248  4864  4894 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-05 01:44:33.250  4864  4864 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-05 01:44:33.253   927  3119 I ActivityManager: Killing 5380:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-05 01:44:33.591  5593  5640 I jxcore-log: 2016-11-05 00:44:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-05 01:44:33.591  5593  5640 I jxcore-log: 
,11-05 01:44:33.593  5593  5640 I jxcore-log: 2016-11-05 00:44:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-05 01:44:33.593  5593  5640 I jxcore-log: 
,11-05 01:44:33.598  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-05 01:44:33.598  5593  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-05 01:44:33.598  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:44:33.598  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:44:33.598  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-05 01:44:33.598  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-05 01:44:33.598  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
11-05 01:44:33.598  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-05 01:44:33.598  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-05 01:44:33.599  5593  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-05 01:44:33.601  5593  5640 I jxcore-log: 2016-11-05 00:44:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-05 01:44:33.601  5593  5640 I jxcore-log: 
11-05 01:44:33.603  5593  5640 I jxcore-log: 2016-11-05 00:44:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-05 01:44:33.603  5593  5640 I jxcore-log: 
,11-05 01:44:33.857  5593  5640 I jxcore-log: 2016-11-05 00:44:33 - DEBUG UnitTest_app: 'Running unit tests'
11-05 01:44:33.857  5593  5640 I jxcore-log: 
,11-05 01:44:33.858  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-05 01:44:33.858  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c026e9e added. We now have 2 listener(s)
11-05 01:44:33.859  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-05 01:44:33.859  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-05 01:44:33.859  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-05 01:44:33.859  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:44:33.859  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f16d7f added. We now have 2 listener(s)
11-05 01:44:33.859  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-05 01:44:33.860  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-05 01:44:33.861  5593  5640 D executeNativeTests: Running unit tests
,11-05 01:44:33.898  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-05 01:44:33.898  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c added. We now have 3 listener(s)
11-05 01:44:33.899  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-05 01:44:33.899  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-05 01:44:33.899  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-05 01:44:33.899  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-05 01:44:33.899  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 added. We now have 3 listener(s)
11-05 01:44:33.899  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-05 01:44:33.900  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-05 01:44:33.901  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-05 01:44:33.901  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-05 01:44:33.902  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-05 01:44:33.902  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-05 01:44:33.902  5593  5640 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-05 01:44:33.902  5593  5640 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-05 01:44:33.902  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-05 01:44:33.902  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-05 01:44:33.902  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-05 01:44:33.903  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-05 01:44:33.903  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-05 01:44:33.903  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:33.903  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:33.903  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:33.903  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-05 01:44:33.903  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-05 01:44:33.903  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c removed from the list
11-05 01:44:33.903  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:33.903  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 removed from the list
,11-05 01:44:33.904  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:33.904  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.904  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.904  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.904  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:33.904  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:33.904  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:33.904  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:33.904  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:33.905  5593  5640 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-05 01:44:33.905  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:33.905  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-05 01:44:33.906  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-05 01:44:33.906  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:33.906  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:33.906  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:33.906  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:33.906  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:33.906  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:33.906  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.906  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.906  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.906  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.906  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:33.906  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:33.907  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:33.907  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-05 01:44:33.909  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-05 01:44:33.910  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-05 01:44:33.910  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-05 01:44:33.910  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-05 01:44:33.910  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-05 01:44:33.910  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-05 01:44:33.910  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-05 01:44:33.910  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-05 01:44:33.910  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:33.910  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:33.910  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:33.910  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:33.910  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:33.910  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:33.910  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
,11-05 01:44:33.910  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:33.910  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.911  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.911  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.911  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.911  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:33.911  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:33.911  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:33.911  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:33.911  5593  5640 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-05 01:44:33.912  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-05 01:44:33.912  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-05 01:44:33.920  5593  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-05 01:44:33.920  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:44:33.920  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:44:33.920  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-05 01:44:33.920  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-05 01:44:33.920  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-05 01:44:33.920  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-05 01:44:33.920  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-05 01:44:33.923  5593  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-05 01:44:33.923  5593  5640 D io.jxcore.node.ConnectivityMonitor: start: OK
11-05 01:44:33.923  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-05 01:44:33.923  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-05 01:44:33.923  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-05 01:44:33.923  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-05 01:44:33.923  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-05 01:44:33.927  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-05 01:44:33.928  5593  5640 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-05 01:44:33.928  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:44:33.928  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-05 01:44:33.930  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:44:33.932  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.932  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-05 01:44:33.933  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-05 01:44:33.933  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-05 01:44:33.933  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-05 01:44:33.934  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-05 01:44:33.935  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-05 01:44:33.935  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.935  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-05 01:44:33.935  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-05 01:44:33.935  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-05 01:44:33.936  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-05 01:44:33.936  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.936  5593  5640 D BluetoothAdapter: STATE_ON
,11-05 01:44:33.943  4641  4837 D BtGatt.GattService: registerClient() - UUID=0ec6b33e-72ee-4621-9c22-521c03cf1fbe
11-05 01:44:33.944  4641  4700 D BtGatt.GattService: onClientRegistered() - UUID=0ec6b33e-72ee-4621-9c22-521c03cf1fbe, clientIf=5
11-05 01:44:33.944  5593  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-05 01:44:33.945  4641  4861 D BtGatt.GattService: start scan with filters
,11-05 01:44:33.950  4641  4703 D BtGatt.ScanManager: handling starting scan
,11-05 01:44:33.951  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-05 01:44:33.951  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.951  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-05 01:44:33.951  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.951  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-05 01:44:33.951  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-05 01:44:33.951  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-05 01:44:33.951  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-05 01:44:33.951  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-05 01:44:33.951  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-05 01:44:33.952  4641  4703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
11-05 01:44:33.952  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-05 01:44:33.952  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-05 01:44:33.952  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.952  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-05 01:44:33.953  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.953  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-05 01:44:33.953  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.953  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:33.954  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-05 01:44:33.954  5593  5640 I io.jxcore.node.ConnectionHelper: start: OK
,11-05 01:44:33.957  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-05 01:44:33.957  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-05 01:44:33.957  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-05 01:44:33.957  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-05 01:44:33.958  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-05 01:44:33.961  4641  4700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-05 01:44:33.961  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:33.962  4641  4703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-05 01:44:33.967  4641  4700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-05 01:44:33.967  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:33.968  4641  4703 D BtGatt.ScanManager: Starting BLE batch scan
11-05 01:44:33.968  4641  4703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-05 01:44:33.978  4641  4700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-05 01:44:33.978  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:44:33.984  4641  4700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-05 01:44:33.984  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:44:34.459  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-05 01:44:34.459  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-05 01:44:34.459  5593  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-05 01:44:38.958  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-05 01:44:38.958  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:38.958  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-05 01:44:38.959  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-05 01:44:38.959  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-05 01:44:38.959  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:38.959  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-05 01:44:38.959  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-05 01:44:38.959  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-05 01:44:38.959  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-05 01:44:38.960  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:38.960  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.961  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.961  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-05 01:44:38.961  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.962  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:44:38.962  4641  4837 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-05 01:44:38.963  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-05 01:44:38.964  4641  4703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-05 01:44:38.964  5593  5640 D BluetoothAdapter: STATE_ON
,11-05 01:44:38.966  4641  4654 D BtGatt.GattService: stopScan() - queue size =1
11-05 01:44:38.968  4641  4837 D BtGatt.GattService: unregisterClient() - clientIf=5
11-05 01:44:38.969  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-05 01:44:38.969  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.969  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-05 01:44:38.970  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:38.970  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.970  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.970  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.971  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-05 01:44:38.971  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.971  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:38.971  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.971  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-05 01:44:38.971  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-05 01:44:38.973  4641  4641 D BtGatt.ScanManager: awakened up at time 98232
11-05 01:44:38.977  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-05 01:44:38.978  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.983  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.983  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-05 01:44:38.984  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.984  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:38.984  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:38.984  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-05 01:44:38.984  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-05 01:44:38.984  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-05 01:44:38.984  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-05 01:44:38.984  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:38.984  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-05 01:44:38.984  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-05 01:44:38.984  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:38.985  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-05 01:44:38.985  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:38.985  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-05 01:44:38.985  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:38.985  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-05 01:44:38.985  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:38.985  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-05 01:44:38.985  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-05 01:44:38.985  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-05 01:44:38.985  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-05 01:44:38.987  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-05 01:44:38.987  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-05 01:44:38.987  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-05 01:44:38.987  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-05 01:44:38.987  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-05 01:44:38.998  4641  4700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-05 01:44:38.998  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:38.999  4641  4700 D BtGatt.GattService: current time is 98258863567
,11-05 01:44:38.999  4641  4700 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -87, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -80, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -88, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -82, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -86, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-05 01:44:39.003  4641  4700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-05 01:44:39.004  4641  4700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-05 01:44:39.004  4641  4700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-05 01:44:39.004  4641  4700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-05 01:44:39.005  4641  4700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-05 01:44:39.011  4641  4700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-05 01:44:39.011  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:39.012  4641  4703 D BtGatt.ScanManager: stopping BLe Batch
,11-05 01:44:39.019  4641  4700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-05 01:44:39.019  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:39.019  4641  4703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-05 01:44:39.025  4641  4700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-05 01:44:39.025  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:44:39.489  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-05 01:44:43.991  5593  5640 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-05 01:44:43.996  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-05 01:44:43.997  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-05 01:44:44.011  5593  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-05 01:44:44.011  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:44:44.011  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:44:44.011  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-05 01:44:44.011  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-05 01:44:44.011  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-05 01:44:44.011  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-05 01:44:44.011  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-05 01:44:44.015  5593  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-05 01:44:44.016  5593  5640 D io.jxcore.node.ConnectivityMonitor: start: OK
11-05 01:44:44.016  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-05 01:44:44.016  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-05 01:44:44.016  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-05 01:44:44.016  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-05 01:44:44.016  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-05 01:44:44.021  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:44:44.023  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-05 01:44:44.023  5593  5640 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-05 01:44:44.024  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-05 01:44:44.026  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-05 01:44:44.031  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:44.032  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-05 01:44:44.033  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-05 01:44:44.033  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-05 01:44:44.033  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-05 01:44:44.039  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:44.039  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-05 01:44:44.039  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-05 01:44:44.039  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-05 01:44:44.039  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-05 01:44:44.039  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.040  5593  5640 D BluetoothAdapter: STATE_ON
,11-05 01:44:44.044  4641  4654 D BtGatt.GattService: registerClient() - UUID=69660d33-981f-490e-b5e4-1e5f555f52f1
,11-05 01:44:44.045  4641  4700 D BtGatt.GattService: onClientRegistered() - UUID=69660d33-981f-490e-b5e4-1e5f555f52f1, clientIf=5
,11-05 01:44:44.046  5593  5604 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-05 01:44:44.046  4641  4837 D BtGatt.GattService: start scan with filters
11-05 01:44:44.051  4641  4703 D BtGatt.ScanManager: handling starting scan
11-05 01:44:44.052  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-05 01:44:44.053  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.053  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-05 01:44:44.053  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.053  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-05 01:44:44.053  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-05 01:44:44.053  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.053  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-05 01:44:44.054  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-05 01:44:44.054  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.054  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.054  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-05 01:44:44.055  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-05 01:44:44.055  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.059  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.059  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-05 01:44:44.059  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.060  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.060  5593  5640 I io.jxcore.node.ConnectionHelper: start: OK
11-05 01:44:44.060  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-05 01:44:44.064  4641  4700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-05 01:44:44.064  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:44:44.064  4641  4703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-05 01:44:44.067  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.067  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-05 01:44:44.068  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-05 01:44:44.068  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.068  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-05 01:44:44.070  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-05 01:44:44.070  5593  5640 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-05 01:44:44.071  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:44.071  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-05 01:44:44.071  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-05 01:44:44.071  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-05 01:44:44.071  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:44.071  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-05 01:44:44.071  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-05 01:44:44.071  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-05 01:44:44.071  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-05 01:44:44.071  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.072  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.072  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.072  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-05 01:44:44.072  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.072  4641  4700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-05 01:44:44.072  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:44.073  4641  4703 D BtGatt.ScanManager: Starting BLE batch scan
11-05 01:44:44.073  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:44:44.073  4641  4703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-05 01:44:44.073  4641  4654 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-05 01:44:44.074  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-05 01:44:44.075  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:44:44.076  4641  4861 D BtGatt.GattService: stopScan() - queue size =1
,11-05 01:44:44.077  4641  4653 D BtGatt.GattService: unregisterClient() - clientIf=5
11-05 01:44:44.078  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-05 01:44:44.078  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.078  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-05 01:44:44.078  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.078  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.078  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.078  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.078  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-05 01:44:44.079  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.079  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.080  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:44.080  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-05 01:44:44.080  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-05 01:44:44.081  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-05 01:44:44.082  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.083  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.083  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-05 01:44:44.084  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:44.084  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.084  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:44.084  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-05 01:44:44.084  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-05 01:44:44.084  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-05 01:44:44.084  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:44.084  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-05 01:44:44.084  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
,11-05 01:44:44.084  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-05 01:44:44.084  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:44.084  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.084  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:44.084  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:44.084  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-05 01:44:44.085  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-05 01:44:44.085  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-05 01:44:44.085  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.085  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.085  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-05 01:44:44.085  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.087  4641  4700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-05 01:44:44.087  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:44.088  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-05 01:44:44.088  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.088  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.088  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.088  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-05 01:44:44.089  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.091  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.091  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.092  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.092  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:44.092  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:44.092  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:44.092  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:44.093  5593  5640 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-05 01:44:44.096  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-05 01:44:44.096  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-05 01:44:44.096  4641  4700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-05 01:44:44.096  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:44.098  4641  4703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-05 01:44:44.102  5593  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-05 01:44:44.102  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:44:44.102  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:44:44.102  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-05 01:44:44.102  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-05 01:44:44.102  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-05 01:44:44.102  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-05 01:44:44.102  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-05 01:44:44.104  4641  4700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-05 01:44:44.104  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:44.104  5593  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-05 01:44:44.104  4641  4700 E BtGatt.ContextMap: Context not found for ID 5
11-05 01:44:44.104  5593  5640 D io.jxcore.node.ConnectivityMonitor: start: OK
11-05 01:44:44.104  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-05 01:44:44.104  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-05 01:44:44.104  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-05 01:44:44.104  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-05 01:44:44.104  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-05 01:44:44.107  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-05 01:44:44.107  5593  5640 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-05 01:44:44.108  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-05 01:44:44.108  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:44:44.111  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.112  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-05 01:44:44.112  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:44:44.112  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-05 01:44:44.112  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-05 01:44:44.112  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-05 01:44:44.113  4641  4700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-05 01:44:44.113  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:44.113  4641  4703 D BtGatt.ScanManager: stopping BLe Batch
,11-05 01:44:44.116  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.116  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-05 01:44:44.116  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-05 01:44:44.116  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-05 01:44:44.116  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-05 01:44:44.116  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.117  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:44:44.119  4641  4700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-05 01:44:44.119  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:44.119  4641  4703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-05 01:44:44.119  4641  4654 D BtGatt.GattService: registerClient() - UUID=d43d1fea-2a80-4f1f-a2e3-8eb4f63a1bd4
,11-05 01:44:44.119  4641  4700 D BtGatt.GattService: onClientRegistered() - UUID=d43d1fea-2a80-4f1f-a2e3-8eb4f63a1bd4, clientIf=5
11-05 01:44:44.120  5593  5604 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-05 01:44:44.120  4641  4861 D BtGatt.GattService: start scan with filters
,11-05 01:44:44.124  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-05 01:44:44.124  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:44.124  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-05 01:44:44.124  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.124  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-05 01:44:44.124  4641  4700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-05 01:44:44.124  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:44.124  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-05 01:44:44.124  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.124  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-05 01:44:44.124  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-05 01:44:44.125  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.125  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.125  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-05 01:44:44.125  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-05 01:44:44.125  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.126  4641  4703 D BtGatt.ScanManager: handling starting scan
11-05 01:44:44.127  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.127  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-05 01:44:44.127  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.127  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:44.127  5593  5640 I io.jxcore.node.ConnectionHelper: start: OK
11-05 01:44:44.128  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-05 01:44:44.130  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.130  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.130  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.130  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-05 01:44:44.130  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-05 01:44:44.134  4641  4700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-05 01:44:44.134  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:44.135  4641  4703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-05 01:44:44.140  4641  4700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-05 01:44:44.140  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:44.140  4641  4703 D BtGatt.ScanManager: Starting BLE batch scan
11-05 01:44:44.140  4641  4703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-05 01:44:44.149  4641  4700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-05 01:44:44.149  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:44:44.154  4641  4700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-05 01:44:44.154  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:44:44.632  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-05 01:44:44.632  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-05 01:44:44.632  5593  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-05 01:44:49.128  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:49.128  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-05 01:44:49.128  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-05 01:44:49.129  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-05 01:44:49.129  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-05 01:44:49.129  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:49.129  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-05 01:44:49.129  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-05 01:44:49.129  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-05 01:44:49.129  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-05 01:44:49.130  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.130  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.131  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.131  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-05 01:44:49.131  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.133  5593  5640 D BluetoothAdapter: STATE_ON
,11-05 01:44:49.134  4641  4837 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-05 01:44:49.135  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-05 01:44:49.136  4641  4703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-05 01:44:49.136  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:44:49.138  4641  4654 D BtGatt.GattService: stopScan() - queue size =1
11-05 01:44:49.140  4641  4861 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-05 01:44:49.141  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-05 01:44:49.141  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.142  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-05 01:44:49.142  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.142  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.142  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.143  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.143  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-05 01:44:49.144  4641  4641 D BtGatt.ScanManager: awakened up at time 108404
11-05 01:44:49.143  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.145  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.145  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.145  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-05 01:44:49.145  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-05 01:44:49.147  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-05 01:44:49.147  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.148   927  3818 I ActivityManager: Killing 5392:com.android.chrome/u0a39 (adj 15): empty #17
11-05 01:44:49.149  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:49.149  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-05 01:44:49.149  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.149  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:49.149  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-05 01:44:49.149  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-05 01:44:49.150  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-05 01:44:49.150  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-05 01:44:49.150  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-05 01:44:49.150  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-05 01:44:49.150  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-05 01:44:49.150  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-05 01:44:49.150  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-05 01:44:49.150  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-05 01:44:49.152  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-05 01:44:49.152  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-05 01:44:49.152  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-05 01:44:49.152  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-05 01:44:49.152  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-05 01:44:49.188  4641  4700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-05 01:44:49.188  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:44:49.189  4641  4700 D BtGatt.GattService: current time is 108448832826
11-05 01:44:49.189  4641  4700 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -85, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-05 01:44:49.189  4641  4700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-05 01:44:49.189  4641  4700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-05 01:44:49.189  4641  4700 E BtGatt.ContextMap: Context not found for ID 5
,11-05 01:44:49.198  4641  4700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-05 01:44:49.198  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:49.198  4641  4703 D BtGatt.ScanManager: stopping BLe Batch
,11-05 01:44:49.205  4641  4700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-05 01:44:49.205  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:44:49.205  4641  4703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-05 01:44:49.212  4641  4700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-05 01:44:49.212  4641  4700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:44:49.653  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-05 01:44:49.654  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-05 01:44:49.654  5593  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-05 01:44:54.151  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:54.151  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-05 01:44:54.151  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:54.151  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:54.151  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-05 01:44:54.152  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-05 01:44:54.152  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:54.152  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
,11-05 01:44:54.152  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.152  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.152  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
,11-05 01:44:54.153  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-05 01:44:54.155  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.159  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.159  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.160  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.160  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:54.160  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:54.160  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.160  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
,11-05 01:44:54.162  5593  5640 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-05 01:44:54.163  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-05 01:44:54.164  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-05 01:44:54.164  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:54.165  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:54.165  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:54.165  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
,11-05 01:44:54.165  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.166  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.166  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:54.166  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:54.170  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.170  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:54.171  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.171  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:54.171  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:54.171  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.171  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
,11-05 01:44:54.174  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-05 01:44:54.174  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-05 01:44:54.174  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:54.175  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:54.175  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:54.175  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:54.175  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:54.175  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.175  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.175  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:54.176  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:54.178  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:54.178  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.179  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.179  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:54.179  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:54.179  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.179  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
,11-05 01:44:54.180  5593  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-05 01:44:54.180  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:54.181  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:54.181  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:54.181  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:54.181  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-05 01:44:54.181  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:54.181  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.181  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.181  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:54.181  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:54.185  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.185  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.186  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.186  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:54.186  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-05 01:44:54.186  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.186  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
,11-05 01:44:54.188  5593  5640 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-05 01:44:54.188  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:54.188  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:54.188  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:54.189  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:54.189  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:54.189  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:54.189  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.189  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.189  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:54.189  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.192  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.192  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:54.192  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.192  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:54.192  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:54.192  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.192  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
,11-05 01:44:54.194  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-05 01:44:54.194  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-05 01:44:54.194  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-05 01:44:54.194  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-05 01:44:54.195  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-05 01:44:54.195  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-05 01:44:54.195  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-05 01:44:54.195  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-05 01:44:54.195  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-05 01:44:54.195  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:54.195  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:54.195  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:54.195  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:54.196  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-05 01:44:54.196  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:54.196  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.196  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.196  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:54.196  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.200  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:54.201  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.203  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.203  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:54.203  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:54.203  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.204  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
,11-05 01:44:54.205  5593  5640 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-05 01:44:54.205  5593  5640 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-05 01:44:54.206  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-05 01:44:54.212  5593  5640 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-05 01:44:54.212  5593  5640 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-05 01:44:54.213  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-05 01:44:54.214  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-05 01:44:54.214  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-05 01:44:54.214  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-05 01:44:54.214  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-05 01:44:54.214  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-05 01:44:54.214  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-05 01:44:54.214  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-05 01:44:54.214  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-05 01:44:54.214  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-05 01:44:54.214  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-05 01:44:54.214  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-05 01:44:54.215  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-05 01:44:54.215  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-05 01:44:54.215  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-05 01:44:54.215  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-05 01:44:54.215  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-05 01:44:54.215  5593  5640 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-05 01:44:54.216  5593  5640 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-05 01:44:54.216  5593  5640 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-05 01:44:54.216  5593  5640 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-05 01:44:54.216  5593  5640 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-05 01:44:54.216  5593  5640 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-05 01:44:54.216  5593  5640 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-05 01:44:54.216  5593  5640 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-05 01:44:54.216  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-05 01:44:54.222  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-05 01:44:54.222  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-05 01:44:54.222  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-05 01:44:54.223  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-05 01:44:54.223  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-05 01:44:54.223  5593  5640 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,11-05 01:44:54.224  5593  5640 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-05 01:44:54.224  5593  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-05 01:44:54.224  5593  5640 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-05 01:44:54.224  5593  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-05 01:44:54.224  5593  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-05 01:44:54.224  5593  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-05 01:44:54.226  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:54.226  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:54.226  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-05 01:44:54.226  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:54.226  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:54.226  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-05 01:44:54.227  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:54.227  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.227  5593  5646 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-05 01:44:54.227  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
,11-05 01:44:54.228  5593  5646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-05 01:44:54.228  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:54.228  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.228  5593  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-05 01:44:54.228  5593  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-05 01:44:54.228  5593  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-05 01:44:54.229  5593  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
,11-05 01:44:54.229  4837  4837 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30687]" dev="sockfs" ino=30687 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-05 01:44:54.229  4837  4837 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[30687]" dev="sockfs" ino=30687 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-05 01:44:54.231  5593  5646 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-05 01:44:54.231  5593  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-05 01:44:54.231  5593  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-05 01:44:54.232  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.232  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.232  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.232  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:54.232  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:54.232  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.232  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.233  5593  5640 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-05 01:44:54.234  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:54.234  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-05 01:44:54.234  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:54.234  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:54.234  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:54.234  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:54.235  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.235  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.235  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:54.235  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.237  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.237  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.238  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:54.238  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:54.238  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:54.238  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.238  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.238  5593  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-05 01:44:54.239  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:54.239  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:54.239  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:54.239  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:54.239  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-05 01:44:54.239  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:54.239  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.239  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.239  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:54.239  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.240  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.240  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.240  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:54.240  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:54.240  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:54.240  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.241  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.241  5593  5640 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-05 01:44:54.241  5593  5640 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-05 01:44:54.241  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-05 01:44:54.241  5593  5640 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-05 01:44:54.241  5593  5640 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-05 01:44:54.242  5593  5640 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,11-05 01:44:54.242  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-05 01:44:54.242  5593  5640 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-05 01:44:54.242  5593  5640 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-05 01:44:54.242  5593  5640 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-05 01:44:54.242  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-05 01:44:54.242  5593  5640 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-05 01:44:54.242  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:54.242  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-05 01:44:54.242  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:54.242  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:54.242  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:54.242  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:54.242  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.242  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.242  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:54.242  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.243  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.244  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:54.244  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:54.244  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:54.244  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:54.244  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:54.244  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.245  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:54.245  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:54.245  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:54.245  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:44:54.245  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:54.245  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
,11-05 01:44:54.865   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-05 01:44:54.865   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-05 01:44:59.246  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:44:59.246  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:59.247  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:59.247  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-05 01:44:59.247  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:59.247  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:59.247  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-05 01:44:59.248  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:59.248  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:59.248  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-05 01:44:59.249  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:59.249  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:44:59.249  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:59.249  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:59.250  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:59.254  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:59.255  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.255  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.255  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:59.255  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:59.255  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:44:59.255  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:59.259  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-05 01:44:59.260  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-05 01:44:59.260  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-05 01:44:59.267  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-05 01:44:59.270  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-05 01:44:59.270  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-05 01:44:59.270  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-05 01:44:59.271  5593  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-05 01:44:59.271  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-05 01:44:59.271  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-05 01:44:59.271  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-05 01:44:59.272  5593  5648 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-05 01:44:59.273  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:59.273  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-05 01:44:59.274  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-05 01:44:59.274  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-05 01:44:59.274  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-05 01:44:59.275  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-05 01:44:59.275  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-05 01:44:59.276  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:59.276  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:59.276  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-05 01:44:59.276  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-05 01:44:59.276  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-05 01:44:59.277  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-05 01:44:59.277  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.276  4653  4653 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33850]" dev="sockfs" ino=33850 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-05 01:44:59.276  4653  4653 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33850]" dev="sockfs" ino=33850 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-05 01:44:59.278  5593  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-05 01:44:59.278  5593  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-05 01:44:59.278  5593  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-05 01:44:59.279  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:59.279  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-05 01:44:59.279  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.279  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.280  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:59.280  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-05 01:44:59.280  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:59.280  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-05 01:44:59.280  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:59.280  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-05 01:44:59.280  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:59.280  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:59.280  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:59.280  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-05 01:44:59.280  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:59.281  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:59.281  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:59.281  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:59.281  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:59.281  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:59.284  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:59.285  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.285  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.285  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:59.285  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:59.285  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:59.285  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
,11-05 01:44:59.287  5593  5640 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-05 01:44:59.288  5593  5640 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-05 01:44:59.288  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-05 01:44:59.288  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-05 01:44:59.288  5593  5640 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-05 01:44:59.288  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:59.288  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:59.288  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:59.289  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:59.289  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:59.289  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:59.289  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:59.289  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:59.289  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
,11-05 01:44:59.289  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:59.293  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:59.294  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.294  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.294  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:59.294  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:44:59.294  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:59.294  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
,11-05 01:44:59.300  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-05 01:44:59.300  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:44:59.300  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-05 01:44:59.300  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:59.300  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-05 01:44:59.300  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:59.300  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:59.301  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:59.301  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
,11-05 01:44:59.301  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:59.302  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:59.302  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.303  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.303  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:59.303  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-05 01:44:59.303  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:59.303  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:59.305  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:44:59.305  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-05 01:44:59.305  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:44:59.305  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:44:59.305  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:44:59.305  5593  5640 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ed57c not in the list
11-05 01:44:59.305  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:44:59.305  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:59.306  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:44:59.306  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.307  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:44:59.307  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.307  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:44:59.307  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:44:59.307  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-05 01:44:59.307  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:44:59.308  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe4de05 not in the list
11-05 01:44:59.309  5593  5640 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-05 01:44:59.309  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-05 01:44:59.309  5593  5640 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-05 01:44:59.309  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-05 01:44:59.309  5593  5640 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-05 01:44:59.309  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-05 01:44:59.312  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-05 01:44:59.312  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-05 01:44:59.312  5593  5640 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-05 01:44:59.312  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-05 01:44:59.313  5593  5640 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-05 01:44:59.313  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-05 01:44:59.313  5593  5640 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-05 01:44:59.313  5593  5640 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-05 01:44:59.313  5593  5640 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-05 01:44:59.314  5593  5640 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-05 01:44:59.314  5593  5640 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-05 01:44:59.314  5593  5640 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-05 01:44:59.314  5593  5640 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-05 01:44:59.314  5593  5640 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-05 01:44:59.316  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:44:59.316  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20af20a added. We now have 3 listener(s)
,11-05 01:44:59.316  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-05 01:44:59.318  5593  5640 D BluetoothAdapter: enable(): BT is already enabled..!
,11-05 01:44:59.318   927   939 D WifiService: setWifiEnabled: true pid=5593, uid=10077
11-05 01:44:59.318   927   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-05 01:44:59.358  4641  4826 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-05 01:44:59.358  4641  4834 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-05 01:44:59.781  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-05 01:44:59.866   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:00.867   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:01.868   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:02.797   927  2952 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-05 01:45:02.869   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:03.870   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:04.324  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-05 01:45:04.325  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2244a7b added. We now have 4 listener(s)
11-05 01:45:04.325  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-05 01:45:04.337  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:45:04.338  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2244a7b removed from the list
11-05 01:45:04.338  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
,11-05 01:45:04.339  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:45:04.340  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e476098 added. We now have 4 listener(s)
11-05 01:45:04.340  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-05 01:45:04.343  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:45:04.343  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e476098 removed from the list
,11-05 01:45:04.343  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
,11-05 01:45:04.345  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-05 01:45:04.345  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@162a0f1 added. We now have 4 listener(s)
,11-05 01:45:04.345  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-05 01:45:04.349   927  3819 D WifiService: setWifiEnabled: false pid=5593, uid=10077
11-05 01:45:04.350   927  3819 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-05 01:45:04.354   927  2952 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-05 01:45:04.354   927  2952 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-05 01:45:04.354   927  2952 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-05 01:45:04.355   927  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-05 01:45:04.361  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-05 01:45:04.362  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-05 01:45:04.362  4641  4696 D BluetoothAdapterState: Current state: ON, message: 23
11-05 01:45:04.362  4641  4696 D BluetoothAdapterProperties: Setting state to 13
11-05 01:45:04.362  4641  4696 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-05 01:45:04.365  4641  4696 D BluetoothAdapterProperties: onBluetoothDisable()
11-05 01:45:04.367  4641  4696 I BluetoothAdapterState: Entering PendingCommandState
,11-05 01:45:04.369  4641  4700 D BluetoothAdapterProperties: Scan Mode:20
11-05 01:45:04.369  4641  4696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-05 01:45:04.371  4641  4641 D BluetoothMapService: onReceive
11-05 01:45:04.371  4641  4641 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-05 01:45:04.371  4641  4641 D BluetoothMapService: STATE_TURNING_OFF
11-05 01:45:04.371  4641  4641 D BluetoothMapService: MAP Service closeService in
11-05 01:45:04.372  4641  4641 D BluetoothMapMasInstance0: MAP Service shutdown
,11-05 01:45:04.372  4641  4641 D ObexServerSockets0: shutdown(block = true)
11-05 01:45:04.372  4641  4641 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-05 01:45:04.372  4641  4641 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-05 01:45:04.373  4641  4863 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-05 01:45:04.373  4641  4862 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-05 01:45:04.373  4641  4834 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-05 01:45:04.374  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:04.374  5593  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-05 01:45:04.374  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:45:04.374  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:45:04.374  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-05 01:45:04.374  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-05 01:45:04.374  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-05 01:45:04.374  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-05 01:45:04.374  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-05 01:45:04.377   506   920 D CommandListener: Clearing all IP addresses on wlan0
11-05 01:45:04.378   927  5356 D DhcpClient: Clearing IP address
11-05 01:45:04.382  4641  4641 I BtOppRfcommListener: stopping Accept Thread
11-05 01:45:04.382  4641  5274 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-05 01:45:04.383  4641  5274 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-05 01:45:04.385   506   920 D CommandListener: Setting iface cfg
,11-05 01:45:04.387  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:04.387  5593  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-05 01:45:04.387  5593  5640 D io.jxcore.node.ConnectivityMonitor: start: OK
11-05 01:45:04.390  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-05 01:45:04.393  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:45:04.396  3561  5405 V NativeCrypto: Read error: ssl=0x7f9057dc80: I/O error during system call, Connection timed out
11-05 01:45:04.396  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-05 01:45:04.398  3561  5405 V NativeCrypto: SSL shutdown failed: ssl=0x7f9057dc80: I/O error during system call, Broken pipe
,11-05 01:45:04.400  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:45:04.401   927  3818 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-05 01:45:04.401   927  5354 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-05 01:45:04.403   927   941 I ActivityManager: Start proc 5652:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-05 01:45:04.404   927  5357 D DhcpClient: Receive thread stopped
11-05 01:45:04.405   927  5354 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-05 01:45:04.405   927  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-05 01:45:04.405   927  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,11-05 01:45:04.405  4641  4641 D HeadsetService: Received stop request...Stopping profile...
11-05 01:45:04.406   927  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-05 01:45:04.407   927  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-05 01:45:04.408   927  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-05 01:45:04.410   533   533 E Parcel  : Reading a NULL string not supported here.
,11-05 01:45:04.411   927   927 D BluetoothHeadset: Proxy object disconnected
,11-05 01:45:04.411  3108  3121 D BluetoothHeadset: Proxy object disconnected
11-05 01:45:04.411  3108  3108 D HeadsetProfile: Bluetooth service disconnected
11-05 01:45:04.412   927   927 D BluetoothHeadset: Proxy object disconnected
11-05 01:45:04.412   927   927 D BluetoothHeadset: Proxy object disconnected
,11-05 01:45:04.418  3763  3809 D BluetoothHeadset: Proxy object disconnected
,11-05 01:45:04.419   927   927 D RttService: SCAN_AVAILABLE : 1
11-05 01:45:04.419  4641  4641 D A2dpService: Received stop request...Stopping profile...
11-05 01:45:04.420   927  3061 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-05 01:45:04.420  4641  4852 D A2dpStateMachine: Exit Disconnected: -1
11-05 01:45:04.421   927   927 D BluetoothA2dp: Proxy object disconnected
,11-05 01:45:04.423  4641  4641 D HidService: Received stop request...Stopping profile...
,11-05 01:45:04.423   927  2952 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-05 01:45:04.423  4641  4641 D HidService: Stopping Bluetooth HidService
11-05 01:45:04.424   927  2954 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-05 01:45:04.424  4641  4641 V BluetoothAdapterState: isTurningOff()=true
11-05 01:45:04.424  4641  4641 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:04.424  4641  4641 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:04.424  4641  4641 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:04.425  4641  4641 D HealthService: Received stop request...Stopping profile...
11-05 01:45:04.426  3733  3849 W QCNEJ   : |CORE| network lost: 100
11-05 01:45:04.426  3733  3849 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-05 01:45:04.429  3108  3108 D BluetoothA2dp: Proxy object disconnected
11-05 01:45:04.429  4641  4641 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-05 01:45:04.429  4641  4641 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-05 01:45:04.429  4641  4826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-05 01:45:04.429  4641  4826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-05 01:45:04.429  4641  4826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-05 01:45:04.429  4641  4700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-05 01:45:04.429  4641  4700 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-05 01:45:04.430  3108  3108 D BluetoothInputDevice: Proxy object disconnected
11-05 01:45:04.430  3108  3108 D HidProfile: Bluetooth service disconnected
11-05 01:45:04.431   927  2952 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-05 01:45:04.431  4641  4641 D PanService: Received stop request...Stopping profile...
,11-05 01:45:04.435  4641  4641 V BluetoothAdapterState: isTurningOff()=true
,11-05 01:45:04.435  4641  4641 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:04.435  4641  4641 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:04.435  4641  4641 V BluetoothAdapterState: isBleTurningOff()=false
,11-05 01:45:04.436  4641  4641 D BluetoothMapService: Received stop request...Stopping profile...
,11-05 01:45:04.436  4641  4641 D BluetoothMapService: stop()
11-05 01:45:04.437  4641  4641 D BluetoothMapAppObserver: deinitObservers()
11-05 01:45:04.437  4641  4641 D BluetoothMapAppObserver: removeReceiver()
11-05 01:45:04.439  4641  4826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-05 01:45:04.439  4641  4826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-05 01:45:04.439  4641  4641 D SapService: Received stop request...Stopping profile...
11-05 01:45:04.439  4641  4641 V SapService: stop()
11-05 01:45:04.439  4641  4700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-05 01:45:04.439  4641  4826 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-05 01:45:04.439  4641  4826 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-05 01:45:04.439  4641  4826 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-05 01:45:04.440  4641  4826 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-05 01:45:04.444  4641  4641 V BluetoothAdapterState: isTurningOff()=true
,11-05 01:45:04.445  4641  4641 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:04.445  4641  4641 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:04.445  4641  4641 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:04.445  4641  4641 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-05 01:45:04.445  4641  4641 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-05 01:45:04.445  4641  4641 V BluetoothAdapterState: isTurningOff()=true
11-05 01:45:04.445  4641  4700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-05 01:45:04.445  4641  4641 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:04.445  4641  4641 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:04.445  4641  4641 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:04.446  4641  4641 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-05 01:45:04.446  4641  4700 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-05 01:45:04.447  4641  4641 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-05 01:45:04.447  4641  4641 V BluetoothAdapterState: isTurningOff()=true
11-05 01:45:04.447  4641  4641 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:04.447  4641  4641 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:04.447  4641  4641 V BluetoothAdapterState: isBleTurningOff()=false
,11-05 01:45:04.447  4641  4641 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-05 01:45:04.447  4641  4641 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-05 01:45:04.448  4641  4641 D BluetoothMapService: MAP Service closeService in
11-05 01:45:04.448  4641  4641 V BluetoothAdapterState: isTurningOff()=true
,11-05 01:45:04.448  4641  4641 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:04.448  4641  4641 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:04.448  4641  4641 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:04.448  3108  3108 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-05 01:45:04.448  4641  4641 D BluetoothMapService: cleanup()
11-05 01:45:04.448  3108  3108 D PanProfile: Bluetooth service disconnected
11-05 01:45:04.448  4641  4641 D BluetoothMapService: MAP Service closeService in
11-05 01:45:04.449  3108  3108 D BluetoothMap: Proxy object disconnected
11-05 01:45:04.449  3108  3108 D MapProfile: Bluetooth service disconnected
11-05 01:45:04.449  4641  4641 V BluetoothAdapterState: isTurningOff()=true
11-05 01:45:04.449  4641  4641 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:04.449  4641  4641 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:04.449  4641  4641 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:04.449  4641  4696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-05 01:45:04.449  4641  4696 D BluetoothAdapterProperties: Setting state to 15
11-05 01:45:04.449  4641  4696 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-05 01:45:04.450   927   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-05 01:45:04.450  3108  3121 D BluetoothPan: onBluetoothStateChange on: false
11-05 01:45:04.453   927   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-05 01:45:04.453  3108  3975 D BluetoothPbap: onBluetoothStateChange: up=false
11-05 01:45:04.453  4641  4696 I BluetoothAdapterState: Entering BleOnState
11-05 01:45:04.454   927   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-05 01:45:04.454  3108  3120 D BluetoothMap: onBluetoothStateChange: up=false
11-05 01:45:04.455  3108  3121 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-05 01:45:04.456  3763  4117 D BluetoothHeadset: onBluetoothStateChange: up=false
11-05 01:45:04.456   927   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-05 01:45:04.456  3108  3975 D BluetoothHeadset: onBluetoothStateChange: up=false
11-05 01:45:04.456  3108  3120 D BluetoothA2dp: onBluetoothStateChange: up=false
11-05 01:45:04.457  4641  4696 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-05 01:45:04.457  4641  4696 D BluetoothAdapterProperties: Setting state to 16
11-05 01:45:04.457  4641  4696 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-05 01:45:04.458  4641  4696 D BluetoothAdapterProperties: onBleDisable
11-05 01:45:04.458  4641  4696 I BluetoothAdapterState: Entering PendingCommandState
11-05 01:45:04.458  4641  4697 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-05 01:45:04.459  4641  4826 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-05 01:45:04.459  4641  4826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-05 01:45:04.462  4641  4700 D BluetoothAdapterProperties: Scan Mode:20
11-05 01:45:04.463  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:04.463  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-05 01:45:04.463  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:45:04.463  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:45:04.463  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-05 01:45:04.463  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-05 01:45:04.463  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-05 01:45:04.463  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to ac,tive network: false
11-05 01:45:04.463  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-05 01:45:04.464  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:04.464  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-05 01:45:04.466  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:45:04.473   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-05 01:45:04.475  5652  5652 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-05 01:45:04.487  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-05 01:45:04.492   927   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@58e775:true
11-05 01:45:04.493  3561  3561 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-05 01:45:04.495   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-05 01:45:04.495   506   920 D CommandListener: Clearing all IP addresses on wlan0
11-05 01:45:04.495   506   920 D TetherController: Setting IP forward enable = 0
11-05 01:45:04.496   927  2954 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-05 01:45:04.496   927  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-05 01:45:04.499   927  2952 D DhcpClient: doQuit
11-05 01:45:04.499   927  2952 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-05 01:45:04.499   927   945 D Tethering: MasterInitialState.processMessage what=3
11-05 01:45:04.500  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:45:04.500  3429  3429 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-05 01:45:04.500   927  5356 D DhcpClient: onQuitting
11-05 01:45:04.500  5261  5261 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5673cca and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-05 01:45:04.502  3937  3937 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-05 01:45:04.504  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:04.505  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-05 01:45:04.505  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:45:04.505  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:45:04.505  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-05 01:45:04.505  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-05 01:45:04.505  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-05 01:45:04.505  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-05 01:45:04.505  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-05 01:45:04.506  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:04.506  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-05 01:45:04.513   927  3770 I ActivityManager: Start proc 5677:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-05 01:45:04.521  5652  5652 D LocalBluetoothProfileManager: Adding local MAP profile
11-05 01:45:04.523  3429  3429 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-05 01:45:04.524  5652  5652 D BluetoothMap: Create BluetoothMap proxy object
11-05 01:45:04.527  3429  3429 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-05 01:45:04.533  5652  5652 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
11-05 01:45:04.550   506   920 E Netd    : netlink response contains error (No such file or directory)
11-05 01:45:04.551   927  2954 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-05 01:45:04.551  5652  5652 D DockEventReceiver: finishStartingService: stopping service
11-05 01:45:04.551   927  2954 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-05 01:45:04.552   506   920 D TetherController: Setting IP forward enable = 0
,11-05 01:45:04.556   927  3396 I ActivityManager: Killing 4418:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-05 01:45:04.559  3429  3429 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-05 01:45:04.568  5677  5677 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-05 01:45:04.577  3429  3429 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-05 01:45:04.667  4641  4700 I bt_hci  : shut_down
,11-05 01:45:04.673  4641  4704 D bt_hwcfg: hw_epilog_process
,11-05 01:45:04.673  4641  4704 I bt_vendor: low_power_mode_cb
,11-05 01:45:04.676  4641  4704 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-05 01:45:04.676  4641  4704 I bt_vendor: epilog_cb
11-05 01:45:04.676  4641  4704 I bt_hci  : epilog_finished_callback
,11-05 01:45:04.679   927  2952 D wifi    : In wifi stop Hal
,11-05 01:45:04.679  4487  4487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-05 01:45:04.679   927  2952 D wifi    : halHandle = 0x7f7a257080, mVM = 0x7f9688d140, mCls = 0x100a02
11-05 01:45:04.679   927  3428 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-05 01:45:04.679   927  3428 D WifiHAL : Got a signal to exit!!!
11-05 01:45:04.679   927  3428 I WifiHAL : Exit wifi_event_loop
11-05 01:45:04.680   927  2952 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-05 01:45:04.680   927  2952 E WifiHAL : Event processing terminated
11-05 01:45:04.680   927  2952 D wifi    : In wifi cleaned up handler
11-05 01:45:04.680   927  2952 I WifiHAL : Internal cleanup completed
11-05 01:45:04.681  3704  4186 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-05 01:45:04.681  4641  4700 I bt_hci_h4: hal_close
11-05 01:45:04.682  4641  4700 I bt_userial_vendor: device fd = 54 close
11-05 01:45:04.683  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:45:04.702   927  3428 D wifi    : set interface wlan0 flags (DOWN)
11-05 01:45:04.702   927  2952 D WifiNative-HAL: HAL event thread stopped successfully
,11-05 01:45:04.745  5677  5677 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at java.io.File.exists(File.java:361)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-05 01:45:04.745  5677  5677 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-05 01:45:04.745  5677  5677 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-05 01:45:04.745  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-05 01:45:04.746  5677  5677 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.e.b(PG:170)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-05 01:45:04.746  5677  5677 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.k.d(PG:583)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.e.b(PG:170)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-05 01:45:04.746  5677  5677 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.io.File.exists(File.java:361)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-05 01:45:04.746  5677  5677 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.io.File.exists(File.java:361)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-05 01:45:04.746  5677  5677 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-05 01:45:04.746  5677  5677 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-05 01:45:04.751  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-05 01:45:04.755  3561  3561 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-05 01:45:04.759  5652  5652 D DockEventReceiver: finishStartingService: stopping service
11-05 01:45:04.762   927  3819 I ActivityManager: Killing 5422:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-05 01:45:04.791  3954  3954 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-05 01:45:04.795  3954  3954 D SystemUpdateService: onCreate
11-05 01:45:04.795  4641  4697 D bt_stack_manager: event_shut_down_stack finished.
11-05 01:45:04.795  4641  4696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-05 01:45:04.796  4641  4641 D BtGatt.DebugUtils: handleDebugAction() action=null
11-05 01:45:04.797  4641  4696 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-05 01:45:04.797  4641  4641 D BtGatt.GattService: Received stop request...Stopping profile...
11-05 01:45:04.797  4641  4641 D BtGatt.GattService: stop()
11-05 01:45:04.797  4641  4641 D BtGatt.AdvertiseManager: advertise clients cleared
11-05 01:45:04.798  3954  3954 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-05 01:45:04.799  4641  4641 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:04.799  4641  4641 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:04.799  4641  4641 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:04.799  4641  4641 V BluetoothAdapterState: isBleTurningOff()=true
11-05 01:45:04.799  4641  4696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-05 01:45:04.799  4641  4696 D BluetoothAdapterProperties: Setting state to 10
11-05 01:45:04.799  4641  4696 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-05 01:45:04.800  4641  4696 I BluetoothAdapterState: Entering OffState
11-05 01:45:04.801   927   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-05 01:45:04.808  4641  4641 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-05 01:45:04.808  4641  4641 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-05 01:45:04.808  4641  4697 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-05 01:45:04.810  4641  4641 I BluetoothServiceJni: cleanupNative: return from cleanup
11-05 01:45:04.819  3954  3954 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-05 01:45:04.821  4641  4697 D bt_stack_manager: event_clean_up_stack finished.
11-05 01:45:04.822  3954  4250 I iu.UploadsManager: num queued entries: 0
11-05 01:45:04.822  3954  4250 I iu.UploadsManager: num updated entries: 0
11-05 01:45:04.822  3954  4250 I iu.SyncManager: NEXT; no task
,11-05 01:45:04.829  4641  4641 I art     : System.exit called, status: 0
,11-05 01:45:04.829  4641  4641 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-05 01:45:04.834  3954  3954 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-05 01:45:04.836  3954  3954 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-05 01:45:04.847   927  3790 I ActivityManager: Start proc 5719:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-05 01:45:04.854  3954  5715 I SystemUpdateService: active receiver: enabled
,11-05 01:45:04.871   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-05 01:45:04.877  5719  5719 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-05 01:45:04.880  5719  5719 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-05 01:45:04.887  5719  5719 D SprintDMHelper: simOperator: 
,11-05 01:45:04.887  5719  5719 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-05 01:45:04.892   927  3790 I ActivityManager: Process com.android.bluetooth (pid 4641) has died
,11-05 01:45:04.905   927  3818 I ActivityManager: Start proc 5731:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-05 01:45:04.906   927   945 D Tethering: InitialState.processMessage what=4
,11-05 01:45:04.909   927   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-05 01:45:04.912  3954  5715 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-05 01:45:04.924  3954  5715 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-05 01:45:04.929  3954  5715 I SystemUpdateService: now status is 0 (complete)
11-05 01:45:04.929  3954  5715 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-05 01:45:04.929  3954  5715 I SystemUpdateService: file has been verified
11-05 01:45:04.930  3954  5715 I SystemUpdateService: OTA package size = 21989297
,11-05 01:45:04.961  3954  5715 I SystemUpdateService: showing system update notification
,11-05 01:45:05.019   927  3770 I ActivityManager: Start proc 5746:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-05 01:45:05.021   927  3790 I ActivityManager: Killing 5261:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-05 01:45:05.037   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-05 01:45:05.061  3954  3954 D SystemUpdateService: onDestroy
,11-05 01:45:05.065   927  3819 I ActivityManager: Killing 3861:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-05 01:45:05.084  5746  5746 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-05 01:45:05.093   927  3819 I ActivityManager: Killing 5469:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-05 01:45:05.191  5677  5705 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-05 01:45:05.199   927   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c27fe3f:true
,11-05 01:45:09.390   927   938 D WifiService: setWifiEnabled: true pid=5593, uid=10077
,11-05 01:45:09.390   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-05 01:45:09.399   506   920 D SoftapController: Softap fwReload - Ok
,11-05 01:45:09.404   506   920 D CommandListener: Setting iface cfg
,11-05 01:45:09.405   506   920 D CommandListener: Trying to bring down wlan0
11-05 01:45:09.407   506   920 D CommandListener: Clearing all IP addresses on wlan0
,11-05 01:45:09.412   927  2952 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-05 01:45:09.872   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:09.965   927  2952 D wifi    : set interface wlan0 flags (UP)
,11-05 01:45:09.965   927  2952 I WifiHAL : Initializing wifi
,11-05 01:45:09.965   927  2952 I WifiHAL : Creating socket
,11-05 01:45:09.968   927  2952 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-05 01:45:09.968   927  2952 D wifi    : Did set static halHandle = 0x7f7a257080
11-05 01:45:09.968   927  2952 D wifi    : halHandle = 0x7f7a257080, mVM = 0x7f9688d140, mCls = 0x201942
11-05 01:45:09.968   927  2952 D wifi    : array field set
11-05 01:45:09.968   927  2952 I WifiNative-HAL: interface[0] = wlan0
11-05 01:45:09.968   927   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-05 01:45:09.969   927  5765 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547510120576
11-05 01:45:09.969   927  5765 D wifi    : waitForHalEvents called, vm = 0x7f9688d140, obj = 0x201942, env = 0x7f7a27ae40
,11-05 01:45:10.021  5766  5766 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-05 01:45:10.071   927  2952 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-05 01:45:10.078  5766  5766 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-05 01:45:10.079  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-05 01:45:10.139  5766  5766 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-05 01:45:10.139  5766  5766 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-05 01:45:10.160   927  2952 D WifiConfigStore: Loading config and enabling all networks 
,11-05 01:45:10.163  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:10.163  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-05 01:45:10.163  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:45:10.163  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:45:10.163  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-05 01:45:10.163  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-05 01:45:10.163  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-05 01:45:10.163  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-05 01:45:10.163  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-05 01:45:10.164  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:10.164  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-05 01:45:10.191   927  2952 D WifiConfigStore: loaded 0 passpoint configs
,11-05 01:45:10.192   927  2952 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-05 01:45:10.192   927  2952 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-05 01:45:10.193   927  2952 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-05 01:45:10.194   927  2952 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-05 01:45:10.194   927  2952 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-05 01:45:10.195   927  2952 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-05 01:45:10.195   927  2952 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-05 01:45:10.195   927  2952 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-05 01:45:10.196   927  2952 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-05 01:45:10.196   927  2952 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-05 01:45:10.196   927  2952 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-05 01:45:10.196   927  2952 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-05 01:45:10.199   927  2952 D WifiNative-HAL: Setting external_sim to 1
,11-05 01:45:10.199  4487  4487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-05 01:45:10.199   927  2952 D wifi    : setting dfs flag to true, 0x7f7c6fe580
,11-05 01:45:10.200   927  2952 D WifiStateMachine: Setting OUI to DA-A1-19
11-05 01:45:10.200   927  2952 D wifi    : setting scan oui 0x7f7c6fe580
11-05 01:45:10.200   927  2952 D WifiHAL : Sending mac address OUI
,11-05 01:45:10.204   927  2952 E native  : do suspend false
,11-05 01:45:10.210   927  2952 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-05 01:45:10.210   927   927 D RttService: SCAN_AVAILABLE : 3
11-05 01:45:10.211   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-05 01:45:10.211   927  3061 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-05 01:45:10.211   506   920 D CommandListener: Setting iface cfg
,11-05 01:45:10.216   927  2944 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
,11-05 01:45:10.216   927  2944 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-05 01:45:10.227   927   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129487 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,11-05 01:45:10.228   927  2944 D WifiNative-HAL: p2pGetDeviceAddress
,11-05 01:45:10.228   927  2944 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-05 01:45:10.876   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:11.877   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:12.878   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:13.323  5766  5766 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-05 01:45:13.332  5766  5766 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-05 01:45:13.338  5766  5766 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-05 01:45:13.343  5766  5766 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-05 01:45:13.368   927  2952 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-05 01:45:13.369   927  2952 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-05 01:45:13.369   927  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-05 01:45:13.379   927  2952 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-05 01:45:13.409   927  2952 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-05 01:45:13.415  5766  5766 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-05 01:45:13.840  5766  5766 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-05 01:45:13.872  5766  5766 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-05 01:45:13.873  5766  5766 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-05 01:45:13.880   536   536 I ServiceManager: Waiting for service AtCmdFwd...
11-05 01:45:13.882   927  2952 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-05 01:45:13.882   927  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-05 01:45:13.883   927  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-05 01:45:13.903   927  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-05 01:45:13.917   506   920 D CommandListener: Setting iface cfg
,11-05 01:45:13.923   927  2952 D WifiStateMachine: Start Dhcp Watchdog 2
,11-05 01:45:13.930   927  5772 D DhcpClient: Receive thread started
,11-05 01:45:13.934   927  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-05 01:45:13.934   927  2952 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-05 01:45:13.934   927  2954 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-05 01:45:14.015   927  2952 E native  : do suspend false
,11-05 01:45:14.028   927  5771 D DhcpClient: Broadcasting DHCPDISCOVER
,11-05 01:45:14.044   927  5772 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-05 01:45:14.045   927  5771 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-05 01:45:14.049   927  5771 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-05 01:45:14.064   927  5772 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-05 01:45:14.065   927  5771 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-05 01:45:14.069   506   920 D CommandListener: Setting iface cfg
,11-05 01:45:14.074   927  2952 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-05 01:45:14.078   927  5771 D DhcpClient: Scheduling renewal in 86399s
,11-05 01:45:14.091   927  2952 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-05 01:45:14.092   927  2952 D WifiConfigStore: No blacklist allowed without epno enabled
11-05 01:45:14.093   927  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-05 01:45:14.099   927  2954 D ConnectivityService: Adding iface wlan0 to network 101
11-05 01:45:14.103   927  2952 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-05 01:45:14.154   927  2954 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-05 01:45:14.154   927  2954 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
11-05 01:45:14.156   927  2954 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-05 01:45:14.158   927  2954 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-05 01:45:14.160   927  2954 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-05 01:45:14.170   927  2954 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-05 01:45:14.175   927  2954 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-05 01:45:14.175   927  2954 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-05 01:45:14.175   927  2954 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-05 01:45:14.175   927  2952 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-05 01:45:14.175   927  2954 D ConnectivityService:    accepting network in place of null
11-05 01:45:14.175   927  2952 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-05 01:45:14.176   927  2954 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-05 01:45:14.188   927  5770 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133447, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-05 01:45:14.206   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-05 01:45:14.233   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-05 01:45:14.239   927  2954 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-05 01:45:14.239   927  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-05 01:45:14.239  3733  3849 W QCNEJ   : |CORE| network available: 101
,11-05 01:45:14.241   927  2954 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-05 01:45:14.242   927   945 D Tethering: MasterInitialState.processMessage what=3
,11-05 01:45:14.243  3733  3849 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-05 01:45:14.245  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:14.245  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-05 01:45:14.245  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:45:14.245  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:45:14.245  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-05 01:45:14.245  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-05 01:45:14.245  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-05 01:45:14.245  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-05 01:45:14.245  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-05 01:45:14.246  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:14.246  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-05 01:45:14.251  3733  3849 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-05 01:45:14.251  3733  3849 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-05 01:45:14.252   927  5769 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-05 01:45:14.255  3937  3937 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-05 01:45:14.257  3954  3954 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-05 01:45:14.260  3954  3954 D SystemUpdateService: onCreate
11-05 01:45:14.263  3954  3954 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-05 01:45:14.273  3954  3954 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-05 01:45:14.278  3954  4250 I iu.UploadsManager: num queued entries: 0
,11-05 01:45:14.278  3954  4250 I iu.UploadsManager: num updated entries: 0
,11-05 01:45:14.279  3954  4250 I iu.SyncManager: NEXT; no task
11-05 01:45:14.280  3954  5781 I SystemUpdateService: active receiver: enabled
,11-05 01:45:14.283  3954  3954 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-05 01:45:14.284  3954  3954 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-05 01:45:14.286  5719  5719 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-05 01:45:14.290  5719  5719 D SprintDMHelper: simOperator: 
,11-05 01:45:14.290  5719  5719 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-05 01:45:14.296   927  5769 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 05 Nov 2016 00:45:14 GMT], X-Android-Received-Millis=[1478306714296], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478306714274]}
,11-05 01:45:14.297   927  2954 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-05 01:45:14.297   927  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-05 01:45:14.297   927  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-05 01:45:14.298   927  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-05 01:45:14.314  3954  5781 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-05 01:45:14.320  3954  5781 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-05 01:45:14.320  3954  5781 I SystemUpdateService: now status is 0 (complete)
11-05 01:45:14.320  3954  5781 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-05 01:45:14.320  3954  5781 I SystemUpdateService: file has been verified
11-05 01:45:14.320  3954  5781 I SystemUpdateService: OTA package size = 21989297
,11-05 01:45:14.325  3954  5781 I SystemUpdateService: showing system update notification
,11-05 01:45:14.333   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-05 01:45:14.334  3954  3954 D SystemUpdateService: onDestroy
,11-05 01:45:14.396   927  3138 D WifiService: setWifiEnabled: false pid=5593, uid=10077
11-05 01:45:14.396   927  3138 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-05 01:45:14.397   927  2952 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-05 01:45:14.397   927  2952 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-05 01:45:14.398   927  2952 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-05 01:45:14.398   927  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-05 01:45:14.406   927  5771 D DhcpClient: Clearing IP address
11-05 01:45:14.406   506   920 D CommandListener: Clearing all IP addresses on wlan0
,11-05 01:45:14.408   506   920 D CommandListener: Setting iface cfg
,11-05 01:45:14.414  3561  5788 V NativeCrypto: Read error: ssl=0x7f7bb98000: I/O error during system call, Connection timed out
,11-05 01:45:14.415  3561  5788 V NativeCrypto: SSL shutdown failed: ssl=0x7f7bb98000: I/O error during system call, Broken pipe
11-05 01:45:14.417   927  5772 D DhcpClient: Receive thread stopped
11-05 01:45:14.418   927  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-05 01:45:14.418   927  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-05 01:45:14.424   927   927 D RttService: SCAN_AVAILABLE : 1
11-05 01:45:14.424   927  3061 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-05 01:45:14.426   533   533 E Parcel  : Reading a NULL string not supported here.
,11-05 01:45:14.427   927  2952 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-05 01:45:14.428   927  2954 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-05 01:45:14.429  3733  3849 W QCNEJ   : |CORE| network lost: 101
11-05 01:45:14.430  3733  3849 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-05 01:45:14.431   927  2952 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-05 01:45:14.453   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-05 01:45:14.473   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-05 01:45:14.473   927  2954 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-05 01:45:14.473   927  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-05 01:45:14.473   506   920 D CommandListener: Clearing all IP addresses on wlan0
,11-05 01:45:14.477   927   945 D Tethering: MasterInitialState.processMessage what=3
,11-05 01:45:14.478  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:14.478  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-05 01:45:14.478  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:45:14.478  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:45:14.478  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-05 01:45:14.478  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-05 01:45:14.478  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-05 01:45:14.478  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-05 01:45:14.478  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-05 01:45:14.478  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-05 01:45:14.478  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-05 01:45:14.480  3937  3937 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-05 01:45:14.484  3954  3954 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-05 01:45:14.487  3954  3954 D SystemUpdateService: onCreate
,11-05 01:45:14.490  3954  3954 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-05 01:45:14.494  3954  5797 I SystemUpdateService: active receiver: enabled
,11-05 01:45:14.499  3954  3954 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-05 01:45:14.504  3954  4250 I iu.UploadsManager: num queued entries: 0
,11-05 01:45:14.504  3954  4250 I iu.UploadsManager: num updated entries: 0
11-05 01:45:14.505  3954  4250 I iu.SyncManager: NEXT; no task
,11-05 01:45:14.507  3954  3954 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-05 01:45:14.508  3954  3954 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-05 01:45:14.510  5719  5719 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-05 01:45:14.514  5719  5719 D SprintDMHelper: simOperator: 
,11-05 01:45:14.514  5719  5719 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-05 01:45:14.521  3954  5797 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-05 01:45:14.527   506   920 E Netd    : netlink response contains error (No such file or directory)
,11-05 01:45:14.528   927  2954 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-05 01:45:14.529   927  2952 D DhcpClient: doQuit
11-05 01:45:14.529   927  2952 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-05 01:45:14.529   927  5771 D DhcpClient: onQuitting
11-05 01:45:14.529  3954  5797 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-05 01:45:14.529  3954  5797 I SystemUpdateService: now status is 0 (complete)
11-05 01:45:14.529  5766  5766 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-05 01:45:14.529  3954  5797 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-05 01:45:14.529  3954  5797 I SystemUpdateService: file has been verified
11-05 01:45:14.530  3954  5797 I SystemUpdateService: OTA package size = 21989297
,11-05 01:45:14.534  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-05 01:45:14.534  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-05 01:45:14.534  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:45:14.534  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:45:14.534  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-05 01:45:14.534  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-05 01:45:14.534  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-05 01:45:14.534  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-05 01:45:14.534  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-05 01:45:14.534  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:14.535  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-05 01:45:14.540  3954  5797 I SystemUpdateService: showing system update notification
11-05 01:45:14.542  5766  5766 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-05 01:45:14.546  5766  5766 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-05 01:45:14.552   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-05 01:45:14.553  3954  3954 D SystemUpdateService: onDestroy
,11-05 01:45:14.574  5766  5766 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-05 01:45:14.577  5766  5766 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-05 01:45:14.679   927  2952 D wifi    : In wifi stop Hal
11-05 01:45:14.679   927  2952 D wifi    : halHandle = 0x7f7a257080, mVM = 0x7f9688d140, mCls = 0x201942
,11-05 01:45:14.680   927  5765 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-05 01:45:14.680   927  5765 D WifiHAL : Got a signal to exit!!!
11-05 01:45:14.680   927  5765 I WifiHAL : Exit wifi_event_loop
11-05 01:45:14.684   927  2952 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-05 01:45:14.685   927  2952 E WifiHAL : Event processing terminated
11-05 01:45:14.685   927  2952 D wifi    : In wifi cleaned up handler
11-05 01:45:14.686   927  2952 I WifiHAL : Internal cleanup completed
11-05 01:45:14.686  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:45:14.688  3704  4186 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-05 01:45:14.692  4487  4487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-05 01:45:14.700   927  5765 D wifi    : set interface wlan0 flags (DOWN)
,11-05 01:45:14.700   927  2952 D WifiNative-HAL: HAL event thread stopped successfully
,11-05 01:45:14.880   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-05 01:45:14.907   927   945 D Tethering: InitialState.processMessage what=4
,11-05 01:45:14.914   927   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-05 01:45:15.240   927  2954 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-05 01:45:19.434   927   945 I ActivityManager: Start proc 5803:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-05 01:45:19.517  5803  5803 D AdapterServiceConfig: Adding HeadsetService
,11-05 01:45:19.517  5803  5803 D AdapterServiceConfig: Adding A2dpService
11-05 01:45:19.517  5803  5803 D AdapterServiceConfig: Adding HidService
11-05 01:45:19.517  5803  5803 D AdapterServiceConfig: Adding HealthService
11-05 01:45:19.517  5803  5803 D AdapterServiceConfig: Adding PanService
11-05 01:45:19.517  5803  5803 D AdapterServiceConfig: Adding GattService
11-05 01:45:19.518  5803  5803 D AdapterServiceConfig: Adding BluetoothMapService
,11-05 01:45:19.518  5803  5803 D AdapterServiceConfig: Adding SapService
,11-05 01:45:19.528   927   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e0caacd:true
,11-05 01:45:19.528  5803  5803 D BluetoothAdapterState: make() - Creating AdapterState
,11-05 01:45:19.532  5803  5803 I bt_bluedroid: init
,11-05 01:45:19.532  5803  5815 I BluetoothAdapterState: Entering OffState
,11-05 01:45:19.534  5803  5816 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-05 01:45:19.535  5803  5816 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-05 01:45:19.535  5803  5816 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-05 01:45:19.535  5803  5816 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-05 01:45:19.535  5803  5803 I bt_bluedroid: get_profile_interface socket
,11-05 01:45:19.537  5803  5819 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-05 01:45:19.538  5803  5803 I bt_bluedroid: get_profile_interface sdp
11-05 01:45:19.538  5803  5819 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-05 01:45:19.542  5803  5814 I bt_bluedroid: config_hci_snoop_log
11-05 01:45:19.542   927   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-05 01:45:19.546  5803  5815 D BluetoothAdapterState: Current state: OFF, message: 0
11-05 01:45:19.546  5803  5815 D BluetoothAdapterProperties: Setting state to 14
,11-05 01:45:19.546  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-05 01:45:19.548  5803  5815 D BluetoothBondStateMachine: make
,11-05 01:45:19.549  5803  5820 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-05 01:45:19.552  5803  5815 I BluetoothAdapterState: Entering PendingCommandState
,11-05 01:45:19.553  5803  5803 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-05 01:45:19.555  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
,11-05 01:45:19.555  5803  5803 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-05 01:45:19.556  5803  5803 D BtGatt.GattService: Received start request. Starting profile...
,11-05 01:45:19.556  5803  5803 D BtGatt.GattService: start()
11-05 01:45:19.556  5803  5803 I bt_bluedroid: get_profile_interface gatt
11-05 01:45:19.557  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
11-05 01:45:19.557  5803  5803 D BtGatt.AdvertiseManager: advertise manager created
,11-05 01:45:19.561  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:19.561  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:19.561  5803  5803 V BluetoothAdapterState: isBleTurningOn()=true
11-05 01:45:19.561  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:19.561  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-05 01:45:19.562  5803  5815 I bt_bluedroid: bt_bluedroid
,11-05 01:45:19.562  5803  5816 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-05 01:45:19.563  5803  5816 I bt_hci  : start_up
,11-05 01:45:19.568  5803  5816 I bt_vendor: alloc value 0xf40b7871,
11-05 01:45:19.568  5803  5816 I bt_vendor: init
11-05 01:45:19.568  5803  5816 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-05 01:45:19.568  5803  5816 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-05 01:45:19.678  5803  5816 D bt_hci  : start_up starting async portion
,11-05 01:45:19.679  5803  5823 I bt_hci  : event_finish_startup
11-05 01:45:19.679  5803  5823 I bt_hci_h4: hal_open
,11-05 01:45:19.679  5803  5823 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-05 01:45:19.682  5803  5823 I bt_userial_vendor: device fd = 54 open
,11-05 01:45:19.679  5824  5824 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-05 01:45:19.696  5803  5823 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-05 01:45:19.698  5803  5823 D bt_hwcfg: Chipset BCM4358A3
,11-05 01:45:19.698  5803  5823 D bt_hwcfg: Target name = [BCM4358A3]
11-05 01:45:19.699  5803  5823 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-05 01:45:20.081  5803  5823 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-05 01:45:20.082  5803  5823 D bt_hwcfg: Settlement delay -- 100 ms
,11-05 01:45:20.082  5803  5823 I bt_hwcfg: Setting fw settlement delay to 100 
,11-05 01:45:20.216  5803  5823 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-05 01:45:20.216  5803  5823 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-05 01:45:20.218  5803  5823 I bt_hwcfg: vendor lib fwcfg completed
,11-05 01:45:20.219  5803  5823 I bt_vendor: firmware callback
,11-05 01:45:20.219  5803  5823 I bt_hci  : firmware_config_callback
,11-05 01:45:20.227  5803  5826 I bt_btu  : btu_task pending for preload complete event
,11-05 01:45:20.227  5803  5826 I bt_btu_task: Bluetooth chip preload is complete
11-05 01:45:20.228  5803  5826 I bt_btu  : btu_task received preload complete event
,11-05 01:45:20.234  5803  5826 I         : BTE_InitTraceLevels -- TRC_HCI
11-05 01:45:20.234  5803  5826 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-05 01:45:20.234  5803  5826 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-05 01:45:20.234  5803  5826 I         : BTE_InitTraceLevels -- TRC_AVDT
11-05 01:45:20.234  5803  5826 I         : BTE_InitTraceLevels -- TRC_AVRC
11-05 01:45:20.234  5803  5826 I         : BTE_InitTraceLevels -- TRC_A2D
11-05 01:45:20.235  5803  5826 I         : BTE_InitTraceLevels -- TRC_BNEP
11-05 01:45:20.235  5803  5826 I         : BTE_InitTraceLevels -- TRC_BTM
11-05 01:45:20.235  5803  5826 I         : BTE_InitTraceLevels -- TRC_GAP
11-05 01:45:20.235  5803  5826 I         : BTE_InitTraceLevels -- TRC_PAN
11-05 01:45:20.235  5803  5826 I         : BTE_InitTraceLevels -- TRC_SDP
11-05 01:45:20.235  5803  5826 I         : BTE_InitTraceLevels -- TRC_GATT
11-05 01:45:20.235  5803  5826 I         : BTE_InitTraceLevels -- TRC_SMP
11-05 01:45:20.235  5803  5826 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-05 01:45:20.236  5803  5826 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-05 01:45:20.317  5803  5826 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4035549
,11-05 01:45:20.317  5803  5826 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4035549 
,11-05 01:45:20.333  5803  5819 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-05 01:45:20.334  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-05 01:45:20.335  5803  5819 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-05 01:45:20.337  5803  5819 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-05 01:45:20.340  5803  5819 D BluetoothAdapterProperties: Scan Mode:20
11-05 01:45:20.340  5803  5819 D BluetoothAdapterProperties: Discoverable Timeout:120
11-05 01:45:20.341  5803  5819 D bt_hci  : do_postload posting postload work item
11-05 01:45:20.341  5803  5823 I bt_hci  : event_postload
,11-05 01:45:20.341  5803  5823 I bt_vendor: sco_config_cb
,11-05 01:45:20.341  5803  5823 I bt_hci  : sco_config_callback postload finished.
,11-05 01:45:20.346  5803  5819 D bt_bte_conf: Device ID record 1 : primary
11-05 01:45:20.347  5803  5819 D bt_bte_conf:   vendorId            = 000f
11-05 01:45:20.347  5803  5819 D bt_bte_conf:   vendorIdSource      = 0001
11-05 01:45:20.348  5803  5819 D bt_bte_conf:   product             = 1200
,11-05 01:45:20.348  5803  5819 D bt_bte_conf:   version             = 1436
11-05 01:45:20.348  5803  5819 D bt_bte_conf:   clientExecutableURL = 
11-05 01:45:20.348  5803  5819 D bt_bte_conf:   serviceDescription  = 
11-05 01:45:20.348  5803  5819 D bt_bte_conf:   documentationURL    = 
11-05 01:45:20.348  5803  5819 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-05 01:45:20.349  5803  5816 D bt_stack_manager: event_start_up_stack finished
,11-05 01:45:20.349  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-05 01:45:20.350  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-05 01:45:20.351  5803  5815 D BluetoothAdapterProperties: Setting state to 15
11-05 01:45:20.351  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-05 01:45:20.352  5803  5823 I bt_vendor: low_power_mode_cb
,11-05 01:45:20.353  5803  5815 I BluetoothAdapterState: Entering BleOnState
,11-05 01:45:20.359  5803  5815 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-05 01:45:20.359  5803  5815 D BluetoothAdapterProperties: Setting state to 11
11-05 01:45:20.359  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-05 01:45:20.364  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
,11-05 01:45:20.364  5803  5803 D HeadsetService: Received start request. Starting profile...
11-05 01:45:20.368  5803  5803 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-05 01:45:20.369  5803  5803 D HeadsetStateMachine: make
11-05 01:45:20.369  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-05 01:45:20.377  5803  5815 I BluetoothAdapterState: Entering PendingCommandState
,11-05 01:45:20.380  5803  5803 D HeadsetStateMachine: max_hf_connections = 1
11-05 01:45:20.381  5803  5803 I bt_bluedroid: get_profile_interface handsfree
11-05 01:45:20.381  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-05 01:45:20.381  5803  5819 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-05 01:45:20.384  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
,11-05 01:45:20.385  5803  5803 D A2dpService: Received start request. Starting profile...
,11-05 01:45:20.386  5803  5803 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-05 01:45:20.386  5803  5803 I bt_bluedroid: get_profile_interface avrcp
,11-05 01:45:20.392  5803  5803 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-05 01:45:20.392  5803  5803 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-05 01:45:20.392  5803  5803 D A2dpStateMachine: make
,11-05 01:45:20.393  5803  5803 I bt_bluedroid: get_profile_interface a2dp
11-05 01:45:20.394  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-05 01:45:20.395  5803  5834 D A2dpStateMachine: Enter Disconnected: -2
,11-05 01:45:20.395  5803  5803 I BluetoothHidServiceJni: classInitNative: succeeds
11-05 01:45:20.396  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
,11-05 01:45:20.399  5652  5652 D BluetoothInputDevice: Proxy object connected
,11-05 01:45:20.400  5803  5803 D HidService: Received start request. Starting profile...
11-05 01:45:20.400  5803  5803 I bt_bluedroid: get_profile_interface hidhost
11-05 01:45:20.401  5803  5819 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf401656d
11-05 01:45:20.401  5803  5803 D HidService: setHidService(): set to: null
,11-05 01:45:20.401  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-05 01:45:20.401  5652  5652 D HidProfile: Bluetooth service connected
11-05 01:45:20.401  5803  5803 I BluetoothHealthServiceJni: classInitNative: succeeds
11-05 01:45:20.402  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
11-05 01:45:20.402  5803  5803 D HealthService: Received start request. Starting profile...
,11-05 01:45:20.404  5803  5803 I bt_bluedroid: get_profile_interface health
,11-05 01:45:20.404  5803  5803 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-05 01:45:20.405  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
11-05 01:45:20.406  5803  5803 D PanService: Received start request. Starting profile...
11-05 01:45:20.406  5803  5803 D BluetoothPanServiceJni: initializeNative(L110): pan
11-05 01:45:20.406  5803  5803 I bt_bluedroid: get_profile_interface pan
11-05 01:45:20.407  5803  5819 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-05 01:45:20.407  5652  5652 D BluetoothPan: BluetoothPAN Proxy object connected
11-05 01:45:20.409  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
,11-05 01:45:20.409  5652  5652 D PanProfile: Bluetooth service connected
11-05 01:45:20.410  3561  3561 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-05 01:45:20.410  5803  5803 D BluetoothMapService: Received start request. Starting profile...
11-05 01:45:20.410  5652  5652 D BluetoothMap: Proxy object connected
11-05 01:45:20.410  5803  5803 D BluetoothMapService: start()
11-05 01:45:20.411  5652  5652 D MapProfile: Bluetooth service connected
11-05 01:45:20.411  5652  5652 D BluetoothMap: getConnectedDevices()
,11-05 01:45:20.412  5652  5652 D BluetoothMap: Bluetooth is Not enabled
11-05 01:45:20.413  5803  5803 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-05 01:45:20.414  5803  5803 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-05 01:45:20.414  5803  5803 D BluetoothMapAppObserver: createReceiver()
,11-05 01:45:20.415  5803  5803 D BluetoothMapAppObserver: initObservers()
,11-05 01:45:20.415  5803  5803 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-05 01:45:20.424  5803  5803 V SapService: SapBinder()
,11-05 01:45:20.424  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
11-05 01:45:20.425  5803  5803 D SapService: Received start request. Starting profile...
11-05 01:45:20.425  5803  5803 V SapService: start()
,11-05 01:45:20.427  5803  5803 V BluetoothAdapterState: isTurningOff()=false
,11-05 01:45:20.427  5803  5803 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:20.427  5803  5832 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-05 01:45:20.427  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:20.427  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:20.427  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:20.427  5803  5803 V BluetoothAdapterState: isTurningOn()=true
,11-05 01:45:20.427  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:20.427  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:20.427  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:20.428  5803  5803 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:20.428  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:20.428  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
,11-05 01:45:20.428  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:20.428  5803  5803 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:20.428  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:20.428  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:20.428  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:20.428  5803  5803 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:20.428  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:20.428  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:20.429  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:20.429  5803  5803 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:20.429  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:20.429  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
,11-05 01:45:20.429  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:20.430  5803  5803 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:20.430  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:20.430  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
,11-05 01:45:20.430  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-05 01:45:20.430  5803  5815 D BluetoothAdapterProperties: ScanMode =  20
11-05 01:45:20.430  5803  5815 D BluetoothAdapterProperties: State =  11
11-05 01:45:20.430  5803  5815 D BluetoothAdapterProperties: Setting state to 12
11-05 01:45:20.430  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-05 01:45:20.431   927   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-05 01:45:20.431  5803  5819 D BluetoothAdapterProperties: Scan Mode:21
11-05 01:45:20.431  3108  3120 D BluetoothPan: onBluetoothStateChange on: true
11-05 01:45:20.431  5803  5819 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-05 01:45:20.432  5803  5815 I BluetoothAdapterState: Entering OnState
11-05 01:45:20.432  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-05 01:45:20.434  3108  3108 D BluetoothPan: BluetoothPAN Proxy object connected
11-05 01:45:20.434  3108  3108 D PanProfile: Bluetooth service connected
11-05 01:45:20.434   927   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-05 01:45:20.435  3108  3975 D BluetoothPbap: onBluetoothStateChange: up=true
,11-05 01:45:20.436   927   927 D BluetoothA2dp: Proxy object connected
11-05 01:45:20.436  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-05 01:45:20.436  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:45:20.436  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:45:20.436  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-05 01:45:20.436  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-05 01:45:20.436  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-05 01:45:20.436  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-05 01:45:20.436  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-05 01:45:20.437   927   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-05 01:45:20.437  3108  3121 D BluetoothMap: onBluetoothStateChange: up=true
11-05 01:45:20.438  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-05 01:45:20.439  3108  3108 D BluetoothMap: Proxy object connected
11-05 01:45:20.439  5652  5664 D BluetoothPbap: onBluetoothStateChange: up=true
,11-05 01:45:20.439  3108  3108 D MapProfile: Bluetooth service connected
11-05 01:45:20.439  3108  3108 D BluetoothMap: getConnectedDevices()
,11-05 01:45:20.440  3108  3121 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-05 01:45:20.441  3108  3108 D BluetoothInputDevice: Proxy object connected
,11-05 01:45:20.441  5652  5666 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-05 01:45:20.441  3108  3108 D HidProfile: Bluetooth service connected
11-05 01:45:20.442  5803  5803 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-05 01:45:20.442  3763  3791 D BluetoothHeadset: onBluetoothStateChange: up=true
11-05 01:45:20.442  5652  5664 D BluetoothMap: onBluetoothStateChange: up=true
11-05 01:45:20.442  5803  5803 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-05 01:45:20.442   927   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-05 01:45:20.443  5652  5666 D BluetoothPan: onBluetoothStateChange on: true
11-05 01:45:20.443  3108  3120 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-05 01:45:20.443  3108  3121 D BluetoothA2dp: onBluetoothStateChange: up=true
11-05 01:45:20.444  5803  5803 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-05 01:45:20.446  5803  5803 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-05 01:45:20.446  3108  3108 D BluetoothA2dp: Proxy object connected
11-05 01:45:20.447   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-05 01:45:20.447  5803  5803 D ObexServerSockets: Succeed to create listening sockets 
11-05 01:45:20.447  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-05 01:45:20.448  5803  5803 D ObexServerSockets0: startAccept()
11-05 01:45:20.448  5803  5803 D ObexServerSockets0: prepareForNewConnect()
,11-05 01:45:20.449  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-05 01:45:20.450  5803  5840 D ObexServerSockets0: Accepting socket connection...
11-05 01:45:20.450  5803  5803 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-05 01:45:20.450  5803  5803 D BluetoothSdpJni: SDP Create record success - handle: 0
11-05 01:45:20.451  5803  5803 D BluetoothMapService: onReceive
11-05 01:45:20.451  5803  5841 D ObexServerSockets0: Accepting socket connection...
11-05 01:45:20.451  5803  5803 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-05 01:45:20.451  5803  5803 D BluetoothMapService: STATE_ON
11-05 01:45:20.451  5652  5652 D LocalBluetoothProfileManager: Adding local A2DP profile
11-05 01:45:20.453  5803  5842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-05 01:45:20.454  5803  5842 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-05 01:45:20.454  5803  5842 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-05 01:45:20.455  5652  5652 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-05 01:45:20.461  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-05 01:45:20.462  5652  5652 D BluetoothA2dp: Proxy object connected
,11-05 01:45:20.468  3561  3561 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-05 01:45:20.472  5652  5652 D DockEventReceiver: finishStartingService: stopping service
,11-05 01:45:20.475  3108  3108 D BluetoothPbap: Proxy object connected
,11-05 01:45:20.475  5652  5652 D BluetoothPbap: Proxy object connected
11-05 01:45:20.475  3108  3108 D PbapServerProfile: Bluetooth service connected
11-05 01:45:20.475  5803  5803 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-05 01:45:20.475  5803  5803 D ObexServerSockets0: prepareForNewConnect()
11-05 01:45:20.475  5652  5652 D PbapServerProfile: Bluetooth service connected
,11-05 01:45:20.483  5803  5846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-05 01:45:20.496  5803  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-05 01:45:20.499  5803  5850 I BtOppRfcommListener: Accept thread started.
,11-05 01:45:20.532   927   927 D BluetoothHeadset: Proxy object connected
11-05 01:45:20.533  3108  3121 D BluetoothHeadset: Proxy object connected
,11-05 01:45:20.533  3108  3108 D HeadsetProfile: Bluetooth service connected
11-05 01:45:20.533   927   927 D BluetoothHeadset: Proxy object connected
11-05 01:45:20.533   927   927 D BluetoothHeadset: Proxy object connected
11-05 01:45:20.533  3763  3992 D BluetoothHeadset: Proxy object connected
,11-05 01:45:20.538   927   945 D BluetoothHeadset: Proxy object connected
,11-05 01:45:20.542  3763  3809 D BluetoothHeadset: Proxy object connected
,11-05 01:45:20.542   927   945 D BluetoothHeadset: Proxy object connected
,11-05 01:45:20.544  3108  3975 D BluetoothHeadset: Proxy object connected
,11-05 01:45:20.544  3108  3108 D HeadsetProfile: Bluetooth service connected
,11-05 01:45:20.557  5652  5666 D BluetoothHeadset: Proxy object connected
,11-05 01:45:20.558  5652  5652 D HeadsetProfile: Bluetooth service connected
,11-05 01:45:20.573  3621  3839 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-05 01:45:20.573  3621  3839 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-05 01:45:20.584  3561  3561 I ConfigService: onCreate
,11-05 01:45:22.183   927  2954 D ConnectivityService: handlePromptUnvalidated 101
,11-05 01:45:24.412  5803  5815 D BluetoothAdapterState: Current state: ON, message: 23
11-05 01:45:24.412  5803  5815 D BluetoothAdapterProperties: Setting state to 13
,11-05 01:45:24.413  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-05 01:45:24.414  5803  5815 D BluetoothAdapterProperties: onBluetoothDisable()
11-05 01:45:24.417  5803  5815 I BluetoothAdapterState: Entering PendingCommandState
,11-05 01:45:24.420  5803  5803 D BluetoothMapService: onReceive
,11-05 01:45:24.421  5803  5803 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-05 01:45:24.421  5803  5803 D BluetoothMapService: STATE_TURNING_OFF
11-05 01:45:24.421  5803  5803 D BluetoothMapService: MAP Service closeService in
11-05 01:45:24.422  5803  5803 D BluetoothMapMasInstance0: MAP Service shutdown
11-05 01:45:24.422  5803  5803 D ObexServerSockets0: shutdown(block = true)
11-05 01:45:24.423  5803  5803 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-05 01:45:24.423  5803  5803 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-05 01:45:24.423  5803  5828 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-05 01:45:24.425  5803  5819 D BluetoothAdapterProperties: Scan Mode:20
11-05 01:45:24.425  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-05 01:45:24.426  5803  5841 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-05 01:45:24.426  5803  5840 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-05 01:45:24.426  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-05 01:45:24.427  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-05 01:45:24.427  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-05 01:45:24.427  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:45:24.427  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:45:24.427  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-05 01:45:24.427  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-05 01:45:24.427  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-05 01:45:24.427  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-05 01:45:24.427  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-05 01:45:24.428  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-05 01:45:24.428  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-05 01:45:24.430  5803  5803 I BtOppRfcommListener: stopping Accept Thread
11-05 01:45:24.431  5803  5850 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-05 01:45:24.431  5803  5850 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-05 01:45:24.433  5652  5652 D DockEventReceiver: finishStartingService: stopping service
11-05 01:45:24.434  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:45:24.435  5803  5803 D HeadsetService: Received stop request...Stopping profile...
11-05 01:45:24.436   927   927 D BluetoothHeadset: Proxy object disconnected
11-05 01:45:24.437  3108  3121 D BluetoothHeadset: Proxy object disconnected
11-05 01:45:24.437   927   927 D BluetoothHeadset: Proxy object disconnected
11-05 01:45:24.437   927   927 D BluetoothHeadset: Proxy object disconnected
11-05 01:45:24.438  3763  4117 D BluetoothHeadset: Proxy object disconnected
11-05 01:45:24.439  5652  5666 D BluetoothHeadset: Proxy object disconnected
11-05 01:45:24.439  5652  5652 D HeadsetProfile: Bluetooth service disconnected
11-05 01:45:24.441  3108  3108 D HeadsetProfile: Bluetooth service disconnected
,11-05 01:45:24.443  5803  5803 D A2dpService: Received stop request...Stopping profile...
,11-05 01:45:24.444  5803  5834 D A2dpStateMachine: Exit Disconnected: -1
11-05 01:45:24.444  3561  3561 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-05 01:45:24.445   927   927 D BluetoothA2dp: Proxy object disconnected
11-05 01:45:24.445  3108  3108 D BluetoothA2dp: Proxy object disconnected
11-05 01:45:24.445  5652  5652 D BluetoothA2dp: Proxy object disconnected
11-05 01:45:24.447  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-05 01:45:24.447  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:24.447  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
,11-05 01:45:24.447  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:24.448  5803  5803 D HidService: Received stop request...Stopping profile...
11-05 01:45:24.448  5803  5803 D HidService: Stopping Bluetooth HidService
11-05 01:45:24.449  3108  3108 D BluetoothInputDevice: Proxy object disconnected
11-05 01:45:24.449  3108  3108 D HidProfile: Bluetooth service disconnected
11-05 01:45:24.449  5652  5652 D BluetoothInputDevice: Proxy object disconnected
11-05 01:45:24.449  5652  5652 D HidProfile: Bluetooth service disconnected
11-05 01:45:24.450  5803  5803 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-05 01:45:24.450  5803  5803 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-05 01:45:24.450  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-05 01:45:24.450  5803  5826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-05 01:45:24.450  5803  5826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-05 01:45:24.450  5803  5826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-05 01:45:24.451  5803  5819 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-05 01:45:24.451  5803  5803 D HealthService: Received stop request...Stopping profile...
11-05 01:45:24.453  5803  5803 D PanService: Received stop request...Stopping profile...
,11-05 01:45:24.454  5803  5803 D BluetoothMapService: Received stop request...Stopping profile...
,11-05 01:45:24.454  5803  5803 D BluetoothMapService: stop()
11-05 01:45:24.454  5652  5652 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-05 01:45:24.454  5652  5652 D PanProfile: Bluetooth service disconnected
11-05 01:45:24.455  5803  5803 D BluetoothMapAppObserver: deinitObservers()
11-05 01:45:24.455  5803  5803 D BluetoothMapAppObserver: removeReceiver()
11-05 01:45:24.456  5652  5652 D BluetoothMap: Proxy object disconnected
11-05 01:45:24.457  5652  5652 D MapProfile: Bluetooth service disconnected
,11-05 01:45:24.457  3108  3108 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-05 01:45:24.457  3108  3108 D PanProfile: Bluetooth service disconnected
11-05 01:45:24.457  3108  3108 D BluetoothMap: Proxy object disconnected
11-05 01:45:24.457  5652  5652 D BluetoothPbap: Proxy object disconnected
11-05 01:45:24.457  3108  3108 D MapProfile: Bluetooth service disconnected
11-05 01:45:24.458  5652  5652 D PbapServerProfile: Bluetooth service disconnected
11-05 01:45:24.458  3108  3108 D BluetoothPbap: Proxy object disconnected
11-05 01:45:24.458  3108  3108 D PbapServerProfile: Bluetooth service disconnected
11-05 01:45:24.458  5803  5803 D SapService: Received stop request...Stopping profile...
11-05 01:45:24.458  5803  5803 V SapService: stop()
11-05 01:45:24.459  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-05 01:45:24.459  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:24.459  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:24.459  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:24.460  5803  5826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-05 01:45:24.460  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-05 01:45:24.461  5803  5826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-05 01:45:24.461  5803  5826 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-05 01:45:24.461  5803  5826 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-05 01:45:24.461  5803  5826 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-05 01:45:24.461  5803  5826 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-05 01:45:24.461  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-05 01:45:24.461  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:24.461  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:24.461  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:24.462  5803  5803 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-05 01:45:24.462  5803  5803 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-05 01:45:24.463  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-05 01:45:24.463  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:24.463  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:24.463  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:24.463  5803  5803 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-05 01:45:24.463  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-05 01:45:24.463  5803  5819 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-05 01:45:24.464  5803  5803 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-05 01:45:24.464  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-05 01:45:24.464  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:24.464  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:24.464  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:24.464  5803  5803 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-05 01:45:24.464  5803  5803 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-05 01:45:24.465  5803  5803 D BluetoothMapService: MAP Service closeService in
11-05 01:45:24.465  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-05 01:45:24.466  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:24.466  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:24.466  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:24.466  5803  5803 D BluetoothMapService: cleanup()
11-05 01:45:24.466  5803  5803 D BluetoothMapService: MAP Service closeService in
,11-05 01:45:24.467  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-05 01:45:24.467  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:24.467  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:24.467  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:24.467  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-05 01:45:24.467  5803  5815 D BluetoothAdapterProperties: Setting state to 15
11-05 01:45:24.467  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-05 01:45:24.468  5803  5815 I BluetoothAdapterState: Entering BleOnState
,11-05 01:45:24.468  5652  5664 D BluetoothA2dp: onBluetoothStateChange: up=false
11-05 01:45:24.469   927   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-05 01:45:24.470  5652  5666 D BluetoothHeadset: onBluetoothStateChange: up=false
11-05 01:45:24.470  3108  3120 D BluetoothPan: onBluetoothStateChange on: false
11-05 01:45:24.471   927   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-05 01:45:24.471  3108  3975 D BluetoothPbap: onBluetoothStateChange: up=false
11-05 01:45:24.471   927   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-05 01:45:24.472  3108  3121 D BluetoothMap: onBluetoothStateChange: up=false
11-05 01:45:24.472  5652  5664 D BluetoothPbap: onBluetoothStateChange: up=false
,11-05 01:45:24.473  3108  3120 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-05 01:45:24.474  5652  5666 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-05 01:45:24.474  3763  3791 D BluetoothHeadset: onBluetoothStateChange: up=false
11-05 01:45:24.474  5652  5664 D BluetoothMap: onBluetoothStateChange: up=false
11-05 01:45:24.475   927   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-05 01:45:24.475  5652  5666 D BluetoothPan: onBluetoothStateChange on: false
11-05 01:45:24.476  3108  3975 D BluetoothHeadset: onBluetoothStateChange: up=false
11-05 01:45:24.476  3108  3121 D BluetoothA2dp: onBluetoothStateChange: up=false
11-05 01:45:24.477  5803  5815 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-05 01:45:24.477  5803  5815 D BluetoothAdapterProperties: Setting state to 16
11-05 01:45:24.477  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-05 01:45:24.477  5803  5815 D BluetoothAdapterProperties: onBleDisable
11-05 01:45:24.477  5803  5815 I BluetoothAdapterState: Entering PendingCommandState
11-05 01:45:24.477  5803  5816 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-05 01:45:24.480  5803  5819 D BluetoothAdapterProperties: Scan Mode:20
11-05 01:45:24.480  5803  5826 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-05 01:45:24.480  5803  5826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-05 01:45:24.480  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:45:24.481  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-05 01:45:24.482  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-05 01:45:24.485  3561  3561 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-05 01:45:24.486  5652  5652 D DockEventReceiver: finishStartingService: stopping service
,11-05 01:45:24.694  5803  5819 I bt_hci  : shut_down
,11-05 01:45:24.706  5803  5823 D bt_hwcfg: hw_epilog_process
,11-05 01:45:24.706  5803  5823 I bt_vendor: low_power_mode_cb
,11-05 01:45:24.709  5803  5823 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-05 01:45:24.709  5803  5823 I bt_vendor: epilog_cb
,11-05 01:45:24.709  5803  5823 I bt_hci  : epilog_finished_callback
,11-05 01:45:24.714  5803  5819 I bt_hci_h4: hal_close
,11-05 01:45:24.715  5803  5819 I bt_userial_vendor: device fd = 54 close
,11-05 01:45:24.837  5803  5816 D bt_stack_manager: event_shut_down_stack finished.
,11-05 01:45:24.838  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-05 01:45:24.843  5803  5815 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-05 01:45:24.843  5803  5803 D BtGatt.DebugUtils: handleDebugAction() action=null
11-05 01:45:24.845  5803  5803 D BtGatt.GattService: Received stop request...Stopping profile...
11-05 01:45:24.845  5803  5803 D BtGatt.GattService: stop()
11-05 01:45:24.845  5803  5803 D BtGatt.AdvertiseManager: advertise clients cleared
,11-05 01:45:24.849  5803  5803 V BluetoothAdapterState: isTurningOff()=false
,11-05 01:45:24.849  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:24.849  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:24.849  5803  5803 V BluetoothAdapterState: isBleTurningOff()=true
11-05 01:45:24.850  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-05 01:45:24.851  5803  5815 D BluetoothAdapterProperties: Setting state to 10
11-05 01:45:24.851  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-05 01:45:24.852  5803  5815 I BluetoothAdapterState: Entering OffState
,11-05 01:45:24.855   927   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-05 01:45:24.870  5803  5803 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-05 01:45:24.871  5803  5803 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-05 01:45:24.871  5803  5803 I BluetoothServiceJni: cleanupNative: return from cleanup
11-05 01:45:24.874  5803  5816 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-05 01:45:24.879  5803  5803 I art     : System.exit called, status: 0
,11-05 01:45:24.879  5803  5803 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-05 01:45:24.881   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:24.906   927  3138 I ActivityManager: Process com.android.bluetooth (pid 5803) has died
,11-05 01:45:25.608  3561  3561 I ConfigService: onDestroy
,11-05 01:45:25.882   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:26.883   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:27.884   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:28.885   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:29.413  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:45:29.413  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-05 01:45:29.420  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:45:29.420  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@162a0f1 removed from the list
,11-05 01:45:29.420  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
,11-05 01:45:29.423  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-05 01:45:29.423  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59dee44 added. We now have 4 listener(s)
,11-05 01:45:29.424  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-05 01:45:29.425  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:45:29.426  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59dee44 removed from the list
11-05 01:45:29.426  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
,11-05 01:45:29.428  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:45:29.428  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f6f5b2d added. We now have 4 listener(s)
11-05 01:45:29.428  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-05 01:45:29.885   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-05 01:45:33.019  3138  3138 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32458]" dev="sockfs" ino=32458 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-05 01:45:33.022  3138  3138 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32458]" dev="sockfs" ino=32458 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-05 01:45:33.015   927   948 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-05 01:45:33.028  3621  3621 I Keyboard.Facilitator: onFinishInput()
,11-05 01:45:33.035   927   948 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-05 01:45:33.035   927   948 I Adreno  : Build Date                       : 12/06/15
11-05 01:45:33.035   927   948 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-05 01:45:33.035   927   948 I Adreno  : Local Branch                     : mybranch17112971
11-05 01:45:33.035   927   948 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-05 01:45:33.035   927   948 I Adreno  : Remote Branch                    : NONE
11-05 01:45:33.035   927   948 I Adreno  : Reconstruct Branch               : NOTHING
,11-05 01:45:33.073   385   775 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (184 us)
,11-05 01:45:33.790  5593  5593 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-05 01:45:33.790  5593  5593 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-05 01:45:33.817   927   948 I sensors : batch
,11-05 01:45:33.818   927   948 V KeyguardServiceDelegate: onScreenTurnedOff()
11-05 01:45:33.820  5593  5593 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bd65244 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1ffb862, 16908290=android.view.AbsSavedState$1@1ffb862}, android:focusedViewId=100}]}]
11-05 01:45:33.820  5593  5593 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,11-05 01:45:33.820  5593  5593 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-05 01:45:33.820  5593  5593 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-05 01:45:33.822   927   948 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-05 01:45:33.822   927   948 I sensors : activate
,11-05 01:45:33.824   927   946 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-05 01:45:33.824   385   385 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f7bc03c00
11-05 01:45:33.824   385   385 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,11-05 01:45:33.827   927  2705 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
11-05 01:45:33.828   927  2705 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-05 01:45:34.133   385   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-05 01:45:34.135   385   385 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-05 01:45:34.143   927  3064 D SurfaceControl: Excessive delay in setPowerMode(): 318ms
,11-05 01:45:34.162   927   948 I DreamManagerService: Entering dreamland.
,11-05 01:45:34.162   927   948 I PowerManagerService: Dozing...
11-05 01:45:34.163   927   943 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-05 01:45:34.179   938   938 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[35015]" dev="sockfs" ino=35015 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-05 01:45:34.179   938   938 W Binder_1: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[35015]" dev="sockfs" ino=35015 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-05 01:45:34.183   927  3119 I sensors : batch
11-05 01:45:34.183   927  3119 I sensors : activate
,11-05 01:45:34.188   927  2705 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
11-05 01:45:34.188   927  2705 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-05 01:45:34.190   511  3000 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-05 01:45:34.211  3763  4729 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
11-05 01:45:34.211  3763  4729 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
,11-05 01:45:34.211  3763  4729 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-05 01:45:34.211   524  1158 D         : oem-qmi: Connection accepted
11-05 01:45:34.212   524  1158 D         : oem-qmi: Waiting to accept connection
,11-05 01:45:34.214   927   927 I sensors : activate
,11-05 01:45:34.215   511   511 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-05 01:45:34.218   927  2705 I hubconnection: sensorhub said: 'activate 31 enable:0'
11-05 01:45:34.218  3763  4729 D         : oem_qmi_lib:output 0
11-05 01:45:34.218  3763  4729 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-05 01:45:34.241  3763  4729 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-05 01:45:34.241  3763  4729 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-05 01:45:34.241  3763  4729 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-05 01:45:34.241   524  1158 D         : oem-qmi: Connection accepted
11-05 01:45:34.241   524  1158 D         : oem-qmi: Waiting to accept connection
,11-05 01:45:34.247  3763  4729 D         : oem_qmi_lib:output 0
,11-05 01:45:34.247  3763  4729 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-05 01:45:34.437  5593  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-05 01:45:34.470   927   945 I ActivityManager: Start proc 5866:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-05 01:45:34.541  5866  5866 D AdapterServiceConfig: Adding HeadsetService
,11-05 01:45:34.541  5866  5866 D AdapterServiceConfig: Adding A2dpService
11-05 01:45:34.541  5866  5866 D AdapterServiceConfig: Adding HidService
11-05 01:45:34.541  5866  5866 D AdapterServiceConfig: Adding HealthService
11-05 01:45:34.542  5866  5866 D AdapterServiceConfig: Adding PanService
11-05 01:45:34.542  5866  5866 D AdapterServiceConfig: Adding GattService
11-05 01:45:34.542  5866  5866 D AdapterServiceConfig: Adding BluetoothMapService
11-05 01:45:34.542  5866  5866 D AdapterServiceConfig: Adding SapService
,11-05 01:45:34.553   927   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dbee354:true
,11-05 01:45:34.553  5866  5866 D BluetoothAdapterState: make() - Creating AdapterState
,11-05 01:45:34.556  5866  5866 I bt_bluedroid: init
,11-05 01:45:34.557  5866  5878 I BluetoothAdapterState: Entering OffState
,11-05 01:45:34.558  5866  5879 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-05 01:45:34.559  5866  5879 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-05 01:45:34.559  5866  5879 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-05 01:45:34.559  5866  5879 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-05 01:45:34.559  5866  5866 I bt_bluedroid: get_profile_interface socket
,11-05 01:45:34.561  5866  5882 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-05 01:45:34.562  5866  5866 I bt_bluedroid: get_profile_interface sdp
11-05 01:45:34.562  5866  5882 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-05 01:45:34.566  5866  5877 I bt_bluedroid: config_hci_snoop_log
11-05 01:45:34.567   927   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-05 01:45:34.571  5866  5878 D BluetoothAdapterState: Current state: OFF, message: 0
11-05 01:45:34.571  5866  5878 D BluetoothAdapterProperties: Setting state to 14
11-05 01:45:34.571  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-05 01:45:34.573  5866  5878 D BluetoothBondStateMachine: make
,11-05 01:45:34.574  5866  5883 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-05 01:45:34.578  5866  5878 I BluetoothAdapterState: Entering PendingCommandState
,11-05 01:45:34.579  5866  5866 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-05 01:45:34.581  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
,11-05 01:45:34.582  5866  5866 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-05 01:45:34.583  5866  5866 D BtGatt.GattService: Received start request. Starting profile...
11-05 01:45:34.583  5866  5866 D BtGatt.GattService: start()
11-05 01:45:34.583  5866  5866 I bt_bluedroid: get_profile_interface gatt
,11-05 01:45:34.584  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
11-05 01:45:34.584  5866  5866 D BtGatt.AdvertiseManager: advertise manager created
,11-05 01:45:34.593  5866  5866 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:34.593  5866  5866 V BluetoothAdapterState: isTurningOn()=false
11-05 01:45:34.593  5866  5866 V BluetoothAdapterState: isBleTurningOn()=true
,11-05 01:45:34.593  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
,11-05 01:45:34.593  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-05 01:45:34.595  5866  5878 I bt_bluedroid: bt_bluedroid
11-05 01:45:34.595  5866  5879 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-05 01:45:34.595  5866  5879 I bt_hci  : start_up
,11-05 01:45:34.600  5866  5879 I bt_vendor: alloc value 0xf40b7871
,11-05 01:45:34.600  5866  5879 I bt_vendor: init
11-05 01:45:34.600  5866  5879 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-05 01:45:34.600  5866  5879 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-05 01:45:34.709  5866  5879 D bt_hci  : start_up starting async portion
11-05 01:45:34.709  5866  5886 I bt_hci  : event_finish_startup
,11-05 01:45:34.709  5866  5886 I bt_hci_h4: hal_open
,11-05 01:45:34.709  5866  5886 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-05 01:45:34.711  5866  5886 I bt_userial_vendor: device fd = 54 open
,11-05 01:45:34.709  5887  5887 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-05 01:45:34.724  5866  5886 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-05 01:45:34.727  5866  5886 D bt_hwcfg: Chipset BCM4358A3
,11-05 01:45:34.727  5866  5886 D bt_hwcfg: Target name = [BCM4358A3]
11-05 01:45:34.727  5866  5886 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-05 01:45:35.127  5866  5886 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-05 01:45:35.127  5866  5886 D bt_hwcfg: Settlement delay -- 100 ms
11-05 01:45:35.127  5866  5886 I bt_hwcfg: Setting fw settlement delay to 100 
,11-05 01:45:35.262  5866  5886 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-05 01:45:35.263  5866  5886 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-05 01:45:35.264  5866  5886 I bt_hwcfg: vendor lib fwcfg completed
11-05 01:45:35.264  5866  5886 I bt_vendor: firmware callback
11-05 01:45:35.264  5866  5886 I bt_hci  : firmware_config_callback
,11-05 01:45:35.274  5866  5889 I bt_btu  : btu_task pending for preload complete event
,11-05 01:45:35.274  5866  5889 I bt_btu_task: Bluetooth chip preload is complete
,11-05 01:45:35.274  5866  5889 I bt_btu  : btu_task received preload complete event
,11-05 01:45:35.281  5866  5889 I         : BTE_InitTraceLevels -- TRC_HCI
,11-05 01:45:35.281  5866  5889 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-05 01:45:35.281  5866  5889 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-05 01:45:35.281  5866  5889 I         : BTE_InitTraceLevels -- TRC_AVDT
11-05 01:45:35.282  5866  5889 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-05 01:45:35.282  5866  5889 I         : BTE_InitTraceLevels -- TRC_A2D
11-05 01:45:35.282  5866  5889 I         : BTE_InitTraceLevels -- TRC_BNEP
11-05 01:45:35.282  5866  5889 I         : BTE_InitTraceLevels -- TRC_BTM
,11-05 01:45:35.282  5866  5889 I         : BTE_InitTraceLevels -- TRC_GAP
11-05 01:45:35.282  5866  5889 I         : BTE_InitTraceLevels -- TRC_PAN
11-05 01:45:35.282  5866  5889 I         : BTE_InitTraceLevels -- TRC_SDP
,11-05 01:45:35.283  5866  5889 I         : BTE_InitTraceLevels -- TRC_GATT
11-05 01:45:35.283  5866  5889 I         : BTE_InitTraceLevels -- TRC_SMP
11-05 01:45:35.283  5866  5889 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-05 01:45:35.283  5866  5889 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-05 01:45:35.365  5866  5889 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4035549
,11-05 01:45:35.365  5866  5889 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4035549 
,11-05 01:45:35.382  5866  5882 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-05 01:45:35.383  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-05 01:45:35.383  5866  5882 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-05 01:45:35.386  5866  5882 D BluetoothAdapterProperties: Name is: Nexus 6P
11-05 01:45:35.388  5866  5882 D BluetoothAdapterProperties: Scan Mode:20
,11-05 01:45:35.388  5866  5882 D BluetoothAdapterProperties: Discoverable Timeout:120
11-05 01:45:35.388  5866  5882 D bt_hci  : do_postload posting postload work item
11-05 01:45:35.389  5866  5886 I bt_hci  : event_postload
11-05 01:45:35.389  5866  5886 I bt_vendor: sco_config_cb
11-05 01:45:35.389  5866  5886 I bt_hci  : sco_config_callback postload finished.
,11-05 01:45:35.391  5866  5882 D bt_bte_conf: Device ID record 1 : primary
11-05 01:45:35.391  5866  5882 D bt_bte_conf:   vendorId            = 000f
,11-05 01:45:35.391  5866  5882 D bt_bte_conf:   vendorIdSource      = 0001
11-05 01:45:35.392  5866  5882 D bt_bte_conf:   product             = 1200
,11-05 01:45:35.392  5866  5882 D bt_bte_conf:   version             = 1436
,11-05 01:45:35.392  5866  5882 D bt_bte_conf:   clientExecutableURL = 
,11-05 01:45:35.392  5866  5882 D bt_bte_conf:   serviceDescription  = 
11-05 01:45:35.392  5866  5882 D bt_bte_conf:   documentationURL    = 
,11-05 01:45:35.392  5866  5882 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-05 01:45:35.393  5866  5879 D bt_stack_manager: event_start_up_stack finished
11-05 01:45:35.394  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-05 01:45:35.394  5866  5878 D BluetoothAdapterProperties: Setting state to 15
11-05 01:45:35.394  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-05 01:45:35.396  5866  5878 I BluetoothAdapterState: Entering BleOnState
,11-05 01:45:35.398  5866  5886 I bt_vendor: low_power_mode_cb
,11-05 01:45:35.402  5866  5878 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-05 01:45:35.403  5866  5878 D BluetoothAdapterProperties: Setting state to 11
11-05 01:45:35.403  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-05 01:45:35.411  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
,11-05 01:45:35.411  5866  5866 D HeadsetService: Received start request. Starting profile...
11-05 01:45:35.414  5866  5866 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-05 01:45:35.415  5866  5866 D HeadsetStateMachine: make
,11-05 01:45:35.428  5866  5878 I BluetoothAdapterState: Entering PendingCommandState
,11-05 01:45:35.428  5866  5866 D HeadsetStateMachine: max_hf_connections = 1
,11-05 01:45:35.429  5866  5866 I bt_bluedroid: get_profile_interface handsfree
11-05 01:45:35.430  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-05 01:45:35.430  5866  5882 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-05 01:45:35.435  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
,11-05 01:45:35.435  5866  5866 D A2dpService: Received start request. Starting profile...
11-05 01:45:35.436  5866  5866 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-05 01:45:35.436  5866  5866 I bt_bluedroid: get_profile_interface avrcp
,11-05 01:45:35.441  5866  5866 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-05 01:45:35.441  5866  5866 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-05 01:45:35.441  5866  5866 D A2dpStateMachine: make
11-05 01:45:35.442  5866  5866 I bt_bluedroid: get_profile_interface a2dp
,11-05 01:45:35.443  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-05 01:45:35.444  5866  5896 D A2dpStateMachine: Enter Disconnected: -2
,11-05 01:45:35.446  5866  5866 I BluetoothHidServiceJni: classInitNative: succeeds
,11-05 01:45:35.447  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
,11-05 01:45:35.447  3561  3561 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-05 01:45:35.448  5866  5866 D HidService: Received start request. Starting profile...
11-05 01:45:35.448  5866  5866 I bt_bluedroid: get_profile_interface hidhost
11-05 01:45:35.448  5866  5866 D HidService: setHidService(): set to: null
11-05 01:45:35.449  5866  5882 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf401656d
11-05 01:45:35.449  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-05 01:45:35.449  5866  5866 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-05 01:45:35.450  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
11-05 01:45:35.451  5866  5866 D HealthService: Received start request. Starting profile...
,11-05 01:45:35.452  5866  5866 I bt_bluedroid: get_profile_interface health
,11-05 01:45:35.453  5866  5866 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-05 01:45:35.454  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
,11-05 01:45:35.454  5866  5866 D PanService: Received start request. Starting profile...
11-05 01:45:35.455  5866  5866 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-05 01:45:35.455  5866  5866 I bt_bluedroid: get_profile_interface pan
11-05 01:45:35.455  5866  5882 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-05 01:45:35.457  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
11-05 01:45:35.457  5866  5866 D BluetoothMapService: Received start request. Starting profile...
11-05 01:45:35.457  5866  5866 D BluetoothMapService: start()
11-05 01:45:35.459  5866  5866 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-05 01:45:35.460  5866  5866 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-05 01:45:35.460  5866  5866 D BluetoothMapAppObserver: createReceiver()
,11-05 01:45:35.462  5866  5866 D BluetoothMapAppObserver: initObservers()
,11-05 01:45:35.462  5866  5866 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-05 01:45:35.471  5866  5866 V SapService: SapBinder()
11-05 01:45:35.471  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
,11-05 01:45:35.471  5866  5866 D SapService: Received start request. Starting profile...
11-05 01:45:35.472  5866  5866 V SapService: start()
,11-05 01:45:35.473  5866  5866 V BluetoothAdapterState: isTurningOff()=false
,11-05 01:45:35.473  5866  5866 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:35.473  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:35.473  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:35.474  5866  5866 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:35.474  5866  5866 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:35.474  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
,11-05 01:45:35.474  5866  5894 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-05 01:45:35.474  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:35.474  5866  5866 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:35.474  5866  5866 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:35.474  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:35.474  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
,11-05 01:45:35.475  5866  5866 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:35.475  5866  5866 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:35.475  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:35.475  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:35.475  5866  5866 V BluetoothAdapterState: isTurningOff()=false
,11-05 01:45:35.476  5866  5866 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:35.476  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:35.476  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:35.476  5866  5866 V BluetoothAdapterState: isTurningOff()=false
11-05 01:45:35.476  5866  5866 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:35.476  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:35.476  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
,11-05 01:45:35.477  5866  5866 V BluetoothAdapterState: isTurningOff()=false
,11-05 01:45:35.477  5866  5866 V BluetoothAdapterState: isTurningOn()=true
11-05 01:45:35.477  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
11-05 01:45:35.477  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
11-05 01:45:35.477  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-05 01:45:35.477  5866  5878 D BluetoothAdapterProperties: ScanMode =  20
11-05 01:45:35.477  5866  5878 D BluetoothAdapterProperties: State =  11
11-05 01:45:35.478  5866  5878 D BluetoothAdapterProperties: Setting state to 12
11-05 01:45:35.478  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-05 01:45:35.478  5866  5878 I BluetoothAdapterState: Entering OnState
11-05 01:45:35.478  5866  5882 D BluetoothAdapterProperties: Scan Mode:21
11-05 01:45:35.478  5652  5664 D BluetoothA2dp: onBluetoothStateChange: up=true
11-05 01:45:35.478  5866  5882 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-05 01:45:35.480   927   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-05 01:45:35.481  5652  5666 D BluetoothHeadset: onBluetoothStateChange: up=true
11-05 01:45:35.482  3108  3121 D BluetoothPan: onBluetoothStateChange on: true
11-05 01:45:35.483   927   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-05 01:45:35.484   927   927 D BluetoothA2dp: Proxy object connected
11-05 01:45:35.484  3108  3975 D BluetoothPbap: onBluetoothStateChange: up=true
11-05 01:45:35.484  3108  3108 D BluetoothPan: BluetoothPAN Proxy object connected
11-05 01:45:35.484  3108  3108 D PanProfile: Bluetooth service connected
,11-05 01:45:35.485   927   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-05 01:45:35.485  3108  3120 D BluetoothMap: onBluetoothStateChange: up=true
11-05 01:45:35.487  5866  5866 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-05 01:45:35.487  5652  5664 D BluetoothPbap: onBluetoothStateChange: up=true
11-05 01:45:35.487  5866  5866 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-05 01:45:35.488  3108  3121 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-05 01:45:35.488  5866  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-05 01:45:35.490  5652  5652 D BluetoothA2dp: Proxy object connected
11-05 01:45:35.490  5866  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-05 01:45:35.490  5652  5666 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-05 01:45:35.491  5866  5866 D ObexServerSockets: Succeed to create listening sockets 
,11-05 01:45:35.491  5866  5866 D ObexServerSockets0: startAccept()
11-05 01:45:35.491  5866  5866 D ObexServerSockets0: prepareForNewConnect()
11-05 01:45:35.491  3763  3992 D BluetoothHeadset: onBluetoothStateChange: up=true
11-05 01:45:35.492  5652  5664 D BluetoothMap: onBluetoothStateChange: up=true
,11-05 01:45:35.493  5866  5866 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-05 01:45:35.493  5866  5866 D BluetoothSdpJni: SDP Create record success - handle: 0
11-05 01:45:35.494  5866  5902 D ObexServerSockets0: Accepting socket connection...
11-05 01:45:35.494  5866  5903 D ObexServerSockets0: Accepting socket connection...
11-05 01:45:35.494   927   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-05 01:45:35.494  3108  3108 D BluetoothMap: Proxy object connected
11-05 01:45:35.495  5652  5664 D BluetoothPan: onBluetoothStateChange on: true
11-05 01:45:35.495  3108  3108 D MapProfile: Bluetooth service connected
11-05 01:45:35.495  3108  3108 D BluetoothMap: getConnectedDevices()
,11-05 01:45:35.496  3108  3121 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-05 01:45:35.497  3108  3975 D BluetoothA2dp: onBluetoothStateChange: up=true
11-05 01:45:35.497  3108  3108 D BluetoothInputDevice: Proxy object connected
,11-05 01:45:35.497  3108  3108 D HidProfile: Bluetooth service connected
11-05 01:45:35.498  5652  5652 D BluetoothMap: Proxy object connected
11-05 01:45:35.498  5652  5652 D MapProfile: Bluetooth service connected
,11-05 01:45:35.498  5652  5652 D BluetoothMap: getConnectedDevices()
11-05 01:45:35.499   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-05 01:45:35.499  3108  3108 D BluetoothA2dp: Proxy object connected
11-05 01:45:35.501  5866  5866 D BluetoothMapService: onReceive
,11-05 01:45:35.501  5866  5866 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-05 01:45:35.501  5866  5866 D BluetoothMapService: STATE_ON
11-05 01:45:35.501  5652  5652 D BluetoothInputDevice: Proxy object connected
11-05 01:45:35.501  5652  5652 D HidProfile: Bluetooth service connected
,11-05 01:45:35.503  5652  5652 D BluetoothPan: BluetoothPAN Proxy object connected
,11-05 01:45:35.503  5652  5652 D PanProfile: Bluetooth service connected
11-05 01:45:35.503  5866  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-05 01:45:35.504  5866  5906 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-05 01:45:35.504  5866  5906 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-05 01:45:35.507  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-05 01:45:35.513  3561  3561 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-05 01:45:35.513  5652  5652 D DockEventReceiver: finishStartingService: stopping service
,11-05 01:45:35.520  5652  5652 D BluetoothPbap: Proxy object connected
,11-05 01:45:35.520  5652  5652 D PbapServerProfile: Bluetooth service connected
,11-05 01:45:35.525  5866  5866 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-05 01:45:35.525  5866  5866 D ObexServerSockets0: prepareForNewConnect()
,11-05 01:45:35.527  3108  3108 D BluetoothPbap: Proxy object connected
,11-05 01:45:35.527  3108  3108 D PbapServerProfile: Bluetooth service connected
11-05 01:45:35.529  5866  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-05 01:45:35.543  5866  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-05 01:45:35.544  5866  5914 I BtOppRfcommListener: Accept thread started.
,11-05 01:45:35.581   927   927 D BluetoothHeadset: Proxy object connected
,11-05 01:45:35.582  3108  3121 D BluetoothHeadset: Proxy object connected
,11-05 01:45:35.582  3108  3108 D HeadsetProfile: Bluetooth service connected
11-05 01:45:35.582  5652  5664 D BluetoothHeadset: Proxy object connected
11-05 01:45:35.582   927   927 D BluetoothHeadset: Proxy object connected
11-05 01:45:35.582   927   927 D BluetoothHeadset: Proxy object connected
11-05 01:45:35.582  5652  5652 D HeadsetProfile: Bluetooth service connected
11-05 01:45:35.583  3763  3809 D BluetoothHeadset: Proxy object connected
11-05 01:45:35.583  5652  5666 D BluetoothHeadset: Proxy object connected
11-05 01:45:35.585  5652  5652 D HeadsetProfile: Bluetooth service connected
11-05 01:45:35.585   927   945 D BluetoothHeadset: Proxy object connected
,11-05 01:45:35.593  3763  4117 D BluetoothHeadset: Proxy object connected
,11-05 01:45:35.594   927   945 D BluetoothHeadset: Proxy object connected
,11-05 01:45:35.598  3108  3120 D BluetoothHeadset: Proxy object connected
11-05 01:45:35.598  3108  3108 D HeadsetProfile: Bluetooth service connected
,11-05 01:45:37.848  3704  4412 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-05 01:45:39.452  5593  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-05 01:45:39.452  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:45:39.452  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:45:39.452  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-05 01:45:39.452  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-05 01:45:39.452  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-05 01:45:39.452  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-05 01:45:39.452  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-05 01:45:39.457  5593  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-05 01:45:39.458  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:45:39.458  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f6f5b2d removed from the list
11-05 01:45:39.459  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:45:39.460  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:45:39.461  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1db8df3 added. We now have 4 listener(s)
11-05 01:45:39.461  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-05 01:45:39.466   927  3138 D WifiService: setWifiEnabled: false pid=5593, uid=10077
,11-05 01:45:39.466   927  3138 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-05 01:45:44.475  5593  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-05 01:45:44.476   927  3119 D WifiService: setWifiEnabled: true pid=5593, uid=10077
11-05 01:45:44.477   927  3119 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-05 01:45:44.485   506   920 D SoftapController: Softap fwReload - Ok
,11-05 01:45:44.491   506   920 D CommandListener: Setting iface cfg
,11-05 01:45:44.492   506   920 D CommandListener: Trying to bring down wlan0
11-05 01:45:44.493   506   920 D CommandListener: Clearing all IP addresses on wlan0
,11-05 01:45:44.497   927  2952 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-05 01:45:44.886   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:45.168   927  2952 D wifi    : set interface wlan0 flags (UP)
,11-05 01:45:45.170   927  2952 I WifiHAL : Initializing wifi
11-05 01:45:45.170   927  2952 I WifiHAL : Creating socket
,11-05 01:45:45.176   927  2952 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-05 01:45:45.176   927  2952 D wifi    : Did set static halHandle = 0x7f7a257080
,11-05 01:45:45.176   927  2952 D wifi    : halHandle = 0x7f7a257080, mVM = 0x7f9688d140, mCls = 0x2015aa
11-05 01:45:45.177   927  2952 D wifi    : array field set
11-05 01:45:45.177   927  2952 I WifiNative-HAL: interface[0] = wlan0
11-05 01:45:45.177   927   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-05 01:45:45.179   927  5919 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547510120576
11-05 01:45:45.179   927  5919 D wifi    : waitForHalEvents called, vm = 0x7f9688d140, obj = 0x2015aa, env = 0x7f7bd7dc00
,11-05 01:45:45.251  5920  5920 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-05 01:45:45.282   927  2952 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-05 01:45:45.328  5920  5920 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-05 01:45:45.408  5920  5920 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-05 01:45:45.408  5920  5920 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-05 01:45:45.434   927  2952 D WifiConfigStore: Loading config and enabling all networks 
,11-05 01:45:45.458   927  2952 D WifiConfigStore: loaded 0 passpoint configs
,11-05 01:45:45.459   927  2952 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-05 01:45:45.460   927  2952 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-05 01:45:45.460   927  2952 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-05 01:45:45.461   927  2952 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-05 01:45:45.462   927  2952 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-05 01:45:45.463   927  2952 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-05 01:45:45.463   927  2952 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-05 01:45:45.463   927  2952 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-05 01:45:45.464   927  2952 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-05 01:45:45.464   927  2952 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-05 01:45:45.464   927  2952 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-05 01:45:45.464   927  2952 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-05 01:45:45.468   927  2952 D WifiNative-HAL: Setting external_sim to 1
,11-05 01:45:45.469  4487  4487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-05 01:45:45.469   927  2952 D wifi    : setting dfs flag to true, 0x7f7b9329a0
11-05 01:45:45.470   927  2952 D WifiStateMachine: Setting OUI to DA-A1-19
,11-05 01:45:45.470   927  2952 D wifi    : setting scan oui 0x7f7b9329a0
11-05 01:45:45.470   927  2952 D WifiHAL : Sending mac address OUI
,11-05 01:45:45.475   927  2952 E native  : do suspend true
,11-05 01:45:45.483   927  2952 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-05 01:45:45.484   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-05 01:45:45.484   927   927 D RttService: SCAN_AVAILABLE : 3
11-05 01:45:45.484   927  3061 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-05 01:45:45.485   506   920 D CommandListener: Setting iface cfg
,11-05 01:45:45.496   927  2944 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '153 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 153 Failed to set address (No such device)'
,11-05 01:45:45.496   927  2944 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-05 01:45:45.509   927   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164768 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
,11-05 01:45:45.510   927  2944 D WifiNative-HAL: p2pGetDeviceAddress
11-05 01:45:45.510   927  2944 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-05 01:45:45.889   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:46.890   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:47.891   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:48.633  5920  5920 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-05 01:45:48.664   927  2952 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-05 01:45:48.673   927  2952 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,11-05 01:45:48.674   927  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-05 01:45:48.691   927  2952 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-05 01:45:48.747   927  2952 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-05 01:45:48.892   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:45:49.066  5920  5920 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-05 01:45:49.104  5920  5920 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-05 01:45:49.105  5920  5920 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-05 01:45:49.118   927  2952 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-05 01:45:49.119   927  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-05 01:45:49.119   927  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-05 01:45:49.136   927  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-05 01:45:49.148   506   920 D CommandListener: Setting iface cfg
,11-05 01:45:49.154   927  2952 D WifiStateMachine: Start Dhcp Watchdog 3
,11-05 01:45:49.158   927  2952 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-05 01:45:49.162   927  5925 D DhcpClient: Receive thread started
,11-05 01:45:49.244   927  2952 E native  : do suspend false
,11-05 01:45:49.255   927  5924 D DhcpClient: Broadcasting DHCPDISCOVER
,11-05 01:45:49.275   927  5925 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-05 01:45:49.276   927  5924 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-05 01:45:49.278   927  5924 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-05 01:45:49.290   927  5925 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-05 01:45:49.290   927  5924 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-05 01:45:49.293   506   920 D CommandListener: Setting iface cfg
,11-05 01:45:49.298   927  2952 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-05 01:45:49.301   927  2952 E native  : do suspend true
,11-05 01:45:49.302   927  5924 D DhcpClient: Scheduling renewal in 86399s
,11-05 01:45:49.317   927  2952 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-05 01:45:49.319   927  2952 D WifiConfigStore: No blacklist allowed without epno enabled
11-05 01:45:49.320   927  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-05 01:45:49.321   927  2954 D ConnectivityService: Adding iface wlan0 to network 102
,11-05 01:45:49.330   927  2952 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-05 01:45:49.368   927  2954 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-05 01:45:49.368   927  2954 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-05 01:45:49.370   927  2954 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-05 01:45:49.373   927  2954 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-05 01:45:49.375   927  2954 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-05 01:45:49.383   927  2954 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-05 01:45:49.388   927  2954 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-05 01:45:49.388   927  2954 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-05 01:45:49.388   927  2954 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-05 01:45:49.388   927  2954 D ConnectivityService:    accepting network in place of null
11-05 01:45:49.388   927  2952 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-05 01:45:49.388   927  2952 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-05 01:45:49.389   927  2954 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-05 01:45:49.411   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-05 01:45:49.432   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-05 01:45:49.435   927  2954 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-05 01:45:49.435   927  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-05 01:45:49.435  3733  3849 W QCNEJ   : |CORE| network available: 102
11-05 01:45:49.436   927  2954 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-05 01:45:49.438   927   945 D Tethering: MasterInitialState.processMessage what=3
,11-05 01:45:49.442  3733  3849 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-05 01:45:49.443  3733  3849 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-05 01:45:49.444  3733  3849 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-05 01:45:49.449  3937  3937 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-05 01:45:49.452  3954  3954 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-05 01:45:49.456  3954  3954 D SystemUpdateService: onCreate
,11-05 01:45:49.459  3954  3954 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-05 01:45:49.471  3954  3954 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-05 01:45:49.475  3954  5934 I SystemUpdateService: active receiver: enabled
,11-05 01:45:49.477  3954  4250 I iu.UploadsManager: num queued entries: 0
,11-05 01:45:49.477  3954  4250 I iu.UploadsManager: num updated entries: 0
,11-05 01:45:49.478  3954  4250 I iu.SyncManager: NEXT; no task
,11-05 01:45:49.481  3954  3954 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-05 01:45:49.482  3954  3954 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-05 01:45:49.484  5719  5719 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-05 01:45:49.489  5719  5719 D SprintDMHelper: simOperator: 
,11-05 01:45:49.489  5593  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-05 01:45:49.489  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-05 01:45:49.489  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-05 01:45:49.489  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-05 01:45:49.489  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-05 01:45:49.489  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-05 01:45:49.489  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-05 01:45:49.489  5593  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-05 01:45:49.489  5719  5719 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-05 01:45:49.492  5593  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-05 01:45:49.493  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.493  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1db8df3 removed from the list
11-05 01:45:49.493  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:45:49.496  5593  5640 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-05 01:45:49.496  5593  5640 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-05 01:45:49.498  5593  5640 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bd65244 Bundle[{}]
11-05 01:45:49.499  3954  5934 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-05 01:45:49.499  5593  5640 I io.jxcore.node.LifeCycleMonitor: start: OK
11-05 01:45:49.499  5593  5640 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-05 01:45:49.499  5593  5640 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-05 01:45:49.500  5593  5640 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-05 01:45:49.501  5593  5640 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-05 01:45:49.501  5593  5640 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-05 01:45:49.507  5593  5640 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
11-05 01:45:49.508  5593  5640 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-05 01:45:49.508  5593  5640 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-05 01:45:49.509  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-05 01:45:49.510  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cadaab0 added. We now have 3 listener(s)
,11-05 01:45:49.511  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-05 01:45:49.511  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-05 01:45:49.512  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-05 01:45:49.512  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:45:49.512  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4137d29 added. We now have 4 listener(s)
11-05 01:45:49.512  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-05 01:45:49.513  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-05 01:45:49.514  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-05 01:45:49.514  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@324f8ae added. We now have 4 listener(s)
,11-05 01:45:49.516  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-05 01:45:49.516  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-05 01:45:49.516  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-05 01:45:49.516  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:45:49.516  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f17164f added. We now have 5 listener(s)
11-05 01:45:49.517  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-05 01:45:49.517  3954  5934 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-05 01:45:49.517  3954  5934 I SystemUpdateService: now status is 0 (complete)
,11-05 01:45:49.517  3954  5934 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-05 01:45:49.517  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:45:49.517  3954  5934 I SystemUpdateService: file has been verified
11-05 01:45:49.517  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:45:49.517  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:45:49.517  3954  5934 I SystemUpdateService: OTA package size = 21989297
11-05 01:45:49.517  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:45:49.517  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-05 01:45:49.517  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-05 01:45:49.517  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cadaab0 removed from the list
11-05 01:45:49.517  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.517  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4137d29 removed from the list
11-05 01:45:49.518  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:45:49.518  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.519  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.519  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.519  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.519  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:45:49.519  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:45:49.519  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.519  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4137d29 not in the list
11-05 01:45:49.519  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.521  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.521  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.521  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.521  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:45:49.521  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:45:49.521  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.521  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f17164f removed from the list
11-05 01:45:49.521  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-05 01:45:49.521  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:45:49.521  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-05 01:45:49.522  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@324f8ae removed from the list
,11-05 01:45:49.522  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-05 01:45:49.522  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bac1dc added. We now have 3 listener(s)
,11-05 01:45:49.524  3954  5934 I SystemUpdateService: showing system update notification
,11-05 01:45:49.524  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-05 01:45:49.524  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-05 01:45:49.524  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-05 01:45:49.524  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:45:49.524  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bdc2e5 added. We now have 4 listener(s)
11-05 01:45:49.524  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-05 01:45:49.525  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-05 01:45:49.526  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-05 01:45:49.526  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4bf1ba added. We now have 4 listener(s)
,11-05 01:45:49.528  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-05 01:45:49.528  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-05 01:45:49.528  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-05 01:45:49.528  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:45:49.528  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d8c86b added. We now have 5 listener(s)
11-05 01:45:49.528  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-05 01:45:49.528  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-05 01:45:49.528  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-05 01:45:49.529  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-05 01:45:49.529  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-05 01:45:49.529  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-05 01:45:49.530  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-05 01:45:49.532  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-05 01:45:49.532  5593  5640 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-05 01:45:49.532  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-05 01:45:49.534   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-05 01:45:49.535  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.535  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-05 01:45:49.535  3954  3954 D SystemUpdateService: onDestroy
,11-05 01:45:49.536  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-05 01:45:49.536  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-05 01:45:49.536  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-05 01:45:49.538  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.539  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-05 01:45:49.539  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-05 01:45:49.539  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-05 01:45:49.539  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-05 01:45:49.539  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.539  5593  5640 D BluetoothAdapter: STATE_ON
,11-05 01:45:49.541  5866  5876 D BtGatt.GattService: registerClient() - UUID=3996d1db-8427-4ab6-8052-d8cf4fe78fe7
,11-05 01:45:49.542  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=3996d1db-8427-4ab6-8052-d8cf4fe78fe7, clientIf=5
11-05 01:45:49.543  5593  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-05 01:45:49.544  5866  5905 D BtGatt.GattService: start scan with filters
,11-05 01:45:49.546  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-05 01:45:49.546  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.546  5866  5885 D BtGatt.ScanManager: handling starting scan
11-05 01:45:49.546  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-05 01:45:49.546  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.546  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-05 01:45:49.547  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-05 01:45:49.547  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.547  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-05 01:45:49.547  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-05 01:45:49.547  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-05 01:45:49.547  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.547  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-05 01:45:49.547  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-05 01:45:49.548  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.548  5866  5885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19bf4f1
,11-05 01:45:49.549  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.549  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-05 01:45:49.550  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.550  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.550  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.550  5593  5640 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-05 01:45:49.550  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-05 01:45:49.550  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-05 01:45:49.550  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-05 01:45:49.550  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-05 01:45:49.550  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:45:49.550  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-05 01:45:49.552  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-05 01:45:49.552  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.552  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.552  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.552  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-05 01:45:49.552  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-05 01:45:49.552  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-05 01:45:49.552  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-05 01:45:49.552  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.552  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.553  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.553  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-05 01:45:49.553  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.553  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:45:49.553  5866  5905 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-05 01:45:49.554  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-05 01:45:49.554  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:45:49.555  5866  5877 D BtGatt.GattService: stopScan() - queue size =1
11-05 01:45:49.555  5866  5882 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-05 01:45:49.555  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.555  5866  5876 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-05 01:45:49.555  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-05 01:45:49.555  5866  5885 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-05 01:45:49.555  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.555  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-05 01:45:49.555  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.556  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.556  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.556  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.556  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-05 01:45:49.556  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.556  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.556  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.556  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-05 01:45:49.556  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-05 01:45:49.556  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-05 01:45:49.557  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.558  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.558  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-05 01:45:49.558  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.558  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.558  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-05 01:45:49.558  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-05 01:45:49.558  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-05 01:45:49.558  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.558  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-05 01:45:49.558  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-05 01:45:49.559  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.559  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.559  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-05 01:45:49.559  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.560  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.560  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.560  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-05 01:45:49.560  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-05 01:45:49.560  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-05 01:45:49.560  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-05 01:45:49.560  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.561  5866  5885 D BtGatt.ScanManager: Starting BLE batch scan
11-05 01:45:49.561  5866  5885 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-05 01:45:49.561  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:45:49.561  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:45:49.561  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:45:49.561  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:45:49.561  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-05 01:45:49.562  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-05 01:45:49.562  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bac1dc removed from the list
11-05 01:45:49.562  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.562  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bdc2e5 removed from the list
11-05 01:45:49.562  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:45:49.562  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.563  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.563  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.563  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.563  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:45:49.563  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:45:49.563  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:45:49.563  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bdc2e5 not in the list
11-05 01:45:49.563  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.566  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.566  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.566  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.566  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-05 01:45:49.566  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:45:49.566  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.566  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d8c86b removed from the list
11-05 01:45:49.566  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:45:49.566  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:45:49.566  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-05 01:45:49.566  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4bf1ba removed from the list
11-05 01:45:49.567  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-05 01:45:49.567  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fb7074 added. We now have 3 listener(s)
11-05 01:45:49.568  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-05 01:45:49.568  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-05 01:45:49.568  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-05 01:45:49.568  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:45:49.568  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a699d added. We now have 4 listener(s)
11-05 01:45:49.568  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-05 01:45:49.569  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-05 01:45:49.569  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-05 01:45:49.569  5866  5882 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-05 01:45:49.569  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.569  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0afe12 added. We now have 4 listener(s)
11-05 01:45:49.571  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-05 01:45:49.571  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-05 01:45:49.571  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-05 01:45:49.571  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:45:49.571  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b03d9e3 added. We now have 5 listener(s)
11-05 01:45:49.571  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-05 01:45:49.571  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-05 01:45:49.572  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-05 01:45:49.572  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-05 01:45:49.572  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-05 01:45:49.572  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-05 01:45:49.572  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-05 01:45:49.573  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-05 01:45:49.575  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-05 01:45:49.575  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.576  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-05 01:45:49.576  5593  5640 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-05 01:45:49.576  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-05 01:45:49.576  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-05 01:45:49.578  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.579  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-05 01:45:49.579  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-05 01:45:49.579  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-05 01:45:49.579  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-05 01:45:49.581  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-05 01:45:49.581  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.581  5866  5882 E BtGatt.ContextMap: Context not found for ID 5
,11-05 01:45:49.582  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.582  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-05 01:45:49.582  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-05 01:45:49.582  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-05 01:45:49.583  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-05 01:45:49.583  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.583  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:45:49.585  5866  5876 D BtGatt.GattService: registerClient() - UUID=76ee526a-450e-4811-9eca-086f93300a40
11-05 01:45:49.585  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=76ee526a-450e-4811-9eca-086f93300a40, clientIf=5
11-05 01:45:49.585  5593  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-05 01:45:49.586  5866  5877 D BtGatt.GattService: start scan with filters
11-05 01:45:49.586  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-05 01:45:49.587  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:45:49.587  5866  5885 D BtGatt.ScanManager: stopping BLe Batch
,11-05 01:45:49.588  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-05 01:45:49.588  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.588  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-05 01:45:49.588  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.588  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-05 01:45:49.588  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-05 01:45:49.588  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.588  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-05 01:45:49.588  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-05 01:45:49.588  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.589  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.589  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-05 01:45:49.589  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-05 01:45:49.589  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.591  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-05 01:45:49.591  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:45:49.591  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-05 01:45:49.592  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.592  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-05 01:45:49.592  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.592  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.592  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.592  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-05 01:45:49.592  5593  5640 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-05 01:45:49.592  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-05 01:45:49.592  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:45:49.592  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:45:49.592  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:45:49.592  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-05 01:45:49.592  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-05 01:45:49.592  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:45:49.592  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-05 01:45:49.592  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fb7074 removed from the list
11-05 01:45:49.592  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.592  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a699d removed from the list
11-05 01:45:49.592  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:45:49.593  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-05 01:45:49.593  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-05 01:45:49.593  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-05 01:45:49.593  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,11-05 01:45:49.593  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-05 01:45:49.593  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-05 01:45:49.593  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.594  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.594  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.594  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.594  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.594  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.594  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-05 01:45:49.594  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:45:49.594  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.594  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:45:49.594  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.594  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-05 01:45:49.594  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a699d not in the list
,11-05 01:45:49.594  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-05 01:45:49.594  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-05 01:45:49.594  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-05 01:45:49.594  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.594  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.594  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.594  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-05 01:45:49.595   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168855, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
11-05 01:45:49.595  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-05 01:45:49.595  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.594  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.597  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:45:49.597  5866  5885 D BtGatt.ScanManager: handling starting scan
11-05 01:45:49.597  5866  5904 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-05 01:45:49.597  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-05 01:45:49.597  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:45:49.598  5866  5877 D BtGatt.GattService: stopScan() - queue size =1
11-05 01:45:49.598  5866  5876 D BtGatt.GattService: unregisterClient() - clientIf=5
11-05 01:45:49.598  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-05 01:45:49.599  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.599  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-05 01:45:49.599  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.599  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.599  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.599  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.599  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-05 01:45:49.599  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.599  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.599  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.599  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-05 01:45:49.599  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-05 01:45:49.600  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-05 01:45:49.600  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.601  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.601  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-05 01:45:49.601  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.601  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.601  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:45:49.601  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:45:49.601  5866  5882 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-05 01:45:49.601  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:45:49.601  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.601  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-05 01:45:49.601  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b03d9e3 removed from the list
11-05 01:45:49.601  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:45:49.601  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-05 01:45:49.601  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:45:49.601  5866  5885 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-05 01:45:49.601  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-05 01:45:49.601  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-05 01:45:49.601  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0afe12 removed from the list
11-05 01:45:49.601  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.601  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-05 01:45:49.602  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-05 01:45:49.602  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.602  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.602  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-05 01:45:49.602  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.602  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-05 01:45:49.602  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba05a0c added. We now have 3 listener(s)
,11-05 01:45:49.603  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.603  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.603  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.603  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.603  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-05 01:45:49.603  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-05 01:45:49.603  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-05 01:45:49.603  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-05 01:45:49.603  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-05 01:45:49.603  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffe2f55 added. We now have 4 listener(s)
11-05 01:45:49.603  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-05 01:45:49.605  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-05 01:45:49.606  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-05 01:45:49.606  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-05 01:45:49.606  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2643d6a added. We now have 4 listener(s)
11-05 01:45:49.606  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.606  5866  5885 D BtGatt.ScanManager: Starting BLE batch scan
11-05 01:45:49.606  5866  5885 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-05 01:45:49.607  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-05 01:45:49.607  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-05 01:45:49.607  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-05 01:45:49.607  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:45:49.607  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@960a25b added. We now have 5 listener(s)
11-05 01:45:49.607  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-05 01:45:49.607  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-05 01:45:49.607  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-05 01:45:49.607  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-05 01:45:49.607  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-05 01:45:49.608  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-05 01:45:49.609  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-05 01:45:49.611  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-05 01:45:49.612  5593  5640 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-05 01:45:49.612  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-05 01:45:49.616  5866  5882 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-05 01:45:49.616  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.616  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.616  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-05 01:45:49.617  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-05 01:45:49.617  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-05 01:45:49.617  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-05 01:45:49.620  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.620  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-05 01:45:49.620  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-05 01:45:49.620  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-05 01:45:49.620  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-05 01:45:49.620  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.620  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-05 01:45:49.621  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:45:49.621  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:45:49.622  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-05 01:45:49.624  5866  5877 D BtGatt.GattService: registerClient() - UUID=77910eec-ba75-4128-8191-b2ffe5cdc02f
,11-05 01:45:49.624  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=77910eec-ba75-4128-8191-b2ffe5cdc02f, clientIf=5
,11-05 01:45:49.625  5593  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-05 01:45:49.625  5866  5876 D BtGatt.GattService: start scan with filters
,11-05 01:45:49.626  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-05 01:45:49.626  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.627  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-05 01:45:49.627  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.627  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-05 01:45:49.627  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.628  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.628  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-05 01:45:49.628  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-05 01:45:49.628  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.628  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-05 01:45:49.628  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-05 01:45:49.628  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.628  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.628  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-05 01:45:49.629  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-05 01:45:49.629  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.632  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.632  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-05 01:45:49.632  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-05 01:45:49.632  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.632  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.632  5866  5885 D BtGatt.ScanManager: stopping BLe Batch
11-05 01:45:49.632  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.632  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-05 01:45:49.634  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-05 01:45:49.634  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:45:49.634  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:45:49.635  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:45:49.635  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-05 01:45:49.635  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-05 01:45:49.635  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:45:49.635  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-05 01:45:49.635  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba05a0c removed from the list
11-05 01:45:49.635  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.635  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffe2f55 removed from the list
,11-05 01:45:49.635  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:45:49.635  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-05 01:45:49.635  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-05 01:45:49.635  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-05 01:45:49.635  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-05 01:45:49.635  5593  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-05 01:45:49.635  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-05 01:45:49.635  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.635  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.635  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.635  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.635  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.636  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-05 01:45:49.636  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.636  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.636  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.636  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:45:49.637  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:45:49.637  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.637  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffe2f55 not in the list
11-05 01:45:49.637  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-05 01:45:49.637  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-05 01:45:49.637  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-05 01:45:49.637  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.637  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.637  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.637  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-05 01:45:49.637  5593  5640 D org.thaliproject.p2p.btconne,ctorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.637  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-05 01:45:49.637  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.637  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-05 01:45:49.638  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:45:49.638  5866  5904 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-05 01:45:49.638  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-05 01:45:49.639  5593  5640 D BluetoothAdapter: STATE_ON
11-05 01:45:49.639  5866  5876 D BtGatt.GattService: stopScan() - queue size =0
11-05 01:45:49.640  5866  5905 D BtGatt.GattService: unregisterClient() - clientIf=5
11-05 01:45:49.640  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-05 01:45:49.640  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.640  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-05 01:45:49.640  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.640  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.640  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.640  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.640  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-05 01:45:49.640  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.640  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.640  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.640  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-05 01:45:49.641  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-05 01:45:49.641  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-05 01:45:49.642  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.642  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-05 01:45:49.642  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.643  5866  5885 D BtGatt.ScanManager: handling starting scan
11-05 01:45:49.643  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.643  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-05 01:45:49.643  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.643  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.644  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:45:49.644  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:45:49.644  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.644  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-05 01:45:49.644  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@960a25b removed from the list
11-05 01:45:49.644  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:45:49.644  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-05 01:45:49.644  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-05 01:45:49.644  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-05 01:45:49.644  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-05 01:45:49.644  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.644  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2643d6a removed from the list
11-05 01:45:49.644  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-05 01:45:49.644  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-05 01:45:49.644  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.644  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.644  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-05 01:45:49.644  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.644  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-05 01:45:49.644  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b95dea4 added. We now have 3 listener(s)
11-05 01:45:49.645  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.645  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.645  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.645  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-05 01:45:49.645  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-05 01:45:49.645  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-05 01:45:49.646  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-05 01:45:49.646  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-05 01:45:49.646  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:45:49.646  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7df40d added. We now have 4 listener(s)
11-05 01:45:49.646  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-05 01:45:49.648  5866  5882 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-05 01:45:49.648  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-05 01:45:49.648  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:45:49.648  5866  5885 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-05 01:45:49.649  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-05 01:45:49.649  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80b0fc2 added. We now have 4 listener(s)
11-05 01:45:49.650  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-05 01:45:49.650  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-05 01:45:49.651  5593  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-05 01:45:49.651  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-05 01:45:49.651  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8f01d3 added. We now have 5 listener(s)
11-05 01:45:49.651  5593  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-05 01:45:49.651  5593  5640 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-05 01:45:49.651  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:45:49.651  5593  5640 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-05 01:45:49.651  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:45:49.652  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:45:49.652  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-05 01:45:49.652  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b95dea4 removed from the list
11-05 01:45:49.652  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-05 01:45:49.652  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7df40d removed from the list
11-05 01:45:49.652  5593  5640 D io.jxcore.node.ConnectivityMonitor: stop
11-05 01:45:49.652  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.653  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-05 01:45:49.653  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.653  5866  5885 D BtGatt.ScanManager: Starting BLE batch scan
11-05 01:45:49.653  5866  5885 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-05 01:45:49.653  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.653  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.654  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.654  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:45:49.654  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:45:49.654  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.654  5593  5640 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7df40d not in the list
11-05 01:45:49.654  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.657  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-05 01:45:49.657  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.657  5593  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-05 01:45:49.657  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-05 01:45:49.657  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-05 01:45:49.657  5593  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-05 01:45:49.657  5593  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8f01d3 removed from the list
11-05 01:45:49.657  5593  5640 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-05 01:45:49.657  5593  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-05 01:45:49.657  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-05 01:45:49.658  5593  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80b0fc2 removed from the list
,11-05 01:45:49.658  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-05 01:45:49.658  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-05 01:45:49.659  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-05 01:45:49.659  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-05 01:45:49.659  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-05 01:45:49.659  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-05 01:45:49.662  5866  5882 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-05 01:45:49.662  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:45:49.666  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-05 01:45:49.666  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:45:49.667  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-05 01:45:49.671  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-05 01:45:49.671  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.671  5866  5882 E BtGatt.ContextMap: Context not found for ID 5
,11-05 01:45:49.676  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-05 01:45:49.676  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.677  5866  5885 D BtGatt.ScanManager: stopping BLe Batch
,11-05 01:45:49.681  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-05 01:45:49.681  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-05 01:45:49.681  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-05 01:45:49.685  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-05 01:45:49.685  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-05 01:45:49.720   927  5922 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-05 01:45:49.769   927  5922 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 05 Nov 2016 00:45:49 GMT], X-Android-Received-Millis=[1478306749769], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478306749744]}
,11-05 01:45:49.770   927  2954 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-05 01:45:49.770   927  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-05 01:45:49.771   927  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-05 01:45:49.773   927  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-05 01:45:49.893   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-05 01:45:50.061  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-05 01:45:50.104  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-05 01:45:50.146  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-05 01:45:51.836  5593  5942 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-05 01:45:51.836  5593  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-05 01:45:52.657  5593  5942 W !!      : call onHalfStreamCopied
,11-05 01:45:52.657  5593  5942 I testCopyDataAndClose: closing input stream
,11-05 01:45:52.861  3561  5944 I VacuumService: Vacuum at: now=1478306752861 tag=VacuumService
,11-05 01:45:52.901  3561  5947 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-05 01:45:52.930  3561  5945 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-05 01:45:52.933  3561  5945 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-05 01:45:52.955  3561  5945 W Uploader:  no longer exists, so no auth token.
,11-05 01:45:52.960  3561  5947 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-05 01:45:53.252  3561  5949 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-05 01:45:53.397  3561  5945 W Uploader:  no longer exists, so no auth token.
,11-05 01:45:53.404  3561  5947 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-05 01:45:53.427  5593  5942 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-05 01:45:53.427  5593  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-05 01:45:53.427  5593  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-05 01:45:53.427  5593  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-05 01:45:53.427  5593  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-05 01:45:53.427  5593  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-05 01:45:53.427  5593  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-05 01:45:53.427  5593  5942 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-05 01:45:53.427  5593  5942 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-05 01:45:53.427  5593  5942 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-05 01:45:53.427  5593  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-05 01:45:53.476  3561  5949 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-05 01:45:53.559  3561  5947 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-05 01:45:53.646  3561  5949 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-05 01:45:57.395   927  2954 D ConnectivityService: handlePromptUnvalidated 102
,11-05 01:45:57.910  5593  5954 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-05 01:45:57.910  5593  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-05 01:45:59.909  5593  5640 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
11-05 01:45:59.909  5593  5640 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-05 01:45:59.910  5593  5640 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,11-05 01:45:59.921  5593  5954 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-05 01:45:59.921  5593  5954 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-05 01:45:59.921  5593  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,11-05 01:46:00.064  5593  5955 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-05 01:46:00.064  5593  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-05 01:46:01.672  5593  5955 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-05 01:46:01.672  5593  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-05 01:46:01.672  5593  5955 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-05 01:46:01.672  5593  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-05 01:46:01.672  5593  5955 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-05 01:46:01.672  5593  5955 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-05 01:46:01.672  5593  5955 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-05 01:46:01.672  5593  5955 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-05 01:46:01.672  5593  5955 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-05 01:46:01.672  5593  5955 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-05 01:46:01.672  5593  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-05 01:46:06.344  5593  5956 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-05 01:46:06.344  5593  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-05 01:46:06.345  5593  5956 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
11-05 01:46:06.345  5593  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-05 01:46:06.345  5593  5956 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-05 01:46:06.345  5593  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-05 01:46:06.345  5593  5956 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-05 01:46:06.345  5593  5956 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-05 01:46:06.345  5593  5956 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-05 01:46:06.345  5593  5956 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-05 01:46:06.345  5593  5956 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-05 01:46:06.346  5593  5956 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-05 01:46:06.346  5593  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-05 01:46:06.355  5593  5640 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-05 01:46:06.358  5593  5957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-05 01:46:06.358  5593  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-05 01:46:06.359  5593  5957 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
11-05 01:46:06.359  5593  5957 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-05 01:46:06.359  5593  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-05 01:46:06.359  5593  5957 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-05 01:46:06.359  5593  5957 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-05 01:46:06.359  5593  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-05 01:46:06.364  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-05 01:46:06.364  5593  5640 I jxcore-log: 
,11-05 01:46:06.364  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-05 01:46:06.364  5593  5640 I jxcore-log: 
,11-05 01:46:06.364  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-05 01:46:06.364  5593  5640 I jxcore-log: 
11-05 01:46:06.364  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-05 01:46:06.364  5593  5640 I jxcore-log: 
,11-05 01:46:06.365  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG UnitTest_app: 'Total duration:  92463'
11-05 01:46:06.365  5593  5640 I jxcore-log: 
,11-05 01:46:06.367  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-05 01:46:06.367  5593  5640 I jxcore-log: 
,11-05 01:46:06.373  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-05 01:46:06.373  5593  5640 I jxcore-log: 
11-05 01:46:06.374  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-05 01:46:06.374  5593  5640 I jxcore-log: 
,11-05 01:46:06.375  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-05 01:46:06.375  5593  5640 I jxcore-log: 
11-05 01:46:06.375  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-05 01:46:06.375  5593  5640 I jxcore-log: 
11-05 01:46:06.375  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-05 01:46:06.375  5593  5640 I jxcore-log: 
11-05 01:46:06.375  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-05 01:46:06.375  5593  5640 I jxcore-log: 
,11-05 01:46:06.376  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-05 01:46:06.376  5593  5640 I jxcore-log: 
,11-05 01:46:06.383  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-05 01:46:06.383  5593  5640 I jxcore-log: 
,11-05 01:46:06.395  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-05 01:46:06.395  5593  5640 I jxcore-log: 
,11-05 01:46:06.396  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-05 01:46:06.396  5593  5640 I jxcore-log: 
11-05 01:46:06.396  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-05 01:46:06.396  5593  5640 I jxcore-log: 
11-05 01:46:06.396  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-05 01:46:06.396  5593  5640 I jxcore-log: 
11-05 01:46:06.396  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-05 01:46:06.396  5593  5640 I jxcore-log: 
11-05 01:46:06.396  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-05 01:46:06.396  5593  5640 I jxcore-log: 
11-05 01:46:06.397  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-05 01:46:06.397  5593  5640 I jxcore-log: 
,11-05 01:46:06.397  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-05 01:46:06.397  5593  5640 I jxcore-log: 
11-05 01:46:06.397  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-05 01:46:06.397  5593  5640 I jxcore-log: 
11-05 01:46:06.397  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-05 01:46:06.397  5593  5640 I jxcore-log: 
,11-05 01:46:06.398  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-05 01:46:06.398  5593  5640 I jxcore-log: 
11-05 01:46:06.398  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-05 01:46:06.398  5593  5640 I jxcore-log: 
11-05 01:46:06.398  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-05 01:46:06.398  5593  5640 I jxcore-log: 
,11-05 01:46:06.399  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-05 01:46:06.399  5593  5640 I jxcore-log: 
11-05 01:46:06.399  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-05 01:46:06.399  5593  5640 I jxcore-log: 
,11-05 01:46:06.399  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-05 01:46:06.399  5593  5640 I jxcore-log: 
11-05 01:46:06.401  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-05 01:46:06.401  5593  5640 I jxcore-log: 
,11-05 01:46:06.401  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-05 01:46:06.401  5593  5640 I jxcore-log: 
,11-05 01:46:06.401  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-05 01:46:06.401  5593  5640 I jxcore-log: 
,11-05 01:46:06.401  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-05 01:46:06.401  5593  5640 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-05 01:46:06.402  5593  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-05 01:46:06.402  5593  5640 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-05 01:46:06.402  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-05 01:46:06.402  5593  5640 I jxcore-log: 
,11-05 01:46:06.402  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-05 01:46:06.402  5593  5640 I jxcore-log: 
11-05 01:46:06.402  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-05 01:46:06.402  5593  5640 I jxcore-log: 
11-05 01:46:06.402  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-05 01:46:06.402  5593  5640 I jxcore-log: 
11-05 01:46:06.403  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-05 01:46:06.403  5593  5640 I jxcore-log: 
11-05 01:46:06.403  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-05 01:46:06.403  5593  5640 I jxcore-log: 
,11-05 01:46:06.405  5593  5593 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-05 01:46:06.408  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-05 01:46:06.408  5593  5640 I jxcore-log: 
11-05 01:46:06.408  5593  5640 I jxcore-log: 2016-11-05 00:46:06 - WARN testUtils: 'myNameCallback not set!'
11-05 01:46:06.408  5593  5640 I jxcore-log: 
,11-05 01:46:08.477  5593  5640 I jxcore-log: 2016-11-05 00:46:08 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-05 01:46:08.477  5593  5640 I jxcore-log: 
,11-05 01:46:08.479  5593  5640 I jxcore-log: 2016-11-05 00:46:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-05 01:46:08.479  5593  5640 I jxcore-log: 
,11-05 01:46:08.827  5593  5640 I jxcore-log: 2016-11-05 00:46:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-05 01:46:08.827  5593  5640 I jxcore-log: 
,11-05 01:46:08.840  5593  5640 I jxcore-log: 2016-11-05 00:46:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-05 01:46:08.840  5593  5640 I jxcore-log: 
,11-05 01:46:09.894   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:46:09.974  5593  5640 I jxcore-log: 2016-11-05 00:46:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-05 01:46:09.974  5593  5640 I jxcore-log: 
,11-05 01:46:10.167  5593  5640 I jxcore-log: 2016-11-05 00:46:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-05 01:46:10.167  5593  5640 I jxcore-log: 
,11-05 01:46:10.173  5593  5640 I jxcore-log: 2016-11-05 00:46:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-05 01:46:10.173  5593  5640 I jxcore-log: 
,11-05 01:46:10.178  5593  5640 I jxcore-log: 2016-11-05 00:46:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-05 01:46:10.178  5593  5640 I jxcore-log: 
,11-05 01:46:10.665  5593  5640 I jxcore-log: 2016-11-05 00:46:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-05 01:46:10.665  5593  5640 I jxcore-log: 
,11-05 01:46:10.711  5593  5640 I jxcore-log: 2016-11-05 00:46:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-05 01:46:10.711  5593  5640 I jxcore-log: 
,11-05 01:46:10.724  5593  5640 I jxcore-log: 2016-11-05 00:46:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-05 01:46:10.724  5593  5640 I jxcore-log: 
,11-05 01:46:10.728  5593  5640 I jxcore-log: 2016-11-05 00:46:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-05 01:46:10.728  5593  5640 I jxcore-log: 
,11-05 01:46:10.895   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:46:11.001  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-05 01:46:11.001  5593  5640 I jxcore-log: 
,11-05 01:46:11.130  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-05 01:46:11.130  5593  5640 I jxcore-log: 
,11-05 01:46:11.507  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-05 01:46:11.507  5593  5640 I jxcore-log: 
,11-05 01:46:11.515  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-05 01:46:11.515  5593  5640 I jxcore-log: 
,11-05 01:46:11.519  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-05 01:46:11.519  5593  5640 I jxcore-log: 
,11-05 01:46:11.525  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-05 01:46:11.525  5593  5640 I jxcore-log: 
,11-05 01:46:11.530  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-05 01:46:11.530  5593  5640 I jxcore-log: 
,11-05 01:46:11.558  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-05 01:46:11.558  5593  5640 I jxcore-log: 
,11-05 01:46:11.594  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-05 01:46:11.594  5593  5640 I jxcore-log: 
,11-05 01:46:11.601  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-05 01:46:11.601  5593  5640 I jxcore-log: 
,11-05 01:46:11.608  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-05 01:46:11.608  5593  5640 I jxcore-log: 
,11-05 01:46:11.623  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-05 01:46:11.623  5593  5640 I jxcore-log: 
,11-05 01:46:11.628  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-05 01:46:11.628  5593  5640 I jxcore-log: 
,11-05 01:46:11.634  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-05 01:46:11.634  5593  5640 I jxcore-log: 
,11-05 01:46:11.639  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-05 01:46:11.639  5593  5640 I jxcore-log: 
,11-05 01:46:11.652  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-05 01:46:11.652  5593  5640 I jxcore-log: 
,11-05 01:46:11.669  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-05 01:46:11.669  5593  5640 I jxcore-log: 
,11-05 01:46:11.684  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-05 01:46:11.684  5593  5640 I jxcore-log: 
,11-05 01:46:11.695  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-05 01:46:11.695  5593  5640 I jxcore-log: 
,11-05 01:46:11.718  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-05 01:46:11.718  5593  5640 I jxcore-log: 
,11-05 01:46:11.729  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-05 01:46:11.729  5593  5640 I jxcore-log: 
,11-05 01:46:11.742  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-05 01:46:11.742  5593  5640 I jxcore-log: 
,11-05 01:46:11.753  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-05 01:46:11.753  5593  5640 I jxcore-log: 
,11-05 01:46:11.759  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-05 01:46:11.759  5593  5640 I jxcore-log: 
,11-05 01:46:11.781  5593  5640 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-05 01:46:11.782  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - INFO testUtils: 'BLE multiple advertisement supported'
11-05 01:46:11.782  5593  5640 I jxcore-log: 
,11-05 01:46:11.876  5593  5640 I jxcore-log: 2016-11-05 00:46:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:11.876  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:11.876  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:11.876  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:11.876  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:11.876  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:11.876  5593  5640 I jxcore-log: 
,11-05 01:46:11.896   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:46:12.195  5593  5640 I jxcore-log: 2016-11-05 00:46:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:12.195  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:12.195  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:12.195  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:12.195  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:12.195  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:12.195  5593  5640 I jxcore-log: 
,11-05 01:46:12.199  5593  5640 I jxcore-log: 2016-11-05 00:46:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:12.199  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:12.199  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:12.199  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:12.199  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:12.199  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:12.199  5593  5640 I jxcore-log: 
,11-05 01:46:12.834  5593  5640 I jxcore-log: 2016-11-05 00:46:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:12.834  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:12.834  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:12.834  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:12.834  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:12.834  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:12.834  5593  5640 I jxcore-log: 
11-05 01:46:12.836  5593  5640 I jxcore-log: 2016-11-05 00:46:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:12.836  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:12.836  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:12.836  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:12.836  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:12.836  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:12.836  5593  5640 I jxcore-log: 
,11-05 01:46:12.897   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:46:13.867  5593  5640 I jxcore-log: 2016-11-05 00:46:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:13.867  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:13.867  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:13.867  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:13.867  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:13.867  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:13.867  5593  5640 I jxcore-log: 
,11-05 01:46:13.870  5593  5640 I jxcore-log: 2016-11-05 00:46:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:13.870  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:13.870  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:13.870  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:13.870  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:13.870  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:13.870  5593  5640 I jxcore-log: 
,11-05 01:46:13.899   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-05 01:46:14.900   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-05 01:46:14.905  5593  5640 I jxcore-log: 2016-11-05 00:46:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:14.905  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:14.905  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:14.905  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:14.905  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:14.905  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:14.905  5593  5640 I jxcore-log: 
,11-05 01:46:14.911  5593  5640 I jxcore-log: 2016-11-05 00:46:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:14.911  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:14.911  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:14.911  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:14.911  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:14.911  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:14.911  5593  5640 I jxcore-log: 
,11-05 01:46:15.952  5593  5640 I jxcore-log: 2016-11-05 00:46:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:15.952  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:15.952  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:15.952  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:15.952  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:15.952  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:15.952  5593  5640 I jxcore-log: 
,11-05 01:46:15.957  5593  5640 I jxcore-log: 2016-11-05 00:46:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:15.957  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:15.957  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:15.957  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:15.957  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:15.957  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:15.957  5593  5640 I jxcore-log: 
,11-05 01:46:16.990  5593  5640 I jxcore-log: 2016-11-05 00:46:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:16.990  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:16.990  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:16.990  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:16.990  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:16.990  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:16.990  5593  5640 I jxcore-log: 
,11-05 01:46:16.993  5593  5640 I jxcore-log: 2016-11-05 00:46:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:16.993  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:16.993  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:16.993  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:16.993  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:16.993  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:16.993  5593  5640 I jxcore-log: 
,11-05 01:46:18.349  5593  5640 I jxcore-log: 2016-11-05 00:46:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:18.349  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:18.349  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:18.349  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:18.349  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:18.349  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:18.349  5593  5640 I jxcore-log: 
,11-05 01:46:18.355  5593  5640 I jxcore-log: 2016-11-05 00:46:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:18.355  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:18.355  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:18.355  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:18.355  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:18.355  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:18.355  5593  5640 I jxcore-log: 
,11-05 01:46:19.387  5593  5640 I jxcore-log: 2016-11-05 00:46:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:19.387  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:19.387  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:19.387  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:19.387  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:19.387  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:19.387  5593  5640 I jxcore-log: 
,11-05 01:46:19.391  5593  5640 I jxcore-log: 2016-11-05 00:46:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:19.391  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:19.391  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:19.391  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:19.391  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:19.391  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:19.391  5593  5640 I jxcore-log: 
,11-05 01:46:20.421  5593  5640 I jxcore-log: 2016-11-05 00:46:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:20.421  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:20.421  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:20.421  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:20.421  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:20.421  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:20.421  5593  5640 I jxcore-log: 
,11-05 01:46:20.424  5593  5640 I jxcore-log: 2016-11-05 00:46:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:20.424  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:20.424  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:20.424  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:20.424  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:20.424  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:20.424  5593  5640 I jxcore-log: 
,11-05 01:46:21.491  5593  5640 I jxcore-log: 2016-11-05 00:46:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:21.491  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:21.491  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:21.491  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:21.491  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:21.491  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:21.491  5593  5640 I jxcore-log: 
,11-05 01:46:21.495  5593  5640 I jxcore-log: 2016-11-05 00:46:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:21.495  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:21.495  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:21.495  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:21.495  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:21.495  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:21.495  5593  5640 I jxcore-log: 
,11-05 01:46:22.528  5593  5640 I jxcore-log: 2016-11-05 00:46:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:22.528  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:22.528  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:22.528  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:22.528  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:22.528  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:22.528  5593  5640 I jxcore-log: 
,11-05 01:46:22.534  5593  5640 I jxcore-log: 2016-11-05 00:46:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:22.534  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:22.534  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:22.534  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:22.534  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:22.534  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:22.534  5593  5640 I jxcore-log: 
,11-05 01:46:23.561  5593  5640 I jxcore-log: 2016-11-05 00:46:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:23.561  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:23.561  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:23.561  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:23.561  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:23.561  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:23.561  5593  5640 I jxcore-log: 
,11-05 01:46:23.565  5593  5640 I jxcore-log: 2016-11-05 00:46:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:23.565  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:23.565  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:23.565  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:23.565  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:23.565  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:23.565  5593  5640 I jxcore-log: 
,11-05 01:46:24.594  5593  5640 I jxcore-log: 2016-11-05 00:46:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:24.594  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:24.594  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:24.594  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:24.594  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:24.594  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:24.594  5593  5640 I jxcore-log: 
,11-05 01:46:24.598  5593  5640 I jxcore-log: 2016-11-05 00:46:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:24.598  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:24.598  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:24.598  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:24.598  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:24.598  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:24.598  5593  5640 I jxcore-log: 
,11-05 01:46:25.627  5593  5640 I jxcore-log: 2016-11-05 00:46:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:25.627  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:25.627  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:25.627  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:25.627  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:25.627  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:25.627  5593  5640 I jxcore-log: 
,11-05 01:46:25.630  5593  5640 I jxcore-log: 2016-11-05 00:46:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:25.630  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:25.630  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:25.630  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:25.630  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:25.630  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:25.630  5593  5640 I jxcore-log: 
,11-05 01:46:26.658  5593  5640 I jxcore-log: 2016-11-05 00:46:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-05 01:46:26.658  5593  5640 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-05 01:46:26.658  5593  5640 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-05 01:46:26.658  5593  5640 I jxcore-log: emit@events.js:82:1
11-05 01:46:26.658  5593  5640 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-05 01:46:26.658  5593  5640 I jxcore-log: emit@events.js:82:1'
11-05 01:46:26.658  5593  5640 I jxcore-log: 
,11-05 01:46:26.667  5593  5640 E jxcore  : Error!: error is undefined
11-05 01:46:26.667  5593  5640 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-05 01:46:26.671  5593  5640 I jxcore-log: 2016-11-05 00:46:26 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-05 01:46:26.671  5593  5640 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-05 01:46:26.671  5593  5640 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-05 01:46:26.671  5593  5640 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-05 01:46:26.671  5593  5640 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-05 01:46:26.671  5593  5640 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-05 01:46:26.671  5593  5640 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-05 01:46:26.671  5593  5640 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-05 01:46:26.672  5593  5640 I jxcore-log: 2016-11-05 00:46:26 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-05 01:46:26.672  5593  5640 I jxcore-log: 
11-05 01:46:26.674  5593  5640 E jxcore-log: TypeError: 
11-05 01:46:26.674  5593  5640 E jxcore-log: error is undefined
,11-05 01:46:26.674  5593  5640 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-05 01:46:26.674  5593  5640 E jxcore-log: 
,11-05 01:46:26.746   927  3395 D GraphicsStats: Buffer count: 2
11-05 01:46:26.746   927  3138 I WindowState: WIN DEATH: Window{381b333 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-05 01:46:26.746   927  2953 D WifiService: Client connection lost with reason: 4
,11-05 01:46:26.759   526   526 I Zygote  : Process 5593 exited cleanly (139)
11-05 01:46:26.762   927  3395 I ActivityManager: Process com.test.thalitest (pid 5593) has died
,11-05 01:46:26.774   927  3395 I ActivityManager: Start proc 5960:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-05 01:46:26.856  5960  5960 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-05 01:46:26.878  5960  5960 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-05 01:46:26.883  5960  5960 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6141-6143)
,11-05 01:46:26.883  5960  5960 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-05 01:46:26.894  5960  5960 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4e07b9}
,11-05 01:46:26.894  5960  5960 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-05 01:46:26.895  5960  5960 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-05 01:46:26.898  5960  5960 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-05 01:46:26.899  5960  5960 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-05 01:46:26.908  5960  5960 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-05 01:46:26.915  5960  5960 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-05 01:46:26.916  5960  5960 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-05 01:46:26.916  5960  5960 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-05 01:46:26.916  5960  5960 I Adreno  : Build Date                       : 12/06/15
11-05 01:46:26.916  5960  5960 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-05 01:46:26.916  5960  5960 I Adreno  : Local Branch                     : mybranch17112971
11-05 01:46:26.916  5960  5960 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-05 01:46:26.916  5960  5960 I Adreno  : Remote Branch                    : NONE
11-05 01:46:26.916  5960  5960 I Adreno  : Reconstruct Branch               : NOTHING
,11-05 01:46:26.947   927   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c9a21:true
,11-05 01:46:26.962   776   776 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[31190]" dev="sockfs" ino=31190 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-05 01:46:26.962   776   776 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[31190]" dev="sockfs" ino=31190 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-05 01:46:26.974  5960  5960 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-05 01:46:26.982  5960  5960 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-05 01:46:27.009   408   408 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[38100]" dev="sockfs" ino=38100 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-05 01:46:27.010  5960  5996 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-05 01:46:27.009   408   408 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[38100]" dev="sockfs" ino=38100 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-05 01:46:27.012  3395  3395 W Binder_5: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[16874]" dev="sockfs" ino=16874 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-05 01:46:27.012  3395  3395 W Binder_5: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[16874]" dev="sockfs" ino=16874 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-05 01:46:27.018  5960  5983 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-05 01:46:27.061  5960  5996 I OpenGLRenderer: Initialized EGL, version 1.4
,11-05 01:46:27.093   927  3790 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5593 uid 10077
,11-05 01:46:27.092  3790  3790 W Binder_8: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[37425]" dev="sockfs" ino=37425 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-05 01:46:27.092  3790  3790 W Binder_8: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[37425]" dev="sockfs" ino=37425 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-05 01:46:27.095   927   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +301ms (total +331ms)
,11-05 01:46:27.100  3621  3621 I Keyboard.Facilitator: onFinishInput()
,11-05 01:46:27.096   938   938 W Binder_1: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[37424]" dev="sockfs" ino=37424 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-05 01:46:27.096   938   938 W Binder_1: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[37424]" dev="sockfs" ino=37424 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-05 01:46:27.144  5960  5960 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5960
,11-05 01:46:27.179  5960  5960 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-05 01:46:27.190  5958  5958 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-05 01:46:27.205  5958  5958 D AndroidRuntime: CheckJNI is OFF
,11-05 01:46:27.231  5958  5958 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-05 01:46:27.255  5958  5958 I Radio-JNI: register_android_hardware_Radio DONE
,11-05 01:46:27.270  5958  5958 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-05 01:46:27.275   927   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-05 01:46:27.275   927   941 I ActivityManager: Killing 5960:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-05 01:46:27.308   927   938 D GraphicsStats: Buffer count: 2
,11-05 01:46:27.308   927  3396 I WindowState: WIN DEATH: Window{fb97b64 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-05 01:46:27.380   927   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-05 01:46:27.381   927   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-05 01:46:27.382   927   941 E ActivityManager: Failure starting process com.test.thalitest
11-05 01:46:27.382   927   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-05 01:46:27.382   927   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-05 01:46:27.382   927   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-05 01:46:27.382   927   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-05 01:46:27.382   927   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-05 01:46:27.382   927   941 I ActivityManager:   Force finishing activity ActivityRecord{6de5a78 u0 com.test.thalitest/.MainActivity t68}
,11-05 01:46:27.385   927   951 I art     : Starting a blocking GC Explicit
,11-05 01:46:27.394   927  3770 W ActivityManager: Spurious death for ProcessRecord{871da82 0:com.test.thalitest/u0a77}, curProc for 5960: null
,11-05 01:46:27.468   927   951 I art     : Explicit concurrent mark sweep GC freed 12782(849KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.615ms total 82.894ms
,11-05 01:46:27.486   927   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-05 01:46:27.489  5958  5958 I art     : System.exit called, status: 0
,11-05 01:46:27.489  5958  5958 I AndroidRuntime: VM exiting with result code 0.
,11-05 01:46:27.507   927   951 I ActivityManager: Start proc 6011:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-05 01:46:27.507   927   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-05 01:46:27.512   927   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-05 01:46:27.516  5866  5866 D BluetoothMapAppObserver: onReceive
11-05 01:46:27.517  5866  5866 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-05 01:46:27.523  3704  4087 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-05 01:46:27.525  3621  3621 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-05 01:46:27.528   927  2918 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-05 01:46:27.547  3621  6023 I Keyboard.Facilitator.DecoderInitializer: run()
,11-05 01:46:27.553  3381  6024 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-05 01:46:27.559  3621  6023 I Decoder : createOrResetDecoder
,11-05 01:46:27.576  3763  3763 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-05 01:46:27.605  3561  3561 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-05 01:46:27.605  3561  3561 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-05 01:46:27.610   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-05 01:46:27.612    29    29 W kworker/3:1: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-05 01:46:27.619  3790  3790 W Binder_8: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[26943]" dev="sockfs" ino=26943 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-05 01:46:27.619  3790  3790 W Binder_8: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[26943]" dev="sockfs" ino=26943 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-05 01:46:27.619    29    29 W kworker/3:1: type=1400 audit(0.0:136): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-05 01:46:27.619   927  3790 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5960 uid 10077
,11-05 01:46:27.623  3621  3621 I Keyboard.Facilitator: onFinishInput()
,11-05 01:46:27.628  3954  6030 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-05 01:46:27.629  3954  6030 D AccountUtils: Clearing selected account for com.test.thalitest
,11-05 01:46:27.631  3800  3884 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM shortcut_and_widget_previews WHERE packageName = ? AND profileId = ?] disk I/O error
,11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: Unable to delete items from DB
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: 	at com.android.launcher3.WidgetPreviewLoader.removePackage(WidgetPreviewLoader.java:198)
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: 	at com.android.launcher3.WidgetPreviewLoader.removePackage(WidgetPreviewLoader.java:189)
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3047)
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: 	at android.os.Handler.handleCallback(Handler.java:739)
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: 	at android.os.Looper.loop(Looper.java:148)
11-05 01:46:27.632  3800  3884 E WidgetPreviewLoader: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-05 01:46:27.639    29    29 W kworker/3:1: type=1400 audit(0.0:137): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-05 01:46:27.649  3381  3408 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjD7877A9B2) - 
,11-05 01:46:27.658  3561  3561 I ConfigService: onCreate
,11-05 01:46:27.662  3561  6032 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-05 01:46:27.662  3561  6032 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-05 01:46:27.662  3561  6032 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-05 01:46:27.663  3561  6032 W SQLiteOpenHelper: Opened config.db in read-only mode
11-05 01:46:27.674  3621  6023 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-05 01:46:27.700  3954  6030 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-05 01:46:27.712  3954  6030 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-05 01:46:27.712  3954  6030 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-05 01:46:27.713  3954  6030 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-05 01:46:27.713  3954  6030 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-05 01:46:27.720   385   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
