#### Test 9418709429da646_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-23 09:57:07.049   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:07.567  5467  5467 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-23 09:57:07.573  5467  5467 D AndroidRuntime: CheckJNI is OFF
11-23 09:57:07.601  5467  5467 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-23 09:57:07.639  5467  5467 I Radio-JNI: register_android_hardware_Radio DONE
11-23 09:57:07.654  5467  5467 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-23 09:57:07.659   928   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-23 09:57:07.678  5467  5467 D AndroidRuntime: Shutting down VM
11-23 09:57:07.688  3827  3840 W SearchService: Abort, client detached.
11-23 09:57:07.701  3827  3827 I HotwordDetector: Closing mic
11-23 09:57:07.702  3827  4030 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@645e86a
11-23 09:57:07.702  3827  4069 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-23 09:57:07.715   928  3642 I ActivityManager: Start proc 5476:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-23 09:57:07.768   510  4071 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-23 09:57:07.769   510  4071 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-23 09:57:07.775   510  4071 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-23 09:57:07.775   510  4071 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-23 09:57:07.776   510  2857 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-23 09:57:07.780  3827  4058 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-23 09:57:07.780  3827  4067 I MicroRecognitionRnrImpl: Detection finished
11-23 09:57:07.818  5476  5476 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-23 09:57:07.837  5476  5476 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-23 09:57:07.861  5476  5476 I LibraryLoader: Time to load native libraries: 21 ms (timestamps 9650-9671)
11-23 09:57:07.861  5476  5476 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-23 09:57:07.883  5476  5476 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c7664f}
11-23 09:57:07.883  5476  5476 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-23 09:57:07.884  5476  5476 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-23 09:57:07.887  5476  5476 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-23 09:57:07.887  5476  5476 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-23 09:57:07.921  5476  5476 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-23 09:57:07.929  5476  5476 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-23 09:57:07.929  5476  5476 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-23 09:57:07.929  5476  5476 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 09:57:07.929  5476  5476 I Adreno  : Build Date                       : 12/06/15
11-23 09:57:07.929  5476  5476 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 09:57:07.929  5476  5476 I Adreno  : Local Branch                     : mybranch17112971
11-23 09:57:07.929  5476  5476 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 09:57:07.929  5476  5476 I Adreno  : Remote Branch                    : NONE
11-23 09:57:07.929  5476  5476 I Adreno  : Reconstruct Branch               : NOTHING
,11-23 09:57:07.996   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@56319c6:true
,11-23 09:57:08.029   404   404 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[30297]" dev="sockfs" ino=30297 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 09:57:08.033   404   404 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[30297]" dev="sockfs" ino=30297 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 09:57:08.047  5476  5476 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-23 09:57:08.050   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:08.057  5476  5476 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-23 09:57:08.083   404   404 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32581]" dev="sockfs" ino=32581 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 09:57:08.083   404   404 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32581]" dev="sockfs" ino=32581 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 09:57:08.084  5476  5513 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 09:57:08.089  5476  5500 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-23 09:57:08.086  3642  3642 W Binder_9: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30302]" dev="sockfs" ino=30302 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 09:57:08.086  3642  3642 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30302]" dev="sockfs" ino=30302 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 09:57:08.115  5476  5513 I OpenGLRenderer: Initialized EGL, version 1.4
,11-23 09:57:08.183  3004  3004 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32939]" dev="sockfs" ino=32939 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 09:57:08.183  3004  3004 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32939]" dev="sockfs" ino=32939 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 09:57:08.183  3277  3277 W Binder_6: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32938]" dev="sockfs" ino=32938 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 09:57:08.185   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +492ms
11-23 09:57:08.186  3526  3526 I Keyboard.Facilitator: onFinishInput()
11-23 09:57:08.186  3277  3277 W Binder_6: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32938]" dev="sockfs" ino=32938 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 09:57:08.234  5476  5476 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5476
,11-23 09:57:08.339  5476  5476 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-23 09:57:08.517   928  3276 I ActivityManager: Killing 5142:com.android.settings/1000 (adj 15): empty #17
,11-23 09:57:08.533   928  3276 I ActivityManager: Killing 5101:org.codeaurora.ims/1001 (adj 15): empty #18
,11-23 09:57:08.550  5476  5515 D jxcore_app_log: JniHelper::setJavaVM(0xf55bc000), pthread_self() = -562300624
,11-23 09:57:08.556  5476  5515 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-23 09:57:08.556  5476  5515 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-23 09:57:08.556  5476  5515 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-23 09:57:08.556  5476  5515 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-23 09:57:08.556  5476  5515 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-23 09:57:08.558  5476  5515 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8709cd2 added. We now have 1 listener(s)
,11-23 09:57:08.562  5476  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-23 09:57:08.563  5476  5515 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 09:57:08.563  5476  5515 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:57:08.563  5476  5515 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-23 09:57:08.565  5476  5515 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4574059 added. We now have 1 listener(s)
11-23 09:57:08.565  5476  5515 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 09:57:08.570   928  2810 D WifiService: New client listening to asynchronous messages
,11-23 09:57:08.571  5476  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 09:57:08.571  5476  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-23 09:57:08.572  5476  5515 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-23 09:57:08.572  5476  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-23 09:57:08.572  5476  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-23 09:57:08.572  5476  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-23 09:57:08.572  5476  5515 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-23 09:57:08.573  5476  5515 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-23 09:57:08.785  5476  5476 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-23 09:57:09.052   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:09.140  5476  5485 I art     : Background sticky concurrent mark sweep GC freed 76594(7MB) AllocSpace objects, 16(1076KB) LOS objects, 24% free, 24MB/32MB, paused 1.920ms total 297.942ms
,11-23 09:57:10.053   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:10.397  5476  5485 I art     : Background partial concurrent mark sweep GC freed 51825(5MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 1.452ms total 329.667ms
,11-23 09:57:10.453   928  5232 D NetlinkSocketObserver: NeighborEvent{elapsedMs=192263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 09:57:11.054   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:11.084   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 09:57:11.619  5476  5524 W jxcore-log: Initializing JXcore engine
11-23 09:57:11.620  5476  5524 W jxcore-log: JXcore engine is ready
,11-23 09:57:11.646  5524  5524 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12612 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-23 09:57:11.646  5524  5524 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[11903]" dev="sockfs" ino=11903 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-23 09:57:11.646  5524  5524 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-23 09:57:11.646  5524  5524 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32922]" dev="sockfs" ino=32922 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-23 09:57:11.655  5476  5524 W jxcore-log: Starting JXcore engine
,11-23 09:57:11.705  5476  5524 W jxcore-log: Platform android
11-23 09:57:11.705  5476  5524 W jxcore-log: 
,11-23 09:57:11.706  5476  5524 W jxcore-log: Process ARCH arm
11-23 09:57:11.706  5476  5524 W jxcore-log: 
,11-23 09:57:11.895  5476  5524 I jxcore-log: JXcore Cordova bridge is ready!
11-23 09:57:11.895  5476  5524 I jxcore-log: 
,11-23 09:57:11.895  5476  5524 W jxcore-log: JXcore engine is started
,11-23 09:57:11.906  5476  5515 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-23 09:57:11.914  5476  5476 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-23 09:57:12.055   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 09:57:14.114   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 09:57:17.817  3827  5525 W CronetSyncConnectionRcs: Upload content type not set.
,11-23 09:57:19.647   928  2809 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 09:57:21.649  5476  5524 I jxcore-log: 2016-11-23 08:57:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-23 09:57:21.649  5476  5524 I jxcore-log: 
,11-23 09:57:21.650  5476  5524 I jxcore-log: 2016-11-23 08:57:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-23 09:57:21.650  5476  5524 I jxcore-log: 
,11-23 09:57:21.655  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-23 09:57:21.656  5476  5524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 09:57:21.656  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:57:21.656  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:57:21.656  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 09:57:21.656  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 09:57:21.656  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 09:57:21.656  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 09:57:21.656  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 09:57:21.656  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 09:57:21.664  5476  5524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 09:57:21.665  5476  5524 I jxcore-log: 2016-11-23 08:57:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-23 09:57:21.665  5476  5524 I jxcore-log: 
,11-23 09:57:21.667  5476  5524 I jxcore-log: 2016-11-23 08:57:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-23 09:57:21.667  5476  5524 I jxcore-log: 
,11-23 09:57:21.915  5476  5524 I jxcore-log: 2016-11-23 08:57:21 - DEBUG UnitTest_app: 'Running unit tests'
11-23 09:57:21.915  5476  5524 I jxcore-log: 
,11-23 09:57:21.916  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 09:57:21.916  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9740105 added. We now have 2 listener(s)
11-23 09:57:21.917  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 09:57:21.917  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:57:21.917  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 09:57:21.917  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:57:21.917  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d92255a added. We now have 2 listener(s)
11-23 09:57:21.917  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:57:21.918  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 09:57:21.919  5476  5524 D executeNativeTests: Running unit tests
,11-23 09:57:21.959  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 09:57:21.959  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b added. We now have 3 listener(s)
,11-23 09:57:21.960  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 09:57:21.960  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:57:21.960  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 09:57:21.960  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 09:57:21.960  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 added. We now have 3 listener(s)
,11-23 09:57:21.960  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:57:21.961  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 09:57:21.963  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 09:57:21.963  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-23 09:57:21.963  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 09:57:21.963  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 09:57:21.964  5476  5524 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-23 09:57:21.964  5476  5524 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-23 09:57:21.964  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 09:57:21.964  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 09:57:21.964  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 09:57:21.964  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-23 09:57:21.965  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:21.965  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:21.965  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:21.965  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 09:57:21.965  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:21.966  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 09:57:21.966  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b removed from the list
11-23 09:57:21.966  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:21.966  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 removed from the list
11-23 09:57:21.966  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:21.966  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.966  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.967  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.967  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.967  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.967  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:21.967  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:21.967  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:21.967  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:21.968  5476  5524 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-23 09:57:21.969  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:21.969  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:21.969  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:21.969  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:21.969  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:21.969  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:21.969  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:21.969  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:21.969  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:21.969  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.969  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.970  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:21.970  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.970  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.970  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:21.970  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:21.970  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:21.970  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:21.973  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 09:57:21.973  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 09:57:21.973  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 09:57:21.973  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 09:57:21.973  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 09:57:21.973  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 09:57:21.973  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 09:57:21.973  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 09:57:21.973  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 09:57:21.973  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 09:57:21.974  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 09:57:21.974  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:21.974  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:21.974  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:21.974  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 09:57:21.974  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:21.974  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:21.975  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:21.975  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:21.975  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:21.975  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.975  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:21.975  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.976  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.976  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.976  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:21.976  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:21.976  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:21.976  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:21.976  5476  5524 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 09:57:21.978  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 09:57:21.978  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 09:57:21.982  5476  5524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 09:57:21.982  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:57:21.982  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:57:21.982  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 09:57:21.982  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 09:57:21.982  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 09:57:21.982  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 09:57:21.982  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 09:57:21.982  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 09:57:21.984  5476  5524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 09:57:21.984  5476  5524 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 09:57:21.984  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 09:57:21.984  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 09:57:21.985  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-23 09:57:21.985  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 09:57:21.985  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 09:57:21.987  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 09:57:21.987  5476  5524 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 09:57:21.987  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 09:57:21.990  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 09:57:21.992  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 09:57:21.992  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.992  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 09:57:21.993  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 09:57:21.993  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 09:57:21.993  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 09:57:21.994  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-23 09:57:21.995  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-23 09:57:21.995  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.995  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 09:57:21.995  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 09:57:21.995  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 09:57:21.996  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 09:57:21.996  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:21.996  5476  5524 D BluetoothAdapter: STATE_ON
,11-23 09:57:21.998  4512  4527 D BtGatt.GattService: registerClient() - UUID=7337d0aa-bb52-495c-aff6-8d6d184ee960
,11-23 09:57:21.999  4512  4587 D BtGatt.GattService: onClientRegistered() - UUID=7337d0aa-bb52-495c-aff6-8d6d184ee960, clientIf=5
,11-23 09:57:21.999  5476  5486 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 09:57:22.000  4512  4525 D BtGatt.GattService: start scan with filters
,11-23 09:57:22.004  4512  4590 D BtGatt.ScanManager: handling starting scan
,11-23 09:57:22.004  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 09:57:22.004  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:22.004  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 09:57:22.004  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:22.005  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 09:57:22.005  5476  5476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 09:57:22.005  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 09:57:22.005  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 09:57:22.005  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 09:57:22.005  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-23 09:57:22.005  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 09:57:22.005  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 09:57:22.005  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:22.005  4512  4590 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
11-23 09:57:22.006  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 09:57:22.006  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 09:57:22.006  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:22.007  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 09:57:22.007  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:22.007  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:22.007  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 09:57:22.007  5476  5524 I io.jxcore.node.ConnectionHelper: start: OK
,11-23 09:57:22.012  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-23 09:57:22.012  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 09:57:22.012  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 09:57:22.012  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 09:57:22.013  4512  4587 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 09:57:22.013  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:22.013  4512  4590 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 09:57:22.019  4512  4587 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 09:57:22.019  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:22.019  4512  4590 D BtGatt.ScanManager: Starting BLE batch scan
11-23 09:57:22.019  4512  4590 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 09:57:22.028  4512  4587 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-23 09:57:22.028  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:57:22.033  4512  4587 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 09:57:22.033  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:57:22.513  5476  5476 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-23 09:57:22.514  5476  5476 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 09:57:22.514  5476  5476 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 09:57:22.840   928  5232 D NetlinkSocketObserver: NeighborEvent{elapsedMs=204650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 09:57:23.190   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 09:57:26.220   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 09:57:27.012  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 09:57:27.012  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:27.012  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 09:57:27.012  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:57:27.012  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-23 09:57:27.012  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 09:57:27.012  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 09:57:27.012  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 09:57:27.013  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:27.013  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-23 09:57:27.013  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 09:57:27.014  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:27.014  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:27.014  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:27.014  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 09:57:27.014  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:27.015  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:57:27.015  4512  4724 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 09:57:27.016  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 09:57:27.017  4512  4590 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 09:57:27.017  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:57:27.018  4512  4525 D BtGatt.GattService: stopScan() - queue size =1
11-23 09:57:27.019  4512  4724 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 09:57:27.019  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 09:57:27.019  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:27.019  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-23 09:57:27.020  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:27.020  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:27.020  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:27.020  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:27.020  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 09:57:27.020  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:27.021  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:27.021  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:27.021  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 09:57:27.021  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 09:57:27.022  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 09:57:27.022  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:27.024  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:27.024  4512  4512 D BtGatt.ScanManager: awakened up at time 208834
11-23 09:57:27.025  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:57:27.025  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:27.025  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:27.025  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:27.025  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:57:27.026  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:57:27.026  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:57:27.026  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 09:57:27.026  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:27.026  5476  5476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-23 09:57:27.026  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:27.026  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 09:57:27.026  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:27.027  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 09:57:27.027  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
,11-23 09:57:27.027  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:27.027  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 09:57:27.027  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 09:57:27.027  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 09:57:27.027  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 09:57:27.028  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-23 09:57:27.028  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:57:27.028  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 09:57:27.028  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 09:57:27.032  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 09:57:27.032  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 09:57:27.032  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 09:57:27.051  4512  4587 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-23 09:57:27.051  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:27.051  4512  4587 D BtGatt.GattService: current time is 208861938213
11-23 09:57:27.052  4512  4587 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -88, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -92, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -84, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -82, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -88, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 09:57:27.054  4512  4587 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-23 09:57:27.057  4512  4587 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-23 09:57:27.057  4512  4587 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 09:57:27.058  4512  4587 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 09:57:27.058  4512  4587 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-23 09:57:27.067  4512  4587 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 09:57:27.067  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:27.067  4512  4590 D BtGatt.ScanManager: stopping BLe Batch
,11-23 09:57:27.076  4512  4587 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 09:57:27.076  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:27.077  4512  4590 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 09:57:27.086  4512  4587 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 09:57:27.086  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:57:27.528  5476  5476 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 09:57:32.029  5476  5524 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 09:57:32.032  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 09:57:32.032  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 09:57:32.039  5476  5524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 09:57:32.039  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:57:32.039  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:57:32.039  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 09:57:32.039  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 09:57:32.039  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 09:57:32.039  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 09:57:32.039  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 09:57:32.039  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 09:57:32.041  5476  5524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 09:57:32.042  5476  5524 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-23 09:57:32.042  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 09:57:32.042  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 09:57:32.042  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 09:57:32.042  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 09:57:32.042  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 09:57:32.048  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 09:57:32.048  5476  5524 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 09:57:32.048  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 09:57:32.051  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:57:32.055  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:32.055  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 09:57:32.055  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:57:32.057  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 09:57:32.057  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 09:57:32.057  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 09:57:32.063  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:32.063  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 09:57:32.063  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 09:57:32.063  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 09:57:32.063  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 09:57:32.063  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:32.064  5476  5524 D BluetoothAdapter: STATE_ON
,11-23 09:57:32.068  4512  4724 D BtGatt.GattService: registerClient() - UUID=bcb4da47-3565-4ea8-b319-ab2e23995495
11-23 09:57:32.069  4512  4587 D BtGatt.GattService: onClientRegistered() - UUID=bcb4da47-3565-4ea8-b319-ab2e23995495, clientIf=5
,11-23 09:57:32.069  5476  5486 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 09:57:32.070  4512  4527 D BtGatt.GattService: start scan with filters
,11-23 09:57:32.074  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 09:57:32.074  4512  4590 D BtGatt.ScanManager: handling starting scan
11-23 09:57:32.074  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.074  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 09:57:32.074  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.074  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 09:57:32.075  5476  5476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 09:57:32.075  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.075  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 09:57:32.075  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 09:57:32.075  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.076  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.076  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.076  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.077  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 09:57:32.077  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:32.082  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.082  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 09:57:32.082  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:32.082  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.082  5476  5524 I io.jxcore.node.ConnectionHelper: start: OK
11-23 09:57:32.082  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.083  4512  4587 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-23 09:57:32.083  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:32.084  4512  4590 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 09:57:32.086  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:32.087  5476  5524 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 09:57:32.087  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:32.087  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 09:57:32.087  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:57:32.087  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 09:57:32.087  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:32.087  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 09:57:32.088  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.088  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-23 09:57:32.089  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.089  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 09:57:32.089  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 09:57:32.089  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.089  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 09:57:32.089  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-23 09:57:32.090  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:32.090  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.090  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.092  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 09:57:32.092  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:32.093  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:57:32.094  4512  4724 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 09:57:32.094  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 09:57:32.094  4512  4587 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 09:57:32.094  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:32.094  4512  4590 D BtGatt.ScanManager: Starting BLE batch scan
,11-23 09:57:32.094  4512  4590 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 09:57:32.095  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:57:32.096  4512  4525 D BtGatt.GattService: stopScan() - queue size =1
11-23 09:57:32.096  4512  4724 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 09:57:32.097  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 09:57:32.097  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.097  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 09:57:32.097  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.097  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.097  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.097  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.098  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 09:57:32.098  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.098  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.098  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:32.098  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 09:57:32.098  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 09:57:32.099  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 09:57:32.099  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.100  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.101  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:57:32.101  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.101  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.101  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:32.101  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-23 09:57:32.101  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:57:32.101  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:57:32.101  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 09:57:32.101  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:32.101  5476  5476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-23 09:57:32.101  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:32.101  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.101  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:32.102  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 09:57:32.102  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:32.102  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:32.102  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-23 09:57:32.102  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 09:57:32.102  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.102  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.102  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.102  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:57:32.102  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.102  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.104  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.104  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.104  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 09:57:32.105  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.105  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:32.110  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.110  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.110  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.110  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:32.110  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:32.110  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:32.110  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:32.111  4512  4587 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 09:57:32.111  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:32.112  5476  5524 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 09:57:32.114  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 09:57:32.114  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 09:57:32.119  4512  4587 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 09:57:32.119  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:57:32.121  4512  4590 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 09:57:32.121  5476  5524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 09:57:32.121  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:57:32.121  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:57:32.121  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 09:57:32.121  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 09:57:32.121  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 09:57:32.121  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 09:57:32.121  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 09:57:32.121  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 09:57:32.124  5476  5524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 09:57:32.124  5476  5524 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 09:57:32.124  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 09:57:32.124  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 09:57:32.124  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 09:57:32.124  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 09:57:32.124  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 09:57:32.127  4512  4587 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 09:57:32.127  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:32.128  4512  4587 E BtGatt.ContextMap: Context not found for ID 5
,11-23 09:57:32.128  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 09:57:32.128  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 09:57:32.128  5476  5524 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 09:57:32.128  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 09:57:32.132  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:32.133  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 09:57:32.133  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:57:32.134  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 09:57:32.134  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 09:57:32.134  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 09:57:32.136  4512  4587 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 09:57:32.136  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:32.136  4512  4590 D BtGatt.ScanManager: stopping BLe Batch
11-23 09:57:32.137  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.137  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 09:57:32.137  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 09:57:32.137  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 09:57:32.137  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 09:57:32.137  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.138  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:57:32.140  4512  4724 D BtGatt.GattService: registerClient() - UUID=88925631-4a80-414f-b11d-54ac4c8ce107
11-23 09:57:32.140  4512  4587 D BtGatt.GattService: onClientRegistered() - UUID=88925631-4a80-414f-b11d-54ac4c8ce107, clientIf=5
11-23 09:57:32.141  4512  4587 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 09:57:32.141  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:32.141  4512  4590 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 09:57:32.141  5476  5486 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 09:57:32.142  4512  4525 D BtGatt.GattService: start scan with filters
,11-23 09:57:32.147  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 09:57:32.147  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.147  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-23 09:57:32.147  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.147  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 09:57:32.148  5476  5476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 09:57:32.148  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.148  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 09:57:32.148  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-23 09:57:32.148  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.148  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.148  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.148  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.149  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 09:57:32.149  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.151  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.151  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 09:57:32.151  4512  4587 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-23 09:57:32.151  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:32.151  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:32.151  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:32.151  4512  4587 D BtGatt.GattService: current time is 213962044302
11-23 09:57:32.152  5476  5524 I io.jxcore.node.ConnectionHelper: start: OK
11-23 09:57:32.152  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.152  4512  4587 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 09:57:32.152  4512  4587 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-23 09:57:32.154  4512  4590 D BtGatt.ScanManager: handling starting scan
11-23 09:57:32.154  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.154  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-23 09:57:32.154  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 09:57:32.154  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 09:57:32.159  4512  4587 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 09:57:32.160  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:32.160  4512  4590 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 09:57:32.164  4512  4587 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 09:57:32.164  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:32.165  4512  4590 D BtGatt.ScanManager: Starting BLE batch scan
11-23 09:57:32.165  4512  4590 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 09:57:32.173  4512  4587 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 09:57:32.173  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:57:32.178  4512  4587 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 09:57:32.178  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:57:32.279   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 09:57:32.655  5476  5476 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-23 09:57:32.656  5476  5476 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 09:57:32.656  5476  5476 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 09:57:37.055   533   533 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 09:57:37.056   533   533 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 09:57:37.152  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 09:57:37.152  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-23 09:57:37.153  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-23 09:57:37.153  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:57:37.153  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 09:57:37.153  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:37.153  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 09:57:37.154  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 09:57:37.154  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.154  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 09:57:37.154  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 09:57:37.154  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:37.155  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.155  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.155  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-23 09:57:37.155  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:37.159  5476  5524 D BluetoothAdapter: STATE_ON
,11-23 09:57:37.160  4512  4724 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 09:57:37.161  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 09:57:37.162  4512  4590 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 09:57:37.162  5476  5524 D BluetoothAdapter: STATE_ON
,11-23 09:57:37.165  4512  4527 D BtGatt.GattService: stopScan() - queue size =1
,11-23 09:57:37.168  4512  4724 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-23 09:57:37.169  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 09:57:37.169  4512  4512 D BtGatt.ScanManager: awakened up at time 218979
,11-23 09:57:37.171  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.171  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 09:57:37.172  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.172  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.172  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.172  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.172  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 09:57:37.172  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:37.172  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.172  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.173  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 09:57:37.173  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 09:57:37.174  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 09:57:37.174  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.175  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.175  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:57:37.176  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.176  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:37.176  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:57:37.176  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:57:37.176  5476  5476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 09:57:37.176  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-23 09:57:37.177  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 09:57:37.177  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 09:57:37.177  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 09:57:37.177  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-23 09:57:37.177  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-23 09:57:37.177  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:57:37.177  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 09:57:37.178  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 09:57:37.179  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 09:57:37.179  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 09:57:37.180  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 09:57:37.191  4512  4587 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-23 09:57:37.191  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:57:37.191  4512  4587 D BtGatt.GattService: current time is 219001884544
11-23 09:57:37.192  4512  4587 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -93, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -84, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -93, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -82, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 09:57:37.192  4512  4587 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 09:57:37.192  4512  4587 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 09:57:37.192  4512  4587 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 09:57:37.193  4512  4587 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-23 09:57:37.193  4512  4587 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 09:57:37.193  4512  4587 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-23 09:57:37.198  4512  4587 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 09:57:37.198  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:57:37.198  4512  4590 D BtGatt.ScanManager: stopping BLe Batch
,11-23 09:57:37.203  4512  4587 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 09:57:37.203  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:57:37.203  4512  4590 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 09:57:37.208  4512  4587 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 09:57:37.208  4512  4587 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:57:37.678  5476  5476 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 09:57:37.678  5476  5476 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:37.678  5476  5476 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 09:57:39.650   928  2809 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 09:57:41.363   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 09:57:42.177  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
11-23 09:57:42.178  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 09:57:42.178  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:42.178  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 09:57:42.178  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:57:42.178  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 09:57:42.178  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 09:57:42.179  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:42.179  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.179  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
,11-23 09:57:42.179  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:42.179  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 09:57:42.182  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.183  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:42.187  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.188  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:42.188  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.189  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:42.189  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 09:57:42.189  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.189  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.191  5476  5524 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-23 09:57:42.194  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 09:57:42.194  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 09:57:42.194  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:42.195  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:42.195  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:42.195  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
,11-23 09:57:42.195  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.195  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.196  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 09:57:42.197  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.198  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.201  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.201  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:42.201  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.201  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:42.201  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:42.201  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 09:57:42.201  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.203  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 09:57:42.203  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:42.203  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:42.203  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:42.203  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:42.203  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:42.203  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
,11-23 09:57:42.203  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.204  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.204  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:42.204  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.204  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.205  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.205  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.205  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.205  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:42.206  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:42.206  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.206  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
,11-23 09:57:42.207  5476  5524 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-23 09:57:42.207  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:42.207  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:42.207  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:42.207  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:42.207  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:42.207  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:42.208  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.208  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.208  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:42.208  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.208  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.209  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.209  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.209  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.210  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:42.210  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:42.210  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.210  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.211  5476  5524 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-23 09:57:42.211  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:42.211  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:42.211  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:42.211  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:42.211  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 09:57:42.211  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:42.211  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.212  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.212  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:42.212  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.212  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.216  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.217  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.217  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.218  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:42.218  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:42.218  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.218  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.219  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 09:57:42.219  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 09:57:42.220  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 09:57:42.220  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 09:57:42.220  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 09:57:42.220  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 09:57:42.220  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 09:57:42.220  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 09:57:42.220  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 09:57:42.220  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:42.221  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:42.221  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:42.221  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:42.221  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:42.221  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:42.221  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.221  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.221  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:42.221  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.221  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.224  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.224  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.224  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.224  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:42.224  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:42.225  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.225  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.226  5476  5524 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 09:57:42.226  5476  5524 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 09:57:42.226  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 09:57:42.229  5476  5524 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 09:57:42.229  5476  5524 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-23 09:57:42.229  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 09:57:42.230  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 09:57:42.231  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 09:57:42.231  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 09:57:42.231  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 09:57:42.231  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 09:57:42.231  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 09:57:42.231  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 09:57:42.231  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 09:57:42.231  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 09:57:42.231  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 09:57:42.231  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 09:57:42.231  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 09:57:42.231  5476  5524 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-23 09:57:42.232  5476  5524 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 09:57:42.232  5476  5524 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-23 09:57:42.232  5476  5524 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 09:57:42.232  5476  5524 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 09:57:42.232  5476  5524 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-23 09:57:42.232  5476  5524 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 09:57:42.232  5476  5524 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 09:57:42.232  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-23 09:57:42.236  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-23 09:57:42.237  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-23 09:57:42.237  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-23 09:57:42.238  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-23 09:57:42.238  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-23 09:57:42.238  5476  5524 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-23 09:57:42.238  5476  5524 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 09:57:42.239  5476  5524 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-23 09:57:42.239  5476  5529 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-23 09:57:42.239  5476  5529 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-23 09:57:42.239  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:42.240  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:42.240  5476  5529 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-23 09:57:42.240  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:42.240  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:42.240  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:42.243  4525  4525 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33797]" dev="sockfs" ino=33797 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 09:57:42.243  4525  4525 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33797]" dev="sockfs" ino=33797 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 09:57:42.240  5476  5529 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-23 09:57:42.240  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-23 09:57:42.241  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:42.241  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.241  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.241  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:42.242  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.242  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.242  5476  5530 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-23 09:57:42.242  5476  5530 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-23 09:57:42.243  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.243  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.244  5476  5529 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-23 09:57:42.244  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.244  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:42.244  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:42.244  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.244  5476  5529 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 09:57:42.244  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.244  5476  5524 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-23 09:57:42.245  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:42.245  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:42.245  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:42.245  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:42.245  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:42.245  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:42.245  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.245  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.245  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:42.246  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.246  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.247  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.247  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.247  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.247  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:42.247  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:42.247  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.247  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.248  5476  5524 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-23 09:57:42.249  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:42.249  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:42.249  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:42.249  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:42.249  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:42.249  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:42.249  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.249  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.249  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:42.249  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.249  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.250  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.250  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.250  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.250  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:42.250  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:42.251  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.251  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.253  5476  5524 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-23 09:57:42.253  5476  5524 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-23 09:57:42.253  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 09:57:42.253  5476  5524 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-23 09:57:42.253  5476  5524 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 09:57:42.253  5476  5524 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-23 09:57:42.253  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 09:57:42.253  5476  5524 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-23 09:57:42.253  5476  5524 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 09:57:42.253  5476  5524 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 09:57:42.253  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 09:57:42.253  5476  5524 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-23 09:57:42.253  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:42.253  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:42.254  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:42.254  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:42.254  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:42.254  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:42.254  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.254  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.254  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:42.254  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.254  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.255  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.255  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.255  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:42.256  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:42.256  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:42.256  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.256  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.256  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:42.256  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:42.256  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:42.256  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:42.256  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:42.257  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 09:57:47.057   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:47.257  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:47.258  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
,11-23 09:57:47.258  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:47.258  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:47.258  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:47.258  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 09:57:47.259  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:47.259  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:47.259  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:47.259  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 09:57:47.259  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:47.260  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:47.260  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:47.260  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:47.261  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:47.261  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.265  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:47.266  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:47.266  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.267  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:47.267  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:47.267  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 09:57:47.268  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:47.271  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-23 09:57:47.271  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 09:57:47.272  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 09:57:47.278  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-23 09:57:47.280  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-23 09:57:47.280  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-23 09:57:47.280  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-23 09:57:47.281  5476  5531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-23 09:57:47.281  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-23 09:57:47.281  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 09:57:47.281  5476  5476 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-23 09:57:47.281  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:47.282  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-23 09:57:47.282  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-23 09:57:47.282  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-23 09:57:47.282  5476  5531 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 09:57:47.282  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 09:57:47.283  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 09:57:47.283  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-23 09:57:47.284  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:47.284  5476  5476 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-23 09:57:47.284  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:47.284  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 09:57:47.284  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.284  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 09:57:47.284  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-23 09:57:47.284  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.283  4527  4527 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32970]" dev="sockfs" ino=32970 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 09:57:47.286  5476  5531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-23 09:57:47.286  5476  5531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-23 09:57:47.286  5476  5531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-23 09:57:47.286  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.287  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:57:47.287  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:47.287  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.287  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:47.283  4527  4527 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32970]" dev="sockfs" ino=32970 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 09:57:47.287  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:57:47.287  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:47.287  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:57:47.287  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 09:57:47.288  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:47.288  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:57:47.288  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:47.288  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 09:57:47.288  5476  5476 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-23 09:57:47.288  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:47.288  5476  5476 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 09:57:47.288  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:47.288  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:47.288  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:47.288  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.288  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.291  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.291  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.291  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:47.291  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:47.291  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:47.292  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:47.292  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:47.295  5476  5524 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-23 09:57:47.295  5476  5524 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 09:57:47.296  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 09:57:47.296  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 09:57:47.298  5476  5524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-23 09:57:47.299  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 09:57:47.301  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:47.301  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:47.301  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:47.301  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:47.301  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:47.301  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:47.302  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
,11-23 09:57:47.302  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:47.302  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.302  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:47.304  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:47.304  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.304  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.304  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:47.304  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:47.304  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:47.304  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
,11-23 09:57:47.310  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 09:57:47.310  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:47.310  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:47.311  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:57:47.311  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:47.311  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:47.311  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 09:57:47.311  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:47.311  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 09:57:47.311  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:47.311  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.312  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.313  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.313  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:47.313  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:47.313  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:57:47.313  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:47.313  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
,11-23 09:57:47.314  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:57:47.314  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:57:47.314  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:57:47.314  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 09:57:47.314  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:57:47.315  5476  5524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff4657b not in the list
11-23 09:57:47.315  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:47.315  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
,11-23 09:57:47.315  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:47.315  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.315  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.316  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:57:47.316  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.317  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:57:47.317  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:57:47.317  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 09:57:47.317  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:57:47.317  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cdf98 not in the list
11-23 09:57:47.319  5476  5524 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-23 09:57:47.319  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-23 09:57:47.319  5476  5524 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-23 09:57:47.319  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 09:57:47.319  5476  5524 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-23 09:57:47.319  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-23 09:57:47.321  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 09:57:47.321  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-23 09:57:47.322  5476  5524 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-23 09:57:47.322  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-23 09:57:47.322  5476  5524 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-23 09:57:47.322  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 09:57:47.322  5476  5524 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-23 09:57:47.322  5476  5524 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-23 09:57:47.323  5476  5524 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-23 09:57:47.323  5476  5524 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-23 09:57:47.323  5476  5524 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-23 09:57:47.324  5476  5524 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-23 09:57:47.324  5476  5524 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-23 09:57:47.324  5476  5524 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-23 09:57:47.325  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:57:47.325  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f907b61 added. We now have 3 listener(s)
,11-23 09:57:47.325  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:57:47.327  5476  5524 D BluetoothAdapter: enable(): BT is already enabled..!
11-23 09:57:47.328   928  3276 D WifiService: setWifiEnabled: true pid=5476, uid=10077
11-23 09:57:47.328   928  3276 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 09:57:47.372  4512  4708 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-23 09:57:47.372  4512  4722 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-23 09:57:47.372  5476  5529 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
,11-23 09:57:47.373  5476  5529 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-23 09:57:47.373  5476  5529 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-23 09:57:47.405   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 09:57:47.788  5476  5476 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 09:57:48.057   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:49.058   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:50.059   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:50.424   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 09:57:51.060   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:51.307   928  5232 D NetlinkSocketObserver: NeighborEvent{elapsedMs=233117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 09:57:52.061   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 09:57:52.334  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 09:57:52.334  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4224686 added. We now have 4 listener(s)
,11-23 09:57:52.334  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 09:57:52.349  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 09:57:52.349  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4224686 removed from the list
11-23 09:57:52.349  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 09:57:52.351  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 09:57:52.351  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5b90b47 added. We now have 4 listener(s)
11-23 09:57:52.351  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 09:57:52.353  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 09:57:52.354  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5b90b47 removed from the list
,11-23 09:57:52.354  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:57:52.355  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 09:57:52.355  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1239f74 added. We now have 4 listener(s)
,11-23 09:57:52.355  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 09:57:52.360   928  3698 D WifiService: setWifiEnabled: false pid=5476, uid=10077
11-23 09:57:52.360   928  3698 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 09:57:52.364   928  2809 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-23 09:57:52.364   928  2809 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-23 09:57:52.365   928  2809 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 09:57:52.365   928  2809 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 09:57:52.370  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 09:57:52.370  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 09:57:52.373  4512  4583 D BluetoothAdapterState: Current state: ON, message: 23
11-23 09:57:52.373  4512  4583 D BluetoothAdapterProperties: Setting state to 13
11-23 09:57:52.373  4512  4583 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 09:57:52.374  4512  4583 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 09:57:52.375  4512  4583 I BluetoothAdapterState: Entering PendingCommandState
11-23 09:57:52.377  4512  4587 D BluetoothAdapterProperties: Scan Mode:20
,11-23 09:57:52.378  4512  4583 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-23 09:57:52.381  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 09:57:52.381  5476  5524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 09:57:52.381  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:57:52.381  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:57:52.381  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 09:57:52.381  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 09:57:52.381  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 09:57:52.381  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 09:57:52.381  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 09:57:52.381  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 09:57:52.384  4512  4512 D HeadsetService: Received stop request...Stopping profile...
11-23 09:57:52.384  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:57:52.385  5476  5524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 09:57:52.385  5476  5524 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-23 09:57:52.389   928  5233 D DhcpClient: Clearing IP address
11-23 09:57:52.389  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:57:52.389   505   926 D CommandListener: Clearing all IP addresses on wlan0
,11-23 09:57:52.394  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:57:52.398   505   926 D CommandListener: Setting iface cfg
,11-23 09:57:52.400  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:57:52.403  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 09:57:52.406   928   941 I ActivityManager: Start proc 5536:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-23 09:57:52.409  3437  5288 V NativeCrypto: Read error: ssl=0x7f7c485000: I/O error during system call, Connection timed out
,11-23 09:57:52.409  2989  3014 D BluetoothHeadset: Proxy object disconnected
,11-23 09:57:52.411   928   928 D BluetoothHeadset: Proxy object disconnected
11-23 09:57:52.411   928   928 D BluetoothHeadset: Proxy object disconnected
11-23 09:57:52.411   928   928 D BluetoothHeadset: Proxy object disconnected
,11-23 09:57:52.412  3618  3852 D BluetoothHeadset: Proxy object disconnected
11-23 09:57:52.412  3437  5288 V NativeCrypto: SSL shutdown failed: ssl=0x7f7c485000: I/O error during system call, Broken pipe
11-23 09:57:52.413   928  2811 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 09:57:52.413   928  2811 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-23 09:57:52.414  2989  2989 D HeadsetProfile: Bluetooth service disconnected
11-23 09:57:52.420   928   928 D RttService: SCAN_AVAILABLE : 1
,11-23 09:57:52.420  4512  4512 D BluetoothMapService: onReceive
11-23 09:57:52.420  4512  4512 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 09:57:52.420   928  2917 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 09:57:52.420  4512  4512 D BluetoothMapService: STATE_TURNING_OFF
11-23 09:57:52.421   928  2811 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-23 09:57:52.421  4512  4512 D A2dpService: Received stop request...Stopping profile...
11-23 09:57:52.422  4512  4727 D A2dpStateMachine: Exit Disconnected: -1
11-23 09:57:52.423  3577  3738 W QCNEJ   : |CORE| network lost: 100
11-23 09:57:52.424   928   928 D BluetoothA2dp: Proxy object disconnected
11-23 09:57:52.424  4512  4512 V BluetoothAdapterState: isTurningOff()=true
,11-23 09:57:52.424  4512  4512 V BluetoothAdapterState: isTurningOn()=false
11-23 09:57:52.424  3577  3738 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-23 09:57:52.424  4512  4512 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:57:52.424  4512  4512 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:57:52.425  2989  2989 D BluetoothA2dp: Proxy object disconnected
11-23 09:57:52.426   531   531 E Parcel  : Reading a NULL string not supported here.
11-23 09:57:52.427  4512  4512 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 09:57:52.427  4512  4512 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 09:57:52.428  4512  4708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 09:57:52.428  4512  4708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 09:57:52.428  4512  4708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 09:57:52.428  4512  4587 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 09:57:52.428  4512  4587 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 09:57:52.428  4512  4512 D HidService: Received stop request...Stopping profile...
11-23 09:57:52.428  4512  4512 D HidService: Stopping Bluetooth HidService
11-23 09:57:52.430  4512  4512 D HealthService: Received stop request...Stopping profile...
11-23 09:57:52.431  4512  4512 D PanService: Received stop request...Stopping profile...
11-23 09:57:52.432  4512  4512 D BluetoothMapService: MAP Service closeService in
11-23 09:57:52.433  4512  4512 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 09:57:52.433  4512  4512 D ObexServerSockets0: shutdown(block = true)
11-23 09:57:52.433  4512  4733 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-23 09:57:52.434  4512  4512 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 09:57:52.434  4512  4512 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 09:57:52.434  4512  4734 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 09:57:52.434  4512  4722 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 09:57:52.434  4512  4512 I BtOppRfcommListener: stopping Accept Thread
11-23 09:57:52.435  4512  5162 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 09:57:52.435  4512  5162 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-23 09:57:52.435   928  2809 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-23 09:57:52.436  4512  4512 D BluetoothMapService: Received stop request...Stopping profile...
11-23 09:57:52.436  4512  4512 D BluetoothMapService: stop()
11-23 09:57:52.437  4512  4512 D BluetoothMapAppObserver: deinitObservers()
11-23 09:57:52.437  4512  4512 D BluetoothMapAppObserver: removeReceiver()
11-23 09:57:52.438   928  5234 D DhcpClient: Receive thread stopped
,11-23 09:57:52.439  4512  4512 D SapService: Received stop request...Stopping profile...
11-23 09:57:52.439  4512  4512 V SapService: stop()
11-23 09:57:52.440  4512  4512 V BluetoothAdapterState: isTurningOff()=true
11-23 09:57:52.440  4512  4512 V BluetoothAdapterState: isTurningOn()=false
,11-23 09:57:52.440  4512  4512 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:57:52.440  4512  4512 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:57:52.441  4512  4587 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 09:57:52.441  4512  4708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 09:57:52.442  4512  4512 V BluetoothAdapterState: isTurningOff()=true
11-23 09:57:52.442  4512  4512 V BluetoothAdapterState: isTurningOn()=false
11-23 09:57:52.442  4512  4708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 09:57:52.442  4512  4512 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 09:57:52.442  4512  4512 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 09:57:52.442  4512  4708 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 09:57:52.442  4512  4708 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 09:57:52.442  4512  4708 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-23 09:57:52.442  4512  4708 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 09:57:52.442  4512  4512 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 09:57:52.442  4512  4512 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 09:57:52.442  4512  4587 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 09:57:52.442  4512  4512 V BluetoothAdapterState: isTurningOff()=true
11-23 09:57:52.442  4512  4512 V BluetoothAdapterState: isTurningOn()=false
,11-23 09:57:52.442  4512  4512 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:57:52.442  4512  4512 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:57:52.443  4512  4512 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 09:57:52.443  4512  4587 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 09:57:52.443  4512  4512 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 09:57:52.443  4512  4512 V BluetoothAdapterState: isTurningOff()=true
11-23 09:57:52.444  4512  4512 V BluetoothAdapterState: isTurningOn()=false
,11-23 09:57:52.444  4512  4512 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:57:52.444  4512  4512 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:57:52.444  4512  4512 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 09:57:52.444  4512  4512 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 09:57:52.449  4512  4512 D BluetoothMapService: MAP Service closeService in
11-23 09:57:52.449  4512  4512 V BluetoothAdapterState: isTurningOff()=true
,11-23 09:57:52.449  4512  4512 V BluetoothAdapterState: isTurningOn()=false
11-23 09:57:52.449  4512  4512 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:57:52.449  4512  4512 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:57:52.450  4512  4512 D BluetoothMapService: cleanup()
11-23 09:57:52.450  4512  4512 D BluetoothMapService: MAP Service closeService in
11-23 09:57:52.450  4512  4512 V BluetoothAdapterState: isTurningOff()=true
11-23 09:57:52.450  4512  4512 V BluetoothAdapterState: isTurningOn()=false
11-23 09:57:52.450  4512  4512 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:57:52.450  4512  4512 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 09:57:52.450  4512  4583 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 09:57:52.450  4512  4583 D BluetoothAdapterProperties: Setting state to 15
11-23 09:57:52.450  4512  4583 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 09:57:52.451  2989  2989 D BluetoothInputDevice: Proxy object disconnected
11-23 09:57:52.451  2989  2989 D HidProfile: Bluetooth service disconnected
,11-23 09:57:52.451  2989  2989 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 09:57:52.451  2989  2989 D PanProfile: Bluetooth service disconnected
11-23 09:57:52.451  2989  2989 D BluetoothMap: Proxy object disconnected
11-23 09:57:52.451  2989  2989 D MapProfile: Bluetooth service disconnected
,11-23 09:57:52.458   928  2809 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 09:57:52.461   505   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 09:57:52.463  4512  4583 I BluetoothAdapterState: Entering BleOnState
11-23 09:57:52.463   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-23 09:57:52.464  2989  3849 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 09:57:52.465  2989  3003 D BluetoothPan: onBluetoothStateChange on: false
,11-23 09:57:52.466  2989  3014 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-23 09:57:52.466  2989  3847 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 09:57:52.467   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 09:57:52.467   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 09:57:52.468  3618  3637 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 09:57:52.468   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 09:57:52.468  2989  5556 D BluetoothMap: onBluetoothStateChange: up=false
11-23 09:57:52.469  2989  3849 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 09:57:52.469  4512  4583 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 09:57:52.469  4512  4583 D BluetoothAdapterProperties: Setting state to 16
11-23 09:57:52.469  4512  4583 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 09:57:52.470  4512  4583 D BluetoothAdapterProperties: onBleDisable
11-23 09:57:52.470  4512  4583 I BluetoothAdapterState: Entering PendingCommandState
,11-23 09:57:52.470  4512  4584 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-23 09:57:52.471  4512  4587 D BluetoothAdapterProperties: Scan Mode:20
11-23 09:57:52.473  4512  4708 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 09:57:52.473  4512  4708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 09:57:52.473  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:57:52.473  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 09:57:52.473  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:57:52.473  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:57:52.473  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 09:57:52.473  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 09:57:52.473  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 09:57:52.473  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 09:57:52.473  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 09:57:52.473  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 09:57:52.474  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:57:52.474  5476  5476 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 09:57:52.476  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 09:57:52.478  5536  5536 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-23 09:57:52.489   505   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 09:57:52.489   505   926 D CommandListener: Clearing all IP addresses on wlan0
11-23 09:57:52.490   505   926 D TetherController: Setting IP forward enable = 0
11-23 09:57:52.491   928  2811 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-23 09:57:52.491   928  2811 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 09:57:52.494   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-23 09:57:52.495   928  2809 D DhcpClient: doQuit
,11-23 09:57:52.495   928  2809 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 09:57:52.496  5117  5117 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a77a82b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-23 09:57:52.496   928  5233 D DhcpClient: onQuitting
11-23 09:57:52.496  3301  3301 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 09:57:52.497  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 09:57:52.499  3827  3827 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-23 09:57:52.501  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:57:52.501  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 09:57:52.501  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:57:52.501  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:57:52.501  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 09:57:52.501  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 09:57:52.501  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 09:57:52.501  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 09:57:52.501  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 09:57:52.501  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 09:57:52.501  4906  4929 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 09:57:52.501  4906  4929 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 09:57:52.501  4906  4929 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 09:57:52.502  4906  4929 E SarControlService: no key has been found,reset the power
11-23 09:57:52.502  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:57:52.502  5476  5476 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 09:57:52.502  4906  4941 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 09:57:52.502  4906  4941 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 09:57:52.502  4906  4941 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 09:57:52.502  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 09:57:52.502  4931  4931 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 09:57:52.504  4906  4941 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-23 09:57:52.504  4906  4941 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 09:57:52.504  4906  4941 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 09:57:52.505  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 09:57:52.505  4931  4931 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 09:57:52.507  4931  4945 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1174d29 HexData = [00000000ea03000000000000ffffffff]
11-23 09:57:52.507  4931  4945 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 09:57:52.508  4931  4945 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-23 09:57:52.510  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 09:57:52.511  4906  4916 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 09:57:52.512  3301  3301 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 09:57:52.514  5536  5536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 09:57:52.516  4931  4945 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1174d29 HexData = [00000000eb03000000000000ffffffff]
,11-23 09:57:52.517  4931  4945 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 09:57:52.517  4931  4945 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-23 09:57:52.517  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 09:57:52.518  3301  3301 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-23 09:57:52.518  4906  4917 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 09:57:52.519   505   919 W SocketClient: write error (Broken pipe)
,11-23 09:57:52.519   505   919 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-23 09:57:52.519   505   919 W SocketListener: Error sending broadcast (Broken pipe)
11-23 09:57:52.522  3437  3437 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 09:57:52.522   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3aa5b12:true
,11-23 09:57:52.539  5536  5536 D LocalBluetoothProfileManager: Adding local MAP profile
,11-23 09:57:52.541  5536  5536 D BluetoothMap: Create BluetoothMap proxy object
,11-23 09:57:52.544  3301  3301 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 09:57:52.551  5536  5536 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-23 09:57:52.557  3301  3301 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 09:57:52.557   505   919 W SocketClient: write error (Broken pipe)
11-23 09:57:52.557   505   919 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-23 09:57:52.557   505   919 W SocketListener: Error sending broadcast (Broken pipe)
11-23 09:57:52.557  5536  5536 D DockEventReceiver: finishStartingService: stopping service
,11-23 09:57:52.560  5536  5536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 09:57:52.565  3437  3437 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 09:57:52.571  5536  5536 D DockEventReceiver: finishStartingService: stopping service
,11-23 09:57:52.574  3710  3710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 09:57:52.577  3710  3710 D SystemUpdateService: onCreate
,11-23 09:57:52.582  3710  3710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 09:57:52.585  3710  5570 I SystemUpdateService: active receiver: enabled
,11-23 09:57:52.590  3710  3710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 09:57:52.595  3710  5259 I iu.UploadsManager: num queued entries: 0
11-23 09:57:52.595  3710  5259 I iu.UploadsManager: num updated entries: 0
,11-23 09:57:52.601  3710  3710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 09:57:52.602  3710  5570 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-23 09:57:52.603  3710  3710 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 09:57:52.605  5262  5262 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-23 09:57:52.609  5262  5262 D SprintDMHelper: simOperator: 
11-23 09:57:52.609  5262  5262 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-23 09:57:52.611  3710  5570 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-23 09:57:52.612  3710  5570 I SystemUpdateService: now status is 0 (complete)
11-23 09:57:52.612  3710  5570 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 09:57:52.616  3710  5259 I iu.SyncManager: NEXT; no task
11-23 09:57:52.618  3710  5570 I SystemUpdateService: file has been verified
11-23 09:57:52.618  3710  5570 I SystemUpdateService: OTA package size = 21989297
11-23 09:57:52.622  4870  5572 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-23 09:57:52.632  3710  5570 I SystemUpdateService: showing system update notification
11-23 09:57:52.640   928   938 I ActivityManager: Start proc 5573:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-23 09:57:52.651   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 09:57:52.652  3710  3710 D SystemUpdateService: onDestroy
11-23 09:57:52.653   928  3004 I ActivityManager: Killing 5117:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-23 09:57:52.682   928  2809 D wifi    : In wifi stop Hal
,11-23 09:57:52.682   928  2809 D wifi    : halHandle = 0x7f7a26a680, mVM = 0x7f9684d140, mCls = 0x100a02
,11-23 09:57:52.683   928  3300 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 09:57:52.683   928  3300 D WifiHAL : Got a signal to exit!!!
11-23 09:57:52.683  4870  4870 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 09:57:52.683   928  3300 I WifiHAL : Exit wifi_event_loop
11-23 09:57:52.683   928  2809 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 09:57:52.684   928  2809 E WifiHAL : Event processing terminated
11-23 09:57:52.684   928  2809 D wifi    : In wifi cleaned up handler
11-23 09:57:52.684   928  2809 I WifiHAL : Internal cleanup completed
11-23 09:57:52.685  3929  4080 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 09:57:52.685  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 09:57:52.686  4512  4587 I bt_hci  : shut_down
,11-23 09:57:52.690  4512  4591 D bt_hwcfg: hw_epilog_process
,11-23 09:57:52.690  4512  4591 I bt_vendor: low_power_mode_cb
,11-23 09:57:52.693  4512  4591 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 09:57:52.693  4512  4591 I bt_vendor: epilog_cb
11-23 09:57:52.693  4512  4591 I bt_hci  : epilog_finished_callback
11-23 09:57:52.695  4512  4587 I bt_hci_h4: hal_close
11-23 09:57:52.696  4512  4587 I bt_userial_vendor: device fd = 54 close
,11-23 09:57:52.699  5573  5573 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-23 09:57:52.705   928  3597 I ActivityManager: Killing 5338:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-23 09:57:52.709   928  3300 D wifi    : set interface wlan0 flags (DOWN)
,11-23 09:57:52.709   505   919 W SocketClient: write error (Broken pipe)
11-23 09:57:52.709   505   919 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 down'
11-23 09:57:52.710   505   919 W SocketListener: Error sending broadcast (Broken pipe)
11-23 09:57:52.710   928  2809 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 09:57:52.807  4512  4584 D bt_stack_manager: event_shut_down_stack finished.
,11-23 09:57:52.808  4512  4583 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-23 09:57:52.810  4512  4583 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-23 09:57:52.810  4512  4512 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 09:57:52.811  4512  4512 D BtGatt.GattService: Received stop request...Stopping profile...
11-23 09:57:52.811  4512  4512 D BtGatt.GattService: stop()
11-23 09:57:52.811  4512  4512 D BtGatt.AdvertiseManager: advertise clients cleared
,11-23 09:57:52.814  4512  4512 V BluetoothAdapterState: isTurningOff()=false
11-23 09:57:52.814  4512  4512 V BluetoothAdapterState: isTurningOn()=false
11-23 09:57:52.814  4512  4512 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:57:52.814  4512  4512 V BluetoothAdapterState: isBleTurningOff()=true
11-23 09:57:52.814  4512  4583 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-23 09:57:52.814  4512  4583 D BluetoothAdapterProperties: Setting state to 10
11-23 09:57:52.814  4512  4583 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 09:57:52.815  4512  4583 I BluetoothAdapterState: Entering OffState
,11-23 09:57:52.816   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 09:57:52.823  4512  4512 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 09:57:52.823  4512  4512 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-23 09:57:52.823  4512  4584 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 09:57:52.825  4512  4512 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-23 09:57:52.827  4512  4512 I art     : System.exit called, status: 0
11-23 09:57:52.827  4512  4512 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 09:57:52.850   928  3004 I ActivityManager: Process com.android.bluetooth (pid 4512) has died
,11-23 09:57:52.912   928   945 D Tethering: InitialState.processMessage what=4
,11-23 09:57:52.917   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 09:57:53.574   505   926 E Netd    : netlink response contains error (No such file or directory)
,11-23 09:57:53.576   928  2811 E NetdConnector: NDC Command {114 network destroy 100} took too long (1084ms)
,11-23 09:57:53.577   928  2807 E NetdConnector: NDC Command {115 bandwidth setglobalalert 2097152} took too long (1078ms)
11-23 09:57:53.578   928  2806 E NetdConnector: NDC Command {116 bandwidth gettetherstats} took too long (659ms)
11-23 09:57:53.578   505   926 D TetherController: Setting IP forward enable = 0
,11-23 09:57:57.062   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:57.389   928  3276 D WifiService: setWifiEnabled: true pid=5476, uid=10077
,11-23 09:57:57.389   928  3276 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 09:57:57.401   505   926 D SoftapController: Softap fwReload - Ok
,11-23 09:57:57.407   505   926 D CommandListener: Setting iface cfg
,11-23 09:57:57.408   505   926 D CommandListener: Trying to bring down wlan0
,11-23 09:57:57.409   505   926 D CommandListener: Clearing all IP addresses on wlan0
,11-23 09:57:57.416   928  2809 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 09:57:58.010   928  2809 D wifi    : set interface wlan0 flags (UP)
,11-23 09:57:58.015   928  2809 I WifiHAL : Initializing wifi
11-23 09:57:58.015   928  2809 I WifiHAL : Creating socket
,11-23 09:57:58.019   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-23 09:57:58.021   928  2809 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-23 09:57:58.021   928  2809 D wifi    : Did set static halHandle = 0x7f7a26a680
11-23 09:57:58.022   928  2809 D wifi    : halHandle = 0x7f7a26a680, mVM = 0x7f9684d140, mCls = 0x198a
,11-23 09:57:58.022   928  2809 D wifi    : array field set
,11-23 09:57:58.022   928  2809 I WifiNative-HAL: interface[0] = wlan0
11-23 09:57:58.024   928  5593 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547510199936
11-23 09:57:58.024   928  5593 D wifi    : waitForHalEvents called, vm = 0x7f9684d140, obj = 0x198a, env = 0x7f7a8be580
,11-23 09:57:58.063   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:58.092  5594  5594 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 09:57:58.126   928  2809 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 09:57:58.132  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:57:58.161  5594  5594 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 09:57:58.216  5594  5594 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-23 09:57:58.216  5594  5594 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 09:57:58.240   928  2809 D WifiConfigStore: Loading config and enabling all networks 
,11-23 09:57:58.243  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:57:58.243  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 09:57:58.243  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:57:58.243  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:57:58.243  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 09:57:58.243  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 09:57:58.243  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 09:57:58.243  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 09:57:58.243  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 09:57:58.243  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 09:57:58.243  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 09:57:58.243  5476  5476 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 09:57:58.264   928  2809 D WifiConfigStore: loaded 0 passpoint configs
,11-23 09:57:58.265   928  2809 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-23 09:57:58.266   928  2809 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-23 09:57:58.266   928  2809 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-23 09:57:58.267   928  2809 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-23 09:57:58.267   928  2809 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-23 09:57:58.268   928  2809 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-23 09:57:58.268   928  2809 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-23 09:57:58.269   928  2809 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-23 09:57:58.269   928  2809 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-23 09:57:58.269   928  2809 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-23 09:57:58.269   928  2809 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-23 09:57:58.269   928  2809 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-23 09:57:58.272   928  2809 D WifiNative-HAL: Setting external_sim to 1
,11-23 09:57:58.272  4870  4870 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 09:57:58.272   928  2809 D wifi    : setting dfs flag to true, 0x7f7c3d0a40
11-23 09:57:58.273   928  2809 D WifiStateMachine: Setting OUI to DA-A1-19
,11-23 09:57:58.273   928  2809 D wifi    : setting scan oui 0x7f7c3d0a40
11-23 09:57:58.273   928  2809 D WifiHAL : Sending mac address OUI
,11-23 09:57:58.277   928  2809 E native  : do suspend false
,11-23 09:57:58.284   928   928 D RttService: SCAN_AVAILABLE : 3
,11-23 09:57:58.284   928  2809 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-23 09:57:58.284   505   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-23 09:57:58.284   928  2917 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 09:57:58.285   505   926 D CommandListener: Setting iface cfg
,11-23 09:57:58.289   928  2808 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
11-23 09:57:58.289   928  2808 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 09:57:58.298   928  2808 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 09:57:58.303   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=240113 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-23 09:57:58.303   928  2808 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-23 09:57:59.064   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:57:59.652   928  2809 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 13, 14 -> obsolete
,11-23 09:58:00.066   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:01.069   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:01.374  5594  5594 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 09:58:01.382  5594  5594 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 09:58:01.387  5594  5594 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 09:58:01.411   928  2809 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 09:58:01.412   928  2809 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 09:58:01.412   928  2809 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 09:58:01.422   928  2809 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 09:58:01.455   928  2809 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 09:58:01.461  5594  5594 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 09:58:01.879  5594  5594 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 09:58:01.908  5594  5594 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 09:58:01.909  5594  5594 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 09:58:01.922   928  2809 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-23 09:58:01.923   928  2809 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 09:58:01.923   928  2811 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 09:58:01.940   928  2809 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 09:58:01.954   505   926 D CommandListener: Setting iface cfg
,11-23 09:58:01.959   928  2809 D WifiStateMachine: Start Dhcp Watchdog 2
,11-23 09:58:01.965   928  5601 D DhcpClient: Receive thread started
,11-23 09:58:01.970   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 09:58:01.970   928  2809 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-23 09:58:01.970   928  2811 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-23 09:58:02.051   928  2809 E native  : do suspend false
,11-23 09:58:02.067   928  5600 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 09:58:02.070   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 09:58:02.080   928  5601 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172597, domain null
,11-23 09:58:02.081   928  5600 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172597 seconds
,11-23 09:58:02.083   928  5600 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-23 09:58:02.099   928  5601 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 09:58:02.100   928  5600 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 09:58:02.103   505   926 D CommandListener: Setting iface cfg
11-23 09:58:02.108   928  2809 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 09:58:02.113   928  5600 D DhcpClient: Scheduling renewal in 86399s
,11-23 09:58:02.128   928  2809 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 09:58:02.129   928  2809 D WifiConfigStore: No blacklist allowed without epno enabled
11-23 09:58:02.130   928  2811 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-23 09:58:02.132   928  2811 D ConnectivityService: Adding iface wlan0 to network 101
,11-23 09:58:02.142   928  2809 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 09:58:02.180   928  2811 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-23 09:58:02.180   928  2811 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-23 09:58:02.182   928  2811 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-23 09:58:02.183   928  2811 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-23 09:58:02.185   928  2811 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-23 09:58:02.193   928  2811 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 09:58:02.197   928  2811 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-23 09:58:02.197   928  2811 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-23 09:58:02.198   928  2811 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-23 09:58:02.198   928  2809 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 09:58:02.198   928  2811 D ConnectivityService:    accepting network in place of null
11-23 09:58:02.198   928  2809 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 09:58:02.198   928  2811 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 09:58:02.209   928  5599 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244019, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 09:58:02.222   505   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 09:58:02.245   505   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 09:58:02.250   928  2811 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-23 09:58:02.250   928  2811 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 09:58:02.250  3577  3738 W QCNEJ   : |CORE| network available: 101
11-23 09:58:02.252   928  2811 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-23 09:58:02.252   928   945 D Tethering: MasterInitialState.processMessage what=3
11-23 09:58:02.255  3577  3738 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-23 09:58:02.256  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:58:02.256  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 09:58:02.256  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:58:02.256  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:58:02.256  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 09:58:02.256  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 09:58:02.256  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 09:58:02.256  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 09:58:02.256  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 09:58:02.256  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 09:58:02.256  3577  3738 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 09:58:02.256  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:58:02.257  5476  5476 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 09:58:02.257  3577  3738 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 09:58:02.267  4906  4929 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 09:58:02.268  4906  4929 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 09:58:02.268  4906  4929 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 09:58:02.268  4906  4929 E SarControlService: no key has been found,reset the power
11-23 09:58:02.268  4906  4941 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 09:58:02.268  4906  4941 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 09:58:02.268  4906  4941 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 09:58:02.269  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 09:58:02.269  4931  4931 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-23 09:58:02.270  4906  4941 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 09:58:02.270  4906  4941 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 09:58:02.270  4906  4941 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 09:58:02.271  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 09:58:02.271  4931  4931 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 09:58:02.272  3827  3827 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-23 09:58:02.274  3710  3710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 09:58:02.275  4931  4945 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1174d29 HexData = [00000000ec03000000000000ffffffff]
11-23 09:58:02.275  4931  4945 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 09:58:02.275  4931  4945 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-23 09:58:02.277  4931  4945 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1174d29 HexData = [00000000ed03000000000000ffffffff]
11-23 09:58:02.277  4931  4945 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 09:58:02.278  4931  4945 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-23 09:58:02.278  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 09:58:02.278  4906  4916 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 09:58:02.279  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 09:58:02.279  4906  4917 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 09:58:02.279  3710  3710 D SystemUpdateService: onCreate
11-23 09:58:02.281   928  5598 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:804::200e
,11-23 09:58:02.283  3710  3710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 09:58:02.292  3710  3710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 09:58:02.298  3710  5259 I iu.UploadsManager: num queued entries: 0
,11-23 09:58:02.298  3710  5259 I iu.UploadsManager: num updated entries: 0
11-23 09:58:02.299  3710  5259 I iu.SyncManager: NEXT; no task
,11-23 09:58:02.300  3710  5613 I SystemUpdateService: active receiver: enabled
,11-23 09:58:02.303  3710  3710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 09:58:02.304  3710  3710 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 09:58:02.307  5262  5262 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 09:58:02.310  5262  5262 D SprintDMHelper: simOperator: 
11-23 09:58:02.310  5262  5262 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 09:58:02.331  3710  5613 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 09:58:02.332   928  5598 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 08:58:02 GMT], X-Android-Received-Millis=[1479891482331], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479891482307]}
11-23 09:58:02.332   928  2811 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 09:58:02.332   928  2811 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-23 09:58:02.332   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-23 09:58:02.333   928  2811 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 09:58:02.344  3710  5613 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-23 09:58:02.344  3710  5613 I SystemUpdateService: now status is 0 (complete)
11-23 09:58:02.344  3710  5613 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 09:58:02.345  3710  5613 I SystemUpdateService: file has been verified
11-23 09:58:02.345  3710  5613 I SystemUpdateService: OTA package size = 21989297
,11-23 09:58:02.350  3710  5613 I SystemUpdateService: showing system update notification
,11-23 09:58:02.359   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 09:58:02.361  3710  3710 D SystemUpdateService: onDestroy
,11-23 09:58:02.396   928  3642 D WifiService: setWifiEnabled: false pid=5476, uid=10077
,11-23 09:58:02.397   928  3642 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-23 09:58:02.398   928  2809 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-23 09:58:02.398   928  2809 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-23 09:58:02.398   928  2809 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 09:58:02.398   928  2809 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 09:58:02.406   928  5600 D DhcpClient: Clearing IP address
,11-23 09:58:02.406   505   926 D CommandListener: Clearing all IP addresses on wlan0
,11-23 09:58:02.408   505   926 D CommandListener: Setting iface cfg
11-23 09:58:02.409   928  5601 D DhcpClient: Receive thread stopped
,11-23 09:58:02.415  3437  5624 V NativeCrypto: Read error: ssl=0x7f7b842000: I/O error during system call, Connection timed out
11-23 09:58:02.415  3437  5624 V NativeCrypto: SSL shutdown failed: ssl=0x7f7b842000: I/O error during system call, Broken pipe
11-23 09:58:02.417  4870  5617 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
11-23 09:58:02.418   928  2811 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 09:58:02.418   928  2811 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-23 09:58:02.424   531   531 E Parcel  : Reading a NULL string not supported here.
11-23 09:58:02.424   928   928 D RttService: SCAN_AVAILABLE : 1
,11-23 09:58:02.425   928  2917 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 09:58:02.427   928  2811 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-23 09:58:02.427   928  2809 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionChecking,Service: 	at libcore.io.Posix.recvfromBytes(Native Method)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
11-23 09:58:02.429  4870  5617 W Babel_NetworkConnectionCheckingService: 	... 21 more
11-23 09:58:02.429  3577  3738 W QCNEJ   : |CORE| network lost: 101
11-23 09:58:02.430  4870  5617 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-23 09:58:02.430  3577  3738 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-23 09:58:02.430   928  2809 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 09:58:02.449   505   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 09:58:02.469   505   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 09:58:02.470   928  2811 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-23 09:58:02.470   505   926 D CommandListener: Clearing all IP addresses on wlan0
11-23 09:58:02.470   928  2811 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 09:58:02.471   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-23 09:58:02.474  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:58:02.474  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 09:58:02.474  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:58:02.474  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:58:02.474  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 09:58:02.474  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 09:58:02.474  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 09:58:02.474  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 09:58:02.474  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 09:58:02.474  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 09:58:02.474  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:58:02.474  5476  5476 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 09:58:02.478  3827  3827 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-23 09:58:02.481  3710  3710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 09:58:02.484  4906  4929 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 09:58:02.484  4906  4929 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 09:58:02.484  4906  4929 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 09:58:02.485  4906  4929 E SarControlService: no key has been found,reset the power
,11-23 09:58:02.485  4906  4941 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 09:58:02.485  4906  4941 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 09:58:02.485  4906  4941 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 09:58:02.485  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 09:58:02.486  4931  4931 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 09:58:02.487  4906  4941 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 09:58:02.487  4906  4941 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 09:58:02.487  4906  4941 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 09:58:02.487  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 09:58:02.488  4931  4931 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 09:58:02.490  3710  3710 D SystemUpdateService: onCreate
,11-23 09:58:02.493  4931  4945 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1174d29 HexData = [00000000ee03000000000000ffffffff]
11-23 09:58:02.493  4931  4945 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 09:58:02.493  4931  4945 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-23 09:58:02.493  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 09:58:02.494  4906  4917 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 09:58:02.494  4931  4945 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1174d29 HexData = [00000000ef03000000000000ffffffff]
11-23 09:58:02.494  4931  4945 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 09:58:02.494  4931  4945 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-23 09:58:02.495  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 09:58:02.495  4906  4916 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 09:58:02.496  3710  3710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 09:58:02.500  3710  5635 I SystemUpdateService: active receiver: enabled
,11-23 09:58:02.504  3710  3710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 09:58:02.512  3710  3710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 09:58:02.513  3710  3710 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 09:58:02.515  5262  5262 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 09:58:02.518  5262  5262 D SprintDMHelper: simOperator: 
11-23 09:58:02.518  5262  5262 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 09:58:02.520   505   926 E Netd    : netlink response contains error (No such file or directory)
,11-23 09:58:02.521   928  2811 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-23 09:58:02.522   928  2809 D DhcpClient: doQuit
,11-23 09:58:02.522   928  2809 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 09:58:02.522   928  5600 D DhcpClient: onQuitting
11-23 09:58:02.522  3710  5635 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-23 09:58:02.523  5594  5594 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 09:58:02.523  3710  5259 I iu.UploadsManager: num queued entries: 0
,11-23 09:58:02.526  3710  5259 I iu.UploadsManager: num updated entries: 0
11-23 09:58:02.527  3710  5259 I iu.SyncManager: NEXT; no task
11-23 09:58:02.527  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:58:02.527  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 09:58:02.527  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:58:02.527  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:58:02.527  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 09:58:02.527  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 09:58:02.527  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 09:58:02.527  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 09:58:02.527  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 09:58:02.527  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 09:58:02.527  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:58:02.527  5476  5476 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 09:58:02.528  3710  5635 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 09:58:02.529  3710  5635 I SystemUpdateService: now status is 0 (complete)
11-23 09:58:02.529  3710  5635 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 09:58:02.529  3710  5635 I SystemUpdateService: file has been verified
,11-23 09:58:02.529  3710  5635 I SystemUpdateService: OTA package size = 21989297
11-23 09:58:02.532  4870  5638 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-23 09:58:02.538  5594  5594 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 09:58:02.542  5594  5594 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-23 09:58:02.551  3710  5635 I SystemUpdateService: showing system update notification
,11-23 09:58:02.557   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 09:58:02.558  3710  3710 D SystemUpdateService: onDestroy
,11-23 09:58:02.565  5594  5594 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 09:58:02.575  5594  5594 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 09:58:02.677   928  2809 D wifi    : In wifi stop Hal
11-23 09:58:02.677   928  2809 D wifi    : halHandle = 0x7f7a26a680, mVM = 0x7f9684d140, mCls = 0x198a
,11-23 09:58:02.678   928  5593 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 09:58:02.678   928  5593 D WifiHAL : Got a signal to exit!!!
11-23 09:58:02.678   928  5593 I WifiHAL : Exit wifi_event_loop
,11-23 09:58:02.677  4870  4870 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 09:58:02.678   928  2809 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 09:58:02.678   928  2809 E WifiHAL : Event processing terminated
,11-23 09:58:02.678   928  2809 D wifi    : In wifi cleaned up handler
11-23 09:58:02.679   928  2809 I WifiHAL : Internal cleanup completed
11-23 09:58:02.679  3929  4080 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 09:58:02.682  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:58:02.711   928  5593 D wifi    : set interface wlan0 flags (DOWN)
,11-23 09:58:02.711   928  2809 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 09:58:02.919   928   945 D Tethering: InitialState.processMessage what=4
,11-23 09:58:02.926   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 09:58:03.252   928  2811 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-23 09:58:07.434   928   945 I ActivityManager: Start proc 5640:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 09:58:07.525  5640  5640 D AdapterServiceConfig: Adding HeadsetService
,11-23 09:58:07.525  5640  5640 D AdapterServiceConfig: Adding A2dpService
11-23 09:58:07.525  5640  5640 D AdapterServiceConfig: Adding HidService
11-23 09:58:07.525  5640  5640 D AdapterServiceConfig: Adding HealthService
11-23 09:58:07.525  5640  5640 D AdapterServiceConfig: Adding PanService
11-23 09:58:07.525  5640  5640 D AdapterServiceConfig: Adding GattService
11-23 09:58:07.526  5640  5640 D AdapterServiceConfig: Adding BluetoothMapService
11-23 09:58:07.526  5640  5640 D AdapterServiceConfig: Adding SapService
,11-23 09:58:07.535   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a2e2e7:true
,11-23 09:58:07.535  5640  5640 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 09:58:07.538  5640  5640 I bt_bluedroid: init
,11-23 09:58:07.538  5640  5652 I BluetoothAdapterState: Entering OffState
,11-23 09:58:07.541  5640  5653 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 09:58:07.541  5640  5653 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 09:58:07.541  5640  5653 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 09:58:07.541  5640  5653 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-23 09:58:07.541  5640  5640 I bt_bluedroid: get_profile_interface socket
,11-23 09:58:07.543  5640  5656 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 09:58:07.544  5640  5640 I bt_bluedroid: get_profile_interface sdp
11-23 09:58:07.545  5640  5656 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 09:58:07.548  5640  5651 I bt_bluedroid: config_hci_snoop_log
11-23 09:58:07.549   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 09:58:07.554  5640  5652 D BluetoothAdapterState: Current state: OFF, message: 0
11-23 09:58:07.554  5640  5652 D BluetoothAdapterProperties: Setting state to 14
11-23 09:58:07.554  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 09:58:07.555  5640  5652 D BluetoothBondStateMachine: make
,11-23 09:58:07.557  5640  5657 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 09:58:07.559  5640  5652 I BluetoothAdapterState: Entering PendingCommandState
,11-23 09:58:07.560  5640  5640 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 09:58:07.562  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
,11-23 09:58:07.563  5640  5640 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 09:58:07.563  5640  5640 D BtGatt.GattService: Received start request. Starting profile...
,11-23 09:58:07.564  5640  5640 D BtGatt.GattService: start()
11-23 09:58:07.564  5640  5640 I bt_bluedroid: get_profile_interface gatt
11-23 09:58:07.564  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
11-23 09:58:07.565  5640  5640 D BtGatt.AdvertiseManager: advertise manager created
,11-23 09:58:07.569  5640  5640 V BluetoothAdapterState: isTurningOff()=false
11-23 09:58:07.569  5640  5640 V BluetoothAdapterState: isTurningOn()=false
11-23 09:58:07.569  5640  5640 V BluetoothAdapterState: isBleTurningOn()=true
11-23 09:58:07.569  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:07.569  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 09:58:07.570  5640  5652 I bt_bluedroid: bt_bluedroid
,11-23 09:58:07.570  5640  5653 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-23 09:58:07.571  5640  5653 I bt_hci  : start_up
,11-23 09:58:07.575  5640  5653 I bt_vendor: alloc value 0xf4273871
11-23 09:58:07.576  5640  5653 I bt_vendor: init
,11-23 09:58:07.576  5640  5653 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 09:58:07.576  5640  5653 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 09:58:07.686  5640  5653 D bt_hci  : start_up starting async portion
,11-23 09:58:07.687  5640  5660 I bt_hci  : event_finish_startup
,11-23 09:58:07.687  5640  5660 I bt_hci_h4: hal_open
11-23 09:58:07.687  5640  5660 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 09:58:07.690  5640  5660 I bt_userial_vendor: device fd = 54 open
,11-23 09:58:07.686  5661  5661 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 09:58:07.704  5640  5660 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 09:58:07.707  5640  5660 D bt_hwcfg: Chipset BCM4358A3
,11-23 09:58:07.707  5640  5660 D bt_hwcfg: Target name = [BCM4358A3]
11-23 09:58:07.708  5640  5660 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 09:58:08.116  5640  5660 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 09:58:08.116  5640  5660 D bt_hwcfg: Settlement delay -- 100 ms
11-23 09:58:08.117  5640  5660 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 09:58:08.187  3526  3694 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-23 09:58:08.189  3526  3694 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-23 09:58:08.218  3437  3437 I ConfigService: onCreate
,11-23 09:58:08.250  5640  5660 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 09:58:08.250  5640  5660 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-23 09:58:08.251  5640  5660 I bt_hwcfg: vendor lib fwcfg completed
,11-23 09:58:08.251  5640  5660 I bt_vendor: firmware callback
11-23 09:58:08.251  5640  5660 I bt_hci  : firmware_config_callback
,11-23 09:58:08.255  5640  5664 I bt_btu  : btu_task pending for preload complete event
,11-23 09:58:08.255  5640  5664 I bt_btu_task: Bluetooth chip preload is complete
11-23 09:58:08.255  5640  5664 I bt_btu  : btu_task received preload complete event
,11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_HCI
11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_BNEP
11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_GAP
11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_SDP
,11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 09:58:08.259  5640  5664 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 09:58:08.331  5640  5664 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41f1549
,11-23 09:58:08.332  5640  5664 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41f1549 
,11-23 09:58:08.355  5640  5656 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 09:58:08.356  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 09:58:08.357  5640  5656 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 09:58:08.359  5640  5656 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 09:58:08.362  5640  5656 D BluetoothAdapterProperties: Scan Mode:20
11-23 09:58:08.363  5640  5656 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-23 09:58:08.364  5640  5656 D bt_hci  : do_postload posting postload work item
11-23 09:58:08.364  5640  5660 I bt_hci  : event_postload
11-23 09:58:08.364  5640  5660 I bt_vendor: sco_config_cb
11-23 09:58:08.364  5640  5660 I bt_hci  : sco_config_callback postload finished.
,11-23 09:58:08.368  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:58:08.371  5640  5656 D bt_bte_conf: Device ID record 1 : primary
,11-23 09:58:08.371  5640  5656 D bt_bte_conf:   vendorId            = 000f
11-23 09:58:08.371  5640  5656 D bt_bte_conf:   vendorIdSource      = 0001
11-23 09:58:08.371  5640  5656 D bt_bte_conf:   product             = 1200
11-23 09:58:08.372  5640  5656 D bt_bte_conf:   version             = 1436
11-23 09:58:08.372  5640  5660 I bt_vendor: low_power_mode_cb
,11-23 09:58:08.372  5640  5656 D bt_bte_conf:   clientExecutableURL = 
11-23 09:58:08.372  5640  5656 D bt_bte_conf:   serviceDescription  = 
11-23 09:58:08.372  5640  5656 D bt_bte_conf:   documentationURL    = 
11-23 09:58:08.372  5640  5656 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 09:58:08.372  5640  5653 D bt_stack_manager: event_start_up_stack finished
11-23 09:58:08.373  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 09:58:08.374  5640  5652 D BluetoothAdapterProperties: Setting state to 15
11-23 09:58:08.374  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 09:58:08.375  5640  5652 I BluetoothAdapterState: Entering BleOnState
,11-23 09:58:08.381  5640  5652 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 09:58:08.381  5640  5652 D BluetoothAdapterProperties: Setting state to 11
11-23 09:58:08.381  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 09:58:08.388  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
11-23 09:58:08.389  5640  5640 D HeadsetService: Received start request. Starting profile...
,11-23 09:58:08.391  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:58:08.397  5640  5640 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-23 09:58:08.397  5640  5640 D HeadsetStateMachine: make
11-23 09:58:08.405  5640  5652 I BluetoothAdapterState: Entering PendingCommandState
,11-23 09:58:08.406  5640  5640 D HeadsetStateMachine: max_hf_connections = 1
,11-23 09:58:08.407  5640  5640 I bt_bluedroid: get_profile_interface handsfree
11-23 09:58:08.407  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 09:58:08.407  5640  5656 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
11-23 09:58:08.410  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
11-23 09:58:08.410  5640  5640 D A2dpService: Received start request. Starting profile...
11-23 09:58:08.411  5640  5640 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-23 09:58:08.411  5640  5640 I bt_bluedroid: get_profile_interface avrcp
,11-23 09:58:08.418  5640  5640 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-23 09:58:08.418  5640  5640 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 09:58:08.418  5640  5640 D A2dpStateMachine: make
,11-23 09:58:08.419  5640  5640 I bt_bluedroid: get_profile_interface a2dp
,11-23 09:58:08.420  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-23 09:58:08.421  5640  5672 D A2dpStateMachine: Enter Disconnected: -2
,11-23 09:58:08.423  5640  5640 I BluetoothHidServiceJni: classInitNative: succeeds
11-23 09:58:08.424  3437  3437 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 09:58:08.425  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
11-23 09:58:08.426  5536  5536 D BluetoothInputDevice: Proxy object connected
11-23 09:58:08.426  5640  5640 D HidService: Received start request. Starting profile...
,11-23 09:58:08.426  5640  5640 I bt_bluedroid: get_profile_interface hidhost
,11-23 09:58:08.426  5640  5656 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41d256d
11-23 09:58:08.426  5640  5640 D HidService: setHidService(): set to: null
11-23 09:58:08.427  5536  5536 D HidProfile: Bluetooth service connected
11-23 09:58:08.427  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 09:58:08.427  5640  5640 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 09:58:08.428  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
,11-23 09:58:08.429  5640  5640 D HealthService: Received start request. Starting profile...
,11-23 09:58:08.430  5640  5640 I bt_bluedroid: get_profile_interface health
11-23 09:58:08.431  5640  5640 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-23 09:58:08.432  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
,11-23 09:58:08.433  5536  5536 D BluetoothPan: BluetoothPAN Proxy object connected
,11-23 09:58:08.433  5640  5640 D PanService: Received start request. Starting profile...
11-23 09:58:08.433  5640  5640 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 09:58:08.433  5536  5536 D PanProfile: Bluetooth service connected
11-23 09:58:08.433  5640  5640 I bt_bluedroid: get_profile_interface pan
11-23 09:58:08.434  5640  5656 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-23 09:58:08.435  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
,11-23 09:58:08.436  5536  5536 D BluetoothMap: Proxy object connected
11-23 09:58:08.437  5536  5536 D MapProfile: Bluetooth service connected
,11-23 09:58:08.437  5536  5536 D BluetoothMap: getConnectedDevices()
11-23 09:58:08.438  5536  5536 D BluetoothMap: Bluetooth is Not enabled
11-23 09:58:08.438  5640  5640 D BluetoothMapService: Received start request. Starting profile...
11-23 09:58:08.438  5640  5640 D BluetoothMapService: start()
,11-23 09:58:08.441  5640  5640 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-23 09:58:08.441  5640  5640 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-23 09:58:08.441  5640  5640 D BluetoothMapAppObserver: createReceiver()
,11-23 09:58:08.443  5640  5640 D BluetoothMapAppObserver: initObservers()
11-23 09:58:08.443  5640  5640 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 09:58:08.449  5640  5640 V SapService: SapBinder()
,11-23 09:58:08.449  5640  5640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
11-23 09:58:08.449  5640  5640 D SapService: Received start request. Starting profile...
11-23 09:58:08.449  5640  5640 V SapService: start()
,11-23 09:58:08.451  5640  5640 V BluetoothAdapterState: isTurningOff()=false
,11-23 09:58:08.451  5640  5640 V BluetoothAdapterState: isTurningOn()=true
11-23 09:58:08.451  5640  5670 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 09:58:08.451  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:08.451  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:08.452  5640  5640 V BluetoothAdapterState: isTurningOff()=false
,11-23 09:58:08.452  5640  5640 V BluetoothAdapterState: isTurningOn()=true
11-23 09:58:08.452  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:08.452  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:08.452  5640  5640 V BluetoothAdapterState: isTurningOff()=false
11-23 09:58:08.453  5640  5640 V BluetoothAdapterState: isTurningOn()=true
11-23 09:58:08.453  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 09:58:08.453  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 09:58:08.453  5640  5640 V BluetoothAdapterState: isTurningOff()=false
11-23 09:58:08.453  5640  5640 V BluetoothAdapterState: isTurningOn()=true
11-23 09:58:08.453  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:08.453  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:08.453  5640  5640 V BluetoothAdapterState: isTurningOff()=false
11-23 09:58:08.453  5640  5640 V BluetoothAdapterState: isTurningOn()=true
11-23 09:58:08.454  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:08.454  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:08.454  5640  5640 V BluetoothAdapterState: isTurningOff()=false
,11-23 09:58:08.454  5640  5640 V BluetoothAdapterState: isTurningOn()=true
11-23 09:58:08.454  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:08.454  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:08.455  5640  5640 V BluetoothAdapterState: isTurningOff()=false
11-23 09:58:08.455  5640  5640 V BluetoothAdapterState: isTurningOn()=true
11-23 09:58:08.455  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:08.455  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:08.455  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 09:58:08.455  5640  5652 D BluetoothAdapterProperties: ScanMode =  20
11-23 09:58:08.455  5640  5652 D BluetoothAdapterProperties: State =  11
11-23 09:58:08.456  5640  5656 D BluetoothAdapterProperties: Scan Mode:21
11-23 09:58:08.456  5640  5656 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 09:58:08.457  5640  5652 D BluetoothAdapterProperties: Setting state to 12
11-23 09:58:08.457  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 09:58:08.457   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 09:58:08.457  5640  5652 I BluetoothAdapterState: Entering OnState
11-23 09:58:08.457  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 09:58:08.458  2989  3849 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-23 09:58:08.459   928   928 D BluetoothA2dp: Proxy object connected
11-23 09:58:08.460  2989  3847 D BluetoothPan: onBluetoothStateChange on: true
,11-23 09:58:08.460  2989  2989 D BluetoothA2dp: Proxy object connected
,11-23 09:58:08.462  2989  3014 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 09:58:08.462  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 09:58:08.462  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:58:08.462  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:58:08.462  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 09:58:08.462  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 09:58:08.462  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 09:58:08.462  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 09:58:08.462  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 09:58:08.462  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 09:58:08.464  2989  2989 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 09:58:08.464  2989  2989 D PanProfile: Bluetooth service connected
11-23 09:58:08.464  2989  2989 D BluetoothInputDevice: Proxy object connected
11-23 09:58:08.464  2989  5556 D BluetoothPbap: onBluetoothStateChange: up=true
,11-23 09:58:08.464  2989  2989 D HidProfile: Bluetooth service connected
11-23 09:58:08.464  5476  5476 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 09:58:08.465  5536  5546 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-23 09:58:08.465   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 09:58:08.466  5536  5549 D BluetoothPan: onBluetoothStateChange on: true
11-23 09:58:08.466   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 09:58:08.466  3618  3629 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 09:58:08.467  5536  5546 D BluetoothMap: onBluetoothStateChange: up=true
11-23 09:58:08.467   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 09:58:08.467  5640  5640 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 09:58:08.467  2989  3847 D BluetoothMap: onBluetoothStateChange: up=true
11-23 09:58:08.468  5640  5640 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 09:58:08.469  2989  2989 D BluetoothMap: Proxy object connected
11-23 09:58:08.469  2989  2989 D MapProfile: Bluetooth service connected
11-23 09:58:08.469  5536  5549 D BluetoothPbap: onBluetoothStateChange: up=true
,11-23 09:58:08.469  2989  2989 D BluetoothMap: getConnectedDevices()
11-23 09:58:08.469  5640  5640 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 09:58:08.470  2989  3014 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 09:58:08.470  5640  5640 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 09:58:08.472  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 09:58:08.472   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,11-23 09:58:08.473  5640  5640 D ObexServerSockets: Succeed to create listening sockets 
11-23 09:58:08.473  5640  5640 D ObexServerSockets0: startAccept()
11-23 09:58:08.473  5640  5640 D ObexServerSockets0: prepareForNewConnect()
11-23 09:58:08.474  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 09:58:08.475  5640  5640 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 09:58:08.475  5640  5640 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 09:58:08.476  5640  5640 D BluetoothMapService: onReceive
11-23 09:58:08.476  5640  5679 D ObexServerSockets0: Accepting socket connection...
11-23 09:58:08.476  5640  5640 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 09:58:08.476  5640  5640 D BluetoothMapService: STATE_ON
11-23 09:58:08.476  5640  5680 D ObexServerSockets0: Accepting socket connection...
11-23 09:58:08.476  5536  5536 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-23 09:58:08.478  5640  5681 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 09:58:08.480  5640  5681 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-23 09:58:08.480  5640  5681 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 09:58:08.480  5536  5536 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-23 09:58:08.486  5536  5536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 09:58:08.488  5536  5536 D BluetoothA2dp: Proxy object connected
,11-23 09:58:08.492  3437  3437 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 09:58:08.494  5536  5536 D DockEventReceiver: finishStartingService: stopping service
,11-23 09:58:08.501  5536  5536 D BluetoothPbap: Proxy object connected
11-23 09:58:08.501  5536  5536 D PbapServerProfile: Bluetooth service connected
,11-23 09:58:08.503  2989  2989 D BluetoothPbap: Proxy object connected
,11-23 09:58:08.503  2989  2989 D PbapServerProfile: Bluetooth service connected
,11-23 09:58:08.504  5640  5640 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 09:58:08.504  5640  5640 D ObexServerSockets0: prepareForNewConnect()
11-23 09:58:08.506  5640  5685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 09:58:08.521  5640  5689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 09:58:08.522  5640  5689 I BtOppRfcommListener: Accept thread started.
,11-23 09:58:08.567  2989  3014 D BluetoothHeadset: Proxy object connected
,11-23 09:58:08.567   928   945 D BluetoothHeadset: Proxy object connected
11-23 09:58:08.568  2989  2989 D HeadsetProfile: Bluetooth service connected
11-23 09:58:08.568   928   928 D BluetoothHeadset: Proxy object connected
11-23 09:58:08.568   928   928 D BluetoothHeadset: Proxy object connected
11-23 09:58:08.568   928   928 D BluetoothHeadset: Proxy object connected
11-23 09:58:08.568  3618  3852 D BluetoothHeadset: Proxy object connected
,11-23 09:58:08.570  2989  3849 D BluetoothHeadset: Proxy object connected
11-23 09:58:08.570  2989  2989 D HeadsetProfile: Bluetooth service connected
,11-23 09:58:08.582  5536  5549 D BluetoothHeadset: Proxy object connected
11-23 09:58:08.584  5536  5536 D HeadsetProfile: Bluetooth service connected
,11-23 09:58:10.204   928  2811 D ConnectivityService: handlePromptUnvalidated 101
,11-23 09:58:12.071   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:12.412  5640  5652 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 09:58:12.413  5640  5652 D BluetoothAdapterProperties: Setting state to 13
11-23 09:58:12.413  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-23 09:58:12.414  5640  5652 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 09:58:12.416  5640  5652 I BluetoothAdapterState: Entering PendingCommandState
,11-23 09:58:12.421  5640  5640 D BluetoothMapService: onReceive
11-23 09:58:12.421  5640  5640 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 09:58:12.421  5640  5640 D BluetoothMapService: STATE_TURNING_OFF
,11-23 09:58:12.422  5640  5640 D BluetoothMapService: MAP Service closeService in
,11-23 09:58:12.422  5640  5640 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 09:58:12.422  5640  5640 D ObexServerSockets0: shutdown(block = true)
11-23 09:58:12.424  5640  5640 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 09:58:12.424  5640  5679 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-23 09:58:12.425  5640  5680 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 09:58:12.426  5640  5666 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 09:58:12.427  5640  5640 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 09:58:12.428  5640  5656 D BluetoothAdapterProperties: Scan Mode:20
11-23 09:58:12.428  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-23 09:58:12.429  5536  5536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 09:58:12.432  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 09:58:12.432  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 09:58:12.432  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:58:12.432  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:58:12.432  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 09:58:12.432  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 09:58:12.432  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 09:58:12.432  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 09:58:12.432  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 09:58:12.432  5476  5476 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 09:58:12.432  5640  5640 I BtOppRfcommListener: stopping Accept Thread
11-23 09:58:12.434  5640  5689 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 09:58:12.435  5640  5689 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-23 09:58:12.437  5476  5476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 09:58:12.437  5476  5476 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 09:58:12.441  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 09:58:12.444  3437  3437 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 09:58:12.445  5536  5536 D DockEventReceiver: finishStartingService: stopping service
11-23 09:58:12.447  5640  5640 D HeadsetService: Received stop request...Stopping profile...
,11-23 09:58:12.450  2989  3014 D BluetoothHeadset: Proxy object disconnected
,11-23 09:58:12.451   928   928 D BluetoothHeadset: Proxy object disconnected
11-23 09:58:12.451   928   928 D BluetoothHeadset: Proxy object disconnected
11-23 09:58:12.451   928   928 D BluetoothHeadset: Proxy object disconnected
11-23 09:58:12.452  5536  5549 D BluetoothHeadset: Proxy object disconnected
11-23 09:58:12.453  3618  3637 D BluetoothHeadset: Proxy object disconnected
11-23 09:58:12.454  5536  5536 D HeadsetProfile: Bluetooth service disconnected
,11-23 09:58:12.455  5536  5536 D BluetoothPbap: Proxy object disconnected
11-23 09:58:12.455  5640  5640 D A2dpService: Received stop request...Stopping profile...
11-23 09:58:12.455  5536  5536 D PbapServerProfile: Bluetooth service disconnected
11-23 09:58:12.455  5640  5672 D A2dpStateMachine: Exit Disconnected: -1
11-23 09:58:12.459   928   928 D BluetoothA2dp: Proxy object disconnected
,11-23 09:58:12.459  5536  5536 D BluetoothA2dp: Proxy object disconnected
11-23 09:58:12.460  5640  5640 D HidService: Received stop request...Stopping profile...
,11-23 09:58:12.460  5640  5640 D HidService: Stopping Bluetooth HidService
,11-23 09:58:12.461  5536  5536 D BluetoothInputDevice: Proxy object disconnected
11-23 09:58:12.461  5536  5536 D HidProfile: Bluetooth service disconnected
11-23 09:58:12.461  5640  5640 V BluetoothAdapterState: isTurningOff()=true
11-23 09:58:12.461  5640  5640 V BluetoothAdapterState: isTurningOn()=false
11-23 09:58:12.461  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:12.461  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:12.462  2989  2989 D HeadsetProfile: Bluetooth service disconnected
,11-23 09:58:12.462  5640  5640 D HealthService: Received stop request...Stopping profile...
11-23 09:58:12.462  2989  2989 D BluetoothPbap: Proxy object disconnected
11-23 09:58:12.462  2989  2989 D PbapServerProfile: Bluetooth service disconnected
11-23 09:58:12.462  2989  2989 D BluetoothA2dp: Proxy object disconnected
11-23 09:58:12.462  2989  2989 D BluetoothInputDevice: Proxy object disconnected
11-23 09:58:12.462  2989  2989 D HidProfile: Bluetooth service disconnected
11-23 09:58:12.465  5640  5640 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 09:58:12.465  5640  5640 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 09:58:12.465  5640  5664 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 09:58:12.465  5640  5664 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 09:58:12.466  5640  5664 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 09:58:12.466  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 09:58:12.466  5640  5640 D PanService: Received stop request...Stopping profile...
11-23 09:58:12.466  5640  5656 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 09:58:12.467  2989  2989 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 09:58:12.467  5536  5536 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 09:58:12.467  2989  2989 D PanProfile: Bluetooth service disconnected
11-23 09:58:12.467  5536  5536 D PanProfile: Bluetooth service disconnected
11-23 09:58:12.468  5640  5640 D BluetoothMapService: Received stop request...Stopping profile...
11-23 09:58:12.468  5640  5640 D BluetoothMapService: stop()
11-23 09:58:12.469  5640  5640 D BluetoothMapAppObserver: deinitObservers()
11-23 09:58:12.469  5640  5640 D BluetoothMapAppObserver: removeReceiver()
11-23 09:58:12.470  2989  2989 D BluetoothMap: Proxy object disconnected
11-23 09:58:12.470  2989  2989 D MapProfile: Bluetooth service disconnected
11-23 09:58:12.470  5536  5536 D BluetoothMap: Proxy object disconnected
11-23 09:58:12.470  5536  5536 D MapProfile: Bluetooth service disconnected
11-23 09:58:12.471  5640  5640 D SapService: Received stop request...Stopping profile...
11-23 09:58:12.471  5640  5640 V SapService: stop()
11-23 09:58:12.472  5640  5640 V BluetoothAdapterState: isTurningOff()=true
11-23 09:58:12.472  5640  5640 V BluetoothAdapterState: isTurningOn()=false
11-23 09:58:12.472  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:12.472  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:12.473  5640  5664 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 09:58:12.474  5640  5664 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 09:58:12.474  5640  5640 V BluetoothAdapterState: isTurningOff()=true
11-23 09:58:12.474  5640  5640 V BluetoothAdapterState: isTurningOn()=false
11-23 09:58:12.474  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:12.474  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 09:58:12.474  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 09:58:12.474  5640  5664 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 09:58:12.474  5640  5664 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 09:58:12.474  5640  5664 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 09:58:12.474  5640  5640 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 09:58:12.474  5640  5664 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 09:58:12.474  5640  5640 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 09:58:12.474  5640  5656 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 09:58:12.474  5640  5640 V BluetoothAdapterState: isTurningOff()=true
11-23 09:58:12.474  5640  5640 V BluetoothAdapterState: isTurningOn()=false
11-23 09:58:12.474  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:12.474  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:12.475  5640  5640 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 09:58:12.475  5640  5656 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 09:58:12.475  5640  5640 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 09:58:12.475  5640  5640 V BluetoothAdapterState: isTurningOff()=true
,11-23 09:58:12.475  5640  5640 V BluetoothAdapterState: isTurningOn()=false
11-23 09:58:12.475  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:12.475  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:12.476  5640  5640 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 09:58:12.476  5640  5640 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 09:58:12.477  5640  5640 D BluetoothMapService: MAP Service closeService in
11-23 09:58:12.477  5640  5640 V BluetoothAdapterState: isTurningOff()=true
11-23 09:58:12.477  5640  5640 V BluetoothAdapterState: isTurningOn()=false
11-23 09:58:12.477  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:12.477  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:12.477  5640  5640 D BluetoothMapService: cleanup()
11-23 09:58:12.477  5640  5640 D BluetoothMapService: MAP Service closeService in
11-23 09:58:12.478  5640  5640 V BluetoothAdapterState: isTurningOff()=true
11-23 09:58:12.478  5640  5640 V BluetoothAdapterState: isTurningOn()=false
11-23 09:58:12.478  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:12.478  5640  5640 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:12.478  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 09:58:12.478  5640  5652 D BluetoothAdapterProperties: Setting state to 15
11-23 09:58:12.478  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 09:58:12.479  5640  5652 I BluetoothAdapterState: Entering BleOnState
11-23 09:58:12.479   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-23 09:58:12.480  5536  5693 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 09:58:12.481  2989  5556 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 09:58:12.482  2989  3847 D BluetoothPan: onBluetoothStateChange on: false
11-23 09:58:12.482  2989  3003 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 09:58:12.484  2989  5556 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 09:58:12.484  5536  5549 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-23 09:58:12.485   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 09:58:12.485  5536  5546 D BluetoothPan: onBluetoothStateChange on: false
11-23 09:58:12.485   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 09:58:12.486  3618  3629 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 09:58:12.486  5536  5693 D BluetoothMap: onBluetoothStateChange: up=false
11-23 09:58:12.486   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 09:58:12.487  5536  5549 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 09:58:12.487  2989  3847 D BluetoothMap: onBluetoothStateChange: up=false
11-23 09:58:12.487  5536  5546 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 09:58:12.488  2989  3849 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 09:58:12.488  5640  5652 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 09:58:12.488  5640  5652 D BluetoothAdapterProperties: Setting state to 16
11-23 09:58:12.488  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 09:58:12.489  5640  5652 D BluetoothAdapterProperties: onBleDisable
11-23 09:58:12.489  5640  5652 I BluetoothAdapterState: Entering PendingCommandState
11-23 09:58:12.489  5640  5653 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-23 09:58:12.491  5640  5664 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 09:58:12.491  5640  5664 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 09:58:12.492  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:58:12.494  5640  5656 D BluetoothAdapterProperties: Scan Mode:20
,11-23 09:58:12.494  5536  5536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 09:58:12.496  5476  5476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:58:12.500  3437  3437 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 09:58:12.500  5536  5536 D DockEventReceiver: finishStartingService: stopping service
,11-23 09:58:12.703  5640  5656 I bt_hci  : shut_down
,11-23 09:58:12.708  5640  5660 D bt_hwcfg: hw_epilog_process
,11-23 09:58:12.710  5640  5660 I bt_vendor: low_power_mode_cb
,11-23 09:58:12.713  5640  5660 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 09:58:12.713  5640  5660 I bt_vendor: epilog_cb
11-23 09:58:12.714  5640  5660 I bt_hci  : epilog_finished_callback
,11-23 09:58:12.717  5640  5656 I bt_hci_h4: hal_close
,11-23 09:58:12.717  5640  5656 I bt_userial_vendor: device fd = 54 close
,11-23 09:58:12.836  5640  5653 D bt_stack_manager: event_shut_down_stack finished.
,11-23 09:58:12.837  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 09:58:12.840  5640  5652 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-23 09:58:12.840  5640  5640 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 09:58:12.841  5640  5640 D BtGatt.GattService: Received stop request...Stopping profile...
,11-23 09:58:12.842  5640  5640 D BtGatt.GattService: stop()
11-23 09:58:12.842  5640  5640 D BtGatt.AdvertiseManager: advertise clients cleared
11-23 09:58:12.845  5640  5640 V BluetoothAdapterState: isTurningOff()=false
11-23 09:58:12.845  5640  5640 V BluetoothAdapterState: isTurningOn()=false
11-23 09:58:12.845  5640  5640 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:12.845  5640  5640 V BluetoothAdapterState: isBleTurningOff()=true
11-23 09:58:12.846  5640  5652 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-23 09:58:12.846  5640  5652 D BluetoothAdapterProperties: Setting state to 10
11-23 09:58:12.846  5640  5652 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 09:58:12.847  5640  5652 I BluetoothAdapterState: Entering OffState
,11-23 09:58:12.848   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 09:58:12.861  5640  5640 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 09:58:12.861  5640  5640 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 09:58:12.862  5640  5640 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-23 09:58:12.864  5640  5653 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 09:58:12.872  5640  5640 I art     : System.exit called, status: 0
,11-23 09:58:12.872  5640  5640 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 09:58:12.906   928  3705 I ActivityManager: Process com.android.bluetooth (pid 5640) has died
,11-23 09:58:13.072   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:13.244  3437  3437 I ConfigService: onDestroy
,11-23 09:58:14.073   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:15.074   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:16.075   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:17.076   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 09:58:17.412  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 09:58:17.412  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 09:58:17.418  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 09:58:17.418  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1239f74 removed from the list
11-23 09:58:17.418  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 09:58:17.422  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 09:58:17.423  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9f114e3 added. We now have 4 listener(s)
11-23 09:58:17.423  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 09:58:17.425  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:17.425  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9f114e3 removed from the list
11-23 09:58:17.425  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:58:17.427  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:58:17.427  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a953ee0 added. We now have 4 listener(s)
,11-23 09:58:17.427  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 09:58:22.437  5476  5524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:58:22.474   928   945 I ActivityManager: Start proc 5698:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 09:58:22.572  5698  5698 D AdapterServiceConfig: Adding HeadsetService
,11-23 09:58:22.572  5698  5698 D AdapterServiceConfig: Adding A2dpService
11-23 09:58:22.572  5698  5698 D AdapterServiceConfig: Adding HidService
11-23 09:58:22.573  5698  5698 D AdapterServiceConfig: Adding HealthService
11-23 09:58:22.573  5698  5698 D AdapterServiceConfig: Adding PanService
11-23 09:58:22.573  5698  5698 D AdapterServiceConfig: Adding GattService
11-23 09:58:22.573  5698  5698 D AdapterServiceConfig: Adding BluetoothMapService
11-23 09:58:22.573  5698  5698 D AdapterServiceConfig: Adding SapService
,11-23 09:58:22.585   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fd22e43:true
,11-23 09:58:22.586  5698  5698 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 09:58:22.589  5698  5698 I bt_bluedroid: init
,11-23 09:58:22.590  5698  5710 I BluetoothAdapterState: Entering OffState
,11-23 09:58:22.592  5698  5711 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-23 09:58:22.592  5698  5711 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 09:58:22.592  5698  5711 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 09:58:22.592  5698  5711 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-23 09:58:22.593  5698  5698 I bt_bluedroid: get_profile_interface socket
,11-23 09:58:22.595  5698  5698 I bt_bluedroid: get_profile_interface sdp
,11-23 09:58:22.595  5698  5714 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-23 09:58:22.596  5698  5714 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 09:58:22.600  5698  5709 I bt_bluedroid: config_hci_snoop_log
11-23 09:58:22.601   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 09:58:22.604  5698  5710 D BluetoothAdapterState: Current state: OFF, message: 0
11-23 09:58:22.604  5698  5710 D BluetoothAdapterProperties: Setting state to 14
,11-23 09:58:22.604  5698  5710 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-23 09:58:22.606  5698  5710 D BluetoothBondStateMachine: make
,11-23 09:58:22.608  5698  5715 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 09:58:22.610  5698  5710 I BluetoothAdapterState: Entering PendingCommandState
,11-23 09:58:22.611  5698  5698 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-23 09:58:22.613  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
,11-23 09:58:22.614  5698  5698 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 09:58:22.614  5698  5698 D BtGatt.GattService: Received start request. Starting profile...
11-23 09:58:22.614  5698  5698 D BtGatt.GattService: start()
11-23 09:58:22.614  5698  5698 I bt_bluedroid: get_profile_interface gatt
,11-23 09:58:22.615  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
11-23 09:58:22.615  5698  5698 D BtGatt.AdvertiseManager: advertise manager created
,11-23 09:58:22.620  5698  5698 V BluetoothAdapterState: isTurningOff()=false
,11-23 09:58:22.620  5698  5698 V BluetoothAdapterState: isTurningOn()=false
11-23 09:58:22.620  5698  5698 V BluetoothAdapterState: isBleTurningOn()=true
11-23 09:58:22.620  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:22.620  5698  5710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 09:58:22.622  5698  5710 I bt_bluedroid: bt_bluedroid
11-23 09:58:22.622  5698  5711 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-23 09:58:22.622  5698  5711 I bt_hci  : start_up
,11-23 09:58:22.627  5698  5711 I bt_vendor: alloc value 0xf4273871
,11-23 09:58:22.627  5698  5711 I bt_vendor: init
11-23 09:58:22.627  5698  5711 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 09:58:22.627  5698  5711 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 09:58:22.737  5698  5711 D bt_hci  : start_up starting async portion
11-23 09:58:22.737  5698  5718 I bt_hci  : event_finish_startup
11-23 09:58:22.737  5698  5718 I bt_hci_h4: hal_open
11-23 09:58:22.737  5698  5718 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 09:58:22.736  5719  5719 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-23 09:58:22.739  5698  5718 I bt_userial_vendor: device fd = 54 open
,11-23 09:58:22.752  5698  5718 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 09:58:22.754  5698  5718 D bt_hwcfg: Chipset BCM4358A3
,11-23 09:58:22.754  5698  5718 D bt_hwcfg: Target name = [BCM4358A3]
11-23 09:58:22.754  5698  5718 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 09:58:23.154  5698  5718 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 09:58:23.155  5698  5718 D bt_hwcfg: Settlement delay -- 100 ms
11-23 09:58:23.155  5698  5718 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 09:58:23.290  5698  5718 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-23 09:58:23.290  5698  5718 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-23 09:58:23.292  5698  5718 I bt_hwcfg: vendor lib fwcfg completed
,11-23 09:58:23.292  5698  5718 I bt_vendor: firmware callback
11-23 09:58:23.292  5698  5718 I bt_hci  : firmware_config_callback
,11-23 09:58:23.303  5698  5721 I bt_btu  : btu_task pending for preload complete event
,11-23 09:58:23.303  5698  5721 I bt_btu_task: Bluetooth chip preload is complete
11-23 09:58:23.303  5698  5721 I bt_btu  : btu_task received preload complete event
,11-23 09:58:23.309  5698  5721 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 09:58:23.310  5698  5721 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 09:58:23.310  5698  5721 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-23 09:58:23.310  5698  5721 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 09:58:23.310  5698  5721 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 09:58:23.310  5698  5721 I         : BTE_InitTraceLevels -- TRC_A2D
,11-23 09:58:23.310  5698  5721 I         : BTE_InitTraceLevels -- TRC_BNEP
11-23 09:58:23.310  5698  5721 I         : BTE_InitTraceLevels -- TRC_BTM
,11-23 09:58:23.311  5698  5721 I         : BTE_InitTraceLevels -- TRC_GAP
11-23 09:58:23.311  5698  5721 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 09:58:23.311  5698  5721 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 09:58:23.311  5698  5721 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 09:58:23.311  5698  5721 I         : BTE_InitTraceLevels -- TRC_SMP
,11-23 09:58:23.311  5698  5721 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 09:58:23.311  5698  5721 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 09:58:23.396  5698  5721 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41f1549
11-23 09:58:23.396  5698  5721 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41f1549 
,11-23 09:58:23.420  5698  5714 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 09:58:23.421  5698  5714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 09:58:23.421  5698  5714 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 09:58:23.424  5698  5714 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 09:58:23.425  5698  5714 D BluetoothAdapterProperties: Scan Mode:20
11-23 09:58:23.426  5698  5714 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 09:58:23.426  5698  5714 D bt_hci  : do_postload posting postload work item
11-23 09:58:23.426  5698  5718 I bt_hci  : event_postload
11-23 09:58:23.426  5698  5718 I bt_vendor: sco_config_cb
11-23 09:58:23.426  5698  5718 I bt_hci  : sco_config_callback postload finished.
11-23 09:58:23.428  5698  5714 D bt_bte_conf: Device ID record 1 : primary
11-23 09:58:23.428  5698  5714 D bt_bte_conf:   vendorId            = 000f
11-23 09:58:23.428  5698  5714 D bt_bte_conf:   vendorIdSource      = 0001
11-23 09:58:23.428  5698  5714 D bt_bte_conf:   product             = 1200
11-23 09:58:23.428  5698  5714 D bt_bte_conf:   version             = 1436
11-23 09:58:23.428  5698  5714 D bt_bte_conf:   clientExecutableURL = 
11-23 09:58:23.428  5698  5714 D bt_bte_conf:   serviceDescription  = 
,11-23 09:58:23.428  5698  5714 D bt_bte_conf:   documentationURL    = 
11-23 09:58:23.428  5698  5714 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 09:58:23.429  5698  5711 D bt_stack_manager: event_start_up_stack finished
,11-23 09:58:23.429  5698  5710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-23 09:58:23.430  5698  5710 D BluetoothAdapterProperties: Setting state to 15
11-23 09:58:23.430  5698  5710 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 09:58:23.431  5698  5710 I BluetoothAdapterState: Entering BleOnState
,11-23 09:58:23.437  5698  5718 I bt_vendor: low_power_mode_cb
11-23 09:58:23.439  5698  5710 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-23 09:58:23.439  5698  5710 D BluetoothAdapterProperties: Setting state to 11
11-23 09:58:23.440  5698  5710 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 09:58:23.446  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
11-23 09:58:23.447  5698  5698 D HeadsetService: Received start request. Starting profile...
11-23 09:58:23.449  5698  5698 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 09:58:23.450  5698  5698 D HeadsetStateMachine: make
,11-23 09:58:23.464  5698  5698 D HeadsetStateMachine: max_hf_connections = 1
11-23 09:58:23.464  5698  5698 I bt_bluedroid: get_profile_interface handsfree
,11-23 09:58:23.464  5698  5714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 09:58:23.464  5698  5714 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-23 09:58:23.467  5698  5710 I BluetoothAdapterState: Entering PendingCommandState
,11-23 09:58:23.467  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
,11-23 09:58:23.469  5698  5698 D A2dpService: Received start request. Starting profile...
,11-23 09:58:23.469  5698  5698 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 09:58:23.470  5698  5698 I bt_bluedroid: get_profile_interface avrcp
,11-23 09:58:23.475  5698  5698 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 09:58:23.475  5698  5698 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 09:58:23.475  5698  5698 D A2dpStateMachine: make
11-23 09:58:23.477  5698  5698 I bt_bluedroid: get_profile_interface a2dp
,11-23 09:58:23.477  5698  5714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-23 09:58:23.479  5698  5729 D A2dpStateMachine: Enter Disconnected: -2
,11-23 09:58:23.479  5698  5698 I BluetoothHidServiceJni: classInitNative: succeeds
,11-23 09:58:23.480  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
11-23 09:58:23.480  5698  5698 D HidService: Received start request. Starting profile...
11-23 09:58:23.481  5698  5698 I bt_bluedroid: get_profile_interface hidhost
11-23 09:58:23.481  5698  5698 D HidService: setHidService(): set to: null
11-23 09:58:23.481  5698  5714 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41d256d
11-23 09:58:23.481  5698  5714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 09:58:23.481  5698  5698 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 09:58:23.482  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
11-23 09:58:23.482  5698  5698 D HealthService: Received start request. Starting profile...
,11-23 09:58:23.483  5698  5698 I bt_bluedroid: get_profile_interface health
,11-23 09:58:23.484  5698  5698 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 09:58:23.485  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
,11-23 09:58:23.485  5698  5698 D PanService: Received start request. Starting profile...
11-23 09:58:23.485  5698  5698 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 09:58:23.485  5698  5698 I bt_bluedroid: get_profile_interface pan
11-23 09:58:23.486  5698  5714 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 09:58:23.489  3437  3437 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 09:58:23.490  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
11-23 09:58:23.491  5698  5698 D BluetoothMapService: Received start request. Starting profile...
11-23 09:58:23.491  5698  5698 D BluetoothMapService: start()
,11-23 09:58:23.494  5698  5698 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-23 09:58:23.494  5698  5698 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 09:58:23.495  5698  5698 D BluetoothMapAppObserver: createReceiver()
,11-23 09:58:23.496  5698  5698 D BluetoothMapAppObserver: initObservers()
,11-23 09:58:23.496  5698  5698 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 09:58:23.504  5698  5698 V SapService: SapBinder()
11-23 09:58:23.504  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
,11-23 09:58:23.504  5698  5698 D SapService: Received start request. Starting profile...
11-23 09:58:23.504  5698  5698 V SapService: start()
,11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isTurningOff()=false
11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isTurningOn()=true
11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:23.506  5698  5726 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isTurningOff()=false
11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isTurningOn()=true
,11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isTurningOff()=false
11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isTurningOn()=true
11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isTurningOff()=false
,11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isTurningOn()=true
11-23 09:58:23.506  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:23.507  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:23.507  5698  5698 V BluetoothAdapterState: isTurningOff()=false
11-23 09:58:23.507  5698  5698 V BluetoothAdapterState: isTurningOn()=true
,11-23 09:58:23.507  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:23.507  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:23.507  5698  5698 V BluetoothAdapterState: isTurningOff()=false
11-23 09:58:23.507  5698  5698 V BluetoothAdapterState: isTurningOn()=true
11-23 09:58:23.507  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:23.507  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:23.508  5698  5698 V BluetoothAdapterState: isTurningOff()=false
11-23 09:58:23.508  5698  5698 V BluetoothAdapterState: isTurningOn()=true
11-23 09:58:23.508  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-23 09:58:23.508  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-23 09:58:23.508  5698  5710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 09:58:23.508  5698  5710 D BluetoothAdapterProperties: ScanMode =  20
11-23 09:58:23.508  5698  5710 D BluetoothAdapterProperties: State =  11
,11-23 09:58:23.508  5698  5710 D BluetoothAdapterProperties: Setting state to 12
11-23 09:58:23.509  5698  5710 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 09:58:23.509   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 09:58:23.510  5698  5710 I BluetoothAdapterState: Entering OnState
,11-23 09:58:23.512  5536  5693 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-23 09:58:23.512  5698  5714 D BluetoothAdapterProperties: Scan Mode:21
11-23 09:58:23.513  5698  5714 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 09:58:23.513   928   928 D BluetoothA2dp: Proxy object connected
11-23 09:58:23.514  2989  3014 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 09:58:23.516  2989  2989 D BluetoothA2dp: Proxy object connected
11-23 09:58:23.516  2989  3003 D BluetoothPan: onBluetoothStateChange on: true
11-23 09:58:23.516  5536  5536 D BluetoothA2dp: Proxy object connected
11-23 09:58:23.518  2989  3847 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 09:58:23.519  2989  2989 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 09:58:23.519  2989  2989 D PanProfile: Bluetooth service connected
,11-23 09:58:23.522  2989  3014 D BluetoothPbap: onBluetoothStateChange: up=true
,11-23 09:58:23.523  5698  5698 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 09:58:23.523  5698  5698 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 09:58:23.524  5698  5698 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 09:58:23.526  5698  5698 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 09:58:23.527  5698  5698 D ObexServerSockets: Succeed to create listening sockets 
11-23 09:58:23.527  5698  5698 D ObexServerSockets0: startAccept()
11-23 09:58:23.527  5698  5698 D ObexServerSockets0: prepareForNewConnect()
,11-23 09:58:23.527  5536  5546 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 09:58:23.529   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 09:58:23.529  5536  5549 D BluetoothPan: onBluetoothStateChange on: true
11-23 09:58:23.530  5698  5698 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 09:58:23.530  5698  5698 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-23 09:58:23.530  5698  5735 D ObexServerSockets0: Accepting socket connection...
11-23 09:58:23.530  5698  5736 D ObexServerSockets0: Accepting socket connection...
11-23 09:58:23.531   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 09:58:23.531  2989  2989 D BluetoothInputDevice: Proxy object connected
11-23 09:58:23.531  2989  2989 D HidProfile: Bluetooth service connected
11-23 09:58:23.531  3618  3852 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 09:58:23.532  5536  5693 D BluetoothMap: onBluetoothStateChange: up=true
11-23 09:58:23.534   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 09:58:23.534  5536  5549 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 09:58:23.535  2989  3003 D BluetoothMap: onBluetoothStateChange: up=true
11-23 09:58:23.536  2989  2989 D BluetoothMap: Proxy object connected
11-23 09:58:23.536  5536  5693 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 09:58:23.536  2989  2989 D MapProfile: Bluetooth service connected
11-23 09:58:23.536  2989  2989 D BluetoothMap: getConnectedDevices()
11-23 09:58:23.538  2989  3847 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 09:58:23.539  5536  5536 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 09:58:23.539  5536  5536 D PanProfile: Bluetooth service connected
11-23 09:58:23.539  5536  5536 D BluetoothInputDevice: Proxy object connected
11-23 09:58:23.539   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 09:58:23.539  5536  5536 D HidProfile: Bluetooth service connected
11-23 09:58:23.540  5698  5698 D BluetoothMapService: onReceive
11-23 09:58:23.540  5698  5698 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 09:58:23.540  5698  5698 D BluetoothMapService: STATE_ON
11-23 09:58:23.542  5536  5536 D BluetoothMap: Proxy object connected
11-23 09:58:23.542  5536  5536 D MapProfile: Bluetooth service connected
11-23 09:58:23.542  5536  5536 D BluetoothMap: getConnectedDevices()
11-23 09:58:23.543  5698  5737 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 09:58:23.544  5698  5737 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 09:58:23.544  5698  5737 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 09:58:23.548  5536  5536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 09:58:23.554  5536  5536 D DockEventReceiver: finishStartingService: stopping service
11-23 09:58:23.555  3437  3437 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 09:58:23.561  2989  2989 D BluetoothPbap: Proxy object connected
,11-23 09:58:23.561  5536  5536 D BluetoothPbap: Proxy object connected
11-23 09:58:23.561  2989  2989 D PbapServerProfile: Bluetooth service connected
11-23 09:58:23.561  5536  5536 D PbapServerProfile: Bluetooth service connected
,11-23 09:58:23.567  5698  5698 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 09:58:23.567  5698  5698 D ObexServerSockets0: prepareForNewConnect()
11-23 09:58:23.569  5698  5741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 09:58:23.583  5698  5745 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 09:58:23.584  5698  5745 I BtOppRfcommListener: Accept thread started.
,11-23 09:58:23.631  2989  3847 D BluetoothHeadset: Proxy object connected
11-23 09:58:23.631  2989  2989 D HeadsetProfile: Bluetooth service connected
,11-23 09:58:23.631   928   928 D BluetoothHeadset: Proxy object connected
11-23 09:58:23.631   928   928 D BluetoothHeadset: Proxy object connected
11-23 09:58:23.631   928   928 D BluetoothHeadset: Proxy object connected
11-23 09:58:23.631   928   945 D BluetoothHeadset: Proxy object connected
11-23 09:58:23.631  5536  5549 D BluetoothHeadset: Proxy object connected
11-23 09:58:23.632  3618  3637 D BluetoothHeadset: Proxy object connected
,11-23 09:58:23.633  3618  3629 D BluetoothHeadset: Proxy object connected
,11-23 09:58:23.633  5536  5536 D HeadsetProfile: Bluetooth service connected
11-23 09:58:23.634   928   945 D BluetoothHeadset: Proxy object connected
11-23 09:58:23.634  5536  5693 D BluetoothHeadset: Proxy object connected
,11-23 09:58:23.635  5536  5536 D HeadsetProfile: Bluetooth service connected
,11-23 09:58:23.638  2989  3014 D BluetoothHeadset: Proxy object connected
,11-23 09:58:23.638  2989  2989 D HeadsetProfile: Bluetooth service connected
,11-23 09:58:27.454  5476  5524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 09:58:27.454  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:58:27.454  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:58:27.454  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 09:58:27.454  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 09:58:27.454  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 09:58:27.454  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 09:58:27.454  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 09:58:27.454  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 09:58:27.459  5476  5524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 09:58:27.460  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:27.460  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a953ee0 removed from the list
11-23 09:58:27.461  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 09:58:27.462  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:58:27.463  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bf43599 added. We now have 4 listener(s)
11-23 09:58:27.463  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 09:58:27.467   928  3002 D WifiService: setWifiEnabled: false pid=5476, uid=10077
,11-23 09:58:27.467   928  3002 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 09:58:32.077   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:32.477  5476  5524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 09:58:32.478   928  3276 D WifiService: setWifiEnabled: true pid=5476, uid=10077
11-23 09:58:32.478   928  3276 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 09:58:32.486   505   926 D SoftapController: Softap fwReload - Ok
,11-23 09:58:32.492   505   926 D CommandListener: Setting iface cfg
,11-23 09:58:32.492   505   926 D CommandListener: Trying to bring down wlan0
11-23 09:58:32.494   505   926 D CommandListener: Clearing all IP addresses on wlan0
,11-23 09:58:32.498   928  2809 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 09:58:33.078   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:33.174   928  2809 D wifi    : set interface wlan0 flags (UP)
,11-23 09:58:33.175   928  2809 I WifiHAL : Initializing wifi
11-23 09:58:33.175   928  2809 I WifiHAL : Creating socket
,11-23 09:58:33.183   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 09:58:33.184   928  2809 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-23 09:58:33.184   928  2809 D wifi    : Did set static halHandle = 0x7f7a26a680
11-23 09:58:33.185   928  2809 D wifi    : halHandle = 0x7f7a26a680, mVM = 0x7f9684d140, mCls = 0x201906
,11-23 09:58:33.185   928  2809 D wifi    : array field set
11-23 09:58:33.185   928  2809 I WifiNative-HAL: interface[0] = wlan0
11-23 09:58:33.187   928  5750 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547510199936
11-23 09:58:33.187   928  5750 D wifi    : waitForHalEvents called, vm = 0x7f9684d140, obj = 0x201906, env = 0x7f7ab2b2c0
,11-23 09:58:33.244  5751  5751 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 09:58:33.288   928  2809 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 09:58:33.319  5751  5751 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 09:58:33.376  5751  5751 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 09:58:33.376  5751  5751 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 09:58:33.396   928  2809 D WifiConfigStore: Loading config and enabling all networks 
,11-23 09:58:33.427   928  2809 D WifiConfigStore: loaded 0 passpoint configs
,11-23 09:58:33.429   928  2809 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-23 09:58:33.429   928  2809 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-23 09:58:33.430   928  2809 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-23 09:58:33.431   928  2809 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-23 09:58:33.431   928  2809 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-23 09:58:33.432   928  2809 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-23 09:58:33.433   928  2809 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-23 09:58:33.433   928  2809 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-23 09:58:33.433   928  2809 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-23 09:58:33.433   928  2809 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-23 09:58:33.433   928  2809 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-23 09:58:33.434   928  2809 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-23 09:58:33.438   928  2809 D WifiNative-HAL: Setting external_sim to 1
,11-23 09:58:33.438  4870  4870 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 09:58:33.438   928  2809 D wifi    : setting dfs flag to true, 0x7f7c3d0b40
11-23 09:58:33.439   928  2809 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 09:58:33.439   928  2809 D wifi    : setting scan oui 0x7f7c3d0b40
11-23 09:58:33.439   928  2809 D WifiHAL : Sending mac address OUI
,11-23 09:58:33.443   928  2809 E native  : do suspend false
,11-23 09:58:33.454   928  2809 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 09:58:33.455   928   928 D RttService: SCAN_AVAILABLE : 3
11-23 09:58:33.455   505   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-23 09:58:33.455   928  2917 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-23 09:58:33.457   505   926 D CommandListener: Setting iface cfg
,11-23 09:58:33.460   928  2808 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
11-23 09:58:33.460   928  2808 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 09:58:33.470   928  2808 D WifiNative-HAL: p2pGetDeviceAddress
11-23 09:58:33.470   928  2808 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-23 09:58:33.476   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=275287 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-23 09:58:34.085   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:35.086   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:36.087   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:36.496  5751  5751 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 09:58:36.500  5751  5751 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 09:58:36.547   928  2809 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 09:58:36.548   928  2809 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 09:58:36.548   928  2809 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 09:58:36.561   928  2809 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 09:58:36.593   928  2809 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 09:58:36.600  5751  5751 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 09:58:37.023  5751  5751 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 09:58:37.059  5751  5751 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 09:58:37.059  5751  5751 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 09:58:37.067   928  2809 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-23 09:58:37.068   928  2809 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 09:58:37.068   928  2811 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 09:58:37.086   928  2809 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 09:58:37.088   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 09:58:37.098   505   926 D CommandListener: Setting iface cfg
,11-23 09:58:37.105   928  2809 D WifiStateMachine: Start Dhcp Watchdog 3
,11-23 09:58:37.111   928  5756 D DhcpClient: Receive thread started
,11-23 09:58:37.117   928  2809 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-23 09:58:37.117   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-23 09:58:37.117   928  2811 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-23 09:58:37.198   928  2809 E native  : do suspend false
,11-23 09:58:37.212   928  5755 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 09:58:37.225   928  5756 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-23 09:58:37.226   928  5755 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-23 09:58:37.228   928  5755 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-23 09:58:37.242   928  5756 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 09:58:37.242   928  5755 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 09:58:37.245   505   926 D CommandListener: Setting iface cfg
,11-23 09:58:37.248   928  2809 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 09:58:37.253   928  5755 D DhcpClient: Scheduling renewal in 86399s
,11-23 09:58:37.262   928  2809 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-23 09:58:37.263   928  2809 D WifiConfigStore: No blacklist allowed without epno enabled
11-23 09:58:37.264   928  2811 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-23 09:58:37.265   928  2811 D ConnectivityService: Adding iface wlan0 to network 102
,11-23 09:58:37.268   928  2809 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 09:58:37.311   928  2811 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-23 09:58:37.311   928  2811 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-23 09:58:37.313   928  2811 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-23 09:58:37.318   928  2811 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-23 09:58:37.321   928  2811 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-23 09:58:37.327   928  2811 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 09:58:37.332   928  2811 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-23 09:58:37.332   928  2811 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-23 09:58:37.332   928  2811 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-23 09:58:37.332   928  2811 D ConnectivityService:    accepting network in place of null
11-23 09:58:37.332   928  2809 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 09:58:37.332   928  2809 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 09:58:37.333   928  2811 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 09:58:37.345   928  5754 D NetlinkSocketObserver: NeighborEvent{elapsedMs=279155, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 09:58:37.356   505   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 09:58:37.378   505   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 09:58:37.382   928  2811 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-23 09:58:37.382  3577  3738 W QCNEJ   : |CORE| network available: 102
11-23 09:58:37.382   928  2811 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 09:58:37.383   928  2811 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-23 09:58:37.384   928   945 D Tethering: MasterInitialState.processMessage what=3
11-23 09:58:37.386  3577  3738 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 09:58:37.387  3577  3738 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 09:58:37.387  3577  3738 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 09:58:37.397  4906  4929 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 09:58:37.398  4906  4929 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 09:58:37.398  4906  4929 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 09:58:37.398  4906  4929 E SarControlService: no key has been found,reset the power
11-23 09:58:37.398  4906  4941 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 09:58:37.398  4906  4941 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 09:58:37.398  4906  4941 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 09:58:37.398  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 09:58:37.399  4931  4931 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-23 09:58:37.400  4906  4941 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-23 09:58:37.400  4906  4941 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 09:58:37.400  4906  4941 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 09:58:37.401  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 09:58:37.401  4931  4931 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 09:58:37.403  3710  3710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 09:58:37.406  4931  4945 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1174d29 HexData = [00000000f003000000000000ffffffff]
11-23 09:58:37.406  4931  4945 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 09:58:37.406  4931  4945 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-23 09:58:37.407  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 09:58:37.407  4906  4917 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-23 09:58:37.408  3710  3710 D SystemUpdateService: onCreate
,11-23 09:58:37.409  3827  3827 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-23 09:58:37.414  3710  3710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 09:58:37.415  4931  4945 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1174d29 HexData = [00000000f103000000000000ffffffff]
11-23 09:58:37.415  4931  4945 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 09:58:37.415  4931  4945 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-23 09:58:37.416  4931  4931 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 09:58:37.416  4906  4916 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-23 09:58:37.421   928  5753 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:804::200e
,11-23 09:58:37.435  3710  3710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 09:58:37.444  3710  5259 I iu.UploadsManager: num queued entries: 0
,11-23 09:58:37.444  3710  5259 I iu.UploadsManager: num updated entries: 0
11-23 09:58:37.445  3710  5259 I iu.SyncManager: NEXT; no task
,11-23 09:58:37.446  3710  3710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 09:58:37.448  3710  3710 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 09:58:37.450  5262  5262 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-23 09:58:37.454  5262  5262 D SprintDMHelper: simOperator: 
11-23 09:58:37.454  5262  5262 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 09:58:37.459  3710  5768 I SystemUpdateService: active receiver: enabled
,11-23 09:58:37.482   928  5753 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 08:58:37 GMT], X-Android-Received-Millis=[1479891517481], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479891517457]}
,11-23 09:58:37.483   928  2811 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-23 09:58:37.483   928  2811 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-23 09:58:37.483   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-23 09:58:37.484  3710  5768 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-23 09:58:37.484   928  2811 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 09:58:37.490  5476  5524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 09:58:37.490  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 09:58:37.490  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 09:58:37.490  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 09:58:37.490  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 09:58:37.490  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 09:58:37.490  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 09:58:37.490  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 09:58:37.490  5476  5524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 09:58:37.491  3710  5768 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-23 09:58:37.491  3710  5768 I SystemUpdateService: now status is 0 (complete)
11-23 09:58:37.491  3710  5768 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 09:58:37.491  3710  5768 I SystemUpdateService: file has been verified
11-23 09:58:37.491  3710  5768 I SystemUpdateService: OTA package size = 21989297
11-23 09:58:37.491  5476  5524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 09:58:37.492  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.492  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bf43599 removed from the list
11-23 09:58:37.492  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 09:58:37.496  3710  5768 I SystemUpdateService: showing system update notification
,11-23 09:58:37.498  5476  5524 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-23 09:58:37.498  5476  5524 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-23 09:58:37.500  5476  5524 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4c5399d Bundle[{}]
11-23 09:58:37.501  5476  5524 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-23 09:58:37.501  5476  5524 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-23 09:58:37.502  5476  5524 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-23 09:58:37.502  5476  5524 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-23 09:58:37.503  5476  5524 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-23 09:58:37.504  5476  5524 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-23 09:58:37.506   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-23 09:58:37.507  3710  3710 D SystemUpdateService: onDestroy
,11-23 09:58:37.510  5476  5524 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
11-23 09:58:37.511  5476  5524 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-23 09:58:37.511  5476  5524 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-23 09:58:37.513  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 09:58:37.513  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca5a05e added. We now have 3 listener(s)
,11-23 09:58:37.515  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 09:58:37.515  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:58:37.515  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 09:58:37.515  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:58:37.515  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@161c3f added. We now have 4 listener(s)
11-23 09:58:37.515  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:58:37.516  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 09:58:37.517  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 09:58:37.517  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf690c added. We now have 4 listener(s)
,11-23 09:58:37.519  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 09:58:37.519  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:58:37.519  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 09:58:37.519  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:58:37.519  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c99255 added. We now have 5 listener(s)
11-23 09:58:37.519  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:58:37.519  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:58:37.520  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:58:37.520  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:58:37.520  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:58:37.520  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 09:58:37.520  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 09:58:37.520  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca5a05e removed from the list
11-23 09:58:37.520  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.520  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@161c3f removed from the list
11-23 09:58:37.520  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:58:37.520  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.520  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:58:37.522  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:58:37.522  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.522  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.522  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:58:37.522  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:58:37.522  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.522  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@161c3f not in the list
11-23 09:58:37.522  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.522  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.524  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.524  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.524  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.524  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:58:37.524  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 09:58:37.524  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.524  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c99255 removed from the list
11-23 09:58:37.524  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:58:37.524  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:58:37.524  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 09:58:37.524  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf690c removed from the list
11-23 09:58:37.525  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 09:58:37.525  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e27646a added. We now have 3 listener(s)
,11-23 09:58:37.527  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 09:58:37.527  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:58:37.527  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 09:58:37.527  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:58:37.527  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5a3d5b added. We now have 4 listener(s)
11-23 09:58:37.527  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:58:37.528  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 09:58:37.529  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 09:58:37.529  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38009f8 added. We now have 4 listener(s)
,11-23 09:58:37.530  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 09:58:37.530  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:58:37.531  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 09:58:37.531  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:58:37.531  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5dfed1 added. We now have 5 listener(s)
11-23 09:58:37.531  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:58:37.531  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 09:58:37.531  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 09:58:37.531  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 09:58:37.531  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 09:58:37.531  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 09:58:37.532  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 09:58:37.534  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 09:58:37.535  5476  5524 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 09:58:37.535  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 09:58:37.538  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:58:37.538  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 09:58:37.538  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 09:58:37.538  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 09:58:37.538  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 09:58:37.541  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.541  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 09:58:37.541  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 09:58:37.541  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 09:58:37.541  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 09:58:37.541  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.542  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:58:37.544  5698  5727 D BtGatt.GattService: registerClient() - UUID=bc7de167-a43f-449f-a848-6cf8aa767908
,11-23 09:58:37.544  5698  5714 D BtGatt.GattService: onClientRegistered() - UUID=bc7de167-a43f-449f-a848-6cf8aa767908, clientIf=5
11-23 09:58:37.545  5476  5487 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 09:58:37.545  5698  5708 D BtGatt.GattService: start scan with filters
,11-23 09:58:37.548  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 09:58:37.548  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.548  5698  5717 D BtGatt.ScanManager: handling starting scan
11-23 09:58:37.548  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 09:58:37.548  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.548  5476  5476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 09:58:37.548  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.548  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 09:58:37.549  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 09:58:37.549  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.549  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.548  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 09:58:37.549  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.549  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.550  5698  5717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c18ff86
11-23 09:58:37.550  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 09:58:37.551  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:58:37.553  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:58:37.553  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 09:58:37.553  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.553  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.553  5476  5524 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 09:58:37.553  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 09:58:37.553  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 09:58:37.553  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:58:37.553  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 09:58:37.553  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:58:37.553  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 09:58:37.554  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 09:58:37.554  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.554  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 09:58:37.554  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 09:58:37.554  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.554  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.554  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.554  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 09:58:37.554  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.555  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:58:37.555  5698  5727 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 09:58:37.555  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 09:58:37.556  5476  5524 D BluetoothAdapter: STATE_ON
,11-23 09:58:37.556  5698  5709 D BtGatt.GattService: stopScan() - queue size =1
11-23 09:58:37.557  5698  5714 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 09:58:37.557  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.557  5698  5734 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 09:58:37.557  5698  5717 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 09:58:37.558  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-23 09:58:37.558  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.558  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 09:58:37.558  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.558  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.558  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.558  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.558  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 09:58:37.558  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.558  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.558  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:58:37.558  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 09:58:37.558  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 09:58:37.559  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 09:58:37.559  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:58:37.560  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.560  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:58:37.560  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.560  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.560  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.562  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.562  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.562  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.562  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 09:58:37.562  5698  5714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-23 09:58:37.562  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.562  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:58:37.562  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:58:37.562  5476  5476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 09:58:37.562  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.562  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 09:58:37.563  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 09:58:37.563  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.563  5698  5717 D BtGatt.ScanManager: Starting BLE batch scan
11-23 09:58:37.563  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.563  5698  5717 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 09:58:37.563  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-23 09:58:37.563  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:58:37.563  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:58:37.563  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.563  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:58:37.563  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.563  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:58:37.563  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:58:37.563  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:58:37.563  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 09:58:37.563  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e27646a removed from the list
11-23 09:58:37.563  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.563  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5a3d5b removed from the list
11-23 09:58:37.563  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:58:37.563  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.563  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.564  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.564  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.564  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.565  4870  5772 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-23 09:58:37.566  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.566  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.566  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.567  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:58:37.567  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:58:37.567  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.567  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5a3d5b not in the list
11-23 09:58:37.567  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.567  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateSta,te: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.568  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.568  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.568  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.568  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:58:37.568  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:58:37.568  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.568  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5dfed1 removed from the list
11-23 09:58:37.568  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:58:37.568  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:58:37.568  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 09:58:37.568  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38009f8 removed from the list
11-23 09:58:37.569  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 09:58:37.569  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62c16c2 added. We now have 3 listener(s)
11-23 09:58:37.570  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 09:58:37.570  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:58:37.570  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 09:58:37.570  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:58:37.570  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc0fcd3 added. We now have 4 listener(s)
11-23 09:58:37.570  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:58:37.570  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 09:58:37.571  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 09:58:37.571  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c662010 added. We now have 4 listener(s)
11-23 09:58:37.571  5698  5714 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 09:58:37.571  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.572  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 09:58:37.572  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothCon,nector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:58:37.572  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 09:58:37.572  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:58:37.572  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a0b709 added. We now have 5 listener(s)
11-23 09:58:37.572  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:58:37.572  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 09:58:37.573  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 09:58:37.573  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 09:58:37.573  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 09:58:37.573  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 09:58:37.573  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 09:58:37.574  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 09:58:37.576  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 09:58:37.576  5698  5714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 09:58:37.576  5476  5524 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 09:58:37.576  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 09:58:37.576  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.578  5698  5717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 09:58:37.578  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.578  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 09:58:37.578  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 09:58:37.579  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 09:58:37.579  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 09:58:37.582  5698  5714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 09:58:37.582  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.583  5698  5714 E BtGatt.ContextMap: Context not found for ID 5
11-23 09:58:37.583  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.583  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 09:58:37.583  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 09:58:37.583  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 09:58:37.583  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 09:58:37.583  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.584  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:58:37.587  5698  5708 D BtGatt.GattService: registerClient() - UUID=06f47f3a-2c69-420d-8b86-e15ea827851a
11-23 09:58:37.587  5698  5714 D BtGatt.GattService: onClientRegistered() - UUID=06f47f3a-2c69-420d-8b86-e15ea827851a, clientIf=5
11-23 09:58:37.587  5476  5487 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 09:58:37.588  5698  5709 D BtGatt.GattService: start scan with filters
11-23 09:58:37.589  5698  5714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 09:58:37.589  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.589  5698  5717 D BtGatt.ScanManager: stopping BLe Batch
11-23 09:58:37.590  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 09:58:37.590  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.590  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 09:58:37.591  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.591  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 09:58:37.591  5476  5476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 09:58:37.591  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.591  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 09:58:37.591  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 09:58:37.591  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.591  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.591  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.591  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.592  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 09:58:37.592  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.594  5698  5714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 09:58:37.594  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.594  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.594  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 09:58:37.594  5698  5717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 09:58:37.594  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.594  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.594  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 09:58:37.594  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.594  5476  5524 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-23 09:58:37.594  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:58:37.594  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:58:37.594  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:58:37.595  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:58:37.595  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:58:37.595  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 09:58:37.595  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:58:37.595  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 09:58:37.595  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62c16c2 removed from the list
11-23 09:58:37.595  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.595  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc0fcd3 removed from the list
11-23 09:58:37.595  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:58:37.595  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:58:37.595  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 09:58:37.595  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.595  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 09:58:37.595  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 09:58:37.595  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:58:37.595  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 09:58:37.595  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.597  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.597  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.597  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.597  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.597  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.597  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:58:37.597  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.597  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:58:37.597  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.597  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 09:58:37.597  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc0fcd3 not in the list
11-23 09:58:37.597  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 09:58:37.597  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.597  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 09:58:37.597  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 09:58:37.597  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.597  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.597  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.597  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 09:58:37.597  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.598  5698  5714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 09:58:37.598  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.598  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:58:37.599  5698  5734 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 09:58:37.599  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 09:58:37.599  5698  5717 D BtGatt.ScanManager: handling starting scan
11-23 09:58:37.600  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:58:37.600  5698  5727 D BtGatt.GattService: stopScan() - queue size =1
11-23 09:58:37.600  5698  5708 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 09:58:37.600  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 09:58:37.601  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.601  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 09:58:37.601  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.601  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.601  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.601  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.601  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 09:58:37.601  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.601  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.601  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.601  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 09:58:37.601  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 09:58:37.602  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 09:58:37.602  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.603  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.603  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:58:37.603  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.603  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.603  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:58:37.603  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:58:37.603  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.603  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:58:37.603  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a0b709 removed from the list
11-23 09:58:37.603  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:58:37.603  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:58:37.603  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:58:37.603  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 09:58:37.603  5476  5476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 09:58:37.603  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c662010 removed from the list
11-23 09:58:37.603  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.604  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 09:58:37.604  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 09:58:37.604  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.604  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.604  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.604  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 09:58:37.604  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:58:37.604  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@419bc1a added. We now have 3 listener(s)
11-23 09:58:37.604  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.604  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.604  5698  5714 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 09:58:37.604  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.604  5698  5717 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 09:58:37.605  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 09:58:37.605  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:58:37.605  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 09:58:37.605  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:58:37.605  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c61334b added. We now have 4 listener(s)
11-23 09:58:37.605  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.605  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:58:37.605  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.605  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.605  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 09:58:37.606  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 09:58:37.606  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a05e128 added. We now have 4 listener(s)
11-23 09:58:37.607  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 09:58:37.607  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:58:37.607  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 09:58:37.607  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:58:37.607  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0b3e41 added. We now have 5 listener(s)
11-23 09:58:37.607  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:58:37.607  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 09:58:37.607  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 09:58:37.607  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 09:58:37.607  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 09:58:37.607  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 09:58:37.608  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 09:58:37.608  5698  5714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 09:58:37.609  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.609  5698  5717 D BtGatt.ScanManager: Starting BLE batch scan
11-23 09:58:37.609  5698  5717 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 09:58:37.610  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 09:58:37.610  5476  5524 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 09:58:37.610  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 09:58:37.612  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.612  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 09:58:37.612  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 09:58:37.612  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 09:58:37.612  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 09:58:37.616  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.616  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 09:58:37.616  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 09:58:37.616  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 09:58:37.616  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 09:58:37.616  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.617  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:58:37.617  5698  5714 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 09:58:37.617  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.618  5698  5709 D BtGatt.GattService: registerClient() - UUID=9a8e1814-7a71-45c5-a3c0-6cbf63509943
11-23 09:58:37.618  5698  5714 D BtGatt.GattService: onClientRegistered() - UUID=9a8e1814-7a71-45c5-a3c0-6cbf63509943, clientIf=5
11-23 09:58:37.619  5476  5487 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 09:58:37.619  5698  5708 D BtGatt.GattService: start scan with filters
11-23 09:58:37.621  5698  5714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 09:58:37.621  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.622  5698  5717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 09:58:37.622  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 09:58:37.622  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.622  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 09:58:37.622  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.623  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 09:58:37.623  5476  5476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 09:58:37.623  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.623  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 09:58:37.623  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 09:58:37.623  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.623  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.623  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.623  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.623  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 09:58:37.623  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.626  5698  5714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 09:58:37.626  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.627  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.627  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 09:58:37.628  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.628  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.628  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.631  5698  5714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 09:58:37.631  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.631  5698  5717 D BtGatt.ScanManager: stopping BLe Batch
11-23 09:58:37.631  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:58:37.631  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:58:37.632  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:58:37.632  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:58:37.632  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:58:37.632  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 09:58:37.632  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:58:37.632  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 09:58:37.632  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@419bc1a removed from the list
11-23 09:58:37.632  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.632  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c61334b removed from the list
11-23 09:58:37.632  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
11-23 09:58:37.632  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.632  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:58:37.632  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.632  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 09:58:37.632  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.632  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.632  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 09:58:37.632  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.633  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 09:58:37.633  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 09:58:37.633  5476  5524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 09:58:37.633  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 09:58:37.633  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.636  5698  5714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 09:58:37.636  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.636  5698  5717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 09:58:37.636  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.636  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.636  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.636  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:58:37.636  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:58:37.637  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.637  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c61334b not in the list
11-23 09:58:37.637  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 09:58:37.637  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.637  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 09:58:37.637  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 09:58:37.637  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.637  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.637  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.637  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 09:58:37.637  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.638  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:58:37.638  5698  5708 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 09:58:37.638  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 09:58:37.639  5476  5524 D BluetoothAdapter: STATE_ON
11-23 09:58:37.640  5698  5709 D BtGatt.GattService: stopScan() - queue size =0
11-23 09:58:37.640  5698  5714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 09:58:37.640  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.640  5698  5734 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 09:58:37.641  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 09:58:37.641  5698  5717 D BtGatt.ScanManager: handling starting scan
11-23 09:58:37.641  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.641  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 09:58:37.641  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.641  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.641  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.641  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.642  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 09:58:37.642  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.642  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.642  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.642  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 09:58:37.642  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 09:58:37.642  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 09:58:37.643  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.644  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.644  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:58:37.644  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.644  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.644  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:58:37.645  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:58:37.645  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.645  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:58:37.645  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0b3e41 removed from the list
11-23 09:58:37.645  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:58:37.645  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 09:58:37.645  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:58:37.645  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 09:58:37.645  5476  5476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 09:58:37.645  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.645  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a05e128 removed from the list
11-23 09:58:37.645  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 09:58:37.645  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 09:58:37.645  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.645  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.645  5476  5476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.645  5698  5714 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 09:58:37.645  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.645  5476  5476 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 09:58:37.645  5476  5476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.645  5698  5717 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 09:58:37.645  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.645  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 09:58:37.645  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bbb472 added. We now have 3 listener(s)
11-23 09:58:37.646  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.646  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.646  5476  5476 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 09:58:37.647  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 09:58:37.647  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:58:37.647  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 09:58:37.647  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:58:37.647  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e12c0c3 added. We now have 4 listener(s)
11-23 09:58:37.648  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:58:37.648  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 09:58:37.650  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 09:58:37.650  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e89ad40 added. We now have 4 listener(s)
11-23 09:58:37.650  5698  5714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 09:58:37.650  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.650  5698  5717 D BtGatt.ScanManager: Starting BLE batch scan
11-23 09:58:37.650  5698  5717 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 09:58:37.651  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 09:58:37.651  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 09:58:37.651  5476  5524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 09:58:37.651  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 09:58:37.651  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e87479 added. We now have 5 listener(s)
11-23 09:58:37.651  5476  5524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 09:58:37.652  5476  5524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 09:58:37.652  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:58:37.652  5476  5524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 09:58:37.652  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:58:37.652  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:58:37.652  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 09:58:37.652  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bbb472 removed from the list
11-23 09:58:37.652  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.652  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e12c0c3 removed from the list
11-23 09:58:37.652  5476  5524 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 09:58:37.652  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 09:58:37.652  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.653  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.653  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.654  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.654  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:58:37.654  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:58:37.654  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.654  5476  5524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e12c0c3 not in the list
11-23 09:58:37.654  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.654  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.655  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.655  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.655  5476  5524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 09:58:37.655  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 09:58:37.655  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 09:58:37.655  5476  5524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 09:58:37.655  5476  5524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e87479 removed from the list
11-23 09:58:37.655  5476  5524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 09:58:37.655  5476  5524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 09:58:37.655  5476  5524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 09:58:37.656  5476  5524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e89ad40 removed from the list
,11-23 09:58:37.656  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-23 09:58:37.656  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-23 09:58:37.656  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-23 09:58:37.656  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 09:58:37.657  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-23 09:58:37.657  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 09:58:37.658  5698  5714 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 09:58:37.658  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:58:37.662  5698  5714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 09:58:37.662  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:58:37.663  5698  5717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 09:58:37.667  5698  5714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 09:58:37.667  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:58:37.668  5698  5714 E BtGatt.ContextMap: Context not found for ID 5
,11-23 09:58:37.673  5698  5714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 09:58:37.673  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.673  5698  5717 D BtGatt.ScanManager: stopping BLe Batch
,11-23 09:58:37.676  5698  5714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 09:58:37.677  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 09:58:37.677  5698  5717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 09:58:37.681  5698  5714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 09:58:37.681  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 09:58:38.064  5476  5476 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 09:58:38.105  5476  5476 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 09:58:38.146  5476  5476 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 09:58:39.806  5476  5780 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 09:58:39.806  5476  5780 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 09:58:40.124   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 09:58:40.595  5476  5780 W !!      : call onHalfStreamCopied
,11-23 09:58:40.595  5476  5780 I testCopyDataAndClose: closing input stream
,11-23 09:58:41.365  5476  5780 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 09:58:41.365  5476  5780 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 09:58:41.366  5476  5780 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 09:58:41.366  5476  5780 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 09:58:41.366  5476  5780 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 09:58:41.366  5476  5780 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 09:58:41.366  5476  5780 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-23 09:58:41.366  5476  5780 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 09:58:41.366  5476  5780 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 09:58:41.366  5476  5780 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 09:58:41.366  5476  5780 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 09:58:43.148   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 09:58:45.334   928  2811 D ConnectivityService: handlePromptUnvalidated 102
,11-23 09:58:46.057  5476  5781 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-23 09:58:46.057  5476  5781 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 09:58:48.056  5476  5524 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
11-23 09:58:48.056  5476  5524 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 09:58:48.057  5476  5524 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,11-23 09:58:48.108  5476  5781 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
11-23 09:58:48.108  5476  5781 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-23 09:58:48.108  5476  5781 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,11-23 09:58:48.197  5476  5782 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 09:58:48.197  5476  5782 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 09:58:48.480   928  2809 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 16, 17 -> obsolete
,11-23 09:58:49.828  5476  5782 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 09:58:49.828  5476  5782 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 09:58:49.828  5476  5782 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 09:58:49.828  5476  5782 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 09:58:49.828  5476  5782 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-23 09:58:49.828  5476  5782 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 09:58:49.828  5476  5782 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-23 09:58:49.828  5476  5782 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 09:58:49.828  5476  5782 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 09:58:49.828  5476  5782 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 09:58:49.828  5476  5782 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 09:58:54.493  5476  5783 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-23 09:58:54.493  5476  5783 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 09:58:54.494  5476  5783 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
11-23 09:58:54.494  5476  5783 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 09:58:54.494  5476  5783 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 09:58:54.494  5476  5783 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 09:58:54.494  5476  5783 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-23 09:58:54.494  5476  5783 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 09:58:54.494  5476  5783 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 09:58:54.494  5476  5783 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 09:58:54.494  5476  5783 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 09:58:54.495  5476  5783 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-23 09:58:54.495  5476  5783 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-23 09:58:54.496  5476  5524 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-23 09:58:54.499  5476  5784 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-23 09:58:54.499  5476  5784 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 09:58:54.499  5476  5784 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
,11-23 09:58:54.500  5476  5784 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-23 09:58:54.500  5476  5784 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-23 09:58:54.500  5476  5784 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-23 09:58:54.500  5476  5784 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-23 09:58:54.500  5476  5784 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-23 09:58:54.503  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-23 09:58:54.503  5476  5524 I jxcore-log: 
,11-23 09:58:54.503  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-23 09:58:54.503  5476  5524 I jxcore-log: 
11-23 09:58:54.503  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-23 09:58:54.503  5476  5524 I jxcore-log: 
11-23 09:58:54.504  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-23 09:58:54.504  5476  5524 I jxcore-log: 
,11-23 09:58:54.504  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG UnitTest_app: 'Total duration:  92543'
11-23 09:58:54.504  5476  5524 I jxcore-log: 
,11-23 09:58:54.506  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-23 09:58:54.506  5476  5524 I jxcore-log: 
11-23 09:58:54.509  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 09:58:54.509  5476  5524 I jxcore-log: 
,11-23 09:58:54.510  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 09:58:54.510  5476  5524 I jxcore-log: 
11-23 09:58:54.510  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 09:58:54.510  5476  5524 I jxcore-log: 
11-23 09:58:54.511  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 09:58:54.511  5476  5524 I jxcore-log: 
11-23 09:58:54.511  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 09:58:54.511  5476  5524 I jxcore-log: 
11-23 09:58:54.511  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 09:58:54.511  5476  5524 I jxcore-log: 
,11-23 09:58:54.512  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 09:58:54.512  5476  5524 I jxcore-log: 
11-23 09:58:54.512  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 09:58:54.512  5476  5524 I jxcore-log: 
11-23 09:58:54.512  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 09:58:54.512  5476  5524 I jxcore-log: 
11-23 09:58:54.513  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 09:58:54.513  5476  5524 I jxcore-log: 
11-23 09:58:54.513  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 09:58:54.513  5476  5524 I jxcore-log: 
11-23 09:58:54.513  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 09:58:54.513  5476  5524 I jxcore-log: 
11-23 09:58:54.513  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 09:58:54.513  5476  5524 I jxcore-log: 
11-23 09:58:54.513  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 09:58:54.513  5476  5524 I jxcore-log: 
11-23 09:58:54.514  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 09:58:54.514  5476  5524 I jxcore-log: 
11-23 09:58:54.514  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 09:58:54.514  5476  5524 I jxcore-log: 
11-23 09:58:54.514  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 09:58:54.514  5476  5524 I jxcore-log: 
,11-23 09:58:54.514  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 09:58:54.514  5476  5524 I jxcore-log: 
11-23 09:58:54.515  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 09:58:54.515  5476  5524 I jxcore-log: 
11-23 09:58:54.515  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 09:58:54.515  5476  5524 I jxcore-log: 
11-23 09:58:54.515  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 09:58:54.515  5476  5524 I jxcore-log: 
11-23 09:58:54.515  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 09:58:54.515  5476  5524 I jxcore-log: 
,11-23 09:58:54.516  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 09:58:54.516  5476  5524 I jxcore-log: 
11-23 09:58:54.516  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 09:58:54.516  5476  5524 I jxcore-log: 
,11-23 09:58:54.518  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 09:58:54.518  5476  5524 I jxcore-log: 
11-23 09:58:54.518  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 09:58:54.518  5476  5524 I jxcore-log: 
11-23 09:58:54.518  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 09:58:54.518  5476  5524 I jxcore-log: 
11-23 09:58:54.518  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 09:58:54.518  5476  5524 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-23 09:58:54.519  5476  5524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 09:58:54.519  5476  5524 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-23 09:58:54.519  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 09:58:54.519  5476  5524 I jxcore-log: 
11-23 09:58:54.519  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 09:58:54.519  5476  5524 I jxcore-log: 
11-23 09:58:54.519  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 09:58:54.519  5476  5524 I jxcore-log: 
11-23 09:58:54.519  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 09:58:54.519  5476  5524 I jxcore-log: 
11-23 09:58:54.520  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 09:58:54.520  5476  5524 I jxcore-log: 
11-23 09:58:54.520  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 09:58:54.520  5476  5524 I jxcore-log: 
,11-23 09:58:54.525  5476  5476 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-23 09:58:54.526  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-23 09:58:54.526  5476  5524 I jxcore-log: 
11-23 09:58:54.526  5476  5524 I jxcore-log: 2016-11-23 08:58:54 - WARN testUtils: 'myNameCallback not set!'
11-23 09:58:54.526  5476  5524 I jxcore-log: 
,11-23 09:58:55.235   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 09:58:56.598  5476  5524 I jxcore-log: 2016-11-23 08:58:56 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-23 09:58:56.598  5476  5524 I jxcore-log: 
,11-23 09:58:56.599  5476  5524 I jxcore-log: 2016-11-23 08:58:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-23 09:58:56.599  5476  5524 I jxcore-log: 
,11-23 09:58:56.957  5476  5524 I jxcore-log: 2016-11-23 08:58:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-23 09:58:56.957  5476  5524 I jxcore-log: 
,11-23 09:58:56.968  5476  5524 I jxcore-log: 2016-11-23 08:58:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-23 09:58:56.968  5476  5524 I jxcore-log: 
,11-23 09:58:57.089   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:58.090  5476  5524 I jxcore-log: 2016-11-23 08:58:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-23 09:58:58.090  5476  5524 I jxcore-log: 
11-23 09:58:58.090   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:58.259   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 09:58:58.282  5476  5524 I jxcore-log: 2016-11-23 08:58:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-23 09:58:58.282  5476  5524 I jxcore-log: 
,11-23 09:58:58.287  5476  5524 I jxcore-log: 2016-11-23 08:58:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-23 09:58:58.287  5476  5524 I jxcore-log: 
,11-23 09:58:58.292  5476  5524 I jxcore-log: 2016-11-23 08:58:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-23 09:58:58.292  5476  5524 I jxcore-log: 
,11-23 09:58:58.774  5476  5524 I jxcore-log: 2016-11-23 08:58:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-23 09:58:58.774  5476  5524 I jxcore-log: 
,11-23 09:58:58.819  5476  5524 I jxcore-log: 2016-11-23 08:58:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-23 09:58:58.819  5476  5524 I jxcore-log: 
,11-23 09:58:58.833  5476  5524 I jxcore-log: 2016-11-23 08:58:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-23 09:58:58.833  5476  5524 I jxcore-log: 
,11-23 09:58:58.837  5476  5524 I jxcore-log: 2016-11-23 08:58:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-23 09:58:58.837  5476  5524 I jxcore-log: 
,11-23 09:58:59.091   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:58:59.109  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-23 09:58:59.109  5476  5524 I jxcore-log: 
,11-23 09:58:59.237  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-23 09:58:59.237  5476  5524 I jxcore-log: 
,11-23 09:58:59.610  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-23 09:58:59.610  5476  5524 I jxcore-log: 
,11-23 09:58:59.618  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-23 09:58:59.618  5476  5524 I jxcore-log: 
,11-23 09:58:59.622  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-23 09:58:59.622  5476  5524 I jxcore-log: 
,11-23 09:58:59.627  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-23 09:58:59.627  5476  5524 I jxcore-log: 
,11-23 09:58:59.632  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-23 09:58:59.632  5476  5524 I jxcore-log: 
,11-23 09:58:59.660  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-23 09:58:59.660  5476  5524 I jxcore-log: 
,11-23 09:58:59.697  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-23 09:58:59.697  5476  5524 I jxcore-log: 
,11-23 09:58:59.704  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-23 09:58:59.704  5476  5524 I jxcore-log: 
,11-23 09:58:59.711  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-23 09:58:59.711  5476  5524 I jxcore-log: 
,11-23 09:58:59.726  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-23 09:58:59.726  5476  5524 I jxcore-log: 
,11-23 09:58:59.742  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-23 09:58:59.742  5476  5524 I jxcore-log: 
,11-23 09:58:59.748  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-23 09:58:59.748  5476  5524 I jxcore-log: 
,11-23 09:58:59.754  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-23 09:58:59.754  5476  5524 I jxcore-log: 
,11-23 09:58:59.767  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-23 09:58:59.767  5476  5524 I jxcore-log: 
,11-23 09:58:59.785  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-23 09:58:59.785  5476  5524 I jxcore-log: 
,11-23 09:58:59.799  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-23 09:58:59.799  5476  5524 I jxcore-log: 
,11-23 09:58:59.810  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-23 09:58:59.810  5476  5524 I jxcore-log: 
,11-23 09:58:59.823  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-23 09:58:59.823  5476  5524 I jxcore-log: 
,11-23 09:58:59.833  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-23 09:58:59.833  5476  5524 I jxcore-log: 
,11-23 09:58:59.846  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-23 09:58:59.846  5476  5524 I jxcore-log: 
,11-23 09:58:59.856  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-23 09:58:59.856  5476  5524 I jxcore-log: 
,11-23 09:58:59.863  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-23 09:58:59.863  5476  5524 I jxcore-log: 
,11-23 09:58:59.885  5476  5524 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-23 09:58:59.886  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO testUtils: 'BLE multiple advertisement supported'
11-23 09:58:59.886  5476  5524 I jxcore-log: 
,11-23 09:58:59.920  5476  5524 I jxcore-log: 2016-11-23 08:58:59 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-23 09:58:59.920  5476  5524 I jxcore-log: 
,11-23 09:59:00.092   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:59:00.215  5476  5524 I jxcore-log: 2016-11-23 08:59:00 - DEBUG CoordinatedClient: 'connected to the test server'
11-23 09:59:00.215  5476  5524 I jxcore-log: 
,11-23 09:59:01.093   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:59:02.093   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 09:59:07.327   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 09:59:10.362   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 09:59:17.315   928  2809 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 09:59:27.094   533   533 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 09:59:27.095   533   533 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 09:59:41.184  5751  5751 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 09:59:42.096   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:59:43.097   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:59:44.098   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:59:45.099   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:59:46.101   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:59:47.101   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 09:59:52.102   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:59:53.104   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:59:54.105   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:59:55.106   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:59:55.747   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 09:59:56.108   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 09:59:57.108   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 09:59:57.319   928  2809 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 09:59:58.791   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:00:02.143   928  3002 I ActivityManager: Start proc 5794:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-23 10:00:02.177  5794  5794 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-23 10:00:02.261  5794  5806 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-23 10:00:02.362  5794  5806 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...,
,11-23 10:00:02.394  5794  5806 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-23 10:00:02.402  5819  5819 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads675014426.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads675014426.dex
,11-23 10:00:02.422  5794  5794 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-23 10:00:02.434  5819  5819 I dex2oat : dex2oat took 33.014ms (threads: 2) arena alloc=200KB java alloc=37KB native alloc=1258KB free=1045KB
,11-23 10:00:02.562  5794  5794 W InstanceID/Rpc: Found 10012
,11-23 10:00:02.608   928  3277 I ActivityManager: Killing 3767:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-23 10:00:07.110   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:08.111   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:09.112   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:10.114   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:11.115   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:12.116   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 10:00:16.965   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:00:17.320   928  2809 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 10:00:20.004   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:00:23.037   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:00:26.068   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:00:27.117   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:28.118   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:29.119   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:30.121   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:31.122   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:32.123   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 10:00:35.156   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:00:38.172   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:00:41.059  5751  5751 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 10:00:52.124   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:53.126   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:54.127   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:55.128   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:56.129   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:00:57.130   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 10:00:57.324   928  2809 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 10:01:11.433   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:01:14.471   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:01:17.328   928  2809 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 10:01:22.131   533   533 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 10:01:22.131   533   533 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 10:01:26.576   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:01:29.609   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:01:37.328   928  2809 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 10:01:42.132   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:01:43.134   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:01:44.136   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:01:44.759   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:01:45.137   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:01:46.138   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:01:47.139   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 10:01:47.794   928  2811 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 10:01:52.141   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:01:53.142   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:01:54.144   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:01:55.146   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:01:56.147   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 10:01:57.148   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 10:02:00.952  5476  5524 I jxcore-log: 2016-11-23 09:02:00 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-23 10:02:00.952  5476  5524 I jxcore-log: 
,11-23 10:02:01.132  5476  5524 I jxcore-log: 2016-11-23 09:02:01 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 10:02:01.132  5476  5524 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 10:02:01.132  5476  5524 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 10:02:01.132  5476  5524 I jxcore-log: emit@events.js:82:1
11-23 10:02:01.132  5476  5524 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 10:02:01.132  5476  5524 I jxcore-log: emit@events.js:82:1''
11-23 10:02:01.132  5476  5524 I jxcore-log: 
,11-23 10:02:01.133  5476  5524 I jxcore-log: 2016-11-23 09:02:01 - DEBUG CoordinatedClient: 'test client failed'
11-23 10:02:01.133  5476  5524 I jxcore-log: 
,11-23 10:02:01.142  5476  5524 I jxcore-log: 2016-11-23 09:02:01 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 10:02:01.142  5476  5524 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 10:02:01.142  5476  5524 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 10:02:01.142  5476  5524 I jxcore-log: emit@events.js:82:1
11-23 10:02:01.142  5476  5524 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 10:02:01.142  5476  5524 I jxcore-log: emit@events.js:82:1''
11-23 10:02:01.142  5476  5524 I jxcore-log: 
,11-23 10:02:01.145  5476  5524 I jxcore-log: 2016-11-23 09:02:01 - DEBUG CoordinatedClient: 'test client failed'
11-23 10:02:01.145  5476  5524 I jxcore-log: 
,11-23 10:02:01.149  5476  5524 I jxcore-log: 2016-11-23 09:02:01 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 10:02:01.149  5476  5524 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 10:02:01.149  5476  5524 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 10:02:01.149  5476  5524 I jxcore-log: emit@events.js:82:1
11-23 10:02:01.149  5476  5524 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 10:02:01.149  5476  5524 I jxcore-log: emit@events.js:82:1''
11-23 10:02:01.149  5476  5524 I jxcore-log: 
,11-23 10:02:01.150  5476  5524 I jxcore-log: 2016-11-23 09:02:01 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-23 10:02:01.150  5476  5524 I jxcore-log: 
,11-23 10:02:01.702  5878  5878 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-23 10:02:01.707  5878  5878 D AndroidRuntime: CheckJNI is OFF
,11-23 10:02:01.738  5878  5878 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-23 10:02:01.774  5878  5878 I Radio-JNI: register_android_hardware_Radio DONE
,11-23 10:02:01.790  5878  5878 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-23 10:02:01.803   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-23 10:02:01.804   928   941 I ActivityManager: Killing 5476:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-23 10:02:01.909   928  3642 D GraphicsStats: Buffer count: 2
11-23 10:02:01.909   928  3277 I WindowState: WIN DEATH: Window{e0b8076 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-23 10:02:01.910   928  2810 D WifiService: Client connection lost with reason: 4
,11-23 10:02:01.923   928   941 W ActivityManager: Force removing ActivityRecord{e6263e u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-23 10:02:01.947   928   951 I art     : Starting a blocking GC Explicit
,11-23 10:02:01.952   928  3276 W ActivityManager: Spurious death for ProcessRecord{1532764 0:com.test.thalitest/u0a77}, curProc for 5476: null
,11-23 10:02:01.983  3597  3597 W Binder_7: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[29000]" dev="sockfs" ino=29000 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 10:02:01.986  3597  3597 W Binder_7: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[29000]" dev="sockfs" ino=29000 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 10:02:01.985   928  3597 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5476 uid 10077
11-23 10:02:01.987  3526  3526 I Keyboard.Facilitator: onFinishInput()
,11-23 10:02:02.011  3827  3827 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,11-23 10:02:02.047   928   951 I art     : Explicit concurrent mark sweep GC freed 108593(7MB) AllocSpace objects, 60(1768KB) LOS objects, 33% free, 29MB/44MB, paused 1.992ms total 100.102ms
,11-23 10:02:02.069  3827  5890 I MicroRecognitionRnrImpl: Starting detection.
,11-23 10:02:02.070  3827  5891 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@d499ef1
,11-23 10:02:02.070   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
11-23 10:02:02.072   510  5894 I AudioFlinger: AudioFlinger's thread 0xf2280000 ready to run
11-23 10:02:02.072  5878  5878 I art     : System.exit called, status: 0
11-23 10:02:02.072  5878  5878 I AndroidRuntime: VM exiting with result code 0.
,11-23 10:02:02.079   510  2857 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-23 10:02:02.081  3827  5891 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@d499ef1
,11-23 10:02:02.090   928   951 I ActivityManager: Start proc 5895:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-23 10:02:02.090   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
11-23 10:02:02.091   510  5894 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-23 10:02:02.091   510  5894 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-23 10:02:02.091   510  5894 I ACDB-LOADER: ACDB AFE returned = -19
,11-23 10:02:02.091   510  5894 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-23 10:02:02.091   510  5894 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-23 10:02:02.091   510  5894 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-23 10:02:02.100  5698  5698 D BluetoothMapAppObserver: onReceive
,11-23 10:02:02.100   510  5894 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-23 10:02:02.101  5698  5698 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-23 10:02:02.109   928  2801 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-23 10:02:02.111  3526  3526 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-23 10:02:02.112  3929  4016 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-23 10:02:02.132  3526  5907 I Keyboard.Facilitator.DecoderInitializer: run()
,11-23 10:02:02.142  3526  5907 I Decoder : createOrResetDecoder
,11-23 10:02:02.178  3618  3618 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
11-23 10:02:02.179   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-23 10:02:02.189  3827  3827 I HotwordWorkerImpl: onReady
,11-23 10:02:02.193  3437  3437 I ConfigService: onCreate
,11-23 10:02:02.193    17    17 W kworker/2:0: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 10:02:02.196    17    17 W kworker/2:0: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 10:02:02.205  3638  3798 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-23 10:02:02.213    17    17 W kworker/2:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 10:02:02.219  3260  5913 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-23 10:02:02.221   928  3597 I ActivityManager: Start proc 5917:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
11-23 10:02:02.222  3638  3798 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-23 10:02:02.222  3638  3798 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3638
11-23 10:02:02.222  3638  3798 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 10:02:02.222  3638  3798 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 10:02:02.222  3638  3798 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 10:02:02.222  3638  3798 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 10:02:02.222  3638  3798 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 10:02:02.222  3638  3798 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 10:02:02.222  3638  3798 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-23 10:02:02.222  3638  3798 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-23 10:02:02.222  3638  3798 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-23 10:02:02.222  3638  3798 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-23 10:02:02.222  3638  3798 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 10:02:02.222  3638  3798 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 10:02:02.227   928  5927 E DropBoxManagerService: Can't write: system_app_crash
11-23 10:02:02.227   928  5927 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-23 10:02:02.227   928  5927 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 10:02:02.227   928  5927 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 10:02:02.227   928  5927 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 10:02:02.227   928  5927 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 10:02:02.227   928  5927 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 10:02:02.227   928  5927 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 10:02:02.227   928  5927 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 10:02:02.227   928  5927 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 10:02:02.227   928  5927 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 10:02:02.227   928  5927 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 10:02:02.227   928  5927 E DropBoxManagerService: 	... 5 more
,11-23 10:02:02.227   928  3004 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-23 10:02:02.229  3827  3840 W SearchService: Abort, client detached.
,11-23 10:02:02.234  3827  3827 I HotwordDetector: Closing mic
,11-23 10:02:02.234  3827  4030 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d499ef1
11-23 10:02:02.234  3827  5891 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-23 10:02:02.249  5521  5521 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[36100]" dev="sockfs" ino=36100 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 10:02:02.249  5521  5521 W Binder_5: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[36100]" dev="sockfs" ino=36100 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 10:02:02.249  5521  5521 W Binder_5: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[35169]" dev="sockfs" ino=35169 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 10:02:02.249  5521  5521 W Binder_5: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[35169]" dev="sockfs" ino=35169 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 10:02:02.243  3526  5907 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-23 10:02:02.252   928  5930 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 10:02:02.264  3437  3437 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-23 10:02:02.265  3437  3437 D AndroidRuntime: Shutting down VM
11-23 10:02:02.266  3437  3437 E AndroidRuntime: FATAL EXCEPTION: main
11-23 10:02:02.266  3437  3437 E AndroidRuntime: Process: com.google.process.gapps, PID: 3437
11-23 10:02:02.266  3437  3437 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-23 10:02:02.266  3437  3437 E AndroidRuntime: 	... 8 more
,11-23 10:02:02.271   928  5932 E DropBoxManagerService: Can't write: system_app_crash
11-23 10:02:02.271   928  5932 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-23 10:02:02.271   928  5932 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 10:02:02.271   928  5932 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 10:02:02.271   928  5932 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 10:02:02.271   928  5932 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 10:02:02.271   928  5932 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 10:02:02.271   928  5932 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 10:02:02.271   928  5932 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 10:02:02.271   928  5932 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 10:02:02.271   928  5932 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 10:02:02.271   928  5932 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 10:02:02.271   928  5932 E DropBoxManagerService: 	... 5 more
,11-23 10:02:02.291   928  5930 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 10:02:02.291   928  5930 I Adreno  : Build Date                       : 12/06/15
11-23 10:02:02.291   928  5930 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 10:02:02.291   928  5930 I Adreno  : Local Branch                     : mybranch17112971
11-23 10:02:02.291   928  5930 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 10:02:02.291   928  5930 I Adreno  : Remote Branch                    : NONE
11-23 10:02:02.291   928  5930 I Adreno  : Reconstruct Branch               : NOTHING
,11-23 10:02:02.302   928  5930 I OpenGLRenderer: Initialized EGL, version 1.4
,11-23 10:02:02.308  3260  5913 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-23 10:02:02.309  3260  5913 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-23 10:02:02.309  3260  5913 E AndroidRuntime: Process: android.process.acore, PID: 3260
11-23 10:02:02.309  3260  5913 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 10:02:02.309  3260  5913 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 10:02:02.310   510  5894 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-23 10:02:02.311   510  5894 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-23 10:02:02.315   928  5933 E DropBoxManagerService: Can't write: system_app_crash
11-23 10:02:02.315   928  5933 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-23 10:02:02.315   928  5933 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 10:02:02.315   928  5933 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 10:02:02.315   928  5933 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 10:02:02.315   928  5933 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 10:02:02.315   928  5933 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 10:02:02.315   928  5933 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 10:02:02.315   928  5933 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 10:02:02.315   928  5933 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 10:02:02.315   928  5933 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 10:02:02.315   928  5933 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 10:02:02.315   928  5933 E DropBoxManagerService: 	... 5 more
,11-23 10:02:02.316   510  5894 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-23 10:02:02.317   510  5894 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-23 10:02:02.318   510  2857 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-23 10:02:02.321  3827  5890 I MicroRecognitionRnrImpl: Detection finished
,11-23 10:02:02.321  3827  4058 I MicroRecognitionRnrImpl: Stopping hotword detection.

```
