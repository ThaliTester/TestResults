#### Test 93371269c81e6ec_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-18 19:44:35.456  3851  4247 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-18 19:44:35.535  3851  4247 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-18 19:44:35.951  5588  5588 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-18 19:44:35.957  5588  5588 D AndroidRuntime: CheckJNI is OFF
11-18 19:44:35.984  5588  5588 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-18 19:44:36.018  5588  5588 I Radio-JNI: register_android_hardware_Radio DONE
11-18 19:44:36.033  5588  5588 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-18 19:44:36.036   927  3422 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-18 19:44:36.053  5588  5588 D AndroidRuntime: Shutting down VM
11-18 19:44:36.067  3985  4001 W SearchService: Abort, client detached.
11-18 19:44:36.073  3985  3985 I HotwordDetector: Closing mic
11-18 19:44:36.073  3985  4220 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7e82d12
11-18 19:44:36.074  3985  4239 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-18 19:44:36.091   927  3862 I ActivityManager: Start proc 5597:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-18 19:44:36.151   512  4242 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-18 19:44:36.153   512  4242 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-18 19:44:36.157   512  4242 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-18 19:44:36.157   512  4242 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-18 19:44:36.157   512  3014 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-18 19:44:36.159  3985  4237 I MicroRecognitionRnrImpl: Detection finished
11-18 19:44:36.160  3985  4228 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-18 19:44:36.172  5597  5597 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-18 19:44:36.190  5597  5597 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-18 19:44:36.248  5597  5597 I LibraryLoader: Time to load native libraries: 54 ms (timestamps 4865-4919)
11-18 19:44:36.249  5597  5597 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-18 19:44:36.283  5597  5597 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f87f1f3}
11-18 19:44:36.284  5597  5597 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-18 19:44:36.284  5597  5597 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-18 19:44:36.287  5597  5597 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-18 19:44:36.288  5597  5597 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-18 19:44:36.337  5597  5597 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-18 19:44:36.351  5597  5597 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-18 19:44:36.351  5597  5597 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-18 19:44:36.351  5597  5597 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-18 19:44:36.351  5597  5597 I Adreno  : Build Date                       : 12/06/15
11-18 19:44:36.351  5597  5597 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-18 19:44:36.351  5597  5597 I Adreno  : Local Branch                     : mybranch17112971
11-18 19:44:36.351  5597  5597 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-18 19:44:36.351  5597  5597 I Adreno  : Remote Branch                    : NONE
11-18 19:44:36.351  5597  5597 I Adreno  : Reconstruct Branch               : NOTHING
,11-18 19:44:36.392   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e6dc5cb:true
,11-18 19:44:36.418   502   502 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[15166]" dev="sockfs" ino=15166 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 19:44:36.418   502   502 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[15166]" dev="sockfs" ino=15166 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 19:44:36.430  5597  5597 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-18 19:44:36.437  5597  5597 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-18 19:44:36.461   502   502 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33170]" dev="sockfs" ino=33170 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 19:44:36.461   502   502 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33170]" dev="sockfs" ino=33170 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 19:44:36.465  5597  5634 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-18 19:44:36.464  3421  3421 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[27173]" dev="sockfs" ino=27173 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 19:44:36.464  3421  3421 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[27173]" dev="sockfs" ino=27173 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-18 19:44:36.469  5597  5621 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-18 19:44:36.491  5597  5634 I OpenGLRenderer: Initialized EGL, version 1.4
,11-18 19:44:36.571   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +496ms
11-18 19:44:36.568  3862  3862 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33174]" dev="sockfs" ino=33174 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 19:44:36.574  3862  3862 W Binder_9: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33174]" dev="sockfs" ino=33174 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 19:44:36.574  3166  3166 W Binder_4: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33173]" dev="sockfs" ino=33173 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 19:44:36.574  3166  3166 W Binder_4: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33173]" dev="sockfs" ino=33173 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-18 19:44:36.578  3667  3667 I Keyboard.Facilitator: onFinishInput()
,11-18 19:44:36.619  5597  5597 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5597
,11-18 19:44:36.716  5597  5597 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-18 19:44:36.907  5597  5636 D jxcore_app_log: JniHelper::setJavaVM(0xf52fc000), pthread_self() = -562824912
,11-18 19:44:36.914  5597  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-18 19:44:36.914  5597  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-18 19:44:36.914  5597  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-18 19:44:36.914  5597  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-18 19:44:36.914  5597  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-18 19:44:36.914  5597  5636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66fa221 added. We now have 1 listener(s)
,11-18 19:44:36.917  5597  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
11-18 19:44:36.917  5597  5636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-18 19:44:36.918  5597  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 19:44:36.918  5597  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-18 19:44:36.920  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-18 19:44:36.921  5597  5636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91f0534 added. We now have 1 listener(s)
11-18 19:44:36.921  5597  5636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 19:44:36.926   927  2984 D WifiService: New client listening to asynchronous messages
,11-18 19:44:36.926  5597  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-18 19:44:36.926  5597  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-18 19:44:36.927  5597  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-18 19:44:36.927  5597  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-18 19:44:36.927  5597  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-18 19:44:36.927  5597  5636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-18 19:44:36.927  5597  5636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-18 19:44:36.928  5597  5636 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-18 19:44:37.088  5597  5597 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-18 19:44:37.455  5597  5606 I art     : Background sticky concurrent mark sweep GC freed 82187(8MB) AllocSpace objects, 16(1476KB) LOS objects, 22% free, 25MB/32MB, paused 1.364ms total 278.957ms
,11-18 19:44:37.586  5597  5644 W jxcore-log: Initializing JXcore engine
11-18 19:44:37.586  5597  5644 W jxcore-log: JXcore engine is ready
,11-18 19:44:37.608  5644  5644 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10199 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-18 19:44:37.608  5644  5644 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[12827]" dev="sockfs" ino=12827 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-18 19:44:37.608  5644  5644 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-18 19:44:37.608  5644  5644 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33141]" dev="sockfs" ino=33141 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-18 19:44:37.625  5597  5644 W jxcore-log: Starting JXcore engine
,11-18 19:44:37.675  5597  5644 W jxcore-log: Platform android
11-18 19:44:37.675  5597  5644 W jxcore-log: 
,11-18 19:44:37.675  5597  5644 W jxcore-log: Process ARCH arm
11-18 19:44:37.675  5597  5644 W jxcore-log: 
,11-18 19:44:37.810  5597  5644 I jxcore-log: JXcore Cordova bridge is ready!
11-18 19:44:37.810  5597  5644 I jxcore-log: 
,11-18 19:44:37.810  5597  5644 W jxcore-log: JXcore engine is started
,11-18 19:44:37.814  5597  5636 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-18 19:44:37.817  5597  5597 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-18 19:44:38.187   927  2985 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-18 19:44:39.590  3589  3589 I ConfigService: onDestroy
,11-18 19:44:41.082   927  3841 I ActivityManager: Killing 5143:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-18 19:44:42.120   927  2983 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-18 19:44:45.416   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:44:46.417   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:44:47.418   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:44:47.550  5597  5644 I jxcore-log: 2016-11-18 18:44:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-18 19:44:47.550  5597  5644 I jxcore-log: 
,11-18 19:44:47.553  5597  5644 I jxcore-log: 2016-11-18 18:44:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-18 19:44:47.553  5597  5644 I jxcore-log: 
,11-18 19:44:47.558  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-18 19:44:47.559  5597  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 19:44:47.559  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:44:47.559  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 19:44:47.559  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 19:44:47.559  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 19:44:47.559  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 19:44:47.559  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 19:44:47.559  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 19:44:47.559  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 19:44:47.560  5597  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-18 19:44:47.561  5597  5644 I jxcore-log: 2016-11-18 18:44:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-18 19:44:47.561  5597  5644 I jxcore-log: 
11-18 19:44:47.563  5597  5644 I jxcore-log: 2016-11-18 18:44:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-18 19:44:47.563  5597  5644 I jxcore-log: 
,11-18 19:44:47.812  5597  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 19:44:47.812  5597  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dd7a8c added. We now have 2 listener(s)
,11-18 19:44:47.813  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:44:47.813  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 19:44:47.813  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 19:44:47.813  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-18 19:44:47.813  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ec05d5 added. We now have 2 listener(s)
,11-18 19:44:47.813  5597  5644 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 19:44:47.814  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-18 19:44:47.815  5597  5644 D ExecuteNativeTests: Running unit tests
11-18 19:44:47.816  5597  5644 D BluetoothAdapter: enable(): BT is already enabled..!
11-18 19:44:47.816   927  3792 D WifiService: setWifiEnabled: true pid=5597, uid=10077
,11-18 19:44:47.816   927  3792 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 19:44:48.420   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:44:49.278  4835  4906 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-18 19:44:49.279  4835  4835 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-18 19:44:49.282   927   938 I ActivityManager: Killing 5234:org.codeaurora.ims/1001 (adj 15): empty #17
,11-18 19:44:49.344   927  2984 D WifiService: New client listening to asynchronous messages
,11-18 19:44:49.348  3985  5646 W CronetSyncConnectionRcs: Upload content type not set.
,11-18 19:44:49.421   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:44:50.280   927  2985 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-18 19:44:50.422   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-18 19:44:53.311   927  2985 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-18 19:44:57.821  5597  5644 I com.test.thalitest.ThaliTestRunner: Running UT
,11-18 19:44:57.883  5597  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 19:44:57.883  5597  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a91bb3e added. We now have 3 listener(s)
,11-18 19:44:57.884  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:44:57.884  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 19:44:57.884  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 19:44:57.884  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 19:44:57.884  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70dcd9f added. We now have 3 listener(s)
11-18 19:44:57.884  5597  5644 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 19:44:57.885  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 19:44:57.889  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-18 19:44:57.890  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-18 19:44:57.890  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:44:57.890  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 19:44:57.890  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:44:57.891  5597  5644 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-18 19:44:57.891  5597  5644 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-18 19:44:57.891  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-18 19:44:57.891  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:44:57.891  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:44:57.891  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:44:57.892  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-18 19:44:57.893  5597  5644 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-18 19:44:57.895  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-18 19:44:57.896  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-18 19:44:57.897  5597  5644 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 19:44:57.898  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:44:57.898  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 19:44:57.911  5597  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 19:44:57.911  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:44:57.911  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 19:44:57.911  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 19:44:57.911  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 19:44:57.911  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 19:44:57.911  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 19:44:57.911  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 19:44:57.911  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 19:44:57.913  5597  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-18 19:44:57.913  5597  5644 D io.jxcore.node.ConnectivityMonitor: start: OK
11-18 19:44:57.913  5597  5644 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-18 19:44:57.913  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,11-18 19:44:57.914  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.914  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.914  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.914  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:44:57.914  5597  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 19:44:57.914  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 19:44:57.914  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 19:44:57.915  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 19:44:57.916  5597  5597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 19:44:57.916  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 19:44:57.916  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 19:44:57.916  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 19:44:57.916  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 19:44:57.916  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-18 19:44:57.916  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:44:57.916  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 19:44:57.917  5597  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 19:44:57.917  5597  5597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 19:44:57.917  5597  5597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 19:44:57.918  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 19:44:57.918  5597  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 19:44:57.918  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 19:44:57.920  5597  5658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:44:57.918  4662  4662 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[27192]" dev="sockfs" ino=27192 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:44:57.922  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.922  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 19:44:57.922  5597  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 19:44:57.918  4662  4662 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[27192]" dev="sockfs" ino=27192 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:44:57.923  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:44:57.924  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 19:44:57.924  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-18 19:44:57.924  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:57.925  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.925  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 19:44:57.925  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 19:44:57.925  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:44:57.925  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-18 19:44:57.925  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:44:57.925  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 19:44:57.925  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.925  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 19:44:57.926  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:44:57.926  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.926  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.926  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.926  5597  5644 D BluetoothAdapter: STATE_ON
,11-18 19:44:57.929  4640  4874 D BtGatt.GattService: registerClient() - UUID=91bfc930-067c-41a6-a34a-25ed7fc94cd7
,11-18 19:44:57.930  4640  4727 D BtGatt.GattService: onClientRegistered() - UUID=91bfc930-067c-41a6-a34a-25ed7fc94cd7, clientIf=5
,11-18 19:44:57.930  5597  5608 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 19:44:57.933  4640  4729 D BtGatt.AdvertiseManager: message : 0
,11-18 19:44:57.936  4640  4729 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 19:44:57.951  4640  4727 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 19:44:57.958  4640  4727 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 19:44:57.960  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.960  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:57.960  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 19:44:57.960  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.960  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.960  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.960  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.960  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.960  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 19:44:57.961  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-18 19:44:57.961  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.961  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.961  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:57.962  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:57.962  5597  5644 I io.jxcore.node.ConnectionHelper: start: OK
,11-18 19:44:57.962  5597  5597 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:44:57.963  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 19:44:57.963  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 19:44:57.963  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 19:44:57.963  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 19:44:57.964  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:57.964  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-18 19:44:57.964  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:44:57.964  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 19:44:57.964  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 19:44:57.964  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:44:57.964  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 19:44:57.964  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 19:44:57.964  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 19:44:57.967  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:44:57.967  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 19:44:57.968  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:57.968  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:57.968  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:44:57.968  5597  5597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 19:44:58.466  5597  5644 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-18 19:44:58.466  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-18 19:44:58.466  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-18 19:44:58.466  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-18 19:44:58.466  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-18 19:44:58.466  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-18 19:44:58.466  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-18 19:44:58.466  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-18 19:44:58.466  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-18 19:44:58.466  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-18 19:44:58.467  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-18 19:44:58.467  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-18 19:44:58.467  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-18 19:44:58.467  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-18 19:44:58.467  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-18 19:44:58.467  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-18 19:44:58.467  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-18 19:44:58.467  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-18 19:44:58.468  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-18 19:44:58.468  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-18 19:44:58.468  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-18 19:44:58.468  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-18 19:44:58.468  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-18 19:44:58.468  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-18 19:44:58.468  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-18 19:44:58.468  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-18 19:44:58.468  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-18 19:44:58.468  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-18 19:44:58.469  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-18 19:44:58.469  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-18 19:44:58.469  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-18 19:44:58.469  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-18 19:44:58.469  5597  5644 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-18 19:44:58.470  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-18 19:44:58.470  5597  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 19:44:58.470  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 19:44:58.470  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-18 19:44:58.470  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 19:44:58.470  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-18 19:44:58.471  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 19:44:58.471  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 19:44:58.471  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 19:44:58.471  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 19:44:58.471  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 19:44:58.471  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 19:44:58.471  5597  5597 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 19:44:58.472  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.472  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.472  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.472  5597  5658 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 19:44:58.472  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.473  5597  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 19:44:58.473  5597  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 19:44:58.473  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:44:58.474  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 19:44:58.475  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:44:58.475  5597  5644 D BluetoothLeScanner: could not find callback wrapper
11-18 19:44:58.475  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 19:44:58.475  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.475  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.475  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.475  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 19:44:58.475  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.477  4640  4729 D BtGatt.AdvertiseManager: message : 1
11-18 19:44:58.478  4640  4729 D BtGatt.AdvertiseManager: stop advertise for client 5
11-18 19:44:58.491  4640  4727 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 19:44:58.492  4640  4727 D BtGatt.GattService: Client app is not null!
11-18 19:44:58.493  4640  4855 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 19:44:58.495  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 19:44:58.495  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.495  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 19:44:58.495  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:58.495  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.496  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.496  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 19:44:58.496  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 19:44:58.497  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 19:44:58.497  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.499  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.499  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:44:58.499  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.499  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.500  5597  5597 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 19:44:58.500  5597  5597 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 19:44:58.503  5597  5644 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 19:44:58.503  5597  5597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 19:44:58.503  5597  5644 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 19:44:58.504  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:44:58.504  5597  5644 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-18 19:44:58.504  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:44:58.504  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-18 19:44:58.504  5597  5597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 19:44:58.504  5597  5597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:44:58.504  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.504  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 19:44:58.504  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.504  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.504  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.504  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 19:44:58.504  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:44:58.504  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 19:44:58.504  5597  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 19:44:58.504  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.505  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 19:44:58.505  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:44:58.505  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.505  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 19:44:58.505  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.509  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 19:44:58.509  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 19:44:58.509  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-,18 19:44:58.509  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 19:44:58.509  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 19:44:58.510  5597  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 19:44:58.511  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.512  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.512  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.512  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.512  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 19:44:58.512  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:44:58.512  5597  5597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:44:58.512  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 19:44:58.512  5597  5597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 19:44:58.513  5597  5661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:44:58.514  4873  4873 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32039]" dev="sockfs" ino=32039 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:44:58.516  5597  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 19:44:58.514  4873  4873 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32039]" dev="sockfs" ino=32039 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:44:58.517  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 19:44:58.517  5597  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 19:44:58.517  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 19:44:58.521  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.521  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 19:44:58.522  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:44:58.522  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 19:44:58.522  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-18 19:44:58.525  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.525  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.525  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 19:44:58.525  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 19:44:58.525  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:44:58.526  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-18 19:44:58.526  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:44:58.526  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:44:58.526  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.526  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 19:44:58.526  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:44:58.526  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.526  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.526  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.527  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:44:58.530  4640  4874 D BtGatt.GattService: registerClient() - UUID=5663b4cd-497f-440a-9ca7-332ef3d9e592
11-18 19:44:58.531  4640  4727 D BtGatt.GattService: onClientRegistered() - UUID=5663b4cd-497f-440a-9ca7-332ef3d9e592, clientIf=5
11-18 19:44:58.531  5597  5607 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 19:44:58.532  4640  4729 D BtGatt.AdvertiseManager: message : 0
11-18 19:44:58.534  4640  4729 D BtGatt.AdvertiseManager: starting multi advertising
11-18 19:44:58.545  4640  4727 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 19:44:58.551  4640  4727 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-18 19:44:58.552  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.552  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.552  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 19:44:58.552  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.552  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.552  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.553  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.553  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.553  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 19:44:58.554  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 19:44:58.554  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.555  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.555  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.555  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:58.555  5597  5644 I io.jxcore.node.ConnectionHelper: start: OK
11-18 19:44:58.555  5597  5597 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:44:58.556  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.556  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 19:44:58.556  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 19:44:58.556  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.556  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.556  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:44:58.556  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.556  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 19:44:58.556  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 19:44:58.556  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.556  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.556  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 19:44:58.556  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.559  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.559  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 19:44:58.559  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.559  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.559  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:44:58.559  5597  5597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 19:44:59.060  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-18 19:44:59.060  5597  5597 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 19:44:59.060  5597  5597 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 19:44:59.060  5597  5644 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 19:44:59.061  5597  5597 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 19:44:59.061  5597  5644 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 19:44:59.061  5597  5644 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-18 19:44:59.061  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-18 19:44:59.061  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.062  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.062  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.065  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 19:44:59.065  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 19:44:59.065  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 19:44:59.065  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-18 19:44:59.065  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 19:44:59.065  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 19:44:59.065  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 19:44:59.065  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 19:44:59.065  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 19:44:59.065  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.066  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-18 19:44:59.067  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.067  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.067  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.069  4640  4729 D BtGatt.AdvertiseManager: message : 1
,11-18 19:44:59.070  4640  4729 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 19:44:59.085  4640  4727 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 19:44:59.085  4640  4727 D BtGatt.GattService: Client app is not null!
,11-18 19:44:59.086  4640  4874 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 19:44:59.087  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 19:44:59.087  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.087  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-18 19:44:59.087  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.088  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.088  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.088  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 19:44:59.088  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.088  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.088  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.088  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 19:44:59.089  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 19:44:59.089  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:44:59.089  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-18 19:44:59.089  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:44:59.089  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:44:59.090  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.090  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 19:44:59.090  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:44:59.090  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.090  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.090  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.091  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:44:59.096  4640  4663 D BtGatt.GattService: registerClient() - UUID=1ec87197-3b85-4dbb-9040-b1db864fcef7
11-18 19:44:59.096  4640  4727 D BtGatt.GattService: onClientRegistered() - UUID=1ec87197-3b85-4dbb-9040-b1db864fcef7, clientIf=5
11-18 19:44:59.097  5597  5608 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 19:44:59.099  4640  4729 D BtGatt.AdvertiseManager: message : 0
11-18 19:44:59.103  4640  4729 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 19:44:59.118  4640  4727 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 19:44:59.126  4640  4727 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 19:44:59.127  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.127  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.127  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.127  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 19:44:59.127  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.127  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.127  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.128  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.128  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.128  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.128  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:44:59.128  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-18 19:44:59.128  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 19:44:59.128  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.128  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.128  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-18 19:44:59.128  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.128  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 19:44:59.128  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-18 19:44:59.128  5597  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-18 19:44:59.128  5597  5644 I io.jxcore.node.ConnectionHelper: start: OK
11-18 19:44:59.128  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.129  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 19:44:59.129  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 19:44:59.129  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.129  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.130  5597  5644 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-18 19:44:59.130  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 19:44:59.130  5597  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-18 19:44:59.130  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 19:44:59.130  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 19:44:59.130  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 19:44:59.130  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 19:44:59.130  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 19:44:59.130  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 19:44:59.130  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 19:44:59.130  5597  5661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 19:44:59.130  5597  5597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 19:44:59.131  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 19:44:59.131  5597  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 19:44:59.131  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 19:44:59.131  5597  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 19:44:59.131  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 19:44:59.131  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.131  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.131  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.131  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.132  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:44:59.132  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 19:44:59.133  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:44:59.133  5597  5644 D BluetoothLeScanner: could not find callback wrapper
11-18 19:44:59.133  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 19:44:59.133  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.133  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.133  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.133  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 19:44:59.133  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.134  4640  4729 D BtGatt.AdvertiseManager: message : 1
11-18 19:44:59.135  4640  4729 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 19:44:59.143  4640  4727 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 19:44:59.143  4640  4727 D BtGatt.GattService: Client app is not null!
,11-18 19:44:59.145  4640  4663 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 19:44:59.146  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 19:44:59.146  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.146  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 19:44:59.146  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.146  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.146  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.146  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 19:44:59.146  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 19:44:59.147  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 19:44:59.147  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.149  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.149  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:44:59.149  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.149  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.149  5597  5597 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 19:44:59.150  5597  5597 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 19:44:59.150  5597  5597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 19:44:59.150  5597  5597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:44:59.150  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:44:59.150  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 19:44:59.150  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 19:44:59.150  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.150  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 19:44:59.150  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 19:44:59.150  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.150  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.151  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 19:44:59.151  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.151  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-18 19:44:59.151  5597  5644 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-18 19:44:59.152  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.152  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.152  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.152  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.153  5597  5597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:44:59.153  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-18 19:44:59.153  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-18 19:44:59.154  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-18 19:44:59.155  5597  5644 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-18 19:44:59.156  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-18 19:44:59.156  5597  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-18 19:44:59.156  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-18 19:44:59.157  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 19:44:59.157  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:44:59.157  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:44:59.157  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:44:59.157  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 19:44:59.157  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:44:59.157  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:44:59.157  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:44:59.157  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 19:44:59.157  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 19:44:59.157  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:44:59.157  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:44:59.159  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-18 19:44:59.160  5597  5644 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-18 19:44:59.161  5597  5644 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-18 19:44:59.166  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,11-18 19:44:59.167  5597  5644 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-18 19:44:59.169  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,11-18 19:44:59.169  5597  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-18 19:44:59.171  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-18 19:44:59.171  5597  5644 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-18 19:44:59.171  5597  5644 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-18 19:44:59.171  5597  5644 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-18 19:44:59.171  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 19:44:59.172  5597  5644 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-18 19:44:59.172  5597  5644 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 19:44:59.172  5597  5644 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-18 19:44:59.172  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 19:44:59.172  5597  5644 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-18 19:44:59.172  5597  5644 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 19:44:59.172  5597  5644 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,11-18 19:44:59.172  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 19:44:59.172  5597  5644 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,11-18 19:44:59.173  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-18 19:44:59.173  5597  5644 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 19:44:59.173  5597  5644 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 19:44:59.173  5597  5644 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-18 19:44:59.173  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-18 19:44:59.173  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.173  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.174  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.174  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:44:59.174  5597  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 19:44:59.174  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 19:44:59.174  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 19:44:59.175  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 19:44:59.175  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-18 19:44:59.175  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 19:44:59.175  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-18 19:44:59.176  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 19:44:59.176  5597  5597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 19:44:59.176  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 19:44:59.176  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:44:59.176  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-18 19:44:59.176  5597  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 19:44:59.178  5597  5665 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:44:59.178  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 19:44:59.178  5597  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 19:44:59.179  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 19:44:59.180  5597  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 19:44:59.178  4855  4855 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33945]" dev="sockfs" ino=33945 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 19:44:59.178  4855  4855 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33945]" dev="sockfs" ino=33945 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:44:59.182  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.182  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 19:44:59.183  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:44:59.183  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 19:44:59.183  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-18 19:44:59.185  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.185  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.185  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 19:44:59.185  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 19:44:59.185  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:44:59.185  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
,11-18 19:44:59.185  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 19:44:59.186  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:44:59.186  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.186  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 19:44:59.186  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:44:59.186  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.186  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.186  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.187  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:44:59.189  4640  4874 D BtGatt.GattService: registerClient() - UUID=819add4f-2302-4e67-a1d7-38cac22790d0
11-18 19:44:59.190  4640  4727 D BtGatt.GattService: onClientRegistered() - UUID=819add4f-2302-4e67-a1d7-38cac22790d0, clientIf=5
11-18 19:44:59.190  5597  5608 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 19:44:59.191  4640  4729 D BtGatt.AdvertiseManager: message : 0
11-18 19:44:59.192  4640  4729 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 19:44:59.201  4640  4727 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 19:44:59.207  4640  4727 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 19:44:59.208  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.208  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.208  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 19:44:59.208  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.208  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.208  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.208  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.208  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.208  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 19:44:59.209  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 19:44:59.209  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.210  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.210  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.210  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.210  5597  5644 I io.jxcore.node.ConnectionHelper: start: OK
11-18 19:44:59.211  5597  5597 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:44:59.211  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.211  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 19:44:59.211  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 19:44:59.211  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.211  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.211  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:44:59.211  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.211  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 19:44:59.211  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 19:44:59.211  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.211  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.211  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: o,nBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 19:44:59.211  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.213  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.214  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 19:44:59.214  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.214  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.214  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.214  5597  5597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 19:44:59.712  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 19:44:59.712  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 19:44:59.712  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 19:44:59.712  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 19:44:59.713  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 19:44:59.713  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-18 19:44:59.713  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 19:44:59.713  5597  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 19:44:59.713  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 19:44:59.713  5597  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 19:44:59.714  5597  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 19:44:59.714  5597  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a91bb3e removed from the list
,11-18 19:44:59.714  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 19:44:59.714  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 19:44:59.714  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 19:44:59.714  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-18 19:44:59.715  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.715  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.715  5597  5597 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-18 19:44:59.715  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.715  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.716  5597  5597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 19:44:59.716  5597  5597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 19:44:59.716  5597  5597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:44:59.717  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:44:59.717  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 19:44:59.719  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:44:59.720  5597  5644 D BluetoothLeScanner: could not find callback wrapper
,11-18 19:44:59.720  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 19:44:59.720  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.721  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.721  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:44:59.721  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 19:44:59.721  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.725  4640  4729 D BtGatt.AdvertiseManager: message : 1
11-18 19:44:59.726  4640  4729 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 19:44:59.739  4640  4727 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 19:44:59.739  4640  4727 D BtGatt.GattService: Client app is not null!
,11-18 19:44:59.740  4640  4873 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 19:44:59.741  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 19:44:59.742  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.742  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 19:44:59.742  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.742  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.742  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.742  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 19:44:59.742  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 19:44:59.744  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-18 19:44:59.744  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.746  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.746  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:44:59.746  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.746  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:44:59.746  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70dcd9f removed from the list
11-18 19:44:59.746  5597  5644 D io.jxcore.node.ConnectivityMonitor: stop
11-18 19:44:59.746  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-18 19:44:59.747  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:44:59.747  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:44:59.747  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 19:44:59.747  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.747  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 19:44:59.747  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 19:44:59.747  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.748  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.748  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 19:44:59.748  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 19:44:59.750  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.751  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.751  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.751  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:44:59.751  5597  5597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 19:44:59.929   927   927 I ActivityManager: Killing 5272:com.android.settings/1000 (adj 15): empty #17
,11-18 19:45:00.252  5597  5597 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 19:45:04.751  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-18 19:45:04.755  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-18 19:45:04.756  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 19:45:04.756  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 19:45:04.761  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 19:45:04.762  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 19:45:04.762  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 19:45:04.763  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 19:45:04.763  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 19:45:04.763  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 19:45:04.763  5597  5597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 19:45:04.763  5597  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 19:45:04.765  5597  5666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:45:04.766  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-18 19:45:04.767  5597  5644 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-18 19:45:04.767  5597  5644 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-18 19:45:04.768  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 19:45:04.768  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:45:04.768  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:45:04.768  4662  4662 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33948]" dev="sockfs" ino=33948 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 19:45:04.769  5597  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 19:45:04.770  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-18 19:45:04.768  4662  4662 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[33948]" dev="sockfs" ino=33948 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 19:45:04.776  5597  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-18 19:45:04.777  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 19:45:04.777  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 19:45:04.777  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 19:45:04.777  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 19:45:04.777  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 19:45:04.777  5597  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 19:45:04.777  5597  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 19:45:04.777  5597  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 19:45:04.778  5597  5597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 19:45:04.778  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:45:04.778  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 19:45:04.779  5597  5644 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a91bb3e not in the list
11-18 19:45:04.779  5597  5597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:45:04.779  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 19:45:04.779  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 19:45:04.779  5597  5597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 19:45:04.779  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 19:45:04.779  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 19:45:04.779  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:04.781  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:04.782  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:45:04.782  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:04.782  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:04.782  5597  5644 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70dcd9f not in the list
11-18 19:45:04.782  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:45:04.782  5597  5644 D io.jxcore.node.ConnectivityMonitor: stop
11-18 19:45:04.782  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 19:45:04.782  5597  5597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 19:45:04.785  5597  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-18 19:45:04.786  5597  5644 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-18 19:45:04.786  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 19:45:04.787  5597  5644 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-18 19:45:04.787  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 19:45:04.787  5597  5644 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-18 19:45:04.787  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 19:45:04.788  5597  5644 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-18 19:45:04.789  5597  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-18 19:45:04.790  5597  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-18 19:45:04.790  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-18 19:45:04.790  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-18 19:45:04.791  5597  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-18 19:45:04.791  5597  5644 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-18 19:45:04.791  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-18 19:45:04.791  5597  5644 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-18 19:45:04.791  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-18 19:45:04.791  5597  5644 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-18 19:45:04.791  5597  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-18 19:45:04.792  5597  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-18 19:45:04.792  5597  5644 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-18 19:45:04.792  5597  5644 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-18 19:45:04.793  5597  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-18 19:45:04.793  5597  5644 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-18 19:45:04.793  5597  5644 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-18 19:45:04.793  5597  5644 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-18 19:45:04.793  5597  5644 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-18 19:45:04.794  5597  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-18 19:45:04.794  5597  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 19:45:04.794  5597  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b11325 added. We now have 3 listener(s)
,11-18 19:45:04.796  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:45:04.796  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 19:45:04.796  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 19:45:04.796  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-18 19:45:04.796  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d89cfa added. We now have 3 listener(s)
11-18 19:45:04.796  5597  5644 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 19:45:04.797  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 19:45:04.799  5597  5644 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 19:45:04.799   927  3862 D WifiService: setWifiEnabled: true pid=5597, uid=10077
11-18 19:45:04.799   927  3862 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 19:45:04.801  5597  5644 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-18 19:45:04.804  5597  5644 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-18 19:45:04.804  5597  5644 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-18 19:45:04.807  5597  5644 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-18 19:45:04.808  5597  5644 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-18 19:45:04.814  4640  4723 D BluetoothAdapterState: Current state: ON, message: 23
,11-18 19:45:04.814  4640  4723 D BluetoothAdapterProperties: Setting state to 13
11-18 19:45:04.814  4640  4723 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-18 19:45:04.814  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
11-18 19:45:04.814  5597  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 19:45:04.814  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:45:04.814  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
11-18 19:45:04.814  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 19:45:04.814  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 19:45:04.814  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 19:45:04.814  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 19:45:04.814  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 19:45:04.814  5597  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 19:45:04.814  4640  4723 D BluetoothAdapterProperties: onBluetoothDisable()
,11-18 19:45:04.817  4640  4723 I BluetoothAdapterState: Entering PendingCommandState
11-18 19:45:04.818  5597  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 19:45:04.818  5597  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 19:45:04.819  4640  4640 D BluetoothMapService: onReceive
,11-18 19:45:04.819  4640  4640 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-18 19:45:04.820  4640  4640 D BluetoothMapService: STATE_TURNING_OFF
11-18 19:45:04.820  4640  4640 D BluetoothMapService: MAP Service closeService in
11-18 19:45:04.820  4640  4640 D BluetoothMapMasInstance0: MAP Service shutdown
11-18 19:45:04.820  4640  4640 D ObexServerSockets0: shutdown(block = true)
11-18 19:45:04.821  4640  4640 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-18 19:45:04.821  4640  4881 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-18 19:45:04.821  4640  4640 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-18 19:45:04.821  4640  4848 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-18 19:45:04.821  4640  4882 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-18 19:45:04.824  4640  4640 I BtOppRfcommListener: stopping Accept Thread
11-18 19:45:04.824  4640  5296 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-18 19:45:04.824  4640  5296 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-18 19:45:04.836   927   940 I ActivityManager: Start proc 5669:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-18 19:45:04.837  4640  4727 D BluetoothAdapterProperties: Scan Mode:20
,11-18 19:45:04.837  4640  4723 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-18 19:45:04.841  4640  4640 D HeadsetService: Received stop request...Stopping profile...
,11-18 19:45:04.844  3789  3819 D BluetoothHeadset: Proxy object disconnected
,11-18 19:45:04.844   927   927 D BluetoothHeadset: Proxy object disconnected
11-18 19:45:04.845  4640  4640 D A2dpService: Received stop request...Stopping profile...
11-18 19:45:04.845  3152  3163 D BluetoothHeadset: Proxy object disconnected
11-18 19:45:04.845  4640  4865 D A2dpStateMachine: Exit Disconnected: -1
11-18 19:45:04.846   927   927 D BluetoothHeadset: Proxy object disconnected
11-18 19:45:04.846   927   927 D BluetoothHeadset: Proxy object disconnected
,11-18 19:45:04.846   927   927 D BluetoothA2dp: Proxy object disconnected
11-18 19:45:04.846  4640  4640 V BluetoothAdapterState: isTurningOff()=true
,11-18 19:45:04.846  4640  4640 V BluetoothAdapterState: isTurningOn()=false
,11-18 19:45:04.847  4640  4640 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:04.847  4640  4640 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 19:45:04.849  4640  4640 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-18 19:45:04.849  4640  4640 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-18 19:45:04.849  4640  4640 V BluetoothAdapterState: isTurningOff()=true
11-18 19:45:04.849  4640  4640 V BluetoothAdapterState: isTurningOn()=false
11-18 19:45:04.849  4640  4640 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:04.849  4640  4640 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 19:45:04.849  4640  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-18 19:45:04.849  4640  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 19:45:04.849  4640  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 19:45:04.850  4640  4727 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-18 19:45:04.850  4640  4727 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-18 19:45:04.851  4640  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 19:45:04.851  4640  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 19:45:04.852  4640  4640 D HidService: Received stop request...Stopping profile...
11-18 19:45:04.852  4640  4640 D HidService: Stopping Bluetooth HidService
11-18 19:45:04.852  4640  4727 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-18 19:45:04.852  4640  4833 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-18 19:45:04.852  4640  4833 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-18 19:45:04.852  4640  4833 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 19:45:04.852  4640  4833 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-18 19:45:04.853  4640  4640 D HealthService: Received stop request...Stopping profile...
11-18 19:45:04.854  3152  3152 D HeadsetProfile: Bluetooth service disconnected
11-18 19:45:04.855  3152  3152 D BluetoothA2dp: Proxy object disconnected
11-18 19:45:04.855  3152  3152 D BluetoothInputDevice: Proxy object disconnected
11-18 19:45:04.855  3152  3152 D HidProfile: Bluetooth service disconnected
11-18 19:45:04.855  4640  4640 D PanService: Received stop request...Stopping profile...
11-18 19:45:04.857  4640  4640 D BluetoothMapService: Received stop request...Stopping profile...
11-18 19:45:04.857  4640  4640 D BluetoothMapService: stop()
,11-18 19:45:04.859  3152  3152 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-18 19:45:04.859  3152  3152 D PanProfile: Bluetooth service disconnected
,11-18 19:45:04.859  4640  4640 D BluetoothMapAppObserver: deinitObservers()
,11-18 19:45:04.859  4640  4640 D BluetoothMapAppObserver: removeReceiver()
,11-18 19:45:04.861  3152  3152 D BluetoothMap: Proxy object disconnected
,11-18 19:45:04.861  3152  3152 D MapProfile: Bluetooth service disconnected
,11-18 19:45:04.861  4640  4640 D SapService: Received stop request...Stopping profile...
11-18 19:45:04.861  4640  4640 V SapService: stop()
,11-18 19:45:04.865  4640  4640 V BluetoothAdapterState: isTurningOff()=true
,11-18 19:45:04.866  4640  4640 V BluetoothAdapterState: isTurningOn()=false
,11-18 19:45:04.866  4640  4640 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 19:45:04.866  4640  4640 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 19:45:04.866  4640  4640 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-18 19:45:04.866  4640  4640 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-18 19:45:04.866  4640  4727 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-18 19:45:04.866  4640  4640 V BluetoothAdapterState: isTurningOff()=true
11-18 19:45:04.866  4640  4640 V BluetoothAdapterState: isTurningOn()=false
11-18 19:45:04.866  4640  4640 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:04.866  4640  4640 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:45:04.866  4640  4640 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-18 19:45:04.866  4640  4727 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-18 19:45:04.867  4640  4640 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-18 19:45:04.867  4640  4640 V BluetoothAdapterState: isTurningOff()=true
,11-18 19:45:04.867  4640  4640 V BluetoothAdapterState: isTurningOn()=false
,11-18 19:45:04.867  4640  4640 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:04.867  4640  4640 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:45:04.868  4640  4640 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-18 19:45:04.868  4640  4640 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-18 19:45:04.869  4640  4640 D BluetoothMapService: MAP Service closeService in
11-18 19:45:04.869  4640  4640 V BluetoothAdapterState: isTurningOff()=true
11-18 19:45:04.869  4640  4640 V BluetoothAdapterState: isTurningOn()=false
11-18 19:45:04.869  4640  4640 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 19:45:04.869  4640  4640 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:45:04.869  4640  4640 D BluetoothMapService: cleanup()
11-18 19:45:04.869  4640  4640 D BluetoothMapService: MAP Service closeService in
11-18 19:45:04.869  4640  4640 V BluetoothAdapterState: isTurningOff()=true
11-18 19:45:04.869  4640  4640 V BluetoothAdapterState: isTurningOn()=false
11-18 19:45:04.869  4640  4640 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:04.869  4640  4640 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:45:04.870  4640  4723 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-18 19:45:04.870  4640  4723 D BluetoothAdapterProperties: Setting state to 15
11-18 19:45:04.870  4640  4723 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-18 19:45:04.870  4640  4723 I BluetoothAdapterState: Entering BleOnState
11-18 19:45:04.870   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 19:45:04.871  3152  3165 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 19:45:04.871   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 19:45:04.871  3152  3163 D BluetoothPan: onBluetoothStateChange on: false
11-18 19:45:04.872   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 19:45:04.872  3789  3821 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-18 19:45:04.872   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 19:45:04.873  3152  4000 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-18 19:45:04.873  3152  3165 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 19:45:04.874  3152  3163 D BluetoothPbap: onBluetoothStateChange: up=false
11-18 19:45:04.875  3152  4000 D BluetoothMap: onBluetoothStateChange: up=false
11-18 19:45:04.878  4640  4723 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-18 19:45:04.878  4640  4723 D BluetoothAdapterProperties: Setting state to 16
11-18 19:45:04.878  4640  4723 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-18 19:45:04.879  4640  4723 D BluetoothAdapterProperties: onBleDisable
,11-18 19:45:04.879  4640  4723 I BluetoothAdapterState: Entering PendingCommandState
11-18 19:45:04.879  4640  4724 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-18 19:45:04.880  4640  4727 D BluetoothAdapterProperties: Scan Mode:20
11-18 19:45:04.880  4640  4833 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-18 19:45:04.880  4640  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 19:45:04.893  5669  5669 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-18 19:45:04.910  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 19:45:04.916   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b954e7c:true
11-18 19:45:04.916  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 19:45:04.931  5669  5669 D LocalBluetoothProfileManager: Adding local MAP profile
,11-18 19:45:04.933  5669  5669 D BluetoothMap: Create BluetoothMap proxy object
,11-18 19:45:04.941  5669  5669 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-18 19:45:04.946  5669  5669 D DockEventReceiver: finishStartingService: stopping service
,11-18 19:45:04.949  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 19:45:04.954  5669  5669 D DockEventReceiver: finishStartingService: stopping service
,11-18 19:45:04.954  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 19:45:04.956   927  3871 I ActivityManager: Killing 5396:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-18 19:45:05.089  4640  4727 I bt_hci  : shut_down
,11-18 19:45:05.094  4640  4731 D bt_hwcfg: hw_epilog_process
,11-18 19:45:05.095  4640  4731 I bt_vendor: low_power_mode_cb
,11-18 19:45:05.097  4640  4731 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-18 19:45:05.097  4640  4731 I bt_vendor: epilog_cb
,11-18 19:45:05.097  4640  4731 I bt_hci  : epilog_finished_callback
,11-18 19:45:05.101  4640  4727 I bt_hci_h4: hal_close
,11-18 19:45:05.102  4640  4727 I bt_userial_vendor: device fd = 54 close
,11-18 19:45:05.215  4640  4724 D bt_stack_manager: event_shut_down_stack finished.
,11-18 19:45:05.215  4640  4723 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-18 19:45:05.218  4640  4723 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-18 19:45:05.219  4640  4640 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-18 19:45:05.220  4640  4640 D BtGatt.GattService: Received stop request...Stopping profile...
,11-18 19:45:05.220  4640  4640 D BtGatt.GattService: stop()
11-18 19:45:05.220  4640  4640 D BtGatt.AdvertiseManager: advertise clients cleared
11-18 19:45:05.223  4640  4640 V BluetoothAdapterState: isTurningOff()=false
11-18 19:45:05.223  4640  4640 V BluetoothAdapterState: isTurningOn()=false
11-18 19:45:05.223  4640  4640 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:05.223  4640  4640 V BluetoothAdapterState: isBleTurningOff()=true
11-18 19:45:05.223  4640  4723 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-18 19:45:05.224  4640  4723 D BluetoothAdapterProperties: Setting state to 10
11-18 19:45:05.224  4640  4723 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-18 19:45:05.226  4640  4723 I BluetoothAdapterState: Entering OffState
,11-18 19:45:05.227   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-18 19:45:05.235  4640  4640 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-18 19:45:05.235  4640  4640 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-18 19:45:05.235  4640  4640 I BluetoothServiceJni: cleanupNative: return from cleanup
11-18 19:45:05.237  4640  4724 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-18 19:45:05.242  4640  4640 I art     : System.exit called, status: 0
11-18 19:45:05.242  4640  4640 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-18 19:45:05.266   927  3421 I ActivityManager: Process com.android.bluetooth (pid 4640) has died
,11-18 19:45:05.283  5597  5597 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 19:45:05.314  5597  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-18 19:45:05.314  5597  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 19:45:05.314  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:45:05.314  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
11-18 19:45:05.314  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 19:45:05.314  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-18 19:45:05.314  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 19:45:05.314  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 19:45:05.314  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 19:45:05.314  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 19:45:05.315  5597  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 19:45:05.315  5597  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 19:45:05.317  5597  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 19:45:05.330   927   944 I ActivityManager: Start proc 5686:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-18 19:45:05.393  5686  5686 D AdapterServiceConfig: Adding HeadsetService
11-18 19:45:05.393  5686  5686 D AdapterServiceConfig: Adding A2dpService
,11-18 19:45:05.393  5686  5686 D AdapterServiceConfig: Adding HidService
11-18 19:45:05.393  5686  5686 D AdapterServiceConfig: Adding HealthService
11-18 19:45:05.393  5686  5686 D AdapterServiceConfig: Adding PanService
11-18 19:45:05.393  5686  5686 D AdapterServiceConfig: Adding GattService
11-18 19:45:05.394  5686  5686 D AdapterServiceConfig: Adding BluetoothMapService
11-18 19:45:05.394  5686  5686 D AdapterServiceConfig: Adding SapService
,11-18 19:45:05.401   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c715d6:true
,11-18 19:45:05.401  5686  5686 D BluetoothAdapterState: make() - Creating AdapterState
,11-18 19:45:05.403  5686  5686 I bt_bluedroid: init
,11-18 19:45:05.403  5686  5698 I BluetoothAdapterState: Entering OffState
,11-18 19:45:05.405  5686  5699 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-18 19:45:05.405  5686  5699 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-18 19:45:05.405  5686  5699 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-18 19:45:05.405  5686  5699 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-18 19:45:05.406  5686  5686 I bt_bluedroid: get_profile_interface socket
,11-18 19:45:05.407  5686  5686 I bt_bluedroid: get_profile_interface sdp
,11-18 19:45:05.407  5686  5702 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-18 19:45:05.408  5686  5702 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-18 19:45:05.410  5686  5697 I bt_bluedroid: config_hci_snoop_log
11-18 19:45:05.411   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-18 19:45:05.415  5686  5698 D BluetoothAdapterState: Current state: OFF, message: 0
,11-18 19:45:05.415  5686  5698 D BluetoothAdapterProperties: Setting state to 14
11-18 19:45:05.415  5686  5698 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-18 19:45:05.417  5686  5698 D BluetoothBondStateMachine: make
,11-18 19:45:05.419  5686  5703 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-18 19:45:05.421  5686  5698 I BluetoothAdapterState: Entering PendingCommandState
,11-18 19:45:05.421  5686  5686 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-18 19:45:05.423  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@815e5ba
,11-18 19:45:05.423  5686  5686 D BtGatt.DebugUtils: handleDebugAction() action=null
11-18 19:45:05.424  5686  5686 D BtGatt.GattService: Received start request. Starting profile...
11-18 19:45:05.424  5686  5686 D BtGatt.GattService: start()
11-18 19:45:05.424  5686  5686 I bt_bluedroid: get_profile_interface gatt
,11-18 19:45:05.424  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@815e5ba
11-18 19:45:05.424  5686  5686 D BtGatt.AdvertiseManager: advertise manager created
,11-18 19:45:05.427  5686  5686 V BluetoothAdapterState: isTurningOff()=false
,11-18 19:45:05.427  5686  5686 V BluetoothAdapterState: isTurningOn()=false
11-18 19:45:05.428  5686  5686 V BluetoothAdapterState: isBleTurningOn()=true
11-18 19:45:05.428  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:45:05.428  5686  5698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-18 19:45:05.429  5686  5698 I bt_bluedroid: bt_bluedroid
,11-18 19:45:05.429  5686  5699 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-18 19:45:05.430  5686  5699 I bt_hci  : start_up
,11-18 19:45:05.434  5686  5699 I bt_vendor: alloc value 0xf3fbb871
,11-18 19:45:05.434  5686  5699 I bt_vendor: init
11-18 19:45:05.434  5686  5699 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-18 19:45:05.435  5686  5699 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-18 19:45:05.543  5686  5699 D bt_hci  : start_up starting async portion
,11-18 19:45:05.544  5686  5706 I bt_hci  : event_finish_startup
,11-18 19:45:05.544  5686  5706 I bt_hci_h4: hal_open
11-18 19:45:05.544  5686  5706 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-18 19:45:05.541  5707  5707 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 19:45:05.547  5686  5706 I bt_userial_vendor: device fd = 54 open
,11-18 19:45:05.560  5686  5706 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-18 19:45:05.562  5686  5706 D bt_hwcfg: Chipset BCM4358A3
,11-18 19:45:05.562  5686  5706 D bt_hwcfg: Target name = [BCM4358A3]
11-18 19:45:05.563  5686  5706 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-18 19:45:05.823  5686  5698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-18 19:45:05.962  5686  5706 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-18 19:45:05.962  5686  5706 D bt_hwcfg: Settlement delay -- 100 ms
,11-18 19:45:05.962  5686  5706 I bt_hwcfg: Setting fw settlement delay to 100 
,11-18 19:45:06.087  5686  5706 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-18 19:45:06.088  5686  5706 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-18 19:45:06.089  5686  5706 I bt_hwcfg: vendor lib fwcfg completed
11-18 19:45:06.089  5686  5706 I bt_vendor: firmware callback
11-18 19:45:06.089  5686  5706 I bt_hci  : firmware_config_callback
,11-18 19:45:06.097  5686  5709 I bt_btu  : btu_task pending for preload complete event
,11-18 19:45:06.097  5686  5709 I bt_btu_task: Bluetooth chip preload is complete
,11-18 19:45:06.097  5686  5709 I bt_btu  : btu_task received preload complete event
,11-18 19:45:06.104  5686  5709 I         : BTE_InitTraceLevels -- TRC_HCI
,11-18 19:45:06.104  5686  5709 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-18 19:45:06.104  5686  5709 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-18 19:45:06.104  5686  5709 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-18 19:45:06.104  5686  5709 I         : BTE_InitTraceLevels -- TRC_AVRC
11-18 19:45:06.105  5686  5709 I         : BTE_InitTraceLevels -- TRC_A2D
11-18 19:45:06.105  5686  5709 I         : BTE_InitTraceLevels -- TRC_BNEP
11-18 19:45:06.105  5686  5709 I         : BTE_InitTraceLevels -- TRC_BTM
,11-18 19:45:06.105  5686  5709 I         : BTE_InitTraceLevels -- TRC_GAP
11-18 19:45:06.105  5686  5709 I         : BTE_InitTraceLevels -- TRC_PAN
11-18 19:45:06.105  5686  5709 I         : BTE_InitTraceLevels -- TRC_SDP
,11-18 19:45:06.105  5686  5709 I         : BTE_InitTraceLevels -- TRC_GATT
11-18 19:45:06.106  5686  5709 I         : BTE_InitTraceLevels -- TRC_SMP
11-18 19:45:06.106  5686  5709 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-18 19:45:06.106  5686  5709 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-18 19:45:06.189  5686  5709 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f39549
,11-18 19:45:06.189  5686  5709 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f39549 
,11-18 19:45:06.202  5686  5702 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-18 19:45:06.205  5686  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-18 19:45:06.205  5686  5702 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-18 19:45:06.207  5686  5702 D BluetoothAdapterProperties: Name is: Nexus 6P
11-18 19:45:06.209  5686  5702 D BluetoothAdapterProperties: Scan Mode:20
11-18 19:45:06.210  5686  5702 D BluetoothAdapterProperties: Discoverable Timeout:120
11-18 19:45:06.210  5686  5702 D bt_hci  : do_postload posting postload work item
11-18 19:45:06.210  5686  5706 I bt_hci  : event_postload
11-18 19:45:06.210  5686  5706 I bt_vendor: sco_config_cb
11-18 19:45:06.210  5686  5706 I bt_hci  : sco_config_callback postload finished.
,11-18 19:45:06.213  5686  5702 D bt_bte_conf: Device ID record 1 : primary
11-18 19:45:06.213  5686  5702 D bt_bte_conf:   vendorId            = 000f
11-18 19:45:06.213  5686  5702 D bt_bte_conf:   vendorIdSource      = 0001
11-18 19:45:06.213  5686  5702 D bt_bte_conf:   product             = 1200
11-18 19:45:06.213  5686  5702 D bt_bte_conf:   version             = 1436
11-18 19:45:06.213  5686  5702 D bt_bte_conf:   clientExecutableURL = 
11-18 19:45:06.213  5686  5702 D bt_bte_conf:   serviceDescription  = 
11-18 19:45:06.214  5686  5702 D bt_bte_conf:   documentationURL    = 
11-18 19:45:06.214  5686  5702 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-18 19:45:06.214  5686  5699 D bt_stack_manager: event_start_up_stack finished
11-18 19:45:06.215  5686  5698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-18 19:45:06.215  5686  5698 D BluetoothAdapterProperties: Setting state to 15
11-18 19:45:06.215  5686  5698 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-18 19:45:06.217  5686  5698 I BluetoothAdapterState: Entering BleOnState
,11-18 19:45:06.219  5686  5706 I bt_vendor: low_power_mode_cb
,11-18 19:45:06.224  5686  5698 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-18 19:45:06.224  5686  5698 D BluetoothAdapterProperties: Setting state to 11
11-18 19:45:06.224  5686  5698 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-18 19:45:06.230  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@815e5ba
,11-18 19:45:06.231  5686  5686 D HeadsetService: Received start request. Starting profile...
11-18 19:45:06.236  5686  5686 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-18 19:45:06.237  5686  5686 D HeadsetStateMachine: make
,11-18 19:45:06.250  5686  5698 I BluetoothAdapterState: Entering PendingCommandState
,11-18 19:45:06.250  5686  5686 D HeadsetStateMachine: max_hf_connections = 1
,11-18 19:45:06.250  5686  5686 I bt_bluedroid: get_profile_interface handsfree
11-18 19:45:06.250  5686  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-18 19:45:06.250  5686  5702 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-18 19:45:06.255  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@815e5ba
,11-18 19:45:06.256  5686  5686 D A2dpService: Received start request. Starting profile...
,11-18 19:45:06.257  5686  5686 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-18 19:45:06.257  5686  5686 I bt_bluedroid: get_profile_interface avrcp
,11-18 19:45:06.265  5686  5686 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-18 19:45:06.265  5686  5686 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-18 19:45:06.265  5686  5686 D A2dpStateMachine: make
,11-18 19:45:06.266  5686  5686 I bt_bluedroid: get_profile_interface a2dp
,11-18 19:45:06.269  5686  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-18 19:45:06.269  5686  5716 D A2dpStateMachine: Enter Disconnected: -2
,11-18 19:45:06.270  5686  5686 I BluetoothHidServiceJni: classInitNative: succeeds
,11-18 19:45:06.271  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@815e5ba
,11-18 19:45:06.272  5686  5686 D HidService: Received start request. Starting profile...
11-18 19:45:06.273  5669  5669 D BluetoothInputDevice: Proxy object connected
11-18 19:45:06.273  5686  5686 I bt_bluedroid: get_profile_interface hidhost
11-18 19:45:06.273  5686  5686 D HidService: setHidService(): set to: null
11-18 19:45:06.273  5669  5669 D HidProfile: Bluetooth service connected
11-18 19:45:06.275  5686  5686 I BluetoothHealthServiceJni: classInitNative: succeeds
11-18 19:45:06.275  5686  5702 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f1a56d
11-18 19:45:06.275  5686  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-18 19:45:06.276  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@815e5ba
11-18 19:45:06.277  5686  5686 D HealthService: Received start request. Starting profile...
11-18 19:45:06.278  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 19:45:06.278  5686  5686 I bt_bluedroid: get_profile_interface health
,11-18 19:45:06.281  5686  5686 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-18 19:45:06.282  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@815e5ba
11-18 19:45:06.283  5686  5686 D PanService: Received start request. Starting profile...
11-18 19:45:06.284  5686  5686 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-18 19:45:06.284  5686  5686 I bt_bluedroid: get_profile_interface pan
11-18 19:45:06.284  5686  5702 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-18 19:45:06.286  5669  5669 D BluetoothPan: BluetoothPAN Proxy object connected
11-18 19:45:06.287  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@815e5ba
,11-18 19:45:06.287  5669  5669 D PanProfile: Bluetooth service connected
11-18 19:45:06.288  5686  5686 D BluetoothMapService: Received start request. Starting profile...
11-18 19:45:06.288  5686  5686 D BluetoothMapService: start()
11-18 19:45:06.290  5669  5669 D BluetoothMap: Proxy object connected
11-18 19:45:06.291  5669  5669 D MapProfile: Bluetooth service connected
11-18 19:45:06.291  5669  5669 D BluetoothMap: getConnectedDevices()
11-18 19:45:06.292  5686  5686 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-18 19:45:06.292  5669  5669 D BluetoothMap: Bluetooth is Not enabled
11-18 19:45:06.293  5686  5686 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-18 19:45:06.293  5686  5686 D BluetoothMapAppObserver: createReceiver()
,11-18 19:45:06.295  5686  5686 D BluetoothMapAppObserver: initObservers()
11-18 19:45:06.296  5686  5686 D BluetoothMapAppObserver: getEnabledAccountItems()
11-18 19:45:06.303  5686  5686 V SapService: SapBinder()
11-18 19:45:06.303  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@815e5ba
11-18 19:45:06.304  5686  5686 D SapService: Received start request. Starting profile...
11-18 19:45:06.304  5686  5686 V SapService: start()
11-18 19:45:06.305  5686  5686 V BluetoothAdapterState: isTurningOff()=false
11-18 19:45:06.305  5686  5686 V BluetoothAdapterState: isTurningOn()=true
11-18 19:45:06.305  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:06.305  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:45:06.306  5686  5686 V BluetoothAdapterState: isTurningOff()=false
11-18 19:45:06.306  5686  5686 V BluetoothAdapterState: isTurningOn()=true
11-18 19:45:06.306  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:06.306  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:45:06.306  5686  5714 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
11-18 19:45:06.306  5686  5686 V BluetoothAdapterState: isTurningOff()=false
11-18 19:45:06.306  5686  5686 V BluetoothAdapterState: isTurningOn()=true
11-18 19:45:06.306  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:06.306  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:45:06.306  5686  5686 V BluetoothAdapterState: isTurningOff()=false
11-18 19:45:06.306  5686  5686 V BluetoothAdapterState: isTurningOn()=true
11-18 19:45:06.306  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:06.306  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:45:06.307  5686  5686 V BluetoothAdapterState: isTurningOff()=false
11-18 19:45:06.307  5686  5686 V BluetoothAdapterState: isTurningOn()=true
11-18 19:45:06.307  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:06.307  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:45:06.307  5686  5686 V BluetoothAdapterState: isTurningOff()=false
11-18 19:45:06.307  5686  5686 V BluetoothAdapterState: isTurningOn()=true
11-18 19:45:06.307  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:06.307  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:45:06.309  5686  5686 V BluetoothAdapterState: isTurningOff()=false
11-18 19:45:06.309  5686  5686 V BluetoothAdapterState: isTurningOn()=true
11-18 19:45:06.309  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:45:06.309  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:45:06.309  5686  5698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-18 19:45:06.309  5686  5698 D BluetoothAdapterProperties: ScanMode =  20
11-18 19:45:06.309  5686  5698 D BluetoothAdapterProperties: State =  11
11-18 19:45:06.309  5686  5698 D BluetoothAdapterProperties: Setting state to 12
11-18 19:45:06.310  5686  5698 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-18 19:45:06.310  5686  5702 D BluetoothAdapterProperties: Scan Mode:21
11-18 19:45:06.310  5686  5698 I BluetoothAdapterState: Entering OnState
11-18 19:45:06.310   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 19:45:06.311  5686  5702 D BluetoothAdapterProperties: Discoverable Timeout:120
11-18 19:45:06.311  3152  3163 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 19:45:06.314   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 19:45:06.315  3152  3165 D BluetoothPan: onBluetoothStateChange on: true
11-18 19:45:06.315  3152  3152 D BluetoothA2dp: Proxy object connected
11-18 19:45:06.318   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 19:45:06.319   927   927 D BluetoothA2dp: Proxy object connected
11-18 19:45:06.319  3789  3819 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 19:45:06.319   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 19:45:06.319  3152  3152 D BluetoothPan: BluetoothPAN Proxy object connected
11-18 19:45:06.319  3152  4000 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-18 19:45:06.319  3152  3152 D PanProfile: Bluetooth service connected
11-18 19:45:06.321  3152  3152 D BluetoothInputDevice: Proxy object connected
11-18 19:45:06.321  3152  3163 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 19:45:06.321  3152  3152 D HidProfile: Bluetooth service connected
11-18 19:45:06.321  5669  5680 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-18 19:45:06.322  5686  5686 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-18 19:45:06.322  3152  3165 D BluetoothPbap: onBluetoothStateChange: up=true
11-18 19:45:06.322  5686  5686 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-18 19:45:06.324  5669  5679 D BluetoothMap: onBluetoothStateChange: up=true
,11-18 19:45:06.324  5686  5686 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:45:06.324  3152  4000 D BluetoothMap: onBluetoothStateChange: up=true
11-18 19:45:06.326  3152  3152 D BluetoothMap: Proxy object connected
11-18 19:45:06.326  3152  3152 D MapProfile: Bluetooth service connected
11-18 19:45:06.326  5669  5680 D BluetoothPbap: onBluetoothStateChange: up=true
11-18 19:45:06.326  3152  3152 D BluetoothMap: getConnectedDevices()
,11-18 19:45:06.327  5686  5686 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 19:45:06.327  5597  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-18 19:45:06.327  5669  5679 D BluetoothPan: onBluetoothStateChange on: true
11-18 19:45:06.328  5597  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 19:45:06.328  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:45:06.328  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 19:45:06.328  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 19:45:06.328  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 19:45:06.328  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 19:45:06.328  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 19:45:06.328  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 19:45:06.328  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 19:45:06.328  5686  5686 D ObexServerSockets: Succeed to create listening sockets 
11-18 19:45:06.328  5686  5686 D ObexServerSockets0: startAccept()
11-18 19:45:06.328  5686  5686 D ObexServerSockets0: prepareForNewConnect()
11-18 19:45:06.329  5597  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 19:45:06.329   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-18 19:45:06.331  5597  5644 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-18 19:45:06.331  5686  5686 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-18 19:45:06.332  5686  5686 D BluetoothSdpJni: SDP Create record success - handle: 0
11-18 19:45:06.332  5686  5686 D BluetoothMapService: onReceive
11-18 19:45:06.332  5686  5723 D ObexServerSockets0: Accepting socket connection...
11-18 19:45:06.332  5686  5686 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-18 19:45:06.332  5686  5686 D BluetoothMapService: STATE_ON
11-18 19:45:06.333   927  3166 D WifiService: setWifiEnabled: false pid=5597, uid=10077
,11-18 19:45:06.333   927  3166 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 19:45:06.334  5597  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 19:45:06.335   927  2983 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-18 19:45:06.335   927  2983 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-18 19:45:06.335   927  2983 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-18 19:45:06.335   927  2983 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-18 19:45:06.336  5686  5724 D ObexServerSockets0: Accepting socket connection...
11-18 19:45:06.337  5686  5725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:45:06.337  5669  5669 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-18 19:45:06.338  5686  5725 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-18 19:45:06.338  5686  5725 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-18 19:45:06.343  5669  5669 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-18 19:45:06.346   927  5367 D DhcpClient: Clearing IP address
11-18 19:45:06.346   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-18 19:45:06.352  5686  5686 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-18 19:45:06.352  5686  5686 D ObexServerSockets0: prepareForNewConnect()
,11-18 19:45:06.353  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 19:45:06.353   507   920 D CommandListener: Setting iface cfg
11-18 19:45:06.357  3589  5421 V NativeCrypto: Read error: ssl=0x7f92585700: I/O error during system call, Connection timed out
11-18 19:45:06.357   927  2985 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-18 19:45:06.357   927  2985 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-18 19:45:06.358  3589  5421 V NativeCrypto: SSL shutdown failed: ssl=0x7f92585700: I/O error during system call, Broken pipe
11-18 19:45:06.358  5669  5669 D BluetoothA2dp: Proxy object connected
11-18 19:45:06.360   533   533 E Parcel  : Reading a NULL string not supported here.
11-18 19:45:06.363   927   927 D RttService: SCAN_AVAILABLE : 1
11-18 19:45:06.363   927  3092 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-18 19:45:06.367  5669  5669 D DockEventReceiver: finishStartingService: stopping service
11-18 19:45:06.367  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 19:45:06.371   927  2985 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-18 19:45:06.372   927  5368 D DhcpClient: Receive thread stopped
,11-18 19:45:06.373  3760  3894 W QCNEJ   : |CORE| network lost: 100
11-18 19:45:06.373  3760  3894 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-18 19:45:06.374  5669  5669 D BluetoothPbap: Proxy object connected
11-18 19:45:06.374  5669  5669 D PbapServerProfile: Bluetooth service connected
,11-18 19:45:06.379  5686  5731 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 19:45:06.387  3152  3152 D BluetoothPbap: Proxy object connected
11-18 19:45:06.387  3152  3152 D PbapServerProfile: Bluetooth service connected
,11-18 19:45:06.391   927  2983 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-18 19:45:06.399   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-18 19:45:06.400   927  2983 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-18 19:45:06.402  5686  5741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 19:45:06.404  5686  5741 I BtOppRfcommListener: Accept thread started.
,11-18 19:45:06.412  3789  3819 D BluetoothHeadset: Proxy object connected
11-18 19:45:06.412   927   927 D BluetoothHeadset: Proxy object connected
,11-18 19:45:06.413  3152  3165 D BluetoothHeadset: Proxy object connected
11-18 19:45:06.413  3152  3152 D HeadsetProfile: Bluetooth service connected
11-18 19:45:06.413   927   927 D BluetoothHeadset: Proxy object connected
11-18 19:45:06.413   927   927 D BluetoothHeadset: Proxy object connected
,11-18 19:45:06.415   927   944 D BluetoothHeadset: Proxy object connected
,11-18 19:45:06.418   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 19:45:06.419   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-18 19:45:06.419  3789  4006 D BluetoothHeadset: Proxy object connected
11-18 19:45:06.419   507   920 D TetherController: Setting IP forward enable = 0
11-18 19:45:06.419   927  2985 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-18 19:45:06.420   927  2985 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-18 19:45:06.420   927   944 D BluetoothHeadset: Proxy object connected
11-18 19:45:06.422  3152  4002 D BluetoothHeadset: Proxy object connected
11-18 19:45:06.423  3152  3152 D HeadsetProfile: Bluetooth service connected
11-18 19:45:06.428   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-18 19:45:06.434  3985  3985 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-18 19:45:06.425  5248  5248 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1c5ce0f and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-18 19:45:06.437  5038  5062 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-18 19:45:06.437  5038  5062 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-18 19:45:06.437  5038  5062 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-18 19:45:06.439  3851  3851 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-18 19:45:06.442  5038  5062 E SarControlService: no key has been found,reset the power
11-18 19:45:06.442  5038  5075 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 19:45:06.442  5038  5075 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 19:45:06.442  5038  5075 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-18 19:45:06.443  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 19:45:06.443  5063  5063 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-18 19:45:06.444  5038  5075 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-18 19:45:06.444  5038  5075 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-18 19:45:06.444  5038  5075 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-18 19:45:06.445  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 19:45:06.445  5669  5679 D BluetoothHeadset: Proxy object connected
11-18 19:45:06.446  5669  5669 D HeadsetProfile: Bluetooth service connected
11-18 19:45:06.447  5063  5077 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cc41f2d HexData = [00000000ea03000000000000ffffffff]
11-18 19:45:06.447  5063  5077 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 19:45:06.447  5063  5077 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-18 19:45:06.449  5063  5063 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-18 19:45:06.452  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 19:45:06.453  5038  5048 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-18 19:45:06.454  3851  3851 D SystemUpdateService: onCreate
11-18 19:45:06.457  3851  3851 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-18 19:45:06.460  5063  5077 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cc41f2d HexData = [00000000eb03000000000000ffffffff]
,11-18 19:45:06.460  5063  5077 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 19:45:06.460  5063  5077 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-18 19:45:06.461  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 19:45:06.461  5038  5049 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-18 19:45:06.466  3851  3851 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-18 19:45:06.469   507   920 E Netd    : netlink response contains error (No such file or directory)
,11-18 19:45:06.470   507   920 D TetherController: Setting IP forward enable = 0
11-18 19:45:06.471  3851  5752 I SystemUpdateService: active receiver: enabled
11-18 19:45:06.471   927  2985 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-18 19:45:06.471   927  2983 D DhcpClient: doQuit
11-18 19:45:06.471   927  2983 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-18 19:45:06.472   927  5367 D DhcpClient: onQuitting
,11-18 19:45:06.473  3851  5393 I iu.UploadsManager: num queued entries: 0
,11-18 19:45:06.473  3450  3450 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-18 19:45:06.473  3851  5393 I iu.UploadsManager: num updated entries: 0
11-18 19:45:06.474  3851  5393 I iu.SyncManager: NEXT; no task
,11-18 19:45:06.476  3851  3851 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-18 19:45:06.478  3851  3851 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-18 19:45:06.481  3851  5752 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-18 19:45:06.482  3851  5752 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-18 19:45:06.482  3851  5752 I SystemUpdateService: now status is 0 (complete)
,11-18 19:45:06.482  3851  5752 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-18 19:45:06.482  3851  5752 I SystemUpdateService: file has been verified
11-18 19:45:06.483  3851  5752 I SystemUpdateService: OTA package size = 21989297
11-18 19:45:06.488  3851  5752 I SystemUpdateService: showing system update notification
11-18 19:45:06.489   927  3841 I ActivityManager: Start proc 5756:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
11-18 19:45:06.493  3450  3450 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-18 19:45:06.499  3450  3450 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-18 19:45:06.500   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-18 19:45:06.502  3851  3851 D SystemUpdateService: onDestroy
,11-18 19:45:06.531  3450  3450 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-18 19:45:06.535  5756  5756 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-18 19:45:06.537  5756  5756 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-18 19:45:06.542  3450  3450 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-18 19:45:06.544  5756  5756 D SprintDMHelper: simOperator: 
,11-18 19:45:06.544  5756  5756 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 19:45:06.552  4987  5768 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-18 19:45:06.570   927   937 I ActivityManager: Start proc 5769:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-18 19:45:06.572   927   937 I ActivityManager: Killing 5248:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-18 19:45:06.608  5769  5769 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-18 19:45:06.615   927  3862 I ActivityManager: Killing 3903:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-18 19:45:06.644   927  2983 D wifi    : In wifi stop Hal
11-18 19:45:06.644   927  2983 D wifi    : halHandle = 0x7f9035e300, mVM = 0x7fac94d140, mCls = 0x100a02
11-18 19:45:06.644   927  3449 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-18 19:45:06.644   927  3449 D WifiHAL : Got a signal to exit!!!
11-18 19:45:06.644   927  3449 I WifiHAL : Exit wifi_event_loop
11-18 19:45:06.645   927  2983 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-18 19:45:06.645   927  2983 E WifiHAL : Event processing terminated
11-18 19:45:06.645   927  2983 D wifi    : In wifi cleaned up handler
11-18 19:45:06.645   927  2983 I WifiHAL : Internal cleanup completed
,11-18 19:45:06.647  4078  4231 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-18 19:45:06.648  4987  4987 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-18 19:45:06.667   927  3449 D wifi    : set interface wlan0 flags (DOWN)
,11-18 19:45:06.667   927  2983 D WifiNative-HAL: HAL event thread stopped successfully
,11-18 19:45:06.844  5597  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 19:45:06.844  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:45:06.844  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 19:45:06.844  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-18 19:45:06.844  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 19:45:06.844  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 19:45:06.844  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 19:45:06.844  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 19:45:06.844  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 19:45:06.850  5597  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 19:45:06.854   927  3422 D WifiService: setWifiEnabled: true pid=5597, uid=10077
,11-18 19:45:06.854   927  3422 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 19:45:06.856  5597  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 19:45:06.872   507   920 D SoftapController: Softap fwReload - Ok
,11-18 19:45:06.873   927   944 D Tethering: InitialState.processMessage what=4
,11-18 19:45:06.877   507   920 D CommandListener: Setting iface cfg
,11-18 19:45:06.877   507   920 D CommandListener: Trying to bring down wlan0
11-18 19:45:06.879   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-18 19:45:06.880   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-18 19:45:06.886   927  2983 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-18 19:45:07.360   927   937 D WifiService: setWifiEnabled: true pid=5597, uid=10077
,11-18 19:45:07.360   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 19:45:07.484   927  2983 D wifi    : set interface wlan0 flags (UP)
,11-18 19:45:07.484   927  2983 I WifiHAL : Initializing wifi
11-18 19:45:07.485   927  2983 I WifiHAL : Creating socket
11-18 19:45:07.492   927  2983 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-18 19:45:07.492   927  2983 D wifi    : Did set static halHandle = 0x7f9035e300
11-18 19:45:07.493   927  2983 D wifi    : halHandle = 0x7f9035e300, mVM = 0x7fac94d140, mCls = 0x189a
11-18 19:45:07.493   927  2983 D wifi    : array field set
11-18 19:45:07.493   927  2983 I WifiNative-HAL: interface[0] = wlan0
,11-18 19:45:07.492   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-18 19:45:07.496   927  5785 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547880297216
11-18 19:45:07.497   927  5785 D wifi    : waitForHalEvents called, vm = 0x7fac94d140, obj = 0x189a, env = 0x7f923c3a40
,11-18 19:45:07.561  5786  5786 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-18 19:45:07.598   927  2983 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-18 19:45:07.627  5786  5786 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 19:45:07.660  5786  5786 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 19:45:07.660  5786  5786 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-18 19:45:07.673   927  2983 D WifiConfigStore: Loading config and enabling all networks 
,11-18 19:45:07.686   927  2983 D WifiConfigStore: loaded 0 passpoint configs
,11-18 19:45:07.687   927  2983 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-18 19:45:07.687   927  2983 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-18 19:45:07.688   927  2983 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-18 19:45:07.688   927  2983 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-18 19:45:07.688   927  2983 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-18 19:45:07.689   927  2983 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-18 19:45:07.689   927  2983 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-18 19:45:07.689   927  2983 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-18 19:45:07.689   927  2983 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-18 19:45:07.689   927  2983 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-18 19:45:07.689   927  2983 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-18 19:45:07.689   927  2983 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-18 19:45:07.692   927  2983 D WifiNative-HAL: Setting external_sim to 1
,11-18 19:45:07.692   927  2983 D wifi    : setting dfs flag to true, 0x7f95254bc0
11-18 19:45:07.692   927  2983 D WifiStateMachine: Setting OUI to DA-A1-19
,11-18 19:45:07.693   927  2983 D wifi    : setting scan oui 0x7f95254bc0
11-18 19:45:07.693   927  2983 D WifiHAL : Sending mac address OUI
,11-18 19:45:07.693  4987  4987 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-18 19:45:07.695   927  2983 E native  : do suspend false
,11-18 19:45:07.702   927  2983 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-18 19:45:07.702   927   927 D RttService: SCAN_AVAILABLE : 3
11-18 19:45:07.703   927  3092 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-18 19:45:07.712   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-18 19:45:07.715   507   920 D CommandListener: Setting iface cfg
,11-18 19:45:07.717   927  2982 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
11-18 19:45:07.718   927  2982 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-18 19:45:07.718   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=106389 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=10 mControllerEnergyUsed=38 }
,11-18 19:45:07.722   927  2982 D WifiNative-HAL: p2pGetDeviceAddress
11-18 19:45:07.722   927  2982 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-18 19:45:07.870  5597  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 19:45:07.870  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:45:07.870  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 19:45:07.870  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 19:45:07.870  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 19:45:07.870  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 19:45:07.870  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 19:45:07.870  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 19:45:07.870  5597  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 19:45:07.878  5597  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 19:45:07.882  5597  5644 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 19:45:07.883   927  3132 D WifiService: setWifiEnabled: true pid=5597, uid=10077
,11-18 19:45:07.883   927  3132 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 19:45:07.884  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 19:45:07.884  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:45:07.884  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 19:45:07.884  5597  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b11325 removed from the list
,11-18 19:45:07.885  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 19:45:07.885  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d89cfa removed from the list
11-18 19:45:07.885  5597  5644 D io.jxcore.node.ConnectivityMonitor: stop
11-18 19:45:07.888  5597  5644 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-18 19:45:07.890  5597  5644 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-18 19:45:07.892  5597  5644 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-18 19:45:07.894  5597  5644 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-18 19:45:07.898  5597  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-18 19:45:07.899  5597  5644 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-18 19:45:07.901  5597  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-18 19:45:07.901  5597  5644 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-18 19:45:07.902  5597  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-18 19:45:07.906  5597  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-18 19:45:07.906  5597  5644 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f062c61 Bundle[{}]
,11-18 19:45:07.907  5597  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,11-18 19:45:07.908  5597  5644 I io.jxcore.node.LifeCycleMonitor: start: OK
11-18 19:45:07.908  5597  5644 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-18 19:45:07.909  5597  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-18 19:45:07.909  5597  5644 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-18 19:45:07.910  5597  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-18 19:45:07.910  5597  5644 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-18 19:45:07.910  5597  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-18 19:45:07.910  5597  5644 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-18 19:45:07.911  5597  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-18 19:45:07.912  5597  5644 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-18 19:45:07.913  5597  5644 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-18 19:45:07.915  5597  5644 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-18 19:45:07.916  5597  5644 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-18 19:45:07.917  5597  5644 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-18 19:45:07.917  5597  5644 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-18 19:45:07.918  5597  5644 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-18 19:45:07.920  5597  5644 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-18 19:45:07.922  5597  5644 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-18 19:45:07.923  5597  5644 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-18 19:45:07.925  5597  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
11-18 19:45:07.926  5597  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-18 19:45:07.927  5597  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-18 19:45:07.927  5597  5644 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
11-18 19:45:07.927  5597  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-18 19:45:07.927  5597  5644 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-18 19:45:07.928  5597  5644 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-18 19:45:07.928  5597  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-18 19:45:07.929  5597  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-18 19:45:07.929  5597  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-18 19:45:07.930  5597  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-18 19:45:07.930  5597  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56dd08 added. We now have 3 listener(s)
11-18 19:45:07.931  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:45:07.931  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 19:45:07.931  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 19:45:07.931  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 19:45:07.931  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@884bca1 added. We now have 3 listener(s)
11-18 19:45:07.931  5597  5644 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 19:45:07.932  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 19:45:07.937  5597  5644 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-18 19:45:07.938  5597  5644 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-18 19:45:07.938  5597  5644 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-18 19:45:07.938  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-18 19:45:07.938  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.938  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.938  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:07.938  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-18 19:45:07.939  5597  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 19:45:07.939  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 19:45:07.939  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:45:07.939  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 19:45:07.941  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 19:45:07.942  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-18 19:45:07.942  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 19:45:07.942  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 19:45:07.942  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 19:45:07.942  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 19:45:07.942  5597  5789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 19:45:07.942  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:45:07.942  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 19:45:07.943  5597  5597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-18 19:45:07.943  5597  5789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 19:45:07.944  5696  5696 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[34054]" dev="sockfs" ino=34054 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:45:07.946  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 19:45:07.947  5597  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 19:45:07.947  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 19:45:07.944  5696  5696 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[34054]" dev="sockfs" ino=34054 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:45:07.947  5597  5789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 19:45:07.950  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:07.950  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 19:45:07.951  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:45:07.951  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 19:45:07.951  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-18 19:45:07.954  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:07.954  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.954  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 19:45:07.954  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 19:45:07.954  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:45:07.954  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-18 19:45:07.954  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:45:07.954  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:45:07.954  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.954  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-18 19:45:07.955  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:45:07.955  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.955  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.955  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.956  5597  5644 D BluetoothAdapter: STATE_ON
,11-18 19:45:07.959  5686  5697 D BtGatt.GattService: registerClient() - UUID=63be0762-d3d8-40ea-ac57-5c447962350a
11-18 19:45:07.960  5686  5702 D BtGatt.GattService: onClientRegistered() - UUID=63be0762-d3d8-40ea-ac57-5c447962350a, clientIf=5
,11-18 19:45:07.960  5597  5608 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 19:45:07.962  5686  5704 D BtGatt.AdvertiseManager: message : 0
,11-18 19:45:07.964  5686  5704 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 19:45:07.967  5686  5702 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 19:45:07.969  5686  5702 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 19:45:07.969  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:07.970  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.970  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 19:45:07.970  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.970  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.970  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.970  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.970  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.970  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 19:45:07.971  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 19:45:07.971  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:07.972  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.972  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.972  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:07.973  5597  5597 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:45:07.973  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 19:45:07.973  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 19:45:07.973  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 19:45:07.973  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 19:45:07.973  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 19:45:07.973  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-18 19:45:07.973  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:45:07.974  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 19:45:07.974  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 19:45:07.974  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 19:45:07.974  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 19:45:07.974  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-18 19:45:07.974  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 19:45:07.977  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-18 19:45:07.977  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 19:45:07.977  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:45:07.977  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:45:07.977  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:45:07.977  5597  5597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 19:45:08.479  5597  5597 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-18 19:45:08.479  5597  5597 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 19:45:08.479  5597  5597 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 19:45:10.764  5786  5786 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 19:45:10.769  5786  5786 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 19:45:10.774  5786  5786 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 19:45:10.820   927  2983 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-18 19:45:10.821   927  2983 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-18 19:45:10.821   927  2983 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 19:45:10.833   927  2983 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-18 19:45:10.866   927  2983 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-18 19:45:10.871  5786  5786 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-18 19:45:11.291  5786  5786 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-18 19:45:11.325  5786  5786 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-18 19:45:11.326  5786  5786 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-18 19:45:11.336   927  2983 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-18 19:45:11.336   927  2983 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 19:45:11.336   927  2985 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-18 19:45:11.353   927  2983 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 19:45:11.364   507   920 D CommandListener: Setting iface cfg
,11-18 19:45:11.371   927  2983 D WifiStateMachine: Start Dhcp Watchdog 2
,11-18 19:45:11.377   927  5794 D DhcpClient: Receive thread started
,11-18 19:45:11.381   927  2985 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 19:45:11.381   927  2983 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-18 19:45:11.381   927  2985 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-18 19:45:11.462   927  2983 E native  : do suspend false
,11-18 19:45:11.475  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-18 19:45:11.475  5597  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 19:45:11.475  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 19:45:11.475  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-18 19:45:11.475  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 19:45:11.476  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 19:45:11.476  5597  5789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 19:45:11.476  5597  5789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 19:45:11.476  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-18 19:45:11.476  5597  5789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 19:45:11.476  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 19:45:11.477  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 19:45:11.477  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 19:45:11.477  5597  5597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 19:45:11.477  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-18 19:45:11.477  5597  5597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:45:11.477  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 19:45:11.477   927  5793 D DhcpClient: Broadcasting DHCPDISCOVER
,11-18 19:45:11.477  5597  5597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-18 19:45:11.477  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.477  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.477  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.478  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:11.480  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:45:11.481  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 19:45:11.483  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:45:11.483  5597  5644 D BluetoothLeScanner: could not find callback wrapper
,11-18 19:45:11.483  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 19:45:11.483  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.484  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.484  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.484  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-18 19:45:11.484  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.486  5686  5704 D BtGatt.AdvertiseManager: message : 1
11-18 19:45:11.488  5686  5704 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 19:45:11.496   927  5794 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172731, domain null
11-18 19:45:11.497   927  5793 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172731 seconds
,11-18 19:45:11.499   927  5793 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
11-18 19:45:11.504  5686  5702 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 19:45:11.504  5686  5702 D BtGatt.GattService: Client app is not null!
11-18 19:45:11.505  5686  5722 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 19:45:11.506  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 19:45:11.506  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.506  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 19:45:11.506  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:11.507  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.507  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.507  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 19:45:11.507  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 19:45:11.508  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-18 19:45:11.509  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.510   927  5794 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-18 19:45:11.511   927  5793 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-18 19:45:11.513  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.513  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:45:11.513  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.513  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:11.514  5597  5597 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 19:45:11.514  5597  5597 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 19:45:11.514  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:45:11.514  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:45:11.514   507   920 D CommandListener: Setting iface cfg
11-18 19:45:11.514  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 19:45:11.514  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 19:45:11.514  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 19:45:11.515  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 19:45:11.515  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:45:11.515  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-18 19:45:11.515  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-18 19:45:11.516  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:45:11.518   927  2983 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
11-18 19:45:11.519  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-18 19:45:11.519  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:45:11.519  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:45:11.519  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:45:11.519  5597  5597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 19:45:11.521   927  5793 D DhcpClient: Scheduling renewal in 86399s
,11-18 19:45:11.525  5597  5644 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-18 19:45:11.525  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 19:45:11.526  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-18 19:45:11.526  5597  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-18 19:45:11.526  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-18 19:45:11.526  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:45:11.526  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-18 19:45:11.528  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-18 19:45:11.529   927  2983 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-18 19:45:11.530   927  2983 D WifiConfigStore: No blacklist allowed without epno enabled
,11-18 19:45:11.531   927  2985 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-18 19:45:11.533  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-18 19:45:11.533  5597  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 19:45:11.533  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 19:45:11.535   927  2985 D ConnectivityService: Adding iface wlan0 to network 101
11-18 19:45:11.538   927  2983 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-18 19:45:11.538  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.539  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 19:45:11.540  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:45:11.540  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 19:45:11.540  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-18 19:45:11.543  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-18 19:45:11.546  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-18 19:45:11.546  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.546  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 19:45:11.546  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 19:45:11.546  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-18 19:45:11.547  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-18 19:45:11.547  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:11.548  5597  5644 D BluetoothAdapter: STATE_ON
,11-18 19:45:11.551  5686  5697 D BtGatt.GattService: registerClient() - UUID=aae2213e-a7d4-4038-b866-efdc5392f15e
,11-18 19:45:11.551  5686  5702 D BtGatt.GattService: onClientRegistered() - UUID=aae2213e-a7d4-4038-b866-efdc5392f15e, clientIf=5
,11-18 19:45:11.552  5597  5607 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-18 19:45:11.554  5686  5696 D BtGatt.GattService: start scan with filters
11-18 19:45:11.558  5686  5705 D BtGatt.ScanManager: handling starting scan
11-18 19:45:11.560  5686  5705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@815e5ba
11-18 19:45:11.561  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-18 19:45:11.561  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.561  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-18 19:45:11.561  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.562  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:45:11.562  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 19:45:11.562  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 19:45:11.562  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 19:45:11.562  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 19:45:11.562  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:45:11.562  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-18 19:45:11.563  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-18 19:45:11.563  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 19:45:11.563  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.565  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.566  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-18 19:45:11.566  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.566  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:11.566  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:45:11.566  5686  5702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-18 19:45:11.566  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:45:11.567  5686  5705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-18 19:45:11.570  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:45:11.570  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:45:11.570  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:45:11.570  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:45:11.570  5597  5597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-18 19:45:11.573  5686  5702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-18 19:45:11.573  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:45:11.574  5686  5705 D BtGatt.ScanManager: Starting BLE batch scan
11-18 19:45:11.574  5686  5705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-18 19:45:11.581   927  2985 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-18 19:45:11.581   927  2985 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-18 19:45:11.582   927  2985 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-18 19:45:11.583   927  2985 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-18 19:45:11.584   927  2985 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
11-18 19:45:11.588  5686  5702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-18 19:45:11.588  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:45:11.589   927  2985 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-18 19:45:11.594  5686  5702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-18 19:45:11.594  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:45:11.595   927  2985 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-18 19:45:11.595   927  2985 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-18 19:45:11.595   927  2985 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-18 19:45:11.595   927  2985 D ConnectivityService:    accepting network in place of null
,11-18 19:45:11.595   927  2983 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-18 19:45:11.596   927  2983 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-18 19:45:11.596   927  2985 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -56]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-18 19:45:11.617   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 19:45:11.635   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 19:45:11.638   927  2985 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-18 19:45:11.638   927  2985 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-18 19:45:11.638  3760  3894 W QCNEJ   : |CORE| network available: 101
11-18 19:45:11.639   927  2985 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-18 19:45:11.640   927   944 D Tethering: MasterInitialState.processMessage what=3
11-18 19:45:11.641  3760  3894 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-18 19:45:11.643  3760  3894 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-18 19:45:11.643  3760  3894 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-18 19:45:11.648  5038  5062 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-18 19:45:11.651  5038  5062 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-18 19:45:11.651  5038  5062 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-18 19:45:11.651  5038  5062 E SarControlService: no key has been found,reset the power
11-18 19:45:11.651  5038  5075 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 19:45:11.652  5038  5075 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 19:45:11.652  5038  5075 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 19:45:11.652  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 19:45:11.652  5063  5063 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-18 19:45:11.653  5038  5075 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-18 19:45:11.653  5038  5075 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-18 19:45:11.653  5038  5075 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-18 19:45:11.654  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 19:45:11.654  5063  5063 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-18 19:45:11.655  3985  3985 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-18 19:45:11.658  3851  3851 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-18 19:45:11.659  5063  5077 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cc41f2d HexData = [00000000ec03000000000000ffffffff]
11-18 19:45:11.660  5063  5077 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 19:45:11.660  5063  5077 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-18 19:45:11.660  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 19:45:11.660  5038  5048 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-18 19:45:11.662  5063  5077 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cc41f2d HexData = [00000000ed03000000000000ffffffff]
11-18 19:45:11.662  5063  5077 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-18 19:45:11.662  5063  5077 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-18 19:45:11.663  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 19:45:11.663  5038  5049 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-18 19:45:11.663  3851  3851 D SystemUpdateService: onCreate
,11-18 19:45:11.668  3851  3851 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-18 19:45:11.677  3851  3851 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-18 19:45:11.682  3851  5393 I iu.UploadsManager: num queued entries: 0
,11-18 19:45:11.682  3851  5393 I iu.UploadsManager: num updated entries: 0
11-18 19:45:11.683  3851  5393 I iu.SyncManager: NEXT; no task
,11-18 19:45:11.686  3851  5805 I SystemUpdateService: active receiver: enabled
,11-18 19:45:11.689  3851  3851 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-18 19:45:11.690  3851  3851 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-18 19:45:11.692  5756  5756 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-18 19:45:11.695  5756  5756 D SprintDMHelper: simOperator: 
11-18 19:45:11.695  5756  5756 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 19:45:11.717   927  5792 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110388, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-18 19:45:11.718  3851  5805 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-18 19:45:11.733  3851  5805 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-18 19:45:11.733  3851  5805 I SystemUpdateService: now status is 0 (complete)
11-18 19:45:11.733  3851  5805 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-18 19:45:11.734  3851  5805 I SystemUpdateService: file has been verified
11-18 19:45:11.734  3851  5805 I SystemUpdateService: OTA package size = 21989297
,11-18 19:45:11.740  3851  5805 I SystemUpdateService: showing system update notification
,11-18 19:45:11.747   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-18 19:45:11.749  3851  3851 D SystemUpdateService: onDestroy
,11-18 19:45:11.822   927  5791 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-18 19:45:11.824  4987  5810 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-18 19:45:11.901   927  5791 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Nov 2016 18:45:11 GMT], X-Android-Received-Millis=[1479494711899], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479494711872]}
,11-18 19:45:11.902   927  2985 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-18 19:45:11.902   927  2985 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-18 19:45:11.903   927  2985 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 19:45:11.908   927  2985 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-18 19:45:12.072  5597  5597 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-18 19:45:12.072  5597  5597 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 19:45:12.072  5597  5597 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 19:45:12.097  5686  5686 D BtGatt.ScanManager: awakened up at time 110768
,11-18 19:45:12.099  5686  5705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 19:45:12.114  5686  5702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 19:45:12.114  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:45:12.117  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-18 19:45:12.640   927  2985 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-18 19:45:14.395   927  2985 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 19:45:14.568  5597  5644 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-18 19:45:14.569  5597  5644 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,11-18 19:45:14.569  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-18 19:45:14.570  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.570  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.570  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.571  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 19:45:14.571  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 19:45:14.571  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 19:45:14.571  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-18 19:45:14.571  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 19:45:14.571  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 19:45:14.571  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 19:45:14.571  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 19:45:14.571  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 19:45:14.571  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.571  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
,11-18 19:45:14.571  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.571  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.571  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 19:45:14.571  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:45:14.572  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.572  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.572  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:14.575  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:45:14.576  5686  5722 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 19:45:14.577  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 19:45:14.578  5686  5705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 19:45:14.578  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:45:14.580  5686  5696 D BtGatt.GattService: stopScan() - queue size =1
,11-18 19:45:14.582  5686  5721 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 19:45:14.583  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 19:45:14.584  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.584  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-18 19:45:14.584  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.584  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 19:45:14.584  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.585  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.585  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 19:45:14.585  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 19:45:14.586  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-18 19:45:14.586  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-18 19:45:14.586  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:14.588  5597  5644 D BluetoothAdapter: STATE_ON
,11-18 19:45:14.590  5686  5686 D BtGatt.ScanManager: awakened up at time 113261
,11-18 19:45:14.592  5686  5721 D BtGatt.GattService: registerClient() - UUID=1c4d7cb9-6eeb-4306-a3c5-5c15b9403d62
11-18 19:45:14.593  5686  5702 D BtGatt.GattService: onClientRegistered() - UUID=1c4d7cb9-6eeb-4306-a3c5-5c15b9403d62, clientIf=5
11-18 19:45:14.593  5597  5608 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-18 19:45:14.594  5686  5722 D BtGatt.GattService: start scan with filters
,11-18 19:45:14.598  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-18 19:45:14.599  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.599  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-18 19:45:14.599  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:14.599  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.599  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:45:14.600  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 19:45:14.600  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:45:14.600  5597  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 19:45:14.600  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 19:45:14.600  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 19:45:14.600  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:45:14.600  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-18 19:45:14.600  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:45:14.600  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-18 19:45:14.602  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 19:45:14.602  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 19:45:14.602  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 19:45:14.603  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-18 19:45:14.603  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 19:45:14.603  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-18 19:45:14.603  5597  5597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 19:45:14.603  5597  5817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 19:45:14.604  5686  5702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-18 19:45:14.604  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:45:14.605  5686  5702 D BtGatt.GattService: current time is 113276574558
11-18 19:45:14.605  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-18 19:45:14.605  5597  5817 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:45:14.605  5597  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 19:45:14.605  5686  5702 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-18 19:45:14.608  5686  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-18 19:45:14.611  5597  5817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 19:45:14.608  5722  5722 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34113]" dev="sockfs" ino=34113 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:45:14.608  5722  5722 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34113]" dev="sockfs" ino=34113 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 19:45:14.615  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.615  5686  5702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-18 19:45:14.615  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:45:14.615  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.615  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:14.616  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-18 19:45:14.616  5686  5705 D BtGatt.ScanManager: stopping BLe Batch
,11-18 19:45:14.616  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 19:45:14.616  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:45:14.616  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-18 19:45:14.616  5597  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 19:45:14.616  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:45:14.616  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.616  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-18 19:45:14.617  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:45:14.617  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.617  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.617  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.618  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:45:14.621  5686  5722 D BtGatt.GattService: registerClient() - UUID=d03f23b0-7f05-4511-ae08-e8b6dff182f2
11-18 19:45:14.622  5686  5702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-18 19:45:14.622  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:45:14.622  5686  5702 D BtGatt.GattService: onClientRegistered() - UUID=d03f23b0-7f05-4511-ae08-e8b6dff182f2, clientIf=6
11-18 19:45:14.622  5686  5705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 19:45:14.623  5597  5608 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-18 19:45:14.624  5686  5704 D BtGatt.AdvertiseManager: message : 0
11-18 19:45:14.626  5686  5704 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 19:45:14.629  5686  5702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 19:45:14.629  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:45:14.632  5686  5705 D BtGatt.ScanManager: handling starting scan
,11-18 19:45:14.639  5686  5702 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-18 19:45:14.643  5686  5702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-18 19:45:14.643  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:45:14.643  5686  5705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-18 19:45:14.648  5686  5702 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-18 19:45:14.648  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:14.648  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.648  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 19:45:14.648  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.649  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.649  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.649  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:14.649  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.649  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:14.649  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.649  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.649  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-18 19:45:14.649  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
,11-18 19:45:14.649  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 19:45:14.650  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 19:45:14.651  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.653  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.654  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.654  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:14.654  5686  5702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-18 19:45:14.654  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:45:14.654  5686  5705 D BtGatt.ScanManager: Starting BLE batch scan
11-18 19:45:14.654  5686  5705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-18 19:45:14.655  5597  5597 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-18 19:45:14.655  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 1. Current thread: Thread[main,5,main], id: 1
11-18 19:45:14.656  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=111777317891}
11-18 19:45:14.656  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=111777317891}
11-18 19:45:14.657  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 61:7E:A4:16:C8:B6, provideBluetoothMacAddressRequestId = nullextra info = 35]
11-18 19:45:14.657  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-18 19:45:14.657  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 19:45:14.657  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-18 19:45:14.657  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 19:45:14.657  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 19:45:14.657  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 19:45:14.657  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:45:14.657  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:45:14.657  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-18 19:45:14.657  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-18 19:45:14.658  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 19:45:14.658  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 19:45:14.658  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-18 19:45:14.658  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 19:45:14.661  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-18 19:45:14.661  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-18 19:45:14.661  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:45:14.661  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:45:14.661  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:45:14.661  5597  5597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-18 19:45:14.667  5686  5702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-18 19:45:14.667  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:45:14.672  5686  5702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-18 19:45:14.672  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:45:15.162  5597  5597 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
11-18 19:45:15.163  5597  5597 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-18 19:45:15.163  5597  5597 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 19:45:15.422   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-18 19:45:15.423   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-18 19:45:17.657  5597  5644 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-18 19:45:17.658  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 19:45:17.658  5597  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 19:45:17.658  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 19:45:17.658  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 19:45:17.659  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-18 19:45:17.659  5597  5817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 19:45:17.659  5597  5817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 19:45:17.659  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 19:45:17.659  5597  5817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-18 19:45:17.659  5597  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 19:45:17.660  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 19:45:17.660  5597  5597 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 19:45:17.660  5597  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56dd08 removed from the list
,11-18 19:45:17.660  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 19:45:17.660  5597  5597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 19:45:17.660  5597  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 19:45:17.660  5597  5597 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:45:17.660  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 19:45:17.660  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 19:45:17.661  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.661  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.661  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:17.661  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-18 19:45:17.662  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.665  5597  5644 D BluetoothAdapter: STATE_ON
11-18 19:45:17.666  5686  5721 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 19:45:17.667  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-18 19:45:17.668  5686  5705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 19:45:17.670  5597  5644 D BluetoothAdapter: STATE_ON
,11-18 19:45:17.671  5686  5696 D BtGatt.GattService: stopScan() - queue size =1
11-18 19:45:17.673  5686  5721 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 19:45:17.674  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 19:45:17.674  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.674  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-18 19:45:17.674  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.675  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.675  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.675  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 19:45:17.675  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.677  5686  5704 D BtGatt.AdvertiseManager: message : 1
11-18 19:45:17.677  5686  5686 D BtGatt.ScanManager: awakened up at time 116348
11-18 19:45:17.677  5686  5704 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-18 19:45:17.691  5686  5702 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-18 19:45:17.691  5686  5702 D BtGatt.GattService: Client app is not null!
11-18 19:45:17.693  5686  5721 D BtGatt.GattService: unregisterClient() - clientIf=6
11-18 19:45:17.693  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 19:45:17.694  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 19:45:17.694  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 19:45:17.694  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.694  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.694  5597  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.694  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 19:45:17.694  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 19:45:17.695  5597  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 19:45:17.696  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.697  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.698  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:45:17.698  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.698  5597  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 19:45:17.698  5597  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@884bca1 removed from the list
11-18 19:45:17.698  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 19:45:17.698  5597  5644 D io.jxcore.node.ConnectivityMonitor: stop
11-18 19:45:17.698  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:45:17.698  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 19:45:17.699  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:45:17.699  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 19:45:17.699  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-18 19:45:17.699  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:45:17.699  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 19:45:17.699  5597  5597 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-18 19:45:17.699  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:45:17.699  5597  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-18 19:45:17.700  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-18 19:45:17.700  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-18 19:45:17.700  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 19:45:17.700  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 19:45:17.700  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-18 19:45:17.700  5597  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-18 19:45:17.701  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:45:17.701  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:45:17.701  5597  5597 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-18 19:45:17.701  5597  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-18 19:45:17.701  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:45:17.701  5597  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 19:45:17.701  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:45:17.701  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 19:45:17.701  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 19:45:17.701  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 19:45:17.701  5597  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:45:17.701  5597  5597 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:45:17.704  5597  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-18 19:45:17.705  5597  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,11-18 19:45:17.706  5597  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-18 19:45:17.706  5597  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-18 19:45:17.707  5597  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-18 19:45:17.708  5597  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-18 19:45:17.709  5597  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-18 19:45:17.719  5686  5702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-18 19:45:17.719  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:45:17.719  5686  5702 D BtGatt.GattService: current time is 116391224922
11-18 19:45:17.720  5686  5702 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -87, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -79, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -93, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -94, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -91, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-18 19:45:17.720  5686  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-18 19:45:17.720  5686  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-18 19:45:17.720  5686  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-18 19:45:17.720  5686  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-18 19:45:17.721  5686  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-18 19:45:17.726  5686  5702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-18 19:45:17.726  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:45:17.726  5686  5705 D BtGatt.ScanManager: stopping BLe Batch
,11-18 19:45:17.731  5686  5702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-18 19:45:17.731  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:45:17.732  5686  5705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 19:45:17.737  5686  5702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 19:45:17.737  5686  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:45:18.203  5597  5597 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 19:45:19.601   927  2985 D ConnectivityService: handlePromptUnvalidated 101
,11-18 19:45:19.714  5597  5644 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-18 19:45:19.869  5597  5819 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 19:45:19.869  5597  5819 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:45:20.423   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:20.687  5597  5819 W !!      : call onHalfStreamCopied
,11-18 19:45:20.688  5597  5819 I testCopyDataAndClose: closing input stream
,11-18 19:45:21.424   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:21.483  5597  5819 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 19:45:21.483  5597  5819 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 19:45:21.483  5597  5819 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 19:45:21.483  5597  5819 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:45:21.484  5597  5819 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 19:45:21.484  5597  5819 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 19:45:21.484  5597  5819 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-18 19:45:21.484  5597  5819 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 19:45:21.484  5597  5819 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 19:45:21.484  5597  5819 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 19:45:21.484  5597  5819 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 19:45:22.125   927  2983 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-18 19:45:22.426   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:22.720   927  2983 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-18 19:45:23.427   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:24.429   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:25.429   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-18 19:45:25.606  5597  5644 I StreamCopyingThreadTest: Starting test: testRun
,11-18 19:45:25.612  5597  5820 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:45:25.612  5597  5820 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:45:30.431   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:30.618  5597  5821 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-18 19:45:30.620  5597  5644 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-18 19:45:30.818  5597  5822 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 19:45:30.818  5597  5822 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:45:31.432   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:32.433   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:32.457  5597  5822 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 19:45:32.457  5597  5822 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:45:32.457  5597  5822 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 19:45:32.457  5597  5822 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 19:45:32.457  5597  5822 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 19:45:32.457  5597  5822 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 19:45:32.457  5597  5822 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 19:45:32.457  5597  5822 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 19:45:32.457  5597  5822 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-18 19:45:32.457  5597  5822 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 19:45:32.457  5597  5822 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 19:45:33.435   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:34.436   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:35.437   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-18 19:45:36.580  3667  3866 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-18 19:45:36.580  3667  3866 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-18 19:45:36.612  3589  3589 I ConfigService: onCreate
,11-18 19:45:36.617  5597  5644 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-18 19:45:36.619  5597  5824 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:45:36.619  5597  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:45:36.619  5597  5824 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:45:36.619  5597  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 19:45:36.619  5597  5824 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 19:45:36.619  5597  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 19:45:36.619  5597  5824 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 19:45:36.619  5597  5824 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 19:45:36.619  5597  5824 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 19:45:36.619  5597  5824 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 19:45:36.619  5597  5824 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 19:45:36.620  5597  5824 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:45:36.620  5597  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-18 19:45:36.621  5597  5644 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-18 19:45:36.621  5597  5644 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-18 19:45:36.622  5597  5644 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-18 19:45:36.623  5597  5825 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:45:36.623  5597  5825 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:45:36.624  5597  5825 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
11-18 19:45:36.624  5597  5825 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:45:36.624  5597  5825 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 19:45:36.624  5597  5825 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-18 19:45:36.624  5597  5825 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:45:36.624  5597  5825 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 19:45:36.625  5597  5644 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-18 19:45:36.625  5597  5644 E com.test.thalitest.ThaliTestRunner: 
11-18 19:45:36.625  5597  5644 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 19:45:36.625  5597  5644 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:45:36.626  5597,  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTe,stRunner: Expected: is <true>
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.,java:268)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 19:45:36.626  5597  5644 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.,Method.invoke(Native Method)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
,11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:45:36.627  5597  5644 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,11-18 19:45:36.628  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG UnitTest_app: 'Running unit tests'
11-18 19:45:36.628  5597  5644 I jxcore-log: 
,11-18 19:45:36.629  5597  5644 I jxcore-log: *Native tests were executed*
11-18 19:45:36.629  5597  5644 I jxcore-log: 
11-18 19:45:36.629  5597  5644 I jxcore-log: Total number of executed tests:  82
11-18 19:45:36.629  5597  5644 I jxcore-log: 
11-18 19:45:36.629  5597  5644 I jxcore-log: Number of passed tests:  79
11-18 19:45:36.629  5597  5644 I jxcore-log: 
11-18 19:45:36.629  5597  5644 I jxcore-log: Number of failed tests:  3
11-18 19:45:36.629  5597  5644 I jxcore-log: 
11-18 19:45:36.629  5597  5644 I jxcore-log: Number of ignored tests:  0
11-18 19:45:36.629  5597  5644 I jxcore-log: 
11-18 19:45:36.629  5597  5644 I jxcore-log: Total duration:  38743
11-18 19:45:36.629  5597  5644 I jxcore-log: 
11-18 19:45:36.629  5597  5644 I jxcore-log: Failed to execute UT.
11-18 19:45:36.629  5597  5644 I jxcore-log: 
,11-18 19:45:36.630  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-18 19:45:36.630  5597  5644 I jxcore-log: 
11-18 19:45:36.631  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-18 19:45:36.631  5597  5644 I jxcore-log: 
11-18 19:45:36.634  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 19:45:36.634  5597  5644 I jxcore-log: 
,11-18 19:45:36.634  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:45:36.634  5597  5644 I jxcore-log: 
11-18 19:45:36.636  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 19:45:36.636  5597  5644 I jxcore-log: 
11-18 19:45:36.637  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:45:36.637  5597  5644 I jxcore-log: 
,11-18 19:45:36.638  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 19:45:36.638  5597  5644 I jxcore-log: 
,11-18 19:45:36.638  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 19:45:36.638  5597  5644 I jxcore-log: 
11-18 19:45:36.638  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:45:36.638  5597  5644 I jxcore-log: 
11-18 19:45:36.638  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 19:45:36.638  5597  5644 I jxcore-log: 
11-18 19:45:36.639  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 19:45:36.639  5597  5644 I jxcore-log: 
11-18 19:45:36.639  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:45:36.639  5597  5644 I jxcore-log: 
11-18 19:45:36.639  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 19:45:36.639  5597  5644 I jxcore-log: 
11-18 19:45:36.639  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 19:45:36.639  5597  5644 I jxcore-log: 
11-18 19:45:36.639  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:45:36.639  5597  5644 I jxcore-log: 
11-18 19:45:36.640  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 19:45:36.640  5597  5644 I jxcore-log: 
,11-18 19:45:36.640  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:45:36.640  5597  5644 I jxcore-log: 
11-18 19:45:36.640  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 19:45:36.640  5597  5644 I jxcore-log: 
11-18 19:45:36.641  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:45:36.641  5597  5644 I jxcore-log: 
11-18 19:45:36.641  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 19:45:36.641  5597  5644 I jxcore-log: 
11-18 19:45:36.641  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:45:36.641  5597  5644 I jxcore-log: 
11-18 19:45:36.641  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 19:45:36.641  5597  5644 I jxcore-log: 
,11-18 19:45:36.641  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:45:36.641  5597  5644 I jxcore-log: 
11-18 19:45:36.642  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 19:45:36.642  5597  5644 I jxcore-log: 
11-18 19:45:36.642  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:45:36.642  5597  5644 I jxcore-log: 
11-18 19:45:36.642  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-18 19:45:36.642  5597  5644 I jxcore-log: 
11-18 19:45:36.642  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:45:36.642  5597  5644 I jxcore-log: 
11-18 19:45:36.642  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-18 19:45:36.642  5597  5644 I jxcore-log: 
,11-18 19:45:36.643  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:45:36.643  5597  5644 I jxcore-log: 
11-18 19:45:36.643  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 19:45:36.643  5597  5644 I jxcore-log: 
11-18 19:45:36.644  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 19:45:36.644  5597  5644 I jxcore-log: 
11-18 19:45:36.645  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:45:36.645  5597  5644 I jxcore-log: 
11-18 19:45:36.645  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-18 19:45:36.645  5597  5644 I jxcore-log: 
11-18 19:45:36.646  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 19:45:36.646  5597  5644 I jxcore-log: 
,11-18 19:45:36.646  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:45:36.646  5597  5644 I jxcore-log: 
11-18 19:45:36.646  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-18 19:45:36.646  5597  5644 I jxcore-log: 
11-18 19:45:36.646  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 19:45:36.646  5597  5644 I jxcore-log: 
11-18 19:45:36.646  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:45:36.646  5597  5644 I jxcore-log: 
11-18 19:45:36.647  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 19:45:36.647  5597  5644 I jxcore-log: 
11-18 19:45:36.647  5597  5597 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-18 19:45:36.647  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:45:36.647  5597  5644 I jxcore-log: 
11-18 19:45:36.651  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-18 19:45:36.651  5597  5644 I jxcore-log: 
11-18 19:45:36.651  5597  5644 I jxcore-log: 2016-11-18 18:45:36 - WARN testUtils: 'myNameCallback not set!'
11-18 19:45:36.651  5597  5644 I jxcore-log: 
,11-18 19:45:38.724  5597  5644 I jxcore-log: 2016-11-18 18:45:38 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-18 19:45:38.724  5597  5644 I jxcore-log: 
,11-18 19:45:38.726  5597  5644 I jxcore-log: 2016-11-18 18:45:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-18 19:45:38.726  5597  5644 I jxcore-log: 
,11-18 19:45:39.058  5597  5644 I jxcore-log: 2016-11-18 18:45:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-18 19:45:39.058  5597  5644 I jxcore-log: 
,11-18 19:45:39.072  5597  5644 I jxcore-log: 2016-11-18 18:45:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-18 19:45:39.072  5597  5644 I jxcore-log: ,
,11-18 19:45:40.173  5597  5644 I jxcore-log: 2016-11-18 18:45:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-18 19:45:40.173  5597  5644 I jxcore-log: 
,11-18 19:45:40.337  5597  5644 I jxcore-log: 2016-11-18 18:45:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-18 19:45:40.337  5597  5644 I jxcore-log: 
,11-18 19:45:40.343  5597  5644 I jxcore-log: 2016-11-18 18:45:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-18 19:45:40.343  5597  5644 I jxcore-log: 
,11-18 19:45:40.355  5597  5644 I jxcore-log: 2016-11-18 18:45:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-18 19:45:40.355  5597  5644 I jxcore-log: 
,11-18 19:45:40.844  5597  5644 I jxcore-log: 2016-11-18 18:45:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-18 19:45:40.844  5597  5644 I jxcore-log: 
,11-18 19:45:40.889  5597  5644 I jxcore-log: 2016-11-18 18:45:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-18 19:45:40.889  5597  5644 I jxcore-log: 
,11-18 19:45:40.902  5597  5644 I jxcore-log: 2016-11-18 18:45:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-18 19:45:40.902  5597  5644 I jxcore-log: 
,11-18 19:45:40.906  5597  5644 I jxcore-log: 2016-11-18 18:45:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-18 19:45:40.906  5597  5644 I jxcore-log: 
,11-18 19:45:41.184  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-18 19:45:41.184  5597  5644 I jxcore-log: 
,11-18 19:45:41.309  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-18 19:45:41.309  5597  5644 I jxcore-log: 
,11-18 19:45:41.649  3589  3589 I ConfigService: onDestroy
,11-18 19:45:41.684  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-18 19:45:41.684  5597  5644 I jxcore-log: 
,11-18 19:45:41.691  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-18 19:45:41.691  5597  5644 I jxcore-log: 
,11-18 19:45:41.695  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-18 19:45:41.695  5597  5644 I jxcore-log: 
,11-18 19:45:41.699  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-18 19:45:41.699  5597  5644 I jxcore-log: 
,11-18 19:45:41.704  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-18 19:45:41.704  5597  5644 I jxcore-log: 
,11-18 19:45:41.742  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-18 19:45:41.742  5597  5644 I jxcore-log: 
,11-18 19:45:41.748  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-18 19:45:41.748  5597  5644 I jxcore-log: 
,11-18 19:45:41.770  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-18 19:45:41.770  5597  5644 I jxcore-log: 
,11-18 19:45:41.808  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-18 19:45:41.808  5597  5644 I jxcore-log: 
,11-18 19:45:41.824  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-18 19:45:41.824  5597  5644 I jxcore-log: 
,11-18 19:45:41.831  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-18 19:45:41.831  5597  5644 I jxcore-log: 
,11-18 19:45:41.847  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-18 19:45:41.847  5597  5644 I jxcore-log: 
,11-18 19:45:41.861  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-18 19:45:41.861  5597  5644 I jxcore-log: 
,11-18 19:45:41.868  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-18 19:45:41.868  5597  5644 I jxcore-log: 
,11-18 19:45:41.873  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-18 19:45:41.873  5597  5644 I jxcore-log: 
,11-18 19:45:41.886  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-18 19:45:41.886  5597  5644 I jxcore-log: 
,11-18 19:45:41.904  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-18 19:45:41.904  5597  5644 I jxcore-log: 
,11-18 19:45:41.918  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-18 19:45:41.918  5597  5644 I jxcore-log: 
,11-18 19:45:41.929  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-18 19:45:41.929  5597  5644 I jxcore-log: 
,11-18 19:45:41.942  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-18 19:45:41.942  5597  5644 I jxcore-log: 
,11-18 19:45:41.953  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-18 19:45:41.953  5597  5644 I jxcore-log: 
,11-18 19:45:41.966  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-18 19:45:41.966  5597  5644 I jxcore-log: 
,11-18 19:45:41.976  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-18 19:45:41.976  5597  5644 I jxcore-log: 
,11-18 19:45:41.983  5597  5644 I jxcore-log: 2016-11-18 18:45:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-18 19:45:41.983  5597  5644 I jxcore-log: 
,11-18 19:45:42.004  5597  5644 I jxcore-log: 2016-11-18 18:45:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-18 19:45:42.004  5597  5644 I jxcore-log: 
,11-18 19:45:42.010  5597  5644 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-18 19:45:42.011  5597  5644 I jxcore-log: 2016-11-18 18:45:42 - INFO testUtils: 'BLE multiple advertisement supported'
11-18 19:45:42.011  5597  5644 I jxcore-log: 
,11-18 19:45:42.095  5597  5644 I jxcore-log: 2016-11-18 18:45:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:42.095  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:42.095  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:42.095  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:42.095  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:42.095  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:42.095  5597  5644 I jxcore-log: 
,11-18 19:45:42.324  5597  5644 I jxcore-log: 2016-11-18 18:45:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:42.324  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:42.324  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:42.324  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:42.324  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:42.324  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:42.324  5597  5644 I jxcore-log: 
11-18 19:45:42.327  5597  5644 I jxcore-log: 2016-11-18 18:45:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:42.327  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:42.327  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:42.327  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:42.327  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:42.327  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:42.327  5597  5644 I jxcore-log: 
,11-18 19:45:42.892  5597  5644 I jxcore-log: 2016-11-18 18:45:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:42.892  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:42.892  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:42.892  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:42.892  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:42.892  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:42.892  5597  5644 I jxcore-log: 
,11-18 19:45:42.896  5597  5644 I jxcore-log: 2016-11-18 18:45:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:42.896  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:42.896  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:42.896  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:42.896  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:42.896  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:42.896  5597  5644 I jxcore-log: 
,11-18 19:45:43.863  5597  5644 I jxcore-log: 2016-11-18 18:45:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:43.863  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:43.863  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:43.863  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:43.863  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:43.863  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:43.863  5597  5644 I jxcore-log: 
,11-18 19:45:43.866  5597  5644 I jxcore-log: 2016-11-18 18:45:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:43.866  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:43.866  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:43.866  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:43.866  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:43.866  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:43.866  5597  5644 I jxcore-log: 
,11-18 19:45:44.900  5597  5644 I jxcore-log: 2016-11-18 18:45:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:44.900  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:44.900  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:44.900  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:44.900  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:44.900  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:44.900  5597  5644 I jxcore-log: 
,11-18 19:45:44.906  5597  5644 I jxcore-log: 2016-11-18 18:45:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:44.906  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:44.906  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:44.906  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:44.906  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:44.906  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:44.906  5597  5644 I jxcore-log: 
,11-18 19:45:44.919   927  5792 D NetlinkSocketObserver: NeighborEvent{elapsedMs=143590, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-18 19:45:45.438   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:45.948  5597  5644 I jxcore-log: 2016-11-18 18:45:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:45.948  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:45.948  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:45.948  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:45.948  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:45.948  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:45.948  5597  5644 I jxcore-log: 
11-18 19:45:45.951  5597  5644 I jxcore-log: 2016-11-18 18:45:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:45.951  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:45.951  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:45.951  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:45.951  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:45.951  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:45.951  5597  5644 I jxcore-log: 
,11-18 19:45:46.439   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:46.983  5597  5644 I jxcore-log: 2016-11-18 18:45:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:46.983  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:46.983  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:46.983  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:46.983  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:46.983  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:46.983  5597  5644 I jxcore-log: 
,11-18 19:45:46.987  5597  5644 I jxcore-log: 2016-11-18 18:45:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:46.987  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:46.987  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:46.987  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:46.987  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:46.987  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:46.987  5597  5644 I jxcore-log: 
,11-18 19:45:47.440   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:48.020  5597  5644 I jxcore-log: 2016-11-18 18:45:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:48.020  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:48.020  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:48.020  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:48.020  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:48.020  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:48.020  5597  5644 I jxcore-log: 
,11-18 19:45:48.027  5597  5644 I jxcore-log: 2016-11-18 18:45:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:48.027  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:48.027  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:48.027  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:48.027  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:48.027  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:48.027  5597  5644 I jxcore-log: 
,11-18 19:45:48.441   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:49.056  5597  5644 I jxcore-log: 2016-11-18 18:45:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:49.056  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:49.056  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:49.056  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:49.056  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:49.056  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:49.056  5597  5644 I jxcore-log: 
,11-18 19:45:49.060  5597  5644 I jxcore-log: 2016-11-18 18:45:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:49.060  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:49.060  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:49.060  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:49.060  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:49.060  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:49.060  5597  5644 I jxcore-log: 
,11-18 19:45:49.443   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:45:50.091  5597  5644 I jxcore-log: 2016-11-18 18:45:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:50.091  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:50.091  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:50.091  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:50.091  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:50.091  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:50.091  5597  5644 I jxcore-log: 
,11-18 19:45:50.095  5597  5644 I jxcore-log: 2016-11-18 18:45:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:50.095  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:50.095  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:50.095  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:50.095  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:50.095  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:50.095  5597  5644 I jxcore-log: 
,11-18 19:45:50.443   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-18 19:45:50.927   927  5792 D NetlinkSocketObserver: NeighborEvent{elapsedMs=149598, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-18 19:45:51.185  5597  5644 I jxcore-log: 2016-11-18 18:45:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:51.185  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:51.185  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:51.185  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:51.185  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:51.185  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:51.185  5597  5644 I jxcore-log: 
,11-18 19:45:51.192  5597  5644 I jxcore-log: 2016-11-18 18:45:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:51.192  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:51.192  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:51.192  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:51.192  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:51.192  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:51.192  5597  5644 I jxcore-log: 
,11-18 19:45:51.584   927  2983 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-18 19:45:52.226  5597  5644 I jxcore-log: 2016-11-18 18:45:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:52.226  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:52.226  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:52.226  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:52.226  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:52.226  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:52.226  5597  5644 I jxcore-log: 
,11-18 19:45:52.235  5597  5644 I jxcore-log: 2016-11-18 18:45:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:52.235  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:52.235  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:52.235  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:52.235  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:52.235  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:52.235  5597  5644 I jxcore-log: 
,11-18 19:45:53.267  5597  5644 I jxcore-log: 2016-11-18 18:45:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:53.267  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:53.267  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:53.267  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:53.267  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:53.267  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:53.267  5597  5644 I jxcore-log: 
,11-18 19:45:53.270  5597  5644 I jxcore-log: 2016-11-18 18:45:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:53.270  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:53.270  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:53.270  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:53.270  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:53.270  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:53.270  5597  5644 I jxcore-log: 
,11-18 19:45:54.303  5597  5644 I jxcore-log: 2016-11-18 18:45:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:54.303  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:54.303  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:54.303  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:54.303  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:54.303  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:54.303  5597  5644 I jxcore-log: 
,11-18 19:45:54.307  5597  5644 I jxcore-log: 2016-11-18 18:45:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:54.307  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:54.307  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:54.307  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:54.307  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:54.307  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:54.307  5597  5644 I jxcore-log: 
,11-18 19:45:55.338  5597  5644 I jxcore-log: 2016-11-18 18:45:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:55.338  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:55.338  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:55.338  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:55.338  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:55.338  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:55.338  5597  5644 I jxcore-log: 
,11-18 19:45:55.341  5597  5644 I jxcore-log: 2016-11-18 18:45:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:55.341  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:55.341  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:55.341  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:55.341  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:55.341  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:55.341  5597  5644 I jxcore-log: 
,11-18 19:45:56.373  5597  5644 I jxcore-log: 2016-11-18 18:45:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:45:56.373  5597  5644 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:45:56.373  5597  5644 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:45:56.373  5597  5644 I jxcore-log: emit@events.js:82:1
11-18 19:45:56.373  5597  5644 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:45:56.373  5597  5644 I jxcore-log: emit@events.js:82:1'
11-18 19:45:56.373  5597  5644 I jxcore-log: 
,11-18 19:45:56.381  5597  5644 E jxcore  : Error!: error is undefined
11-18 19:45:56.381  5597  5644 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-18 19:45:56.384  5597  5644 I jxcore-log: 2016-11-18 18:45:56 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-18 19:45:56.384  5597  5644 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-18 19:45:56.384  5597  5644 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-18 19:45:56.384  5597  5644 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-18 19:45:56.384  5597  5644 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-18 19:45:56.384  5597  5644 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-18 19:45:56.384  5597  5644 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-18 19:45:56.384  5597  5644 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-18 19:45:56.385  5597  5644 I jxcore-log: 2016-11-18 18:45:56 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-18 19:45:56.385  5597  5644 I jxcore-log: 
,11-18 19:45:56.387  5597  5644 E jxcore-log: TypeError: 
11-18 19:45:56.387  5597  5644 E jxcore-log: error is undefined
11-18 19:45:56.387  5597  5644 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-18 19:45:56.387  5597  5644 E jxcore-log: 
,11-18 19:45:56.452   927  2948 W InputDispatcher: channel '5ed6316 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-18 19:45:56.452   927  2948 E InputDispatcher: channel '5ed6316 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-18 19:45:56.461   927  3422 D GraphicsStats: Buffer count: 2
11-18 19:45:56.461   927  3841 I WindowState: WIN DEATH: Window{5ed6316 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-18 19:45:56.461   927  3841 W InputDispatcher: Attempted to unregister already unregistered input channel '5ed6316 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,11-18 19:45:56.462   927  2984 D WifiService: Client connection lost with reason: 4
,11-18 19:45:56.473   527   527 I Zygote  : Process 5597 exited cleanly (139)
,11-18 19:45:56.477   927  3166 I ActivityManager: Process com.test.thalitest (pid 5597) has died
,11-18 19:45:56.480   927  3166 W ActivityManager: Force removing ActivityRecord{83ee6bf u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-18 19:45:56.534   927  3792 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5597 uid 10077
11-18 19:45:56.535  3667  3667 I Keyboard.Facilitator: onFinishInput()
11-18 19:45:56.531  3792  3792 W Binder_7: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[28079]" dev="sockfs" ino=28079 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-18 19:45:56.531  3792  3792 W Binder_7: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[28079]" dev="sockfs" ino=28079 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 19:45:56.593  3985  5831 I MicroRecognitionRnrImpl: Starting detection.
,11-18 19:45:56.595  3985  5832 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@c5a1849
,11-18 19:45:56.597   512  5834 I AudioFlinger: AudioFlinger's thread 0xf1f40000 ready to run
,11-18 19:45:56.603   512  3014 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-18 19:45:56.605  3985  5832 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@c5a1849
,11-18 19:45:56.615   512  5834 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-18 19:45:56.615   512  5834 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-18 19:45:56.615   512  5834 I ACDB-LOADER: ACDB AFE returned = -19
11-18 19:45:56.615   512  5834 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
,11-18 19:45:56.615   512  5834 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-18 19:45:56.615   512  5834 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-18 19:45:56.623   512  5834 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-18 19:45:56.700  3985  3985 I HotwordWorkerImpl: onReady
,11-18 19:45:56.802  5826  5826 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-18 19:45:56.806  5826  5826 D AndroidRuntime: CheckJNI is OFF
,11-18 19:45:56.830  5826  5826 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-18 19:45:56.855  5826  5826 I Radio-JNI: register_android_hardware_Radio DONE
,11-18 19:45:56.871  5826  5826 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-18 19:45:56.881   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-18 19:45:57.026   927   950 I art     : Starting a blocking GC Explicit
,11-18 19:45:57.077  3823  4022 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-18 19:45:57.133   927   950 I art     : Explicit concurrent mark sweep GC freed 75864(4MB) AllocSpace objects, 22(760KB) LOS objects, 33% free, 29MB/43MB, paused 1.558ms total 106.223ms
,11-18 19:45:57.157   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-18 19:45:57.159  5826  5826 I art     : System.exit called, status: 0
11-18 19:45:57.160  5826  5826 I AndroidRuntime: VM exiting with result code 0.
,11-18 19:45:57.165   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-18 19:45:57.182  5686  5686 D BluetoothMapAppObserver: onReceive
11-18 19:45:57.182  5686  5686 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-18 19:45:57.190   927  2949 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-18 19:45:57.190  3667  3667 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-18 19:45:57.193  4078  4197 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-18 19:45:57.209  3667  5846 I Keyboard.Facilitator.DecoderInitializer: run()
,11-18 19:45:57.217  3667  5846 I Decoder : createOrResetDecoder
,11-18 19:45:57.243  3789  3789 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
11-18 19:45:57.246   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-18 19:45:57.251    28    28 W kworker/2:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 19:45:57.254    28    28 W kworker/2:1: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 19:45:57.264    28    28 W kworker/2:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 19:45:57.269  3404  5849 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-18 19:45:57.276   927  3871 I ActivityManager: Start proc 5850:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
11-18 19:45:57.277  3823  3921 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-18 19:45:57.277  3823  3921 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3823
11-18 19:45:57.277  3823  3921 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-18 19:45:57.277  3823  3921 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 19:45:57.277  3823  3921 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 19:45:57.277  3823  3921 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 19:45:57.277  3823  3921 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 19:45:57.277  3823  3921 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 19:45:57.277  3823  3921 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-18 19:45:57.277  3823  3921 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-18 19:45:57.277  3823  3921 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 19:45:57.277  3823  3921 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 19:45:57.277  3823  3921 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:45:57.277  3823  3921 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 19:45:57.280  3589  3589 I ConfigService: onCreate
,11-18 19:45:57.282  3589  5860 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-18 19:45:57.282  3589  5860 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-18 19:45:57.283  3589  5860 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-18 19:45:57.283   927  5861 E DropBoxManagerService: Can't write: system_app_crash
11-18 19:45:57.283   927  5861 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
11-18 19:45:57.283   927  5861 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 19:45:57.283   927  5861 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 19:45:57.283   927  5861 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 19:45:57.283   927  5861 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 19:45:57.283   927  5861 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 19:45:57.283   927  5861 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 19:45:57.283   927  5861 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 19:45:57.283   927  5861 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 19:45:57.283   927  5861 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 19:45:57.283   927  5861 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 19:45:57.283   927  5861 E DropBoxManagerService: 	... 5 more
11-18 19:45:57.284   927  3841 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-18 19:45:57.285  3589  5860 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-18 19:45:57.287  3985  3998 W SearchService: Abort, client detached.
11-18 19:45:57.291  3985  3985 I HotwordDetector: Closing mic
11-18 19:45:57.292  3985  4220 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c5a1849
11-18 19:45:57.292  3985  5832 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-18 19:45:57.302  3667  5846 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-18 19:45:57.314   927  5864 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-18 19:45:57.308   409   409 W Binder_1: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[27278]" dev="sockfs" ino=27278 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 19:45:57.308   409   409 W Binder_1: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[27278]" dev="sockfs" ino=27278 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 19:45:57.311   502   502 W Binder_4: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[32305]" dev="sockfs" ino=32305 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 19:45:57.311   502   502 W Binder_4: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[32305]" dev="sockfs" ino=32305 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 19:45:57.331  3589  3589 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-18 19:45:57.332  3589  3589 D AndroidRuntime: Shutting down VM
11-18 19:45:57.333  3589  3589 E AndroidRuntime: FATAL EXCEPTION: main
11-18 19:45:57.333  3589  3589 E AndroidRuntime: Process: com.google.process.gapps, PID: 3589
11-18 19:45:57.333  3589  3589 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-18 19:45:57.333  3589  3589 E AndroidRuntime: 	... 8 more
,11-18 19:45:57.343   927  5867 E DropBoxManagerService: Can't write: system_app_crash
11-18 19:45:57.343   927  5867 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
11-18 19:45:57.343   927  5867 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 19:45:57.343   927  5867 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 19:45:57.343   927  5867 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 19:45:57.343   927  5867 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 19:45:57.343   927  5867 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 19:45:57.343   927  5867 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 19:45:57.343   927  5867 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 19:45:57.343   927  5867 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 19:45:57.343   927  5867 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 19:45:57.343   927  5867 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 19:45:57.343   927  5867 E DropBoxManagerService: 	... 5 more
11-18 19:45:57.361   512  5834 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-18 19:45:57.362   512  5834 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-18 19:45:57.364   927  5864 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-18 19:45:57.364   927  5864 I Adreno  : Build Date                       : 12/06/15
11-18 19:45:57.364   927  5864 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-18 19:45:57.364   927  5864 I Adreno  : Local Branch                     : mybranch17112971
11-18 19:45:57.364   927  5864 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-18 19:45:57.364   927  5864 I Adreno  : Remote Branch                    : NONE
11-18 19:45:57.364   927  5864 I Adreno  : Reconstruct Branch               : NOTHING
,11-18 19:45:57.368   512  5834 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-18 19:45:57.368   512  5834 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-18 19:45:57.369   927  3862 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
11-18 19:45:57.370   512  3014 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-18 19:45:57.374  3985  5831 I MicroRecognitionRnrImpl: Detection finished
11-18 19:45:57.375  3985  4228 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-18 19:45:57.377  3404  5849 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-18 19:45:57.386  3404  5849 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-18 19:45:57.386  3404  5849 E AndroidRuntime: Process: android.process.acore, PID: 3404
11-18 19:45:57.386  3404  5849 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:45:57.386  3404  5849 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 19:45:57.647   382   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
