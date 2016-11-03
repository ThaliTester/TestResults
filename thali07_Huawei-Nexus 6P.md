#### Test 914795746db6186_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-03 23:09:47.446  3735  4099 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
11-03 23:09:47.517  3735  4099 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,11-03 23:09:47.966  5491  5491 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-03 23:09:47.971  5491  5491 D AndroidRuntime: CheckJNI is OFF
11-03 23:09:47.999  5491  5491 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-03 23:09:48.031  5491  5491 I Radio-JNI: register_android_hardware_Radio DONE
11-03 23:09:48.046  5491  5491 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-03 23:09:48.064   929  3732 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-03 23:09:48.085  5491  5491 D AndroidRuntime: Shutting down VM
11-03 23:09:48.096  3866  3879 W SearchService: Abort, client detached.
11-03 23:09:48.102  3866  3866 I HotwordDetector: Closing mic
11-03 23:09:48.102  3866  4064 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@fca6a76
11-03 23:09:48.103  3866  4096 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-03 23:09:48.127   929  3322 I ActivityManager: Start proc 5501:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-03 23:09:48.168   513  4102 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-03 23:09:48.170   513  4102 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-03 23:09:48.178   513  4102 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-03 23:09:48.179   513  4102 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-03 23:09:48.179   513  2908 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-03 23:09:48.181  3866  4068 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-03 23:09:48.181  3866  4093 I MicroRecognitionRnrImpl: Detection finished
11-03 23:09:48.229  5501  5501 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-03 23:09:48.250  5501  5501 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-03 23:09:48.314  5501  5501 I LibraryLoader: Time to load native libraries: 61 ms (timestamps 9805-9866)
,11-03 23:09:48.314  5501  5501 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 23:09:48.349  5501  5501 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {daf087}
,11-03 23:09:48.350  5501  5501 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 23:09:48.350  5501  5501 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-03 23:09:48.353  5501  5501 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-03 23:09:48.354  5501  5501 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 23:09:48.402  5501  5501 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 23:09:48.410  5501  5501 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 23:09:48.410  5501  5501 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 23:09:48.410  5501  5501 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 23:09:48.410  5501  5501 I Adreno  : Build Date                       : 12/06/15
11-03 23:09:48.410  5501  5501 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 23:09:48.410  5501  5501 I Adreno  : Local Branch                     : mybranch17112971
11-03 23:09:48.410  5501  5501 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 23:09:48.410  5501  5501 I Adreno  : Remote Branch                    : NONE
11-03 23:09:48.410  5501  5501 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 23:09:48.451   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b17bd8a:true
,11-03 23:09:48.489   728   728 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[29786]" dev="sockfs" ino=29786 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 23:09:48.489   728   728 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[29786]" dev="sockfs" ino=29786 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 23:09:48.501  5501  5501 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 23:09:48.510  5501  5501 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 23:09:48.629  5501  5538 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 23:09:48.626   727   727 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[29544]" dev="sockfs" ino=29544 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 23:09:48.626   727   727 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[29544]" dev="sockfs" ino=29544 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 23:09:48.636  3060  3060 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[29791]" dev="sockfs" ino=29791 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 23:09:48.636  3060  3060 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[29791]" dev="sockfs" ino=29791 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:09:48.639  5501  5525 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-03 23:09:48.679  5501  5538 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 23:09:48.766  3732  3732 W Binder_B: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31744]" dev="sockfs" ino=31744 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:09:48.766  3732  3732 W Binder_B: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31744]" dev="sockfs" ino=31744 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 23:09:48.768   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +666ms
11-03 23:09:48.772  3556  3556 I Keyboard.Facilitator: onFinishInput()
11-03 23:09:48.769   940   940 W Binder_2: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31743]" dev="sockfs" ino=31743 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 23:09:48.769   940   940 W Binder_2: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31743]" dev="sockfs" ino=31743 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:09:48.817  5501  5501 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5501
,11-03 23:09:48.916  5501  5501 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 23:09:49.110  5501  5540 D jxcore_app_log: JniHelper::setJavaVM(0xf537c000), pthread_self() = -562562768
,11-03 23:09:49.125  5501  5540 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-03 23:09:49.125  5501  5540 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-03 23:09:49.125  5501  5540 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-03 23:09:49.125  5501  5540 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-03 23:09:49.125  5501  5540 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-03 23:09:49.127  5501  5540 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eeb696a added. We now have 1 listener(s)
,11-03 23:09:49.148  5501  5540 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-03 23:09:49.149  5501  5540 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:09:49.149  5501  5540 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:09:49.149  5501  5540 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-03 23:09:49.151  5501  5540 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da187d1 added. We now have 1 listener(s)
11-03 23:09:49.152  5501  5540 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:09:49.158   929  2853 D WifiService: New client listening to asynchronous messages
,11-03 23:09:49.158  5501  5540 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 23:09:49.158  5501  5540 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-03 23:09:49.159  5501  5540 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 59
11-03 23:09:49.159  5501  5540 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-03 23:09:49.159  5501  5540 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-03 23:09:49.159  5501  5540 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-03 23:09:49.159  5501  5540 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 59
,11-03 23:09:49.160  5501  5540 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-03 23:09:49.256  5501  5501 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-03 23:09:49.602  5501  5510 I art     : Background sticky concurrent mark sweep GC freed 79177(7MB) AllocSpace objects, 16(1076KB) LOS objects, 22% free, 25MB/32MB, paused 1.331ms total 270.272ms
,11-03 23:09:49.619   929  2852 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 23:09:50.433  5501  5510 I art     : Background partial concurrent mark sweep GC freed 57540(6MB) AllocSpace objects, 3(2MB) LOS objects, 37% free, 26MB/42MB, paused 2.055ms total 122.583ms
,11-03 23:09:50.567  5501  5548 W jxcore-log: Initializing JXcore engine
,11-03 23:09:50.567  5501  5548 W jxcore-log: JXcore engine is ready
,11-03 23:09:50.589  5548  5548 W Thread-65: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12547 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-03 23:09:50.589  5548  5548 W Thread-65: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13503]" dev="sockfs" ino=13503 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-03 23:09:50.589  5548  5548 W Thread-65: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-03 23:09:50.589  5548  5548 W Thread-65: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31711]" dev="sockfs" ino=31711 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-03 23:09:50.598  5501  5548 W jxcore-log: Starting JXcore engine
,11-03 23:09:50.647  5501  5548 W jxcore-log: Platform android
11-03 23:09:50.647  5501  5548 W jxcore-log: 
,11-03 23:09:50.647  5501  5548 W jxcore-log: Process ARCH arm
11-03 23:09:50.647  5501  5548 W jxcore-log: 
,11-03 23:09:50.819  5501  5548 I jxcore-log: JXcore Cordova bridge is ready!
11-03 23:09:50.819  5501  5548 I jxcore-log: 
,11-03 23:09:50.819  5501  5548 W jxcore-log: JXcore engine is started
,11-03 23:09:50.825  5501  5540 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-03 23:09:50.828  5501  5501 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-03 23:09:51.551  3483  3483 I ConfigService: onDestroy
,11-03 23:09:52.689   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:09:53.114   929  3732 I ActivityManager: Killing 5057:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-03 23:09:53.186   929   940 I ActivityManager: Killing 5146:org.codeaurora.ims/1001 (adj 15): empty #17
,11-03 23:09:53.690   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:09:54.691   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:09:55.692   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:09:56.693   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:09:57.694   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 23:10:00.487  5501  5548 I jxcore-log: 2016-11-03 22:10:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-03 23:10:00.487  5501  5548 I jxcore-log: 
,11-03 23:10:00.489  5501  5548 I jxcore-log: 2016-11-03 22:10:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-03 23:10:00.489  5501  5548 I jxcore-log: 
,11-03 23:10:00.494  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-03 23:10:00.494  5501  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 23:10:00.494  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:00.494  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:00.494  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:10:00.494  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:10:00.494  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 23:10:00.494  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:10:00.494  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 23:10:00.496  5501  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 23:10:00.499  5501  5548 I jxcore-log: 2016-11-03 22:10:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-03 23:10:00.499  5501  5548 I jxcore-log: 
,11-03 23:10:00.500  5501  5548 I jxcore-log: 2016-11-03 22:10:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-03 23:10:00.500  5501  5548 I jxcore-log: 
,11-03 23:10:00.759  5501  5548 I jxcore-log: 2016-11-03 22:10:00 - DEBUG UnitTest_app: 'Running unit tests'
11-03 23:10:00.759  5501  5548 I jxcore-log: 
,11-03 23:10:00.760  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:10:00.760  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93c9ea7 added. We now have 2 listener(s)
11-03 23:10:00.761  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:10:00.761  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:10:00.761  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 23:10:00.761  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:10:00.761  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3509f54 added. We now have 2 listener(s)
11-03 23:10:00.761  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:10:00.762  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 23:10:00.763  5501  5548 D executeNativeTests: Running unit tests
,11-03 23:10:00.799  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 23:10:00.799  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d added. We now have 3 listener(s)
11-03 23:10:00.800  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:10:00.800  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 23:10:00.800  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 23:10:00.800  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:10:00.800  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 added. We now have 3 listener(s)
11-03 23:10:00.800  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:10:00.801  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 23:10:00.802  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 23:10:00.802  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 23:10:00.802  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 23:10:00.802  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 23:10:00.803  5501  5548 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-03 23:10:00.803  5501  5548 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 23:10:00.803  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 23:10:00.803  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 23:10:00.803  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 23:10:00.803  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 23:10:00.804  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:00.804  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:00.804  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:00.804  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:00.804  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:00.804  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-03 23:10:00.804  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d removed from the list
11-03 23:10:00.804  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:00.804  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 removed from the list
11-03 23:10:00.804  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:00.805  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.805  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:00.805  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.805  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.805  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:00.805  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:00.805  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:00.805  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:00.806  5501  5548 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-03 23:10:00.806  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:00.806  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 23:10:00.807  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:00.807  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:00.807  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:00.807  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
,11-03 23:10:00.807  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:00.807  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
,11-03 23:10:00.807  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:00.807  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.807  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.807  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.807  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:00.807  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:00.807  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:00.807  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:00.808  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 23:10:00.810  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 23:10:00.811  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-03 23:10:00.811  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 23:10:00.811  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-03 23:10:00.811  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 23:10:00.811  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-03 23:10:00.811  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-03 23:10:00.811  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 23:10:00.811  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 23:10:00.811  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 23:10:00.811  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-03 23:10:00.811  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 23:10:00.811  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:00.811  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:00.811  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:00.811  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:00.811  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:00.811  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:00.811  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:00.811  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:00.811  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.812  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.812  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.812  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:00.812  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:00.812  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:00.812  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:00.812  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
,11-03 23:10:00.812  5501  5548 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-03 23:10:00.813  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:10:00.813  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 23:10:00.816  5501  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 23:10:00.816  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:00.816  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:00.816  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:10:00.816  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:10:00.816  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 23:10:00.816  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:10:00.816  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 23:10:00.817  5501  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 23:10:00.817  5501  5548 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 23:10:00.817  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:10:00.817  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 23:10:00.817  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-03 23:10:00.817  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:10:00.817  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 23:10:00.819  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 23:10:00.819  5501  5548 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 23:10:00.819  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 23:10:00.825  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.825  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 23:10:00.827  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 23:10:00.827  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:10:00.827  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 23:10:00.827  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 23:10:00.831  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:10:00.832  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-03 23:10:00.834  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-03 23:10:00.834  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.834  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 23:10:00.834  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 23:10:00.834  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 23:10:00.834  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 23:10:00.834  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.835  5501  5548 D BluetoothAdapter: STATE_ON
,11-03 23:10:00.837  4569  4788 D BtGatt.GattService: registerClient() - UUID=cfd4dbc8-65f4-4783-a284-0e0a635ac2ed
11-03 23:10:00.837  4569  4628 D BtGatt.GattService: onClientRegistered() - UUID=cfd4dbc8-65f4-4783-a284-0e0a635ac2ed, clientIf=5
11-03 23:10:00.839  5501  5512 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 23:10:00.840  4569  4798 D BtGatt.GattService: start scan with filters
11-03 23:10:00.847  4569  4631 D BtGatt.ScanManager: handling starting scan
,11-03 23:10:00.848  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 23:10:00.848  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.848  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 23:10:00.848  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.848  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-03 23:10:00.848  5501  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 23:10:00.848  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:10:00.849  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 23:10:00.849  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 23:10:00.849  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.849  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 23:10:00.849  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:10:00.849  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 23:10:00.849  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 23:10:00.850  4569  4631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
11-03 23:10:00.852  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.852  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:00.852  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:00.852  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 23:10:00.852  5501  5548 I io.jxcore.node.ConnectionHelper: start: OK
11-03 23:10:00.855  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:10:00.855  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:10:00.856  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-03 23:10:00.856  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:10:00.856  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:10:00.856  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 23:10:00.859  4569  4628 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 23:10:00.859  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:00.860  4569  4631 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 23:10:00.867  4569  4628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-03 23:10:00.867  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:10:00.869  4569  4631 D BtGatt.ScanManager: Starting BLE batch scan
11-03 23:10:00.869  4569  4631 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 23:10:00.882  4569  4628 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-03 23:10:00.882  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:10:00.891  4569  4628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 23:10:00.891  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:10:01.200   929  2853 D WifiService: New client listening to asynchronous messages
,11-03 23:10:01.204  3866  5549 W CronetSyncConnectionRcs: Upload content type not set.
,11-03 23:10:01.282  4778  4822 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-03 23:10:01.283  4778  4778 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-03 23:10:01.357  5501  5501 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-03 23:10:01.357  5501  5501 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:10:01.358  5501  5501 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 23:10:05.856  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 23:10:05.857  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:05.857  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 23:10:05.857  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:10:05.857  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 23:10:05.857  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:05.857  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-03 23:10:05.857  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:10:05.857  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-03 23:10:05.858  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 23:10:05.859  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.859  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:05.859  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.859  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 23:10:05.859  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.860  5501  5548 D BluetoothAdapter: STATE_ON
,11-03 23:10:05.860  4569  4788 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 23:10:05.861  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 23:10:05.862  4569  4631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 23:10:05.862  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:10:05.864  4569  4582 D BtGatt.GattService: stopScan() - queue size =1
11-03 23:10:05.865  4569  4581 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 23:10:05.866  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 23:10:05.866  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.866  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 23:10:05.867  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.867  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.867  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.867  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.868  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 23:10:05.868  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.869  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.869  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.869  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 23:10:05.870  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 23:10:05.870  4569  4569 D BtGatt.ScanManager: awakened up at time 97422
11-03 23:10:05.872  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:10:05.872  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.875  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.875  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:10:05.875  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:05.875  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:05.875  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:05.875  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:10:05.875  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:10:05.876  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-03 23:10:05.876  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-03 23:10:05.876  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:05.876  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:05.876  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:05.876  5501  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 23:10:05.876  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:05.876  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:10:05.876  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:05.876  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 23:10:05.876  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 23:10:05.876  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 23:10:05.876  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:10:05.877  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 23:10:05.877  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 23:10:05.877  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:10:05.880  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:10:05.880  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:10:05.880  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:10:05.880  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:10:05.880  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 23:10:05.893  4569  4628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 23:10:05.893  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:05.894  4569  4628 D BtGatt.GattService: current time is 97446163338
11-03 23:10:05.895  4569  4628 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -75, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -85, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -86, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 23:10:05.897  4569  4628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 23:10:05.898  4569  4628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-03 23:10:05.898  4569  4628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 23:10:05.898  4569  4628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 23:10:05.899  4569  4628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 23:10:05.899  4569  4628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 23:10:05.906  4569  4628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 23:10:05.906  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:05.906  4569  4631 D BtGatt.ScanManager: stopping BLe Batch
,11-03 23:10:05.913  4569  4628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 23:10:05.914  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:10:05.914  4569  4631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 23:10:05.921  4569  4628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 23:10:05.921  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:10:06.382  5501  5501 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 23:10:10.879  5501  5548 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-03 23:10:10.885  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 23:10:10.885  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 23:10:10.898  5501  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 23:10:10.898  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:10.898  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:10.898  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:10:10.898  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:10:10.898  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 23:10:10.898  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:10:10.898  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 23:10:10.900  5501  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 23:10:10.901  5501  5548 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 23:10:10.901  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:10:10.901  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-03 23:10:10.901  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 23:10:10.901  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:10:10.901  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 23:10:10.905  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 23:10:10.905  5501  5548 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 23:10:10.905  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 23:10:10.906  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:10:10.909  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:10:10.910  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:10.910  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 23:10:10.911  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 23:10:10.911  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 23:10:10.911  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 23:10:10.914  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.915  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 23:10:10.915  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 23:10:10.915  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 23:10:10.915  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 23:10:10.915  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.916  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:10:10.918  4569  4581 D BtGatt.GattService: registerClient() - UUID=5a2f1803-d59e-425a-bd70-85e744d21149
11-03 23:10:10.918  4569  4628 D BtGatt.GattService: onClientRegistered() - UUID=5a2f1803-d59e-425a-bd70-85e744d21149, clientIf=5
11-03 23:10:10.919  5501  5512 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-03 23:10:10.919  4569  4582 D BtGatt.GattService: start scan with filters
,11-03 23:10:10.923  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 23:10:10.923  4569  4631 D BtGatt.ScanManager: handling starting scan
11-03 23:10:10.923  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.923  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 23:10:10.923  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.923  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 23:10:10.923  5501  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 23:10:10.924  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.924  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 23:10:10.924  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 23:10:10.924  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.924  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.924  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-03 23:10:10.926  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 23:10:10.926  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:10.929  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.929  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:10:10.929  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.929  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.929  5501  5548 I io.jxcore.node.ConnectionHelper: start: OK
11-03 23:10:10.929  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.930  4569  4628 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 23:10:10.931  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:10:10.931  4569  4631 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 23:10:10.934  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 23:10:10.934  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.934  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-03 23:10:10.934  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.934  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:10:10.935  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:10.935  5501  5548 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 23:10:10.935  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:10.935  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-03 23:10:10.935  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:10:10.935  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 23:10:10.935  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:10.935  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 23:10:10.935  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:10:10.936  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-03 23:10:10.936  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 23:10:10.936  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.936  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.936  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.936  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-03 23:10:10.936  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.937  4569  4628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 23:10:10.937  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:10.937  4569  4631 D BtGatt.ScanManager: Starting BLE batch scan
11-03 23:10:10.937  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:10:10.937  4569  4631 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 23:10:10.937  4569  4581 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-03 23:10:10.937  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-03 23:10:10.938  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:10:10.939  4569  4582 D BtGatt.GattService: stopScan() - queue size =1
11-03 23:10:10.941  4569  4798 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 23:10:10.942  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 23:10:10.942  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:10.942  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 23:10:10.942  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.942  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.942  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.942  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.942  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 23:10:10.942  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.942  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.942  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:10.943  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 23:10:10.943  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 23:10:10.943  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:10:10.943  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.944  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.945  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 23:10:10.945  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.945  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.945  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:10.945  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:10:10.945  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:10:10.945  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:10:10.945  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:10.945  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:10:10.945  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:10.945  5501  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 23:10:10.945  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:10.945  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.945  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:10.945  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:10.945  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 23:10:10.945  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 23:10:10.945  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 23:10:10.945  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.945  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.945  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 23:10:10.945  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.947  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.947  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-03 23:10:10.947  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.947  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.947  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.947  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:10:10.948  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:10.948  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.948  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.948  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 23:10:10.948  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:10.948  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:10.949  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:10.949  4569  4628 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 23:10:10.949  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:10.949  5501  5548 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-03 23:10:10.951  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:10:10.951  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 23:10:10.955  4569  4628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 23:10:10.955  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:10:10.957  4569  4631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 23:10:10.957  5501  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 23:10:10.957  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:10.957  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:10.957  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:10:10.957  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:10:10.957  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 23:10:10.957  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:10:10.957  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 23:10:10.958  5501  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 23:10:10.959  5501  5548 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 23:10:10.959  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:10:10.959  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 23:10:10.959  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 23:10:10.959  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:10:10.959  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 23:10:10.961  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:10:10.962  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 23:10:10.962  5501  5548 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 23:10:10.962  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 23:10:10.962  4569  4628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:10:10.962  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:10.963  4569  4628 E BtGatt.ContextMap: Context not found for ID 5
11-03 23:10:10.964  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:10:10.965  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.966  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 23:10:10.966  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 23:10:10.966  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 23:10:10.966  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 23:10:10.969  4569  4628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 23:10:10.969  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:10.969  4569  4631 D BtGatt.ScanManager: stopping BLe Batch
,11-03 23:10:10.972  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.972  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 23:10:10.972  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-03 23:10:10.972  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 23:10:10.972  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 23:10:10.972  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.972  5501  5548 D BluetoothAdapter: STATE_ON
,11-03 23:10:10.974  4569  4628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 23:10:10.974  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:10.974  4569  4631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 23:10:10.975  4569  4788 D BtGatt.GattService: registerClient() - UUID=c397070c-de0b-4845-a89c-21afd68cd116
11-03 23:10:10.975  4569  4628 D BtGatt.GattService: onClientRegistered() - UUID=c397070c-de0b-4845-a89c-21afd68cd116, clientIf=5
,11-03 23:10:10.975  5501  5512 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 23:10:10.976  4569  4581 D BtGatt.GattService: start scan with filters
11-03 23:10:10.978  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 23:10:10.978  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.978  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 23:10:10.978  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.978  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 23:10:10.978  5501  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 23:10:10.979  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.979  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 23:10:10.979  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 23:10:10.979  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.979  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.979  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 23:10:10.979  4569  4628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:10:10.979  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:10.980  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 23:10:10.980  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.981  4569  4631 D BtGatt.ScanManager: handling starting scan
11-03 23:10:10.983  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.983  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:10:10.983  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.983  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:10.983  5501  5548 I io.jxcore.node.ConnectionHelper: start: OK
11-03 23:10:10.983  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.985  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.985  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.985  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.985  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:10:10.985  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:10:10.986  4569  4628 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 23:10:10.986  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:10.987  4569  4631 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 23:10:10.991  4569  4628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 23:10:10.991  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:10.991  4569  4631 D BtGatt.ScanManager: Starting BLE batch scan
11-03 23:10:10.991  4569  4631 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 23:10:10.999  4569  4628 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 23:10:10.999  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:10:11.004  4569  4628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 23:10:11.004  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:10:11.487  5501  5501 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-03 23:10:11.487  5501  5501 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-03 23:10:11.487  5501  5501 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 23:10:12.847   929  2854 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 23:10:12.855   929  2854 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-03 23:10:15.873   929  2854 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 23:10:15.880   929  2854 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-03 23:10:15.983  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 23:10:15.984  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:15.984  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-03 23:10:15.984  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 23:10:15.984  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 23:10:15.984  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:15.984  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 23:10:15.984  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:10:15.985  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 23:10:15.985  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-03 23:10:15.985  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:15.985  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:15.985  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:15.986  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 23:10:15.986  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:15.987  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:10:15.988  4569  4581 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 23:10:15.989  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 23:10:15.990  4569  4631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 23:10:15.991  5501  5548 D BluetoothAdapter: STATE_ON
,11-03 23:10:15.993  4569  4582 D BtGatt.GattService: stopScan() - queue size =1
,11-03 23:10:16.000  4569  4798 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 23:10:16.001  4569  4569 D BtGatt.ScanManager: awakened up at time 107552
11-03 23:10:16.002  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 23:10:16.003  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:16.003  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 23:10:16.003  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:16.006   929  3726 I ActivityManager: Killing 5185:com.android.settings/1000 (adj 15): empty #17
11-03 23:10:16.006  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:16.006  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:16.007  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:16.007  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 23:10:16.007  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:16.007  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:16.007  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:16.008  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-03 23:10:16.008  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-03 23:10:16.041  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-03 23:10:16.041  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:16.043  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:16.043  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:10:16.043  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:16.043  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:16.043  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-03 23:10:16.043  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-03 23:10:16.043  5501  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-03 23:10:16.044  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:10:16.044  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-03 23:10:16.044  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 23:10:16.044  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:10:16.044  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 23:10:16.044  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,11-03 23:10:16.044  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:10:16.046  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:10:16.046  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:10:16.046  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:10:16.046  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:10:16.046  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 23:10:16.055  4569  4628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-03 23:10:16.055  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:16.055  4569  4628 D BtGatt.GattService: current time is 107607673680
,11-03 23:10:16.055  4569  4628 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -85, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -86, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -75, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 23:10:16.056  4569  4628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 23:10:16.056  4569  4628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 23:10:16.056  4569  4628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 23:10:16.056  4569  4628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 23:10:16.056  4569  4628 E BtGatt.ContextMap: Context not found for ID 5
,11-03 23:10:16.063  4569  4628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 23:10:16.063  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:16.063  4569  4631 D BtGatt.ScanManager: stopping BLe Batch
,11-03 23:10:16.067  4569  4628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 23:10:16.068  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:10:16.068  4569  4631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 23:10:16.072  4569  4628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 23:10:16.072  4569  4628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:10:16.547  5501  5501 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 23:10:16.548  5501  5501 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:16.548  5501  5501 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 23:10:21.045  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:21.045  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 23:10:21.045  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:21.046  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:21.046  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:10:21.046  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:10:21.046  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:10:21.046  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:21.047  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.047  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.047  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:21.047  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 23:10:21.050  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.054  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.054  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.055  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.055  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 23:10:21.055  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:21.055  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:21.055  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.056  5501  5548 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-03 23:10:21.058  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:21.058  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:21.059  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:21.059  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 23:10:21.059  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:21.059  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:21.059  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.059  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
,11-03 23:10:21.060  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:21.060  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.063  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.064  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.064  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.064  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:21.064  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:21.064  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:21.064  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.066  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 23:10:21.067  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:21.067  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 23:10:21.067  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:21.067  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:21.067  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:21.067  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
,11-03 23:10:21.067  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.068  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.068  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:21.068  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.071  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.071  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.072  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.072  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 23:10:21.072  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:21.072  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.072  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
,11-03 23:10:21.074  5501  5548 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-03 23:10:21.074  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:21.074  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:21.074  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 23:10:21.074  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:21.075  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:21.075  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:21.075  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:21.075  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.075  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:21.075  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.077  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.077  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.078  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.078  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:21.078  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:21.078  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.078  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.079  5501  5548 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-03 23:10:21.079  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 23:10:21.079  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:21.080  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:21.080  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:21.080  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:10:21.080  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:21.080  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.080  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.080  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:21.080  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.082  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.083  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.083  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.083  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:21.083  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:21.083  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.083  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
,11-03 23:10:21.085  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-03 23:10:21.086  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 23:10:21.086  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 23:10:21.086  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 23:10:21.086  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 23:10:21.086  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 23:10:21.086  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-03 23:10:21.086  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 23:10:21.086  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 23:10:21.087  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 23:10:21.087  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:21.087  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:21.087  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:21.087  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:21.088  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:21.088  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:21.088  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.088  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:21.088  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.090  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.090  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.091  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.091  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:21.091  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:21.091  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.091  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.092  5501  5548 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 23:10:21.092  5501  5548 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-03 23:10:21.092  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-03 23:10:21.097  5501  5548 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-03 23:10:21.098  5501  5548 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-03 23:10:21.098  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-03 23:10:21.098  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 23:10:21.098  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 23:10:21.098  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-03 23:10:21.098  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-03 23:10:21.098  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-03 23:10:21.098  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 23:10:21.099  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 23:10:21.099  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 23:10:21.099  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 23:10:21.099  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-03 23:10:21.099  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 23:10:21.099  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-03 23:10:21.099  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 23:10:21.099  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-03 23:10:21.099  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-03 23:10:21.099  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 23:10:21.099  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-03 23:10:21.100  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 23:10:21.100  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 23:10:21.100  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-03 23:10:21.100  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 23:10:21.100  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-03 23:10:21.100  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 23:10:21.100  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-03 23:10:21.100  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-03 23:10:21.100  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 23:10:21.100  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 23:10:21.100  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 23:10:21.101  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-03 23:10:21.101  5501  5548 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-03 23:10:21.102  5501  5548 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 23:10:21.102  5501  5548 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-03 23:10:21.103  5501  5548 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 23:10:21.103  5501  5548 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 23:10:21.103  5501  5548 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-03 23:10:21.103  5501  5548 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-03 23:10:21.103  5501  5548 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 23:10:21.103  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-03 23:10:21.108  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-03 23:10:21.109  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-03 23:10:21.109  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-03 23:10:21.110  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,11-03 23:10:21.110  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-03 23:10:21.110  5501  5548 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-03 23:10:21.110  5501  5548 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 23:10:21.111  5501  5548 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-03 23:10:21.111  5501  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 129)
11-03 23:10:21.111  5501  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
,11-03 23:10:21.112  5501  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,11-03 23:10:21.112  5501  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-03 23:10:21.113  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:21.114  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:21.114  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:21.114  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:21.114  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:10:21.114  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-03 23:10:21.116  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:21.116  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.116  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.116  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:21.117  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.118  5501  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 129
11-03 23:10:21.118  5501  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,11-03 23:10:21.119  4798  4798 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32408]" dev="sockfs" ino=32408 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 23:10:21.118  5501  5561 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-03 23:10:21.118  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.118  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.118  5501  5561 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 23:10:21.118  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.118  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:21.118  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:21.119  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.119  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.119  4798  4798 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32408]" dev="sockfs" ino=32408 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 23:10:21.119  5501  5548 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-03 23:10:21.120  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:21.120  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:21.120  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:21.121  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:21.121  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:21.121  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:21.121  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.121  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.121  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:10:21.121  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.123  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.123  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.123  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.123  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:21.123  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:21.123  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.123  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
,11-03 23:10:21.124  5501  5548 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-03 23:10:21.125  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:21.125  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:21.125  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:21.125  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:21.125  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:21.125  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:21.126  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:21.126  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.126  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:21.126  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.127  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.127  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.127  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.127  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:21.127  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:21.127  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:21.128  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.129  5501  5548 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-03 23:10:21.129  5501  5548 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-03 23:10:21.129  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-03 23:10:21.129  5501  5548 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-03 23:10:21.129  5501  5548 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 23:10:21.129  5501  5548 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-03 23:10:21.129  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 23:10:21.129  5501  5548 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-03 23:10:21.130  5501  5548 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 23:10:21.130  5501  5548 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,11-03 23:10:21.130  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 23:10:21.130  5501  5548 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-03 23:10:21.130  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:21.130  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:21.130  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:21.131  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:21.131  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:21.131  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
,11-03 23:10:21.131  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.131  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.131  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:21.132  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.133  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.133  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:21.133  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:21.133  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:21.134  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:21.134  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.134  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:21.134  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:21.134  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:21.134  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:21.135  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:21.135  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
,11-03 23:10:21.135  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:10:22.695   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-03 23:10:22.695   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 23:10:26.135  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:26.136  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
,11-03 23:10:26.136  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:26.136  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:26.136  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:26.137  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:26.137  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 23:10:26.137  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:26.137  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:26.137  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:26.138  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:26.138  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:26.138  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:26.138  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:26.138  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:26.142  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:26.142  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.142  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.143  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:26.143  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 23:10:26.143  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:26.143  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:26.147  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 23:10:26.149  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 23:10:26.149  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 23:10:26.155  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-03 23:10:26.157  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 23:10:26.157  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-03 23:10:26.157  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 23:10:26.157  5501  5563 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 23:10:26.157  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 23:10:26.157  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 23:10:26.157  5501  5501 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-03 23:10:26.158  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:26.158  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-03 23:10:26.158  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 23:10:26.158  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-03 23:10:26.158  5501  5563 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 23:10:26.158  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 23:10:26.159  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 23:10:26.159  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 23:10:26.160  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:26.160  5501  5501 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-03 23:10:26.160  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:26.160  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:10:26.160  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 23:10:26.160  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 23:10:26.160  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:26.159  4582  4582 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32410]" dev="sockfs" ino=32410 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 23:10:26.159  4582  4582 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32410]" dev="sockfs" ino=32410 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 23:10:26.161  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.162  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:10:26.162  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.162  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.162  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:26.162  5501  5563 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 23:10:26.162  5501  5563 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 23:10:26.162  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:26.162  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:10:26.162  5501  5563 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 23:10:26.162  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 23:10:26.162  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:26.162  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:10:26.162  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:26.162  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:10:26.162  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 23:10:26.162  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:26.162  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:26.162  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:26.162  5501  5501 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 23:10:26.163  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:26.163  5501  5501 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:26.163  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.164  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.164  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:26.164  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.164  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:26.165  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:26.165  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:26.165  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:26.166  5501  5548 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-03 23:10:26.166  5501  5548 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 23:10:26.166  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 23:10:26.167  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 23:10:26.167  5501  5548 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 23:10:26.167  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:26.167  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 23:10:26.167  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:26.167  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:26.167  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:26.167  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:26.167  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:26.167  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:26.167  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:10:26.168  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.170  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.170  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:10:26.170  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.170  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:26.171  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 23:10:26.171  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:26.171  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
,11-03 23:10:26.178  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 23:10:26.178  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:26.178  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:26.178  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:26.178  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:26.178  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:26.179  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:26.179  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
11-03 23:10:26.179  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:10:26.179  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.180  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.180  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.180  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.180  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:10:26.180  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:26.180  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:26.180  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
,11-03 23:10:26.181  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:10:26.181  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:10:26.181  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:10:26.181  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:10:26.181  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:10:26.181  5501  5548 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33416d not in the list
11-03 23:10:26.181  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:26.181  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
,11-03 23:10:26.181  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:26.182  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.183  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.183  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.183  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:10:26.183  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 23:10:26.183  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:10:26.183  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:26.183  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1041a2 not in the list
,11-03 23:10:26.185  5501  5548 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-03 23:10:26.185  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 23:10:26.186  5501  5548 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-03 23:10:26.186  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 23:10:26.186  5501  5548 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-03 23:10:26.186  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 23:10:26.187  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 23:10:26.188  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-03 23:10:26.188  5501  5548 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-03 23:10:26.188  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 23:10:26.188  5501  5548 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-03 23:10:26.188  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 23:10:26.188  5501  5548 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-03 23:10:26.188  5501  5548 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-03 23:10:26.189  5501  5548 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-03 23:10:26.189  5501  5548 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-03 23:10:26.189  5501  5548 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-03 23:10:26.190  5501  5548 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-03 23:10:26.190  5501  5548 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-03 23:10:26.190  5501  5548 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-03 23:10:26.190  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:10:26.191  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c5c5a23 added. We now have 3 listener(s)
11-03 23:10:26.191  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:10:26.193  5501  5548 D BluetoothAdapter: enable(): BT is already enabled..!
,11-03 23:10:26.193   929  3731 D WifiService: setWifiEnabled: true pid=5501, uid=10077
,11-03 23:10:26.193   929  3731 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 23:10:26.248  4569  4773 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-03 23:10:26.248  4569  4776 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-03 23:10:26.248  5501  5561 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-03 23:10:26.249  5501  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-03 23:10:26.249  5501  5561 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 129)
,11-03 23:10:26.663  5501  5501 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 23:10:27.696   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:28.697   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:29.625   929  2852 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 23:10:29.698   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:29.885   929  5277 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121436, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 23:10:30.699   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:31.199  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 23:10:31.199  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@db3b20 added. We now have 4 listener(s)
11-03 23:10:31.199  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:10:31.213  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:31.213  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@db3b20 removed from the list
,11-03 23:10:31.214  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:10:31.215  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:10:31.216  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@41c1cd9 added. We now have 4 listener(s)
,11-03 23:10:31.217  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:10:31.220  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:31.221  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@41c1cd9 removed from the list
11-03 23:10:31.221  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:31.222  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:10:31.222  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@998969e added. We now have 4 listener(s)
11-03 23:10:31.223  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:10:31.227   929  3321 D WifiService: setWifiEnabled: false pid=5501, uid=10077
,11-03 23:10:31.227   929  3321 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 23:10:31.232   929  2852 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-03 23:10:31.232   929  2852 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-03 23:10:31.233   929  2852 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 23:10:31.233   929  2852 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 23:10:31.240  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:10:31.241  4569  4624 D BluetoothAdapterState: Current state: ON, message: 23
,11-03 23:10:31.241  4569  4624 D BluetoothAdapterProperties: Setting state to 13
11-03 23:10:31.241  4569  4624 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-03 23:10:31.242  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 23:10:31.242  4569  4624 D BluetoothAdapterProperties: onBluetoothDisable()
11-03 23:10:31.243  4569  4624 I BluetoothAdapterState: Entering PendingCommandState
11-03 23:10:31.244  4569  4628 D BluetoothAdapterProperties: Scan Mode:20
11-03 23:10:31.244  4569  4624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-03 23:10:31.250   929  5278 D DhcpClient: Clearing IP address
11-03 23:10:31.250   508   925 D CommandListener: Clearing all IP addresses on wlan0
,11-03 23:10:31.252  4569  4569 D HeadsetService: Received stop request...Stopping profile...
,11-03 23:10:31.259   508   925 D CommandListener: Setting iface cfg
,11-03 23:10:31.265   929  5279 D DhcpClient: Receive thread stopped
,11-03 23:10:31.266  3483  5343 V NativeCrypto: Read error: ssl=0x7f72049a80: I/O error during system call, Connection timed out
11-03 23:10:31.268   929   942 I ActivityManager: Start proc 5567:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-03 23:10:31.269  3483  5343 V NativeCrypto: SSL shutdown failed: ssl=0x7f72049a80: I/O error during system call, Broken pipe
11-03 23:10:31.272   929   929 D BluetoothHeadset: Proxy object disconnected
11-03 23:10:31.273  3652  3911 D BluetoothHeadset: Proxy object disconnected
11-03 23:10:31.273  4569  4569 D BluetoothMapService: onReceive
11-03 23:10:31.273   929   929 D BluetoothHeadset: Proxy object disconnected
11-03 23:10:31.273  4569  4569 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 23:10:31.274  4569  4569 D BluetoothMapService: STATE_TURNING_OFF
,11-03 23:10:31.274  3020  3042 D BluetoothHeadset: Proxy object disconnected
11-03 23:10:31.274  3020  3020 D HeadsetProfile: Bluetooth service disconnected
11-03 23:10:31.274   929   929 D BluetoothHeadset: Proxy object disconnected
11-03 23:10:31.274   929  3726 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-03 23:10:31.274  4569  4569 D A2dpService: Received stop request...Stopping profile...
11-03 23:10:31.275  4569  4793 D A2dpStateMachine: Exit Disconnected: -1
11-03 23:10:31.275   929  5276 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-03 23:10:31.277   929   929 D BluetoothA2dp: Proxy object disconnected
11-03 23:10:31.277  3020  3020 D BluetoothA2dp: Proxy object disconnected
11-03 23:10:31.277  4569  4569 V BluetoothAdapterState: isTurningOff()=true
11-03 23:10:31.278  4569  4569 V BluetoothAdapterState: isTurningOn()=false
,11-03 23:10:31.278  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:31.278  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:31.279  4569  4569 D HidService: Received stop request...Stopping profile...
11-03 23:10:31.279  4569  4569 D HidService: Stopping Bluetooth HidService
11-03 23:10:31.279  3020  3020 D BluetoothInputDevice: Proxy object disconnected
11-03 23:10:31.279  3020  3020 D HidProfile: Bluetooth service disconnected
11-03 23:10:31.280  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:10:31.280  5501  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 23:10:31.280  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:31.280  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:31.280  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:10:31.280  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:10:31.280  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 23:10:31.280  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:10:31.280  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 23:10:31.281  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 23:10:31.281  5501  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 23:10:31.281   929  5276 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-03 23:10:31.281  5501  5548 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 23:10:31.282   929  2854 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-03 23:10:31.282   929  2854 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-03 23:10:31.283   929  2854 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-03 23:10:31.285   534   534 E Parcel  : Reading a NULL string not supported here.
,11-03 23:10:31.285   929  2854 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-03 23:10:31.285   929  2854 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-03 23:10:31.286  4569  4569 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 23:10:31.286  4569  4569 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 23:10:31.286  4569  4569 D BluetoothMapService: MAP Service closeService in
11-03 23:10:31.286  4569  4773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:10:31.286  4569  4569 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 23:10:31.286  4569  4773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:10:31.287  4569  4773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:10:31.287  4569  4569 D ObexServerSockets0: shutdown(block = true)
11-03 23:10:31.287  4569  4628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 23:10:31.287  4569  4800 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-03 23:10:31.287  4569  4628 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-03 23:10:31.287  4569  4569 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 23:10:31.288  4569  4569 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 23:10:31.288  4569  4776 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 23:10:31.288  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:10:31.288  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:10:31.288  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:31.288  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:31.288  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:10:31.288  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:10:31.288  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:10:31.288  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:10:31.288  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 23:10:31.288   929   929 D RttService: SCAN_AVAILABLE : 1
11-03 23:10:31.288  4569  4801 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 23:10:31.288   929  2961 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-03 23:10:31.289  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:10:31.289  5501  5501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 23:10:31.291  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:10:31.291  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:10:31.291  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:31.291  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported:, SUPPORTED
11-03 23:10:31.291  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:10:31.291  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:10:31.291  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:10:31.291  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:10:31.291  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 23:10:31.292  4569  4569 D HealthService: Received stop request...Stopping profile...
11-03 23:10:31.294   929  2854 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-03 23:10:31.295  4569  4569 I BtOppRfcommListener: stopping Accept Thread
11-03 23:10:31.295  4569  5209 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 23:10:31.296  4569  5209 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-03 23:10:31.296  3617  3755 W QCNEJ   : |CORE| network lost: 100
11-03 23:10:31.296  3617  3755 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-03 23:10:31.297  4569  4569 D PanService: Received stop request...Stopping profile...
11-03 23:10:31.298  4569  4569 V BluetoothAdapterState: isTurningOff()=true
11-03 23:10:31.298  4569  4569 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:31.298  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:31.298  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:31.299  4569  4628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 23:10:31.299  4569  4773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:10:31.299  4569  4773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:10:31.299  4569  4773 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 23:10:31.299  4569  4773 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 23:10:31.299  4569  4569 D BluetoothMapService: Received stop request...Stopping profile...
11-03 23:10:31.299  4569  4773 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 23:10:31.299  4569  4569 D BluetoothMapService: stop()
11-03 23:10:31.299  4569  4773 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 23:10:31.299  4569  4569 D BluetoothMapAppObserver: deinitObservers()
11-03 23:10:31.299  4569  4569 D BluetoothMapAppObserver: removeReceiver()
11-03 23:10:31.300  4569  4569 V BluetoothAdapterState: isTurningOff()=true
11-03 23:10:31.300  4569  4569 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:31.300  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:31.300  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:31.301  4569  4569 D SapService: Received stop request...Stopping profile...
11-03 23:10:31.301  4569  4569 V SapService: stop()
11-03 23:10:31.301  4569  4569 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 23:10:31.302  4569  4569 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 23:10:31.302  4569  4628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 23:10:31.302  4569  4569 V BluetoothAdapterState: isTurningOff()=true
,11-03 23:10:31.302  4569  4569 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:31.302  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 23:10:31.302  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 23:10:31.302  4569  4569 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-03 23:10:31.302  4569  4569 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-03 23:10:31.303  4569  4628 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-03 23:10:31.303  4569  4569 V BluetoothAdapterState: isTurningOff()=true
11-03 23:10:31.303  4569  4569 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:31.303  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:31.303  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 23:10:31.303  4569  4569 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 23:10:31.303  4569  4569 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 23:10:31.305  4569  4569 D BluetoothMapService: MAP Service closeService in
11-03 23:10:31.305  4569  4569 V BluetoothAdapterState: isTurningOff()=true
11-03 23:10:31.305  4569  4569 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:31.305  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:31.305  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 23:10:31.305  4569  4569 D BluetoothMapService: cleanup()
11-03 23:10:31.305  4569  4569 D BluetoothMapService: MAP Service closeService in
11-03 23:10:31.305  4569  4569 V BluetoothAdapterState: isTurningOff()=true
11-03 23:10:31.305  4569  4569 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:31.305  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:31.305  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:31.306  4569  4624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-03 23:10:31.306  4569  4624 D BluetoothAdapterProperties: Setting state to 15
11-03 23:10:31.306  4569  4624 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 23:10:31.306  4569  4624 I BluetoothAdapterState: Entering BleOnState
11-03 23:10:31.309  3020  3020 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 23:10:31.309  3020  3020 D PanProfile: Bluetooth service disconnected
11-03 23:10:31.309  3020  3020 D BluetoothMap: Proxy object disconnected
,11-03 23:10:31.309  3020  3020 D MapProfile: Bluetooth service disconnected
11-03 23:10:31.311  3652  3663 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:10:31.312  3020  5586 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 23:10:31.313   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-03 23:10:31.313   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:10:31.313  3020  5586 D BluetoothMap: onBluetoothStateChange: up=false
11-03 23:10:31.313   929  2852 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-03 23:10:31.313  3020  5588 D BluetoothPan: onBluetoothStateChange on: false
11-03 23:10:31.314  3020  3886 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:10:31.314   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 23:10:31.314   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-03 23:10:31.314  3020  3042 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 23:10:31.315  3020  5588 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 23:10:31.316  4569  4624 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 23:10:31.316  4569  4624 D BluetoothAdapterProperties: Setting state to 16
11-03 23:10:31.316  4569  4624 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 23:10:31.317  4569  4624 D BluetoothAdapterProperties: onBleDisable
,11-03 23:10:31.317  4569  4624 I BluetoothAdapterState: Entering PendingCommandState
11-03 23:10:31.317  4569  4625 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-03 23:10:31.318  4569  4628 D BluetoothAdapterProperties: Scan Mode:20
11-03 23:10:31.318  4569  4773 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 23:10:31.318  4569  4773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:10:31.322  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 23:10:31.322  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:10:31.322  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:31.322  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:31.322  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:10:31.322  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:10:31.322  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:10:31.322  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:10:31.322  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 23:10:31.323  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:10:31.326   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-03 23:10:31.331   929  2852 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 23:10:31.337  5567  5567 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-03 23:10:31.346   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:10:31.347   508   925 D CommandListener: Clearing all IP addresses on wlan0
,11-03 23:10:31.347   929  2854 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-03 23:10:31.347   929  2854 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 23:10:31.348   508   925 D TetherController: Setting IP forward enable = 0
11-03 23:10:31.350   929   946 D Tethering: MasterInitialState.processMessage what=3
11-03 23:10:31.352   929  2852 D DhcpClient: doQuit
11-03 23:10:31.353   929  2852 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 23:10:31.353  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:10:31.353   929  5278 D DhcpClient: onQuitting
11-03 23:10:31.353  3353  3353 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-03 23:10:31.354  3866  3866 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-03 23:10:31.355  5162  5162 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@46e15e3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-03 23:10:31.356  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 23:10:31.356  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:10:31.356  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:31.356  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:31.356  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 23:10:31.356  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:10:31.356  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:10:31.356  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:10:31.356  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 23:10:31.357  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:10:31.357  5501  5501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 23:10:31.360  5567  5567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 23:10:31.365   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@490625:true
,11-03 23:10:31.365  3483  3483 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 23:10:31.368  3353  3353 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-03 23:10:31.373  3353  3353 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 23:10:31.387  5567  5567 D LocalBluetoothProfileManager: Adding local MAP profile
,11-03 23:10:31.390  5567  5567 D BluetoothMap: Create BluetoothMap proxy object
,11-03 23:10:31.398  5567  5567 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-03 23:10:31.398   508   925 E Netd    : netlink response contains error (No such file or directory)
11-03 23:10:31.399   508   925 D TetherController: Setting IP forward enable = 0
11-03 23:10:31.400   929  2854 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-03 23:10:31.403  3353  3353 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 23:10:31.404  5567  5567 D DockEventReceiver: finishStartingService: stopping service
,11-03 23:10:31.407  5567  5567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 23:10:31.412  5567  5567 D DockEventReceiver: finishStartingService: stopping service
,11-03 23:10:31.412  3483  3483 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 23:10:31.414   929  3060 I ActivityManager: Killing 5301:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-03 23:10:31.415  3353  3353 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 23:10:31.430  3735  3735 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-03 23:10:31.435  3735  3735 D SystemUpdateService: onCreate
,11-03 23:10:31.437  3735  3735 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 23:10:31.446  3735  3735 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-03 23:10:31.447  3735  5607 I SystemUpdateService: active receiver: enabled
11-03 23:10:31.450  3735  4182 I iu.UploadsManager: num queued entries: 0
11-03 23:10:31.450  3735  4182 I iu.UploadsManager: num updated entries: 0
11-03 23:10:31.451  3735  4182 I iu.SyncManager: NEXT; no task
11-03 23:10:31.455  3735  3735 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-03 23:10:31.456  3735  3735 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-03 23:10:31.459  3735  5607 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-03 23:10:31.461  3735  5607 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-03 23:10:31.462  3735  5607 I SystemUpdateService: now status is 0 (complete)
11-03 23:10:31.462  3735  5607 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 23:10:31.462  3735  5607 I SystemUpdateService: file has been verified
11-03 23:10:31.462  3735  5607 I SystemUpdateService: OTA package size = 21989297
11-03 23:10:31.467  3735  5607 I SystemUpdateService: showing system update notification
11-03 23:10:31.467   929  3060 I ActivityManager: Start proc 5609:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
11-03 23:10:31.479   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-03 23:10:31.481  3735  3735 D SystemUpdateService: onDestroy
,11-03 23:10:31.500  5609  5609 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-03 23:10:31.503  5609  5609 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 23:10:31.510  5609  5609 D SprintDMHelper: simOperator: 
,11-03 23:10:31.510  5609  5609 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 23:10:31.519   929  2852 D wifi    : In wifi stop Hal
,11-03 23:10:31.519   929  2852 D wifi    : halHandle = 0x7f5f86fa40, mVM = 0x7f7becd140, mCls = 0x100a02
11-03 23:10:31.520   929  3352 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 23:10:31.520   929  3352 D WifiHAL : Got a signal to exit!!!
11-03 23:10:31.520   929  3352 I WifiHAL : Exit wifi_event_loop
11-03 23:10:31.520   929  2852 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-03 23:10:31.520   929  2852 E WifiHAL : Event processing terminated
11-03 23:10:31.522  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:10:31.522   929  2852 D wifi    : In wifi cleaned up handler
11-03 23:10:31.522   929  2852 I WifiHAL : Internal cleanup completed
11-03 23:10:31.522  3935  4092 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 23:10:31.524  4926  4926 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 23:10:31.528  4569  4628 I bt_hci  : shut_down
,11-03 23:10:31.540   929  3321 I ActivityManager: Start proc 5622:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
11-03 23:10:31.540   929  3352 D wifi    : set interface wlan0 flags (DOWN)
,11-03 23:10:31.540   929  2852 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 23:10:31.542   929  3731 I ActivityManager: Killing 5162:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-03 23:10:31.543  4569  4632 D bt_hwcfg: hw_epilog_process
11-03 23:10:31.543  4569  4632 I bt_vendor: low_power_mode_cb
11-03 23:10:31.546  4569  4632 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-03 23:10:31.546  4569  4632 I bt_vendor: epilog_cb
11-03 23:10:31.546  4569  4632 I bt_hci  : epilog_finished_callback
,11-03 23:10:31.569  4569  4628 I bt_hci_h4: hal_close
,11-03 23:10:31.569  4569  4628 I bt_userial_vendor: device fd = 54 close
,11-03 23:10:31.578  5622  5622 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-03 23:10:31.585   929  3732 I ActivityManager: Killing 3764:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-03 23:10:31.674  4569  4625 D bt_stack_manager: event_shut_down_stack finished.
,11-03 23:10:31.674  4569  4624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 23:10:31.676  4569  4569 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 23:10:31.677  4569  4624 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-03 23:10:31.677  4569  4569 D BtGatt.GattService: Received stop request...Stopping profile...
11-03 23:10:31.677  4569  4569 D BtGatt.GattService: stop()
11-03 23:10:31.677  4569  4569 D BtGatt.AdvertiseManager: advertise clients cleared
,11-03 23:10:31.679  4569  4569 V BluetoothAdapterState: isTurningOff()=false
11-03 23:10:31.679  4569  4569 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:31.679  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:31.679  4569  4569 V BluetoothAdapterState: isBleTurningOff()=true
11-03 23:10:31.679  4569  4624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-03 23:10:31.679  4569  4624 D BluetoothAdapterProperties: Setting state to 10
11-03 23:10:31.679  4569  4624 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-03 23:10:31.680   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
11-03 23:10:31.681  4569  4624 I BluetoothAdapterState: Entering OffState
,11-03 23:10:31.686  4569  4569 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-03 23:10:31.687  4569  4569 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-03 23:10:31.687  4569  4569 I BluetoothServiceJni: cleanupNative: return from cleanup
11-03 23:10:31.688  4569  4625 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 23:10:31.692  4569  4569 I art     : System.exit called, status: 0
,11-03 23:10:31.693  4569  4569 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 23:10:31.700   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:31.718   929  3731 I ActivityManager: Process com.android.bluetooth (pid 4569) has died
,11-03 23:10:31.743   929   946 D Tethering: InitialState.processMessage what=4
,11-03 23:10:31.746   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 23:10:32.700   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 23:10:36.284   929  3726 D WifiService: setWifiEnabled: true pid=5501, uid=10077
,11-03 23:10:36.284   929  3726 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 23:10:36.293   508   925 D SoftapController: Softap fwReload - Ok
,11-03 23:10:36.299   508   925 D CommandListener: Setting iface cfg
,11-03 23:10:36.300   508   925 D CommandListener: Trying to bring down wlan0
,11-03 23:10:36.301   508   925 D CommandListener: Clearing all IP addresses on wlan0
,11-03 23:10:36.307   929  2852 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 23:10:36.887   929  2852 D wifi    : set interface wlan0 flags (UP)
,11-03 23:10:36.887   929  2852 I WifiHAL : Initializing wifi
11-03 23:10:36.887   929  2852 I WifiHAL : Creating socket
11-03 23:10:36.890   929  2852 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-03 23:10:36.890   929  2852 D wifi    : Did set static halHandle = 0x7f5f86fa40
11-03 23:10:36.890   929  2852 D wifi    : halHandle = 0x7f5f86fa40, mVM = 0x7f7becd140, mCls = 0x101966
,11-03 23:10:36.890   929  2852 D wifi    : array field set
11-03 23:10:36.890   929  2852 I WifiNative-HAL: interface[0] = wlan0
11-03 23:10:36.890   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-03 23:10:36.892   929  5640 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547063528000
11-03 23:10:36.893   929  5640 D wifi    : waitForHalEvents called, vm = 0x7f7becd140, obj = 0x101966, env = 0x7f5f879940
,11-03 23:10:36.950  5641  5641 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 23:10:36.994   929  2852 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 23:10:37.004  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:10:37.012  5641  5641 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 23:10:37.018  5641  5641 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 23:10:37.018  5641  5641 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 23:10:37.028   929  2852 D WifiConfigStore: Loading config and enabling all networks 
,11-03 23:10:37.030  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:10:37.030  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:10:37.030  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:37.030  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:37.030  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:10:37.030  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:10:37.030  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:10:37.030  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:10:37.030  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 23:10:37.030  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:10:37.030  5501  5501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 23:10:37.042   929  2852 D WifiConfigStore: loaded 0 passpoint configs
,11-03 23:10:37.042   929  2852 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-03 23:10:37.043   929  2852 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-03 23:10:37.043   929  2852 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-03 23:10:37.043   929  2852 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-03 23:10:37.044   929  2852 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-03 23:10:37.044   929  2852 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-03 23:10:37.044   929  2852 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 23:10:37.045   929  2852 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 23:10:37.045   929  2852 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 23:10:37.045   929  2852 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-03 23:10:37.045   929  2852 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-03 23:10:37.045   929  2852 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 23:10:37.047   929  2852 D WifiNative-HAL: Setting external_sim to 1
,11-03 23:10:37.047   929  2852 D wifi    : setting dfs flag to true, 0x7f60690ac0
,11-03 23:10:37.047  4926  4926 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 23:10:37.047   929  2852 D WifiStateMachine: Setting OUI to DA-A1-19
11-03 23:10:37.047   929  2852 D wifi    : setting scan oui 0x7f60690ac0
11-03 23:10:37.047   929  2852 D WifiHAL : Sending mac address OUI
,11-03 23:10:37.050   929  2852 E native  : do suspend false
,11-03 23:10:37.056   929  2852 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-03 23:10:37.056   929   929 D RttService: SCAN_AVAILABLE : 3
11-03 23:10:37.056   929  2961 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 23:10:37.060   508   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-03 23:10:37.062   508   925 D CommandListener: Setting iface cfg
,11-03 23:10:37.064   929  2851 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
,11-03 23:10:37.064   929  2851 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 23:10:37.070   929  2851 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 23:10:37.071   929  2851 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 23:10:37.077   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128629 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-03 23:10:37.701   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:38.702   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:39.703   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:40.228  5641  5641 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 23:10:40.244  5641  5641 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 23:10:40.256  5641  5641 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 23:10:40.264  5641  5641 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 23:10:40.294   929  2852 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 23:10:40.295   929  2852 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-03 23:10:40.295   929  2852 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:10:40.306   929  2852 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 23:10:40.337   929  2852 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 23:10:40.343  5641  5641 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 23:10:40.704   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:40.798  5641  5641 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 23:10:40.833  5641  5641 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 23:10:40.833  5641  5641 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 23:10:40.845   929  2852 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 23:10:40.846   929  2852 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:10:40.846   929  2854 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 23:10:40.865   929  2852 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:10:40.879   508   925 D CommandListener: Setting iface cfg
,11-03 23:10:40.888   929  2852 D WifiStateMachine: Start Dhcp Watchdog 2
,11-03 23:10:40.899   929  2854 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-03 23:10:40.899   929  2852 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-03 23:10:40.899   929  2854 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-03 23:10:40.902   929  5647 D DhcpClient: Receive thread started
,11-03 23:10:40.982   929  2852 E native  : do suspend false
,11-03 23:10:40.997   929  5646 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 23:10:41.019   929  5647 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172708, domain null
,11-03 23:10:41.020   929  5646 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172708 seconds
,11-03 23:10:41.023   929  5646 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 23:10:41.037   929  5647 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 23:10:41.038   929  5646 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-03 23:10:41.043   508   925 D CommandListener: Setting iface cfg
,11-03 23:10:41.049   929  2852 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 23:10:41.052   929  5646 D DhcpClient: Scheduling renewal in 86399s
,11-03 23:10:41.066   929  2852 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-03 23:10:41.067   929  2852 D WifiConfigStore: No blacklist allowed without epno enabled
,11-03 23:10:41.069   929  2854 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-03 23:10:41.072   929  2854 D ConnectivityService: Adding iface wlan0 to network 101
,11-03 23:10:41.080   929  2852 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-03 23:10:41.132   929  2854 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-03 23:10:41.132   929  2854 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-03 23:10:41.134   929  2854 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-03 23:10:41.136   929  2854 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-03 23:10:41.139   929  2854 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-03 23:10:41.148   929  2854 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-03 23:10:41.153   929  2854 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-03 23:10:41.153   929  2854 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-03 23:10:41.153   929  2854 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-03 23:10:41.153   929  2854 D ConnectivityService:    accepting network in place of null
,11-03 23:10:41.153   929  2852 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-03 23:10:41.153   929  2852 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 23:10:41.154   929  2854 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 23:10:41.161   929  5645 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132713, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 23:10:41.178   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:10:41.198   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:10:41.201   929  2854 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-03 23:10:41.201   929  2854 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-03 23:10:41.202  3617  3755 W QCNEJ   : |CORE| network available: 101
,11-03 23:10:41.202   929  2854 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-03 23:10:41.203  3617  3755 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-03 23:10:41.204   929   946 D Tethering: MasterInitialState.processMessage what=3
,11-03 23:10:41.205  3617  3755 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-03 23:10:41.206  3617  3755 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-03 23:10:41.209  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:10:41.209  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:10:41.209  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:41.209  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:41.209  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:10:41.209  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:10:41.209  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 23:10:41.209  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:10:41.209  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 23:10:41.209  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 23:10:41.209  5501  5501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 23:10:41.216  3866  3866 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-03 23:10:41.219  3735  3735 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 23:10:41.222  3735  3735 D SystemUpdateService: onCreate
11-03 23:10:41.225  3735  3735 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 23:10:41.233  3735  3735 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-03 23:10:41.237  3735  4182 I iu.UploadsManager: num queued entries: 0
,11-03 23:10:41.239   929  5644 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-03 23:10:41.242  3735  5656 I SystemUpdateService: active receiver: enabled
,11-03 23:10:41.245  3735  3735 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 23:10:41.246  3735  3735 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-03 23:10:41.248  5609  5609 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 23:10:41.251  5609  5609 D SprintDMHelper: simOperator: 
11-03 23:10:41.251  5609  5609 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 23:10:41.261  3735  4182 I iu.UploadsManager: num updated entries: 0
,11-03 23:10:41.276  3735  5656 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 23:10:41.277  3735  4182 I iu.SyncManager: NEXT; no task
,11-03 23:10:41.282  3735  5656 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-03 23:10:41.282  3735  5656 I SystemUpdateService: now status is 0 (complete)
11-03 23:10:41.282  3735  5656 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 23:10:41.282  3735  5656 I SystemUpdateService: file has been verified
11-03 23:10:41.282  3735  5656 I SystemUpdateService: OTA package size = 21989297
,11-03 23:10:41.285   929  5644 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 22:10:41 GMT], X-Android-Received-Millis=[1478211041284], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478211041263]}
,11-03 23:10:41.285   929  2854 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-03 23:10:41.285   929  2854 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-03 23:10:41.285   929  2854 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-03 23:10:41.287   929  2854 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-03 23:10:41.288  3735  5656 I SystemUpdateService: showing system update notification
,11-03 23:10:41.288   929  3060 D WifiService: setWifiEnabled: false pid=5501, uid=10077
11-03 23:10:41.289   929  3060 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 23:10:41.290   929  2852 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-03 23:10:41.290   929  2852 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-03 23:10:41.291   929  2852 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 23:10:41.291   929  2852 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:10:41.298   929  5646 D DhcpClient: Clearing IP address
11-03 23:10:41.298   508   925 D CommandListener: Clearing all IP addresses on wlan0
,11-03 23:10:41.300   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 23:10:41.300   508   925 D CommandListener: Setting iface cfg
11-03 23:10:41.302   929  5647 D DhcpClient: Receive thread stopped
11-03 23:10:41.302  3735  3735 D SystemUpdateService: onDestroy
,11-03 23:10:41.308   929  3732 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
11-03 23:10:41.309   929  5644 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-03 23:10:41.310   929  5644 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
11-03 23:10:41.312   929  2854 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-03 23:10:41.313   929  2854 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-03 23:10:41.316   534   534 E Parcel  : Reading a NULL string not supported here.
11-03 23:10:41.317   929   929 D RttService: SCAN_AVAILABLE : 1
11-03 23:10:41.317   929  2961 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-03 23:10:41.319   929  2854 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-03 23:10:41.320   929  2852 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-03 23:10:41.320  3617  3755 W QCNEJ   : |CORE| network lost: 101
11-03 23:10:41.320  3617  3755 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-03 23:10:41.322   929  2852 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 23:10:41.323   929  5644 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,11-03 23:10:41.339   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:10:41.359   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-03 23:10:41.360   508   925 D CommandListener: Clearing all IP addresses on wlan0
11-03 23:10:41.360   929  2854 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-03 23:10:41.360   929  2854 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-03 23:10:41.362   929   946 D Tethering: MasterInitialState.processMessage what=3
,11-03 23:10:41.364  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 23:10:41.364  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:10:41.364  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:41.364  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:41.364  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:10:41.364  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:10:41.364  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:10:41.364  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:10:41.364  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 23:10:41.364  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:10:41.364  5501  5501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 23:10:41.366   929  2852 D DhcpClient: doQuit
11-03 23:10:41.366   929  2852 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 23:10:41.366   929  5646 D DhcpClient: onQuitting
,11-03 23:10:41.367  3866  3866 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-03 23:10:41.367  5641  5641 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-03 23:10:41.369  3735  3735 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 23:10:41.371  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:10:41.371  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:10:41.371  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:41.371  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:41.371  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 23:10:41.371  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:10:41.371  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:10:41.371  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:10:41.371  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 23:10:41.371  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:10:41.371  5501  5501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 23:10:41.375  3735  3735 D SystemUpdateService: onCreate
,11-03 23:10:41.378  3735  3735 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-03 23:10:41.379  5641  5641 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-03 23:10:41.383  5641  5641 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 23:10:41.386  3735  5671 I SystemUpdateService: active receiver: enabled
,11-03 23:10:41.388  3735  3735 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-03 23:10:41.394  3735  4182 I iu.UploadsManager: num queued entries: 0
,11-03 23:10:41.394  3735  4182 I iu.UploadsManager: num updated entries: 0
,11-03 23:10:41.397  3735  3735 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 23:10:41.399  3735  3735 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 23:10:41.401  5609  5609 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 23:10:41.407  5609  5609 D SprintDMHelper: simOperator: 
11-03 23:10:41.408  5609  5609 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-03 23:10:41.408  3735  5671 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 23:10:41.414   508   925 E Netd    : netlink response contains error (No such file or directory)
,11-03 23:10:41.416   929  2854 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-03 23:10:41.416   929  2854 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-03 23:10:41.418  3735  4182 I iu.SyncManager: NEXT; no task
,11-03 23:10:41.419  3735  5671 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-03 23:10:41.419  3735  5671 I SystemUpdateService: now status is 0 (complete)
11-03 23:10:41.420  5641  5641 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 23:10:41.421  3735  5671 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 23:10:41.421  3735  5671 I SystemUpdateService: file has been verified
11-03 23:10:41.423  3735  5671 I SystemUpdateService: OTA package size = 21989297
,11-03 23:10:41.431  5641  5641 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 23:10:41.438  3735  5671 I SystemUpdateService: showing system update notification
,11-03 23:10:41.444   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 23:10:41.445  3735  3735 D SystemUpdateService: onDestroy
,11-03 23:10:41.534   929  2852 D wifi    : In wifi stop Hal
,11-03 23:10:41.534  4926  4926 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 23:10:41.534   929  2852 D wifi    : halHandle = 0x7f5f86fa40, mVM = 0x7f7becd140, mCls = 0x101966
11-03 23:10:41.534   929  5640 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 23:10:41.534   929  5640 D WifiHAL : Got a signal to exit!!!
11-03 23:10:41.534   929  5640 I WifiHAL : Exit wifi_event_loop
11-03 23:10:41.535   929  2852 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-03 23:10:41.535   929  2852 E WifiHAL : Event processing terminated
,11-03 23:10:41.535   929  2852 D wifi    : In wifi cleaned up handler
11-03 23:10:41.535   929  2852 I WifiHAL : Internal cleanup completed
11-03 23:10:41.537  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:10:41.537  3935  4092 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 23:10:41.556   929  5640 D wifi    : set interface wlan0 flags (DOWN)
,11-03 23:10:41.556   929  2852 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 23:10:41.705   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:41.764   929   946 D Tethering: InitialState.processMessage what=4
,11-03 23:10:41.771   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 23:10:42.202   929  2854 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-03 23:10:42.706   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 23:10:46.326   929   946 I ActivityManager: Start proc 5677:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 23:10:46.418  5677  5677 D AdapterServiceConfig: Adding HeadsetService
,11-03 23:10:46.418  5677  5677 D AdapterServiceConfig: Adding A2dpService
11-03 23:10:46.418  5677  5677 D AdapterServiceConfig: Adding HidService
11-03 23:10:46.418  5677  5677 D AdapterServiceConfig: Adding HealthService
11-03 23:10:46.419  5677  5677 D AdapterServiceConfig: Adding PanService
,11-03 23:10:46.419  5677  5677 D AdapterServiceConfig: Adding GattService
11-03 23:10:46.419  5677  5677 D AdapterServiceConfig: Adding BluetoothMapService
11-03 23:10:46.419  5677  5677 D AdapterServiceConfig: Adding SapService
,11-03 23:10:46.431   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17b9109:true
,11-03 23:10:46.431  5677  5677 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 23:10:46.433  5677  5677 I bt_bluedroid: init
,11-03 23:10:46.434  5677  5689 I BluetoothAdapterState: Entering OffState
,11-03 23:10:46.436  5677  5690 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-03 23:10:46.436  5677  5690 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 23:10:46.436  5677  5690 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 23:10:46.436  5677  5690 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-03 23:10:46.437  5677  5677 I bt_bluedroid: get_profile_interface socket
,11-03 23:10:46.439  5677  5677 I bt_bluedroid: get_profile_interface sdp
,11-03 23:10:46.439  5677  5693 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-03 23:10:46.440  5677  5693 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 23:10:46.443  5677  5688 I bt_bluedroid: config_hci_snoop_log
,11-03 23:10:46.444   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-03 23:10:46.448  5677  5689 D BluetoothAdapterState: Current state: OFF, message: 0
,11-03 23:10:46.448  5677  5689 D BluetoothAdapterProperties: Setting state to 14
11-03 23:10:46.448  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-03 23:10:46.450  5677  5689 D BluetoothBondStateMachine: make
,11-03 23:10:46.451  5677  5694 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 23:10:46.454  5677  5689 I BluetoothAdapterState: Entering PendingCommandState
,11-03 23:10:46.455  5677  5677 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 23:10:46.457  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
11-03 23:10:46.458  5677  5677 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 23:10:46.458  5677  5677 D BtGatt.GattService: Received start request. Starting profile...
11-03 23:10:46.459  5677  5677 D BtGatt.GattService: start()
11-03 23:10:46.459  5677  5677 I bt_bluedroid: get_profile_interface gatt
11-03 23:10:46.460  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
11-03 23:10:46.460  5677  5677 D BtGatt.AdvertiseManager: advertise manager created
11-03 23:10:46.465  5677  5677 V BluetoothAdapterState: isTurningOff()=false
11-03 23:10:46.465  5677  5677 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:46.465  5677  5677 V BluetoothAdapterState: isBleTurningOn()=true
11-03 23:10:46.465  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:46.466  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-03 23:10:46.467  5677  5689 I bt_bluedroid: bt_bluedroid
11-03 23:10:46.467  5677  5690 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-03 23:10:46.467  5677  5690 I bt_hci  : start_up
,11-03 23:10:46.473  5677  5690 I bt_vendor: alloc value 0xf4049871
,11-03 23:10:46.473  5677  5690 I bt_vendor: init
11-03 23:10:46.473  5677  5690 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 23:10:46.473  5677  5690 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 23:10:46.582  5677  5690 D bt_hci  : start_up starting async portion
,11-03 23:10:46.582  5677  5697 I bt_hci  : event_finish_startup
11-03 23:10:46.582  5677  5697 I bt_hci_h4: hal_open
11-03 23:10:46.582  5677  5697 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 23:10:46.579  5698  5698 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 23:10:46.586  5677  5697 I bt_userial_vendor: device fd = 54 open
,11-03 23:10:46.600  5677  5697 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 23:10:46.602  5677  5697 D bt_hwcfg: Chipset BCM4358A3
,11-03 23:10:46.602  5677  5697 D bt_hwcfg: Target name = [BCM4358A3]
11-03 23:10:46.603  5677  5697 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 23:10:47.005  5677  5697 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 23:10:47.005  5677  5697 D bt_hwcfg: Settlement delay -- 100 ms
,11-03 23:10:47.005  5677  5697 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 23:10:47.139  5677  5697 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 23:10:47.140  5677  5697 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-03 23:10:47.141  5677  5697 I bt_hwcfg: vendor lib fwcfg completed
,11-03 23:10:47.141  5677  5697 I bt_vendor: firmware callback
,11-03 23:10:47.141  5677  5697 I bt_hci  : firmware_config_callback
,11-03 23:10:47.150  5677  5700 I bt_btu  : btu_task pending for preload complete event
,11-03 23:10:47.150  5677  5700 I bt_btu_task: Bluetooth chip preload is complete
11-03 23:10:47.151  5677  5700 I bt_btu  : btu_task received preload complete event
,11-03 23:10:47.157  5677  5700 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 23:10:47.157  5677  5700 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-03 23:10:47.157  5677  5700 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 23:10:47.157  5677  5700 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 23:10:47.158  5677  5700 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-03 23:10:47.158  5677  5700 I         : BTE_InitTraceLevels -- TRC_A2D
11-03 23:10:47.158  5677  5700 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-03 23:10:47.158  5677  5700 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 23:10:47.158  5677  5700 I         : BTE_InitTraceLevels -- TRC_GAP
,11-03 23:10:47.158  5677  5700 I         : BTE_InitTraceLevels -- TRC_PAN
11-03 23:10:47.158  5677  5700 I         : BTE_InitTraceLevels -- TRC_SDP
,11-03 23:10:47.158  5677  5700 I         : BTE_InitTraceLevels -- TRC_GATT
11-03 23:10:47.159  5677  5700 I         : BTE_InitTraceLevels -- TRC_SMP
,11-03 23:10:47.159  5677  5700 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-03 23:10:47.159  5677  5700 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 23:10:47.237  5677  5700 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fc7549
,11-03 23:10:47.237  5677  5700 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fc7549 
,11-03 23:10:47.251  5677  5693 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 23:10:47.252  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 23:10:47.253  5677  5693 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 23:10:47.255  5677  5693 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 23:10:47.257  5677  5693 D BluetoothAdapterProperties: Scan Mode:20
11-03 23:10:47.258  5677  5693 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 23:10:47.258  5677  5693 D bt_hci  : do_postload posting postload work item
11-03 23:10:47.258  5677  5697 I bt_hci  : event_postload
11-03 23:10:47.258  5677  5697 I bt_vendor: sco_config_cb
,11-03 23:10:47.258  5677  5697 I bt_hci  : sco_config_callback postload finished.
,11-03 23:10:47.263  5677  5693 D bt_bte_conf: Device ID record 1 : primary
,11-03 23:10:47.264  5677  5693 D bt_bte_conf:   vendorId            = 000f
,11-03 23:10:47.264  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:10:47.264  5677  5693 D bt_bte_conf:   vendorIdSource      = 0001
11-03 23:10:47.264  5677  5693 D bt_bte_conf:   product             = 1200
11-03 23:10:47.264  5677  5693 D bt_bte_conf:   version             = 1436
,11-03 23:10:47.264  5677  5693 D bt_bte_conf:   clientExecutableURL = 
11-03 23:10:47.264  5677  5693 D bt_bte_conf:   serviceDescription  = 
11-03 23:10:47.264  5677  5693 D bt_bte_conf:   documentationURL    = 
11-03 23:10:47.264  5677  5693 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 23:10:47.265  5677  5690 D bt_stack_manager: event_start_up_stack finished
11-03 23:10:47.265  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-03 23:10:47.266  5677  5697 I bt_vendor: low_power_mode_cb
11-03 23:10:47.266  5677  5689 D BluetoothAdapterProperties: Setting state to 15
11-03 23:10:47.266  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 23:10:47.267  5677  5689 I BluetoothAdapterState: Entering BleOnState
,11-03 23:10:47.273  5677  5689 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-03 23:10:47.273  5677  5689 D BluetoothAdapterProperties: Setting state to 11
11-03 23:10:47.273  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 23:10:47.279  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
,11-03 23:10:47.281  5677  5677 D HeadsetService: Received start request. Starting profile...
,11-03 23:10:47.283  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:10:47.283  5677  5677 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-03 23:10:47.283  5677  5677 D HeadsetStateMachine: make
,11-03 23:10:47.292  5677  5677 D HeadsetStateMachine: max_hf_connections = 1
11-03 23:10:47.292  5677  5677 I bt_bluedroid: get_profile_interface handsfree
11-03 23:10:47.293  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-03 23:10:47.293  5677  5693 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-03 23:10:47.298  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
,11-03 23:10:47.298  5677  5677 D A2dpService: Received start request. Starting profile...
,11-03 23:10:47.299  5677  5677 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 23:10:47.299  5677  5677 I bt_bluedroid: get_profile_interface avrcp
,11-03 23:10:47.300  5677  5689 I BluetoothAdapterState: Entering PendingCommandState
,11-03 23:10:47.304  5677  5677 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-03 23:10:47.304  5677  5677 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 23:10:47.304  5677  5677 D A2dpStateMachine: make
,11-03 23:10:47.306  5677  5677 I bt_bluedroid: get_profile_interface a2dp
,11-03 23:10:47.307  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-03 23:10:47.307  5677  5708 D A2dpStateMachine: Enter Disconnected: -2
,11-03 23:10:47.308  5677  5677 I BluetoothHidServiceJni: classInitNative: succeeds
,11-03 23:10:47.308  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
,11-03 23:10:47.310  5567  5567 D BluetoothInputDevice: Proxy object connected
,11-03 23:10:47.310  5677  5677 D HidService: Received start request. Starting profile...
11-03 23:10:47.310  5677  5677 I bt_bluedroid: get_profile_interface hidhost
11-03 23:10:47.310  5677  5677 D HidService: setHidService(): set to: null
11-03 23:10:47.310  5677  5693 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fa856d
,11-03 23:10:47.310  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 23:10:47.310  5567  5567 D HidProfile: Bluetooth service connected
,11-03 23:10:47.311  5677  5677 I BluetoothHealthServiceJni: classInitNative: succeeds
11-03 23:10:47.312  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
11-03 23:10:47.313  5677  5677 D HealthService: Received start request. Starting profile...
,11-03 23:10:47.313  3483  3483 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 23:10:47.315  5677  5677 I bt_bluedroid: get_profile_interface health
11-03 23:10:47.315  5677  5677 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-03 23:10:47.316  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
,11-03 23:10:47.319  5677  5677 D PanService: Received start request. Starting profile...
,11-03 23:10:47.319  5677  5677 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 23:10:47.319  5677  5677 I bt_bluedroid: get_profile_interface pan
11-03 23:10:47.319  5677  5693 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-03 23:10:47.321  5567  5567 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 23:10:47.323  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
11-03 23:10:47.324  5677  5677 D BluetoothMapService: Received start request. Starting profile...
11-03 23:10:47.324  5567  5567 D PanProfile: Bluetooth service connected
,11-03 23:10:47.324  5677  5677 D BluetoothMapService: start()
11-03 23:10:47.324  5567  5567 D BluetoothMap: Proxy object connected
11-03 23:10:47.325  5567  5567 D MapProfile: Bluetooth service connected
11-03 23:10:47.325  5567  5567 D BluetoothMap: getConnectedDevices()
11-03 23:10:47.326  5677  5677 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-03 23:10:47.327  5677  5677 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-03 23:10:47.327  5677  5677 D BluetoothMapAppObserver: createReceiver()
11-03 23:10:47.328  5677  5677 D BluetoothMapAppObserver: initObservers()
11-03 23:10:47.328  5677  5677 D BluetoothMapAppObserver: getEnabledAccountItems()
11-03 23:10:47.331  5567  5567 D BluetoothMap: Bluetooth is Not enabled
,11-03 23:10:47.333  5677  5677 V BluetoothAdapterState: isTurningOff()=false
11-03 23:10:47.333  5677  5677 V BluetoothAdapterState: isTurningOn()=true
,11-03 23:10:47.333  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:47.333  5677  5705 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 23:10:47.333  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 23:10:47.334  5677  5677 V SapService: SapBinder()
11-03 23:10:47.334  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
11-03 23:10:47.335  5677  5677 D SapService: Received start request. Starting profile...
,11-03 23:10:47.335  5677  5677 V SapService: start()
11-03 23:10:47.336  5677  5677 V BluetoothAdapterState: isTurningOff()=false
,11-03 23:10:47.336  5677  5677 V BluetoothAdapterState: isTurningOn()=true
11-03 23:10:47.336  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 23:10:47.336  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:47.336  5677  5677 V BluetoothAdapterState: isTurningOff()=false
11-03 23:10:47.336  5677  5677 V BluetoothAdapterState: isTurningOn()=true
11-03 23:10:47.336  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:47.336  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:47.336  5677  5677 V BluetoothAdapterState: isTurningOff()=false
,11-03 23:10:47.336  5677  5677 V BluetoothAdapterState: isTurningOn()=true
11-03 23:10:47.336  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:47.336  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 23:10:47.337  5677  5677 V BluetoothAdapterState: isTurningOff()=false
11-03 23:10:47.337  5677  5677 V BluetoothAdapterState: isTurningOn()=true
11-03 23:10:47.337  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:47.337  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:47.337  5677  5677 V BluetoothAdapterState: isTurningOff()=false
11-03 23:10:47.337  5677  5677 V BluetoothAdapterState: isTurningOn()=true
11-03 23:10:47.337  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:47.337  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:47.338  5677  5677 V BluetoothAdapterState: isTurningOff()=false
11-03 23:10:47.338  5677  5677 V BluetoothAdapterState: isTurningOn()=true
,11-03 23:10:47.338  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:47.338  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:47.338  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 23:10:47.338  5677  5689 D BluetoothAdapterProperties: ScanMode =  20
11-03 23:10:47.338  5677  5689 D BluetoothAdapterProperties: State =  11
11-03 23:10:47.342  5677  5693 D BluetoothAdapterProperties: Scan Mode:21
11-03 23:10:47.342  5677  5689 D BluetoothAdapterProperties: Setting state to 12
11-03 23:10:47.342  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 23:10:47.342  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 23:10:47.342  5677  5693 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 23:10:47.342  5677  5689 I BluetoothAdapterState: Entering OnState
11-03 23:10:47.342  5567  5579 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 23:10:47.343  3652  3662 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-03 23:10:47.343  3020  3886 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 23:10:47.344   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:10:47.345   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:10:47.345  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:10:47.345  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:47.345  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:47.345  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 23:10:47.345  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:10:47.345  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:10:47.345  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:10:47.345  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 23:10:47.345  3020  5586 D BluetoothMap: onBluetoothStateChange: up=true
11-03 23:10:47.347  3020  3020 D BluetoothMap: Proxy object connected
11-03 23:10:47.347  5501  5501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 23:10:47.347  3020  3020 D MapProfile: Bluetooth service connected
11-03 23:10:47.347  5567  5581 D BluetoothMap: onBluetoothStateChange: up=true
,11-03 23:10:47.347  3020  3020 D BluetoothMap: getConnectedDevices()
11-03 23:10:47.347  3020  5589 D BluetoothPan: onBluetoothStateChange on: true
11-03 23:10:47.349  3020  3020 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 23:10:47.349  3020  3037 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:10:47.349  3020  3020 D PanProfile: Bluetooth service connected
,11-03 23:10:47.349   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 23:10:47.350  5567  5579 D BluetoothPan: onBluetoothStateChange on: true
11-03 23:10:47.350  5567  5581 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 23:10:47.350   929   929 D BluetoothA2dp: Proxy object connected
11-03 23:10:47.351   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:10:47.351  3020  3886 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 23:10:47.353  3020  3020 D BluetoothInputDevice: Proxy object connected
11-03 23:10:47.353  3020  3020 D HidProfile: Bluetooth service connected
11-03 23:10:47.354  3020  5588 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 23:10:47.354  5677  5677 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 23:10:47.355  5677  5677 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 23:10:47.355  3020  3020 D BluetoothA2dp: Proxy object connected
11-03 23:10:47.356   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-03 23:10:47.357  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 23:10:47.358  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:10:47.361  5677  5677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 23:10:47.362  5567  5567 D LocalBluetoothProfileManager: Adding local A2DP profile
11-03 23:10:47.363  5677  5677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:10:47.364  5677  5677 D ObexServerSockets: Succeed to create listening sockets 
11-03 23:10:47.365  5677  5677 D ObexServerSockets0: startAccept()
,11-03 23:10:47.365  5677  5677 D ObexServerSockets0: prepareForNewConnect()
11-03 23:10:47.365  5567  5567 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-03 23:10:47.366  5677  5677 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 23:10:47.366  5677  5677 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-03 23:10:47.367  5677  5677 D BluetoothMapService: onReceive
11-03 23:10:47.367  5677  5677 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 23:10:47.367  5677  5677 D BluetoothMapService: STATE_ON
11-03 23:10:47.367  5677  5714 D ObexServerSockets0: Accepting socket connection...
11-03 23:10:47.368  5677  5715 D ObexServerSockets0: Accepting socket connection...
,11-03 23:10:47.370  5677  5716 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:10:47.371  5677  5716 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-03 23:10:47.371  5677  5716 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-03 23:10:47.372  5567  5567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 23:10:47.375  5567  5567 D BluetoothA2dp: Proxy object connected
,11-03 23:10:47.379  3483  3483 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 23:10:47.382  5567  5567 D DockEventReceiver: finishStartingService: stopping service
,11-03 23:10:47.387  3020  3020 D BluetoothPbap: Proxy object connected
11-03 23:10:47.387  3020  3020 D PbapServerProfile: Bluetooth service connected
,11-03 23:10:47.389  5567  5567 D BluetoothPbap: Proxy object connected
,11-03 23:10:47.390  5567  5567 D PbapServerProfile: Bluetooth service connected
,11-03 23:10:47.394  5677  5677 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 23:10:47.394  5677  5677 D ObexServerSockets0: prepareForNewConnect()
,11-03 23:10:47.395  5677  5720 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:10:47.411  5677  5724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:10:47.412  5677  5724 I BtOppRfcommListener: Accept thread started.
,11-03 23:10:47.444   929   929 D BluetoothHeadset: Proxy object connected
,11-03 23:10:47.444   929   946 D BluetoothHeadset: Proxy object connected
11-03 23:10:47.445  3652  3663 D BluetoothHeadset: Proxy object connected
11-03 23:10:47.445   929   946 D BluetoothHeadset: Proxy object connected
,11-03 23:10:47.445   929   929 D BluetoothHeadset: Proxy object connected
,11-03 23:10:47.445  3020  3042 D BluetoothHeadset: Proxy object connected
11-03 23:10:47.445  3020  3020 D HeadsetProfile: Bluetooth service connected
11-03 23:10:47.445   929   929 D BluetoothHeadset: Proxy object connected
,11-03 23:10:47.449  3020  5588 D BluetoothHeadset: Proxy object connected
11-03 23:10:47.449  3020  3020 D HeadsetProfile: Bluetooth service connected
,11-03 23:10:47.451   929   946 D BluetoothHeadset: Proxy object connected
,11-03 23:10:47.468  5567  5581 D BluetoothHeadset: Proxy object connected
,11-03 23:10:47.470  5567  5567 D HeadsetProfile: Bluetooth service connected
,11-03 23:10:48.773  3556  3711 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-03 23:10:48.774  3556  3711 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-03 23:10:48.802  3483  3483 I ConfigService: onCreate
,11-03 23:10:49.160   929  2854 D ConnectivityService: handlePromptUnvalidated 101
,11-03 23:10:51.306  5677  5689 D BluetoothAdapterState: Current state: ON, message: 23
,11-03 23:10:51.306  5677  5689 D BluetoothAdapterProperties: Setting state to 13
11-03 23:10:51.307  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-03 23:10:51.308  5677  5689 D BluetoothAdapterProperties: onBluetoothDisable()
,11-03 23:10:51.309  5677  5689 I BluetoothAdapterState: Entering PendingCommandState
,11-03 23:10:51.315  5677  5677 D BluetoothMapService: onReceive
11-03 23:10:51.316  5677  5677 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 23:10:51.316  5677  5677 D BluetoothMapService: STATE_TURNING_OFF
11-03 23:10:51.316  5677  5677 D BluetoothMapService: MAP Service closeService in
,11-03 23:10:51.316  5677  5677 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 23:10:51.316  5677  5677 D ObexServerSockets0: shutdown(block = true)
11-03 23:10:51.320  5677  5677 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 23:10:51.320  5677  5714 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-03 23:10:51.320  5677  5693 D BluetoothAdapterProperties: Scan Mode:20
11-03 23:10:51.321  5677  5715 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 23:10:51.322  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-03 23:10:51.322  5677  5702 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 23:10:51.323  5677  5677 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 23:10:51.322  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:10:51.323  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:10:51.323  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:10:51.323  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:10:51.323  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 23:10:51.323  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:10:51.323  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:10:51.323  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:10:51.323  5501  5501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 23:10:51.323  5567  5567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 23:10:51.324  5677  5677 I BtOppRfcommListener: stopping Accept Thread
11-03 23:10:51.324  5677  5724 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 23:10:51.324  5501  5501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 23:10:51.325  5501  5501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 23:10:51.325  5677  5724 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-03 23:10:51.328  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:10:51.329  5677  5677 D HeadsetService: Received stop request...Stopping profile...
,11-03 23:10:51.331  5567  5567 D DockEventReceiver: finishStartingService: stopping service
11-03 23:10:51.332   929   929 D BluetoothHeadset: Proxy object disconnected
,11-03 23:10:51.332  3652  3911 D BluetoothHeadset: Proxy object disconnected
,11-03 23:10:51.333   929   929 D BluetoothHeadset: Proxy object disconnected
,11-03 23:10:51.333  3020  5589 D BluetoothHeadset: Proxy object disconnected
11-03 23:10:51.334  5567  5579 D BluetoothHeadset: Proxy object disconnected
11-03 23:10:51.334  5677  5677 D A2dpService: Received stop request...Stopping profile...
11-03 23:10:51.334   929   929 D BluetoothHeadset: Proxy object disconnected
11-03 23:10:51.335  5567  5567 D HeadsetProfile: Bluetooth service disconnected
11-03 23:10:51.335  3020  3020 D HeadsetProfile: Bluetooth service disconnected
11-03 23:10:51.336   929   929 D BluetoothA2dp: Proxy object disconnected
,11-03 23:10:51.336  5677  5708 D A2dpStateMachine: Exit Disconnected: -1
11-03 23:10:51.336  3020  3020 D BluetoothA2dp: Proxy object disconnected
11-03 23:10:51.337  5567  5567 D BluetoothA2dp: Proxy object disconnected
11-03 23:10:51.339  5677  5677 D HidService: Received stop request...Stopping profile...
,11-03 23:10:51.339  5677  5677 D HidService: Stopping Bluetooth HidService
11-03 23:10:51.341  5567  5567 D BluetoothInputDevice: Proxy object disconnected
11-03 23:10:51.341  5567  5567 D HidProfile: Bluetooth service disconnected
,11-03 23:10:51.342  3020  3020 D BluetoothInputDevice: Proxy object disconnected
11-03 23:10:51.342  3020  3020 D HidProfile: Bluetooth service disconnected
11-03 23:10:51.342  3483  3483 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 23:10:51.344  5677  5677 D HealthService: Received stop request...Stopping profile...
11-03 23:10:51.345  5677  5677 V BluetoothAdapterState: isTurningOff()=true
11-03 23:10:51.345  5677  5677 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:51.345  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:51.345  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:51.347  5677  5677 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-03 23:10:51.347  5677  5677 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 23:10:51.347  5677  5700 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:10:51.347  5677  5700 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:10:51.347  5677  5700 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:10:51.347  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 23:10:51.347  5677  5677 D PanService: Received stop request...Stopping profile...
11-03 23:10:51.347  5677  5693 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-03 23:10:51.348  3020  3020 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 23:10:51.348  3020  3020 D PanProfile: Bluetooth service disconnected
,11-03 23:10:51.349  5567  5567 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 23:10:51.349  5567  5567 D PanProfile: Bluetooth service disconnected
11-03 23:10:51.349  5677  5677 D BluetoothMapService: Received stop request...Stopping profile...
11-03 23:10:51.349  5677  5677 D BluetoothMapService: stop()
11-03 23:10:51.350  5677  5677 D BluetoothMapAppObserver: deinitObservers()
11-03 23:10:51.350  5677  5677 D BluetoothMapAppObserver: removeReceiver()
11-03 23:10:51.351  3020  3020 D BluetoothMap: Proxy object disconnected
11-03 23:10:51.351  3020  3020 D MapProfile: Bluetooth service disconnected
,11-03 23:10:51.352  5567  5567 D BluetoothMap: Proxy object disconnected
11-03 23:10:51.352  5567  5567 D MapProfile: Bluetooth service disconnected
11-03 23:10:51.354  5677  5677 D SapService: Received stop request...Stopping profile...
11-03 23:10:51.354  5677  5677 V SapService: stop()
11-03 23:10:51.356  5677  5677 V BluetoothAdapterState: isTurningOff()=true
11-03 23:10:51.356  5677  5677 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:51.356  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:51.356  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 23:10:51.357  5677  5700 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 23:10:51.357  5677  5700 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 23:10:51.357  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 23:10:51.357  5677  5700 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 23:10:51.357  5677  5700 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 23:10:51.357  5677  5700 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-03 23:10:51.357  5677  5700 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 23:10:51.359  5677  5677 V BluetoothAdapterState: isTurningOff()=true
11-03 23:10:51.360  5677  5677 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:51.360  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:51.360  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:51.360  5677  5677 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 23:10:51.360  5677  5677 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 23:10:51.360  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 23:10:51.361  5677  5677 V BluetoothAdapterState: isTurningOff()=true
,11-03 23:10:51.361  5677  5677 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:51.361  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:51.361  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:51.361  5567  5567 D BluetoothPbap: Proxy object disconnected
11-03 23:10:51.361  5677  5677 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-03 23:10:51.361  5677  5693 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-03 23:10:51.361  5677  5677 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-03 23:10:51.362  5677  5677 V BluetoothAdapterState: isTurningOff()=true
11-03 23:10:51.362  5677  5677 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:51.362  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:51.362  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:51.362  3020  3020 D BluetoothPbap: Proxy object disconnected
11-03 23:10:51.362  5677  5677 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 23:10:51.362  3020  3020 D PbapServerProfile: Bluetooth service disconnected
11-03 23:10:51.362  5677  5677 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 23:10:51.363  5677  5677 D BluetoothMapService: MAP Service closeService in
11-03 23:10:51.363  5677  5677 V BluetoothAdapterState: isTurningOff()=true
11-03 23:10:51.363  5677  5677 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:51.363  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:51.363  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:51.363  5677  5677 D BluetoothMapService: cleanup()
11-03 23:10:51.363  5677  5677 D BluetoothMapService: MAP Service closeService in
11-03 23:10:51.361  5567  5567 D PbapServerProfile: Bluetooth service disconnected
11-03 23:10:51.363  5677  5677 V BluetoothAdapterState: isTurningOff()=true
,11-03 23:10:51.363  5677  5677 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:51.363  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:51.363  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:10:51.364  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 23:10:51.364  5677  5689 D BluetoothAdapterProperties: Setting state to 15
11-03 23:10:51.364  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 23:10:51.364  5677  5689 I BluetoothAdapterState: Entering BleOnState
11-03 23:10:51.364  5567  5581 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 23:10:51.365  3652  3887 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:10:51.365  3020  3042 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 23:10:51.366  5567  5579 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-03 23:10:51.366   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:10:51.366   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:10:51.367  3020  3037 D BluetoothMap: onBluetoothStateChange: up=false
11-03 23:10:51.367  5567  5581 D BluetoothMap: onBluetoothStateChange: up=false
11-03 23:10:51.368  3020  5586 D BluetoothPan: onBluetoothStateChange on: false
11-03 23:10:51.368  5567  5579 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:10:51.368  3020  5589 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:10:51.369   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 23:10:51.369  5567  5581 D BluetoothPan: onBluetoothStateChange on: false
11-03 23:10:51.369  5567  5579 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 23:10:51.370   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:10:51.370  3020  3886 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 23:10:51.370  3020  5588 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 23:10:51.371  5677  5689 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 23:10:51.371  5677  5689 D BluetoothAdapterProperties: Setting state to 16
11-03 23:10:51.371  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 23:10:51.371  5677  5689 D BluetoothAdapterProperties: onBleDisable
11-03 23:10:51.372  5677  5689 I BluetoothAdapterState: Entering PendingCommandState
,11-03 23:10:51.372  5677  5690 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-03 23:10:51.374  5677  5700 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 23:10:51.374  5677  5700 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:10:51.374  5677  5693 D BluetoothAdapterProperties: Scan Mode:20
11-03 23:10:51.374  5567  5567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 23:10:51.375  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:10:51.376  5501  5501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:10:51.379  3483  3483 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 23:10:51.385  5567  5567 D DockEventReceiver: finishStartingService: stopping service
,11-03 23:10:51.593  5677  5693 I bt_hci  : shut_down
,11-03 23:10:51.598  5677  5697 D bt_hwcfg: hw_epilog_process
,11-03 23:10:51.599  5677  5697 I bt_vendor: low_power_mode_cb
,11-03 23:10:51.602  5677  5697 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-03 23:10:51.602  5677  5697 I bt_vendor: epilog_cb
11-03 23:10:51.602  5677  5697 I bt_hci  : epilog_finished_callback
,11-03 23:10:51.606  5677  5693 I bt_hci_h4: hal_close
,11-03 23:10:51.606  5677  5693 I bt_userial_vendor: device fd = 54 close
,11-03 23:10:51.719  5677  5690 D bt_stack_manager: event_shut_down_stack finished.
,11-03 23:10:51.720  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 23:10:51.724  5677  5689 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-03 23:10:51.724  5677  5677 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 23:10:51.726  5677  5677 D BtGatt.GattService: Received stop request...Stopping profile...
,11-03 23:10:51.726  5677  5677 D BtGatt.GattService: stop()
11-03 23:10:51.727  5677  5677 D BtGatt.AdvertiseManager: advertise clients cleared
,11-03 23:10:51.731  5677  5677 V BluetoothAdapterState: isTurningOff()=false
,11-03 23:10:51.731  5677  5677 V BluetoothAdapterState: isTurningOn()=false
11-03 23:10:51.731  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:10:51.731  5677  5677 V BluetoothAdapterState: isBleTurningOff()=true
11-03 23:10:51.732  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-03 23:10:51.732  5677  5689 D BluetoothAdapterProperties: Setting state to 10
11-03 23:10:51.732  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-03 23:10:51.733  5677  5689 I BluetoothAdapterState: Entering OffState
11-03 23:10:51.734   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-03 23:10:51.748  5677  5677 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-03 23:10:51.749  5677  5677 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-03 23:10:51.749  5677  5677 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-03 23:10:51.751  5677  5690 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.,
,11-03 23:10:51.758  5677  5677 I art     : System.exit called, status: 0
,11-03 23:10:51.759  5677  5677 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 23:10:51.794   929  3731 I ActivityManager: Process com.android.bluetooth (pid 5677) has died
,11-03 23:10:52.707   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:53.708   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:53.835  3483  3483 I ConfigService: onDestroy
,11-03 23:10:54.709   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:55.710   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:56.305  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:10:56.306  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 23:10:56.311  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:10:56.312  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@998969e removed from the list
,11-03 23:10:56.312  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:10:56.314  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 23:10:56.314  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a8ad95 added. We now have 4 listener(s)
,11-03 23:10:56.315  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:10:56.317  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:10:56.317  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a8ad95 removed from the list
11-03 23:10:56.317  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:10:56.319  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:10:56.320  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7f37eaa added. We now have 4 listener(s)
11-03 23:10:56.320  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:10:56.711   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:10:57.712   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 23:11:00.973   929   949 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-03 23:11:00.983  3556  3556 I Keyboard.Facilitator: onFinishInput()
,11-03 23:11:00.979  3732  3732 W Binder_B: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31743]" dev="sockfs" ino=31743 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 23:11:00.979  3732  3732 W Binder_B: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31743]" dev="sockfs" ino=31743 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:11:00.999   929   949 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 23:11:00.999   929   949 I Adreno  : Build Date                       : 12/06/15
11-03 23:11:00.999   929   949 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 23:11:00.999   929   949 I Adreno  : Local Branch                     : mybranch17112971
11-03 23:11:00.999   929   949 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 23:11:00.999   929   949 I Adreno  : Remote Branch                    : NONE
11-03 23:11:00.999   929   949 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 23:11:01.039   381   404 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (181 us)
,11-03 23:11:01.332  5501  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:11:01.368   929   946 I ActivityManager: Start proc 5738:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 23:11:01.456  5738  5738 D AdapterServiceConfig: Adding HeadsetService
,11-03 23:11:01.456  5738  5738 D AdapterServiceConfig: Adding A2dpService
11-03 23:11:01.456  5738  5738 D AdapterServiceConfig: Adding HidService
11-03 23:11:01.457  5738  5738 D AdapterServiceConfig: Adding HealthService
11-03 23:11:01.457  5738  5738 D AdapterServiceConfig: Adding PanService
11-03 23:11:01.457  5738  5738 D AdapterServiceConfig: Adding GattService
11-03 23:11:01.457  5738  5738 D AdapterServiceConfig: Adding BluetoothMapService
11-03 23:11:01.457  5738  5738 D AdapterServiceConfig: Adding SapService
,11-03 23:11:01.468   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19b37e8:true
,11-03 23:11:01.469  5738  5738 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 23:11:01.473  5738  5738 I bt_bluedroid: init
11-03 23:11:01.473  5738  5750 I BluetoothAdapterState: Entering OffState
,11-03 23:11:01.477  5738  5751 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-03 23:11:01.477  5738  5751 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 23:11:01.477  5738  5751 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 23:11:01.477  5738  5751 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-03 23:11:01.478  5738  5738 I bt_bluedroid: get_profile_interface socket
,11-03 23:11:01.480  5738  5754 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-03 23:11:01.480  5738  5738 I bt_bluedroid: get_profile_interface sdp
11-03 23:11:01.481  5738  5754 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 23:11:01.486  5738  5749 I bt_bluedroid: config_hci_snoop_log
11-03 23:11:01.487   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-03 23:11:01.491  5738  5750 D BluetoothAdapterState: Current state: OFF, message: 0
,11-03 23:11:01.491  5738  5750 D BluetoothAdapterProperties: Setting state to 14
11-03 23:11:01.491  5738  5750 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-03 23:11:01.493  5738  5750 D BluetoothBondStateMachine: make
,11-03 23:11:01.495  5738  5755 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 23:11:01.497  5738  5750 I BluetoothAdapterState: Entering PendingCommandState
,11-03 23:11:01.498  5738  5738 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 23:11:01.500  5738  5738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
11-03 23:11:01.501  5738  5738 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 23:11:01.503  5738  5738 D BtGatt.GattService: Received start request. Starting profile...
11-03 23:11:01.504  5738  5738 D BtGatt.GattService: start()
11-03 23:11:01.504  5738  5738 I bt_bluedroid: get_profile_interface gatt
,11-03 23:11:01.505  5738  5738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
,11-03 23:11:01.505  5738  5738 D BtGatt.AdvertiseManager: advertise manager created
,11-03 23:11:01.510  5738  5738 V BluetoothAdapterState: isTurningOff()=false
,11-03 23:11:01.510  5738  5738 V BluetoothAdapterState: isTurningOn()=false
11-03 23:11:01.510  5738  5738 V BluetoothAdapterState: isBleTurningOn()=true
11-03 23:11:01.510  5738  5738 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 23:11:01.511  5738  5750 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-03 23:11:01.512  5738  5750 I bt_bluedroid: bt_bluedroid
,11-03 23:11:01.512  5738  5751 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-03 23:11:01.512  5738  5751 I bt_hci  : start_up
,11-03 23:11:01.517  5738  5751 I bt_vendor: alloc value 0xf4049871
,11-03 23:11:01.517  5738  5751 I bt_vendor: init
11-03 23:11:01.518  5738  5751 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 23:11:01.518  5738  5751 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 23:11:01.628  5738  5751 D bt_hci  : start_up starting async portion
11-03 23:11:01.629  5738  5758 I bt_hci  : event_finish_startup
,11-03 23:11:01.629  5738  5758 I bt_hci_h4: hal_open
11-03 23:11:01.629  5738  5758 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 23:11:01.629  5759  5759 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-03 23:11:01.632  5738  5758 I bt_userial_vendor: device fd = 54 open
,11-03 23:11:01.647  5738  5758 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 23:11:01.650  5738  5758 D bt_hwcfg: Chipset BCM4358A3
11-03 23:11:01.650  5738  5758 D bt_hwcfg: Target name = [BCM4358A3]
11-03 23:11:01.650  5738  5758 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 23:11:01.710  5501  5501 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-03 23:11:01.711  5501  5501 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-03 23:11:01.747   929   949 I sensors : batch
,11-03 23:11:01.749   929   949 V KeyguardServiceDelegate: onScreenTurnedOff()
11-03 23:11:01.752  5501  5501 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21ac195 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4c0ea9b, 16908290=android.view.AbsSavedState$1@4c0ea9b}, android:focusedViewId=100}]}]
11-03 23:11:01.752  5501  5501 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-03 23:11:01.752  5501  5501 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-03 23:11:01.752  5501  5501 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,11-03 23:11:01.753   929   949 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-03 23:11:01.753   929   949 I sensors : activate
11-03 23:11:01.754   381   381 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fb0843c00
11-03 23:11:01.754   381   381 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-03 23:11:01.754   929   947 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-03 23:11:01.761   929  2631 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,11-03 23:11:01.764   929  2631 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-03 23:11:02.071   381   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-03 23:11:02.073   381   381 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-03 23:11:02.077   929  2990 D SurfaceControl: Excessive delay in setPowerMode(): 322ms
,11-03 23:11:02.092   929   949 I DreamManagerService: Entering dreamland.
,11-03 23:11:02.100   929   949 I PowerManagerService: Dozing...
,11-03 23:11:02.101   929   944 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-03 23:11:02.133   929   940 I sensors : batch
,11-03 23:11:02.134   929   940 I sensors : activate
11-03 23:11:02.129  3683  3683 W Binder_7: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33133]" dev="sockfs" ino=33133 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:11:02.129  3683  3683 W Binder_7: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33133]" dev="sockfs" ino=33133 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:11:02.137   929  2631 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-03 23:11:02.138   929  2631 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-03 23:11:02.140  5738  5758 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-03 23:11:02.140  5738  5758 D bt_hwcfg: Settlement delay -- 100 ms
,11-03 23:11:02.140  5738  5758 I bt_hwcfg: Setting fw settlement delay to 100 
11-03 23:11:02.143   513  2916 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-03 23:11:02.171  3652  4652 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
11-03 23:11:02.171  3652  4652 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-03 23:11:02.172  3652  4652 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-03 23:11:02.172   526  1052 D         : oem-qmi: Connection accepted
11-03 23:11:02.172   526  1052 D         : oem-qmi: Waiting to accept connection
,11-03 23:11:02.174   929   929 I sensors : activate
11-03 23:11:02.175   513  2910 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-03 23:11:02.177   929  2631 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-03 23:11:02.179  3652  4652 D         : oem_qmi_lib:output 0
,11-03 23:11:02.179  3652  4652 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-03 23:11:02.203  3652  4652 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-03 23:11:02.204  3652  4652 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-03 23:11:02.204  3652  4652 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-03 23:11:02.204   526  1052 D         : oem-qmi: Connection accepted
11-03 23:11:02.204   526  1052 D         : oem-qmi: Waiting to accept connection
,11-03 23:11:02.210  3652  4652 D         : oem_qmi_lib:output 0
,11-03 23:11:02.210  3652  4652 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-03 23:11:02.275  5738  5758 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 23:11:02.275  5738  5758 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-03 23:11:02.276  5738  5758 I bt_hwcfg: vendor lib fwcfg completed
11-03 23:11:02.276  5738  5758 I bt_vendor: firmware callback
11-03 23:11:02.276  5738  5758 I bt_hci  : firmware_config_callback
,11-03 23:11:02.282  5738  5767 I bt_btu  : btu_task pending for preload complete event
,11-03 23:11:02.282  5738  5767 I bt_btu_task: Bluetooth chip preload is complete
,11-03 23:11:02.282  5738  5767 I bt_btu  : btu_task received preload complete event
,11-03 23:11:02.289  5738  5767 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 23:11:02.290  5738  5767 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-03 23:11:02.290  5738  5767 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 23:11:02.290  5738  5767 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 23:11:02.290  5738  5767 I         : BTE_InitTraceLevels -- TRC_AVRC
11-03 23:11:02.290  5738  5767 I         : BTE_InitTraceLevels -- TRC_A2D
,11-03 23:11:02.290  5738  5767 I         : BTE_InitTraceLevels -- TRC_BNEP
11-03 23:11:02.291  5738  5767 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 23:11:02.291  5738  5767 I         : BTE_InitTraceLevels -- TRC_GAP
11-03 23:11:02.291  5738  5767 I         : BTE_InitTraceLevels -- TRC_PAN
11-03 23:11:02.291  5738  5767 I         : BTE_InitTraceLevels -- TRC_SDP
11-03 23:11:02.291  5738  5767 I         : BTE_InitTraceLevels -- TRC_GATT
,11-03 23:11:02.291  5738  5767 I         : BTE_InitTraceLevels -- TRC_SMP
11-03 23:11:02.292  5738  5767 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-03 23:11:02.292  5738  5767 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 23:11:02.378  5738  5767 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fc7549
,11-03 23:11:02.378  5738  5767 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fc7549 
,11-03 23:11:02.389  5738  5754 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 23:11:02.391  5738  5754 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 23:11:02.392  5738  5754 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 23:11:02.395  5738  5754 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 23:11:02.398  5738  5754 D BluetoothAdapterProperties: Scan Mode:20
11-03 23:11:02.398  5738  5754 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 23:11:02.399  5738  5754 D bt_hci  : do_postload posting postload work item
11-03 23:11:02.399  5738  5758 I bt_hci  : event_postload
11-03 23:11:02.399  5738  5758 I bt_vendor: sco_config_cb
11-03 23:11:02.399  5738  5758 I bt_hci  : sco_config_callback postload finished.
,11-03 23:11:02.402  5738  5754 D bt_bte_conf: Device ID record 1 : primary
,11-03 23:11:02.402  5738  5754 D bt_bte_conf:   vendorId            = 000f
11-03 23:11:02.402  5738  5754 D bt_bte_conf:   vendorIdSource      = 0001
11-03 23:11:02.402  5738  5754 D bt_bte_conf:   product             = 1200
11-03 23:11:02.402  5738  5754 D bt_bte_conf:   version             = 1436
11-03 23:11:02.402  5738  5754 D bt_bte_conf:   clientExecutableURL = 
11-03 23:11:02.402  5738  5754 D bt_bte_conf:   serviceDescription  = 
11-03 23:11:02.402  5738  5754 D bt_bte_conf:   documentationURL    = 
11-03 23:11:02.403  5738  5754 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 23:11:02.403  5738  5751 D bt_stack_manager: event_start_up_stack finished
11-03 23:11:02.404  5738  5750 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-03 23:11:02.404  5738  5750 D BluetoothAdapterProperties: Setting state to 15
11-03 23:11:02.404  5738  5750 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 23:11:02.405  5738  5750 I BluetoothAdapterState: Entering BleOnState
,11-03 23:11:02.405  5738  5758 I bt_vendor: low_power_mode_cb
11-03 23:11:02.409  5738  5750 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-03 23:11:02.409  5738  5750 D BluetoothAdapterProperties: Setting state to 11
11-03 23:11:02.409  5738  5750 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 23:11:02.417  5738  5738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
,11-03 23:11:02.418  5738  5738 D HeadsetService: Received start request. Starting profile...
11-03 23:11:02.420  5738  5738 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-03 23:11:02.420  5738  5738 D HeadsetStateMachine: make
,11-03 23:11:02.429  5738  5750 I BluetoothAdapterState: Entering PendingCommandState
,11-03 23:11:02.429  5738  5738 D HeadsetStateMachine: max_hf_connections = 1
,11-03 23:11:02.430  5738  5738 I bt_bluedroid: get_profile_interface handsfree
11-03 23:11:02.430  5738  5754 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-03 23:11:02.430  5738  5754 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-03 23:11:02.434  5738  5738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
,11-03 23:11:02.435  5738  5738 D A2dpService: Received start request. Starting profile...
11-03 23:11:02.435  3483  3483 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 23:11:02.435  5738  5738 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 23:11:02.436  5738  5738 I bt_bluedroid: get_profile_interface avrcp
,11-03 23:11:02.441  5738  5738 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-03 23:11:02.441  5738  5738 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 23:11:02.441  5738  5738 D A2dpStateMachine: make
,11-03 23:11:02.442  5738  5738 I bt_bluedroid: get_profile_interface a2dp
,11-03 23:11:02.443  5738  5754 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-03 23:11:02.444  5738  5774 D A2dpStateMachine: Enter Disconnected: -2
11-03 23:11:02.445  5738  5738 I BluetoothHidServiceJni: classInitNative: succeeds
11-03 23:11:02.445  5738  5738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
,11-03 23:11:02.446  5738  5738 D HidService: Received start request. Starting profile...
11-03 23:11:02.446  5738  5738 I bt_bluedroid: get_profile_interface hidhost
11-03 23:11:02.446  5738  5738 D HidService: setHidService(): set to: null
11-03 23:11:02.446  5738  5754 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fa856d
11-03 23:11:02.446  5738  5754 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 23:11:02.447  5738  5738 I BluetoothHealthServiceJni: classInitNative: succeeds
11-03 23:11:02.448  5738  5738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
,11-03 23:11:02.448  5738  5738 D HealthService: Received start request. Starting profile...
,11-03 23:11:02.449  5738  5738 I bt_bluedroid: get_profile_interface health
,11-03 23:11:02.450  5738  5738 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-03 23:11:02.451  5738  5738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
11-03 23:11:02.451  5738  5738 D PanService: Received start request. Starting profile...
11-03 23:11:02.451  5738  5738 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 23:11:02.452  5738  5738 I bt_bluedroid: get_profile_interface pan
11-03 23:11:02.452  5738  5754 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-03 23:11:02.455  5738  5738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
,11-03 23:11:02.456  5738  5738 D BluetoothMapService: Received start request. Starting profile...
11-03 23:11:02.456  5738  5738 D BluetoothMapService: start()
11-03 23:11:02.458  5738  5738 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-03 23:11:02.459  5738  5738 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-03 23:11:02.459  5738  5738 D BluetoothMapAppObserver: createReceiver()
,11-03 23:11:02.460  5738  5738 D BluetoothMapAppObserver: initObservers()
11-03 23:11:02.460  5738  5738 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 23:11:02.466  5738  5738 V SapService: SapBinder()
,11-03 23:11:02.466  5738  5738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
,11-03 23:11:02.466  5738  5738 D SapService: Received start request. Starting profile...
11-03 23:11:02.466  5738  5738 V SapService: start()
,11-03 23:11:02.469  5738  5738 V BluetoothAdapterState: isTurningOff()=false
,11-03 23:11:02.469  5738  5738 V BluetoothAdapterState: isTurningOn()=true
11-03 23:11:02.469  5738  5738 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:11:02.469  5738  5738 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 23:11:02.470  5738  5772 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 23:11:02.470  5738  5738 V BluetoothAdapterState: isTurningOff()=false
,11-03 23:11:02.470  5738  5738 V BluetoothAdapterState: isTurningOn()=true
11-03 23:11:02.470  5738  5738 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:11:02.470  5738  5738 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 23:11:02.470  5738  5738 V BluetoothAdapterState: isTurningOff()=false
11-03 23:11:02.470  5738  5738 V BluetoothAdapterState: isTurningOn()=true
11-03 23:11:02.470  5738  5738 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:11:02.470  5738  5738 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:11:02.471  5738  5738 V BluetoothAdapterState: isTurningOff()=false
11-03 23:11:02.471  5738  5738 V BluetoothAdapterState: isTurningOn()=true
11-03 23:11:02.471  5738  5738 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:11:02.471  5738  5738 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:11:02.471  5738  5738 V BluetoothAdapterState: isTurningOff()=false
11-03 23:11:02.471  5738  5738 V BluetoothAdapterState: isTurningOn()=true
,11-03 23:11:02.471  5738  5738 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:11:02.471  5738  5738 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:11:02.471  5738  5738 V BluetoothAdapterState: isTurningOff()=false
11-03 23:11:02.471  5738  5738 V BluetoothAdapterState: isTurningOn()=true
11-03 23:11:02.472  5738  5738 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:11:02.472  5738  5738 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:11:02.472  5738  5738 V BluetoothAdapterState: isTurningOff()=false
11-03 23:11:02.473  5738  5738 V BluetoothAdapterState: isTurningOn()=true
11-03 23:11:02.473  5738  5738 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:11:02.473  5738  5738 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:11:02.473  5738  5750 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-03 23:11:02.473  5738  5750 D BluetoothAdapterProperties: ScanMode =  20
11-03 23:11:02.473  5738  5750 D BluetoothAdapterProperties: State =  11
11-03 23:11:02.473  5738  5750 D BluetoothAdapterProperties: Setting state to 12
11-03 23:11:02.473  5738  5750 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 23:11:02.474  5567  5581 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 23:11:02.474  5738  5754 D BluetoothAdapterProperties: Scan Mode:21
11-03 23:11:02.474  5738  5750 I BluetoothAdapterState: Entering OnState
11-03 23:11:02.474  5738  5754 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-03 23:11:02.476  3652  3663 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:11:02.477  3020  5589 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 23:11:02.478  5567  5581 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 23:11:02.480   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:11:02.480   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:11:02.480  3020  3042 D BluetoothMap: onBluetoothStateChange: up=true
,11-03 23:11:02.481  5567  5581 D BluetoothMap: onBluetoothStateChange: up=true
,11-03 23:11:02.482  3020  3020 D BluetoothMap: Proxy object connected
11-03 23:11:02.482  3020  3020 D MapProfile: Bluetooth service connected
11-03 23:11:02.483  3020  3020 D BluetoothMap: getConnectedDevices()
11-03 23:11:02.483  3020  3037 D BluetoothPan: onBluetoothStateChange on: true
11-03 23:11:02.485  5738  5738 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 23:11:02.485  5567  5567 D BluetoothInputDevice: Proxy object connected
11-03 23:11:02.485  5567  5567 D HidProfile: Bluetooth service connected
,11-03 23:11:02.485  5738  5738 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 23:11:02.485  5567  5579 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:11:02.486  3020  3886 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:11:02.486  5738  5738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 23:11:02.486   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 23:11:02.487   929   929 D BluetoothA2dp: Proxy object connected
11-03 23:11:02.487  5567  5581 D BluetoothPan: onBluetoothStateChange on: true
,11-03 23:11:02.488  5738  5738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 23:11:02.488  5567  5579 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 23:11:02.489  5738  5738 D ObexServerSockets: Succeed to create listening sockets 
,11-03 23:11:02.489  5738  5738 D ObexServerSockets0: startAccept()
11-03 23:11:02.489  5738  5738 D ObexServerSockets0: prepareForNewConnect()
11-03 23:11:02.490   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:11:02.490  3020  5589 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 23:11:02.491  5738  5738 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-03 23:11:02.491  5738  5738 D BluetoothSdpJni: SDP Create record success - handle: 0
11-03 23:11:02.491  3020  3020 D BluetoothInputDevice: Proxy object connected
11-03 23:11:02.491  3020  5586 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 23:11:02.492  3020  3020 D HidProfile: Bluetooth service connected
11-03 23:11:02.493  5738  5782 D ObexServerSockets0: Accepting socket connection...
11-03 23:11:02.493  5738  5781 D ObexServerSockets0: Accepting socket connection...
11-03 23:11:02.494  3020  3020 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 23:11:02.494  3020  3020 D PanProfile: Bluetooth service connected
11-03 23:11:02.494  3020  3020 D BluetoothA2dp: Proxy object connected
,11-03 23:11:02.495   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-03 23:11:02.496  5738  5738 D BluetoothMapService: onReceive
11-03 23:11:02.496  5738  5738 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 23:11:02.496  5738  5738 D BluetoothMapService: STATE_ON
11-03 23:11:02.497  5567  5567 D BluetoothA2dp: Proxy object connected
11-03 23:11:02.498  5738  5784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:11:02.500  5567  5567 D BluetoothMap: Proxy object connected
,11-03 23:11:02.500  5567  5567 D MapProfile: Bluetooth service connected
11-03 23:11:02.500  5567  5567 D BluetoothMap: getConnectedDevices()
11-03 23:11:02.500  5738  5784 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 23:11:02.500  5738  5784 D BluetoothSdpJni: SDP Create record success - handle: 1
11-03 23:11:02.502  5567  5567 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 23:11:02.502  5567  5567 D PanProfile: Bluetooth service connected
11-03 23:11:02.505  5567  5567 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 23:11:02.511  3483  3483 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 23:11:02.512  5567  5567 D DockEventReceiver: finishStartingService: stopping service
,11-03 23:11:02.519  5567  5567 D BluetoothPbap: Proxy object connected
11-03 23:11:02.519  5567  5567 D PbapServerProfile: Bluetooth service connected
,11-03 23:11:02.523  5738  5738 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 23:11:02.523  5738  5738 D ObexServerSockets0: prepareForNewConnect()
,11-03 23:11:02.525  3020  3020 D BluetoothPbap: Proxy object connected
,11-03 23:11:02.525  5738  5789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 23:11:02.525  3020  3020 D PbapServerProfile: Bluetooth service connected
,11-03 23:11:02.541  5738  5793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:11:02.542  5738  5793 I BtOppRfcommListener: Accept thread started.
,11-03 23:11:02.578   929   929 D BluetoothHeadset: Proxy object connected
,11-03 23:11:02.579  3652  3911 D BluetoothHeadset: Proxy object connected
11-03 23:11:02.579   929   929 D BluetoothHeadset: Proxy object connected
11-03 23:11:02.579  3020  5588 D BluetoothHeadset: Proxy object connected
,11-03 23:11:02.579  3020  3020 D HeadsetProfile: Bluetooth service connected
11-03 23:11:02.580  5567  5579 D BluetoothHeadset: Proxy object connected
,11-03 23:11:02.580   929   946 D BluetoothHeadset: Proxy object connected
11-03 23:11:02.581   929   946 D BluetoothHeadset: Proxy object connected
,11-03 23:11:02.582   929   929 D BluetoothHeadset: Proxy object connected
11-03 23:11:02.585  5567  5567 D HeadsetProfile: Bluetooth service connected
11-03 23:11:02.586  5567  5779 D BluetoothHeadset: Proxy object connected
,11-03 23:11:02.587  3020  3042 D BluetoothHeadset: Proxy object connected
11-03 23:11:02.587  5567  5567 D HeadsetProfile: Bluetooth service connected
11-03 23:11:02.587  3020  3020 D HeadsetProfile: Bluetooth service connected
,11-03 23:11:02.590   929   946 D BluetoothHeadset: Proxy object connected
,11-03 23:11:06.336  3935  4392 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-03 23:11:06.349  5501  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:11:06.349  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:11:06.349  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:11:06.349  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 23:11:06.349  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:11:06.349  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:11:06.349  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:11:06.349  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 23:11:06.354  5501  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 23:11:06.354  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:11:06.355  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7f37eaa removed from the list
,11-03 23:11:06.355  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:11:06.356  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:11:06.357  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c814e38 added. We now have 4 listener(s)
,11-03 23:11:06.357  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:11:06.360   929   939 D WifiService: setWifiEnabled: false pid=5501, uid=10077
11-03 23:11:06.360   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 23:11:11.371  5501  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:11:11.372   929  3060 D WifiService: setWifiEnabled: true pid=5501, uid=10077
11-03 23:11:11.372   929  3060 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 23:11:11.380   508   925 D SoftapController: Softap fwReload - Ok
,11-03 23:11:11.386   508   925 D CommandListener: Setting iface cfg
,11-03 23:11:11.386   508   925 D CommandListener: Trying to bring down wlan0
,11-03 23:11:11.388   508   925 D CommandListener: Clearing all IP addresses on wlan0
,11-03 23:11:11.393   929  2852 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 23:11:12.059   929  2852 D wifi    : set interface wlan0 flags (UP)
,11-03 23:11:12.061   929  2852 I WifiHAL : Initializing wifi
11-03 23:11:12.061   929  2852 I WifiHAL : Creating socket
,11-03 23:11:12.069   929  2852 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-03 23:11:12.069   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-03 23:11:12.069   929  2852 D wifi    : Did set static halHandle = 0x7f5f86fa40
,11-03 23:11:12.069   929  2852 D wifi    : halHandle = 0x7f5f86fa40, mVM = 0x7f7becd140, mCls = 0x1566
,11-03 23:11:12.070   929  2852 D wifi    : array field set
11-03 23:11:12.070   929  2852 I WifiNative-HAL: interface[0] = wlan0
,11-03 23:11:12.073   929  5798 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547063528000
11-03 23:11:12.073   929  5798 D wifi    : waitForHalEvents called, vm = 0x7f7becd140, obj = 0x1566, env = 0x7f6347d840
,11-03 23:11:12.077   929  2852 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 23:11:12.079   929  2852 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-03 23:11:12.126  5799  5799 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 23:11:12.193  5799  5799 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 23:11:12.248  5799  5799 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-03 23:11:12.248  5799  5799 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 23:11:12.713   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:11:13.094   929  2852 D WifiConfigStore: Loading config and enabling all networks 
,11-03 23:11:13.137   929  2852 D WifiConfigStore: loaded 0 passpoint configs
,11-03 23:11:13.139   929  2852 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-03 23:11:13.139   929  2852 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-03 23:11:13.140   929  2852 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-03 23:11:13.141   929  2852 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-03 23:11:13.142   929  2852 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-03 23:11:13.143   929  2852 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-03 23:11:13.144   929  2852 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 23:11:13.144   929  2852 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 23:11:13.144   929  2852 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-03 23:11:13.144   929  2852 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-03 23:11:13.144   929  2852 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 23:11:13.144   929  2852 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 23:11:13.149   929  2852 D WifiNative-HAL: Setting external_sim to 1
,11-03 23:11:13.149  4926  4926 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 23:11:13.150   929  2852 D wifi    : setting dfs flag to true, 0x7f60676ac0
11-03 23:11:13.151   929  2852 D WifiStateMachine: Setting OUI to DA-A1-19
,11-03 23:11:13.151   929  2852 D wifi    : setting scan oui 0x7f60676ac0
11-03 23:11:13.151   929  2852 D WifiHAL : Sending mac address OUI
,11-03 23:11:13.157   929  2852 E native  : do suspend true
,11-03 23:11:13.166   929  2852 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-03 23:11:13.167   929   929 D RttService: SCAN_AVAILABLE : 3
11-03 23:11:13.167   508   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-03 23:11:13.167   929  2961 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 23:11:13.169   508   925 D CommandListener: Setting iface cfg
,11-03 23:11:13.180   929  2851 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,11-03 23:11:13.180   929  2851 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 23:11:13.189   929  2851 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 23:11:13.190   929  2851 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 23:11:13.196   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164748 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=10 mControllerEnergyUsed=38 }
,11-03 23:11:13.715   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:11:14.716   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:11:15.719   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:11:16.359  5799  5799 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 23:11:16.391  5501  5548 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:11:16.391  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:11:16.391  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:11:16.391  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:11:16.391  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:11:16.391  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:11:16.391  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:11:16.391  5501  5548 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 23:11:16.396  5501  5548 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 23:11:16.397   929  2852 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-03 23:11:16.397  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.397  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c814e38 removed from the list
11-03 23:11:16.397  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:11:16.402   929  2852 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,11-03 23:11:16.402   929  2852 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:11:16.408  5501  5548 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-03 23:11:16.409  5501  5548 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-03 23:11:16.413  5501  5548 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21ac195 Bundle[{}]
,11-03 23:11:16.415  5501  5548 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-03 23:11:16.416  5501  5548 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-03 23:11:16.416  5501  5548 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-03 23:11:16.417  5501  5548 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-03 23:11:16.417   929  2852 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
11-03 23:11:16.418  5501  5548 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-03 23:11:16.418  5501  5548 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-03 23:11:16.426  5501  5548 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 172)
,11-03 23:11:16.427  5501  5548 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-03 23:11:16.427  5501  5548 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 173)
,11-03 23:11:16.430  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 23:11:16.430  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@338e11 added. We now have 3 listener(s)
,11-03 23:11:16.432  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 23:11:16.433  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:11:16.433  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:11:16.433  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 23:11:16.433  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d62db76 added. We now have 4 listener(s)
11-03 23:11:16.433  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:11:16.434  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 23:11:16.436  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 23:11:16.436  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5399577 added. We now have 4 listener(s)
11-03 23:11:16.438  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:11:16.438  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:11:16.438  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:11:16.438  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 23:11:16.439  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61915e4 added. We now have 5 listener(s)
11-03 23:11:16.439  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:11:16.439  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:11:16.439  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:11:16.439  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:11:16.439  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 23:11:16.439  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:11:16.439  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:11:16.439  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@338e11 removed from the list
11-03 23:11:16.439  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.439  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d62db76 removed from the list
11-03 23:11:16.440  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:11:16.440  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:11:16.442  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.442  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.442  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.442  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:11:16.442  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 23:11:16.442  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.442  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d62db76 not in the list
11-03 23:11:16.443  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:11:16.444  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.444  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.445  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.445  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:11:16.445  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 23:11:16.445  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.445  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61915e4 removed from the list
11-03 23:11:16.445  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:11:16.445  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:11:16.445  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:11:16.445  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5399577 removed from the list
11-03 23:11:16.446  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:11:16.446  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb1fa4d added. We now have 3 listener(s)
11-03 23:11:16.448  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:11:16.448  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 23:11:16.448  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:11:16.448  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:11:16.449  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d993902 added. We now have 4 listener(s)
11-03 23:11:16.449  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:11:16.449  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 23:11:16.451  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:11:16.451  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3281213 added. We now have 4 listener(s)
11-03 23:11:16.453  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:11:16.453  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 23:11:16.453  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:11:16.453  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:11:16.453  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b43ac50 added. We now have 5 listener(s)
11-03 23:11:16.453  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:11:16.453  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:11:16.453  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 23:11:16.454  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 23:11:16.454  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:11:16.454  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 23:11:16.456  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 23:11:16.461  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 23:11:16.461  5501  5548 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 23:11:16.461  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 23:11:16.463   929  2852 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 23:11:16.466  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:11:16.466  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 23:11:16.467  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 23:11:16.467  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 23:11:16.467  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 23:11:16.470  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.471  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 23:11:16.471  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-03 23:11:16.471  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 23:11:16.471  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 23:11:16.471  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.472  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:11:16.475  5738  5783 D BtGatt.GattService: registerClient() - UUID=8e0f16d9-f9ac-4f37-afcb-e369a7cb2e53
,11-03 23:11:16.477  5738  5754 D BtGatt.GattService: onClientRegistered() - UUID=8e0f16d9-f9ac-4f37-afcb-e369a7cb2e53, clientIf=5
,11-03 23:11:16.477  5501  5512 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 23:11:16.478  5738  5748 D BtGatt.GattService: start scan with filters
,11-03 23:11:16.482  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 23:11:16.482  5738  5757 D BtGatt.ScanManager: handling starting scan
11-03 23:11:16.482  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:11:16.482  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 23:11:16.482  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:11:16.482  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 23:11:16.482  5501  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 23:11:16.482  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-03 23:11:16.482  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 23:11:16.482  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 23:11:16.483  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.483  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.483  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 23:11:16.483  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 23:11:16.483  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.484  5738  5757 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e2da9e
,11-03 23:11:16.486  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.486  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:11:16.486  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.486  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.486  5501  5548 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 23:11:16.486  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 23:11:16.486  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 23:11:16.486  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:11:16.486  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.486  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:11:16.486  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:11:16.487  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 23:11:16.490  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.490  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.492  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.492  5738  5754 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 23:11:16.492  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.492  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.492  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 23:11:16.492  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:11:16.492  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 23:11:16.492  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 23:11:16.492  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.492  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:11:16.492  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:11:16.493  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 23:11:16.493  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.493  5738  5757 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 23:11:16.494  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:11:16.494  5738  5783 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 23:11:16.494  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 23:11:16.495  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:11:16.496  5738  5749 D BtGatt.GattService: stopScan() - queue size =1
,11-03 23:11:16.496  5738  5785 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 23:11:16.497  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 23:11:16.497  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.497  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 23:11:16.497  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.497  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.497  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.497  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.497  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 23:11:16.497  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.497  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.497  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.498  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 23:11:16.498  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 23:11:16.498  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 23:11:16.498  5738  5754 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 23:11:16.499  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.499  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.499  5738  5757 D BtGatt.ScanManager: Starting BLE batch scan
11-03 23:11:16.499  5738  5757 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 23:11:16.500  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.500  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:11:16.500  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.500  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.500  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:11:16.500  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:11:16.500  5501  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-03 23:11:16.500  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.500  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 23:11:16.500  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 23:11:16.500  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.500  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.500  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 23:11:16.501  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.502  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:11:16.502  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 23:11:16.502  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:11:16.502  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:11:16.502  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:11:16.502  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:11:16.502  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.503  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.503  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb1fa4d removed from the list
11-03 23:11:16.503  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.503  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.503  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d993902 removed from the list
,11-03 23:11:16.503  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.503  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:11:16.503  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:11:16.503  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.504  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.504  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.504  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.504  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:11:16.504  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:11:16.504  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.504  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d993902 not in the list
11-03 23:11:16.504  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.507  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.507  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.507  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.507  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:11:16.507  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:11:16.507  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.507  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b43ac50 removed from the list
11-03 23:11:16.507  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:11:16.507  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:11:16.507  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:11:16.507  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3281213 removed from the list
11-03 23:11:16.508  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:11:16.508  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3912605 added. We now have 3 listener(s)
11-03 23:11:16.510  5738  5754 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 23:11:16.510  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.510  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:11:16.510  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:11:16.510  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 23:11:16.511  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:11:16.511  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b40e65a added. We now have 4 listener(s)
11-03 23:11:16.511  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:11:16.511  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 23:11:16.515  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:11:16.515  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46db08b added. We now have 4 listener(s)
,11-03 23:11:16.516  5738  5754 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 23:11:16.516  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:11:16.516  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.517  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:11:16.517  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:11:16.517  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:11:16.517  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@500b568 added. We now have 5 listener(s)
11-03 23:11:16.517  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:11:16.517  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-03 23:11:16.518  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:11:16.518  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 23:11:16.518  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 23:11:16.518  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:11:16.518  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 23:11:16.519  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 23:11:16.520  5738  5757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 23:11:16.522  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 23:11:16.523  5501  5548 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 23:11:16.523  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 23:11:16.525  5738  5754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:11:16.525  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.526  5738  5754 E BtGatt.ContextMap: Context not found for ID 5
,11-03 23:11:16.527  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.527  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 23:11:16.528  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 23:11:16.528  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 23:11:16.528  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 23:11:16.531  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:11:16.532  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 23:11:16.532  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 23:11:16.532  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 23:11:16.532  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 23:11:16.532  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.532  5738  5754 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 23:11:16.532  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:11:16.533  5738  5757 D BtGatt.ScanManager: stopping BLe Batch
11-03 23:11:16.533  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:11:16.535  5738  5783 D BtGatt.GattService: registerClient() - UUID=d6999941-6a8d-4178-a0af-c365626f1c4e
,11-03 23:11:16.536  5738  5754 D BtGatt.GattService: onClientRegistered() - UUID=d6999941-6a8d-4178-a0af-c365626f1c4e, clientIf=5
,11-03 23:11:16.536  5501  5512 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-03 23:11:16.537  5738  5785 D BtGatt.GattService: start scan with filters
,11-03 23:11:16.539  5738  5754 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 23:11:16.539  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.539  5738  5757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 23:11:16.540  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 23:11:16.540  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.540  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 23:11:16.540  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.540  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 23:11:16.540  5501  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 23:11:16.540  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.540  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 23:11:16.540  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 23:11:16.540  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.541  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.541  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 23:11:16.542  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-03 23:11:16.542  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.544  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.544  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:11:16.544  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.544  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.544  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.544  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:11:16.544  5501  5548 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 23:11:16.544  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:11:16.544  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:11:16.544  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:11:16.545  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:11:16.545  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 23:11:16.545  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:11:16.545  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:11:16.545  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:11:16.545  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3912605 removed from the list
11-03 23:11:16.545  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.545  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b40e65a removed from the list
,11-03 23:11:16.545  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:11:16.545  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:11:16.545  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-03 23:11:16.545  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-03 23:11:16.545  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-03 23:11:16.545  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:11:16.545  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:11:16.545  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.546  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.546  5738  5754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:11:16.546  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.546  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:11:16.546  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.546  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:11:16.546  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:11:16.546  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.546  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b40e65a not in the list
11-03 23:11:16.547  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.547  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.547  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.547  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.547  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:11:16.547  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:11:16.547  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 23:11:16.547  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 23:11:16.547  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.547  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.547  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.547  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 23:11:16.547  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.548  5738  5757 D BtGatt.ScanManager: handling starting scan
11-03 23:11:16.548  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:11:16.548  5738  5785 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 23:11:16.549  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 23:11:16.549  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:11:16.550  5738  5749 D BtGatt.GattService: stopScan() - queue size =1
11-03 23:11:16.550  5738  5748 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 23:11:16.551  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 23:11:16.551  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.551  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 23:11:16.551  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.551  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:11:16.551  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.551  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.551  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 23:11:16.551  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.551  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.551  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.551  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 23:11:16.551  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 23:11:16.552  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 23:11:16.552  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.553  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.553  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:11:16.554  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.554  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.554  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:11:16.554  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:11:16.554  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.554  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@500b568 removed from the list
11-03 23:11:16.554  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:11:16.554  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:11:16.554  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:11:16.554  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:11:16.554  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:11:16.554  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46db08b removed from the list
11-03 23:11:16.554  5501  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 23:11:16.554  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.554  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 23:11:16.554  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 23:11:16.554  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.554  5738  5754 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 23:11:16.554  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.554  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.555  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 23:11:16.555  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.555  5738  5757 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 23:11:16.555  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:11:16.555  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4310bd added. We now have 3 listener(s)
11-03 23:11:16.556  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.556  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.556  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.556  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.556  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:11:16.556  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:11:16.556  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:11:16.557  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:11:16.557  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:11:16.557  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad5e6b2 added. We now have 4 listener(s)
11-03 23:11:16.557  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:11:16.557  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 23:11:16.558  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:11:16.558  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@909a603 added. We now have 4 listener(s)
11-03 23:11:16.559  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:11:16.559  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:11:16.560  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:11:16.560  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:11:16.560  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@302c980 added. We now have 5 listener(s)
11-03 23:11:16.560  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:11:16.560  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:11:16.560  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 23:11:16.560  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 23:11:16.560  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:11:16.560  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 23:11:16.560  5738  5754 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 23:11:16.561  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.561  5738  5757 D BtGatt.ScanManager: Starting BLE batch scan
11-03 23:11:16.561  5738  5757 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 23:11:16.561  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 23:11:16.565  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 23:11:16.565  5501  5548 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 23:11:16.565  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 23:11:16.569  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.569  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 23:11:16.570  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 23:11:16.570  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 23:11:16.570  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 23:11:16.573  5738  5754 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 23:11:16.573  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.575  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.575  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 23:11:16.575  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 23:11:16.575  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 23:11:16.575  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 23:11:16.576  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.576  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:11:16.577  5738  5754 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 23:11:16.577  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.579  5738  5757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 23:11:16.579  5738  5780 D BtGatt.GattService: registerClient() - UUID=937b6df3-f6a4-4fb0-9d8d-6f6005596249
11-03 23:11:16.579  5738  5754 D BtGatt.GattService: onClientRegistered() - UUID=937b6df3-f6a4-4fb0-9d8d-6f6005596249, clientIf=5
11-03 23:11:16.580  5501  5512 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 23:11:16.580  5738  5749 D BtGatt.GattService: start scan with filters
11-03 23:11:16.584  5738  5754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:11:16.584  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.585  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 23:11:16.585  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.585  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 23:11:16.585  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.585  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 23:11:16.585  5501  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 23:11:16.585  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.585  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 23:11:16.585  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 23:11:16.585  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.586  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.586  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 23:11:16.586  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 23:11:16.586  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
,11-03 23:11:16.589  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.589  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:11:16.589  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.589  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.589  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.590  5738  5754 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 23:11:16.590  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.590  5738  5757 D BtGatt.ScanManager: stopping BLe Batch
11-03 23:11:16.592  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.592  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.592  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.592  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.592  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.593  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:11:16.593  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:11:16.593  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:11:16.593  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:11:16.593  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:11:16.593  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:11:16.593  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:11:16.593  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:11:16.593  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:11:16.593  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4310bd removed from the list
11-03 23:11:16.593  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.593  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad5e6b2 removed from the list
11-03 23:11:16.594  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:11:16.594  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:11:16.594  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:11:16.594  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-03 23:11:16.594  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-03 23:11:16.594  5501  5548 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:11:16.594  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:11:16.594  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.594  5738  5754 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 23:11:16.595  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.595  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.595  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.595  5738  5757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 23:11:16.595  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.595  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:11:16.595  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:11:16.595  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.595  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad5e6b2 not in the list
11-03 23:11:16.595  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:11:16.595  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 23:11:16.595  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 23:11:16.595  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.595  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.595  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.595  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 23:11:16.595  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.596  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:11:16.596  5738  5783 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 23:11:16.596  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 23:11:16.597  5501  5548 D BluetoothAdapter: STATE_ON
11-03 23:11:16.597  5738  5749 D BtGatt.GattService: stopScan() - queue size =0
11-03 23:11:16.597  5738  5785 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 23:11:16.598  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 23:11:16.598  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.598  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 23:11:16.598  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.598  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.598  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.598  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.598  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 23:11:16.598  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.598  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.598  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.598  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 23:11:16.598  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 23:11:16.599  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 23:11:16.599  5738  5754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:11:16.599  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.599  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.600  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.600  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:11:16.600  5738  5757 D BtGatt.ScanManager: handling starting scan
11-03 23:11:16.600  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.600  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.600  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:11:16.600  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:11:16.600  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.600  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:11:16.600  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@302c980 removed from the list
11-03 23:11:16.600  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:11:16.601  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:11:16.601  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:11:16.601  5501  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 23:11:16.601  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:11:16.601  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@909a603 removed from the list
11-03 23:11:16.601  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.601  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 23:11:16.601  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 23:11:16.601  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.601  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.601  5501  5501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 23:11:16.601  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.601  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:11:16.601  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7809a75 added. We now have 3 listener(s)
11-03 23:11:16.602  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.602  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.602  5501  5501 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.602  5501  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:11:16.602  5501  5501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:11:16.602  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:11:16.603  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:11:16.603  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:11:16.603  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:11:16.603  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4f9a0a added. We now have 4 listener(s)
11-03 23:11:16.603  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:11:16.604  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 23:11:16.605  5738  5754 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 23:11:16.605  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:11:16.605  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.605  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8fd27b added. We now have 4 listener(s)
11-03 23:11:16.606  5738  5757 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 23:11:16.606  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:11:16.606  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:11:16.606  5501  5548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:11:16.607  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:11:16.607  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1804898 added. We now have 5 listener(s)
11-03 23:11:16.607  5501  5548 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:11:16.607  5501  5548 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:11:16.607  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:11:16.607  5501  5548 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:11:16.607  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:11:16.607  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:11:16.607  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:11:16.607  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7809a75 removed from the list
11-03 23:11:16.607  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.607  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4f9a0a removed from the list
11-03 23:11:16.607  5501  5548 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:11:16.607  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.608  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.608  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.608  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.608  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:11:16.609  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:11:16.609  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.609  5501  5548 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4f9a0a not in the list
11-03 23:11:16.609  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.610  5738  5754 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 23:11:16.610  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.610  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.610  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.610  5501  5548 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-65,5,main], id: 65
11-03 23:11:16.611  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:11:16.611  5738  5757 D BtGatt.ScanManager: Starting BLE batch scan
11-03 23:11:16.611  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:11:16.611  5501  5548 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:11:16.611  5738  5757 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 23:11:16.611  5501  5548 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1804898 removed from the list
11-03 23:11:16.611  5501  5548 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:11:16.611  5501  5548 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:11:16.611  5501  5548 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:11:16.611  5501  5548 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8fd27b removed from the list
11-03 23:11:16.612  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-03 23:11:16.612  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-03 23:11:16.612  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-03 23:11:16.612  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:11:16.612  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-03 23:11:16.612  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 23:11:16.619  5738  5754 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 23:11:16.619  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.624  5738  5754 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 23:11:16.624  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.625  5738  5757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 23:11:16.630  5738  5754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:11:16.630  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.630  5738  5754 E BtGatt.ContextMap: Context not found for ID 5
11-03 23:11:16.635  5738  5754 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 23:11:16.635  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.635  5738  5757 D BtGatt.ScanManager: stopping BLe Batch
11-03 23:11:16.640  5738  5754 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 23:11:16.640  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:11:16.640  5738  5757 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 23:11:16.644  5738  5754 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:11:16.644  5738  5754 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:11:16.720   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:11:16.819  5799  5799 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 23:11:16.858  5799  5799 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 23:11:16.859  5799  5799 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 23:11:16.870   929  2852 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 23:11:16.871   929  2852 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 23:11:16.871   929  2854 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 23:11:16.888   929  2852 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:11:16.903   508   925 D CommandListener: Setting iface cfg
,11-03 23:11:16.910   929  2852 D WifiStateMachine: Start Dhcp Watchdog 3
,11-03 23:11:16.915   929  2852 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-03 23:11:16.929   929  5804 D DhcpClient: Receive thread started
,11-03 23:11:17.004  5501  5501 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 23:11:17.026   929  2852 E native  : do suspend false
,11-03 23:11:17.045   929  5803 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 23:11:17.057  5501  5501 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 23:11:17.065   929  5804 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-03 23:11:17.066   929  5803 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-03 23:11:17.070   929  5803 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 23:11:17.085   929  5804 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 23:11:17.086   929  5803 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-03 23:11:17.090   508   925 D CommandListener: Setting iface cfg
,11-03 23:11:17.096   929  2852 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 23:11:17.101   929  5803 D DhcpClient: Scheduling renewal in 86399s
,11-03 23:11:17.102  5501  5501 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
11-03 23:11:17.102   929  2852 E native  : do suspend true
,11-03 23:11:17.131   929  2852 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-03 23:11:17.133   929  2852 D WifiConfigStore: No blacklist allowed without epno enabled
,11-03 23:11:17.135   929  2854 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-03 23:11:17.138   929  2854 D ConnectivityService: Adding iface wlan0 to network 102
,11-03 23:11:17.140   929  2852 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-03 23:11:17.195   929  2854 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-03 23:11:17.197   929  2854 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-03 23:11:17.200   929  2854 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-03 23:11:17.202   929  2854 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-03 23:11:17.205   929  2854 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-03 23:11:17.211   929  2854 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-03 23:11:17.216   929  2854 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-03 23:11:17.216   929  2854 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-03 23:11:17.216   929  2854 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,11-03 23:11:17.216   929  2854 D ConnectivityService:    accepting network in place of null
11-03 23:11:17.216   929  2852 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-03 23:11:17.216   929  2852 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 23:11:17.217   929  2854 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 23:11:17.232   929  5802 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 23:11:17.239   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:11:17.262   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:11:17.266   929  2854 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-03 23:11:17.266   929  2854 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-03 23:11:17.266  3617  3755 W QCNEJ   : |CORE| network available: 102
,11-03 23:11:17.270  3617  3755 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-03 23:11:17.270   929   946 D Tethering: MasterInitialState.processMessage what=3
11-03 23:11:17.270   929  2854 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-03 23:11:17.271  3617  3755 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-03 23:11:17.272  3617  3755 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-03 23:11:17.280  3866  3866 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-03 23:11:17.283  3735  3735 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-03 23:11:17.286  3735  3735 D SystemUpdateService: onCreate
,11-03 23:11:17.290  3735  3735 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 23:11:17.303  3735  3735 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-03 23:11:17.308  3735  5813 I SystemUpdateService: active receiver: enabled
,11-03 23:11:17.311  3735  4182 I iu.UploadsManager: num queued entries: 0
,11-03 23:11:17.311  3735  4182 I iu.UploadsManager: num updated entries: 0
11-03 23:11:17.313   929  5801 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:400d:803::200e
11-03 23:11:17.313  3735  3735 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-03 23:11:17.319  3735  3735 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-03 23:11:17.321  5609  5609 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-03 23:11:17.324  5609  5609 D SprintDMHelper: simOperator: 
11-03 23:11:17.324  5609  5609 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 23:11:17.327  3735  5813 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 23:11:17.332  3735  4182 I iu.SyncManager: NEXT; no task
,11-03 23:11:17.346  3735  5813 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-03 23:11:17.346  3735  5813 I SystemUpdateService: now status is 0 (complete)
11-03 23:11:17.346  3735  5813 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 23:11:17.347  3735  5813 I SystemUpdateService: file has been verified
11-03 23:11:17.347  3735  5813 I SystemUpdateService: OTA package size = 21989297
,11-03 23:11:17.358  3735  5813 I SystemUpdateService: showing system update notification
,11-03 23:11:17.368   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 23:11:17.369  3735  3735 D SystemUpdateService: onDestroy
,11-03 23:11:17.379   929  5801 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 22:11:17 GMT], X-Android-Received-Millis=[1478211077379], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478211077349]}
,11-03 23:11:17.380   929  2854 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-03 23:11:17.380   929  2854 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-03 23:11:17.380   929  2854 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-03 23:11:17.381   929  2854 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-03 23:11:17.721   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-03 23:11:18.785  5501  5821 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 23:11:18.785  5501  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:11:19.588  5501  5821 W !!      : call onHalfStreamCopied
,11-03 23:11:19.588  5501  5821 I testCopyDataAndClose: closing input stream
,11-03 23:11:20.366  5501  5821 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 181, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 23:11:20.366  5501  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:11:20.366  5501  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 23:11:20.366  5501  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 23:11:20.366  5501  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 23:11:20.366  5501  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-03 23:11:20.366  5501  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-03 23:11:20.366  5501  5821 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 23:11:20.366  5501  5821 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 23:11:20.366  5501  5821 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 23:11:20.366  5501  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 23:11:20.593  3735  5822 I EventLogService: Aggregate from 1478210094317 (log), 1478209272911 (data)
,11-03 23:11:20.666  3483  5825 I VacuumService: Vacuum at: now=1478211080666 tag=VacuumService
,11-03 23:11:20.708  3483  5828 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-03 23:11:20.737  3483  5826 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-03 23:11:20.739  3483  5826 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-03 23:11:20.762  3483  5826 W Uploader:  no longer exists, so no auth token.
,11-03 23:11:20.767  3483  5828 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 23:11:21.035  3483  5830 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 23:11:21.182  3483  5826 W Uploader:  no longer exists, so no auth token.
,11-03 23:11:21.189  3483  5828 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 23:11:21.267  3483  5830 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 23:11:21.363  3483  5828 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 23:11:21.459  3483  5830 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 23:11:24.809  5501  5835 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:11:24.809  5501  5835 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:11:25.224   929  2854 D ConnectivityService: handlePromptUnvalidated 102
,11-03 23:11:26.809  5501  5548 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 184. Connection data: Peer properties: [null null].
11-03 23:11:26.809  5501  5548 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 23:11:26.809  5501  5548 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 184, name: My test thread name)
,11-03 23:11:26.864  5501  5835 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-03 23:11:26.864  5501  5835 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:11:26.864  5501  5835 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-03 23:11:26.977  5501  5836 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 23:11:26.977  5501  5836 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:11:28.614  5501  5836 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 186, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 23:11:28.614  5501  5836 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:11:28.615  5501  5836 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 23:11:28.615  5501  5836 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:11:28.615  5501  5836 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 23:11:28.615  5501  5836 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-03 23:11:28.615  5501  5836 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 23:11:28.615  5501  5836 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 23:11:28.615  5501  5836 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 23:11:28.615  5501  5836 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 23:11:28.615  5501  5836 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 23:11:33.090  5501  5837 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:11:33.090  5501  5837 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:11:33.090  5501  5837 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 188, thread name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:11:33.090  5501  5837 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 23:11:33.090  5501  5837 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 23:11:33.090  5501  5837 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:11:33.091  5501  5837 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 23:11:33.091  5501  5837 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-03 23:11:33.091  5501  5837 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-03 23:11:33.091  5501  5837 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-03 23:11:33.091  5501  5837 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-03 23:11:33.092  5501  5837 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:11:33.092  5501  5837 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-03 23:11:33.093  5501  5548 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-03 23:11:33.097  5501  5838 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:11:33.097  5501  5838 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 23:11:33.098  5501  5838 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 192, thread name: My test thread name): Test exception.
,11-03 23:11:33.099  5501  5838 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:11:33.099  5501  5838 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-03 23:11:33.099  5501  5838 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-03 23:11:33.099  5501  5838 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:11:33.099  5501  5838 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-03 23:11:33.105  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-03 23:11:33.105  5501  5548 I jxcore-log: 
,11-03 23:11:33.106  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-03 23:11:33.106  5501  5548 I jxcore-log: 
11-03 23:11:33.106  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-03 23:11:33.106  5501  5548 I jxcore-log: 
11-03 23:11:33.106  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-03 23:11:33.106  5501  5548 I jxcore-log: 
11-03 23:11:33.106  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG UnitTest_app: 'Total duration:  92303'
11-03 23:11:33.106  5501  5548 I jxcore-log: 
,11-03 23:11:33.108  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-03 23:11:33.108  5501  5548 I jxcore-log: 
,11-03 23:11:33.112  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 23:11:33.112  5501  5548 I jxcore-log: 
,11-03 23:11:33.112  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 23:11:33.112  5501  5548 I jxcore-log: 
11-03 23:11:33.113  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-03 23:11:33.113  5501  5548 I jxcore-log: 
,11-03 23:11:33.113  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-03 23:11:33.113  5501  5548 I jxcore-log: 
11-03 23:11:33.113  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:11:33.113  5501  5548 I jxcore-log: 
11-03 23:11:33.114  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 23:11:33.114  5501  5548 I jxcore-log: 
,11-03 23:11:33.114  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:11:33.114  5501  5548 I jxcore-log: 
11-03 23:11:33.114  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 23:11:33.114  5501  5548 I jxcore-log: 
11-03 23:11:33.115  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 23:11:33.115  5501  5548 I jxcore-log: 
,11-03 23:11:33.115  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-03 23:11:33.115  5501  5548 I jxcore-log: 
11-03 23:11:33.115  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-03 23:11:33.115  5501  5548 I jxcore-log: 
11-03 23:11:33.115  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:11:33.115  5501  5548 I jxcore-log: 
,11-03 23:11:33.116  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 23:11:33.116  5501  5548 I jxcore-log: 
11-03 23:11:33.116  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:11:33.116  5501  5548 I jxcore-log: 
11-03 23:11:33.116  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 23:11:33.116  5501  5548 I jxcore-log: 
11-03 23:11:33.116  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:11:33.116  5501  5548 I jxcore-log: 
,11-03 23:11:33.116  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 23:11:33.116  5501  5548 I jxcore-log: 
11-03 23:11:33.117  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 23:11:33.117  5501  5548 I jxcore-log: 
11-03 23:11:33.117  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 23:11:33.117  5501  5548 I jxcore-log: 
11-03 23:11:33.117  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 23:11:33.117  5501  5548 I jxcore-log: 
11-03 23:11:33.117  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 23:11:33.117  5501  5548 I jxcore-log: 
,11-03 23:11:33.118  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 23:11:33.118  5501  5548 I jxcore-log: 
11-03 23:11:33.118  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 23:11:33.118  5501  5548 I jxcore-log: 
11-03 23:11:33.118  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 23:11:33.118  5501  5548 I jxcore-log: 
11-03 23:11:33.120  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 23:11:33.120  5501  5548 I jxcore-log: 
11-03 23:11:33.120  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 23:11:33.120  5501  5548 I jxcore-log: 
11-03 23:11:33.120  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 23:11:33.120  5501  5548 I jxcore-log: 
11-03 23:11:33.121  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:11:33.121  5501  5548 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-03 23:11:33.121  5501  5548 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:11:33.121  5501  5548 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,11-03 23:11:33.121  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 23:11:33.121  5501  5548 I jxcore-log: 
11-03 23:11:33.121  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:11:33.121  5501  5548 I jxcore-log: 
11-03 23:11:33.122  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 23:11:33.122  5501  5548 I jxcore-log: 
,11-03 23:11:33.122  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:11:33.122  5501  5548 I jxcore-log: 
11-03 23:11:33.122  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 23:11:33.122  5501  5548 I jxcore-log: 
11-03 23:11:33.122  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:11:33.122  5501  5548 I jxcore-log: 
,11-03 23:11:33.124  5501  5501 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-03 23:11:33.127  5501  5548 I jxcore-log: 2016-11-03 22:11:33 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-03 23:11:33.127  5501  5548 I jxcore-log: 
,11-03 23:11:35.193  5501  5548 I jxcore-log: 2016-11-03 22:11:35 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-03 23:11:35.193  5501  5548 I jxcore-log: 
,11-03 23:11:35.195  5501  5548 I jxcore-log: 2016-11-03 22:11:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-03 23:11:35.195  5501  5548 I jxcore-log: 
,11-03 23:11:35.533  5501  5548 I jxcore-log: 2016-11-03 22:11:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-03 23:11:35.533  5501  5548 I jxcore-log: 
,11-03 23:11:35.547  5501  5548 I jxcore-log: 2016-11-03 22:11:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-03 23:11:35.547  5501  5548 I jxcore-log: 
,11-03 23:11:36.667  5501  5548 I jxcore-log: 2016-11-03 22:11:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-03 23:11:36.667  5501  5548 I jxcore-log: 
,11-03 23:11:36.854  5501  5548 I jxcore-log: 2016-11-03 22:11:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-03 23:11:36.854  5501  5548 I jxcore-log: 
,11-03 23:11:36.860  5501  5548 I jxcore-log: 2016-11-03 22:11:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-03 23:11:36.860  5501  5548 I jxcore-log: 
,11-03 23:11:36.865  5501  5548 I jxcore-log: 2016-11-03 22:11:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-03 23:11:36.865  5501  5548 I jxcore-log: 
,11-03 23:11:37.344  5501  5548 I jxcore-log: 2016-11-03 22:11:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-03 23:11:37.344  5501  5548 I jxcore-log: 
,11-03 23:11:37.388  5501  5548 I jxcore-log: 2016-11-03 22:11:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-03 23:11:37.388  5501  5548 I jxcore-log: 
,11-03 23:11:37.401  5501  5548 I jxcore-log: 2016-11-03 22:11:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-03 23:11:37.401  5501  5548 I jxcore-log: 
,11-03 23:11:37.406  5501  5548 I jxcore-log: 2016-11-03 22:11:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-03 23:11:37.406  5501  5548 I jxcore-log: 
,11-03 23:11:37.692  5501  5548 I jxcore-log: 2016-11-03 22:11:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-03 23:11:37.692  5501  5548 I jxcore-log: 
,11-03 23:11:37.722   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:11:37.817  5501  5548 I jxcore-log: 2016-11-03 22:11:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-03 23:11:37.817  5501  5548 I jxcore-log: 
,11-03 23:11:38.192  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-03 23:11:38.192  5501  5548 I jxcore-log: 
,11-03 23:11:38.200  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-03 23:11:38.200  5501  5548 I jxcore-log: 
,11-03 23:11:38.204  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-03 23:11:38.204  5501  5548 I jxcore-log: 
,11-03 23:11:38.210  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-03 23:11:38.210  5501  5548 I jxcore-log: 
,11-03 23:11:38.216  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-03 23:11:38.216  5501  5548 I jxcore-log: 
,11-03 23:11:38.243  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-03 23:11:38.243  5501  5548 I jxcore-log: 
,11-03 23:11:38.278  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-03 23:11:38.278  5501  5548 I jxcore-log: 
,11-03 23:11:38.285  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-03 23:11:38.285  5501  5548 I jxcore-log: 
,11-03 23:11:38.292  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-03 23:11:38.292  5501  5548 I jxcore-log: 
,11-03 23:11:38.307  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-03 23:11:38.307  5501  5548 I jxcore-log: 
,11-03 23:11:38.312  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-03 23:11:38.312  5501  5548 I jxcore-log: 
,11-03 23:11:38.318  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-03 23:11:38.318  5501  5548 I jxcore-log: 
,11-03 23:11:38.323  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-03 23:11:38.323  5501  5548 I jxcore-log: 
,11-03 23:11:38.336  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-03 23:11:38.336  5501  5548 I jxcore-log: 
,11-03 23:11:38.372  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-03 23:11:38.372  5501  5548 I jxcore-log: 
,11-03 23:11:38.387  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-03 23:11:38.387  5501  5548 I jxcore-log: 
,11-03 23:11:38.398  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-03 23:11:38.398  5501  5548 I jxcore-log: 
,11-03 23:11:38.420  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-03 23:11:38.420  5501  5548 I jxcore-log: 
,11-03 23:11:38.431  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-03 23:11:38.431  5501  5548 I jxcore-log: 
,11-03 23:11:38.445  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-03 23:11:38.445  5501  5548 I jxcore-log: 
,11-03 23:11:38.455  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-03 23:11:38.455  5501  5548 I jxcore-log: 
,11-03 23:11:38.462  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-03 23:11:38.462  5501  5548 I jxcore-log: 
,11-03 23:11:38.484  5501  5548 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-03 23:11:38.485  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - INFO testUtils: 'BLE multiple advertisement supported'
11-03 23:11:38.485  5501  5548 I jxcore-log: 
,11-03 23:11:38.562  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:38.562  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:38.562  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:38.562  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:38.562  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:38.562  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:38.562  5501  5548 I jxcore-log: 
,11-03 23:11:38.723   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:11:38.745  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:38.745  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:38.745  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:38.745  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:38.745  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:38.745  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:38.745  5501  5548 I jxcore-log: 
,11-03 23:11:38.748  5501  5548 I jxcore-log: 2016-11-03 22:11:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:38.748  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:38.748  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:38.748  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:38.748  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:38.748  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:38.748  5501  5548 I jxcore-log: 
,11-03 23:11:39.383  5501  5548 I jxcore-log: 2016-11-03 22:11:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:39.383  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:39.383  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:39.383  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:39.383  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:39.383  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:39.383  5501  5548 I jxcore-log: 
,11-03 23:11:39.388  5501  5548 I jxcore-log: 2016-11-03 22:11:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:39.388  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:39.388  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:39.388  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:39.388  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:39.388  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:39.388  5501  5548 I jxcore-log: 
,11-03 23:11:39.724   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:11:40.126  5501  5548 I jxcore-log: 2016-11-03 22:11:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:40.126  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:40.126  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:40.126  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:40.126  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:40.126  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:40.126  5501  5548 I jxcore-log: 
,11-03 23:11:40.130  5501  5548 I jxcore-log: 2016-11-03 22:11:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:40.130  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:40.130  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:40.130  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:40.130  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:40.130  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:40.130  5501  5548 I jxcore-log: 
,11-03 23:11:40.725   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:11:41.226  5501  5548 I jxcore-log: 2016-11-03 22:11:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:41.226  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:41.226  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:41.226  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:41.226  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:41.226  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:41.226  5501  5548 I jxcore-log: 
,11-03 23:11:41.235  5501  5548 I jxcore-log: 2016-11-03 22:11:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:41.235  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:41.235  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:41.235  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:41.235  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:41.235  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:41.235  5501  5548 I jxcore-log: 
,11-03 23:11:41.726   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:11:42.273  5501  5548 I jxcore-log: 2016-11-03 22:11:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:42.273  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:42.273  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:42.273  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:42.273  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:42.273  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:42.273  5501  5548 I jxcore-log: 
,11-03 23:11:42.276  5501  5548 I jxcore-log: 2016-11-03 22:11:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:42.276  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:42.276  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:42.276  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:42.276  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:42.276  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:42.276  5501  5548 I jxcore-log: 
,11-03 23:11:42.727   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 23:11:43.306  5501  5548 I jxcore-log: 2016-11-03 22:11:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:43.306  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:43.306  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:43.306  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:43.306  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:43.306  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:43.306  5501  5548 I jxcore-log: 
,11-03 23:11:43.310  5501  5548 I jxcore-log: 2016-11-03 22:11:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:43.310  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:43.310  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:43.310  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:43.310  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:43.310  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:43.310  5501  5548 I jxcore-log: 
,11-03 23:11:44.343  5501  5548 I jxcore-log: 2016-11-03 22:11:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:44.343  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:44.343  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:44.343  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:44.343  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:44.343  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:44.343  5501  5548 I jxcore-log: 
,11-03 23:11:44.347  5501  5548 I jxcore-log: 2016-11-03 22:11:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:44.347  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:44.347  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:44.347  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:44.347  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:44.347  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:44.347  5501  5548 I jxcore-log: 
,11-03 23:11:45.379  5501  5548 I jxcore-log: 2016-11-03 22:11:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:45.379  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:45.379  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:45.379  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:45.379  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:45.379  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:45.379  5501  5548 I jxcore-log: 
,11-03 23:11:45.385  5501  5548 I jxcore-log: 2016-11-03 22:11:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:45.385  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:45.385  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:45.385  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:45.385  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:45.385  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:45.385  5501  5548 I jxcore-log: 
,11-03 23:11:46.413  5501  5548 I jxcore-log: 2016-11-03 22:11:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:46.413  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:46.413  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:46.413  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:46.413  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:46.413  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:46.413  5501  5548 I jxcore-log: 
,11-03 23:11:46.416  5501  5548 I jxcore-log: 2016-11-03 22:11:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:46.416  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:46.416  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:46.416  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:46.416  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:46.416  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:46.416  5501  5548 I jxcore-log: 
,11-03 23:11:47.479  5501  5548 I jxcore-log: 2016-11-03 22:11:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:47.479  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:47.479  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:47.479  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:47.479  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:47.479  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:47.479  5501  5548 I jxcore-log: 
,11-03 23:11:47.483  5501  5548 I jxcore-log: 2016-11-03 22:11:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:47.483  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:47.483  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:47.483  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:47.483  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:47.483  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:47.483  5501  5548 I jxcore-log: 
,11-03 23:11:48.513  5501  5548 I jxcore-log: 2016-11-03 22:11:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:48.513  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:48.513  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:48.513  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:48.513  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:48.513  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:48.513  5501  5548 I jxcore-log: 
,11-03 23:11:48.517  5501  5548 I jxcore-log: 2016-11-03 22:11:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:48.517  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:48.517  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:48.517  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:48.517  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:48.517  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:48.517  5501  5548 I jxcore-log: 
,11-03 23:11:49.541  5501  5548 I jxcore-log: 2016-11-03 22:11:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:49.541  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:49.541  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:49.541  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:49.541  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:49.541  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:49.541  5501  5548 I jxcore-log: 
,11-03 23:11:49.546  5501  5548 I jxcore-log: 2016-11-03 22:11:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:49.546  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:49.546  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:49.546  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:49.546  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:49.546  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:49.546  5501  5548 I jxcore-log: 
,11-03 23:11:50.574  5501  5548 I jxcore-log: 2016-11-03 22:11:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:50.574  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:50.574  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:50.574  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:50.574  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:50.574  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:50.574  5501  5548 I jxcore-log: 
,11-03 23:11:50.578  5501  5548 I jxcore-log: 2016-11-03 22:11:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:50.578  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:50.578  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:50.578  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:50.578  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:50.578  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:50.578  5501  5548 I jxcore-log: 
,11-03 23:11:51.606  5501  5548 I jxcore-log: 2016-11-03 22:11:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:51.606  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:51.606  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:51.606  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:51.606  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:51.606  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:51.606  5501  5548 I jxcore-log: 
,11-03 23:11:51.612  5501  5548 I jxcore-log: 2016-11-03 22:11:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:51.612  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:51.612  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:51.612  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:51.612  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:51.612  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:51.612  5501  5548 I jxcore-log: 
,11-03 23:11:52.641  5501  5548 I jxcore-log: 2016-11-03 22:11:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:11:52.641  5501  5548 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:11:52.641  5501  5548 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:11:52.641  5501  5548 I jxcore-log: emit@events.js:82:1
11-03 23:11:52.641  5501  5548 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:11:52.641  5501  5548 I jxcore-log: emit@events.js:82:1'
11-03 23:11:52.641  5501  5548 I jxcore-log: 
,11-03 23:11:52.650  5501  5548 E jxcore  : Error!: error is undefined
11-03 23:11:52.650  5501  5548 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-03 23:11:52.653  5501  5548 I jxcore-log: 2016-11-03 22:11:52 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-03 23:11:52.653  5501  5548 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-03 23:11:52.653  5501  5548 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-03 23:11:52.653  5501  5548 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-03 23:11:52.653  5501  5548 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-03 23:11:52.653  5501  5548 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-03 23:11:52.653  5501  5548 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-03 23:11:52.653  5501  5548 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-03 23:11:52.655  5501  5548 I jxcore-log: 2016-11-03 22:11:52 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-03 23:11:52.655  5501  5548 I jxcore-log: 
,11-03 23:11:52.657  5501  5548 E jxcore-log: TypeError: 
11-03 23:11:52.657  5501  5548 E jxcore-log: error is undefined
11-03 23:11:52.657  5501  5548 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-03 23:11:52.657  5501  5548 E jxcore-log: 
,11-03 23:11:52.727   929  2843 W InputDispatcher: channel '8cd5306 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-03 23:11:52.728   929  2843 E InputDispatcher: channel '8cd5306 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-03 23:11:52.739   929  3732 I WindowState: WIN DEATH: Window{8cd5306 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-03 23:11:52.739   929  3732 W InputDispatcher: Attempted to unregister already unregistered input channel '8cd5306 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,11-03 23:11:52.739   929  3322 D GraphicsStats: Buffer count: 2
11-03 23:11:52.741   929  2853 D WifiService: Client connection lost with reason: 4
,11-03 23:11:52.751   528   528 I Zygote  : Process 5501 exited cleanly (139)
,11-03 23:11:52.755   929  3720 I ActivityManager: Process com.test.thalitest (pid 5501) has died
,11-03 23:11:52.775   929  3720 I ActivityManager: Start proc 5841:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-03 23:11:52.870  5841  5841 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-03 23:11:52.889  5841  5841 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-03 23:11:52.894  5841  5841 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4444-4446)
11-03 23:11:52.894  5841  5841 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 23:11:52.904  5841  5841 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {13378c6}
,11-03 23:11:52.904  5841  5841 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-03 23:11:52.904  5841  5841 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-03 23:11:52.907  5841  5841 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-03 23:11:52.908  5841  5841 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 23:11:52.918  5841  5841 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 23:11:52.925  5841  5841 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-03 23:11:52.925  5841  5841 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 23:11:52.925  5841  5841 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 23:11:52.925  5841  5841 I Adreno  : Build Date                       : 12/06/15
11-03 23:11:52.925  5841  5841 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 23:11:52.925  5841  5841 I Adreno  : Local Branch                     : mybranch17112971
11-03 23:11:52.925  5841  5841 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 23:11:52.925  5841  5841 I Adreno  : Remote Branch                    : NONE
11-03 23:11:52.925  5841  5841 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 23:11:52.957   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@188c699:true
,11-03 23:11:52.969   404   404 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[29827]" dev="sockfs" ino=29827 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 23:11:52.969   404   404 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[29827]" dev="sockfs" ino=29827 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 23:11:52.983  5841  5841 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 23:11:52.991  5841  5841 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 23:11:53.016   728   728 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[36680]" dev="sockfs" ino=36680 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 23:11:53.016   728   728 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[36680]" dev="sockfs" ino=36680 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 23:11:53.019  5841  5877 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 23:11:53.019   939   939 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[29839]" dev="sockfs" ino=29839 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:11:53.019   939   939 W Binder_1: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[29839]" dev="sockfs" ino=29839 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:11:53.023  5841  5864 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-03 23:11:53.065  5841  5877 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 23:11:53.094   929   939 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5501 uid 10077
,11-03 23:11:53.096   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +284ms (total +336ms)
,11-03 23:11:53.093   939   939 W Binder_1: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[37709]" dev="sockfs" ino=37709 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 23:11:53.093   939   939 W Binder_1: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[37709]" dev="sockfs" ino=37709 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:11:53.093  3321  3321 W Binder_5: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[37708]" dev="sockfs" ino=37708 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 23:11:53.093  3321  3321 W Binder_5: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[37708]" dev="sockfs" ino=37708 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:11:53.098  3556  3556 I Keyboard.Facilitator: onFinishInput()
,11-03 23:11:53.102  5841  5841 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5841
,11-03 23:11:53.112  5839  5839 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-03 23:11:53.115  5839  5839 D AndroidRuntime: CheckJNI is OFF
,11-03 23:11:53.136  5839  5839 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-03 23:11:53.159  5839  5839 I Radio-JNI: register_android_hardware_Radio DONE
,11-03 23:11:53.169  5841  5841 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 23:11:53.174  5839  5839 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-03 23:11:53.180   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-03 23:11:53.181   929   942 I ActivityManager: Killing 5841:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-03 23:11:53.212   929  3060 D GraphicsStats: Buffer count: 2
,11-03 23:11:53.213   929   939 I WindowState: WIN DEATH: Window{226f23c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-03 23:11:53.286   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
11-03 23:11:53.286   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-03 23:11:53.287   929   952 I art     : Starting a blocking GC Explicit
,11-03 23:11:53.288   929   942 E ActivityManager: Failure starting process com.test.thalitest
11-03 23:11:53.288   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-03 23:11:53.288   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 23:11:53.288   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-03 23:11:53.288   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-03 23:11:53.288   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-03 23:11:53.288   929   942 I ActivityManager:   Force finishing activity ActivityRecord{cf0eece u0 com.test.thalitest/.MainActivity t68}
,11-03 23:11:53.299   929  3726 W ActivityManager: Spurious death for ProcessRecord{585891a 0:com.test.thalitest/u0a77}, curProc for 5841: null
,11-03 23:11:53.368   929   952 I art     : Explicit concurrent mark sweep GC freed 12694(835KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.685ms total 80.845ms
,11-03 23:11:53.386   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-03 23:11:53.389  5839  5839 I art     : System.exit called, status: 0
11-03 23:11:53.389  5839  5839 I AndroidRuntime: VM exiting with result code 0.
,11-03 23:11:53.398   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-03 23:11:53.405   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-03 23:11:53.411  3556  3556 I Keyboard.Facilitator: resetDictionaries() : en_US
11-03 23:11:53.411  5738  5738 D BluetoothMapAppObserver: onReceive
11-03 23:11:53.411  5738  5738 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-03 23:11:53.412  3935  4047 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-03 23:11:53.422   929  2844 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-03 23:11:53.446  3556  5892 I Keyboard.Facilitator.DecoderInitializer: run()
,11-03 23:11:53.450  3303  5893 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-03 23:11:53.477  3652  3652 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-03 23:11:53.479    17    17 W kworker/2:0: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 23:11:53.483  3556  5892 I Decoder : createOrResetDecoder
,11-03 23:11:53.485  3483  3483 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-03 23:11:53.485  3483  3483 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-03 23:11:53.490   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-03 23:11:53.486    17    17 W kworker/2:0: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 23:11:53.508  3735  5898 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-03 23:11:53.508  3735  5898 D AccountUtils: Clearing selected account for com.test.thalitest
,11-03 23:11:53.539    17    17 W kworker/2:0: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 23:11:53.548   929  3683 I ActivityManager: Start proc 5902:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-03 23:11:53.548  3670  3811 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-03 23:11:53.548  3670  3811 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3670
11-03 23:11:53.548  3670  3811 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-03 23:11:53.548  3670  3811 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-03 23:11:53.548  3670  3811 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-03 23:11:53.548  3670  3811 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-03 23:11:53.548  3670  3811 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-03 23:11:53.548  3670  3811 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-03 23:11:53.548  3670  3811 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-03 23:11:53.548  3670  3811 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-03 23:11:53.548  3670  3811 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 23:11:53.548  3670  3811 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 23:11:53.548  3670  3811 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 23:11:53.548  3670  3811 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-03 23:11:53.551  3483  3483 I ConfigService: onCreate
,11-03 23:11:53.555   929  5913 E DropBoxManagerService: Can't write: system_app_crash
11-03 23:11:53.555   929  5913 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-03 23:11:53.555   929  5913 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 23:11:53.555   929  5913 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 23:11:53.555   929  5913 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 23:11:53.555   929  5913 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 23:11:53.555   929  5913 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 23:11:53.555   929  5913 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 23:11:53.555   929  5913 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 23:11:53.555   929  5913 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 23:11:53.555   929  5913 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 23:11:53.555   929  5913 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 23:11:53.555   929  5913 E DropBoxManagerService: 	... 5 more
,11-03 23:11:53.557  3483  5912 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
11-03 23:11:53.557   929  3322 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-03 23:11:53.567  3670  3811 I Process : Sending signal. PID: 3670 SIG: 9

```
