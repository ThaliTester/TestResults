#### Test 944077483e9c5d2_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-18 19:19:44.684  3689  4237 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
11-18 19:19:44.764  3689  4237 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,11-18 19:19:44.808   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
11-18 19:19:45.220  5560  5560 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-18 19:19:45.225  5560  5560 D AndroidRuntime: CheckJNI is OFF
11-18 19:19:45.253  5560  5560 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-18 19:19:45.286  5560  5560 I Radio-JNI: register_android_hardware_Radio DONE
11-18 19:19:45.302  5560  5560 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-18 19:19:45.314   929  3152 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-18 19:19:45.330  5560  5560 D AndroidRuntime: Shutting down VM
11-18 19:19:45.341  3967  4123 W SearchService: Abort, client detached.
11-18 19:19:45.352  3967  3967 I HotwordDetector: Closing mic
11-18 19:19:45.352  3967  4185 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@4f5d215
11-18 19:19:45.352  3967  4230 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-18 19:19:45.367   929  3833 I ActivityManager: Start proc 5570:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-18 19:19:45.420   513  4235 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-18 19:19:45.421   513  4235 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-18 19:19:45.427   513  4235 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-18 19:19:45.427   513  4235 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-18 19:19:45.428   513  2993 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-18 19:19:45.432  3967  4225 I MicroRecognitionRnrImpl: Detection finished
11-18 19:19:45.433  3967  4202 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-18 19:19:45.471  5570  5570 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-18 19:19:45.498  5570  5570 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-18 19:19:45.557  5570  5570 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 4766-4821)
11-18 19:19:45.557  5570  5570 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-18 19:19:45.588  5570  5570 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3649a2b}
11-18 19:19:45.589  5570  5570 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-18 19:19:45.589  5570  5570 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-18 19:19:45.594  5570  5570 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-18 19:19:45.596  5570  5570 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-18 19:19:45.653  5570  5570 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-18 19:19:45.668  5570  5570 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-18 19:19:45.668  5570  5570 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-18 19:19:45.668  5570  5570 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-18 19:19:45.668  5570  5570 I Adreno  : Build Date                       : 12/06/15
11-18 19:19:45.668  5570  5570 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-18 19:19:45.668  5570  5570 I Adreno  : Local Branch                     : mybranch17112971
11-18 19:19:45.668  5570  5570 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-18 19:19:45.668  5570  5570 I Adreno  : Remote Branch                    : NONE
11-18 19:19:45.668  5570  5570 I Adreno  : Reconstruct Branch               : NOTHING
,11-18 19:19:45.719   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@551f59e:true
,11-18 19:19:45.754   401   401 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[15003]" dev="sockfs" ino=15003 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 19:19:45.754   401   401 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[15003]" dev="sockfs" ino=15003 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 19:19:45.767  5570  5570 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-18 19:19:45.781  5570  5570 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-18 19:19:45.804   746   746 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[30594]" dev="sockfs" ino=30594 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 19:19:45.804   746   746 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30594]" dev="sockfs" ino=30594 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 19:19:45.808  5570  5607 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-18 19:19:45.808  3153  3153 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[15006]" dev="sockfs" ino=15006 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 19:19:45.808  3153  3153 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15006]" dev="sockfs" ino=15006 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-18 19:19:45.811  5570  5594 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-18 19:19:45.832  5570  5607 I OpenGLRenderer: Initialized EGL, version 1.4
,11-18 19:19:45.908  3152  3152 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31720]" dev="sockfs" ino=31720 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 19:19:45.908  3152  3152 W Binder_3: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31720]" dev="sockfs" ino=31720 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 19:19:45.911  3153  3153 W Binder_4: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31719]" dev="sockfs" ino=31719 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 19:19:45.911   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +568ms
11-18 19:19:45.913  3651  3651 I Keyboard.Facilitator: onFinishInput()
11-18 19:19:45.911  3153  3153 W Binder_4: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31719]" dev="sockfs" ino=31719 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 19:19:45.951  5570  5570 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5570
,11-18 19:19:46.042  5570  5570 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-18 19:19:46.170  5570  5609 D jxcore_app_log: JniHelper::setJavaVM(0xf537c000), pthread_self() = -561776336
,11-18 19:19:46.176  5570  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-18 19:19:46.176  5570  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-18 19:19:46.176  5570  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-18 19:19:46.176  5570  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-18 19:19:46.176  5570  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-18 19:19:46.176  5570  5609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecf019 added. We now have 1 listener(s)
,11-18 19:19:46.179  5570  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-18 19:19:46.179  5570  5609 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-18 19:19:46.179  5570  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 19:19:46.180  5570  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-18 19:19:46.182  5570  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@511458c added. We now have 1 listener(s)
11-18 19:19:46.182  5570  5609 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 19:19:46.187   929  2986 D WifiService: New client listening to asynchronous messages
11-18 19:19:46.187  5570  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-18 19:19:46.187  5570  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-18 19:19:46.188  5570  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-18 19:19:46.188  5570  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-18 19:19:46.188  5570  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-18 19:19:46.188  5570  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-18 19:19:46.188  5570  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-18 19:19:46.189  5570  5609 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-18 19:19:46.302  5570  5570 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-18 19:19:46.584  5570  5618 W jxcore-log: Initializing JXcore engine
11-18 19:19:46.584  5570  5618 W jxcore-log: JXcore engine is ready
,11-18 19:19:46.608  5618  5618 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12461 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-18 19:19:46.608  5618  5618 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[16416]" dev="sockfs" ino=16416 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-18 19:19:46.608  5618  5618 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-18 19:19:46.608  5618  5618 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31700]" dev="sockfs" ino=31700 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-18 19:19:46.616  5570  5618 W jxcore-log: Starting JXcore engine
,11-18 19:19:46.666  5570  5618 W jxcore-log: Platform android
11-18 19:19:46.666  5570  5618 W jxcore-log: 
,11-18 19:19:46.666  5570  5618 W jxcore-log: Process ARCH arm
11-18 19:19:46.666  5570  5618 W jxcore-log: 
,11-18 19:19:46.812  5570  5618 I jxcore-log: JXcore Cordova bridge is ready!
11-18 19:19:46.812  5570  5618 I jxcore-log: 
,11-18 19:19:46.812  5570  5618 W jxcore-log: JXcore engine is started
,11-18 19:19:46.824  5570  5609 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-18 19:19:46.831  5570  5570 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-18 19:19:48.814  3577  3577 I ConfigService: onDestroy
,11-18 19:19:50.353   929  3416 I ActivityManager: Killing 5087:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-18 19:19:55.455  3967  5620 W CronetSyncConnectionRcs: Upload content type not set.
,11-18 19:19:56.382  5570  5618 I jxcore-log: 2016-11-18 18:19:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-18 19:19:56.382  5570  5618 I jxcore-log: 
,11-18 19:19:56.384  5570  5618 I jxcore-log: 2016-11-18 18:19:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-18 19:19:56.384  5570  5618 I jxcore-log: 
,11-18 19:19:56.389  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-18 19:19:56.389  5570  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 19:19:56.389  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:19:56.389  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 19:19:56.389  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 19:19:56.389  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 19:19:56.389  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 19:19:56.389  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 19:19:56.389  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 19:19:56.389  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 19:19:56.391  5570  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-18 19:19:56.393  5570  5618 I jxcore-log: 2016-11-18 18:19:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-18 19:19:56.393  5570  5618 I jxcore-log: 
11-18 19:19:56.395  5570  5618 I jxcore-log: 2016-11-18 18:19:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-18 19:19:56.395  5570  5618 I jxcore-log: 
,11-18 19:19:56.641  5570  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-18 19:19:56.641  5570  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc38902 added. We now have 2 listener(s)
11-18 19:19:56.642  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:19:56.642  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 19:19:56.642  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 19:19:56.642  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 19:19:56.642  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98c2213 added. We now have 2 listener(s)
11-18 19:19:56.642  5570  5618 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 19:19:56.643  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 19:19:56.644  5570  5618 D ExecuteNativeTests: Running unit tests
,11-18 19:19:56.645  5570  5618 D BluetoothAdapter: enable(): BT is already enabled..!
11-18 19:19:56.645   929  3153 D WifiService: setWifiEnabled: true pid=5570, uid=10077
11-18 19:19:56.645   929  3153 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 19:19:58.521  4762  4825 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-18 19:19:58.522  4762  4762 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-18 19:20:01.819   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-18 19:20:04.807   929   939 I ActivityManager: Killing 5256:com.android.settings/1000 (adj 15): empty #17
,11-18 19:20:04.810   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:04.837   929   939 I ActivityManager: Killing 5217:org.codeaurora.ims/1001 (adj 15): empty #18
,11-18 19:20:05.812   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:06.653  5570  5618 I com.test.thalitest.ThaliTestRunner: Running UT
,11-18 19:20:06.720  5570  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-18 19:20:06.720  5570  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7132644 added. We now have 3 listener(s)
11-18 19:20:06.721  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-18 19:20:06.721  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-18 19:20:06.721  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 19:20:06.721  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-18 19:20:06.721  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@568332d added. We now have 3 listener(s)
11-18 19:20:06.721  5570  5618 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 19:20:06.722  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 19:20:06.727  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-18 19:20:06.728  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 19:20:06.728  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 19:20:06.728  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:20:06.728  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:20:06.729  5570  5618 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-18 19:20:06.729  5570  5618 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-18 19:20:06.729  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 19:20:06.729  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:20:06.729  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:20:06.729  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-18 19:20:06.731  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-18 19:20:06.731  5570  5618 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-18 19:20:06.733  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-18 19:20:06.735  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,11-18 19:20:06.735  5570  5618 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-18 19:20:06.738  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:20:06.738  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 19:20:06.744  5570  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 19:20:06.744  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:20:06.744  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 19:20:06.744  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 19:20:06.744  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 19:20:06.744  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 19:20:06.744  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 19:20:06.744  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 19:20:06.744  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 19:20:06.745  5570  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-18 19:20:06.745  5570  5618 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-18 19:20:06.745  5570  5618 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,11-18 19:20:06.745  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-18 19:20:06.745  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.745  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:06.745  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.745  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:20:06.745  5570  5618 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 19:20:06.746  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 19:20:06.746  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:20:06.746  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 19:20:06.747  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 19:20:06.747  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 19:20:06.747  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 19:20:06.747  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 19:20:06.747  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 19:20:06.747  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:20:06.747  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-18 19:20:06.749  5570  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 19:20:06.752  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 19:20:06.752  5570  5618 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 19:20:06.752  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 19:20:06.754  5570  5625 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:20:06.755  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 19:20:06.758  4794  4794 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[21451]" dev="sockfs" ino=21451 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 19:20:06.758  4794  4794 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[21451]" dev="sockfs" ino=21451 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:20:06.760  5570  5625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 19:20:06.762  5570  5570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 19:20:06.763  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.763  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 19:20:06.763  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 19:20:06.764  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-18 19:20:06.764  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-18 19:20:06.764  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-18 19:20:06.765  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.766  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.766  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-18 19:20:06.766  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 19:20:06.766  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-18 19:20:06.766  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-18 19:20:06.766  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:06.766  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:06.766  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.766  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 19:20:06.766  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:06.767  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.767  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.767  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.767  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:06.770  4597  4610 D BtGatt.GattService: registerClient() - UUID=cf8db8f6-4d14-47f2-8b90-f00872008a02
,11-18 19:20:06.771  4597  4659 D BtGatt.GattService: onClientRegistered() - UUID=cf8db8f6-4d14-47f2-8b90-f00872008a02, clientIf=5
,11-18 19:20:06.772  5570  5581 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 19:20:06.775  4597  4661 D BtGatt.AdvertiseManager: message : 0
,11-18 19:20:06.778  4597  4661 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 19:20:06.795  4597  4659 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 19:20:06.803  4597  4659 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 19:20:06.805  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:06.805  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.805  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 19:20:06.805  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.805  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.805  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:06.805  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.805  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.805  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 19:20:06.806  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 19:20:06.806  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.806  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.806  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:06.806  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:06.807  5570  5618 I io.jxcore.node.ConnectionHelper: start: OK
11-18 19:20:06.807  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:20:06.808  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 19:20:06.808  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:06.808  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 19:20:06.808  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-18 19:20:06.809  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:06.809  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:06.809  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:06.810  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-18 19:20:06.810  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-18 19:20:06.810  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:20:06.810  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 19:20:06.810  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 19:20:06.810  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:20:06.813   536   536 I ServiceManager: Waiting for service AtCmdFwd...
11-18 19:20:06.814  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:20:06.814  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 19:20:06.815  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:06.815  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:06.815  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:06.815  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 19:20:07.310  5570  5618 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-18 19:20:07.310  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-18 19:20:07.310  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-18 19:20:07.311  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-18 19:20:07.311  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-18 19:20:07.311  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-18 19:20:07.311  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-18 19:20:07.311  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-18 19:20:07.311  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-18 19:20:07.311  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-18 19:20:07.311  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-18 19:20:07.311  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-18 19:20:07.311  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-18 19:20:07.311  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-18 19:20:07.311  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-18 19:20:07.312  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-18 19:20:07.312  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-18 19:20:07.312  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-18 19:20:07.312  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-18 19:20:07.312  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-18 19:20:07.312  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-18 19:20:07.312  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-18 19:20:07.313  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-18 19:20:07.313  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-18 19:20:07.313  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-18 19:20:07.313  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-18 19:20:07.313  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-18 19:20:07.313  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-18 19:20:07.313  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-18 19:20:07.313  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-18 19:20:07.313  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-18 19:20:07.313  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-18 19:20:07.313  5570  5618 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-18 19:20:07.314  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 19:20:07.314  5570  5618 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 19:20:07.314  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 19:20:07.314  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 19:20:07.314  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 19:20:07.315  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 19:20:07.315  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 19:20:07.315  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 19:20:07.315  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-18 19:20:07.315  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 19:20:07.315  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 19:20:07.315  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 19:20:07.316  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.316  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.316  5570  5625 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 19:20:07.316  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:07.316  5570  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 19:20:07.316  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.316  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 19:20:07.316  5570  5625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 19:20:07.318  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:07.318  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-18 19:20:07.319  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:07.319  5570  5618 D BluetoothLeScanner: could not find callback wrapper
11-18 19:20:07.320  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 19:20:07.320  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.320  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.320  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.320  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 19:20:07.320  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.322  4597  4661 D BtGatt.AdvertiseManager: message : 1
11-18 19:20:07.323  4597  4661 D BtGatt.AdvertiseManager: stop advertise for client 5
11-18 19:20:07.336  4597  4659 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 19:20:07.336  4597  4659 D BtGatt.GattService: Client app is not null!
11-18 19:20:07.337  4597  4794 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 19:20:07.338  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 19:20:07.338  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.338  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 19:20:07.339  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.339  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.339  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.339  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-18 19:20:07.339  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 19:20:07.341  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-18 19:20:07.341  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.343  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.343  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:20:07.343  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.343  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.344  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 19:20:07.344  5570  5570 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 19:20:07.345  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 19:20:07.345  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 19:20:07.345  5570  5618 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 19:20:07.345  5570  5618 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 19:20:07.345  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:20:07.345  5570  5618 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-18 19:20:07.346  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-18 19:20:07.346  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 19:20:07.346  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.346  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:20:07.346  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:07.346  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:07.346  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.346  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.346  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:20:07.346  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 19:20:07.347  5570  5618 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 19:20:07.347  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 19:20:07.347  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 19:20:07.347  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.347  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:20:07.347  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.347  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 19:20:07.351  4612  4612 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32378]" dev="sockfs" ino=32378 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:20:07.351  4612  4612 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32378]" dev="sockfs" ino=32378 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:20:07.347  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.349  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 19:20:07.349  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 19:20:07.350  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 19:20:07.350  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 19:20:07.350  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 19:20:07.350  5570  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 19:20:07.351  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.351  5570  5628 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:20:07.351  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.351  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.351  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.352  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:20:07.352  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 19:20:07.352  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 19:20:07.352  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:20:07.352  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 19:20:07.355  5570  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 19:20:07.358  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 19:20:07.359  5570  5618 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 19:20:07.359  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 19:20:07.365  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.365  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 19:20:07.366  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:20:07.366  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 19:20:07.366  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-18 19:20:07.369  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.369  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.369  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 19:20:07.369  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 19:20:07.370  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:20:07.370  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-18 19:20:07.370  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:07.370  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:07.370  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.370  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 19:20:07.370  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:07.371  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.371  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.371  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.372  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:07.374  4597  4612 D BtGatt.GattService: registerClient() - UUID=adc18f1c-dff4-4ddb-8acf-15fba8a4f6f1
11-18 19:20:07.375  4597  4659 D BtGatt.GattService: onClientRegistered() - UUID=adc18f1c-dff4-4ddb-8acf-15fba8a4f6f1, clientIf=5
11-18 19:20:07.375  5570  5580 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 19:20:07.377  4597  4661 D BtGatt.AdvertiseManager: message : 0
11-18 19:20:07.378  4597  4661 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 19:20:07.389  4597  4659 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-18 19:20:07.396  4597  4659 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-18 19:20:07.397  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.397  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.397  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 19:20:07.397  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.397  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.397  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.397  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.397  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.397  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 19:20:07.398  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 19:20:07.399  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.400  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.400  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.400  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.400  5570  5618 I io.jxcore.node.ConnectionHelper: start: OK
11-18 19:20:07.400  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:20:07.401  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.401  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:07.401  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 19:20:07.401  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.401  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.401  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:07.401  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.401  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 19:20:07.401  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 19:20:07.401  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.401  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.401  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 19:20:07.401  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.404  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.404  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 19:20:07.404  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.404  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.404  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.404  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 19:20:07.814   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:07.904  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-18 19:20:07.904  5570  5618 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 19:20:07.904  5570  5618 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 19:20:07.905  5570  5618 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-18 19:20:07.905  5570  5618 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-18 19:20:07.905  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-18 19:20:07.905  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 19:20:07.905  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.906  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:07.906  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.908  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 19:20:07.908  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 19:20:07.908  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 19:20:07.908  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-18 19:20:07.908  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 19:20:07.908  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 19:20:07.908  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 19:20:07.908  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 19:20:07.908  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 19:20:07.908  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:07.908  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-18 19:20:07.909  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:07.912  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.913  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.918  4597  4661 D BtGatt.AdvertiseManager: message : 1
,11-18 19:20:07.919  4597  4661 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 19:20:07.927  4597  4659 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-18 19:20:07.928  4597  4659 D BtGatt.GattService: Client app is not null!
11-18 19:20:07.928  4597  4794 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 19:20:07.929  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 19:20:07.929  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:07.929  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 19:20:07.929  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.929  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.930  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.930  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 19:20:07.930  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.930  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.930  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.930  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-18 19:20:07.930  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 19:20:07.930  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:20:07.930  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-18 19:20:07.930  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:07.931  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:07.931  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.931  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 19:20:07.931  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:07.931  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.931  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.931  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.932  5570  5618 D BluetoothAdapter: STATE_ON
,11-18 19:20:07.936  4597  4612 D BtGatt.GattService: registerClient() - UUID=b3eb29cc-366f-43bc-b9d5-7f2bf57b84e9
11-18 19:20:07.936  4597  4659 D BtGatt.GattService: onClientRegistered() - UUID=b3eb29cc-366f-43bc-b9d5-7f2bf57b84e9, clientIf=5
,11-18 19:20:07.937  5570  5581 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 19:20:07.938  4597  4661 D BtGatt.AdvertiseManager: message : 0
11-18 19:20:07.940  4597  4661 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 19:20:07.954  4597  4659 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 19:20:07.961  4597  4659 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 19:20:07.961  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.962  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:07.962  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 19:20:07.962  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.962  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.962  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:07.962  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.962  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.963  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.963  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:20:07.963  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:07.963  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 19:20:07.963  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 19:20:07.963  5570  5618 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-18 19:20:07.964  5570  5618 I io.jxcore.node.ConnectionHelper: start: OK
11-18 19:20:07.964  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.964  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-18 19:20:07.964  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 19:20:07.964  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.964  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.964  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:07.965  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.965  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-18 19:20:07.965  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 19:20:07.965  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.965  5570  5618 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-18 19:20:07.965  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.965  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 19:20:07.965  5570  5618 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 19:20:07.965  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 19:20:07.965  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 19:20:07.965  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 19:20:07.966  5570  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 19:20:07.966  5570  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 19:20:07.966  5570  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 19:20:07.966  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-18 19:20:07.966  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 19:20:07.966  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 19:20:07.966  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 19:20:07.966  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 19:20:07.967  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:20:07.967  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-18 19:20:07.967  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 19:20:07.967  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 19:20:07.967  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 19:20:07.967  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.968  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.968  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:07.968  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.969  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:07.969  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 19:20:07.970  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:07.970  5570  5618 D BluetoothLeScanner: could not find callback wrapper
11-18 19:20:07.970  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-18 19:20:07.970  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.971  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.971  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.971  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-18 19:20:07.971  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:07.973  4597  4661 D BtGatt.AdvertiseManager: message : 1
,11-18 19:20:07.973  4597  4661 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 19:20:07.980  4597  4659 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-18 19:20:07.980  4597  4659 D BtGatt.GattService: Client app is not null!
,11-18 19:20:07.981  4597  4612 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 19:20:07.982  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 19:20:07.982  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.982  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-18 19:20:07.982  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.982  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.982  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.982  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 19:20:07.982  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 19:20:07.983  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-18 19:20:07.983  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.984  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.985  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:20:07.985  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.985  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:07.985  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 19:20:07.985  5570  5570 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 19:20:07.985  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 19:20:07.985  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:20:07.985  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:07.985  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.985  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 19:20:07.986  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 19:20:07.986  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 19:20:07.986  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.986  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-18 19:20:07.986  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.988  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-18 19:20:07.988  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.988  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.989  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:07.989  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 19:20:07.990  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-18 19:20:07.991  5570  5618 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-18 19:20:07.992  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-18 19:20:07.992  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-18 19:20:07.993  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,11-18 19:20:07.993  5570  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-18 19:20:07.994  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-18 19:20:07.994  5570  5618 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-18 19:20:07.995  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-18 19:20:07.995  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 19:20:07.996  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 19:20:07.996  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:20:07.996  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:20:07.996  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 19:20:07.996  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-18 19:20:07.996  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:20:07.996  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:20:07.996  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 19:20:07.996  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 19:20:07.996  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:20:07.996  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 19:20:07.997  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-18 19:20:07.997  5570  5618 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-18 19:20:07.998  5570  5618 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-18 19:20:08.001  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-18 19:20:08.001  5570  5618 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-18 19:20:08.003  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,11-18 19:20:08.003  5570  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-18 19:20:08.004  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-18 19:20:08.004  5570  5618 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-18 19:20:08.004  5570  5618 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-18 19:20:08.004  5570  5618 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-18 19:20:08.004  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 19:20:08.004  5570  5618 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-18 19:20:08.004  5570  5618 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 19:20:08.004  5570  5618 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-18 19:20:08.005  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 19:20:08.005  5570  5618 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-18 19:20:08.005  5570  5618 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 19:20:08.005  5570  5618 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-18 19:20:08.005  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 19:20:08.005  5570  5618 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-18 19:20:08.006  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-18 19:20:08.006  5570  5618 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 19:20:08.006  5570  5618 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 19:20:08.006  5570  5618 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-18 19:20:08.006  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-18 19:20:08.006  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.006  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.006  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.006  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:20:08.006  5570  5618 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 19:20:08.006  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 19:20:08.006  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:20:08.007  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 19:20:08.008  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 19:20:08.008  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 19:20:08.008  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 19:20:08.008  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 19:20:08.008  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 19:20:08.008  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:20:08.008  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 19:20:08.008  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 19:20:08.008  5570  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 19:20:08.010  5570  5632 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:20:08.008  4794  4794 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32801]" dev="sockfs" ino=32801 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:20:08.008  4794  4794 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32801]" dev="sockfs" ino=32801 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:20:08.012  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 19:20:08.012  5570  5618 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 19:20:08.013  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 19:20:08.013  5570  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 19:20:08.016  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.016  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 19:20:08.017  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:20:08.017  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 19:20:08.017  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
,11-18 19:20:08.020  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:08.020  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.020  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 19:20:08.020  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 19:20:08.020  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:20:08.020  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-18 19:20:08.020  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:08.020  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:08.020  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.020  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 19:20:08.020  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 19:20:08.020  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.021  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.021  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.021  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:08.024  4597  4610 D BtGatt.GattService: registerClient() - UUID=0c606446-7026-4456-81ba-f231fa6022e6
11-18 19:20:08.024  4597  4659 D BtGatt.GattService: onClientRegistered() - UUID=0c606446-7026-4456-81ba-f231fa6022e6, clientIf=5
,11-18 19:20:08.025  5570  5581 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 19:20:08.026  4597  4661 D BtGatt.AdvertiseManager: message : 0
,11-18 19:20:08.028  4597  4661 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 19:20:08.038  4597  4659 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 19:20:08.043  4597  4659 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 19:20:08.044  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.044  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.044  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-18 19:20:08.044  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.044  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.044  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.044  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.044  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.044  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-18 19:20:08.045  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-18 19:20:08.046  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.047  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:08.047  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.047  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.047  5570  5618 I io.jxcore.node.ConnectionHelper: start: OK
11-18 19:20:08.047  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:20:08.047  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-18 19:20:08.047  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-18 19:20:08.047  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 19:20:08.047  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.047  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.048  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:08.048  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.048  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 19:20:08.048  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 19:20:08.048  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 19:20:08.048  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.048  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 19:20:08.048  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.051  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.051  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 19:20:08.051  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.051  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.051  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.051  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 19:20:08.548  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-18 19:20:08.548  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 19:20:08.548  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 19:20:08.548  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 19:20:08.549  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 19:20:08.549  5570  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 19:20:08.549  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-18 19:20:08.549  5570  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 19:20:08.549  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-18 19:20:08.549  5570  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 19:20:08.550  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-18 19:20:08.550  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-18 19:20:08.550  5570  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7132644 removed from the list
,11-18 19:20:08.550  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 19:20:08.550  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 19:20:08.550  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-18 19:20:08.550  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 19:20:08.550  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 19:20:08.550  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-18 19:20:08.551  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.551  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.551  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.551  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.554  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:08.554  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 19:20:08.556  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:08.556  5570  5618 D BluetoothLeScanner: could not find callback wrapper
11-18 19:20:08.557  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 19:20:08.557  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:08.557  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.557  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.557  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 19:20:08.557  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.559  4597  4661 D BtGatt.AdvertiseManager: message : 1
,11-18 19:20:08.560  4597  4661 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 19:20:08.573  4597  4659 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 19:20:08.573  4597  4659 D BtGatt.GattService: Client app is not null!
11-18 19:20:08.576  4597  4612 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 19:20:08.576  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 19:20:08.577  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.577  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 19:20:08.577  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.577  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.577  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.577  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 19:20:08.577  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 19:20:08.579  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 19:20:08.579  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:08.581  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.581  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:20:08.581  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.581  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:08.581  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@568332d removed from the list
11-18 19:20:08.581  5570  5618 D io.jxcore.node.ConnectivityMonitor: stop
,11-18 19:20:08.581  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:20:08.581  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-18 19:20:08.582  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 19:20:08.582  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:20:08.582  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:08.582  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 19:20:08.583  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 19:20:08.583  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 19:20:08.583  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 19:20:08.583  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.583  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 19:20:08.583  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.585  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-18 19:20:08.586  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.586  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.586  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:08.586  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 19:20:08.815   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:09.087  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 19:20:09.815   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-18 19:20:13.586  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-18 19:20:13.589  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-18 19:20:13.589  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 19:20:13.590  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 19:20:13.596  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 19:20:13.597  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-18 19:20:13.597  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 19:20:13.597  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 19:20:13.598  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 19:20:13.598  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 19:20:13.598  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-18 19:20:13.598  5570  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 19:20:13.599  5570  5633 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:20:13.600  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-18 19:20:13.601  4610  4610 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32809]" dev="sockfs" ino=32809 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 19:20:13.601  5570  5618 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-18 19:20:13.602  5570  5618 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-18 19:20:13.602  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 19:20:13.602  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:20:13.603  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 19:20:13.604  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-18 19:20:13.604  4610  4610 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32809]" dev="sockfs" ino=32809 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:20:13.606  5570  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 19:20:13.609  5570  5618 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-18 19:20:13.609  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-18 19:20:13.610  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 19:20:13.610  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-18 19:20:13.610  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 19:20:13.610  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 19:20:13.610  5570  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 19:20:13.610  5570  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 19:20:13.610  5570  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 19:20:13.610  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-18 19:20:13.611  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:20:13.611  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 19:20:13.611  5570  5618 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7132644 not in the list
11-18 19:20:13.611  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-18 19:20:13.611  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 19:20:13.611  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 19:20:13.611  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:20:13.611  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-18 19:20:13.611  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 19:20:13.612  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:13.613  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:13.613  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:20:13.613  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:13.614  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:13.614  5570  5618 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@568332d not in the list
11-18 19:20:13.614  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:20:13.614  5570  5618 D io.jxcore.node.ConnectivityMonitor: stop
11-18 19:20:13.614  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 19:20:13.614  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:20:13.615  5570  5618 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-18 19:20:13.616  5570  5618 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-18 19:20:13.616  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-18 19:20:13.617  5570  5618 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-18 19:20:13.617  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 19:20:13.617  5570  5618 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-18 19:20:13.617  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-18 19:20:13.618  5570  5618 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-18 19:20:13.618  5570  5618 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-18 19:20:13.620  5570  5618 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-18 19:20:13.620  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-18 19:20:13.620  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-18 19:20:13.621  5570  5618 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-18 19:20:13.621  5570  5618 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-18 19:20:13.621  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-18 19:20:13.621  5570  5618 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-18 19:20:13.621  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-18 19:20:13.621  5570  5618 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-18 19:20:13.621  5570  5618 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-18 19:20:13.622  5570  5618 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-18 19:20:13.623  5570  5618 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-18 19:20:13.623  5570  5618 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-18 19:20:13.623  5570  5618 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-18 19:20:13.624  5570  5618 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-18 19:20:13.624  5570  5618 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-18 19:20:13.624  5570  5618 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-18 19:20:13.624  5570  5618 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-18 19:20:13.625  5570  5618 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-18 19:20:13.625  5570  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 19:20:13.625  5570  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5a71e3 added. We now have 3 listener(s)
11-18 19:20:13.628  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:20:13.628  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 19:20:13.628  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 19:20:13.628  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 19:20:13.628  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c7d7e0 added. We now have 3 listener(s)
11-18 19:20:13.628  5570  5618 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 19:20:13.629  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 19:20:13.632  5570  5618 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 19:20:13.632   929  3833 D WifiService: setWifiEnabled: true pid=5570, uid=10077
11-18 19:20:13.632   929  3833 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 19:20:13.634  5570  5618 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-18 19:20:13.637  5570  5618 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-18 19:20:13.638  5570  5618 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-18 19:20:13.641  5570  5618 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-18 19:20:13.641  5570  5618 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-18 19:20:13.647  4597  4655 D BluetoothAdapterState: Current state: ON, message: 23
,11-18 19:20:13.648  4597  4655 D BluetoothAdapterProperties: Setting state to 13
11-18 19:20:13.648  4597  4655 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-18 19:20:13.648  5570  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 19:20:13.648  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:20:13.648  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 19:20:13.648  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 19:20:13.648  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 19:20:13.648  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 19:20:13.648  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 19:20:13.648  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 19:20:13.648  5570  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 19:20:13.648  4597  4655 D BluetoothAdapterProperties: onBluetoothDisable()
11-18 19:20:13.649  4597  4655 I BluetoothAdapterState: Entering PendingCommandState
11-18 19:20:13.649  5570  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 19:20:13.650  5570  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 19:20:13.651  4597  4597 D BluetoothMapService: onReceive
11-18 19:20:13.651  4597  4597 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-18 19:20:13.652  4597  4597 D BluetoothMapService: STATE_TURNING_OFF
,11-18 19:20:13.652  4597  4597 D BluetoothMapService: MAP Service closeService in
,11-18 19:20:13.652  4597  4597 D BluetoothMapMasInstance0: MAP Service shutdown
11-18 19:20:13.652  4597  4597 D ObexServerSockets0: shutdown(block = true)
11-18 19:20:13.653  4597  4804 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-18 19:20:13.654  4597  4597 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-18 19:20:13.654  4597  4597 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-18 19:20:13.654  4597  4792 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-18 19:20:13.654  4597  4805 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-18 19:20:13.656  4597  4597 I BtOppRfcommListener: stopping Accept Thread
11-18 19:20:13.656  4597  5304 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-18 19:20:13.656  4597  5304 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-18 19:20:13.669   929   942 I ActivityManager: Start proc 5636:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-18 19:20:13.672  4597  4659 D BluetoothAdapterProperties: Scan Mode:20
11-18 19:20:13.672  4597  4655 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-18 19:20:13.676  4597  4597 D HeadsetService: Received stop request...Stopping profile...
,11-18 19:20:13.679  3771  3797 D BluetoothHeadset: Proxy object disconnected
11-18 19:20:13.679   929   929 D BluetoothHeadset: Proxy object disconnected
,11-18 19:20:13.680  3126  3851 D BluetoothHeadset: Proxy object disconnected
11-18 19:20:13.680  4597  4597 D A2dpService: Received stop request...Stopping profile...
11-18 19:20:13.680  3126  3126 D HeadsetProfile: Bluetooth service disconnected
,11-18 19:20:13.680  4597  4797 D A2dpStateMachine: Exit Disconnected: -1
11-18 19:20:13.681   929   929 D BluetoothHeadset: Proxy object disconnected
11-18 19:20:13.682   929   929 D BluetoothHeadset: Proxy object disconnected
,11-18 19:20:13.685   929   929 D BluetoothA2dp: Proxy object disconnected
,11-18 19:20:13.685  3126  3126 D BluetoothA2dp: Proxy object disconnected
,11-18 19:20:13.686  4597  4597 D HidService: Received stop request...Stopping profile...
,11-18 19:20:13.686  4597  4597 D HidService: Stopping Bluetooth HidService
11-18 19:20:13.687  3126  3126 D BluetoothInputDevice: Proxy object disconnected
11-18 19:20:13.687  4597  4597 V BluetoothAdapterState: isTurningOff()=true
11-18 19:20:13.687  3126  3126 D HidProfile: Bluetooth service disconnected
11-18 19:20:13.687  4597  4597 V BluetoothAdapterState: isTurningOn()=false
11-18 19:20:13.687  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:13.687  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:13.687  4597  4597 D HealthService: Received stop request...Stopping profile...
11-18 19:20:13.690  4597  4597 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-18 19:20:13.690  4597  4597 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-18 19:20:13.690  4597  4659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-18 19:20:13.690  4597  4787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 19:20:13.690  4597  4787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 19:20:13.690  4597  4787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 19:20:13.690  4597  4659 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-18 19:20:13.691  4597  4597 D PanService: Received stop request...Stopping profile...
11-18 19:20:13.692  3126  3126 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-18 19:20:13.692  3126  3126 D PanProfile: Bluetooth service disconnected
11-18 19:20:13.692  4597  4597 D BluetoothMapService: Received stop request...Stopping profile...
,11-18 19:20:13.692  4597  4597 D BluetoothMapService: stop()
11-18 19:20:13.693  4597  4597 D BluetoothMapAppObserver: deinitObservers()
11-18 19:20:13.693  4597  4597 D BluetoothMapAppObserver: removeReceiver()
,11-18 19:20:13.695  3126  3126 D BluetoothMap: Proxy object disconnected
11-18 19:20:13.695  3126  3126 D MapProfile: Bluetooth service disconnected
11-18 19:20:13.695  4597  4597 D SapService: Received stop request...Stopping profile...
11-18 19:20:13.696  4597  4597 V SapService: stop()
11-18 19:20:13.698  4597  4597 V BluetoothAdapterState: isTurningOff()=true
11-18 19:20:13.698  4597  4597 V BluetoothAdapterState: isTurningOn()=false
11-18 19:20:13.698  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:13.699  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:13.701  4597  4597 V BluetoothAdapterState: isTurningOff()=true
11-18 19:20:13.702  4597  4659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-18 19:20:13.702  4597  4787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 19:20:13.702  4597  4787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 19:20:13.702  4597  4787 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 19:20:13.702  4597  4787 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-18 19:20:13.702  4597  4787 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 19:20:13.702  4597  4787 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-18 19:20:13.701  4597  4597 V BluetoothAdapterState: isTurningOn()=false
11-18 19:20:13.702  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:13.702  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:13.703  4597  4597 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-18 19:20:13.703  4597  4659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-18 19:20:13.703  4597  4597 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-18 19:20:13.704  4597  4597 V BluetoothAdapterState: isTurningOff()=true
11-18 19:20:13.704  4597  4597 V BluetoothAdapterState: isTurningOn()=false
11-18 19:20:13.704  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:13.704  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:13.704  4597  4597 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-18 19:20:13.704  4597  4659 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-18 19:20:13.705  4597  4597 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-18 19:20:13.705  4597  4597 V BluetoothAdapterState: isTurningOff()=true
11-18 19:20:13.705  4597  4597 V BluetoothAdapterState: isTurningOn()=false
11-18 19:20:13.705  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:13.705  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:13.706  4597  4597 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-18 19:20:13.706  4597  4597 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-18 19:20:13.707  4597  4597 D BluetoothMapService: MAP Service closeService in
11-18 19:20:13.707  4597  4597 V BluetoothAdapterState: isTurningOff()=true
11-18 19:20:13.707  4597  4597 V BluetoothAdapterState: isTurningOn()=false
,11-18 19:20:13.707  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:13.707  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:13.707  4597  4597 D BluetoothMapService: cleanup()
11-18 19:20:13.707  4597  4597 D BluetoothMapService: MAP Service closeService in
11-18 19:20:13.708  4597  4597 V BluetoothAdapterState: isTurningOff()=true
11-18 19:20:13.708  4597  4597 V BluetoothAdapterState: isTurningOn()=false
11-18 19:20:13.708  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:13.708  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:13.708  4597  4655 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-18 19:20:13.708  4597  4655 D BluetoothAdapterProperties: Setting state to 15
11-18 19:20:13.708  4597  4655 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-18 19:20:13.709   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 19:20:13.709  4597  4655 I BluetoothAdapterState: Entering BleOnState
11-18 19:20:13.709   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 19:20:13.709  3126  3141 D BluetoothPan: onBluetoothStateChange on: false
,11-18 19:20:13.710  3126  3138 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-18 19:20:13.711  3126  3851 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 19:20:13.711  3771  3992 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 19:20:13.711  3126  3141 D BluetoothPbap: onBluetoothStateChange: up=false
,11-18 19:20:13.715   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-18 19:20:13.715  3126  3138 D BluetoothMap: onBluetoothStateChange: up=false
11-18 19:20:13.716   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 19:20:13.716  3126  3851 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 19:20:13.717  4597  4655 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-18 19:20:13.717  4597  4655 D BluetoothAdapterProperties: Setting state to 16
11-18 19:20:13.717  4597  4655 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-18 19:20:13.718  4597  4655 D BluetoothAdapterProperties: onBleDisable
,11-18 19:20:13.719  4597  4655 I BluetoothAdapterState: Entering PendingCommandState
,11-18 19:20:13.719  4597  4656 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-18 19:20:13.719  4597  4659 D BluetoothAdapterProperties: Scan Mode:20
11-18 19:20:13.723  4597  4787 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-18 19:20:13.723  4597  4787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-18 19:20:13.729  5636  5636 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-18 19:20:13.743  5636  5636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 19:20:13.748   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30f1512:true
,11-18 19:20:13.752  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 19:20:13.767  5636  5636 D LocalBluetoothProfileManager: Adding local MAP profile
,11-18 19:20:13.769  5636  5636 D BluetoothMap: Create BluetoothMap proxy object
,11-18 19:20:13.775  5636  5636 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-18 19:20:13.782  5636  5636 D DockEventReceiver: finishStartingService: stopping service
,11-18 19:20:13.784  5636  5636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 19:20:13.789  5636  5636 D DockEventReceiver: finishStartingService: stopping service
,11-18 19:20:13.789  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 19:20:13.791   929  3811 I ActivityManager: Killing 5233:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-18 19:20:13.929  4597  4659 I bt_hci  : shut_down
,11-18 19:20:13.934  4597  4663 D bt_hwcfg: hw_epilog_process
,11-18 19:20:13.934  4597  4663 I bt_vendor: low_power_mode_cb
,11-18 19:20:13.936  4597  4663 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-18 19:20:13.936  4597  4663 I bt_vendor: epilog_cb
11-18 19:20:13.936  4597  4663 I bt_hci  : epilog_finished_callback
,11-18 19:20:13.940  4597  4659 I bt_hci_h4: hal_close
,11-18 19:20:13.940  4597  4659 I bt_userial_vendor: device fd = 54 close
,11-18 19:20:14.053  4597  4656 D bt_stack_manager: event_shut_down_stack finished.
,11-18 19:20:14.054  4597  4655 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-18 19:20:14.058  4597  4655 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-18 19:20:14.059  4597  4597 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-18 19:20:14.060  4597  4597 D BtGatt.GattService: Received stop request...Stopping profile...
11-18 19:20:14.060  4597  4597 D BtGatt.GattService: stop()
11-18 19:20:14.060  4597  4597 D BtGatt.AdvertiseManager: advertise clients cleared
,11-18 19:20:14.063  4597  4597 V BluetoothAdapterState: isTurningOff()=false
,11-18 19:20:14.063  4597  4597 V BluetoothAdapterState: isTurningOn()=false
,11-18 19:20:14.063  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 19:20:14.063  4597  4597 V BluetoothAdapterState: isBleTurningOff()=true
11-18 19:20:14.064  4597  4655 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-18 19:20:14.064  4597  4655 D BluetoothAdapterProperties: Setting state to 10
11-18 19:20:14.064  4597  4655 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-18 19:20:14.066   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-18 19:20:14.071  4597  4655 I BluetoothAdapterState: Entering OffState
,11-18 19:20:14.076  4597  4597 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-18 19:20:14.076  4597  4597 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-18 19:20:14.076  4597  4597 I BluetoothServiceJni: cleanupNative: return from cleanup
11-18 19:20:14.078  4597  4656 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-18 19:20:14.083  4597  4597 I art     : System.exit called, status: 0
,11-18 19:20:14.083  4597  4597 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-18 19:20:14.111   929  3153 I ActivityManager: Process com.android.bluetooth (pid 4597) has died
,11-18 19:20:14.114  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 19:20:14.152  5570  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-18 19:20:14.153  5570  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 19:20:14.153  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:20:14.153  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 19:20:14.153  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 19:20:14.153  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-18 19:20:14.153  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 19:20:14.153  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 19:20:14.153  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 19:20:14.153  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 19:20:14.153  5570  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 19:20:14.153  5570  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 19:20:14.161  5570  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 19:20:14.182   929   946 I ActivityManager: Start proc 5653:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-18 19:20:14.254  5653  5653 D AdapterServiceConfig: Adding HeadsetService
,11-18 19:20:14.255  5653  5653 D AdapterServiceConfig: Adding A2dpService
11-18 19:20:14.255  5653  5653 D AdapterServiceConfig: Adding HidService
11-18 19:20:14.255  5653  5653 D AdapterServiceConfig: Adding HealthService
11-18 19:20:14.255  5653  5653 D AdapterServiceConfig: Adding PanService
11-18 19:20:14.255  5653  5653 D AdapterServiceConfig: Adding GattService
11-18 19:20:14.255  5653  5653 D AdapterServiceConfig: Adding BluetoothMapService
,11-18 19:20:14.256  5653  5653 D AdapterServiceConfig: Adding SapService
,11-18 19:20:14.265   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ed57d3c:true
,11-18 19:20:14.265  5653  5653 D BluetoothAdapterState: make() - Creating AdapterState
,11-18 19:20:14.269  5653  5653 I bt_bluedroid: init
,11-18 19:20:14.269  5653  5665 I BluetoothAdapterState: Entering OffState
,11-18 19:20:14.271  5653  5666 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-18 19:20:14.271  5653  5666 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-18 19:20:14.271  5653  5666 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-18 19:20:14.271  5653  5666 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-18 19:20:14.271  5653  5653 I bt_bluedroid: get_profile_interface socket
,11-18 19:20:14.273  5653  5669 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-18 19:20:14.274  5653  5653 I bt_bluedroid: get_profile_interface sdp
11-18 19:20:14.274  5653  5669 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-18 19:20:14.281  5653  5664 I bt_bluedroid: config_hci_snoop_log
11-18 19:20:14.282   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-18 19:20:14.287  5653  5665 D BluetoothAdapterState: Current state: OFF, message: 0
,11-18 19:20:14.287  5653  5665 D BluetoothAdapterProperties: Setting state to 14
11-18 19:20:14.287  5653  5665 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-18 19:20:14.288  5653  5665 D BluetoothBondStateMachine: make
,11-18 19:20:14.290  5653  5670 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-18 19:20:14.293  5653  5665 I BluetoothAdapterState: Entering PendingCommandState
,11-18 19:20:14.294  5653  5653 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-18 19:20:14.296  5653  5653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18756d2
11-18 19:20:14.296  5653  5653 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-18 19:20:14.297  5653  5653 D BtGatt.GattService: Received start request. Starting profile...
11-18 19:20:14.297  5653  5653 D BtGatt.GattService: start()
11-18 19:20:14.297  5653  5653 I bt_bluedroid: get_profile_interface gatt
,11-18 19:20:14.298  5653  5653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18756d2
,11-18 19:20:14.298  5653  5653 D BtGatt.AdvertiseManager: advertise manager created
,11-18 19:20:14.304  5653  5653 V BluetoothAdapterState: isTurningOff()=false
11-18 19:20:14.304  5653  5653 V BluetoothAdapterState: isTurningOn()=false
11-18 19:20:14.304  5653  5653 V BluetoothAdapterState: isBleTurningOn()=true
11-18 19:20:14.304  5653  5653 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 19:20:14.305  5653  5665 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-18 19:20:14.306  5653  5665 I bt_bluedroid: bt_bluedroid
11-18 19:20:14.306  5653  5666 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-18 19:20:14.307  5653  5666 I bt_hci  : start_up
,11-18 19:20:14.312  5653  5666 I bt_vendor: alloc value 0xf404d871
11-18 19:20:14.312  5653  5666 I bt_vendor: init
11-18 19:20:14.312  5653  5666 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-18 19:20:14.312  5653  5666 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-18 19:20:14.423  5653  5666 D bt_hci  : start_up starting async portion
,11-18 19:20:14.423  5653  5673 I bt_hci  : event_finish_startup
11-18 19:20:14.423  5653  5673 I bt_hci_h4: hal_open
11-18 19:20:14.424  5653  5673 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-18 19:20:14.421  5674  5674 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 19:20:14.428  5653  5673 I bt_userial_vendor: device fd = 54 open
,11-18 19:20:14.442  5653  5673 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-18 19:20:14.444  5653  5673 D bt_hwcfg: Chipset BCM4358A3
11-18 19:20:14.445  5653  5673 D bt_hwcfg: Target name = [BCM4358A3]
11-18 19:20:14.445  5653  5673 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-18 19:20:14.667  5653  5665 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-18 19:20:14.842  5653  5673 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-18 19:20:14.842  5653  5673 D bt_hwcfg: Settlement delay -- 100 ms
,11-18 19:20:14.842  5653  5673 I bt_hwcfg: Setting fw settlement delay to 100 
,11-18 19:20:14.966  5653  5673 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-18 19:20:14.966  5653  5673 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-18 19:20:14.970  5653  5673 I bt_hwcfg: vendor lib fwcfg completed
11-18 19:20:14.970  5653  5673 I bt_vendor: firmware callback
,11-18 19:20:14.970  5653  5673 I bt_hci  : firmware_config_callback
,11-18 19:20:14.980  5653  5676 I bt_btu  : btu_task pending for preload complete event
,11-18 19:20:14.980  5653  5676 I bt_btu_task: Bluetooth chip preload is complete
11-18 19:20:14.980  5653  5676 I bt_btu  : btu_task received preload complete event
,11-18 19:20:14.986  5653  5676 I         : BTE_InitTraceLevels -- TRC_HCI
,11-18 19:20:14.987  5653  5676 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-18 19:20:14.987  5653  5676 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-18 19:20:14.987  5653  5676 I         : BTE_InitTraceLevels -- TRC_AVDT
11-18 19:20:14.987  5653  5676 I         : BTE_InitTraceLevels -- TRC_AVRC
11-18 19:20:14.987  5653  5676 I         : BTE_InitTraceLevels -- TRC_A2D
11-18 19:20:14.987  5653  5676 I         : BTE_InitTraceLevels -- TRC_BNEP
11-18 19:20:14.987  5653  5676 I         : BTE_InitTraceLevels -- TRC_BTM
11-18 19:20:14.987  5653  5676 I         : BTE_InitTraceLevels -- TRC_GAP
11-18 19:20:14.987  5653  5676 I         : BTE_InitTraceLevels -- TRC_PAN
11-18 19:20:14.988  5653  5676 I         : BTE_InitTraceLevels -- TRC_SDP
11-18 19:20:14.988  5653  5676 I         : BTE_InitTraceLevels -- TRC_GATT
11-18 19:20:14.988  5653  5676 I         : BTE_InitTraceLevels -- TRC_SMP
11-18 19:20:14.988  5653  5676 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-18 19:20:14.988  5653  5676 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-18 19:20:15.066  5653  5676 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fcb549
11-18 19:20:15.066  5653  5676 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fcb549 
,11-18 19:20:15.081  5653  5669 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-18 19:20:15.082  5653  5669 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-18 19:20:15.083  5653  5669 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-18 19:20:15.085  5653  5669 D BluetoothAdapterProperties: Name is: Nexus 6P
11-18 19:20:15.088  5653  5669 D BluetoothAdapterProperties: Scan Mode:20
11-18 19:20:15.088  5653  5669 D BluetoothAdapterProperties: Discoverable Timeout:120
11-18 19:20:15.089  5653  5669 D bt_hci  : do_postload posting postload work item
11-18 19:20:15.089  5653  5673 I bt_hci  : event_postload
11-18 19:20:15.089  5653  5673 I bt_vendor: sco_config_cb
11-18 19:20:15.089  5653  5673 I bt_hci  : sco_config_callback postload finished.
11-18 19:20:15.093  5653  5669 D bt_bte_conf: Device ID record 1 : primary
11-18 19:20:15.093  5653  5669 D bt_bte_conf:   vendorId            = 000f
11-18 19:20:15.093  5653  5669 D bt_bte_conf:   vendorIdSource      = 0001
11-18 19:20:15.093  5653  5669 D bt_bte_conf:   product             = 1200
11-18 19:20:15.093  5653  5669 D bt_bte_conf:   version             = 1436
11-18 19:20:15.093  5653  5669 D bt_bte_conf:   clientExecutableURL = 
11-18 19:20:15.093  5653  5669 D bt_bte_conf:   serviceDescription  = 
11-18 19:20:15.093  5653  5669 D bt_bte_conf:   documentationURL    = 
11-18 19:20:15.094  5653  5669 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-18 19:20:15.094  5653  5666 D bt_stack_manager: event_start_up_stack finished
11-18 19:20:15.095  5653  5665 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-18 19:20:15.096  5653  5665 D BluetoothAdapterProperties: Setting state to 15
11-18 19:20:15.096  5653  5665 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-18 19:20:15.096  5653  5673 I bt_vendor: low_power_mode_cb
11-18 19:20:15.097  5653  5665 I BluetoothAdapterState: Entering BleOnState
11-18 19:20:15.104  5653  5665 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-18 19:20:15.104  5653  5665 D BluetoothAdapterProperties: Setting state to 11
11-18 19:20:15.105  5653  5665 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-18 19:20:15.118  5653  5653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18756d2
,11-18 19:20:15.119  5653  5653 D HeadsetService: Received start request. Starting profile...
11-18 19:20:15.121  5653  5653 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-18 19:20:15.122  5653  5653 D HeadsetStateMachine: make
,11-18 19:20:15.132  5653  5665 I BluetoothAdapterState: Entering PendingCommandState
,11-18 19:20:15.133  5653  5653 D HeadsetStateMachine: max_hf_connections = 1
11-18 19:20:15.134  5653  5653 I bt_bluedroid: get_profile_interface handsfree
,11-18 19:20:15.134  5653  5669 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-18 19:20:15.135  5653  5669 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-18 19:20:15.138  5653  5653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18756d2
,11-18 19:20:15.139  5653  5653 D A2dpService: Received start request. Starting profile...
,11-18 19:20:15.140  5653  5653 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-18 19:20:15.140  5653  5653 I bt_bluedroid: get_profile_interface avrcp
,11-18 19:20:15.146  5653  5653 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-18 19:20:15.146  5653  5653 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-18 19:20:15.146  5653  5653 D A2dpStateMachine: make
11-18 19:20:15.148  5653  5653 I bt_bluedroid: get_profile_interface a2dp
,11-18 19:20:15.149  5653  5669 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-18 19:20:15.151  5653  5684 D A2dpStateMachine: Enter Disconnected: -2
11-18 19:20:15.152  5653  5653 I BluetoothHidServiceJni: classInitNative: succeeds
11-18 19:20:15.153  5653  5653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18756d2
11-18 19:20:15.154  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 19:20:15.159  5636  5636 D BluetoothInputDevice: Proxy object connected
,11-18 19:20:15.159  5653  5653 D HidService: Received start request. Starting profile...
,11-18 19:20:15.159  5653  5653 I bt_bluedroid: get_profile_interface hidhost
11-18 19:20:15.159  5636  5636 D HidProfile: Bluetooth service connected
11-18 19:20:15.159  5653  5669 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fac56d
11-18 19:20:15.159  5653  5653 D HidService: setHidService(): set to: null
11-18 19:20:15.159  5653  5669 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-18 19:20:15.160  5653  5653 I BluetoothHealthServiceJni: classInitNative: succeeds
11-18 19:20:15.161  5653  5653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18756d2
,11-18 19:20:15.162  5653  5653 D HealthService: Received start request. Starting profile...
,11-18 19:20:15.163  5653  5653 I bt_bluedroid: get_profile_interface health
,11-18 19:20:15.164  5653  5653 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-18 19:20:15.165  5653  5653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18756d2
,11-18 19:20:15.166  5636  5636 D BluetoothPan: BluetoothPAN Proxy object connected
11-18 19:20:15.167  5653  5653 D PanService: Received start request. Starting profile...
11-18 19:20:15.167  5636  5636 D PanProfile: Bluetooth service connected
11-18 19:20:15.167  5653  5653 D BluetoothPanServiceJni: initializeNative(L110): pan
11-18 19:20:15.167  5653  5653 I bt_bluedroid: get_profile_interface pan
11-18 19:20:15.167  5653  5669 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-18 19:20:15.170  5653  5665 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-18 19:20:15.172  5653  5653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18756d2
,11-18 19:20:15.173  5636  5636 D BluetoothMap: Proxy object connected
11-18 19:20:15.173  5653  5653 D BluetoothMapService: Received start request. Starting profile...
11-18 19:20:15.173  5653  5653 D BluetoothMapService: start()
,11-18 19:20:15.174  5636  5636 D MapProfile: Bluetooth service connected
11-18 19:20:15.174  5636  5636 D BluetoothMap: getConnectedDevices()
11-18 19:20:15.174  5636  5636 D BluetoothMap: Bluetooth is Not enabled
,11-18 19:20:15.176  5653  5653 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-18 19:20:15.177  5653  5653 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-18 19:20:15.177  5653  5653 D BluetoothMapAppObserver: createReceiver()
11-18 19:20:15.178  5653  5653 D BluetoothMapAppObserver: initObservers()
11-18 19:20:15.178  5653  5653 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-18 19:20:15.184  5653  5653 V SapService: SapBinder()
,11-18 19:20:15.184  5653  5653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18756d2
,11-18 19:20:15.185  5653  5653 D SapService: Received start request. Starting profile...
11-18 19:20:15.185  5653  5653 V SapService: start()
,11-18 19:20:15.186  5653  5653 V BluetoothAdapterState: isTurningOff()=false
,11-18 19:20:15.187  5653  5653 V BluetoothAdapterState: isTurningOn()=true
11-18 19:20:15.187  5653  5653 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:15.187  5653  5653 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:15.187  5653  5653 V BluetoothAdapterState: isTurningOff()=false
11-18 19:20:15.187  5653  5653 V BluetoothAdapterState: isTurningOn()=true
11-18 19:20:15.187  5653  5653 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:15.187  5653  5681 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
11-18 19:20:15.187  5653  5653 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:15.188  5653  5653 V BluetoothAdapterState: isTurningOff()=false
11-18 19:20:15.188  5653  5653 V BluetoothAdapterState: isTurningOn()=true
11-18 19:20:15.188  5653  5653 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:15.188  5653  5653 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:15.188  5653  5653 V BluetoothAdapterState: isTurningOff()=false
11-18 19:20:15.188  5653  5653 V BluetoothAdapterState: isTurningOn()=true
11-18 19:20:15.189  5653  5653 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 19:20:15.189  5653  5653 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:15.189  5653  5653 V BluetoothAdapterState: isTurningOff()=false
11-18 19:20:15.189  5653  5653 V BluetoothAdapterState: isTurningOn()=true
11-18 19:20:15.189  5653  5653 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:15.189  5653  5653 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:15.189  5653  5653 V BluetoothAdapterState: isTurningOff()=false
11-18 19:20:15.189  5653  5653 V BluetoothAdapterState: isTurningOn()=true
11-18 19:20:15.189  5653  5653 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:15.190  5653  5653 V BluetoothAdapterState: isBleTurningOff()=false
11-18 19:20:15.190  5653  5653 V BluetoothAdapterState: isTurningOff()=false
11-18 19:20:15.190  5653  5653 V BluetoothAdapterState: isTurningOn()=true
11-18 19:20:15.190  5653  5653 V BluetoothAdapterState: isBleTurningOn()=false
11-18 19:20:15.191  5653  5653 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 19:20:15.191  5653  5665 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-18 19:20:15.191  5653  5665 D BluetoothAdapterProperties: ScanMode =  20
11-18 19:20:15.191  5653  5665 D BluetoothAdapterProperties: State =  11
11-18 19:20:15.191  5653  5665 D BluetoothAdapterProperties: Setting state to 12
11-18 19:20:15.191  5653  5665 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-18 19:20:15.192   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 19:20:15.192  5653  5665 I BluetoothAdapterState: Entering OnState
11-18 19:20:15.192  5653  5669 D BluetoothAdapterProperties: Scan Mode:21
11-18 19:20:15.193  5636  5646 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-18 19:20:15.193  5653  5669 D BluetoothAdapterProperties: Discoverable Timeout:120
11-18 19:20:15.193  5636  5647 D BluetoothMap: onBluetoothStateChange: up=true
11-18 19:20:15.193   929   929 D BluetoothA2dp: Proxy object connected
,11-18 19:20:15.194  5636  5646 D BluetoothPbap: onBluetoothStateChange: up=true
,11-18 19:20:15.195  5636  5647 D BluetoothPan: onBluetoothStateChange on: true
11-18 19:20:15.195   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 19:20:15.195  3126  3851 D BluetoothPan: onBluetoothStateChange on: true
,11-18 19:20:15.197  3126  3126 D BluetoothPan: BluetoothPAN Proxy object connected
,11-18 19:20:15.197  3126  3126 D PanProfile: Bluetooth service connected
11-18 19:20:15.197  3126  3138 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-18 19:20:15.199  3126  3126 D BluetoothInputDevice: Proxy object connected
11-18 19:20:15.199  3126  3141 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 19:20:15.199  3126  3126 D HidProfile: Bluetooth service connected
11-18 19:20:15.199  3771  3804 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-18 19:20:15.200  3126  3138 D BluetoothPbap: onBluetoothStateChange: up=true
,11-18 19:20:15.201   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 19:20:15.201  3126  3851 D BluetoothMap: onBluetoothStateChange: up=true
,11-18 19:20:15.202  5653  5653 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-18 19:20:15.203  5653  5653 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-18 19:20:15.203  3126  3126 D BluetoothMap: Proxy object connected
11-18 19:20:15.203  3126  3126 D MapProfile: Bluetooth service connected
11-18 19:20:15.203  3126  3126 D BluetoothMap: getConnectedDevices()
11-18 19:20:15.203   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 19:20:15.203  3126  3138 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 19:20:15.204  5653  5653 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:20:15.205  3126  3126 D BluetoothA2dp: Proxy object connected
,11-18 19:20:15.206   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,11-18 19:20:15.209  5653  5653 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 19:20:15.210  5653  5653 D ObexServerSockets: Succeed to create listening sockets 
11-18 19:20:15.210  5653  5653 D ObexServerSockets0: startAccept()
11-18 19:20:15.210  5653  5653 D ObexServerSockets0: prepareForNewConnect()
,11-18 19:20:15.211  5636  5636 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-18 19:20:15.212  5653  5653 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-18 19:20:15.212  5653  5691 D ObexServerSockets0: Accepting socket connection...
11-18 19:20:15.212  5653  5653 D BluetoothSdpJni: SDP Create record success - handle: 0
11-18 19:20:15.213  5653  5692 D ObexServerSockets0: Accepting socket connection...
11-18 19:20:15.213  5653  5653 D BluetoothMapService: onReceive
,11-18 19:20:15.213  5653  5653 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-18 19:20:15.213  5653  5653 D BluetoothMapService: STATE_ON
11-18 19:20:15.214  5636  5636 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-18 19:20:15.216  5653  5693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:20:15.218  5653  5693 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-18 19:20:15.218  5653  5693 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-18 19:20:15.221  5636  5636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 19:20:15.223  5636  5636 D BluetoothA2dp: Proxy object connected
,11-18 19:20:15.227  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 19:20:15.233  3126  3126 D BluetoothPbap: Proxy object connected
11-18 19:20:15.233  3126  3126 D PbapServerProfile: Bluetooth service connected
,11-18 19:20:15.234  5636  5636 D DockEventReceiver: finishStartingService: stopping service
,11-18 19:20:15.234  5636  5636 D BluetoothPbap: Proxy object connected
11-18 19:20:15.235  5636  5636 D PbapServerProfile: Bluetooth service connected
,11-18 19:20:15.240  5653  5653 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-18 19:20:15.240  5653  5653 D ObexServerSockets0: prepareForNewConnect()
11-18 19:20:15.242  5653  5697 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 19:20:15.254  5653  5701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 19:20:15.255  5653  5701 I BtOppRfcommListener: Accept thread started.
,11-18 19:20:15.296  3771  3797 D BluetoothHeadset: Proxy object connected
,11-18 19:20:15.296   929   929 D BluetoothHeadset: Proxy object connected
11-18 19:20:15.297  3126  3138 D BluetoothHeadset: Proxy object connected
11-18 19:20:15.297  3126  3126 D HeadsetProfile: Bluetooth service connected
11-18 19:20:15.297   929   929 D BluetoothHeadset: Proxy object connected
11-18 19:20:15.297   929   929 D BluetoothHeadset: Proxy object connected
,11-18 19:20:15.300  3126  3141 D BluetoothHeadset: Proxy object connected
,11-18 19:20:15.300  3126  3126 D HeadsetProfile: Bluetooth service connected
11-18 19:20:15.300  3771  3992 D BluetoothHeadset: Proxy object connected
,11-18 19:20:15.301   929   946 D BluetoothHeadset: Proxy object connected
,11-18 19:20:15.304   929   946 D BluetoothHeadset: Proxy object connected
,11-18 19:20:15.317  5636  5647 D BluetoothHeadset: Proxy object connected
,11-18 19:20:15.318  5636  5636 D HeadsetProfile: Bluetooth service connected
,11-18 19:20:15.683  5570  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 19:20:15.683  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:20:15.683  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 19:20:15.683  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 19:20:15.683  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 19:20:15.683  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 19:20:15.683  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 19:20:15.683  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 19:20:15.683  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 19:20:15.689  5570  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 19:20:15.692  5570  5618 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-18 19:20:15.696   929  3152 D WifiService: setWifiEnabled: false pid=5570, uid=10077
,11-18 19:20:15.696   929  3152 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 19:20:15.700   929  2985 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-18 19:20:15.701   929  2985 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-18 19:20:15.703   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-18 19:20:15.703  5570  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 19:20:15.704   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 19:20:15.722   929  5354 D DhcpClient: Clearing IP address
,11-18 19:20:15.722   508   923 D CommandListener: Clearing all IP addresses on wlan0
,11-18 19:20:15.730   508   923 D CommandListener: Setting iface cfg
,11-18 19:20:15.732   929  5355 D DhcpClient: Receive thread stopped
11-18 19:20:15.735  3577  5410 V NativeCrypto: Read error: ssl=0x7f8c0c5700: I/O error during system call, Connection timed out
,11-18 19:20:15.738  3577  5410 V NativeCrypto: SSL shutdown failed: ssl=0x7f8c0c5700: I/O error during system call, Broken pipe
,11-18 19:20:15.742   929  3811 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-18 19:20:15.743   929  5352 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-18 19:20:15.746   929  5352 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-18 19:20:15.747   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-18 19:20:15.747   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-18 19:20:15.749   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-18 19:20:15.758   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-18 19:20:15.759   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-18 19:20:15.761   534   534 E Parcel  : Reading a NULL string not supported here.
11-18 19:20:15.764   929   929 D RttService: SCAN_AVAILABLE : 1
11-18 19:20:15.764   929  3041 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-18 19:20:15.766   929  2987 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-18 19:20:15.768  3743  3861 W QCNEJ   : |CORE| network lost: 100
,11-18 19:20:15.769  3743  3861 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-18 19:20:15.775   929  2985 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-18 19:20:15.791   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-18 19:20:15.796   508   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 19:20:15.819   508   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 19:20:15.820   508   923 D CommandListener: Clearing all IP addresses on wlan0
11-18 19:20:15.820   508   923 D TetherController: Setting IP forward enable = 0
,11-18 19:20:15.820   929  2987 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-18 19:20:15.820   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-18 19:20:15.823   929   946 D Tethering: MasterInitialState.processMessage what=3
11-18 19:20:15.826   929  2985 D DhcpClient: doQuit
11-18 19:20:15.826   929  2985 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-18 19:20:15.827   929  5354 D DhcpClient: onQuitting
11-18 19:20:15.827  3439  3439 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-18 19:20:15.827  3967  3967 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-18 19:20:15.832  3689  3689 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-18 19:20:15.830  4919  4950 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-18 19:20:15.833  4919  4950 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-18 19:20:15.833  4919  4950 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-18 19:20:15.834  4919  4950 E SarControlService: no key has been found,reset the power
11-18 19:20:15.839  4919  4988 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 19:20:15.839  4919  4988 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 19:20:15.839  4919  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 19:20:15.839  4975  4975 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 19:20:15.840  4975  4975 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-18 19:20:15.841  4919  4988 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-18 19:20:15.841  4919  4988 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-18 19:20:15.841  4919  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-18 19:20:15.841  4975  4975 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-18 19:20:15.841  4975  4975 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-18 19:20:15.843  3689  3689 D SystemUpdateService: onCreate
11-18 19:20:15.844  4975  4994 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8574ea5 HexData = [00000000ea03000000000000ffffffff]
11-18 19:20:15.844  4975  4994 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 19:20:15.844  4975  4994 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-18 19:20:15.844  4975  4975 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 19:20:15.844  4919  4930 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-18 19:20:15.847  3689  3689 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-18 19:20:15.851  4975  4994 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8574ea5 HexData = [00000000eb03000000000000ffffffff]
,11-18 19:20:15.851  4975  4994 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-18 19:20:15.853  4975  4994 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-18 19:20:15.853  4975  4975 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 19:20:15.853  4919  4929 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-18 19:20:15.855  3689  5716 I SystemUpdateService: active receiver: enabled
11-18 19:20:15.855  3439  3439 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-18 19:20:15.857  3689  3689 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-18 19:20:15.861  3439  3439 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-18 19:20:15.862   508   916 W SocketClient: write error (Broken pipe)
11-18 19:20:15.862   508   916 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-18 19:20:15.863   508   916 W SocketListener: Error sending broadcast (Broken pipe)
,11-18 19:20:15.865  3689  3689 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-18 19:20:15.867  3689  3689 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-18 19:20:15.868  5378  5378 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-18 19:20:15.872  5378  5378 D SprintDMHelper: simOperator: 
11-18 19:20:15.872  5378  5378 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 19:20:15.876  3689  5716 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-18 19:20:15.880  3689  5376 I iu.UploadsManager: num queued entries: 0
,11-18 19:20:15.885  3689  5716 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-18 19:20:15.885  3689  5716 I SystemUpdateService: now status is 0 (complete)
11-18 19:20:15.885  3689  5716 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-18 19:20:15.885  3689  5716 I SystemUpdateService: file has been verified
11-18 19:20:15.886  3689  5716 I SystemUpdateService: OTA package size = 21989297
11-18 19:20:15.887   508   923 E Netd    : netlink response contains error (No such file or directory)
,11-18 19:20:15.888   929  2987 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-18 19:20:15.888   929  2987 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-18 19:20:15.888  4295  5720 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-18 19:20:15.890  3689  5376 I iu.UploadsManager: num updated entries: 0
11-18 19:20:15.891  3689  5376 I iu.SyncManager: NEXT; no task
11-18 19:20:15.892  3439  3439 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-18 19:20:15.895  3689  5716 I SystemUpdateService: showing system update notification
,11-18 19:20:15.899  3439  3439 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-18 19:20:15.901   929  3416 I ActivityManager: Start proc 5721:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-18 19:20:15.918   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-18 19:20:15.921  3689  3689 D SystemUpdateService: onDestroy
,11-18 19:20:15.934  5721  5721 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-18 19:20:15.941   929  3153 I ActivityManager: Killing 5434:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-18 19:20:16.004   929  2985 D wifi    : In wifi stop Hal
,11-18 19:20:16.004   929  2985 D wifi    : halHandle = 0x7f89ed1680, mVM = 0x7fa648d140, mCls = 0x1009fa
11-18 19:20:16.005   929  3437 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-18 19:20:16.005   929  3437 D WifiHAL : Got a signal to exit!!!
11-18 19:20:16.005   929  3437 I WifiHAL : Exit wifi_event_loop
11-18 19:20:16.005   929  2985 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-18 19:20:16.006   929  2985 E WifiHAL : Event processing terminated
11-18 19:20:16.006   929  2985 D wifi    : In wifi cleaned up handler
11-18 19:20:16.006   929  2985 I WifiHAL : Internal cleanup completed
11-18 19:20:16.006  4018  4206 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-18 19:20:16.006  4295  4295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-18 19:20:16.027   929  3437 D wifi    : set interface wlan0 flags (DOWN)
,11-18 19:20:16.028   929  2985 D WifiNative-HAL: HAL event thread stopped successfully
,11-18 19:20:16.210  5570  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 19:20:16.210  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:20:16.210  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 19:20:16.210  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-18 19:20:16.210  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 19:20:16.210  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 19:20:16.210  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 19:20:16.210  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 19:20:16.210  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 19:20:16.215  5570  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 19:20:16.219   929   940 D WifiService: setWifiEnabled: true pid=5570, uid=10077
,11-18 19:20:16.220   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 19:20:16.221  5570  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 19:20:16.233   508   923 D SoftapController: Softap fwReload - Ok
11-18 19:20:16.234   929   946 D Tethering: InitialState.processMessage what=4
,11-18 19:20:16.238   508   923 D CommandListener: Setting iface cfg
,11-18 19:20:16.238   508   923 D CommandListener: Trying to bring down wlan0
,11-18 19:20:16.240   508   923 D CommandListener: Clearing all IP addresses on wlan0
,11-18 19:20:16.240   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-18 19:20:16.244   929  2985 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-18 19:20:16.724   929  3753 D WifiService: setWifiEnabled: true pid=5570, uid=10077
,11-18 19:20:16.728   929  3753 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 19:20:16.843   929  2985 D wifi    : set interface wlan0 flags (UP)
11-18 19:20:16.843   929  2985 I WifiHAL : Initializing wifi
,11-18 19:20:16.844   929  2985 I WifiHAL : Creating socket
,11-18 19:20:16.850   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-18 19:20:16.853   929  2985 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-18 19:20:16.854   929  2985 D wifi    : Did set static halHandle = 0x7f89ed1680
,11-18 19:20:16.855   929  2985 D wifi    : halHandle = 0x7f89ed1680, mVM = 0x7fa648d140, mCls = 0x1676
11-18 19:20:16.855   929  2985 D wifi    : array field set
,11-18 19:20:16.855   929  2985 I WifiNative-HAL: interface[0] = wlan0
11-18 19:20:16.858   929  5737 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547774862976
11-18 19:20:16.858   929  5737 D wifi    : waitForHalEvents called, vm = 0x7fa648d140, obj = 0x1676, env = 0x7f8eea9a40
,11-18 19:20:16.892   508   923 D TetherController: Setting IP forward enable = 0
,11-18 19:20:16.928  5738  5738 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-18 19:20:16.959   929  2985 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-18 19:20:17.017  5738  5738 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 19:20:17.028  5738  5738 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 19:20:17.028  5738  5738 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-18 19:20:17.040   929  2985 D WifiConfigStore: Loading config and enabling all networks 
,11-18 19:20:17.056   929  2985 D WifiConfigStore: loaded 0 passpoint configs
,11-18 19:20:17.057   929  2985 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-18 19:20:17.057   929  2985 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-18 19:20:17.058   929  2985 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-18 19:20:17.058   929  2985 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-18 19:20:17.059   929  2985 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-18 19:20:17.059   929  2985 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-18 19:20:17.059   929  2985 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-18 19:20:17.060   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-18 19:20:17.060   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-18 19:20:17.060   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-18 19:20:17.060   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-18 19:20:17.060   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-18 19:20:17.062   929  2985 D WifiNative-HAL: Setting external_sim to 1
,11-18 19:20:17.063   929  2985 D wifi    : setting dfs flag to true, 0x7f8bee39c0
,11-18 19:20:17.063  4295  4295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-18 19:20:17.063   929  2985 D WifiStateMachine: Setting OUI to DA-A1-19
11-18 19:20:17.063   929  2985 D wifi    : setting scan oui 0x7f8bee39c0
11-18 19:20:17.063   929  2985 D WifiHAL : Sending mac address OUI
,11-18 19:20:17.067   929  2985 E native  : do suspend false
,11-18 19:20:17.074   929  2985 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-18 19:20:17.074   929   929 D RttService: SCAN_AVAILABLE : 3
11-18 19:20:17.075   929  3041 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-18 19:20:17.079   508   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-18 19:20:17.082   508   923 D CommandListener: Setting iface cfg
,11-18 19:20:17.088   929  2970 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,11-18 19:20:17.088   929  2970 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-18 19:20:17.093   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=96357 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-18 19:20:17.095   929  2970 D WifiNative-HAL: p2pGetDeviceAddress
,11-18 19:20:17.095   929  2970 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-18 19:20:17.237  5570  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 19:20:17.237  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 19:20:17.237  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 19:20:17.237  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 19:20:17.237  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 19:20:17.237  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 19:20:17.237  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 19:20:17.237  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 19:20:17.237  5570  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 19:20:17.242  5570  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 19:20:17.246  5570  5618 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 19:20:17.247   929  3799 D WifiService: setWifiEnabled: true pid=5570, uid=10077
,11-18 19:20:17.247   929  3799 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 19:20:17.248  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-18 19:20:17.249  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-18 19:20:17.249  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 19:20:17.249  5570  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5a71e3 removed from the list
11-18 19:20:17.249  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-18 19:20:17.250  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c7d7e0 removed from the list
11-18 19:20:17.250  5570  5618 D io.jxcore.node.ConnectivityMonitor: stop
11-18 19:20:17.252  5570  5618 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-18 19:20:17.254  5570  5618 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-18 19:20:17.255  5570  5618 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-18 19:20:17.257  5570  5618 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-18 19:20:17.259  5570  5618 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-18 19:20:17.260  5570  5618 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-18 19:20:17.261  5570  5618 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-18 19:20:17.261  5570  5618 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-18 19:20:17.262  5570  5618 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-18 19:20:17.264  5570  5618 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-18 19:20:17.265  5570  5618 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@400c259 Bundle[{}]
,11-18 19:20:17.266  5570  5618 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-18 19:20:17.266  5570  5618 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-18 19:20:17.266  5570  5618 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-18 19:20:17.267  5570  5618 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-18 19:20:17.267  5570  5618 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-18 19:20:17.268  5570  5618 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-18 19:20:17.268  5570  5618 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-18 19:20:17.269  5570  5618 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,11-18 19:20:17.269  5570  5618 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-18 19:20:17.270  5570  5618 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-18 19:20:17.270  5570  5618 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-18 19:20:17.273  5570  5618 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-18 19:20:17.275  5570  5618 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-18 19:20:17.275  5570  5618 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-18 19:20:17.277  5570  5618 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-18 19:20:17.278  5570  5618 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-18 19:20:17.279  5570  5618 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-18 19:20:17.280  5570  5618 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-18 19:20:17.281  5570  5618 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-18 19:20:17.282  5570  5618 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
11-18 19:20:17.283  5570  5618 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-18 19:20:17.284  5570  5618 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-18 19:20:17.284  5570  5618 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-18 19:20:17.285  5570  5618 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 137)
,11-18 19:20:17.285  5570  5618 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,11-18 19:20:17.286  5570  5618 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-18 19:20:17.286  5570  5618 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 138)
,11-18 19:20:17.286  5570  5618 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-18 19:20:17.287  5570  5618 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-18 19:20:17.288  5570  5618 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-18 19:20:17.288  5570  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 19:20:17.288  5570  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f70615e added. We now have 3 listener(s)
,11-18 19:20:17.290  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:20:17.290  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 19:20:17.290  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 19:20:17.290  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-18 19:20:17.290  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d38493f added. We now have 3 listener(s)
11-18 19:20:17.290  5570  5618 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 19:20:17.291  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 19:20:17.295  5570  5618 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-18 19:20:17.295  5570  5618 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-18 19:20:17.295  5570  5618 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-18 19:20:17.295  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,11-18 19:20:17.295  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.295  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.296  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.296  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:20:17.296  5570  5618 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 19:20:17.296  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 19:20:17.296  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:20:17.296  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 19:20:17.298  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 19:20:17.299  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 19:20:17.299  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 19:20:17.299  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-18 19:20:17.299  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 19:20:17.299  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 19:20:17.299  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 19:20:17.299  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:20:17.299  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 19:20:17.299  5570  5746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 19:20:17.300  5570  5746 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 19:20:17.301  5689  5689 W Binder_4: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33867]" dev="sockfs" ino=33867 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 19:20:17.301  5689  5689 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33867]" dev="sockfs" ino=33867 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:20:17.302  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 19:20:17.302  5570  5618 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 19:20:17.302  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 19:20:17.303  5570  5746 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 19:20:17.306  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:17.306  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 19:20:17.307  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:20:17.308  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 19:20:17.308  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-18 19:20:17.310  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:17.310  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.310  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 19:20:17.310  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 19:20:17.310  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:20:17.310  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-18 19:20:17.310  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:17.310  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:17.311  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.311  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 19:20:17.311  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:17.311  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:17.311  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.311  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.312  5570  5618 D BluetoothAdapter: STATE_ON
,11-18 19:20:17.315  5653  5682 D BtGatt.GattService: registerClient() - UUID=d54b1696-9dfc-4134-a995-10fd4099a19a
,11-18 19:20:17.316  5653  5669 D BtGatt.GattService: onClientRegistered() - UUID=d54b1696-9dfc-4134-a995-10fd4099a19a, clientIf=5
,11-18 19:20:17.316  5570  5580 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 19:20:17.318  5653  5671 D BtGatt.AdvertiseManager: message : 0
,11-18 19:20:17.319  5653  5671 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 19:20:17.328  5653  5669 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 19:20:17.334  5653  5669 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 19:20:17.334  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:17.334  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.335  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 19:20:17.335  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.335  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.335  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.335  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.335  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.335  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-18 19:20:17.336  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-18 19:20:17.336  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:17.338  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:17.338  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.338  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:17.338  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 19:20:17.338  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 19:20:17.338  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:17.338  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 19:20:17.339  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 19:20:17.339  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:17.339  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:17.339  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:17.339  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 19:20:17.339  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 19:20:17.339  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:20:17.339  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 19:20:17.339  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 19:20:17.339  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:20:17.341  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-18 19:20:17.341  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 19:20:17.341  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:17.341  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:17.341  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:17.342  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 19:20:17.842  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-18 19:20:17.843  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 19:20:17.843  5570  5570 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 19:20:20.141  5738  5738 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 19:20:20.148  5738  5738 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 19:20:20.155  5738  5738 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 19:20:20.202   929  2985 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-18 19:20:20.204   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-18 19:20:20.204   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 19:20:20.219   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-18 19:20:20.254   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-18 19:20:20.259  5738  5738 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-18 19:20:20.705  5738  5738 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-18 19:20:20.747  5738  5738 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-18 19:20:20.748  5738  5738 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-18 19:20:20.759   929  2985 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-18 19:20:20.760   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-18 19:20:20.760   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-18 19:20:20.777   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 19:20:20.787   508   923 D CommandListener: Setting iface cfg
,11-18 19:20:20.791   929  2985 D WifiStateMachine: Start Dhcp Watchdog 2
,11-18 19:20:20.796   929  5751 D DhcpClient: Receive thread started
,11-18 19:20:20.800   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 19:20:20.800   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-18 19:20:20.800   929  2987 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-18 19:20:20.841  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 19:20:20.841  5570  5618 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 19:20:20.842  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 19:20:20.842  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 19:20:20.842  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 19:20:20.842  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 19:20:20.842  5570  5746 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 19:20:20.842  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-18 19:20:20.842  5570  5746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 19:20:20.842  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 19:20:20.842  5570  5746 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 19:20:20.842  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 19:20:20.842  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-18 19:20:20.842  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 19:20:20.842  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 19:20:20.842  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 19:20:20.843  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.843  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.843  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:20.843  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.844  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:20.844  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 19:20:20.844  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:20.845  5570  5618 D BluetoothLeScanner: could not find callback wrapper
11-18 19:20:20.845  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 19:20:20.845  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:20.845  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.845  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.845  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 19:20:20.845  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.846  5653  5671 D BtGatt.AdvertiseManager: message : 1
11-18 19:20:20.847  5653  5671 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 19:20:20.856  5653  5669 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 19:20:20.856  5653  5669 D BtGatt.GattService: Client app is not null!
,11-18 19:20:20.858  5653  5663 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 19:20:20.859  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 19:20:20.859  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.859  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 19:20:20.860  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:20.860  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.860  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.860  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 19:20:20.860  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 19:20:20.862  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-18 19:20:20.863  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:20.864  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.865  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:20:20.865  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:20.865  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.865  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 19:20:20.865  5570  5570 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 19:20:20.865  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 19:20:20.865  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:20:20.865  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:20:20.866  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:20:20.866  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-18 19:20:20.866  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.866  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 19:20:20.866  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 19:20:20.866  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 19:20:20.866  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.866  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 19:20:20.866  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.868  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.868  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-18 19:20:20.868  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.869  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.869  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 19:20:20.873  5570  5618 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,11-18 19:20:20.874  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 19:20:20.874  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 19:20:20.875  5570  5618 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-18 19:20:20.875  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-18 19:20:20.875  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:20:20.875  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-18 19:20:20.877  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-18 19:20:20.881   929  2985 E native  : do suspend false
,11-18 19:20:20.881  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 19:20:20.881  5570  5618 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 19:20:20.881  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-18 19:20:20.885  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.885  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 19:20:20.885  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:20:20.885  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 19:20:20.886  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-18 19:20:20.888  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-18 19:20:20.889   929  5750 D DhcpClient: Broadcasting DHCPDISCOVER
,11-18 19:20:20.891  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-18 19:20:20.892  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.892  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 19:20:20.892  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 19:20:20.892  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-18 19:20:20.893  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-18 19:20:20.893  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.894  5570  5618 D BluetoothAdapter: STATE_ON
,11-18 19:20:20.897  5653  5689 D BtGatt.GattService: registerClient() - UUID=35c53355-4b9d-416d-86a6-950728287914
,11-18 19:20:20.898  5653  5669 D BtGatt.GattService: onClientRegistered() - UUID=35c53355-4b9d-416d-86a6-950728287914, clientIf=5
,11-18 19:20:20.899  5570  5580 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-18 19:20:20.900  5653  5682 D BtGatt.GattService: start scan with filters
11-18 19:20:20.901   929  5751 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172741, domain null
,11-18 19:20:20.902   929  5750 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172741 seconds
11-18 19:20:20.902   929  5750 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-18 19:20:20.905  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-18 19:20:20.905  5653  5672 D BtGatt.ScanManager: handling starting scan
11-18 19:20:20.905  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.905  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-18 19:20:20.905  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.906  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 19:20:20.906  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:20.906  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.906  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 19:20:20.906  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-18 19:20:20.906  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.906  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.906  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-18 19:20:20.906  5653  5672 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18756d2
11-18 19:20:20.907  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 19:20:20.907  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.909  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:20.909  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-18 19:20:20.909  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.909  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:20.910  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 19:20:20.912  5653  5669 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-18 19:20:20.912  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:20:20.912  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.912  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.912  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.912  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:20.913  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-18 19:20:20.913  5653  5672 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-18 19:20:20.918  5653  5669 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-18 19:20:20.918  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:20:20.919  5653  5672 D BtGatt.ScanManager: Starting BLE batch scan
,11-18 19:20:20.919  5653  5672 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-18 19:20:20.928   929  5751 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-18 19:20:20.928   929  5750 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-18 19:20:20.930   508   923 D CommandListener: Setting iface cfg
,11-18 19:20:20.930  5653  5669 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-18 19:20:20.930  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:20:20.931   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-18 19:20:20.934   929  5750 D DhcpClient: Scheduling renewal in 86399s
11-18 19:20:20.936  5653  5669 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-18 19:20:20.937  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:20:20.940   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-18 19:20:20.940   929  2985 D WifiConfigStore: No blacklist allowed without epno enabled
,11-18 19:20:20.943   929  2985 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-18 19:20:20.943   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-18 19:20:20.945   929  2987 D ConnectivityService: Adding iface wlan0 to network 101
,11-18 19:20:20.968   929  2987 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-18 19:20:20.969   929  2987 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
11-18 19:20:20.970   929  2987 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-18 19:20:20.971   929  2987 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-18 19:20:20.972   929  2987 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-18 19:20:20.977   929  2987 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 19:20:20.980   929  2987 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-18 19:20:20.981   929  2987 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-18 19:20:20.981   929  2987 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-18 19:20:20.981   929  2987 D ConnectivityService:    accepting network in place of null
11-18 19:20:20.981   929  2985 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-18 19:20:20.981   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-18 19:20:20.981   929  2987 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -56]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-18 19:20:21.000   508   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 19:20:21.019   508   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 19:20:21.022   929  2987 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-18 19:20:21.022  3743  3861 W QCNEJ   : |CORE| network available: 101
11-18 19:20:21.022   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-18 19:20:21.024  3743  3861 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-18 19:20:21.024   929  2987 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-18 19:20:21.024   929   946 D Tethering: MasterInitialState.processMessage what=3
11-18 19:20:21.025  3743  3861 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-18 19:20:21.026  3743  3861 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-18 19:20:21.035  4919  4950 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-18 19:20:21.035  4919  4950 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-18 19:20:21.035  4919  4950 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-18 19:20:21.035  4919  4950 E SarControlService: no key has been found,reset the power
11-18 19:20:21.036  4919  4988 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 19:20:21.036  4919  4988 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 19:20:21.036  4919  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 19:20:21.036  4975  4975 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 19:20:21.036  4975  4975 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-18 19:20:21.037  4919  4988 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-18 19:20:21.037  4919  4988 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-18 19:20:21.037  4919  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-18 19:20:21.038  4975  4975 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 19:20:21.038  4975  4975 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-18 19:20:21.041  3689  3689 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-18 19:20:21.043  4975  4994 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8574ea5 HexData = [00000000ec03000000000000ffffffff]
11-18 19:20:21.043  4975  4994 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 19:20:21.043  4975  4994 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-18 19:20:21.045  4975  4975 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 19:20:21.045  4919  4930 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-18 19:20:21.046  3967  3967 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-18 19:20:21.047  4975  4994 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8574ea5 HexData = [00000000ed03000000000000ffffffff]
11-18 19:20:21.047  4975  4994 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 19:20:21.047  4975  4994 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-18 19:20:21.048  4975  4975 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 19:20:21.048  4919  4929 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-18 19:20:21.048  3689  3689 D SystemUpdateService: onCreate
11-18 19:20:21.052  3689  3689 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-18 19:20:21.057   929  5749 D NetlinkSocketObserver: NeighborEvent{elapsedMs=100320, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-18 19:20:21.065  3689  3689 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-18 19:20:21.073  3689  5376 I iu.UploadsManager: num queued entries: 0
,11-18 19:20:21.073  3689  5376 I iu.UploadsManager: num updated entries: 0
11-18 19:20:21.074  3689  5376 I iu.SyncManager: NEXT; no task
,11-18 19:20:21.074  3689  5762 I SystemUpdateService: active receiver: enabled
,11-18 19:20:21.076  3689  3689 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-18 19:20:21.077  3689  3689 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-18 19:20:21.079  5378  5378 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-18 19:20:21.082  5378  5378 D SprintDMHelper: simOperator: 
11-18 19:20:21.082  5378  5378 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 19:20:21.112  3689  5762 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-18 19:20:21.118  3689  5762 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-18 19:20:21.118  3689  5762 I SystemUpdateService: now status is 0 (complete)
11-18 19:20:21.119  3689  5762 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-18 19:20:21.119  3689  5762 I SystemUpdateService: file has been verified
11-18 19:20:21.119  3689  5762 I SystemUpdateService: OTA package size = 21989297
,11-18 19:20:21.124  3689  5762 I SystemUpdateService: showing system update notification
,11-18 19:20:21.132   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-18 19:20:21.133  3689  3689 D SystemUpdateService: onDestroy
,11-18 19:20:21.148   929  5748 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,11-18 19:20:21.262  4295  5767 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-18 19:20:21.262   929  5748 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Nov 2016 18:20:21 GMT], X-Android-Received-Millis=[1479493221261], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479493221232]}
11-18 19:20:21.264   929  2987 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-18 19:20:21.265   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-18 19:20:21.266   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 19:20:21.269   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-18 19:20:21.414  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-18 19:20:21.414  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 19:20:21.415  5570  5570 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 19:20:21.440  5653  5653 D BtGatt.ScanManager: awakened up at time 100704
,11-18 19:20:21.441  5653  5672 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 19:20:21.468  5653  5669 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,11-18 19:20:21.468  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:20:21.468  5653  5669 D BtGatt.GattService: current time is 100732477214
11-18 19:20:21.468  5653  5669 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
11-18 19:20:21.471  5653  5669 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,11-18 19:20:21.475  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 1. Current thread: Thread[main,5,main], id: 1
,11-18 19:20:21.476  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=100582984245}
11-18 19:20:21.476  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=100582984245}
,11-18 19:20:21.819   929  2985 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 6, 8 -> obsolete
,11-18 19:20:21.973  5653  5653 D BtGatt.ScanManager: awakened up at time 101237
,11-18 19:20:21.975  5653  5672 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 19:20:21.990  5653  5669 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 19:20:21.990  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:20:21.991  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-18 19:20:22.022   929  2987 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-18 19:20:23.810   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 19:20:23.912  5570  5618 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-18 19:20:23.913  5570  5618 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-18 19:20:23.913  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-18 19:20:23.913  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.914  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:23.914  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.914  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 19:20:23.914  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 19:20:23.914  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 19:20:23.914  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-18 19:20:23.914  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 19:20:23.914  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 19:20:23.914  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 19:20:23.914  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 19:20:23.914  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 19:20:23.914  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:23.914  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-18 19:20:23.915  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:23.915  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.915  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 19:20:23.915  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 19:20:23.915  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.915  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.916  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.918  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:23.919  5653  5663 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 19:20:23.920  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 19:20:23.922  5653  5672 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 19:20:23.922  5570  5618 D BluetoothAdapter: STATE_ON
,11-18 19:20:23.924  5653  5690 D BtGatt.GattService: stopScan() - queue size =1
,11-18 19:20:23.926  5653  5664 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 19:20:23.926  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 19:20:23.927  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:23.927  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-18 19:20:23.927  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:23.927  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 19:20:23.928  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.928  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.928  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 19:20:23.928  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 19:20:23.928  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-18 19:20:23.928  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-18 19:20:23.929  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.931  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:23.931  5653  5653 D BtGatt.ScanManager: awakened up at time 103195
11-18 19:20:23.934  5653  5663 D BtGatt.GattService: registerClient() - UUID=dfdb9e30-0d5e-41a7-9cfe-aae08f0f52a0
11-18 19:20:23.935  5653  5669 D BtGatt.GattService: onClientRegistered() - UUID=dfdb9e30-0d5e-41a7-9cfe-aae08f0f52a0, clientIf=5
11-18 19:20:23.935  5570  5581 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-18 19:20:23.936  5653  5689 D BtGatt.GattService: start scan with filters
,11-18 19:20:23.941  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-18 19:20:23.941  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.941  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-18 19:20:23.941  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:23.941  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.941  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 19:20:23.941  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:23.941  5570  5618 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 19:20:23.941  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.941  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 19:20:23.941  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-18 19:20:23.941  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 19:20:23.941  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-18 19:20:23.942  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.942  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.942  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 19:20:23.942  5653  5669 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-18 19:20:23.942  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:20:23.943  5653  5669 D BtGatt.GattService: current time is 103206971667
11-18 19:20:23.943  5653  5669 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-18 19:20:23.943  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 19:20:23.943  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 19:20:23.943  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 19:20:23.943  5653  5669 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-18 19:20:23.943  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 19:20:23.943  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-18 19:20:23.943  5570  5774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 19:20:23.943  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 19:20:23.944  5570  5774 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 19:20:23.945  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 19:20:23.945  5570  5618 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 19:20:23.941  5663  5663 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33944]" dev="sockfs" ino=33944 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:20:23.941  5663  5663 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33944]" dev="sockfs" ino=33944 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 19:20:23.947  5570  5774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 19:20:23.952  5653  5669 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-18 19:20:23.952  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:20:23.952  5653  5672 D BtGatt.ScanManager: stopping BLe Batch
11-18 19:20:23.953  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.953  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.954  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.954  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 19:20:23.954  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 19:20:23.954  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 19:20:23.954  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-18 19:20:23.954  5570  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:23.954  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:23.954  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.954  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 19:20:23.954  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 19:20:23.954  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.954  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.955  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.956  5570  5618 D BluetoothAdapter: STATE_ON
,11-18 19:20:23.959  5653  5682 D BtGatt.GattService: registerClient() - UUID=224328ee-3d88-4045-ab4f-ee0973ca71b5
11-18 19:20:23.959  5653  5669 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-18 19:20:23.959  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:20:23.959  5653  5672 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 19:20:23.959  5653  5669 D BtGatt.GattService: onClientRegistered() - UUID=224328ee-3d88-4045-ab4f-ee0973ca71b5, clientIf=6
11-18 19:20:23.960  5570  5580 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-18 19:20:23.961  5653  5671 D BtGatt.AdvertiseManager: message : 0
,11-18 19:20:23.964  5653  5671 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 19:20:23.964  5653  5669 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-18 19:20:23.964  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:20:23.967  5653  5672 D BtGatt.ScanManager: handling starting scan
,11-18 19:20:23.974  5653  5669 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-18 19:20:23.978  5653  5669 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-18 19:20:23.978  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:20:23.978  5653  5672 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-18 19:20:23.983  5653  5669 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-18 19:20:23.983  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.983  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.983  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 19:20:23.984  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.984  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:23.984  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.984  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.984  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.984  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.984  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.984  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.984  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-18 19:20:23.984  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-18 19:20:23.984  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-18 19:20:23.985  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 19:20:23.986  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.988  5653  5669 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-18 19:20:23.988  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:20:23.988  5653  5672 D BtGatt.ScanManager: Starting BLE batch scan
11-18 19:20:23.988  5653  5672 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-18 19:20:23.989  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.989  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:23.989  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:23.989  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 19:20:23.989  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 1. Current thread: Thread[main,5,main], id: 1
,11-18 19:20:23.990  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=101407191874}
,11-18 19:20:23.990  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=101407191874}
11-18 19:20:23.991  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
11-18 19:20:23.991  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-18 19:20:23.991  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.991  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:23.991  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 19:20:23.991  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-18 19:20:23.991  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.991  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:23.991  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.992  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-18 19:20:23.992  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-18 19:20:23.992  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.992  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.992  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,11-18 19:20:23.992  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.994  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.994  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-18 19:20:23.995  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.995  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.995  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:23.995  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-18 19:20:23.998  5653  5669 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-18 19:20:23.998  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:20:24.003  5653  5669 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-18 19:20:24.004  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:20:24.496  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-18 19:20:24.496  5570  5570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-18 19:20:24.496  5570  5570 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 19:20:26.993  5570  5618 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-18 19:20:26.993  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 19:20:26.993  5570  5618 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 19:20:26.993  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 19:20:26.994  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-18 19:20:26.994  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 19:20:26.994  5570  5774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 19:20:26.994  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-18 19:20:26.994  5570  5774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 19:20:26.994  5570  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 19:20:26.994  5570  5774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 19:20:26.995  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 19:20:26.995  5570  5570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 19:20:26.995  5570  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f70615e removed from the list
,11-18 19:20:26.995  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 19:20:26.995  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 19:20:26.995  5570  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 19:20:26.995  5570  5570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 19:20:26.995  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 19:20:26.995  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-18 19:20:26.996  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:26.996  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:26.996  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:26.996  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-18 19:20:26.997  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:26.998  5570  5618 D BluetoothAdapter: STATE_ON
11-18 19:20:26.999  5653  5664 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 19:20:27.000  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 19:20:27.001  5653  5672 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 19:20:27.003  5570  5618 D BluetoothAdapter: STATE_ON
,11-18 19:20:27.004  5653  5690 D BtGatt.GattService: stopScan() - queue size =1
,11-18 19:20:27.006  5653  5689 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 19:20:27.007  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 19:20:27.007  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:27.008  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-18 19:20:27.008  5653  5653 D BtGatt.ScanManager: awakened up at time 106271
11-18 19:20:27.008  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:27.008  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:27.008  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:27.008  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 19:20:27.009  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:27.011  5653  5671 D BtGatt.AdvertiseManager: message : 1
,11-18 19:20:27.012  5653  5671 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-18 19:20:27.024  5653  5669 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-18 19:20:27.024  5653  5669 D BtGatt.GattService: Client app is not null!
11-18 19:20:27.025  5653  5663 D BtGatt.GattService: unregisterClient() - clientIf=6
11-18 19:20:27.026  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 19:20:27.026  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:27.026  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 19:20:27.026  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:27.026  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:27.026  5570  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:27.026  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 19:20:27.026  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 19:20:27.027  5570  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-18 19:20:27.029  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:27.031  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-18 19:20:27.031  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:20:27.031  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:27.031  5570  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-18 19:20:27.031  5570  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d38493f removed from the list
11-18 19:20:27.031  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:20:27.031  5570  5618 D io.jxcore.node.ConnectivityMonitor: stop
11-18 19:20:27.031  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 19:20:27.031  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 19:20:27.031  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:27.031  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 19:20:27.031  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-18 19:20:27.032  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:20:27.032  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 19:20:27.032  5570  5570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-18 19:20:27.032  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 19:20:27.033  5570  5618 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-18 19:20:27.033  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-18 19:20:27.033  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 19:20:27.033  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 19:20:27.033  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 19:20:27.033  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-18 19:20:27.033  5570  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-18 19:20:27.033  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 19:20:27.033  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:27.033  5570  5570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 19:20:27.033  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:27.033  5570  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-18 19:20:27.034  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 19:20:27.034  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 19:20:27.034  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 19:20:27.034  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 19:20:27.034  5570  5570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 19:20:27.034  5570  5618 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,11-18 19:20:27.034  5570  5570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 19:20:27.036  5570  5618 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-18 19:20:27.037  5653  5669 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
11-18 19:20:27.037  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:20:27.037  5570  5618 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-18 19:20:27.037  5653  5669 D BtGatt.GattService: current time is 106301698063
,11-18 19:20:27.038  5653  5669 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -89, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-18 19:20:27.038  5653  5669 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-18 19:20:27.038  5570  5618 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-18 19:20:27.038  5653  5669 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-18 19:20:27.038  5653  5669 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-18 19:20:27.038  5653  5669 E BtGatt.ContextMap: Context not found for ID 5
11-18 19:20:27.039  5570  5618 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-18 19:20:27.040  5570  5618 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-18 19:20:27.041  5570  5618 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-18 19:20:27.041  5570  5618 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
11-18 19:20:27.047  5653  5669 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-18 19:20:27.047  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:20:27.047  5653  5672 D BtGatt.ScanManager: stopping BLe Batch
,11-18 19:20:27.052  5653  5669 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-18 19:20:27.052  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 19:20:27.052  5653  5672 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 19:20:27.056  5653  5669 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 19:20:27.056  5653  5669 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 19:20:27.535  5570  5570 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 19:20:28.985   929  2987 D ConnectivityService: handlePromptUnvalidated 101
,11-18 19:20:29.046  5570  5618 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-18 19:20:29.194  5570  5776 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 151, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 19:20:29.194  5570  5776 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:20:30.013  5570  5776 W !!      : call onHalfStreamCopied
,11-18 19:20:30.013  5570  5776 I testCopyDataAndClose: closing input stream
,11-18 19:20:30.796  5570  5776 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 151, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 19:20:30.796  5570  5776 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 19:20:30.796  5570  5776 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 19:20:30.796  5570  5776 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:20:30.796  5570  5776 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 19:20:30.796  5570  5776 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 19:20:30.796  5570  5776 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 19:20:30.796  5570  5776 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 19:20:30.796  5570  5776 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 19:20:30.796  5570  5776 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 151, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 19:20:30.796  5570  5776 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 19:20:32.097   929  2985 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,11-18 19:20:34.816   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-18 19:20:34.817   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-18 19:20:34.870  5570  5618 I StreamCopyingThreadTest: Starting test: testRun
,11-18 19:20:34.875  5570  5777 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:20:34.875  5570  5777 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:20:39.818   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:39.883  5570  5778 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-18 19:20:39.885  5570  5618 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-18 19:20:40.042  5570  5779 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 19:20:40.042  5570  5779 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:20:40.819   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:41.679  5570  5779 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 157, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 19:20:41.679  5570  5779 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 19:20:41.679  5570  5779 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 19:20:41.679  5570  5779 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:20:41.679  5570  5779 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 19:20:41.679  5570  5779 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 19:20:41.679  5570  5779 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 19:20:41.679  5570  5779 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 19:20:41.679  5570  5779 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 19:20:41.679  5570  5779 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 19:20:41.679  5570  5779 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 19:20:41.820   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:42.821   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:43.822   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:44.823   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-18 19:20:45.797  5570  5618 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-18 19:20:45.800  5570  5780 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:20:45.800  5570  5780 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:20:45.800  5570  5780 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:20:45.800  5570  5780 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 19:20:45.801  5570  5780 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 19:20:45.801  5570  5780 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 19:20:45.801  5570  5780 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-18 19:20:45.801  5570  5780 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 19:20:45.801  5570  5780 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 19:20:45.801  5570  5780 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 19:20:45.801  5570  5780 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-18 19:20:45.801  5570  5780 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:20:45.801  5570  5780 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-18 19:20:45.803  5570  5618 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-18 19:20:45.803  5570  5618 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-18 19:20:45.804  5570  5618 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-18 19:20:45.806  5570  5781 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:20:45.806  5570  5781 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 19:20:45.807  5570  5781 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 163, thread name: My test thread name): Test exception.
11-18 19:20:45.807  5570  5781 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:20:45.807  5570  5781 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 19:20:45.808  5570  5781 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-18 19:20:45.808  5570  5781 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 19:20:45.808  5570  5781 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 19:20:45.809  5570  5618 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-18 19:20:45.810  5570  5618 E com.test.thalitest.ThaliTestRunner: 
11-18 19:20:45.810  5570  5618 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 19:20:45.810  5570  5618 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:20:45.811  5570,  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTe,stRunner: Expected: is <true>
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.,java:268)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:20:45.811  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
,11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
,11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:20:45.812  5570  5618 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 19:20:45.815  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG UnitTest_app: 'Running unit tests'
11-18 19:20:45.815  5570  5618 I jxcore-log: 
11-18 19:20:45.815  5570  5618 I jxcore-log: *Native tests were executed*
11-18 19:20:45.815  5570  5618 I jxcore-log: 
11-18 19:20:45.816  5570  5618 I jxcore-log: Total number of executed tests:  82
11-18 19:20:45.816  5570  5618 I jxcore-log: 
11-18 19:20:45.816,  5570  5618 I jxcore-log: Number of passed tests:  79
11-18 19:20:45.816  5570  5618 I jxcore-log: 
11-18 19:20:45.816  5570  5618 I jxcore-log: Number of failed tests:  3
11-18 19:20:45.816  5570  5618 I jxcore-log: 
11-18 19:20:45.816  5570  5618 I jxcore-log: Number of ignored tests:  0
11-18 19:20:45.816  5570  5618 I jxcore-log: 
11-18 19:20:45.816  5570  5618 I jxcore-log: Total duration:  39091
11-18 19:20:45.816  5570  5618 I jxcore-log: 
11-18 19:20:45.816  5570  5618 I jxcore-log: Failed to execute UT.
11-18 19:20:45.816  5570  5618 I jxcore-log: 
11-18 19:20:45.817  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-18 19:20:45.817  5570  5618 I jxcore-log: 
11-18 19:20:45.818  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-18 19:20:45.818  5570  5618 I jxcore-log: 
11-18 19:20:45.821  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 19:20:45.821  5570  5618 I jxcore-log: 
11-18 19:20:45.821  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:20:45.821  5570  5618 I jxcore-log: 
11-18 19:20:45.822  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 19:20:45.822  5570  5618 I jxcore-log: 
11-18 19:20:45.823  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:20:45.823  5570  5618 I jxcore-log: 
11-18 19:20:45.824  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 19:20:45.824  5570  5618 I jxcore-log: 
11-18 19:20:45.824  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 19:20:45.824  5570  5618 I jxcore-log: 
11-18 19:20:45.824  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:20:45.824  5570  5618 I jxcore-log: 
11-18 19:20:45.825  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 19:20:45.825  5570  5618 I jxcore-log: 
11-18 19:20:45.825  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 19:20:45.825  5570  5618 I jxcore-log: 
11-18 19:20:45.825  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:20:45.825  5570  5618 I jxcore-log: 
11-18 19:20:45.825  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 19:20:45.825  5570  5618 I jxcore-log: 
11-18 19:20:45.825  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 19:20:45.825  5570  5618 I jxcore-log: 
11-18 19:20:45.826  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:,20:45.826  5570  5618 I jxcore-log: 
11-18 19:20:45.826  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 19:20:45.826  5570  5618 I jxcore-log: 
11-18 19:20:45.826  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:20:45.826  5570  5618 I jxcore-log: 
11-18 19:20:45.826  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 19:20:45.826  5570  5618 I jxcore-log: 
11-18 19:20:45.827  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:20:45.827  5570  5618 I jxcore-log: 
11-18 19:20:45.827  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 19:20:45.827  5570  5618 I jxcore-log: 
11-18 19:20:45.827  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:20:45.827  5570  5618 I jxcore-log: 
11-18 19:20:45.827  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 19:20:45.827  5570  5618 I jxcore-log: 
,11-18 19:20:45.827  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:20:45.827  5570  5618 I jxcore-log: 
11-18 19:20:45.828  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 19:20:45.828  5570  5618 I jxcore-log: 
11-18 19:20:45.828  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:20:45.828  5570  5618 I jxcore-log: 
11-18 19:20:45.828  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-18 19:20:45.828  5570  5618 I jxcore-log: 
11-18 19:20:45.828  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:20:45.828  5570  5618 I jxcore-log: 
,11-18 19:20:45.829  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-18 19:20:45.829  5570  5618 I jxcore-log: 
11-18 19:20:45.829  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 19:20:45.829  5570  5618 I jxcore-log: 
11-18 19:20:45.829  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 19:20:45.829  5570  5618 I jxcore-log: 
11-18 19:20:45.830  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 19:20:45.830  5570  5618 I jxcore-log: 
11-18 19:20:45.831  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:20:45.831  5570  5618 I jxcore-log: ,
11-18 19:20:45.831  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-18 19:20:45.831  5570  5618 I jxcore-log: 
11-18 19:20:45.831  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 19:20:45.831  5570  5618 I jxcore-log: 
11-18 19:20:45.831  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:20:45.831  5570  5618 I jxcore-log: 
11-18 19:20:45.832  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-18 19:20:45.832  5570  5618 I jxcore-log: 
,11-18 19:20:45.832  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 19:20:45.832  5570  5618 I jxcore-log: 
11-18 19:20:45.832  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:20:45.832  5570  5618 I jxcore-log: 
11-18 19:20:45.832  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 19:20:45.832  5570  5618 I jxcore-log: 
11-18 19:20:45.832  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 19:20:45.832  5570  5618 I jxcore-log: 
,11-18 19:20:45.837  5570  5570 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-18 19:20:45.837  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-18 19:20:45.837  5570  5618 I jxcore-log: 
11-18 19:20:45.837  5570  5618 I jxcore-log: 2016-11-18 18:20:45 - WARN testUtils: 'myNameCallback not set!'
11-18 19:20:45.837  5570  5618 I jxcore-log: 
,11-18 19:20:45.914  3651  3846 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-18 19:20:45.915  3651  3846 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-18 19:20:45.944  3577  3577 I ConfigService: onCreate
,11-18 19:20:47.886  5570  5618 I jxcore-log: 2016-11-18 18:20:47 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-18 19:20:47.886  5570  5618 I jxcore-log: 
,11-18 19:20:47.888  5570  5618 I jxcore-log: 2016-11-18 18:20:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-18 19:20:47.888  5570  5618 I jxcore-log: 
,11-18 19:20:47.899   929  5749 D NetlinkSocketObserver: NeighborEvent{elapsedMs=127163, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-18 19:20:48.214  5570  5618 I jxcore-log: 2016-11-18 18:20:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-18 19:20:48.214  5570  5618 I jxcore-log: 
,11-18 19:20:48.227  5570  5618 I jxcore-log: 2016-11-18 18:20:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-18 19:20:48.227  5570  5618 I jxcore-log: 
,11-18 19:20:49.323  5570  5618 I jxcore-log: 2016-11-18 18:20:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-18 19:20:49.323  5570  5618 I jxcore-log: 
,11-18 19:20:49.491  5570  5618 I jxcore-log: 2016-11-18 18:20:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-18 19:20:49.491  5570  5618 I jxcore-log: 
,11-18 19:20:49.497  5570  5618 I jxcore-log: 2016-11-18 18:20:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-18 19:20:49.497  5570  5618 I jxcore-log: 
,11-18 19:20:49.509  5570  5618 I jxcore-log: 2016-11-18 18:20:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-18 19:20:49.509  5570  5618 I jxcore-log: 
,11-18 19:20:49.824   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:49.993  5570  5618 I jxcore-log: 2016-11-18 18:20:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-18 19:20:49.993  5570  5618 I jxcore-log: 
,11-18 19:20:50.038  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-18 19:20:50.038  5570  5618 I jxcore-log: 
,11-18 19:20:50.051  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-18 19:20:50.051  5570  5618 I jxcore-log: 
,11-18 19:20:50.055  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-18 19:20:50.055  5570  5618 I jxcore-log: 
,11-18 19:20:50.333  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-18 19:20:50.333  5570  5618 I jxcore-log: 
,11-18 19:20:50.457  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-18 19:20:50.457  5570  5618 I jxcore-log: 
,11-18 19:20:50.825   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:50.831  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-18 19:20:50.831  5570  5618 I jxcore-log: 
,11-18 19:20:50.838  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-18 19:20:50.838  5570  5618 I jxcore-log: 
,11-18 19:20:50.843  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-18 19:20:50.843  5570  5618 I jxcore-log: 
,11-18 19:20:50.846  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-18 19:20:50.846  5570  5618 I jxcore-log: 
,11-18 19:20:50.851  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-18 19:20:50.851  5570  5618 I jxcore-log: 
,11-18 19:20:50.888  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-18 19:20:50.888  5570  5618 I jxcore-log: 
,11-18 19:20:50.894  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-18 19:20:50.894  5570  5618 I jxcore-log: 
,11-18 19:20:50.917  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-18 19:20:50.917  5570  5618 I jxcore-log: 
,11-18 19:20:50.954  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-18 19:20:50.954  5570  5618 I jxcore-log: 
,11-18 19:20:50.971  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-18 19:20:50.971  5570  5618 I jxcore-log: 
,11-18 19:20:50.978  3577  3577 I ConfigService: onDestroy
,11-18 19:20:50.978  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-18 19:20:50.978  5570  5618 I jxcore-log: 
,11-18 19:20:50.994  5570  5618 I jxcore-log: 2016-11-18 18:20:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-18 19:20:50.994  5570  5618 I jxcore-log: 
,11-18 19:20:51.007  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerConnectionInformation.js'
11-18 19:20:51.007  5570  5618 I jxcore-log: 
,11-18 19:20:51.017  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-18 19:20:51.017  5570  5618 I jxcore-log: 
,11-18 19:20:51.022  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-18 19:20:51.022  5570  5618 I jxcore-log: 
,11-18 19:20:51.027  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-18 19:20:51.027  5570  5618 I jxcore-log: 
,11-18 19:20:51.039  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-18 19:20:51.039  5570  5618 I jxcore-log: 
,11-18 19:20:51.054  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-18 19:20:51.054  5570  5618 I jxcore-log: 
,11-18 19:20:51.067  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-18 19:20:51.067  5570  5618 I jxcore-log: 
,11-18 19:20:51.077  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-18 19:20:51.077  5570  5618 I jxcore-log: 
,11-18 19:20:51.089  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-18 19:20:51.089  5570  5618 I jxcore-log: 
,11-18 19:20:51.098  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-18 19:20:51.098  5570  5618 I jxcore-log: 
,11-18 19:20:51.110  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-18 19:20:51.110  5570  5618 I jxcore-log: 
,11-18 19:20:51.118  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-18 19:20:51.118  5570  5618 I jxcore-log: 
,11-18 19:20:51.124  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-18 19:20:51.124  5570  5618 I jxcore-log: 
,11-18 19:20:51.143  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-18 19:20:51.143  5570  5618 I jxcore-log: 
,11-18 19:20:51.148  5570  5618 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-18 19:20:51.148  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - INFO testUtils: 'BLE multiple advertisement supported'
11-18 19:20:51.148  5570  5618 I jxcore-log: 
,11-18 19:20:51.220  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:51.220  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:51.220  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:51.220  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:51.220  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:51.220  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:51.220  5570  5618 I jxcore-log: 
,11-18 19:20:51.468  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:51.468  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:51.468  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:51.468  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:51.468  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:51.468  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:51.468  5570  5618 I jxcore-log: 
,11-18 19:20:51.473  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:51.473  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:51.473  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:51.473  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:51.473  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:51.473  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:51.473  5570  5618 I jxcore-log: 
,11-18 19:20:51.827   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:51.830  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:51.830  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:51.830  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:51.830  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:51.830  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:51.830  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:51.830  5570  5618 I jxcore-log: 
,11-18 19:20:51.834  5570  5618 I jxcore-log: 2016-11-18 18:20:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:51.834  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:51.834  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:51.834  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:51.834  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:51.834  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:51.834  5570  5618 I jxcore-log: 
,11-18 19:20:52.473  5570  5618 I jxcore-log: 2016-11-18 18:20:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:52.473  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:52.473  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:52.473  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:52.473  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:52.473  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:52.473  5570  5618 I jxcore-log: 
,11-18 19:20:52.477  5570  5618 I jxcore-log: 2016-11-18 18:20:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:52.477  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:52.477  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:52.477  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:52.477  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:52.477  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:52.477  5570  5618 I jxcore-log: 
,11-18 19:20:52.828   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:53.510  5570  5618 I jxcore-log: 2016-11-18 18:20:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:53.510  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:53.510  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:53.510  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:53.510  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:53.510  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:53.510  5570  5618 I jxcore-log: 
,11-18 19:20:53.517  5570  5618 I jxcore-log: 2016-11-18 18:20:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:53.517  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:53.517  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:53.517  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:53.517  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:53.517  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:53.517  5570  5618 I jxcore-log: 
,11-18 19:20:53.829   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:20:54.554  5570  5618 I jxcore-log: 2016-11-18 18:20:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:54.554  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:54.554  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:54.554  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:54.554  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:54.554  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:54.554  5570  5618 I jxcore-log: 
,11-18 19:20:54.556  5570  5618 I jxcore-log: 2016-11-18 18:20:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:54.556  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:54.556  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:54.556  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:54.556  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:54.556  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:54.556  5570  5618 I jxcore-log: 
,11-18 19:20:54.830   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-18 19:20:55.589  5570  5618 I jxcore-log: 2016-11-18 18:20:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:55.589  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:55.589  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:55.589  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:55.589  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:55.589  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:55.589  5570  5618 I jxcore-log: 
,11-18 19:20:55.592  5570  5618 I jxcore-log: 2016-11-18 18:20:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:55.592  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:55.592  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:55.592  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:55.592  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:55.592  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:55.592  5570  5618 I jxcore-log: 
,11-18 19:20:56.213   929  5749 D NetlinkSocketObserver: NeighborEvent{elapsedMs=135477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-18 19:20:56.624  5570  5618 I jxcore-log: 2016-11-18 18:20:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:56.624  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:56.624  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:56.624  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:56.624  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:56.624  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:56.624  5570  5618 I jxcore-log: 
,11-18 19:20:56.628  5570  5618 I jxcore-log: 2016-11-18 18:20:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:56.628  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:56.628  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:56.628  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:56.628  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:56.628  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:56.628  5570  5618 I jxcore-log: 
,11-18 19:20:57.661  5570  5618 I jxcore-log: 2016-11-18 18:20:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:57.661  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:57.661  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:57.661  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:57.661  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:57.661  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:57.661  5570  5618 I jxcore-log: 
,11-18 19:20:57.665  5570  5618 I jxcore-log: 2016-11-18 18:20:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:57.665  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:57.665  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:57.665  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:57.665  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:57.665  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:57.665  5570  5618 I jxcore-log: 
,11-18 19:20:58.698  5570  5618 I jxcore-log: 2016-11-18 18:20:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:58.698  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:58.698  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:58.698  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:58.698  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:58.698  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:58.698  5570  5618 I jxcore-log: 
,11-18 19:20:58.704  5570  5618 I jxcore-log: 2016-11-18 18:20:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:58.704  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:58.704  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:58.704  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:58.704  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:58.704  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:58.704  5570  5618 I jxcore-log: 
,11-18 19:20:59.772  5570  5618 I jxcore-log: 2016-11-18 18:20:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:59.772  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:59.772  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:59.772  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:59.772  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:59.772  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:59.772  5570  5618 I jxcore-log: 
,11-18 19:20:59.776  5570  5618 I jxcore-log: 2016-11-18 18:20:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:20:59.776  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:20:59.776  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:20:59.776  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:20:59.776  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:20:59.776  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:20:59.776  5570  5618 I jxcore-log: 
,11-18 19:21:00.808  5570  5618 I jxcore-log: 2016-11-18 18:21:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:21:00.808  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:21:00.808  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:21:00.808  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:21:00.808  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:21:00.808  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:21:00.808  5570  5618 I jxcore-log: 
,11-18 19:21:00.814  5570  5618 I jxcore-log: 2016-11-18 18:21:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:21:00.814  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:21:00.814  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:21:00.814  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:21:00.814  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:21:00.814  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:21:00.814  5570  5618 I jxcore-log: 
,11-18 19:21:00.947   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-18 19:21:01.843  5570  5618 I jxcore-log: 2016-11-18 18:21:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:21:01.843  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:21:01.843  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:21:01.843  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:21:01.843  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:21:01.843  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:21:01.843  5570  5618 I jxcore-log: 
,11-18 19:21:01.847  5570  5618 I jxcore-log: 2016-11-18 18:21:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:21:01.847  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:21:01.847  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:21:01.847  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:21:01.847  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:21:01.847  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:21:01.847  5570  5618 I jxcore-log: 
,11-18 19:21:02.876  5570  5618 I jxcore-log: 2016-11-18 18:21:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:21:02.876  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:21:02.876  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:21:02.876  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:21:02.876  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:21:02.876  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:21:02.876  5570  5618 I jxcore-log: 
,11-18 19:21:02.880  5570  5618 I jxcore-log: 2016-11-18 18:21:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:21:02.880  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:21:02.880  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:21:02.880  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:21:02.880  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:21:02.880  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:21:02.880  5570  5618 I jxcore-log: 
,11-18 19:21:03.104   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 19:21:03.909  5570  5618 I jxcore-log: 2016-11-18 18:21:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:21:03.909  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:21:03.909  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:21:03.909  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:21:03.909  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:21:03.909  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:21:03.909  5570  5618 I jxcore-log: 
,11-18 19:21:03.913  5570  5618 I jxcore-log: 2016-11-18 18:21:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:21:03.913  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:21:03.913  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:21:03.913  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:21:03.913  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:21:03.913  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:21:03.913  5570  5618 I jxcore-log: 
,11-18 19:21:04.831   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:21:04.948  5570  5618 I jxcore-log: 2016-11-18 18:21:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 19:21:04.948  5570  5618 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 19:21:04.948  5570  5618 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 19:21:04.948  5570  5618 I jxcore-log: emit@events.js:82:1
11-18 19:21:04.948  5570  5618 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 19:21:04.948  5570  5618 I jxcore-log: emit@events.js:82:1'
11-18 19:21:04.948  5570  5618 I jxcore-log: 
,11-18 19:21:04.959  5570  5618 E jxcore  : Error!: error is undefined
11-18 19:21:04.959  5570  5618 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-18 19:21:04.963  5570  5618 I jxcore-log: 2016-11-18 18:21:04 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-18 19:21:04.963  5570  5618 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-18 19:21:04.963  5570  5618 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-18 19:21:04.963  5570  5618 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-18 19:21:04.963  5570  5618 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-18 19:21:04.963  5570  5618 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-18 19:21:04.963  5570  5618 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-18 19:21:04.963  5570  5618 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-18 19:21:04.965  5570  5618 I jxcore-log: 2016-11-18 18:21:04 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-18 19:21:04.965  5570  5618 I jxcore-log: 
11-18 19:21:04.966  5570  5618 E jxcore-log: TypeError: 
11-18 19:21:04.966  5570  5618 E jxcore-log: error is undefined
11-18 19:21:04.966  5570  5618 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-18 19:21:04.966  5570  5618 E jxcore-log: 
,11-18 19:21:05.035   929  2931 W InputDispatcher: channel '299ef6f com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-18 19:21:05.035   929  2931 E InputDispatcher: channel '299ef6f com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-18 19:21:05.046   929  3833 D GraphicsStats: Buffer count: 2
,11-18 19:21:05.046   929  3799 I WindowState: WIN DEATH: Window{299ef6f u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-18 19:21:05.046   929  2986 D WifiService: Client connection lost with reason: 4
11-18 19:21:05.046   929  3799 W InputDispatcher: Attempted to unregister already unregistered input channel '299ef6f com.test.thalitest/com.test.thalitest.MainActivity (server)'
,11-18 19:21:05.052   929  3417 I ActivityManager: Process com.test.thalitest (pid 5570) has died
,11-18 19:21:05.053   929  3417 W ActivityManager: Force removing ActivityRecord{e89d297 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
11-18 19:21:05.047   528   528 I Zygote  : Process 5570 exited cleanly (139)
,11-18 19:21:05.113   929  3833 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5570 uid 10077
,11-18 19:21:05.117  3651  3651 I Keyboard.Facilitator: onFinishInput()
,11-18 19:21:05.111  3833  3833 W Binder_A: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[27532]" dev="sockfs" ino=27532 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 19:21:05.111  3833  3833 W Binder_A: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[27532]" dev="sockfs" ino=27532 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 19:21:05.185  3967  5788 I MicroRecognitionRnrImpl: Starting detection.
,11-18 19:21:05.187  3967  5789 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@30378ca
,11-18 19:21:05.190   513  5791 I AudioFlinger: AudioFlinger's thread 0xf1d40000 ready to run
,11-18 19:21:05.193   513  2993 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-18 19:21:05.196  3967  5789 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@30378ca
,11-18 19:21:05.205   513  5791 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-18 19:21:05.205   513  5791 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-18 19:21:05.205   513  5791 I ACDB-LOADER: ACDB AFE returned = -19
,11-18 19:21:05.206   513  5791 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
,11-18 19:21:05.206   513  5791 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-18 19:21:05.206   513  5791 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-18 19:21:05.214   513  5791 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-18 19:21:05.295  3967  3967 I HotwordWorkerImpl: onReady
,11-18 19:21:05.408  5783  5783 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-18 19:21:05.412  5783  5783 D AndroidRuntime: CheckJNI is OFF
,11-18 19:21:05.435  5783  5783 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-18 19:21:05.466  5783  5783 I Radio-JNI: register_android_hardware_Radio DONE
,11-18 19:21:05.482  5783  5783 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-18 19:21:05.494   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-18 19:21:05.650  3801  4048 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-18 19:21:05.660   929   952 I art     : Starting a blocking GC Explicit
,11-18 19:21:05.754   929   952 I art     : Explicit concurrent mark sweep GC freed 77740(4MB) AllocSpace objects, 22(752KB) LOS objects, 33% free, 29MB/43MB, paused 1.708ms total 93.364ms
,11-18 19:21:05.775   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-18 19:21:05.778  5783  5783 I art     : System.exit called, status: 0
,11-18 19:21:05.778  5783  5783 I AndroidRuntime: VM exiting with result code 0.
,11-18 19:21:05.792   929   952 I ActivityManager: Start proc 5802:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-18 19:21:05.792   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-18 19:21:05.812  5653  5653 D BluetoothMapAppObserver: onReceive
11-18 19:21:05.813  5653  5653 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-18 19:21:05.820  3651  3651 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-18 19:21:05.821  4018  4159 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-18 19:21:05.826   929  2932 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-18 19:21:05.829  3651  5814 I Keyboard.Facilitator.DecoderInitializer: run()
11-18 19:21:05.831   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 19:21:05.835  3651  5814 I Decoder : createOrResetDecoder
,11-18 19:21:05.842  3771  3771 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-18 19:21:05.863  3401  5816 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-18 19:21:05.874    29    29 W kworker/3:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 19:21:05.881    29    29 W kworker/3:1: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 19:21:05.888    29    29 W kworker/3:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-18 19:21:05.891  3577  3577 I ConfigService: onCreate
,11-18 19:21:05.903   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-18 19:21:05.909  3577  3577 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-18 19:21:05.910  3651  5814 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-18 19:21:05.910  3577  3577 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-18 19:21:05.911  3577  3577 E AndroidRuntime: FATAL EXCEPTION: main
11-18 19:21:05.911  3577  3577 E AndroidRuntime: Process: com.google.process.gapps, PID: 3577
11-18 19:21:05.911  3577  3577 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-18 19:21:05.911  3577  3577 E AndroidRuntime: 	... 8 more
11-18 19:21:05.912  3801  3918 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-18 19:21:05.912   929   941 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-18 19:21:05.913   929   941 E PackageManager: Failed to write settings, restoring backup
11-18 19:21:05.913   929   941 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-18 19:21:05.913   929   941 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-18 19:21:05.913   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-18 19:21:05.913   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-18 19:21:05.913   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.hand,leMessage(Settings.java:4830)
11-18 19:21:05.913   929   941 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 19:21:05.913   929   941 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:21:05.913   929   941 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 19:21:05.917   929   942 E DropBoxManagerService: Can't write: system_server_wtf
11-18 19:21:05.917   929   942 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-18 19:21:05.917   929   942 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 19:21:05.917   929   942 E DropBoxManagerService: 	... 13 more
11-18 19:21:05.918   929  5822 E DropBoxManagerService: Can't write: system_app_crash
11-18 19:21:05.918   929  5822 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
11-18 19:21:05.918   929  5822 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 19:21:05.918   929  5822 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 19:21:05.918   929  5822 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 19:21:05.918   929  5822 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 19:21:05.918   929  5822 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 19:21:05.918   929  5822 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 19:21:05.918   929  5822 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 19:21:05.918   929  5822 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 19:21:05.918   929  5822 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 19:21:05.918   929  5822 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 19:21:05.918   929  5822 E DropBoxManagerService: 	... 5 more
11-18 19:21:05.927   929  3811 I ActivityManager: Start proc 5823:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-18 19:21:05.927  3801  3918 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-18 19:21:05.927  3801  3918 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3801
11-18 19:21:05.927  3801  3918 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 19:21:05.927  3801  3918 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 19:21:05.927  3801  3918 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 19:21:05.927  3801  3918 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 19:21:05.927  3801  3918 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 19:21:05.927  3801  3918 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 19:21:05.927  3801  3918 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-18 19:21:05.927  3801  3918 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-18 19:21:05.927  3801  3918 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 19:21:05.927  3801  3918 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 19:21:05.927  3801  3918 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:21:05.927  3801  3918 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 19:21:05.942  3401  3426 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj879123909) - 
11-18 19:21:05.944   403   403 W Binder_2: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[34827]" dev="sockfs" ino=34827 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 19:21:05.944   403   403 W Binder_2: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[34827]" dev="sockfs" ino=34827 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 19:21:05.948   746   746 W Binder_4: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[32556]" dev="sockfs" ino=32556 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 19:21:05.948   746   746 W Binder_4: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[32556]" dev="sockfs" ino=32556 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 19:21:05.951   929  5835 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-18 19:21:05.957   929  5836 E DropBoxManagerService: Can't write: system_app_crash
11-18 19:21:05.957   929  5836 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
11-18 19:21:05.957   929  5836 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 19:21:05.957   929  5836 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 19:21:05.957   929  5836 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 19:21:05.957   929  5836 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 19:21:05.957   929  5836 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 19:21:05.957   929  5836 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 19:21:05.957   929  5836 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 19:21:05.957   929  5836 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 19:21:05.957   929  5836 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 19:21:05.957   929  5836 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 19:21:05.957   929  5836 E DropBoxManagerService: 	... 5 more
11-18 19:21:05.961   929  3753 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-18 19:21:05.965  3967  3980 W SearchService: Abort, client detached.
11-18 19:21:05.967  3967  3967 I HotwordDetector: Closing mic
11-18 19:21:05.967  3967  4185 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@30378ca
11-18 19:21:05.968  3967  5789 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-18 19:21:05.984  3401  5816 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-18 19:21:05.985  3401  5816 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-18 19:21:05.985  3401  5816 E AndroidRuntime: Process: android.process.acore, PID: 3401
11-18 19:21:05.985  3401  5816 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 19:21:05.985  3401  5816 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 19:21:05.987  3401  3426 I Process : Sending signal. PID: 3401 SIG: 9
11-18 19:21:05.990   929  5838 E DropBoxManagerService: Can't write: system_app_crash
11-18 19:21:05.990   929  5838 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-18 19:21:05.990   929  5838 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 19:21:05.990   929  5838 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 19:21:05.990   929  5838 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 19:21:05.990   929  5838 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 19:21:05.990   929  5838 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 19:21:05.990   929  5838 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 19:21:05.990   929  5838 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 19:21:05.990   929  5838 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 19:21:05.990   929  5838 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 19:21:05.990   929  5838 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 19:21:05.990   929  5838 E DropBoxManagerService: 	... 5 more
,11-18 19:21:06.007   378   378 E lowmemorykiller: Error writing /proc/3401/oom_score_adj; errno=22
,11-18 19:21:06.020  3651  5814 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-18 19:21:06.022  3651  5814 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-18 19:21:06.022  3651  5814 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-18 19:21:06.030   513  5791 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-18 19:21:06.031   513  5791 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-18 19:21:06.034   929  3833 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
11-18 19:21:06.035   513  5791 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-18 19:21:06.035   513  5791 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-18 19:21:06.036   513  2993 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-18 19:21:06.038  3967  5788 I MicroRecognitionRnrImpl: Detection finished
11-18 19:21:06.040  3967  4202 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-18 19:21:06.044  3651  5814 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,11-18 19:21:06.044  3651  5814 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-18 19:21:06.044  3651  5814 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-18 19:21:06.044  3651  5814 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-18 19:21:06.045  3651  5814 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-18 19:21:06.045  3651  5814 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-18 19:21:06.045  3651  5814 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-18 19:21:06.045  3651  5814 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-18 19:21:06.045  3651  5814 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-18 19:21:06.045  3651  5814 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-18 19:21:06.083   929   939 I ActivityManager: Process android.process.acore (pid 3401) has died
11-18 19:21:06.083   929   939 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-18 19:21:06.123   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 19:21:06.292   380   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
