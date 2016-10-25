#### Test 908573253c85758_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-25 20:04:52.623  3924  4190 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,10-25 20:04:52.695  3924  4190 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
10-25 20:04:53.055  5506  5506 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-25 20:04:53.060  5506  5506 D AndroidRuntime: CheckJNI is OFF
10-25 20:04:53.088  5506  5506 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-25 20:04:53.120  5506  5506 I Radio-JNI: register_android_hardware_Radio DONE
10-25 20:04:53.135  5506  5506 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-25 20:04:53.146   925  3761 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-25 20:04:53.164  5506  5506 D AndroidRuntime: Shutting down VM
10-25 20:04:53.169  3910  3923 W SearchService: Abort, client detached.
10-25 20:04:53.181  3910  3910 I HotwordDetector: Closing mic
10-25 20:04:53.182  3910  4177 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@9fbd654
10-25 20:04:53.182  3910  4183 E AudioRecord-JNI: Error -4 during AudioRecord native read
10-25 20:04:53.197   925  3665 I ActivityManager: Start proc 5515:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-25 20:04:53.249   513  4186 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
10-25 20:04:53.252   513  4186 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
10-25 20:04:53.257   513  4186 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
10-25 20:04:53.257   513  4186 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
10-25 20:04:53.258   513  2943 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
10-25 20:04:53.261  3910  4178 I MicroRecognitionRnrImpl: Stopping hotword detection.
10-25 20:04:53.261  3910  4182 I MicroRecognitionRnrImpl: Detection finished
10-25 20:04:53.300  5515  5515 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
10-25 20:04:53.320  5515  5515 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
10-25 20:04:53.382  5515  5515 I LibraryLoader: Time to load native libraries: 59 ms (timestamps 9773-9832)
10-25 20:04:53.382  5515  5515 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-25 20:04:53.422  5515  5515 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c7bf9f}
10-25 20:04:53.422  5515  5515 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-25 20:04:53.422  5515  5515 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-25 20:04:53.425  5515  5515 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-25 20:04:53.426  5515  5515 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-25 20:04:53.471  5515  5515 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-25 20:04:53.479  5515  5515 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-25 20:04:53.479  5515  5515 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-25 20:04:53.479  5515  5515 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-25 20:04:53.479  5515  5515 I Adreno  : Build Date                       : 12/06/15
10-25 20:04:53.479  5515  5515 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-25 20:04:53.479  5515  5515 I Adreno  : Local Branch                     : mybranch17112971
10-25 20:04:53.479  5515  5515 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-25 20:04:53.479  5515  5515 I Adreno  : Remote Branch                    : NONE
10-25 20:04:53.479  5515  5515 I Adreno  : Reconstruct Branch               : NOTHING
,10-25 20:04:53.520   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b4aaf93:true
,10-25 20:04:53.545   402   402 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[25239]" dev="sockfs" ino=25239 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 20:04:53.545   402   402 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25239]" dev="sockfs" ino=25239 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 20:04:53.558  5515  5515 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-25 20:04:53.568  5515  5515 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-25 20:04:53.601   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33870]" dev="sockfs" ino=33870 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 20:04:53.601   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33870]" dev="sockfs" ino=33870 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-25 20:04:53.606  5515  5552 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-25 20:04:53.608  3761  3761 W Binder_9: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30821]" dev="sockfs" ino=30821 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 20:04:53.608  3761  3761 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30821]" dev="sockfs" ino=30821 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 20:04:53.613  5515  5539 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-25 20:04:53.642  5515  5552 I OpenGLRenderer: Initialized EGL, version 1.4
,10-25 20:04:53.719   925   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +544ms
,10-25 20:04:53.723  3590  3590 I Keyboard.Facilitator: onFinishInput()
,10-25 20:04:53.718   935   935 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[29618]" dev="sockfs" ino=29618 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-25 20:04:53.718   935   935 W Binder_1: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[29618]" dev="sockfs" ino=29618 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-25 20:04:53.718  3763  3763 W Binder_A: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[29617]" dev="sockfs" ino=29617 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 20:04:53.718  3763  3763 W Binder_A: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[29617]" dev="sockfs" ino=29617 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 20:04:53.762  5515  5515 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5515
,10-25 20:04:53.853  5515  5515 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-25 20:04:54.076  5515  5554 D jxcore_app_log: JniHelper::setJavaVM(0xf52fc000), pthread_self() = -584316624
,10-25 20:04:54.084  5515  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-25 20:04:54.084  5515  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-25 20:04:54.084  5515  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-25 20:04:54.084  5515  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-25 20:04:54.084  5515  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-25 20:04:54.084  5515  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e75b462 added. We now have 1 listener(s)
,10-25 20:04:54.087  5515  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,10-25 20:04:54.087  5515  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-25 20:04:54.088  5515  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-25 20:04:54.089  5515  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-25 20:04:54.091  5515  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48ea929 added. We now have 1 listener(s)
10-25 20:04:54.091  5515  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 20:04:54.096   925  2920 D WifiService: New client listening to asynchronous messages
,10-25 20:04:54.096  5515  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-25 20:04:54.096  5515  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,10-25 20:04:54.096  5515  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-25 20:04:54.096  5515  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-25 20:04:54.096  5515  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-25 20:04:54.099  5515  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 20:04:54.099  5515  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,10-25 20:04:54.104  5515  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-25 20:04:54.105  5515  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:04:54.105  5515  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:04:54.105  5515  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:04:54.105  5515  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:04:54.105  5515  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:04:54.105  5515  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:04:54.105  5515  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:04:54.105  5515  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 20:04:54.105  5515  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-25 20:04:54.105  5515  5554 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 20:04:54.105  5515  5554 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-25 20:04:54.217  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:04:54.222  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:04:54.226  5515  5515 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-25 20:04:54.528  5515  5524 I art     : Background sticky concurrent mark sweep GC freed 75757(7MB) AllocSpace objects, 17(1096KB) LOS objects, 24% free, 24MB/32MB, paused 1.457ms total 241.452ms
,10-25 20:04:55.183  5515  5562 W jxcore-log: Initializing JXcore engine
10-25 20:04:55.183  5515  5562 W jxcore-log: JXcore engine is ready
,10-25 20:04:55.186   925  2918 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-25 20:04:55.208  5562  5562 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12122 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-25 20:04:55.208  5562  5562 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15401]" dev="sockfs" ino=15401 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-25 20:04:55.208  5562  5562 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-25 20:04:55.208  5562  5562 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33839]" dev="sockfs" ino=33839 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-25 20:04:55.217  5515  5562 W jxcore-log: Starting JXcore engine
,10-25 20:04:55.273  5515  5562 W jxcore-log: Platform android
10-25 20:04:55.273  5515  5562 W jxcore-log: 
,10-25 20:04:55.273  5515  5562 W jxcore-log: Process ARCH arm
10-25 20:04:55.273  5515  5562 W jxcore-log: 
,10-25 20:04:55.464  5515  5562 I jxcore-log: JXcore Cordova bridge is ready!
10-25 20:04:55.464  5515  5562 I jxcore-log: 
,10-25 20:04:55.465  5515  5562 W jxcore-log: JXcore engine is started
,10-25 20:04:55.476  5515  5554 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-25 20:04:55.480  5515  5515 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-25 20:04:56.772  3521  3521 I ConfigService: onDestroy
,10-25 20:04:57.566   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:04:58.188   925  3979 I ActivityManager: Killing 5156:org.codeaurora.ims/1001 (adj 15): empty #17
,10-25 20:04:58.226   925  3979 I ActivityManager: Killing 5066:com.google.android.youtube/u0a75 (adj 15): empty #18
,10-25 20:04:58.567   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:04:59.568   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:00.569   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:01.570   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:02.571   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-25 20:05:05.349  5515  5562 I jxcore-log: 2016-10-25 18:05:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-25 20:05:05.349  5515  5562 I jxcore-log: 
,10-25 20:05:05.351  5515  5562 I jxcore-log: 2016-10-25 18:05:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-25 20:05:05.351  5515  5562 I jxcore-log: 
,10-25 20:05:05.355  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:05:05.355  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:05.355  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:05.355  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:05.355  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:05:05.355  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:05.355  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:05:05.355  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 20:05:05.357  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 20:05:05.358  5515  5562 I jxcore-log: 2016-10-25 18:05:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-25 20:05:05.358  5515  5562 I jxcore-log: 
,10-25 20:05:05.360  5515  5562 I jxcore-log: 2016-10-25 18:05:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-25 20:05:05.360  5515  5562 I jxcore-log: 
,10-25 20:05:05.618  5515  5562 I jxcore-log: 2016-10-25 18:05:05 - DEBUG UnitTest_app: 'Running unit tests'
10-25 20:05:05.618  5515  5562 I jxcore-log: 
,10-25 20:05:05.619  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-25 20:05:05.619  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7148f97 added. We now have 2 listener(s)
,10-25 20:05:05.619  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 20:05:05.619  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 20:05:05.620  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 20:05:05.620  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-25 20:05:05.620  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4b5584 added. We now have 2 listener(s)
10-25 20:05:05.620  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 20:05:05.620  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-25 20:05:05.622  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 20:05:05.625  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:05:05.625  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:05.625  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:05.625  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:05.625  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:05:05.625  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:05.625  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:05:05.625  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 20:05:05.626  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:05.627  5515  5562 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 20:05:05.627  5515  5562 D executeNativeTests: Running unit tests
,10-25 20:05:05.634  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:05.639  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:05.661  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-25 20:05:05.661  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 added. We now have 3 listener(s)
10-25 20:05:05.662  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-25 20:05:05.662  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-25 20:05:05.662  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 20:05:05.662  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-25 20:05:05.662  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 added. We now have 3 listener(s)
10-25 20:05:05.662  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 20:05:05.663  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-25 20:05:05.664  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 20:05:05.666  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:05:05.666  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:05.666  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:05.666  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:05.666  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:05:05.666  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:05.666  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:05:05.666  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 20:05:05.667  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:05.667  5515  5562 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-25 20:05:05.669  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-25 20:05:05.669  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 20:05:05.669  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-25 20:05:05.669  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 20:05:05.669  5515  5562 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-25 20:05:05.670  5515  5562 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-25 20:05:05.670  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-25 20:05:05.670  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 20:05:05.670  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 20:05:05.670  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 20:05:05.670  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:05.670  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:05.670  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:05.670  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:05.670  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:05.670  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:05.671  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 20:05:05.671  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:05.671  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 20:05:05.671  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 removed from the list
10-25 20:05:05.671  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:05.671  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 removed from the list
,10-25 20:05:05.677  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:05.678  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:05.678  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:05.678  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:05.678  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:05.679  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:05.679  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.679  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.679  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.679  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:05.679  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:05.679  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:05.680  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
,10-25 20:05:05.680  5515  5562 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-25 20:05:05.681  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:05.681  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:05.681  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-25 20:05:05.681  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:05.681  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:05.681  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:05.681  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-25 20:05:05.681  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:05.682  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:05.682  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:05.682  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:05.682  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:05.682  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:05.682  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:05.682  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:05.682  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.682  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:05.682  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.682  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:05.682  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:05.682  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:05.682  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:05.683  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-25 20:05:05.685  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-25 20:05:05.686  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:05.686  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:05.686  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:05.686  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:05.686  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:05.686  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:05.686  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:05.686  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:05.686  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:05.686  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:05.686  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:05.686  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:05.687  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:05.687  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:05.687  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:05.687  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.687  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.687  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.687  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.687  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:05.687  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:05.687  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:05.687  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:05.688  5515  5562 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-25 20:05:05.689  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 20:05:05.691  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:05:05.691  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:05.691  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:05.691  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:05.691  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:05:05.691  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:05.691  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:05:05.691  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 20:05:05.691  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:05.692  5515  5562 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 20:05:05.692  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 20:05:05.692  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-25 20:05:05.692  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-25 20:05:05.692  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 20:05:05.692  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 20:05:05.694  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-25 20:05:05.694  5515  5562 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-25 20:05:05.694  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-25 20:05:05.694  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:05.696  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-25 20:05:05.697  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:05.698  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-25 20:05:05.698  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 20:05:05.699  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-25 20:05:05.700  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-25 20:05:05.700  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.700  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-25 20:05:05.701  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-25 20:05:05.701  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-25 20:05:05.701  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-25 20:05:05.701  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.701  5515  5562 D BluetoothAdapter: STATE_ON
10-25 20:05:05.703  4567  4796 D BtGatt.GattService: registerClient() - UUID=240f8984-f391-4887-8d73-07aed3b4a395
10-25 20:05:05.705  4567  4648 D BtGatt.GattService: onClientRegistered() - UUID=240f8984-f391-4887-8d73-07aed3b4a395, clientIf=5
10-25 20:05:05.705  5515  5525 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-25 20:05:05.707  4567  4804 D BtGatt.GattService: start scan with filters
10-25 20:05:05.711  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-25 20:05:05.711  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.711  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-25 20:05:05.711  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.711  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.711  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-25 20:05:05.711  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-25 20:05:05.711  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.711  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.711  4567  4652 D BtGatt.ScanManager: handling starting scan
10-25 20:05:05.711  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-25 20:05:05.711  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.712  4567  4652 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
10-25 20:05:05.713  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.713  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 20:05:05.713  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.713  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.713  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.713  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-25 20:05:05.713  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 20:05:05.714  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 20:05:05.714  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.715  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.715  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.715  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:05.715  5515  5562 I io.jxcore.node.ConnectionHelper: start: OK
10-25 20:05:05.719  4567  4648 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-25 20:05:05.720  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:05.720  4567  4652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-25 20:05:05.727  4567  4648 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-25 20:05:05.727  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:05.727  4567  4652 D BtGatt.ScanManager: Starting BLE batch scan
10-25 20:05:05.727  4567  4652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-25 20:05:05.738  4567  4648 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-25 20:05:05.738  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:05.744  4567  4648 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-25 20:05:05.744  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 20:05:06.215  5515  5515 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-25 20:05:06.216  5515  5515 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-25 20:05:06.216  5515  5515 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-25 20:05:06.353  3910  5563 W CronetSyncConnectionRcs: Upload content type not set.
,10-25 20:05:06.379   925  2921 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-25 20:05:06.380   925  2921 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-25 20:05:06.431  4770  4826 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,10-25 20:05:06.432  4770  4770 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,10-25 20:05:09.402   925  2921 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-25 20:05:09.407   925  2921 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-25 20:05:10.720  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-25 20:05:10.720  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-25 20:05:10.720  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-25 20:05:10.720  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 20:05:10.720  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-25 20:05:10.720  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-25 20:05:10.720  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-25 20:05:10.720  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 20:05:10.721  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 20:05:10.721  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-25 20:05:10.722  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.723  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.723  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-25 20:05:10.724  5515  5562 D BluetoothAdapter: STATE_ON
10-25 20:05:10.725  4567  4796 D BtGatt.GattService: stopScan() - queue size =1
10-25 20:05:10.726  4567  4804 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-25 20:05:10.728  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 20:05:10.728  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.728  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-25 20:05:10.728  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.729  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.729  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 20:05:10.729  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-25 20:05:10.729  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.729  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.730  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-25 20:05:10.730  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.732  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.732  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 20:05:10.732  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.732  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.732  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.733  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.733  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.733  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-25 20:05:10.734  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.734  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.734  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.734  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 20:05:10.735  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 20:05:10.736  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 20:05:10.736  5515  5562 D org.thaliproject.p2p.btconnectorlib.D,iscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.735  4567  4567 D BtGatt.ScanManager: awakened up at time 97185
10-25 20:05:10.739  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.739  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.739  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:10.739  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:10.739  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:10.739  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 20:05:10.739  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:10.739  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:10.739  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:05:10.739  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:05:10.739  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:10.740  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:10.740  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:10.740  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:05:10.740  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 20:05:10.744  4567  4648 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-25 20:05:10.744  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:10.744  4567  4652 D BtGatt.ScanManager: stopping BLe Batch
,10-25 20:05:10.752  4567  4648 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-25 20:05:10.752  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:10.752  4567  4652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-25 20:05:10.774  4567  4648 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
10-25 20:05:10.775  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:10.775  4567  4648 D BtGatt.GattService: current time is 97225227668
,10-25 20:05:10.777  4567  4648 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -76, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -88, 96, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -82, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -76, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-25 20:05:10.778  4567  4648 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-25 20:05:10.779  4567  4648 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-25 20:05:10.780  4567  4648 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-25 20:05:10.780  4567  4648 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-25 20:05:10.780  4567  4648 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-25 20:05:11.241  5515  5515 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-25 20:05:15.741  5515  5562 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-25 20:05:15.747  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 20:05:15.757  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:05:15.757  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:15.757  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:15.757  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:15.757  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:05:15.757  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:15.757  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:05:15.757  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 20:05:15.762  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 20:05:15.762  5515  5562 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 20:05:15.762  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 20:05:15.763  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-25 20:05:15.763  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-25 20:05:15.763  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 20:05:15.764  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 20:05:15.767  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:15.770  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-25 20:05:15.770  5515  5562 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-25 20:05:15.770  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-25 20:05:15.779  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:15.780  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-25 20:05:15.783  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-25 20:05:15.783  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-25 20:05:15.789  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:15.789  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-25 20:05:15.789  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-25 20:05:15.790  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-25 20:05:15.790  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-25 20:05:15.790  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:15.791  5515  5562 D BluetoothAdapter: STATE_ON
,10-25 20:05:15.795  4567  4804 D BtGatt.GattService: registerClient() - UUID=ef2a43bf-9a5e-4efb-a5b6-8ab109fbd37e
10-25 20:05:15.796  4567  4648 D BtGatt.GattService: onClientRegistered() - UUID=ef2a43bf-9a5e-4efb-a5b6-8ab109fbd37e, clientIf=5
,10-25 20:05:15.797  5515  5526 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-25 20:05:15.797  4567  4796 D BtGatt.GattService: start scan with filters
,10-25 20:05:15.803  4567  4652 D BtGatt.ScanManager: handling starting scan
10-25 20:05:15.805  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-25 20:05:15.805  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.805  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-25 20:05:15.805  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.805  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:15.805  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-25 20:05:15.806  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,10-25 20:05:15.806  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.806  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.806  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-25 20:05:15.806  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:15.812  4567  4648 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-25 20:05:15.813  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:15.813  4567  4652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-25 20:05:15.814  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:15.814  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 20:05:15.814  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.815  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.815  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.815  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 20:05:15.815  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-25 20:05:15.817  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 20:05:15.817  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:15.820  4567  4648 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-25 20:05:15.820  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:15.821  4567  4652 D BtGatt.ScanManager: Starting BLE batch scan
10-25 20:05:15.821  4567  4652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-25 20:05:15.821  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.821  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.821  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.821  5515  5562 I io.jxcore.node.ConnectionHelper: start: OK
,10-25 20:05:15.824  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:15.824  5515  5562 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-25 20:05:15.824  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:15.824  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-25 20:05:15.824  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:15.824  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 20:05:15.824  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:15.825  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-25 20:05:15.825  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 20:05:15.825  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 20:05:15.825  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 20:05:15.825  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.825  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.825  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-25 20:05:15.826  5515  5562 D BluetoothAdapter: STATE_ON
10-25 20:05:15.827  4567  4796 D BtGatt.GattService: stopScan() - queue size =1
10-25 20:05:15.827  4567  4585 D BtGatt.GattService: unregisterClient() - clientIf=5
10-25 20:05:15.827  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 20:05:15.828  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.828  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-25 20:05:15.828  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.828  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.828  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 20:05:15.828  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-25 20:05:15.828  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.828  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.828  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-25 20:05:15.828  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.829  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.829  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 20:05:15.829  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.829  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.829  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.829  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.830  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.830  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-25 20:05:15.830  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:15.830  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.830  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.830  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 20:05:15.830  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 20:05:15.831  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 20:05:15.831  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.832  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.832  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.832  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.832  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:15.832  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 20:05:15.832  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 20:05:15.832  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:05:15.832  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:15.832  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:15.832  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-25 20:05:15.832  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:15.832  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 20:05:15.832  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:15.832  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:15.832  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:15.833  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:15.834  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:15.834  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.834  4567  4648 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-25 20:05:15.834  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:15.835  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.835  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.835  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.835  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:15.835  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:15.835  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:15.835  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:15.836  5515  5562 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-25 20:05:15.837  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 20:05:15.840  4567  4648 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-25 20:05:15.840  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 20:05:15.842  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:05:15.842  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:15.842  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:15.842  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:15.842  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:05:15.842  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:15.842  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:05:15.842  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 20:05:15.844  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:15.845  5515  5562 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 20:05:15.845  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 20:05:15.845  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-25 20:05:15.845  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-25 20:05:15.845  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 20:05:15.845  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 20:05:15.848  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-25 20:05:15.848  5515  5562 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-25 20:05:15.848  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-25 20:05:15.848  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:15.849  4567  4648 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-25 20:05:15.849  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:15.849  4567  4652 D BtGatt.ScanManager: stopping BLe Batch
,10-25 20:05:15.851  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:15.851  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-25 20:05:15.852  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-25 20:05:15.852  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 20:05:15.854  4567  4648 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-25 20:05:15.854  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:15.854  4567  4652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-25 20:05:15.856  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.857  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-25 20:05:15.857  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-25 20:05:15.857  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-25 20:05:15.857  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-25 20:05:15.857  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.858  5515  5562 D BluetoothAdapter: STATE_ON
10-25 20:05:15.859  4567  4648 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-25 20:05:15.859  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:15.860  4567  4585 D BtGatt.GattService: registerClient() - UUID=2d35ba4f-d4c7-4b0b-99a7-53b72b26a0cc
10-25 20:05:15.861  4567  4648 D BtGatt.GattService: onClientRegistered() - UUID=2d35ba4f-d4c7-4b0b-99a7-53b72b26a0cc, clientIf=5
,10-25 20:05:15.861  5515  5525 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-25 20:05:15.861  4567  4804 D BtGatt.GattService: start scan with filters
,10-25 20:05:15.863  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-25 20:05:15.863  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.863  4567  4652 D BtGatt.ScanManager: handling starting scan
,10-25 20:05:15.863  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-25 20:05:15.864  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.864  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.864  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-25 20:05:15.864  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-25 20:05:15.864  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.864  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.864  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-25 20:05:15.864  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:15.866  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.866  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 20:05:15.866  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.866  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 20:05:15.866  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.866  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.866  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-25 20:05:15.867  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 20:05:15.867  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.869  4567  4648 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-25 20:05:15.869  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:15.869  4567  4652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-25 20:05:15.870  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.870  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.870  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:15.870  5515  5562 I io.jxcore.node.ConnectionHelper: start: OK
,10-25 20:05:15.874  4567  4648 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-25 20:05:15.874  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:15.874  4567  4652 D BtGatt.ScanManager: Starting BLE batch scan
10-25 20:05:15.874  4567  4652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-25 20:05:15.882  4567  4648 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-25 20:05:15.882  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:15.887  4567  4648 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-25 20:05:15.887  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 20:05:16.367  5515  5515 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-25 20:05:16.368  5515  5515 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 20:05:16.368  5515  5515 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-25 20:05:20.871  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-25 20:05:20.871  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:20.871  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-25 20:05:20.871  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:20.871  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 20:05:20.872  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:20.872  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-25 20:05:20.872  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 20:05:20.872  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 20:05:20.872  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-25 20:05:20.872  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.873  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.873  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-25 20:05:20.875  5515  5562 D BluetoothAdapter: STATE_ON
,10-25 20:05:20.877  4567  4796 D BtGatt.GattService: stopScan() - queue size =1
,10-25 20:05:20.880  4567  4585 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-25 20:05:20.881  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-25 20:05:20.881  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.882  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-25 20:05:20.882  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.882  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:20.882  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 20:05:20.882  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-25 20:05:20.883  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.883  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.883  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-25 20:05:20.883  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:20.884  4567  4567 D BtGatt.ScanManager: awakened up at time 107334
10-25 20:05:20.887   925  3104 I ActivityManager: Killing 5195:com.android.settings/1000 (adj 15): empty #17
10-25 20:05:20.888  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.888  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 20:05:20.889  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:20.889  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.890  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.890  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.890  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:20.890  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-25 20:05:20.891  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.891  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.891  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:20.891  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 20:05:20.891  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-25 20:05:20.920  4567  4648 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-25 20:05:20.920  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 20:05:20.920  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 20:05:20.920  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.921  4567  4652 D BtGatt.ScanManager: stopping BLe Batch
,10-25 20:05:20.923  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:20.923  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.923  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:20.923  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:05:20.923  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:05:20.923  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 20:05:20.927  4567  4648 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-25 20:05:20.927  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:20.927  4567  4652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-25 20:05:20.945  4567  4648 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,10-25 20:05:20.945  4567  4648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:05:20.945  4567  4648 D BtGatt.GattService: current time is 107395462878
10-25 20:05:20.945  4567  4648 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -77, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -79, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -76, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-25 20:05:20.946  4567  4648 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-25 20:05:20.946  4567  4648 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-25 20:05:20.946  4567  4648 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-25 20:05:20.946  4567  4648 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-25 20:05:21.424  5515  5515 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-25 20:05:21.425  5515  5515 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:21.425  5515  5515 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-25 20:05:25.925  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-25 20:05:25.925  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:25.925  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-25 20:05:25.925  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:25.925  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.926  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 20:05:25.926  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-25 20:05:25.926  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
,10-25 20:05:25.926  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:05:25.926  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
,10-25 20:05:25.927  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:25.929  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.932  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.932  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:25.934  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:25.938  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.938  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:25.939  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.939  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:25.939  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:25.939  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.939  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:25.941  5515  5562 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-25 20:05:25.943  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-25 20:05:25.944  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:25.944  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:25.944  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:25.944  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.944  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.944  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:25.945  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
,10-25 20:05:25.945  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.945  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:25.945  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:25.945  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.945  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.945  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.945  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:25.945  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:25.948  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.948  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.948  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.948  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:25.948  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:25.948  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:05:25.948  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
,10-25 20:05:25.950  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-25 20:05:25.951  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:25.951  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:25.951  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:25.951  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:25.951  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.951  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.951  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:25.952  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:25.952  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.952  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
,10-25 20:05:25.952  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:25.952  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.952  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.952  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.952  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.952  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.954  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:25.954  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.954  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.954  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:25.955  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-25 20:05:25.955  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.955  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:25.956  5515  5562 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,10-25 20:05:25.956  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:25.956  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:25.956  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:25.956  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:25.956  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.956  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.957  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:25.957  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:25.957  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.957  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
,10-25 20:05:25.957  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:25.957  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.957  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.957  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.957  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.957  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.959  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.959  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.959  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.960  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-25 20:05:25.960  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-25 20:05:25.960  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:05:25.960  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:25.962  5515  5562 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-25 20:05:25.962  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:25.962  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:25.962  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:25.963  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:25.963  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.963  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:25.963  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:25.963  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:25.963  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.963  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:25.963  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
,10-25 20:05:25.963  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.963  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.963  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.963  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.964  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.965  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.965  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.965  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.965  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-25 20:05:25.965  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:25.965  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.965  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:25.966  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-25 20:05:25.966  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 20:05:25.966  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 20:05:25.966  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-25 20:05:25.966  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 20:05:25.967  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 20:05:25.967  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-25 20:05:25.967  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 20:05:25.967  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 20:05:25.967  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-25 20:05:25.967  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:25.967  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:25.967  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:25.967  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.967  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.967  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:25.967  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:25.967  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.968  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:25.968  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:25.968  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.968  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.968  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.968  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.968  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.970  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.970  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:25.970  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.970  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:25.970  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:25.971  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.971  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:25.971  5515  5562 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-25 20:05:25.972  5515  5562 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-25 20:05:25.972  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-25 20:05:25.975  5515  5562 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-25 20:05:25.975  5515  5562 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-25 20:05:25.975  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-25 20:05:25.976  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-25 20:05:25.976  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-25 20:05:25.976  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-25 20:05:25.976  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-25 20:05:25.976  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-25 20:05:25.976  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-25 20:05:25.976  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-25 20:05:25.976  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-25 20:05:25.976  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-25 20:05:25.976  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,10-25 20:05:25.976  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,10-25 20:05:25.977  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,10-25 20:05:25.977  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-25 20:05:25.977  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-25 20:05:25.977  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-25 20:05:25.977  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-25 20:05:25.977  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-25 20:05:25.977  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-25 20:05:25.977  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-25 20:05:25.977  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,10-25 20:05:25.977  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-25 20:05:25.977  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-25 20:05:25.977  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-25 20:05:25.978  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-25 20:05:25.978  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-25 20:05:25.978  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-25 20:05:25.978  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,10-25 20:05:25.978  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-25 20:05:25.978  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-25 20:05:25.978  5515  5562 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-25 20:05:25.978  5515  5562 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-25 20:05:25.978  5515  5562 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-25 20:05:25.979  5515  5562 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-25 20:05:25.979  5515  5562 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-25 20:05:25.979  5515  5562 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-25 20:05:25.979  5515  5562 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-25 20:05:25.979  5515  5562 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,10-25 20:05:25.979  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
10-25 20:05:25.983  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-25 20:05:25.984  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-25 20:05:25.985  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-25 20:05:25.986  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-25 20:05:25.986  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,10-25 20:05:25.986  5515  5562 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-25 20:05:25.986  5515  5562 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-25 20:05:25.986  5515  5562 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-25 20:05:25.987  5515  5567 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
10-25 20:05:25.987  5515  5567 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-25 20:05:25.987  5515  5567 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-25 20:05:25.987  5515  5567 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,10-25 20:05:25.988  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:25.988  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-25 20:05:25.988  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:25.988  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:25.988  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.988  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.988  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:25.988  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,10-25 20:05:25.991  4804  4804 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[34074]" dev="sockfs" ino=34074 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 20:05:25.991  4804  4804 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[34074]" dev="sockfs" ino=34074 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-25 20:05:25.990  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
,10-25 20:05:25.990  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.990  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:25.990  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:25.990  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.990  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.990  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.990  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.991  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:25.991  5515  5568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
10-25 20:05:25.992  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.992  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:25.992  5515  5567 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-25 20:05:25.992  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.992  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:25.992  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:25.992  5515  5567 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 20:05:25.992  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.992  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
,10-25 20:05:25.993  5515  5562 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-25 20:05:25.994  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:25.994  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:25.994  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:25.994  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-25 20:05:25.994  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.994  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.994  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:25.994  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:25.994  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:05:25.994  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:25.994  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:25.994  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.994  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.994  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.994  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.995  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.995  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.996  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:25.996  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:25.996  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:25.996  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:25.996  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.996  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:25.997  5515  5562 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-25 20:05:25.997  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:25.997  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:25.997  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:25.997  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:25.997  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 20:05:25.997  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.997  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:25.997  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:25.997  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:25.997  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:25.998  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:25.998  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.998  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.998  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:25.998  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:25.998  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:26.000  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:26.000  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:26.000  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:26.000  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:26.000  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:26.000  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:26.000  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:26.001  5515  5562 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-25 20:05:26.001  5515  5562 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-25 20:05:26.001  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-25 20:05:26.001  5515  5562 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-25 20:05:26.001  5515  5562 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-25 20:05:26.002  5515  5562 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-25 20:05:26.002  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-25 20:05:26.002  5515  5562 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-25 20:05:26.002  5515  5562 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-25 20:05:26.002  5515  5562 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-25 20:05:26.002  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-25 20:05:26.002  5515  5562 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-25 20:05:26.002  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:26.002  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:26.002  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:26.002  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:26.002  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:26.002  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:26.002  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:26.002  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:26.002  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:26.002  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:26.003  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:26.003  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:26.003  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:26.003  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:26.003  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:26.003  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:26.004  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:26.004  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:26.004  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:26.004  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:26.004  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:26.004  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:26.004  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:26.005  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:26.005  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:26.005  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:26.005  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:26.005  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:26.005  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:26.005  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:26.005  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:26.005  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:26.005  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:27.572   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-25 20:05:27.572   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-25 20:05:31.006  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:05:31.007  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:31.007  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:31.007  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 20:05:31.007  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.007  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-25 20:05:31.007  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:31.008  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-25 20:05:31.008  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-25 20:05:31.008  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:31.008  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-25 20:05:31.008  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.009  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:31.009  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:31.009  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
,10-25 20:05:31.009  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:05:31.009  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
,10-25 20:05:31.009  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:31.009  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.010  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:31.010  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.010  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.010  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.014  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:31.015  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.015  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:31.015  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:31.015  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:31.015  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:31.015  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
,10-25 20:05:31.021  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-25 20:05:31.022  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 20:05:31.024  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-25 20:05:31.028  4796  4796 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29643]" dev="sockfs" ino=29643 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-25 20:05:31.031  4796  4796 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[29643]" dev="sockfs" ino=29643 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-25 20:05:31.026  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-25 20:05:31.027  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-25 20:05:31.027  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-25 20:05:31.028  5515  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-25 20:05:31.028  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-25 20:05:31.028  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-25 20:05:31.028  5515  5515 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-25 20:05:31.029  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:31.029  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-25 20:05:31.029  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-25 20:05:31.029  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-25 20:05:31.029  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:31.029  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 20:05:31.029  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-25 20:05:31.029  5515  5569 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 20:05:31.030  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:31.030  5515  5515 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-25 20:05:31.030  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:31.030  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 20:05:31.030  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 20:05:31.030  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 20:05:31.030  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 20:05:31.030  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.031  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.032  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.032  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 20:05:31.033  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:31.033  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.033  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:31.033  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:05:31.033  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-25 20:05:31.033  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:05:31.033  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 20:05:31.033  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:31.033  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-25 20:05:31.034  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:31.034  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.034  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.034  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 20:05:31.034  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:31.034  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:31.034  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:31.034  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:31.034  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.035  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.035  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.035  5515  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-25 20:05:31.035  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.035  5515  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-25 20:05:31.035  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.035  5515  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-25 20:05:31.037  5515  5515 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-25 20:05:31.037  5515  5515 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-25 20:05:31.038  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.038  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.038  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.038  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:31.038  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-25 20:05:31.039  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:31.039  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:31.041  5515  5562 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-25 20:05:31.041  5515  5562 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-25 20:05:31.042  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-25 20:05:31.042  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 20:05:31.042  5515  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 20:05:31.042  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-25 20:05:31.042  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:31.042  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:31.043  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:31.043  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.043  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.043  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:31.043  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:31.043  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:31.043  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:31.044  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:31.044  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.044  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.044  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 20:05:31.044  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.044  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.047  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.048  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.048  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.048  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-25 20:05:31.048  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:31.048  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:31.048  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:31.053  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:31.053  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:31.054  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:31.054  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-25 20:05:31.054  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.054  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.054  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:31.054  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:31.054  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:31.054  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
,10-25 20:05:31.054  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:31.054  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.054  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.055  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.055  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:31.055  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:31.057  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:31.057  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.057  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.057  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:31.057  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:31.057  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:31.057  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
,10-25 20:05:31.058  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:05:31.059  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:05:31.059  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:05:31.059  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:05:31.059  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.059  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:31.059  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:05:31.059  5515  5562 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0fa752 not in the list
10-25 20:05:31.059  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:31.059  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:31.059  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:31.059  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 20:05:31.059  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.059  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:31.060  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:05:31.060  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:31.061  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:31.061  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:05:31.061  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:05:31.061  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:05:31.061  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:05:31.062  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:05:31.062  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d116a23 not in the list
10-25 20:05:31.063  5515  5562 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-25 20:05:31.063  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-25 20:05:31.063  5515  5562 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-25 20:05:31.063  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-25 20:05:31.064  5515  5562 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-25 20:05:31.064  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-25 20:05:31.068  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-25 20:05:31.068  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-25 20:05:31.068  5515  5562 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,10-25 20:05:31.068  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-25 20:05:31.068  5515  5562 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-25 20:05:31.068  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-25 20:05:31.068  5515  5562 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-25 20:05:31.069  5515  5562 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-25 20:05:31.069  5515  5562 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-25 20:05:31.069  5515  5562 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-25 20:05:31.069  5515  5562 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,10-25 20:05:31.069  5515  5562 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-25 20:05:31.069  5515  5562 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-25 20:05:31.070  5515  5562 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,10-25 20:05:31.070  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-25 20:05:31.071  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b408a4d added. We now have 3 listener(s)
10-25 20:05:31.071  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 20:05:31.072  5515  5562 D BluetoothAdapter: enable(): BT is already enabled..!
10-25 20:05:31.073   925  3665 D WifiService: setWifiEnabled: true pid=5515, uid=10077
10-25 20:05:31.073   925  3665 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 20:05:31.121  4567  4764 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-25 20:05:31.121  4567  4794 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
10-25 20:05:31.121  5515  5567 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
10-25 20:05:31.122  5515  5567 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-25 20:05:31.122  5515  5567 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,10-25 20:05:31.534  5515  5515 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-25 20:05:32.573   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:33.574   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:34.575   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:35.194   925  2918 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-25 20:05:35.576   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:36.078  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-25 20:05:36.079  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@92c8902 added. We now have 4 listener(s)
,10-25 20:05:36.079  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 20:05:36.092  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:05:36.093  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@92c8902 removed from the list
,10-25 20:05:36.093  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:05:36.093  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:05:36.093  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:36.097  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-25 20:05:36.098  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3412213 added. We now have 4 listener(s)
10-25 20:05:36.098  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 20:05:36.100  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:05:36.101  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3412213 removed from the list
10-25 20:05:36.101  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
,10-25 20:05:36.101  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 20:05:36.101  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:05:36.102  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-25 20:05:36.102  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8cf7c50 added. We now have 4 listener(s)
10-25 20:05:36.103  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 20:05:36.107   925  3103 D WifiService: setWifiEnabled: false pid=5515, uid=10077
,10-25 20:05:36.107   925  3103 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-25 20:05:36.111   925  2918 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-25 20:05:36.111   925  2918 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-25 20:05:36.112   925  2918 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-25 20:05:36.112   925  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 20:05:36.117  4567  4644 D BluetoothAdapterState: Current state: ON, message: 23
10-25 20:05:36.117  4567  4644 D BluetoothAdapterProperties: Setting state to 13
10-25 20:05:36.118  4567  4644 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-25 20:05:36.119  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 20:05:36.120  4567  4644 D BluetoothAdapterProperties: onBluetoothDisable()
10-25 20:05:36.121  4567  4644 I BluetoothAdapterState: Entering PendingCommandState
,10-25 20:05:36.122  4567  4648 D BluetoothAdapterProperties: Scan Mode:20
,10-25 20:05:36.123  4567  4644 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-25 20:05:36.126  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.127  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:05:36.127  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:36.127  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:36.127  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:36.127  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:36.127  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:36.127  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:05:36.127  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 20:05:36.127  4567  4567 D HeadsetService: Received stop request...Stopping profile...
10-25 20:05:36.127  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.127  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 20:05:36.128  5515  5562 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 20:05:36.129   925   925 D BluetoothHeadset: Proxy object disconnected
10-25 20:05:36.130   925   925 D BluetoothHeadset: Proxy object disconnected
10-25 20:05:36.130  4567  4567 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:36.130  3062  3077 D BluetoothHeadset: Proxy object disconnected
10-25 20:05:36.130  4567  4567 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:36.130  4567  4567 V BluetoothAdapterState: isBleTurningOn()=false
,10-25 20:05:36.130  4567  4567 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:36.130  3062  3062 D HeadsetProfile: Bluetooth service disconnected
10-25 20:05:36.131  3703  3754 D BluetoothHeadset: Proxy object disconnected
10-25 20:05:36.131   925   925 D BluetoothHeadset: Proxy object disconnected
10-25 20:05:36.132  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:36.132   925  5286 D DhcpClient: Clearing IP address
,10-25 20:05:36.132   508   919 D CommandListener: Clearing all IP addresses on wlan0
10-25 20:05:36.135  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:36.137  4567  4567 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-25 20:05:36.137  4567  4567 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-25 20:05:36.138  4567  4648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-25 20:05:36.138  4567  4567 D A2dpService: Received stop request...Stopping profile...
10-25 20:05:36.139  4567  4764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 20:05:36.139  4567  4764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 20:05:36.139  4567  4764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 20:05:36.139  4567  4799 D A2dpStateMachine: Exit Disconnected: -1
10-25 20:05:36.139  4567  4648 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-25 20:05:36.139  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.140  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:36.140  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:36.140  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:36.140  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:36.140  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:36.140  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:36.140  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:05:36.140  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 20:05:36.140  3062  3062 D BluetoothA2dp: Proxy object disconnected
10-25 20:05:36.141   925   925 D BluetoothA2dp: Proxy object disconnected
10-25 20:05:36.141  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.142  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:36.142  4567  4567 D HidService: Received stop request...Stopping profile...
10-25 20:05:36.142  4567  4567 D HidService: Stopping Bluetooth HidService
,10-25 20:05:36.143  3062  3062 D BluetoothInputDevice: Proxy object disconnected
10-25 20:05:36.143  3062  3062 D HidProfile: Bluetooth service disconnected
10-25 20:05:36.143  4567  4567 D HealthService: Received stop request...Stopping profile...
10-25 20:05:36.144   508   919 D CommandListener: Setting iface cfg
10-25 20:05:36.144  4567  4567 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:36.144  4567  4567 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:36.144  4567  4567 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:36.144  4567  4567 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 20:05:36.145  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.146  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:36.146  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:36.146  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:36.146  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:36.146  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:36.146  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:36.146  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:05:36.146  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 20:05:36.146  4567  4567 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:36.146  4567  4567 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:36.146  4567  4567 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:36.146  4567  4567 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:36.146  4567  4648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-25 20:05:36.146  4567  4764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 20:05:36.147  4567  4567 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,10-25 20:05:36.147  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 20:05:36.147  3521  5337 V NativeCrypto: Read error: ssl=0x7f86fbaf80: I/O error during system call, Connection timed out
10-25 20:05:36.147  4567  4567 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-25 20:05:36.147  4567  4764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 20:05:36.147  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:36.147  4567  4764 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-25 20:05:36.147  4567  4567 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:36.147  4567  4567 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:36.147  4567  4764 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-25 20:05:36.147  4567  4567 V BluetoothAdapterState: isBleTurningOn()=false
,10-25 20:05:36.147  4567  4567 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:36.147  4567  4764 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-25 20:05:36.147  4567  4764 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-25 20:05:36.148  4567  4648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-25 20:05:36.148   925  5287 D DhcpClient: Receive thread stopped
,10-25 20:05:36.148  4567  4567 D PanService: Received stop request...Stopping profile...
10-25 20:05:36.149  3521  5337 V NativeCrypto: SSL shutdown failed: ssl=0x7f86fbaf80: I/O error during system call, Broken pipe
,10-25 20:05:36.149  3062  3062 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-25 20:05:36.149  3062  3062 D PanProfile: Bluetooth service disconnected
10-25 20:05:36.149  4567  4567 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-25 20:05:36.149  4567  4648 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-25 20:05:36.150  4567  4567 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-25 20:05:36.152   925  3665 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-25 20:05:36.152   925  5284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,10-25 20:05:36.153  4567  4567 D BluetoothMapService: Received stop request...Stopping profile...
10-25 20:05:36.153  4567  4567 D BluetoothMapService: stop()
10-25 20:05:36.154  4567  4567 D BluetoothMapAppObserver: deinitObservers()
10-25 20:05:36.154  4567  4567 D BluetoothMapAppObserver: removeReceiver()
10-25 20:05:36.155   925  5284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-25 20:05:36.155  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:36.155  3062  3062 D BluetoothMap: Proxy object disconnected
10-25 20:05:36.155   925  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-25 20:05:36.155  3062  3062 D MapProfile: Bluetooth service disconnected
10-25 20:05:36.155   925  2921 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-25 20:05:36.157   925  2921 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-25 20:05:36.157  4567  4567 D SapService: Received stop request...Stopping profile...
10-25 20:05:36.157  4567  4567 V SapService: stop()
10-25 20:05:36.159  4567  4567 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:36.159  4567  4567 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:36.159  4567  4567 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:36.160  4567  4567 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:36.160  4567  4567 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-25 20:05:36.160  4567  4567 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-25 20:05:36.162  4567  4567 D BluetoothMapService: MAP Service closeService in
10-25 20:05:36.162  4567  4567 D BluetoothMapMasInstance0: MAP Service shutdown
10-25 20:05:36.162  4567  4567 D ObexServerSockets0: shutdown(block = true)
10-25 20:05:36.162   925  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-25 20:05:36.163   925  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-25 20:05:36.163  4567  4567 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-25 20:05:36.163  4567  4806 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-25 20:05:36.163  4567  4567 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-25 20:05:36.163  4567  4807 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-25 20:05:36.163  4567  4794 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-25 20:05:36.163  4567  4567 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:36.163  4567  4567 V BluetoothAdapterState: isTurningOn()=false
,10-25 20:05:36.163  4567  4567 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:36.163  4567  4567 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:36.164  4567  4567 D BluetoothMapService: cleanup()
10-25 20:05:36.164  4567  4567 D BluetoothMapService: MAP Service closeService in
,10-25 20:05:36.165  4567  4567 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:36.165  4567  4567 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:36.165  4567  4567 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:36.165  4567  4567 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:36.166  4567  4644 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-25 20:05:36.166  4567  4644 D BluetoothAdapterProperties: Setting state to 15
10-25 20:05:36.166  4567  4644 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-25 20:05:36.167  4567  4644 I BluetoothAdapterState: Entering BleOnState
10-25 20:05:36.167   534   534 E Parcel  : Reading a NULL string not supported here.
10-25 20:05:36.168   925   925 D RttService: SCAN_AVAILABLE : 1
10-25 20:05:36.168   925  2921 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,10-25 20:05:36.168   925  3029 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-25 20:05:36.171  4567  4567 I BtOppRfcommListener: stopping Accept Thread
,10-25 20:05:36.171  4567  5215 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-25 20:05:36.171  3679  3820 W QCNEJ   : |CORE| network lost: 100
10-25 20:05:36.172  4567  5215 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-25 20:05:36.174  3679  3820 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-25 20:05:36.176  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.176  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:36.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:36.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:36.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:36.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:36.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:36.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:36.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 20:05:36.177  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 20:05:36.177  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:36.179  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.179  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:36.179  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:36.179  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:36.179  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:36.179  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:36.179  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:36.179  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:36.179  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:36.179  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.180  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:05:36.182  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.182  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:36.182  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:36.182  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:36.182  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:36.182  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:36.182  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:36.182  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:36.182  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:36.183  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.183  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:05:36.186   925   938 I ActivityManager: Start proc 5575:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-25 20:05:36.187  3062  3077 D BluetoothMap: onBluetoothStateChange: up=false
,10-25 20:05:36.188   925  2918 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-25 20:05:36.189   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 20:05:36.189  3062  3941 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 20:05:36.191  3062  3082 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 20:05:36.191   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 20:05:36.192  3062  3077 D BluetoothPan: onBluetoothStateChange on: false
10-25 20:05:36.192  3062  3941 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-25 20:05:36.193  3703  3961 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 20:05:36.193  3062  3082 D BluetoothPbap: onBluetoothStateChange: up=false
10-25 20:05:36.194   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 20:05:36.194   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 20:05:36.194  4567  4644 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-25 20:05:36.194  4567  4644 D BluetoothAdapterProperties: Setting state to 16
10-25 20:05:36.194  4567  4644 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-25 20:05:36.195  4567  4644 D BluetoothAdapterProperties: onBleDisable
10-25 20:05:36.196  4567  4644 I BluetoothAdapterState: Entering PendingCommandState
10-25 20:05:36.196  4567  4645 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-25 20:05:36.197  4567  4764 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-25 20:05:36.197  4567  4764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-25 20:05:36.197  4567  4648 D BluetoothAdapterProperties: Scan Mode:20
10-25 20:05:36.197  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:36.200  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:36.201   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-25 20:05:36.202  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:36.202   925  2918 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-25 20:05:36.203  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:36.204  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:36.205  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:36.223   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-25 20:05:36.224   508   919 D CommandListener: Clearing all IP addresses on wlan0
10-25 20:05:36.224   925  2921 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-25 20:05:36.224   925  2921 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-25 20:05:36.224   508   919 D TetherController: Setting IP forward enable = 0
,10-25 20:05:36.227   925  2918 D DhcpClient: doQuit
,10-25 20:05:36.227   925  2918 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-25 20:05:36.228  3387  3387 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-25 20:05:36.228   925  5286 D DhcpClient: onQuitting
10-25 20:05:36.232   925   942 D Tethering: MasterInitialState.processMessage what=3
,10-25 20:05:36.233  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.233  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:36.233  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:36.233  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:36.233  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:05:36.233  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:36.233  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:36.233  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:36.233  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:36.234  5172  5172 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@49b167b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-25 20:05:36.234  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 20:05:36.234  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:05:36.236  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 20:05:36.236  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:36.236  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:36.236  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:36.236  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:05:36.236  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:36.236  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:36.236  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:36.236  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:36.237  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.237  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:05:36.240  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 20:05:36.240  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:36.240  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:36.240  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:36.240  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:05:36.240  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:36.240  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:36.240  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:36.240  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:36.240  3910  3910 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-25 20:05:36.241  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:36.241  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:36.242  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:36.243  4926  4959 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-25 20:05:36.243  4926  4959 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-25 20:05:36.243  4926  4959 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-25 20:05:36.243  4926  4959 E SarControlService: no key has been found,reset the power
10-25 20:05:36.243  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:36.244  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:36.245  4926  4993 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-25 20:05:36.245  4926  4993 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-25 20:05:36.245  4926  4993 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-25 20:05:36.246  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 20:05:36.246  4979  4979 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-25 20:05:36.248  4926  4993 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-25 20:05:36.248  4926  4993 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-25 20:05:36.248  4926  4993 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-25 20:05:36.248  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 20:05:36.249  4979  4979 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-25 20:05:36.250  4979  5001 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c1e91f9 HexData = [00000000ea03000000000000ffffffff]
10-25 20:05:36.250  4979  5001 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-25 20:05:36.250  4979  5001 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-25 20:05:36.250  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 20:05:36.250  4926  4936 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-25 20:05:36.251  4979  5001 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c1e91f9 HexData = [00000000eb03000000000000ffffffff]
,10-25 20:05:36.251  4979  5001 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 20:05:36.252  4979  5001 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-25 20:05:36.252  3387  3387 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-25 20:05:36.252  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 20:05:36.253  4926  4938 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-25 20:05:36.256  3387  3387 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-25 20:05:36.265  5575  5575 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-25 20:05:36.277  5575  5575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-25 20:05:36.281   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c5e1145:true
10-25 20:05:36.282  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-25 20:05:36.285  3387  3387 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
10-25 20:05:36.297  3387  3387 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-25 20:05:36.297  5575  5575 D LocalBluetoothProfileManager: Adding local MAP profile
,10-25 20:05:36.300  5575  5575 D BluetoothMap: Create BluetoothMap proxy object
,10-25 20:05:36.307  5575  5575 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-25 20:05:36.313  5575  5575 D DockEventReceiver: finishStartingService: stopping service
,10-25 20:05:36.318  5575  5575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-25 20:05:36.322  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 20:05:36.323  5575  5575 D DockEventReceiver: finishStartingService: stopping service
,10-25 20:05:36.325   925   935 I ActivityManager: Killing 5312:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-25 20:05:36.351   925  3103 I ActivityManager: Start proc 5605:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-25 20:05:36.381  5605  5605 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-25 20:05:36.388   925  3104 I ActivityManager: Killing 5324:com.android.chrome/u0a39 (adj 15): empty #17
,10-25 20:05:36.407   925  2918 D wifi    : In wifi stop Hal
,10-25 20:05:36.407   925  2918 D wifi    : halHandle = 0x7f70a5b680, mVM = 0x7f8d00d140, mCls = 0x100a02
,10-25 20:05:36.407   925  3386 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-25 20:05:36.407   925  3386 D WifiHAL : Got a signal to exit!!!
10-25 20:05:36.407   925  3386 I WifiHAL : Exit wifi_event_loop
10-25 20:05:36.408   925  2918 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-25 20:05:36.408   925  2918 E WifiHAL : Event processing terminated
10-25 20:05:36.408   925  2918 D wifi    : In wifi cleaned up handler
10-25 20:05:36.408   925  2918 I WifiHAL : Internal cleanup completed
,10-25 20:05:36.410  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:36.410  4384  4384 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 20:05:36.412  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:36.413  3924  3924 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-25 20:05:36.413  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:36.414  3658  4130 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-25 20:05:36.415  4567  4648 I bt_hci  : shut_down
10-25 20:05:36.419  3924  3924 D SystemUpdateService: onCreate
10-25 20:05:36.421  4567  4654 D bt_hwcfg: hw_epilog_process
10-25 20:05:36.421  4567  4654 I bt_vendor: low_power_mode_cb
,10-25 20:05:36.423  4567  4654 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-25 20:05:36.423  4567  4654 I bt_vendor: epilog_cb
10-25 20:05:36.423  4567  4654 I bt_hci  : epilog_finished_callback
,10-25 20:05:36.424  3924  3924 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-25 20:05:36.425  4567  4648 I bt_hci_h4: hal_close
10-25 20:05:36.426  4567  4648 I bt_userial_vendor: device fd = 54 close
,10-25 20:05:36.428  3924  5618 I SystemUpdateService: active receiver: enabled
,10-25 20:05:36.428   925  3386 D wifi    : set interface wlan0 flags (DOWN)
10-25 20:05:36.429   925  2918 D WifiNative-HAL: HAL event thread stopped successfully
,10-25 20:05:36.433  3924  3924 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-25 20:05:36.437  3924  5309 I iu.UploadsManager: num queued entries: 0
10-25 20:05:36.437  3924  5309 I iu.UploadsManager: num updated entries: 0
,10-25 20:05:36.438  3924  5309 I iu.SyncManager: NEXT; no task
,10-25 20:05:36.441  3924  3924 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-25 20:05:36.442  3924  3924 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-25 20:05:36.443  3924  5618 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-25 20:05:36.445  3924  5618 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-25 20:05:36.445  3924  5618 I SystemUpdateService: now status is 0 (complete)
10-25 20:05:36.445  3924  5618 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-25 20:05:36.445  3924  5618 I SystemUpdateService: file has been verified
10-25 20:05:36.446  3924  5618 I SystemUpdateService: OTA package size = 21989297
,10-25 20:05:36.452  3924  5618 I SystemUpdateService: showing system update notification
,10-25 20:05:36.454   925  3763 I ActivityManager: Start proc 5620:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-25 20:05:36.467   925   925 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-25 20:05:36.469  3924  3924 D SystemUpdateService: onDestroy
,10-25 20:05:36.488  5620  5620 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-25 20:05:36.491  5620  5620 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-25 20:05:36.497  5620  5620 D SprintDMHelper: simOperator: 
,10-25 20:05:36.497  5620  5620 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-25 20:05:36.509   925  3104 I ActivityManager: Start proc 5632:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-25 20:05:36.510   925  3104 I ActivityManager: Killing 5172:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-25 20:05:36.540  4567  4645 D bt_stack_manager: event_shut_down_stack finished.
,10-25 20:05:36.540  4567  4644 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-25 20:05:36.542  4567  4567 D BtGatt.DebugUtils: handleDebugAction() action=null
10-25 20:05:36.542  4567  4644 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-25 20:05:36.542  4567  4567 D BtGatt.GattService: Received stop request...Stopping profile...
,10-25 20:05:36.542  4567  4567 D BtGatt.GattService: stop()
,10-25 20:05:36.542  4567  4567 D BtGatt.AdvertiseManager: advertise clients cleared
10-25 20:05:36.544  4567  4567 V BluetoothAdapterState: isTurningOff()=false
10-25 20:05:36.544  4567  4567 V BluetoothAdapterState: isTurningOn()=false
,10-25 20:05:36.544  4567  4567 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:36.544  4567  4567 V BluetoothAdapterState: isBleTurningOff()=true
10-25 20:05:36.544  4567  4644 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-25 20:05:36.544  4567  4644 D BluetoothAdapterProperties: Setting state to 10
10-25 20:05:36.544  4567  4644 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-25 20:05:36.545  4567  4644 I BluetoothAdapterState: Entering OffState
,10-25 20:05:36.545   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-25 20:05:36.551  4567  4567 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-25 20:05:36.551  4567  4567 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-25 20:05:36.551  4567  4567 I BluetoothServiceJni: cleanupNative: return from cleanup
10-25 20:05:36.552  4567  4645 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-25 20:05:36.560  4567  4567 I art     : System.exit called, status: 0
,10-25 20:05:36.560  4567  4567 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-25 20:05:36.577   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:36.598   925  3761 I ActivityManager: Process com.android.bluetooth (pid 4567) has died
,10-25 20:05:36.621  4384  5647 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-25 20:05:36.625   925  3665 I ActivityManager: Killing 3843:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-25 20:05:36.631   925   942 D Tethering: InitialState.processMessage what=4
,10-25 20:05:36.646   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-25 20:05:37.310   508   919 E Netd    : netlink response contains error (No such file or directory)
,10-25 20:05:37.312   925  2921 E NetdConnector: NDC Command {109 network destroy 100} took too long (1082ms)
10-25 20:05:37.313   925  2921 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-25 20:05:37.313   925  2921 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-25 20:05:37.314   925  2891 E NetdConnector: NDC Command {110 bandwidth setglobalalert 2097152} took too long (1076ms)
10-25 20:05:37.314   925  2890 E NetdConnector: NDC Command {111 bandwidth gettetherstats} took too long (666ms)
10-25 20:05:37.314   508   919 D TetherController: Setting IP forward enable = 0
,10-25 20:05:37.577   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-25 20:05:41.131   925  3814 D WifiService: setWifiEnabled: true pid=5515, uid=10077
,10-25 20:05:41.131   925  3814 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 20:05:41.141   508   919 D SoftapController: Softap fwReload - Ok
,10-25 20:05:41.146   508   919 D CommandListener: Setting iface cfg
,10-25 20:05:41.146   508   919 D CommandListener: Trying to bring down wlan0
10-25 20:05:41.147   508   919 D CommandListener: Clearing all IP addresses on wlan0
,10-25 20:05:41.152   925  2918 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-25 20:05:41.730   925  2918 D wifi    : set interface wlan0 flags (UP)
,10-25 20:05:41.737   925  2918 I WifiHAL : Initializing wifi
,10-25 20:05:41.738   925  2918 I WifiHAL : Creating socket
,10-25 20:05:41.738   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-25 20:05:41.744   925  2918 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-25 20:05:41.744   925  2918 D wifi    : Did set static halHandle = 0x7f70a5b680
10-25 20:05:41.744   925  2918 D wifi    : halHandle = 0x7f70a5b680, mVM = 0x7f8d00d140, mCls = 0x1019c2
10-25 20:05:41.745   925  2918 D wifi    : array field set
10-25 20:05:41.745   925  2918 I WifiNative-HAL: interface[0] = wlan0
,10-25 20:05:41.747   925  5656 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547350754944
10-25 20:05:41.747   925  5656 D wifi    : waitForHalEvents called, vm = 0x7f8d00d140, obj = 0x1019c2, env = 0x7f6eae2bc0
,10-25 20:05:41.825  5657  5657 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-25 20:05:41.850   925  2918 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-25 20:05:41.858  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:41.861  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:41.863  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:41.898  5657  5657 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-25 20:05:41.925  5657  5657 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-25 20:05:41.925  5657  5657 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-25 20:05:41.939   925  2918 D WifiConfigStore: Loading config and enabling all networks 
,10-25 20:05:41.943  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 20:05:41.944  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:41.944  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:41.944  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:41.944  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:41.944  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:41.944  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:41.944  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:41.944  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:41.944  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:41.944  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:41.948  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:41.948  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:41.948  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:41.948  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:41.948  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:41.948  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:41.948  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:41.948  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:41.948  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 20:05:41.948  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:41.948  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:05:41.950  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 20:05:41.951  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:41.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:41.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:41.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:41.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:41.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:41.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:41.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:41.951  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:41.951  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:05:41.959   925  2918 D WifiConfigStore: loaded 0 passpoint configs
,10-25 20:05:41.959   925  2918 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
10-25 20:05:41.960   925  2918 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-25 20:05:41.960   925  2918 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-25 20:05:41.961   925  2918 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
10-25 20:05:41.961   925  2918 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,10-25 20:05:41.962   925  2918 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-25 20:05:41.962   925  2918 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-25 20:05:41.962   925  2918 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
10-25 20:05:41.962   925  2918 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
10-25 20:05:41.962   925  2918 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-25 20:05:41.962   925  2918 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
10-25 20:05:41.962   925  2918 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,10-25 20:05:41.964   925  2918 D WifiNative-HAL: Setting external_sim to 1
,10-25 20:05:41.965   925  2918 D wifi    : setting dfs flag to true, 0x7f6e811aa0
10-25 20:05:41.965   925  2918 D WifiStateMachine: Setting OUI to DA-A1-19
10-25 20:05:41.965  4384  4384 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-25 20:05:41.965   925  2918 D wifi    : setting scan oui 0x7f6e811aa0
,10-25 20:05:41.966   925  2918 D WifiHAL : Sending mac address OUI
,10-25 20:05:41.969   925  2918 E native  : do suspend false
,10-25 20:05:41.975   925  2918 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-25 20:05:41.975   925   925 D RttService: SCAN_AVAILABLE : 3
10-25 20:05:41.975   925  3029 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-25 20:05:41.978   508   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-25 20:05:41.980   508   919 D CommandListener: Setting iface cfg
,10-25 20:05:41.981   925  2892 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
,10-25 20:05:41.981   925  2892 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-25 20:05:41.987   925  2892 D WifiNative-HAL: p2pGetDeviceAddress
,10-25 20:05:41.990   925  2892 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-25 20:05:41.990   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128440 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=11 mControllerEnergyUsed=41 }
,10-25 20:05:42.579   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:43.580   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:44.581   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:45.109  5657  5657 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 20:05:45.121  5657  5657 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 20:05:45.130  5657  5657 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 20:05:45.138  5657  5657 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 20:05:45.176   925  2918 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-25 20:05:45.179   925  2918 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-25 20:05:45.179   925  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 20:05:45.191   925  2918 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-25 20:05:45.225   925  2918 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-25 20:05:45.232  5657  5657 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-25 20:05:45.582   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:45.669  5657  5657 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-25 20:05:45.713  5657  5657 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-25 20:05:45.715  5657  5657 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-25 20:05:45.725   925  2918 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-25 20:05:45.725   925  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 20:05:45.725   925  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-25 20:05:45.742   925  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 20:05:45.755   508   919 D CommandListener: Setting iface cfg
,10-25 20:05:45.761   925  2918 D WifiStateMachine: Start Dhcp Watchdog 2
,10-25 20:05:45.768   925  5663 D DhcpClient: Receive thread started
,10-25 20:05:45.770   925  2921 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-25 20:05:45.770   925  2918 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-25 20:05:45.770   925  2921 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-25 20:05:45.858   925  2918 E native  : do suspend false
,10-25 20:05:45.868   925  5662 D DhcpClient: Broadcasting DHCPDISCOVER
,10-25 20:05:45.900   925  5663 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.111, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,10-25 20:05:45.901   925  5662 D DhcpClient: Got pending lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,10-25 20:05:45.903   925  5662 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.111 serverid=192.168.1.1
,10-25 20:05:45.918   925  5663 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.111, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-25 20:05:45.919   925  5662 D DhcpClient: Confirmed lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-25 20:05:45.922   508   919 D CommandListener: Setting iface cfg
10-25 20:05:45.927   925  2918 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-25 20:05:45.930   925  5662 D DhcpClient: Scheduling renewal in 86399s
,10-25 20:05:45.942   925  2918 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
10-25 20:05:45.946   925  2918 D WifiConfigStore: No blacklist allowed without epno enabled
,10-25 20:05:45.947   925  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-25 20:05:45.952   925  2921 D ConnectivityService: Adding iface wlan0 to network 101
10-25 20:05:45.955   925  2918 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-25 20:05:45.999   925  2921 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-25 20:05:45.999   925  2921 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-25 20:05:46.002   925  2921 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-25 20:05:46.007   925  2921 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-25 20:05:46.009   925  2921 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-25 20:05:46.016   925  2921 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-25 20:05:46.021   925  2921 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-25 20:05:46.021   925  2921 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-25 20:05:46.021   925  2921 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-25 20:05:46.021   925  2918 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,10-25 20:05:46.021   925  2921 D ConnectivityService:    accepting network in place of null
10-25 20:05:46.021   925  2918 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-25 20:05:46.022   925  2921 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-25 20:05:46.051   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 20:05:46.052   925  5661 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132501, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-25 20:05:46.088   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 20:05:46.092   925  2921 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-25 20:05:46.092   925  2921 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-25 20:05:46.092  3679  3820 W QCNEJ   : |CORE| network available: 101
,10-25 20:05:46.094   925  2921 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,10-25 20:05:46.097   925   942 D Tethering: MasterInitialState.processMessage what=3
10-25 20:05:46.099  3679  3820 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-25 20:05:46.100  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.100  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:46.100  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:46.100  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:46.100  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:46.100  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:46.100  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:46.100  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:05:46.100  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 20:05:46.100  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 20:05:46.100  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:46.101  3679  3820 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-25 20:05:46.101  3679  3820 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-25 20:05:46.103  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.104  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:46.104  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:46.104  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:46.104  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:46.104  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:46.104  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:46.104  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:05:46.104  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 20:05:46.104  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.104  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 20:05:46.107  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.107  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:46.107  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:46.107  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:46.107  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:46.107  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:46.107  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:05:46.107  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:05:46.107  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 20:05:46.107  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.107  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 20:05:46.114  4926  4959 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-25 20:05:46.114  4926  4959 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-25 20:05:46.114  4926  4959 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-25 20:05:46.114  4926  4959 E SarControlService: no key has been found,reset the power
10-25 20:05:46.115  4926  4993 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-25 20:05:46.115  4926  4993 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-25 20:05:46.115  4926  4993 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-25 20:05:46.115  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 20:05:46.115  4979  4979 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-25 20:05:46.117  4926  4993 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-25 20:05:46.117  4926  4993 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-25 20:05:46.117  4926  4993 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-25 20:05:46.118  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 20:05:46.118  4979  4979 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-25 20:05:46.121  3910  3910 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-25 20:05:46.122  4979  5001 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c1e91f9 HexData = [00000000ec03000000000000ffffffff]
10-25 20:05:46.122  4979  5001 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 20:05:46.123  4979  5001 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-25 20:05:46.123  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 20:05:46.124  4926  4936 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-25 20:05:46.127  3924  3924 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-25 20:05:46.131  3924  3924 D SystemUpdateService: onCreate
,10-25 20:05:46.135  3924  3924 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-25 20:05:46.136  4979  5001 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c1e91f9 HexData = [00000000ed03000000000000ffffffff]
10-25 20:05:46.136  4979  5001 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 20:05:46.136  4979  5001 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,10-25 20:05:46.137  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 20:05:46.137  4926  4938 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-25 20:05:46.138   925  3757 D WifiService: setWifiEnabled: false pid=5515, uid=10077
10-25 20:05:46.138   925  3757 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 20:05:46.140   925  2918 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-25 20:05:46.140   925  2918 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-25 20:05:46.140   925  2918 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-25 20:05:46.140   925  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 20:05:46.149  3924  3924 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
10-25 20:05:46.151   925  5662 D DhcpClient: Clearing IP address
,10-25 20:05:46.152   508   919 D CommandListener: Clearing all IP addresses on wlan0
,10-25 20:05:46.153   508   919 D CommandListener: Setting iface cfg
,10-25 20:05:46.161   925  5663 D DhcpClient: Receive thread stopped
,10-25 20:05:46.162  3924  5309 I iu.UploadsManager: num queued entries: 0
,10-25 20:05:46.162  3924  5309 I iu.UploadsManager: num updated entries: 0
10-25 20:05:46.164   925  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-25 20:05:46.165   925  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-25 20:05:46.165  3924  5673 I SystemUpdateService: active receiver: enabled
,10-25 20:05:46.167  3924  3924 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-25 20:05:46.169  3924  3924 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-25 20:05:46.169   925   925 D RttService: SCAN_AVAILABLE : 1
10-25 20:05:46.169   925  3029 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-25 20:05:46.170   534   534 E Parcel  : Reading a NULL string not supported here.
10-25 20:05:46.172   925  2921 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-25 20:05:46.172  5620  5620 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-25 20:05:46.175   925  2918 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-25 20:05:46.174  3679  3820 W QCNEJ   : |CORE| network lost: 101
10-25 20:05:46.175  3679  3820 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-25 20:05:46.178   925  2918 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-25 20:05:46.181  5620  5620 D SprintDMHelper: simOperator: 
10-25 20:05:46.181  5620  5620 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-25 20:05:46.195   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 20:05:46.196  3924  5309 I iu.SyncManager: NEXT; no task
,10-25 20:05:46.196  3924  5673 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-25 20:05:46.209  3924  5673 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-25 20:05:46.209  3924  5673 I SystemUpdateService: now status is 0 (complete)
10-25 20:05:46.209  3924  5673 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-25 20:05:46.209  3924  5673 I SystemUpdateService: file has been verified
10-25 20:05:46.209  3924  5673 I SystemUpdateService: OTA package size = 21989297
,10-25 20:05:46.215  3924  5673 I SystemUpdateService: showing system update notification
,10-25 20:05:46.217   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 20:05:46.217   508   919 D CommandListener: Clearing all IP addresses on wlan0
10-25 20:05:46.218   925  2921 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-25 20:05:46.218   925  2921 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-25 20:05:46.221   925   942 D Tethering: MasterInitialState.processMessage what=3
10-25 20:05:46.222  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.222  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:46.222  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:46.222  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:46.222  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:46.222  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:46.222  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:46.222  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:46.222  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:46.222  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.222  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:46.223   925  2918 D DhcpClient: doQuit
10-25 20:05:46.223   925  2918 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-25 20:05:46.224   925  5662 D DhcpClient: onQuitting
,10-25 20:05:46.224  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.224  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:46.224  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:46.224  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:46.224  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:05:46.224  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:46.224  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:46.224  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:46.224  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:46.224  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.224  5657  5657 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-25 20:05:46.224  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:46.226  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 20:05:46.227  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:46.227  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:46.227  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:46.227  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:05:46.227  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:46.227  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:46.227  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:46.227  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:46.227  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 20:05:46.227  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:46.229  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.229  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:46.229  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:46.229  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:46.229  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:05:46.229  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:46.229  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:46.229  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:46.229  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:46.229  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.229  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:46.229  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.230  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:46.230  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:46.230  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:46.230  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:05:46.230  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:46.230  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:46.230  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:46.230  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 20:05:46.230  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:46.230  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:46.230  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:46.231  3910  3910 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-25 20:05:46.234  4926  4959 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-25 20:05:46.234  4926  4959 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-25 20:05:46.234  4926  4959 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-25 20:05:46.234  4926  4959 E SarControlService: no key has been found,reset the power
10-25 20:05:46.234  4926  4993 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-25 20:05:46.234  4926  4993 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-25 20:05:46.234  4926  4993 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-25 20:05:46.235  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 20:05:46.235  4979  4979 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-25 20:05:46.236  3924  3924 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-25 20:05:46.237  4926  4993 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-25 20:05:46.237  4926  4993 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-25 20:05:46.237  4926  4993 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-25 20:05:46.237  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 20:05:46.238  4979  4979 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-25 20:05:46.242  3924  3924 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-25 20:05:46.241  4979  5001 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c1e91f9 HexData = [00000000ee03000000000000ffffffff]
10-25 20:05:46.244  4979  5001 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 20:05:46.244  4979  5001 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-25 20:05:46.244  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 20:05:46.244  4926  4938 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-25 20:05:46.245  5657  5657 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-25 20:05:46.245  4979  5001 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c1e91f9 HexData = [00000000ef03000000000000ffffffff]
10-25 20:05:46.245  4979  5001 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 20:05:46.246  4979  5001 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-25 20:05:46.246  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 20:05:46.247  4926  4936 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-25 20:05:46.247  5657  5657 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-25 20:05:46.256  3924  3924 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-25 20:05:46.262   925   925 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
10-25 20:05:46.262  3924  5309 I iu.UploadsManager: num queued entries: 0
10-25 20:05:46.262  3924  5309 I iu.UploadsManager: num updated entries: 0
,10-25 20:05:46.265  3924  3924 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-25 20:05:46.266  3924  3924 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-25 20:05:46.268  5620  5620 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-25 20:05:46.270   508   919 E Netd    : netlink response contains error (No such file or directory)
10-25 20:05:46.271   925  2921 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-25 20:05:46.274  5620  5620 D SprintDMHelper: simOperator: 
,10-25 20:05:46.274  5620  5620 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-25 20:05:46.277  5657  5657 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-25 20:05:46.281  3924  5309 I iu.SyncManager: NEXT; no task
,10-25 20:05:46.289  3924  5691 I SystemUpdateService: active receiver: enabled
,10-25 20:05:46.298  5657  5657 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-25 20:05:46.300  3924  5691 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-25 20:05:46.305  3924  5691 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-25 20:05:46.305  3924  5691 I SystemUpdateService: now status is 0 (complete)
10-25 20:05:46.305  3924  5691 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-25 20:05:46.305  3924  5691 I SystemUpdateService: file has been verified
10-25 20:05:46.305  3924  5691 I SystemUpdateService: OTA package size = 21989297
,10-25 20:05:46.310  3924  5691 I SystemUpdateService: showing system update notification
,10-25 20:05:46.317   925   925 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-25 20:05:46.319  3924  3924 D SystemUpdateService: onDestroy
,10-25 20:05:46.399   925  2918 D wifi    : In wifi stop Hal
,10-25 20:05:46.399   925  2918 D wifi    : halHandle = 0x7f70a5b680, mVM = 0x7f8d00d140, mCls = 0x1019c2
10-25 20:05:46.400   925  5656 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-25 20:05:46.400   925  5656 D WifiHAL : Got a signal to exit!!!
10-25 20:05:46.400   925  5656 I WifiHAL : Exit wifi_event_loop
10-25 20:05:46.400   925  2918 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,10-25 20:05:46.400   925  2918 E WifiHAL : Event processing terminated
10-25 20:05:46.400   925  2918 D wifi    : In wifi cleaned up handler
10-25 20:05:46.400   925  2918 I WifiHAL : Internal cleanup completed
,10-25 20:05:46.403  3658  4130 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 20:05:46.403  4384  4384 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 20:05:46.404  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:46.404  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:46.406  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:46.427   925  5656 D wifi    : set interface wlan0 flags (DOWN)
,10-25 20:05:46.427   925  2918 D WifiNative-HAL: HAL event thread stopped successfully
,10-25 20:05:46.583   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:46.634   925   942 D Tethering: InitialState.processMessage what=4
,10-25 20:05:46.640   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-25 20:05:47.093   925  2921 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-25 20:05:47.583   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-25 20:05:51.035   925  5660 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,10-25 20:05:51.036   925  2921 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-25 20:05:51.175   925   942 I ActivityManager: Start proc 5694:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-25 20:05:51.266  5694  5694 D AdapterServiceConfig: Adding HeadsetService
,10-25 20:05:51.266  5694  5694 D AdapterServiceConfig: Adding A2dpService
10-25 20:05:51.266  5694  5694 D AdapterServiceConfig: Adding HidService
,10-25 20:05:51.266  5694  5694 D AdapterServiceConfig: Adding HealthService
,10-25 20:05:51.267  5694  5694 D AdapterServiceConfig: Adding PanService
10-25 20:05:51.267  5694  5694 D AdapterServiceConfig: Adding GattService
10-25 20:05:51.267  5694  5694 D AdapterServiceConfig: Adding BluetoothMapService
10-25 20:05:51.267  5694  5694 D AdapterServiceConfig: Adding SapService
,10-25 20:05:51.279   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39682d:true
,10-25 20:05:51.279  5694  5694 D BluetoothAdapterState: make() - Creating AdapterState
,10-25 20:05:51.282  5694  5694 I bt_bluedroid: init
,10-25 20:05:51.282  5694  5706 I BluetoothAdapterState: Entering OffState
,10-25 20:05:51.284  5694  5707 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-25 20:05:51.284  5694  5707 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-25 20:05:51.284  5694  5707 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-25 20:05:51.285  5694  5707 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-25 20:05:51.285  5694  5694 I bt_bluedroid: get_profile_interface socket
,10-25 20:05:51.287  5694  5710 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-25 20:05:51.287  5694  5694 I bt_bluedroid: get_profile_interface sdp
10-25 20:05:51.288  5694  5710 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-25 20:05:51.291  5694  5705 I bt_bluedroid: config_hci_snoop_log
,10-25 20:05:51.292   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-25 20:05:51.295  5694  5706 D BluetoothAdapterState: Current state: OFF, message: 0
10-25 20:05:51.295  5694  5706 D BluetoothAdapterProperties: Setting state to 14
10-25 20:05:51.295  5694  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-25 20:05:51.297  5694  5706 D BluetoothBondStateMachine: make
,10-25 20:05:51.298  5694  5711 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-25 20:05:51.300  5694  5706 I BluetoothAdapterState: Entering PendingCommandState
,10-25 20:05:51.302  5694  5694 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-25 20:05:51.303  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:05:51.304  5694  5694 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-25 20:05:51.305  5694  5694 D BtGatt.GattService: Received start request. Starting profile...
10-25 20:05:51.305  5694  5694 D BtGatt.GattService: start()
10-25 20:05:51.305  5694  5694 I bt_bluedroid: get_profile_interface gatt
10-25 20:05:51.306  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
10-25 20:05:51.306  5694  5694 D BtGatt.AdvertiseManager: advertise manager created
,10-25 20:05:51.310  5694  5694 V BluetoothAdapterState: isTurningOff()=false
,10-25 20:05:51.310  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:51.310  5694  5694 V BluetoothAdapterState: isBleTurningOn()=true
10-25 20:05:51.310  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 20:05:51.311  5694  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-25 20:05:51.312  5694  5706 I bt_bluedroid: bt_bluedroid
10-25 20:05:51.312  5694  5707 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-25 20:05:51.312  5694  5707 I bt_hci  : start_up
,10-25 20:05:51.317  5694  5707 I bt_vendor: alloc value 0xf3fb9871,
10-25 20:05:51.317  5694  5707 I bt_vendor: init
10-25 20:05:51.317  5694  5707 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-25 20:05:51.317  5694  5707 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-25 20:05:51.425  5694  5707 D bt_hci  : start_up starting async portion
10-25 20:05:51.425  5694  5714 I bt_hci  : event_finish_startup
10-25 20:05:51.425  5694  5714 I bt_hci_h4: hal_open
10-25 20:05:51.425  5694  5714 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-25 20:05:51.421  5715  5715 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 20:05:51.427  5694  5714 I bt_userial_vendor: device fd = 54 open
,10-25 20:05:51.439  5694  5714 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-25 20:05:51.441  5694  5714 D bt_hwcfg: Chipset BCM4358A3
,10-25 20:05:51.441  5694  5714 D bt_hwcfg: Target name = [BCM4358A3]
10-25 20:05:51.441  5694  5714 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-25 20:05:51.812  5694  5714 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-25 20:05:51.813  5694  5714 D bt_hwcfg: Settlement delay -- 100 ms
10-25 20:05:51.813  5694  5714 I bt_hwcfg: Setting fw settlement delay to 100 
,10-25 20:05:51.947  5694  5714 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-25 20:05:51.947  5694  5714 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
10-25 20:05:51.948  5694  5714 I bt_hwcfg: vendor lib fwcfg completed
10-25 20:05:51.949  5694  5714 I bt_vendor: firmware callback
10-25 20:05:51.949  5694  5714 I bt_hci  : firmware_config_callback
10-25 20:05:51.957  5694  5717 I bt_btu  : btu_task pending for preload complete event
10-25 20:05:51.957  5694  5717 I bt_btu_task: Bluetooth chip preload is complete
10-25 20:05:51.957  5694  5717 I bt_btu  : btu_task received preload complete event
,10-25 20:05:51.964  5694  5717 I         : BTE_InitTraceLevels -- TRC_HCI
,10-25 20:05:51.965  5694  5717 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-25 20:05:51.965  5694  5717 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-25 20:05:51.965  5694  5717 I         : BTE_InitTraceLevels -- TRC_AVDT
10-25 20:05:51.965  5694  5717 I         : BTE_InitTraceLevels -- TRC_AVRC
10-25 20:05:51.965  5694  5717 I         : BTE_InitTraceLevels -- TRC_A2D
10-25 20:05:51.965  5694  5717 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-25 20:05:51.965  5694  5717 I         : BTE_InitTraceLevels -- TRC_BTM
,10-25 20:05:51.965  5694  5717 I         : BTE_InitTraceLevels -- TRC_GAP
10-25 20:05:51.966  5694  5717 I         : BTE_InitTraceLevels -- TRC_PAN
,10-25 20:05:51.966  5694  5717 I         : BTE_InitTraceLevels -- TRC_SDP
10-25 20:05:51.966  5694  5717 I         : BTE_InitTraceLevels -- TRC_GATT
10-25 20:05:51.966  5694  5717 I         : BTE_InitTraceLevels -- TRC_SMP
10-25 20:05:51.966  5694  5717 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-25 20:05:51.966  5694  5717 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-25 20:05:52.049  5694  5717 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f37549
,10-25 20:05:52.049  5694  5717 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f37549 
,10-25 20:05:52.069  5694  5710 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-25 20:05:52.070  5694  5710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-25 20:05:52.071  5694  5710 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
10-25 20:05:52.073  5694  5710 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-25 20:05:52.075  5694  5710 D BluetoothAdapterProperties: Scan Mode:20
10-25 20:05:52.076  5694  5710 D BluetoothAdapterProperties: Discoverable Timeout:120
10-25 20:05:52.076  5694  5710 D bt_hci  : do_postload posting postload work item
,10-25 20:05:52.076  5694  5714 I bt_hci  : event_postload
10-25 20:05:52.076  5694  5714 I bt_vendor: sco_config_cb
10-25 20:05:52.076  5694  5714 I bt_hci  : sco_config_callback postload finished.
10-25 20:05:52.079  5694  5710 D bt_bte_conf: Device ID record 1 : primary
10-25 20:05:52.079  5694  5710 D bt_bte_conf:   vendorId            = 000f
10-25 20:05:52.079  5694  5710 D bt_bte_conf:   vendorIdSource      = 0001
10-25 20:05:52.079  5694  5710 D bt_bte_conf:   product             = 1200
10-25 20:05:52.079  5694  5710 D bt_bte_conf:   version             = 1436
10-25 20:05:52.079  5694  5710 D bt_bte_conf:   clientExecutableURL = 
10-25 20:05:52.079  5694  5710 D bt_bte_conf:   serviceDescription  = 
10-25 20:05:52.079  5694  5710 D bt_bte_conf:   documentationURL    = 
10-25 20:05:52.079  5694  5710 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-25 20:05:52.080  5694  5707 D bt_stack_manager: event_start_up_stack finished
,10-25 20:05:52.081  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:52.082  5694  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-25 20:05:52.082  5694  5706 D BluetoothAdapterProperties: Setting state to 15
10-25 20:05:52.082  5694  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-25 20:05:52.084  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:52.085  5694  5706 I BluetoothAdapterState: Entering BleOnState
10-25 20:05:52.087  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:52.088  5694  5706 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-25 20:05:52.089  5694  5706 D BluetoothAdapterProperties: Setting state to 11
10-25 20:05:52.089  5694  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-25 20:05:52.090  5694  5714 I bt_vendor: low_power_mode_cb
,10-25 20:05:52.093  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:05:52.094  5694  5694 D HeadsetService: Received start request. Starting profile...
10-25 20:05:52.098  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:52.100  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:52.102  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:52.104  5694  5694 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-25 20:05:52.104  5694  5694 D HeadsetStateMachine: make
,10-25 20:05:52.106  5694  5706 I BluetoothAdapterState: Entering PendingCommandState
,10-25 20:05:52.113  5694  5694 D HeadsetStateMachine: max_hf_connections = 1
,10-25 20:05:52.113  5694  5694 I bt_bluedroid: get_profile_interface handsfree
10-25 20:05:52.113  5694  5710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-25 20:05:52.114  5694  5710 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-25 20:05:52.116  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:05:52.117  5694  5694 D A2dpService: Received start request. Starting profile...
,10-25 20:05:52.118  5694  5694 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-25 20:05:52.118  5694  5694 I bt_bluedroid: get_profile_interface avrcp
,10-25 20:05:52.122  5694  5694 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-25 20:05:52.123  5694  5694 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-25 20:05:52.123  5694  5694 D A2dpStateMachine: make
,10-25 20:05:52.124  5694  5694 I bt_bluedroid: get_profile_interface a2dp
,10-25 20:05:52.124  5694  5710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-25 20:05:52.127  5694  5725 D A2dpStateMachine: Enter Disconnected: -2
,10-25 20:05:52.127  5694  5694 I BluetoothHidServiceJni: classInitNative: succeeds
,10-25 20:05:52.128  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:05:52.129  5575  5575 D BluetoothInputDevice: Proxy object connected
10-25 20:05:52.129  5694  5694 D HidService: Received start request. Starting profile...
10-25 20:05:52.129  5694  5694 I bt_bluedroid: get_profile_interface hidhost
,10-25 20:05:52.129  5694  5694 D HidService: setHidService(): set to: null
10-25 20:05:52.129  5694  5710 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f1856d
10-25 20:05:52.129  5694  5710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-25 20:05:52.129  5575  5575 D HidProfile: Bluetooth service connected
10-25 20:05:52.130  5694  5694 I BluetoothHealthServiceJni: classInitNative: succeeds
10-25 20:05:52.130  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:05:52.131  5694  5694 D HealthService: Received start request. Starting profile...
,10-25 20:05:52.132  5694  5694 I bt_bluedroid: get_profile_interface health
10-25 20:05:52.133  5694  5694 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-25 20:05:52.133  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:05:52.135  5575  5575 D BluetoothPan: BluetoothPAN Proxy object connected
10-25 20:05:52.135  5694  5694 D PanService: Received start request. Starting profile...
10-25 20:05:52.135  5694  5694 D BluetoothPanServiceJni: initializeNative(L110): pan
10-25 20:05:52.135  5694  5694 I bt_bluedroid: get_profile_interface pan
10-25 20:05:52.135  5575  5575 D PanProfile: Bluetooth service connected
10-25 20:05:52.135  5694  5710 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-25 20:05:52.137  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:05:52.138  5575  5575 D BluetoothMap: Proxy object connected
,10-25 20:05:52.138  5694  5694 D BluetoothMapService: Received start request. Starting profile...
10-25 20:05:52.138  5694  5694 D BluetoothMapService: start()
10-25 20:05:52.139  5575  5575 D MapProfile: Bluetooth service connected
10-25 20:05:52.139  5575  5575 D BluetoothMap: getConnectedDevices()
10-25 20:05:52.139  5575  5575 D BluetoothMap: Bluetooth is Not enabled
,10-25 20:05:52.141  5694  5694 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-25 20:05:52.142  5694  5694 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-25 20:05:52.142  5694  5694 D BluetoothMapAppObserver: createReceiver()
10-25 20:05:52.143  5694  5694 D BluetoothMapAppObserver: initObservers()
10-25 20:05:52.143  5694  5694 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-25 20:05:52.151  5694  5694 V SapService: SapBinder()
10-25 20:05:52.151  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:05:52.152  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-25 20:05:52.152  5694  5694 D SapService: Received start request. Starting profile...
10-25 20:05:52.152  5694  5694 V SapService: start()
,10-25 20:05:52.155  5694  5694 V BluetoothAdapterState: isTurningOff()=false
10-25 20:05:52.155  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-25 20:05:52.155  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:52.155  5694  5723 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
10-25 20:05:52.155  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 20:05:52.155  5694  5694 V BluetoothAdapterState: isTurningOff()=false
10-25 20:05:52.155  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-25 20:05:52.155  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:52.155  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:52.155  5694  5694 V BluetoothAdapterState: isTurningOff()=false
10-25 20:05:52.155  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-25 20:05:52.155  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:52.155  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:52.156  5694  5694 V BluetoothAdapterState: isTurningOff()=false
,10-25 20:05:52.156  5694  5694 V BluetoothAdapterState: isTurningOn()=true
,10-25 20:05:52.156  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
,10-25 20:05:52.156  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:52.156  5694  5694 V BluetoothAdapterState: isTurningOff()=false
,10-25 20:05:52.156  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-25 20:05:52.156  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:52.156  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:52.156  5694  5694 V BluetoothAdapterState: isTurningOff()=false
10-25 20:05:52.156  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-25 20:05:52.156  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:52.156  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 20:05:52.158  5694  5694 V BluetoothAdapterState: isTurningOff()=false
10-25 20:05:52.158  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-25 20:05:52.158  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:52.158  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:52.158  5694  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-25 20:05:52.158  5694  5706 D BluetoothAdapterProperties: ScanMode =  20
10-25 20:05:52.158  5694  5706 D BluetoothAdapterProperties: State =  11
10-25 20:05:52.158  5694  5706 D BluetoothAdapterProperties: Setting state to 12
10-25 20:05:52.158  5694  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-25 20:05:52.159  5694  5706 I BluetoothAdapterState: Entering OnState
10-25 20:05:52.159  5575  5592 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-25 20:05:52.160  3062  3941 D BluetoothMap: onBluetoothStateChange: up=true
10-25 20:05:52.161  5694  5710 D BluetoothAdapterProperties: Scan Mode:21
10-25 20:05:52.161  5694  5710 D BluetoothAdapterProperties: Discoverable Timeout:120
10-25 20:05:52.162  5515  5515 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-25 20:05:52.164  3062  3062 D BluetoothMap: Proxy object connected
10-25 20:05:52.164  5575  5591 D BluetoothMap: onBluetoothStateChange: up=true
10-25 20:05:52.164  3062  3062 D MapProfile: Bluetooth service connected
10-25 20:05:52.164  3062  3062 D BluetoothMap: getConnectedDevices()
10-25 20:05:52.164   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 20:05:52.164  3062  3077 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 20:05:52.165  3062  3941 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-25 20:05:52.167   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-25 20:05:52.167  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:52.167  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:52.167  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:52.167  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:05:52.167  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:05:52.167  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:52.167  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:52.167  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:52.168   925   925 D BluetoothA2dp: Proxy object connected
10-25 20:05:52.168  3062  3082 D BluetoothPan: onBluetoothStateChange on: true
10-25 20:05:52.168  3062  3062 D BluetoothA2dp: Proxy object connected
10-25 20:05:52.169  5694  5694 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-25 20:05:52.169  5694  5694 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,10-25 20:05:52.170  3062  3077 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-25 20:05:52.171  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:52.171  3062  3062 D BluetoothPan: BluetoothPAN Proxy object connected
10-25 20:05:52.171  3062  3062 D PanProfile: Bluetooth service connected
10-25 20:05:52.172  5694  5694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 20:05:52.173  3062  3062 D BluetoothInputDevice: Proxy object connected
10-25 20:05:52.173  3062  3062 D HidProfile: Bluetooth service connected
10-25 20:05:52.174  5694  5694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 20:05:52.174  3703  3737 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-25 20:05:52.174  5575  5592 D BluetoothPan: onBluetoothStateChange on: true
,10-25 20:05:52.175  3062  3077 D BluetoothPbap: onBluetoothStateChange: up=true
,10-25 20:05:52.176  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:52.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:52.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:52.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:05:52.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:05:52.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:52.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:52.176  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:52.176  5694  5694 D ObexServerSockets: Succeed to create listening sockets 
10-25 20:05:52.176  5694  5694 D ObexServerSockets0: startAccept()
10-25 20:05:52.176  5694  5694 D ObexServerSockets0: prepareForNewConnect()
10-25 20:05:52.177  5575  5591 D BluetoothPbap: onBluetoothStateChange: up=true
10-25 20:05:52.178   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-25 20:05:52.178   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 20:05:52.178  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:52.178  5694  5694 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-25 20:05:52.179   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
,10-25 20:05:52.179  5694  5731 D ObexServerSockets0: Accepting socket connection...
,10-25 20:05:52.180  5694  5694 D BluetoothSdpJni: SDP Create record success - handle: 0
10-25 20:05:52.180  5694  5694 D BluetoothMapService: onReceive
10-25 20:05:52.180  5694  5694 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-25 20:05:52.180  5694  5694 D BluetoothMapService: STATE_ON
10-25 20:05:52.180  5694  5732 D ObexServerSockets0: Accepting socket connection...
10-25 20:05:52.183  5575  5575 D LocalBluetoothProfileManager: Adding local A2DP profile
,10-25 20:05:52.184  5694  5734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 20:05:52.184  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:52.184  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:52.184  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:52.184  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:05:52.184  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:05:52.184  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:52.184  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:52.184  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:52.186  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:52.186  5575  5575 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-25 20:05:52.186  5515  5515 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-25 20:05:52.187  5694  5734 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,10-25 20:05:52.187  5694  5734 D BluetoothSdpJni: SDP Create record success - handle: 1
10-25 20:05:52.187  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:52.189  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:52.190  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:52.192  5575  5575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-25 20:05:52.196  5575  5575 D BluetoothA2dp: Proxy object connected
,10-25 20:05:52.200  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 20:05:52.203  5575  5575 D DockEventReceiver: finishStartingService: stopping service
,10-25 20:05:52.207  3062  3062 D BluetoothPbap: Proxy object connected
,10-25 20:05:52.207  3062  3062 D PbapServerProfile: Bluetooth service connected
,10-25 20:05:52.207  5694  5694 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-25 20:05:52.207  5694  5694 D ObexServerSockets0: prepareForNewConnect()
,10-25 20:05:52.210  5575  5575 D BluetoothPbap: Proxy object connected
,10-25 20:05:52.210  5575  5575 D PbapServerProfile: Bluetooth service connected
,10-25 20:05:52.214  5694  5738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 20:05:52.230  5694  5742 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 20:05:52.231  5694  5742 I BtOppRfcommListener: Accept thread started.
,10-25 20:05:52.265   925   925 D BluetoothHeadset: Proxy object connected
10-25 20:05:52.265   925   925 D BluetoothHeadset: Proxy object connected
,10-25 20:05:52.266  3062  3082 D BluetoothHeadset: Proxy object connected
,10-25 20:05:52.266  3062  3062 D HeadsetProfile: Bluetooth service connected
10-25 20:05:52.266  3062  3077 D BluetoothHeadset: Proxy object connected
10-25 20:05:52.266  3703  3960 D BluetoothHeadset: Proxy object connected
10-25 20:05:52.266   925   925 D BluetoothHeadset: Proxy object connected
10-25 20:05:52.268  3062  3062 D HeadsetProfile: Bluetooth service connected
,10-25 20:05:52.274  3703  3754 D BluetoothHeadset: Proxy object connected
,10-25 20:05:52.278   925   942 D BluetoothHeadset: Proxy object connected
,10-25 20:05:52.278   925   942 D BluetoothHeadset: Proxy object connected
,10-25 20:05:52.288  5575  5592 D BluetoothHeadset: Proxy object connected
,10-25 20:05:52.289  5575  5575 D HeadsetProfile: Bluetooth service connected
,10-25 20:05:53.724  3590  3792 I Keyboard.Facilitator.LanguageModelFlusher: run()
,10-25 20:05:53.724  3590  3792 I Keyboard.Facilitator: flushDynamicLanguageModels()
,10-25 20:05:53.755  3521  3521 I ConfigService: onCreate
,10-25 20:05:54.024   925  2921 D ConnectivityService: handlePromptUnvalidated 101
,10-25 20:05:56.159  5694  5706 D BluetoothAdapterState: Current state: ON, message: 23
,10-25 20:05:56.159  5694  5706 D BluetoothAdapterProperties: Setting state to 13
10-25 20:05:56.159  5694  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-25 20:05:56.161  5694  5706 D BluetoothAdapterProperties: onBluetoothDisable()
,10-25 20:05:56.164  5694  5706 I BluetoothAdapterState: Entering PendingCommandState
,10-25 20:05:56.167  5694  5694 D BluetoothMapService: onReceive
,10-25 20:05:56.168  5694  5694 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-25 20:05:56.168  5694  5694 D BluetoothMapService: STATE_TURNING_OFF
10-25 20:05:56.168  5694  5694 D BluetoothMapService: MAP Service closeService in
,10-25 20:05:56.169  5694  5694 D BluetoothMapMasInstance0: MAP Service shutdown
10-25 20:05:56.169  5694  5694 D ObexServerSockets0: shutdown(block = true)
10-25 20:05:56.170  5694  5694 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-25 20:05:56.171  5694  5694 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-25 20:05:56.171  5694  5719 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-25 20:05:56.171  5694  5731 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-25 20:05:56.171  5694  5732 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-25 20:05:56.173  5694  5710 D BluetoothAdapterProperties: Scan Mode:20
10-25 20:05:56.174  5694  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-25 20:05:56.177  5694  5694 I BtOppRfcommListener: stopping Accept Thread
10-25 20:05:56.177  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:56.177  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:56.177  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:56.177  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:56.177  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:05:56.177  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:56.177  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:56.177  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:56.177  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:56.178  5694  5742 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-25 20:05:56.178  5694  5742 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-25 20:05:56.181  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:56.181  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:05:56.184  5575  5575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-25 20:05:56.184  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:56.185  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:56.185  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:56.185  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:56.185  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:05:56.185  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:56.185  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:56.185  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:56.185  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:56.185  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:56.185  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:56.188  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:56.188  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:05:56.188  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:05:56.188  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:05:56.188  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:05:56.188  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 20:05:56.188  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:05:56.188  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:05:56.188  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:05:56.189  5515  5515 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 20:05:56.189  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:05:56.190  5575  5575 D DockEventReceiver: finishStartingService: stopping service
10-25 20:05:56.190  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:56.192  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:56.193  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:56.201  5694  5694 D HeadsetService: Received stop request...Stopping profile...
,10-25 20:05:56.203   925   925 D BluetoothHeadset: Proxy object disconnected
10-25 20:05:56.204  5694  5694 D A2dpService: Received stop request...Stopping profile...
10-25 20:05:56.204  5694  5725 D A2dpStateMachine: Exit Disconnected: -1
10-25 20:05:56.204  5575  5592 D BluetoothHeadset: Proxy object disconnected
10-25 20:05:56.205   925   925 D BluetoothHeadset: Proxy object disconnected
,10-25 20:05:56.205  3062  3941 D BluetoothHeadset: Proxy object disconnected
10-25 20:05:56.205  3062  3062 D BluetoothA2dp: Proxy object disconnected
10-25 20:05:56.205  3062  3062 D HeadsetProfile: Bluetooth service disconnected
10-25 20:05:56.205  5575  5575 D HeadsetProfile: Bluetooth service disconnected
10-25 20:05:56.206  3703  3961 D BluetoothHeadset: Proxy object disconnected
10-25 20:05:56.206   925   925 D BluetoothHeadset: Proxy object disconnected
,10-25 20:05:56.206   925   925 D BluetoothA2dp: Proxy object disconnected
10-25 20:05:56.207  5694  5694 D HidService: Received stop request...Stopping profile...
10-25 20:05:56.207  5694  5694 D HidService: Stopping Bluetooth HidService
10-25 20:05:56.207  5575  5575 D BluetoothA2dp: Proxy object disconnected
,10-25 20:05:56.208  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-25 20:05:56.208  5575  5575 D BluetoothInputDevice: Proxy object disconnected
10-25 20:05:56.208  5575  5575 D HidProfile: Bluetooth service disconnected
10-25 20:05:56.208  3062  3062 D BluetoothInputDevice: Proxy object disconnected
10-25 20:05:56.208  3062  3062 D HidProfile: Bluetooth service disconnected
10-25 20:05:56.209  5694  5694 D HealthService: Received stop request...Stopping profile...
,10-25 20:05:56.210  5694  5694 D PanService: Received stop request...Stopping profile...
10-25 20:05:56.211  5575  5575 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-25 20:05:56.211  5575  5575 D PanProfile: Bluetooth service disconnected
10-25 20:05:56.211  3062  3062 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-25 20:05:56.211  3062  3062 D PanProfile: Bluetooth service disconnected
,10-25 20:05:56.211  5694  5694 D BluetoothMapService: Received stop request...Stopping profile...
10-25 20:05:56.211  5694  5694 D BluetoothMapService: stop()
,10-25 20:05:56.212  5694  5694 D BluetoothMapAppObserver: deinitObservers()
,10-25 20:05:56.212  5694  5694 D BluetoothMapAppObserver: removeReceiver()
10-25 20:05:56.213  3062  3062 D BluetoothMap: Proxy object disconnected
10-25 20:05:56.213  3062  3062 D MapProfile: Bluetooth service disconnected
10-25 20:05:56.213  5575  5575 D BluetoothMap: Proxy object disconnected
10-25 20:05:56.213  5575  5575 D MapProfile: Bluetooth service disconnected
,10-25 20:05:56.213  5694  5694 D SapService: Received stop request...Stopping profile...
10-25 20:05:56.213  5694  5694 V SapService: stop()
,10-25 20:05:56.215  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:56.215  5694  5694 V BluetoothAdapterState: isTurningOn()=false
,10-25 20:05:56.215  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:56.215  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 20:05:56.218  5694  5694 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-25 20:05:56.218  5694  5694 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-25 20:05:56.218  5694  5710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-25 20:05:56.218  5694  5717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-25 20:05:56.218  5694  5717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 20:05:56.218  5694  5717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 20:05:56.218  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:56.219  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:56.219  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:56.219  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:56.219  5694  5710 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-25 20:05:56.219  5694  5710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-25 20:05:56.220  5694  5717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 20:05:56.220  5694  5717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 20:05:56.220  5694  5717 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-25 20:05:56.220  5694  5717 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-25 20:05:56.220  5694  5717 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-25 20:05:56.220  5694  5717 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-25 20:05:56.221  5575  5575 D BluetoothPbap: Proxy object disconnected
10-25 20:05:56.221  5575  5575 D PbapServerProfile: Bluetooth service disconnected
10-25 20:05:56.221  3062  3062 D BluetoothPbap: Proxy object disconnected
10-25 20:05:56.221  3062  3062 D PbapServerProfile: Bluetooth service disconnected
,10-25 20:05:56.221  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:56.221  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:56.221  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:56.221  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:56.222  5694  5694 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,10-25 20:05:56.222  5694  5694 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-25 20:05:56.222  5694  5710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-25 20:05:56.222  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:56.222  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:56.222  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:56.222  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:56.222  5694  5694 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-25 20:05:56.223  5694  5710 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-25 20:05:56.223  5694  5694 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-25 20:05:56.223  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:56.223  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:56.223  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
,10-25 20:05:56.223  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:56.223  5694  5694 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-25 20:05:56.223  5694  5694 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-25 20:05:56.224  5694  5694 D BluetoothMapService: MAP Service closeService in
10-25 20:05:56.224  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:56.224  5694  5694 V BluetoothAdapterState: isTurningOn()=false
,10-25 20:05:56.224  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:56.224  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:56.225  5694  5694 D BluetoothMapService: cleanup()
10-25 20:05:56.225  5694  5694 D BluetoothMapService: MAP Service closeService in
10-25 20:05:56.225  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-25 20:05:56.225  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:56.225  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
,10-25 20:05:56.225  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:05:56.225  5694  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-25 20:05:56.225  5694  5706 D BluetoothAdapterProperties: Setting state to 15
10-25 20:05:56.225  5694  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-25 20:05:56.226  5694  5706 I BluetoothAdapterState: Entering BleOnState
10-25 20:05:56.226  5575  5747 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-25 20:05:56.233  3062  3082 D BluetoothMap: onBluetoothStateChange: up=false
,10-25 20:05:56.233  5575  5592 D BluetoothMap: onBluetoothStateChange: up=false
,10-25 20:05:56.234   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 20:05:56.234  3062  3077 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-25 20:05:56.234  3062  3941 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 20:05:56.235   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 20:05:56.235  3062  3082 D BluetoothPan: onBluetoothStateChange on: false
10-25 20:05:56.235  5575  5591 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 20:05:56.236  5575  5747 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 20:05:56.236  3062  3077 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-25 20:05:56.237  3703  3737 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 20:05:56.237  5575  5592 D BluetoothPan: onBluetoothStateChange on: false
10-25 20:05:56.238  3062  3941 D BluetoothPbap: onBluetoothStateChange: up=false
10-25 20:05:56.238  5575  5591 D BluetoothPbap: onBluetoothStateChange: up=false
10-25 20:05:56.238   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 20:05:56.238   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 20:05:56.239  5694  5706 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-25 20:05:56.239  5694  5706 D BluetoothAdapterProperties: Setting state to 16
10-25 20:05:56.239  5694  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-25 20:05:56.239  5694  5706 D BluetoothAdapterProperties: onBleDisable
10-25 20:05:56.239  5694  5706 I BluetoothAdapterState: Entering PendingCommandState
,10-25 20:05:56.239  5694  5707 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-25 20:05:56.240  5694  5717 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-25 20:05:56.241  5694  5717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 20:05:56.243  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:56.243  5694  5710 D BluetoothAdapterProperties: Scan Mode:20
10-25 20:05:56.244  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:56.246  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:56.247  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:56.247  5575  5575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-25 20:05:56.248  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:05:56.250  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:05:56.252  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 20:05:56.255  5575  5575 D DockEventReceiver: finishStartingService: stopping service
,10-25 20:05:56.448  5694  5710 I bt_hci  : shut_down
,10-25 20:05:56.451  5694  5714 D bt_hwcfg: hw_epilog_process
,10-25 20:05:56.451  5694  5714 I bt_vendor: low_power_mode_cb
,10-25 20:05:56.454  5694  5714 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-25 20:05:56.454  5694  5714 I bt_vendor: epilog_cb
10-25 20:05:56.454  5694  5714 I bt_hci  : epilog_finished_callback
,10-25 20:05:56.456  5694  5710 I bt_hci_h4: hal_close
,10-25 20:05:56.457  5694  5710 I bt_userial_vendor: device fd = 54 close
,10-25 20:05:56.568  5694  5707 D bt_stack_manager: event_shut_down_stack finished.
10-25 20:05:56.568  5694  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-25 20:05:56.571  5694  5706 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-25 20:05:56.571  5694  5694 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-25 20:05:56.572  5694  5694 D BtGatt.GattService: Received stop request...Stopping profile...
,10-25 20:05:56.572  5694  5694 D BtGatt.GattService: stop()
10-25 20:05:56.572  5694  5694 D BtGatt.AdvertiseManager: advertise clients cleared
10-25 20:05:56.574  5694  5694 V BluetoothAdapterState: isTurningOff()=false
10-25 20:05:56.574  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-25 20:05:56.574  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:05:56.574  5694  5694 V BluetoothAdapterState: isBleTurningOff()=true
10-25 20:05:56.574  5694  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-25 20:05:56.574  5694  5706 D BluetoothAdapterProperties: Setting state to 10
,10-25 20:05:56.575  5694  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-25 20:05:56.575  5694  5706 I BluetoothAdapterState: Entering OffState
,10-25 20:05:56.576   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-25 20:05:56.583  5694  5694 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-25 20:05:56.583  5694  5694 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-25 20:05:56.583  5694  5694 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-25 20:05:56.585  5694  5707 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-25 20:05:56.589  5694  5694 I art     : System.exit called, status: 0
,10-25 20:05:56.590  5694  5694 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-25 20:05:56.612   925  3763 I ActivityManager: Process com.android.bluetooth (pid 5694) has died
,10-25 20:05:57.584   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:58.585   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:05:58.786  3521  3521 I ConfigService: onDestroy
,10-25 20:05:59.586   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:00.587   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:01.154  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:06:01.155  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:01.159  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:01.159  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8cf7c50 removed from the list
10-25 20:06:01.159  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:06:01.159  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:01.159  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:06:01.162  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 20:06:01.162  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c5e334e added. We now have 4 listener(s)
10-25 20:06:01.162  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 20:06:01.165  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:01.165  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c5e334e removed from the list
10-25 20:06:01.165  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:06:01.165  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:01.165  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:06:01.168  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 20:06:01.168  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@411cc6f added. We now have 4 listener(s)
10-25 20:06:01.168  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 20:06:01.588   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:02.589   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-25 20:06:05.482   925   945 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,10-25 20:06:05.488   935   935 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[29617]" dev="sockfs" ino=29617 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 20:06:05.488   935   935 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[29617]" dev="sockfs" ino=29617 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 20:06:05.493  3590  3590 I Keyboard.Facilitator: onFinishInput()
,10-25 20:06:05.505   925   945 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-25 20:06:05.505   925   945 I Adreno  : Build Date                       : 12/06/15
10-25 20:06:05.505   925   945 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-25 20:06:05.505   925   945 I Adreno  : Local Branch                     : mybranch17112971
10-25 20:06:05.505   925   945 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-25 20:06:05.505   925   945 I Adreno  : Remote Branch                    : NONE
10-25 20:06:05.505   925   945 I Adreno  : Reconstruct Branch               : NOTHING
,10-25 20:06:05.545   381   407 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (181 us)
,10-25 20:06:06.181  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:06:06.214   925   942 I ActivityManager: Start proc 5754:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-25 20:06:06.256  5515  5515 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-25 20:06:06.257  5515  5515 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,10-25 20:06:06.286   925   945 I sensors : batch
,10-25 20:06:06.287   925   945 V KeyguardServiceDelegate: onScreenTurnedOff()
,10-25 20:06:06.293   925   945 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,10-25 20:06:06.293   925   945 I sensors : activate
10-25 20:06:06.294   381   381 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f86003c00
10-25 20:06:06.294   925   943 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
10-25 20:06:06.294   381   381 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,10-25 20:06:06.295   925  2661 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,10-25 20:06:06.298  5515  5515 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@380656d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4b80d7c, 16908290=android.view.AbsSavedState$1@4b80d7c}, android:focusedViewId=100}]}]
,10-25 20:06:06.298  5515  5515 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
10-25 20:06:06.298  5515  5515 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-25 20:06:06.298  5515  5515 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
10-25 20:06:06.299   925  2661 I hubconnection: sensorhub said: 'activate 7 enable:0'
,10-25 20:06:06.328  5754  5754 D AdapterServiceConfig: Adding HeadsetService
10-25 20:06:06.328  5754  5754 D AdapterServiceConfig: Adding A2dpService
,10-25 20:06:06.329  5754  5754 D AdapterServiceConfig: Adding HidService
10-25 20:06:06.329  5754  5754 D AdapterServiceConfig: Adding HealthService
10-25 20:06:06.329  5754  5754 D AdapterServiceConfig: Adding PanService
10-25 20:06:06.329  5754  5754 D AdapterServiceConfig: Adding GattService
10-25 20:06:06.329  5754  5754 D AdapterServiceConfig: Adding BluetoothMapService
10-25 20:06:06.329  5754  5754 D AdapterServiceConfig: Adding SapService
,10-25 20:06:06.335  5754  5754 D BluetoothAdapterState: make() - Creating AdapterState
10-25 20:06:06.335   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93709a5:true
,10-25 20:06:06.337  5754  5754 I bt_bluedroid: init
10-25 20:06:06.338  5754  5766 I BluetoothAdapterState: Entering OffState
,10-25 20:06:06.339  5754  5767 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-25 20:06:06.340  5754  5767 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,10-25 20:06:06.340  5754  5767 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,10-25 20:06:06.341  5754  5767 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-25 20:06:06.341  5754  5754 I bt_bluedroid: get_profile_interface socket
,10-25 20:06:06.342  5754  5754 I bt_bluedroid: get_profile_interface sdp
,10-25 20:06:06.342  5754  5770 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-25 20:06:06.343  5754  5770 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-25 20:06:06.346  5754  5764 I bt_bluedroid: config_hci_snoop_log
,10-25 20:06:06.346   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
10-25 20:06:06.349  5754  5766 D BluetoothAdapterState: Current state: OFF, message: 0
10-25 20:06:06.349  5754  5766 D BluetoothAdapterProperties: Setting state to 14
10-25 20:06:06.350  5754  5766 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-25 20:06:06.351  5754  5766 D BluetoothBondStateMachine: make
,10-25 20:06:06.353  5754  5771 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-25 20:06:06.355  5754  5766 I BluetoothAdapterState: Entering PendingCommandState
,10-25 20:06:06.356  5754  5754 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-25 20:06:06.357  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
10-25 20:06:06.358  5754  5754 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-25 20:06:06.358  5754  5754 D BtGatt.GattService: Received start request. Starting profile...
10-25 20:06:06.358  5754  5754 D BtGatt.GattService: start()
10-25 20:06:06.358  5754  5754 I bt_bluedroid: get_profile_interface gatt
,10-25 20:06:06.359  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
10-25 20:06:06.359  5754  5754 D BtGatt.AdvertiseManager: advertise manager created
,10-25 20:06:06.362  5754  5754 V BluetoothAdapterState: isTurningOff()=false
10-25 20:06:06.362  5754  5754 V BluetoothAdapterState: isTurningOn()=false
10-25 20:06:06.362  5754  5754 V BluetoothAdapterState: isBleTurningOn()=true
10-25 20:06:06.363  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 20:06:06.363  5754  5766 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-25 20:06:06.364  5754  5766 I bt_bluedroid: bt_bluedroid
10-25 20:06:06.364  5754  5767 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-25 20:06:06.364  5754  5767 I bt_hci  : start_up
,10-25 20:06:06.368  5754  5767 I bt_vendor: alloc value 0xf3fb9871
10-25 20:06:06.368  5754  5767 I bt_vendor: init
,10-25 20:06:06.368  5754  5767 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-25 20:06:06.369  5754  5767 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-25 20:06:06.486  5754  5767 D bt_hci  : start_up starting async portion
,10-25 20:06:06.487  5754  5774 I bt_hci  : event_finish_startup
10-25 20:06:06.487  5754  5774 I bt_hci_h4: hal_open
,10-25 20:06:06.487  5754  5774 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-25 20:06:06.485  5775  5775 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 20:06:06.490  5754  5774 I bt_userial_vendor: device fd = 54 open
,10-25 20:06:06.505  5754  5774 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-25 20:06:06.509  5754  5774 D bt_hwcfg: Chipset BCM4358A3
10-25 20:06:06.509  5754  5774 D bt_hwcfg: Target name = [BCM4358A3]
10-25 20:06:06.509  5754  5774 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-25 20:06:06.601   381   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,10-25 20:06:06.606   381   381 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,10-25 20:06:06.608   925  3032 D SurfaceControl: Excessive delay in setPowerMode(): 314ms
,10-25 20:06:06.627   925   945 I DreamManagerService: Entering dreamland.
,10-25 20:06:06.628   925   945 I PowerManagerService: Dozing...
,10-25 20:06:06.628   925   940 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,10-25 20:06:06.655  3761  3761 W Binder_9: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[30375]" dev="sockfs" ino=30375 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 20:06:06.658  3761  3761 W Binder_9: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[30375]" dev="sockfs" ino=30375 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 20:06:06.660   925  3103 I sensors : batch
,10-25 20:06:06.661   925  3103 I sensors : activate
10-25 20:06:06.665   925  2661 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
10-25 20:06:06.665   925  2661 I hubconnection: sensorhub said: 'activate 21 enable:1'
,10-25 20:06:06.674   513  2944 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,10-25 20:06:06.746  3703  4660 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
10-25 20:06:06.747  3703  4660 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
,10-25 20:06:06.747  3703  4660 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-25 20:06:06.747   526  1292 D         : oem-qmi: Connection accepted
10-25 20:06:06.747   526  1292 D         : oem-qmi: Waiting to accept connection
,10-25 20:06:06.749   925   925 I sensors : activate
,10-25 20:06:06.752   513  2980 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,10-25 20:06:06.752   925  2661 I hubconnection: sensorhub said: 'activate 31 enable:0'
10-25 20:06:06.754  3703  4660 D         : oem_qmi_lib:output 0
,10-25 20:06:06.754  3703  4660 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-25 20:06:06.776  3703  4660 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,10-25 20:06:06.776  3703  4660 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
10-25 20:06:06.777  3703  4660 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-25 20:06:06.777   526  1292 D         : oem-qmi: Connection accepted
10-25 20:06:06.777   526  1292 D         : oem-qmi: Waiting to accept connection
,10-25 20:06:06.783  3703  4660 D         : oem_qmi_lib:output 0
,10-25 20:06:06.783  3703  4660 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-25 20:06:06.979  5754  5774 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-25 20:06:06.979  5754  5774 D bt_hwcfg: Settlement delay -- 100 ms
10-25 20:06:06.979  5754  5774 I bt_hwcfg: Setting fw settlement delay to 100 
,10-25 20:06:07.115  5754  5774 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-25 20:06:07.115  5754  5774 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,10-25 20:06:07.118  5754  5774 I bt_hwcfg: vendor lib fwcfg completed
10-25 20:06:07.119  5754  5774 I bt_vendor: firmware callback
,10-25 20:06:07.119  5754  5774 I bt_hci  : firmware_config_callback
,10-25 20:06:07.130  5754  5781 I bt_btu  : btu_task pending for preload complete event
10-25 20:06:07.130  5754  5781 I bt_btu_task: Bluetooth chip preload is complete
,10-25 20:06:07.130  5754  5781 I bt_btu  : btu_task received preload complete event
,10-25 20:06:07.136  5754  5781 I         : BTE_InitTraceLevels -- TRC_HCI
,10-25 20:06:07.136  5754  5781 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-25 20:06:07.136  5754  5781 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-25 20:06:07.136  5754  5781 I         : BTE_InitTraceLevels -- TRC_AVDT
10-25 20:06:07.137  5754  5781 I         : BTE_InitTraceLevels -- TRC_AVRC
10-25 20:06:07.137  5754  5781 I         : BTE_InitTraceLevels -- TRC_A2D
10-25 20:06:07.137  5754  5781 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-25 20:06:07.137  5754  5781 I         : BTE_InitTraceLevels -- TRC_BTM
10-25 20:06:07.137  5754  5781 I         : BTE_InitTraceLevels -- TRC_GAP
10-25 20:06:07.137  5754  5781 I         : BTE_InitTraceLevels -- TRC_PAN
10-25 20:06:07.137  5754  5781 I         : BTE_InitTraceLevels -- TRC_SDP
10-25 20:06:07.137  5754  5781 I         : BTE_InitTraceLevels -- TRC_GATT
,10-25 20:06:07.138  5754  5781 I         : BTE_InitTraceLevels -- TRC_SMP
10-25 20:06:07.138  5754  5781 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-25 20:06:07.138  5754  5781 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-25 20:06:07.236  5754  5781 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f37549
10-25 20:06:07.237  5754  5781 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f37549 
,10-25 20:06:07.258  5754  5770 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-25 20:06:07.260  5754  5770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-25 20:06:07.260  5754  5770 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-25 20:06:07.263  5754  5770 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-25 20:06:07.266  5754  5770 D BluetoothAdapterProperties: Scan Mode:20
10-25 20:06:07.267  5754  5770 D BluetoothAdapterProperties: Discoverable Timeout:120
10-25 20:06:07.267  5754  5770 D bt_hci  : do_postload posting postload work item
10-25 20:06:07.267  5754  5774 I bt_hci  : event_postload
,10-25 20:06:07.267  5754  5774 I bt_vendor: sco_config_cb
10-25 20:06:07.267  5754  5774 I bt_hci  : sco_config_callback postload finished.
,10-25 20:06:07.272  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:06:07.275  5754  5770 D bt_bte_conf: Device ID record 1 : primary
10-25 20:06:07.275  5754  5770 D bt_bte_conf:   vendorId            = 000f
,10-25 20:06:07.275  5754  5770 D bt_bte_conf:   vendorIdSource      = 0001
10-25 20:06:07.275  5754  5770 D bt_bte_conf:   product             = 1200
10-25 20:06:07.276  5754  5770 D bt_bte_conf:   version             = 1436
10-25 20:06:07.276  5754  5770 D bt_bte_conf:   clientExecutableURL = 
10-25 20:06:07.276  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:06:07.276  5754  5770 D bt_bte_conf:   serviceDescription  = 
,10-25 20:06:07.276  5754  5770 D bt_bte_conf:   documentationURL    = 
10-25 20:06:07.276  5754  5770 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-25 20:06:07.276  5754  5767 D bt_stack_manager: event_start_up_stack finished
,10-25 20:06:07.277  5754  5766 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-25 20:06:07.277  5754  5774 I bt_vendor: low_power_mode_cb
10-25 20:06:07.277  5754  5766 D BluetoothAdapterProperties: Setting state to 15
10-25 20:06:07.277  5754  5766 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-25 20:06:07.278  5754  5766 I BluetoothAdapterState: Entering BleOnState
,10-25 20:06:07.283  5754  5766 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-25 20:06:07.283  5754  5766 D BluetoothAdapterProperties: Setting state to 11
,10-25 20:06:07.283  5754  5766 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-25 20:06:07.290  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:06:07.291  5754  5754 D HeadsetService: Received start request. Starting profile...
,10-25 20:06:07.293  5754  5754 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-25 20:06:07.293  5754  5754 D HeadsetStateMachine: make
,10-25 20:06:07.298  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:06:07.300  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:06:07.308  5754  5766 I BluetoothAdapterState: Entering PendingCommandState
,10-25 20:06:07.309  5754  5754 D HeadsetStateMachine: max_hf_connections = 1
10-25 20:06:07.309  5754  5754 I bt_bluedroid: get_profile_interface handsfree
10-25 20:06:07.309  5754  5770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-25 20:06:07.310  5754  5770 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,10-25 20:06:07.313  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:06:07.313  5754  5754 D A2dpService: Received start request. Starting profile...
,10-25 20:06:07.314  5754  5754 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-25 20:06:07.314  5754  5754 I bt_bluedroid: get_profile_interface avrcp
,10-25 20:06:07.319  5754  5754 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-25 20:06:07.320  5754  5754 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-25 20:06:07.320  5754  5754 D A2dpStateMachine: make
,10-25 20:06:07.321  5754  5754 I bt_bluedroid: get_profile_interface a2dp
,10-25 20:06:07.322  5754  5770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-25 20:06:07.323  5754  5789 D A2dpStateMachine: Enter Disconnected: -2
,10-25 20:06:07.323  5754  5754 I BluetoothHidServiceJni: classInitNative: succeeds
,10-25 20:06:07.324  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:06:07.325  5754  5754 D HidService: Received start request. Starting profile...
10-25 20:06:07.325  5754  5754 I bt_bluedroid: get_profile_interface hidhost
,10-25 20:06:07.325  5754  5754 D HidService: setHidService(): set to: null
10-25 20:06:07.325  5754  5770 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f1856d
10-25 20:06:07.325  5754  5770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-25 20:06:07.327  5754  5754 I BluetoothHealthServiceJni: classInitNative: succeeds
10-25 20:06:07.327  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
10-25 20:06:07.328  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-25 20:06:07.328  5754  5754 D HealthService: Received start request. Starting profile...
,10-25 20:06:07.330  5754  5754 I bt_bluedroid: get_profile_interface health
,10-25 20:06:07.330  5754  5754 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-25 20:06:07.331  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
10-25 20:06:07.331  5754  5754 D PanService: Received start request. Starting profile...
10-25 20:06:07.332  5754  5754 D BluetoothPanServiceJni: initializeNative(L110): pan
10-25 20:06:07.332  5754  5754 I bt_bluedroid: get_profile_interface pan
10-25 20:06:07.332  5754  5770 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-25 20:06:07.334  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:06:07.335  5754  5754 D BluetoothMapService: Received start request. Starting profile...
10-25 20:06:07.335  5754  5754 D BluetoothMapService: start()
,10-25 20:06:07.337  5754  5754 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-25 20:06:07.338  5754  5754 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-25 20:06:07.338  5754  5754 D BluetoothMapAppObserver: createReceiver()
10-25 20:06:07.339  5754  5754 D BluetoothMapAppObserver: initObservers()
10-25 20:06:07.339  5754  5754 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-25 20:06:07.347  5754  5754 V SapService: SapBinder()
,10-25 20:06:07.347  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
,10-25 20:06:07.348  5754  5754 D SapService: Received start request. Starting profile...
,10-25 20:06:07.348  5754  5754 V SapService: start()
10-25 20:06:07.349  5754  5754 V BluetoothAdapterState: isTurningOff()=false
10-25 20:06:07.350  5754  5754 V BluetoothAdapterState: isTurningOn()=true
10-25 20:06:07.350  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:06:07.350  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:06:07.350  5754  5786 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
,10-25 20:06:07.350  5754  5754 V BluetoothAdapterState: isTurningOff()=false
10-25 20:06:07.350  5754  5754 V BluetoothAdapterState: isTurningOn()=true
10-25 20:06:07.350  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:06:07.350  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:06:07.350  5754  5754 V BluetoothAdapterState: isTurningOff()=false
10-25 20:06:07.350  5754  5754 V BluetoothAdapterState: isTurningOn()=true
10-25 20:06:07.350  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:06:07.350  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:06:07.351  5754  5754 V BluetoothAdapterState: isTurningOff()=false
10-25 20:06:07.351  5754  5754 V BluetoothAdapterState: isTurningOn()=true
10-25 20:06:07.351  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:06:07.351  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:06:07.351  5754  5754 V BluetoothAdapterState: isTurningOff()=false
10-25 20:06:07.351  5754  5754 V BluetoothAdapterState: isTurningOn()=true
10-25 20:06:07.351  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:06:07.351  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:06:07.351  5754  5754 V BluetoothAdapterState: isTurningOff()=false
10-25 20:06:07.351  5754  5754 V BluetoothAdapterState: isTurningOn()=true
,10-25 20:06:07.351  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:06:07.351  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:06:07.352  5754  5754 V BluetoothAdapterState: isTurningOff()=false
10-25 20:06:07.353  5754  5754 V BluetoothAdapterState: isTurningOn()=true
10-25 20:06:07.353  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
10-25 20:06:07.353  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
10-25 20:06:07.353  5754  5766 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-25 20:06:07.353  5754  5766 D BluetoothAdapterProperties: ScanMode =  20
10-25 20:06:07.353  5754  5766 D BluetoothAdapterProperties: State =  11
10-25 20:06:07.353  5754  5766 D BluetoothAdapterProperties: Setting state to 12
10-25 20:06:07.353  5754  5766 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-25 20:06:07.354  5754  5766 I BluetoothAdapterState: Entering OnState
10-25 20:06:07.355  5575  5591 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-25 20:06:07.357  5754  5770 D BluetoothAdapterProperties: Scan Mode:21
,10-25 20:06:07.357  3062  3077 D BluetoothMap: onBluetoothStateChange: up=true
10-25 20:06:07.357  5754  5770 D BluetoothAdapterProperties: Discoverable Timeout:120
10-25 20:06:07.357  5575  5575 D BluetoothInputDevice: Proxy object connected
10-25 20:06:07.357  5515  5515 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-25 20:06:07.358  5575  5575 D HidProfile: Bluetooth service connected
10-25 20:06:07.359  5575  5747 D BluetoothMap: onBluetoothStateChange: up=true
,10-25 20:06:07.360  3062  3062 D BluetoothMap: Proxy object connected
,10-25 20:06:07.361  3062  3062 D MapProfile: Bluetooth service connected
10-25 20:06:07.361  3062  3062 D BluetoothMap: getConnectedDevices()
10-25 20:06:07.361   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 20:06:07.362  3062  3941 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 20:06:07.362  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:06:07.362  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:07.362  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:07.362  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:06:07.362  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:07.362  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:06:07.362  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:06:07.362  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:06:07.362  3062  3082 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-25 20:06:07.364   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-25 20:06:07.364  3062  3077 D BluetoothPan: onBluetoothStateChange on: true
10-25 20:06:07.365  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:06:07.365  5754  5754 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-25 20:06:07.366  5754  5754 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,10-25 20:06:07.366  5575  5592 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 20:06:07.367  5575  5591 D BluetoothA2dp: onBluetoothStateChange: up=true
10-25 20:06:07.367  5754  5754 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 20:06:07.368  3062  3941 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-25 20:06:07.368  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:06:07.368  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:07.368  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:07.368  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:06:07.368  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:07.368  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:06:07.368  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:06:07.368  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:06:07.368  5754  5754 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 20:06:07.370  3062  3062 D BluetoothInputDevice: Proxy object connected
10-25 20:06:07.370  3062  3062 D HidProfile: Bluetooth service connected
10-25 20:06:07.370  3703  3960 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 20:06:07.370  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:06:07.370  5575  5747 D BluetoothPan: onBluetoothStateChange on: true
,10-25 20:06:07.371  5754  5754 D ObexServerSockets: Succeed to create listening sockets 
10-25 20:06:07.371  5754  5754 D ObexServerSockets0: startAccept()
10-25 20:06:07.371  5754  5754 D ObexServerSockets0: prepareForNewConnect()
10-25 20:06:07.371  5575  5575 D BluetoothMap: Proxy object connected
10-25 20:06:07.371  5575  5575 D MapProfile: Bluetooth service connected
10-25 20:06:07.371  5575  5575 D BluetoothMap: getConnectedDevices()
10-25 20:06:07.372  3062  3082 D BluetoothPbap: onBluetoothStateChange: up=true
,10-25 20:06:07.373  5754  5754 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-25 20:06:07.373  5754  5754 D BluetoothSdpJni: SDP Create record success - handle: 0
10-25 20:06:07.373  5754  5796 D ObexServerSockets0: Accepting socket connection...
10-25 20:06:07.374  5754  5797 D ObexServerSockets0: Accepting socket connection...
10-25 20:06:07.374  5575  5592 D BluetoothPbap: onBluetoothStateChange: up=true
10-25 20:06:07.374   925   925 D BluetoothA2dp: Proxy object connected
10-25 20:06:07.375  3062  3062 D BluetoothA2dp: Proxy object connected
,10-25 20:06:07.375   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 20:06:07.376   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 20:06:07.377  5515  5515 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-25 20:06:07.377  5754  5754 D BluetoothMapService: onReceive
10-25 20:06:07.377  5754  5754 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-25 20:06:07.377  5754  5754 D BluetoothMapService: STATE_ON
10-25 20:06:07.378  3062  3062 D BluetoothPan: BluetoothPAN Proxy object connected
10-25 20:06:07.378  3062  3062 D PanProfile: Bluetooth service connected
,10-25 20:06:07.378  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:06:07.378  5575  5575 D BluetoothA2dp: Proxy object connected
10-25 20:06:07.379   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
10-25 20:06:07.380  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:06:07.380  5575  5575 D BluetoothPan: BluetoothPAN Proxy object connected
10-25 20:06:07.380  5575  5575 D PanProfile: Bluetooth service connected
10-25 20:06:07.382  5754  5799 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 20:06:07.384  5754  5799 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-25 20:06:07.384  5754  5799 D BluetoothSdpJni: SDP Create record success - handle: 1
10-25 20:06:07.386  5575  5575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-25 20:06:07.391  5575  5575 D DockEventReceiver: finishStartingService: stopping service
10-25 20:06:07.393  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 20:06:07.399  5754  5754 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-25 20:06:07.399  5575  5575 D BluetoothPbap: Proxy object connected
10-25 20:06:07.399  5754  5754 D ObexServerSockets0: prepareForNewConnect()
10-25 20:06:07.399  5575  5575 D PbapServerProfile: Bluetooth service connected
,10-25 20:06:07.404  3062  3062 D BluetoothPbap: Proxy object connected
,10-25 20:06:07.405  3062  3062 D PbapServerProfile: Bluetooth service connected
,10-25 20:06:07.408  5754  5803 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 20:06:07.420  5754  5807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 20:06:07.421  5754  5807 I BtOppRfcommListener: Accept thread started.
,10-25 20:06:07.463   925   925 D BluetoothHeadset: Proxy object connected
,10-25 20:06:07.463  5575  5592 D BluetoothHeadset: Proxy object connected
10-25 20:06:07.464   925   925 D BluetoothHeadset: Proxy object connected
10-25 20:06:07.464  3062  3077 D BluetoothHeadset: Proxy object connected
10-25 20:06:07.464  3062  3062 D HeadsetProfile: Bluetooth service connected
,10-25 20:06:07.464  3703  3754 D BluetoothHeadset: Proxy object connected
,10-25 20:06:07.465   925   925 D BluetoothHeadset: Proxy object connected
10-25 20:06:07.465  5575  5575 D HeadsetProfile: Bluetooth service connected
,10-25 20:06:07.466  5575  5591 D BluetoothHeadset: Proxy object connected
,10-25 20:06:07.467  5575  5575 D HeadsetProfile: Bluetooth service connected
,10-25 20:06:07.471  3703  3961 D BluetoothHeadset: Proxy object connected
,10-25 20:06:07.476   925   942 D BluetoothHeadset: Proxy object connected
10-25 20:06:07.476   925   942 D BluetoothHeadset: Proxy object connected
,10-25 20:06:09.974  3658  4343 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,10-25 20:06:11.199  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:06:11.199  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:11.199  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:11.199  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 20:06:11.199  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:11.199  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:06:11.199  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:06:11.199  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 20:06:11.206  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:06:11.207  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:06:11.207  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@411cc6f removed from the list
,10-25 20:06:11.207  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:06:11.207  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 20:06:11.208  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:06:11.213  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-25 20:06:11.214  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61b605 added. We now have 4 listener(s)
10-25 20:06:11.214  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 20:06:11.217   925  3763 D WifiService: setWifiEnabled: false pid=5515, uid=10077
,10-25 20:06:11.217   925  3763 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 20:06:16.227  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:06:16.228   925  3757 D WifiService: setWifiEnabled: true pid=5515, uid=10077
10-25 20:06:16.228   925  3757 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 20:06:16.237   508   919 D SoftapController: Softap fwReload - Ok
,10-25 20:06:16.242   508   919 D CommandListener: Setting iface cfg
,10-25 20:06:16.243   508   919 D CommandListener: Trying to bring down wlan0
10-25 20:06:16.245   508   919 D CommandListener: Clearing all IP addresses on wlan0
,10-25 20:06:16.251   925  2918 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-25 20:06:16.914   925  2918 D wifi    : set interface wlan0 flags (UP)
,10-25 20:06:16.916   925  2918 I WifiHAL : Initializing wifi
10-25 20:06:16.916   925  2918 I WifiHAL : Creating socket
,10-25 20:06:16.921   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-25 20:06:16.922   925  2918 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-25 20:06:16.922   925  2918 D wifi    : Did set static halHandle = 0x7f70a5b680
10-25 20:06:16.922   925  2918 D wifi    : halHandle = 0x7f70a5b680, mVM = 0x7f8d00d140, mCls = 0x20162a
10-25 20:06:16.922   925  2918 D wifi    : array field set
10-25 20:06:16.923   925  2918 I WifiNative-HAL: interface[0] = wlan0
,10-25 20:06:16.925   925  5813 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547350754944
10-25 20:06:16.925   925  5813 D wifi    : waitForHalEvents called, vm = 0x7f8d00d140, obj = 0x20162a, env = 0x7f6eae2ec0
,10-25 20:06:16.928   925  2918 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-25 20:06:16.931   925  2918 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,10-25 20:06:16.936  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:06:16.940  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:06:16.983  5814  5814 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-25 20:06:17.058  5814  5814 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-25 20:06:17.113  5814  5814 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-25 20:06:17.113  5814  5814 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-25 20:06:17.591   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:17.945   925  2918 D WifiConfigStore: Loading config and enabling all networks 
,10-25 20:06:17.951  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:06:17.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:17.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:17.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:06:17.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:17.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:06:17.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:06:17.951  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 20:06:17.955  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:06:17.959  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:06:17.959  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:17.959  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:17.959  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:06:17.959  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:17.959  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:06:17.959  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:06:17.959  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 20:06:17.962  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:06:17.985   925  2918 D WifiConfigStore: loaded 0 passpoint configs
10-25 20:06:17.985   925  2918 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
10-25 20:06:17.986   925  2918 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-25 20:06:17.987   925  2918 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-25 20:06:17.988   925  2918 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,10-25 20:06:17.988   925  2918 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,10-25 20:06:17.989   925  2918 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-25 20:06:17.990   925  2918 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-25 20:06:17.990   925  2918 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,10-25 20:06:17.990   925  2918 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
10-25 20:06:17.990   925  2918 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-25 20:06:17.990   925  2918 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
10-25 20:06:17.990   925  2918 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,10-25 20:06:17.994   925  2918 D WifiNative-HAL: Setting external_sim to 1
10-25 20:06:17.994  4384  4384 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 20:06:17.994   925  2918 D wifi    : setting dfs flag to true, 0x7f72f3fa00
10-25 20:06:17.995   925  2918 D WifiStateMachine: Setting OUI to DA-A1-19
,10-25 20:06:17.995   925  2918 D wifi    : setting scan oui 0x7f72f3fa00
10-25 20:06:17.995   925  2918 D WifiHAL : Sending mac address OUI
,10-25 20:06:18.000   925  2918 E native  : do suspend true
,10-25 20:06:18.008   925  2918 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-25 20:06:18.009   508   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-25 20:06:18.009   925   925 D RttService: SCAN_AVAILABLE : 3
10-25 20:06:18.009   925  3029 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-25 20:06:18.010   508   919 D CommandListener: Setting iface cfg
,10-25 20:06:18.020   925  2892 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '153 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 153 Failed to set address (No such device)'
10-25 20:06:18.020   925  2892 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-25 20:06:18.027   925  2892 D WifiNative-HAL: p2pGetDeviceAddress
10-25 20:06:18.028   925  2892 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-25 20:06:18.034   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164484 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=8 mControllerEnergyUsed=30 }
,10-25 20:06:18.593   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:19.594   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:20.595   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:21.159  5814  5814 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-25 20:06:21.187   925  2918 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-25 20:06:21.189   925  2918 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
10-25 20:06:21.190   925  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 20:06:21.204   925  2918 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-25 20:06:21.240  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:06:21.240  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:21.240  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:21.240  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:06:21.240  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:21.240  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:06:21.240  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:06:21.240  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 20:06:21.242  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:06:21.243  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:06:21.243  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61b605 removed from the list
10-25 20:06:21.243  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:06:21.243  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 20:06:21.243  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:06:21.249  5515  5562 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-25 20:06:21.250  5515  5562 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-25 20:06:21.253  5515  5562 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@380656d Bundle[{}]
,10-25 20:06:21.254  5515  5562 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-25 20:06:21.254  5515  5562 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-25 20:06:21.255  5515  5562 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-25 20:06:21.256  5515  5562 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,10-25 20:06:21.257  5515  5562 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-25 20:06:21.257  5515  5562 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-25 20:06:21.259   925  2918 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-25 20:06:21.266  5515  5562 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 164)
,10-25 20:06:21.266  5515  5562 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-25 20:06:21.266  5515  5562 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
,10-25 20:06:21.269  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-25 20:06:21.269  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bee365a added. We now have 3 listener(s)
10-25 20:06:21.270  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 20:06:21.271  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 20:06:21.271  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 20:06:21.271  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-25 20:06:21.271  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98c08b added. We now have 4 listener(s)
10-25 20:06:21.271  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 20:06:21.272  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-25 20:06:21.275  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 20:06:21.279  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:06:21.279  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:21.279  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:21.279  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:06:21.279  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:21.279  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:06:21.279  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:06:21.279  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 20:06:21.281  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:06:21.281  5515  5562 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 20:06:21.282  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-25 20:06:21.282  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cad81 added. We now have 4 listener(s)
,10-25 20:06:21.283  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:06:21.283  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 20:06:21.283  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 20:06:21.283  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 20:06:21.284  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 20:06:21.284  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@495e26 added. We now have 5 listener(s)
10-25 20:06:21.284  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 20:06:21.284  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:06:21.284  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:06:21.284  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:06:21.284  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:06:21.284  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.284  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-25 20:06:21.284  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:06:21.284  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 20:06:21.284  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bee365a removed from the list
10-25 20:06:21.284  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.284  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98c08b removed from the list
10-25 20:06:21.284  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:06:21.285  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:06:21.285  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.286  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.286  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:06:21.286  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.288  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.288  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.288  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.288  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:06:21.289  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:06:21.289  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.289  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98c08b not in the list
,10-25 20:06:21.289  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.289  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.289  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.290  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.291  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.291  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.291  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:06:21.291  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-25 20:06:21.291  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:06:21.291  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@495e26 removed from the list
10-25 20:06:21.291  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:06:21.291  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.291  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.291  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:06:21.291  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 20:06:21.291  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cad81 removed from the list
10-25 20:06:21.292  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-25 20:06:21.292  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@150da67 added. We now have 3 listener(s)
,10-25 20:06:21.293  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 20:06:21.293  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 20:06:21.293  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 20:06:21.293  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 20:06:21.293  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a29014 added. We now have 4 listener(s)
10-25 20:06:21.293  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 20:06:21.294  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-25 20:06:21.297  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 20:06:21.299  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:06:21.299  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:21.299  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:21.299  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:06:21.299  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:21.299  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:06:21.299  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:06:21.299  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 20:06:21.301  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:06:21.301  5515  5562 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 20:06:21.301  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-25 20:06:21.301  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9dd36b2 added. We now have 4 listener(s)
10-25 20:06:21.302  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:06:21.302  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 20:06:21.302  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 20:06:21.302  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 20:06:21.303  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 20:06:21.303  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@986b603 added. We now have 5 listener(s)
10-25 20:06:21.303  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 20:06:21.303  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 20:06:21.303  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-25 20:06:21.303  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-25 20:06:21.303  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 20:06:21.303  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 20:06:21.303  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:06:21.306  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-25 20:06:21.306  5515  5562 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-25 20:06:21.307  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-25 20:06:21.309  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-25 20:06:21.310  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-25 20:06:21.310  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-25 20:06:21.313  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.313  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-25 20:06:21.313  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-25 20:06:21.313  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-25 20:06:21.313  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-25 20:06:21.313  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.314  5515  5562 D BluetoothAdapter: STATE_ON
,10-25 20:06:21.317  5754  5795 D BtGatt.GattService: registerClient() - UUID=0a5db414-0d3d-4603-975f-f1ce732ae4e6
,10-25 20:06:21.318  5754  5770 D BtGatt.GattService: onClientRegistered() - UUID=0a5db414-0d3d-4603-975f-f1ce732ae4e6, clientIf=5
,10-25 20:06:21.319  5515  5526 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-25 20:06:21.320  5754  5787 D BtGatt.GattService: start scan with filters
,10-25 20:06:21.323  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-25 20:06:21.323  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.324  5754  5773 D BtGatt.ScanManager: handling starting scan
,10-25 20:06:21.324  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-25 20:06:21.324  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.324  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.324  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-25 20:06:21.324  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-25 20:06:21.324  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.324  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.324  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-25 20:06:21.324  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.326  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.326  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 20:06:21.326  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.326  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 20:06:21.326  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.327  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.327  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-25 20:06:21.327  5754  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9fae16
10-25 20:06:21.328  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 20:06:21.328  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.330  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.330  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.330  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.330  5515  5562 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-25 20:06:21.330  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-25 20:06:21.330  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-25 20:06:21.330  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.330  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 20:06:21.331  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:06:21.331  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-25 20:06:21.331  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 20:06:21.331  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 20:06:21.331  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-25 20:06:21.331  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.331  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.331  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-25 20:06:21.333  5515  5562 D BluetoothAdapter: STATE_ON
,10-25 20:06:21.333  5754  5795 D BtGatt.GattService: stopScan() - queue size =1
10-25 20:06:21.334  5754  5770 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-25 20:06:21.334  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.334  5754  5787 D BtGatt.GattService: unregisterClient() - clientIf=5
10-25 20:06:21.334  5754  5773 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-25 20:06:21.335  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 20:06:21.335  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.335  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-25 20:06:21.335  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.335  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.335  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 20:06:21.335  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-25 20:06:21.335  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.335  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.335  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-25 20:06:21.335  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.336  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.336  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 20:06:21.337  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.337  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.337  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.337  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.337  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.337  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-25 20:06:21.337  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.337  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.337  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.337  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 20:06:21.337  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 20:06:21.338  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 20:06:21.338  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.339  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.339  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.339  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.339  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:06:21.339  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:06:21.339  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 20:06:21.340  5754  5770 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-25 20:06:21.340  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 20:06:21.341  5754  5773 D BtGatt.ScanManager: Starting BLE batch scan
10-25 20:06:21.341  5754  5773 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-25 20:06:21.342  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:06:21.342  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:06:21.342  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:06:21.342  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:06:21.342  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.342  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 20:06:21.342  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:06:21.342  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 20:06:21.342  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@150da67 removed from the list
,10-25 20:06:21.342  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.342  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a29014 removed from the list
10-25 20:06:21.342  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:06:21.343  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:06:21.343  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.343  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.343  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.345  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.345  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.345  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.345  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:06:21.345  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:06:21.345  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.345  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a29014 not in the list
,10-25 20:06:21.345  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.345  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.345  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.349  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.349  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.349  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.349  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:06:21.349  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:06:21.349  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.349  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@986b603 removed from the list
10-25 20:06:21.349  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:06:21.349  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.349  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.349  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:06:21.350  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 20:06:21.350  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9dd36b2 removed from the list
,10-25 20:06:21.351  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-25 20:06:21.351  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab4af5f added. We now have 3 listener(s)
10-25 20:06:21.351  5754  5770 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-25 20:06:21.351  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.352  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 20:06:21.352  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 20:06:21.352  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 20:06:21.352  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 20:06:21.353  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed7cdac added. We now have 4 listener(s)
10-25 20:06:21.353  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 20:06:21.353  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-25 20:06:21.356  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 20:06:21.357  5754  5770 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-25 20:06:21.357  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 20:06:21.360  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:06:21.360  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:21.360  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:21.360  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:06:21.360  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:21.360  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:06:21.360  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:06:21.360  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 20:06:21.362  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 20:06:21.362  5515  5562 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 20:06:21.362  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-25 20:06:21.363  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af0ea0a added. We now have 4 listener(s)
10-25 20:06:21.363  5754  5770 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-25 20:06:21.363  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.363  5754  5773 D BtGatt.ScanManager: stopping BLe Batch
,10-25 20:06:21.365  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 20:06:21.365  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 20:06:21.365  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 20:06:21.365  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:06:21.365  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-25 20:06:21.365  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9ee27b added. We now have 5 listener(s)
10-25 20:06:21.365  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 20:06:21.366  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-25 20:06:21.366  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 20:06:21.366  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-25 20:06:21.366  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-25 20:06:21.366  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 20:06:21.367  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-25 20:06:21.369  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:06:21.370  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-25 20:06:21.370  5515  5562 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-25 20:06:21.370  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-25 20:06:21.370  5754  5770 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-25 20:06:21.370  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.371  5754  5773 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-25 20:06:21.373  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-25 20:06:21.374  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-25 20:06:21.374  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 20:06:21.375  5754  5770 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-25 20:06:21.375  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 20:06:21.377  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.377  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-25 20:06:21.377  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-25 20:06:21.377  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-25 20:06:21.377  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-25 20:06:21.377  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.378  5515  5562 D BluetoothAdapter: STATE_ON
10-25 20:06:21.379  5754  5764 D BtGatt.GattService: registerClient() - UUID=e1fa8f83-983c-439d-984b-c931deabcc67
10-25 20:06:21.379  5754  5770 D BtGatt.GattService: onClientRegistered() - UUID=e1fa8f83-983c-439d-984b-c931deabcc67, clientIf=5
,10-25 20:06:21.380  5515  5525 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-25 20:06:21.380  5754  5794 D BtGatt.GattService: start scan with filters
10-25 20:06:21.382  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-25 20:06:21.382  5754  5773 D BtGatt.ScanManager: handling starting scan
10-25 20:06:21.382  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.382  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-25 20:06:21.382  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.382  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.382  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-25 20:06:21.382  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-25 20:06:21.382  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.383  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.383  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-25 20:06:21.383  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.385  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.385  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 20:06:21.385  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.385  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 20:06:21.385  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.385  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.385  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-25 20:06:21.386  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 20:06:21.387  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.387  5754  5770 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-25 20:06:21.388  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.388  5754  5773 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-25 20:06:21.388  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.388  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.388  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.388  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 20:06:21.389  5515  5562 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-25 20:06:21.389  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:06:21.389  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:06:21.389  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:06:21.389  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:06:21.389  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.389  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 20:06:21.389  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:06:21.389  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-25 20:06:21.389  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab4af5f removed from the list
10-25 20:06:21.389  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.389  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed7cdac removed from the list
10-25 20:06:21.389  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:06:21.389  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-25 20:06:21.391  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.391  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-25 20:06:21.391  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.391  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 20:06:21.391  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.392  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.392  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.392  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.392  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:06:21.392  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:06:21.392  5754  5770 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-25 20:06:21.392  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.392  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.392  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed7cdac not in the list
10-25 20:06:21.392  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-25 20:06:21.392  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 20:06:21.392  5754  5773 D BtGatt.ScanManager: Starting BLE batch scan
10-25 20:06:21.392  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 20:06:21.392  5754  5773 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-25 20:06:21.392  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.392  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.392  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-25 20:06:21.396  5515  5562 D BluetoothAdapter: STATE_ON
,10-25 20:06:21.397  5754  5764 D BtGatt.GattService: stopScan() - queue size =1
,10-25 20:06:21.398  5754  5794 D BtGatt.GattService: unregisterClient() - clientIf=5
10-25 20:06:21.398  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 20:06:21.398  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.398  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-25 20:06:21.398  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.398  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.398  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 20:06:21.398  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-25 20:06:21.398  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.398  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.398  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-25 20:06:21.399  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.400  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.400  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 20:06:21.400  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.400  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.400  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.400  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.400  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.400  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-25 20:06:21.400  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.400  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.400  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.401  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 20:06:21.401  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 20:06:21.401  5754  5770 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-25 20:06:21.401  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.401  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.402  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.403  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.403  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.403  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.403  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:06:21.403  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:06:21.403  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.403  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:06:21.403  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9ee27b removed from the list
10-25 20:06:21.403  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:06:21.404  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:06:21.404  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 20:06:21.404  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.404  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.404  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:06:21.404  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 20:06:21.404  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af0ea0a removed from the list
10-25 20:06:21.405  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-25 20:06:21.405  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92f2b57 added. We now have 3 listener(s)
10-25 20:06:21.406  5754  5770 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-25 20:06:21.406  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 20:06:21.406  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 20:06:21.406  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 20:06:21.406  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 20:06:21.407  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 20:06:21.407  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4942644 added. We now have 4 listener(s)
10-25 20:06:21.407  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 20:06:21.407  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-25 20:06:21.410  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 20:06:21.412  5754  5770 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-25 20:06:21.412  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.412  5754  5773 D BtGatt.ScanManager: stopping BLe Batch
,10-25 20:06:21.413  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:06:21.413  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:21.413  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:21.413  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:06:21.413  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:21.413  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:06:21.413  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:06:21.413  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 20:06:21.415  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:06:21.415  5515  5562 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 20:06:21.416  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-25 20:06:21.416  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acb062 added. We now have 4 listener(s)
,10-25 20:06:21.416  5754  5770 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-25 20:06:21.416  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.416  5754  5773 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-25 20:06:21.417  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 20:06:21.417  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 20:06:21.417  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 20:06:21.417  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 20:06:21.417  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 20:06:21.417  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1125f3 added. We now have 5 listener(s)
10-25 20:06:21.417  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 20:06:21.417  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 20:06:21.417  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-25 20:06:21.417  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-25 20:06:21.417  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 20:06:21.417  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 20:06:21.418  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:06:21.420  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-25 20:06:21.420  5515  5562 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-25 20:06:21.420  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-25 20:06:21.421  5754  5770 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-25 20:06:21.422  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.422  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-25 20:06:21.423  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-25 20:06:21.423  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-25 20:06:21.425  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.426  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-25 20:06:21.426  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-25 20:06:21.426  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-25 20:06:21.426  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-25 20:06:21.426  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.426  5515  5562 D BluetoothAdapter: STATE_ON
,10-25 20:06:21.428  5754  5765 D BtGatt.GattService: registerClient() - UUID=e8912cee-5cb8-467e-981d-379c792d387c
,10-25 20:06:21.428  5754  5770 D BtGatt.GattService: onClientRegistered() - UUID=e8912cee-5cb8-467e-981d-379c792d387c, clientIf=5
10-25 20:06:21.429  5515  5526 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-25 20:06:21.429  5754  5794 D BtGatt.GattService: start scan with filters
,10-25 20:06:21.431  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-25 20:06:21.431  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.431  5754  5773 D BtGatt.ScanManager: handling starting scan
10-25 20:06:21.431  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-25 20:06:21.431  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.431  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.431  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-25 20:06:21.431  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-25 20:06:21.432  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.432  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.432  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-25 20:06:21.432  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.434  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.434  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 20:06:21.434  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.434  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 20:06:21.434  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.434  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.434  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-25 20:06:21.435  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 20:06:21.435  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.436  5754  5770 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-25 20:06:21.436  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.436  5754  5773 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-25 20:06:21.437  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.437  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.437  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.439  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:06:21.439  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:06:21.439  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:06:21.439  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:06:21.439  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.439  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-25 20:06:21.439  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:06:21.439  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 20:06:21.439  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92f2b57 removed from the list
10-25 20:06:21.439  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.440  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4942644 removed from the list
10-25 20:06:21.440  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:06:21.440  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-25 20:06:21.440  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.441  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-25 20:06:21.441  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.441  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 20:06:21.441  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.441  5754  5770 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-25 20:06:21.441  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.441  5754  5773 D BtGatt.ScanManager: Starting BLE batch scan
10-25 20:06:21.441  5754  5773 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-25 20:06:21.442  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.442  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.442  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.442  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:06:21.442  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:06:21.442  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.443  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4942644 not in the list
10-25 20:06:21.443  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 20:06:21.443  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 20:06:21.443  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-25 20:06:21.443  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.443  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.443  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-25 20:06:21.444  5515  5562 D BluetoothAdapter: STATE_ON
10-25 20:06:21.444  5754  5795 D BtGatt.GattService: stopScan() - queue size =1
10-25 20:06:21.444  5754  5787 D BtGatt.GattService: unregisterClient() - clientIf=5
10-25 20:06:21.445  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 20:06:21.445  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.445  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-25 20:06:21.445  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.445  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.445  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 20:06:21.445  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-25 20:06:21.445  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.445  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.445  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-25 20:06:21.445  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.446  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.446  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 20:06:21.446  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.446  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.446  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.446  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.446  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.447  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-25 20:06:21.447  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.447  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.447  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.447  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 20:06:21.447  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 20:06:21.448  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.448  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-25 20:06:21.449  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.449  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.449  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.449  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:06:21.449  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:06:21.449  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.450  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:06:21.450  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1125f3 removed from the list
10-25 20:06:21.450  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:06:21.450  5754  5770 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-25 20:06:21.450  5515  5515 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 20:06:21.450  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.450  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.450  5515  5515 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 20:06:21.450  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.450  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:06:21.450  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 20:06:21.450  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2acb062 removed from the list
10-25 20:06:21.451  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-25 20:06:21.451  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e2e4f added. We now have 3 listener(s)
,10-25 20:06:21.452  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-25 20:06:21.453  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 20:06:21.453  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 20:06:21.453  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-25 20:06:21.453  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63ff9dc added. We now have 4 listener(s)
10-25 20:06:21.453  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 20:06:21.454  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-25 20:06:21.456  5754  5770 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-25 20:06:21.456  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.456  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 20:06:21.459  5515  5562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 20:06:21.459  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:21.459  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:21.459  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:06:21.459  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:21.459  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 20:06:21.459  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 20:06:21.459  5515  5562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 20:06:21.461  5515  5562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 20:06:21.462  5515  5562 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 20:06:21.462  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-25 20:06:21.462  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59fe9ba added. We now have 4 listener(s)
10-25 20:06:21.462  5754  5770 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-25 20:06:21.462  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 20:06:21.462  5754  5773 D BtGatt.ScanManager: stopping BLe Batch
,10-25 20:06:21.463  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:06:21.463  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-25 20:06:21.463  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 20:06:21.463  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 20:06:21.463  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 20:06:21.463  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e29606b added. We now have 5 listener(s)
10-25 20:06:21.463  5515  5562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 20:06:21.463  5515  5562 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 20:06:21.464  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-25 20:06:21.464  5515  5562 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 20:06:21.464  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:06:21.464  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.464  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 20:06:21.464  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:06:21.464  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 20:06:21.464  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60e2e4f removed from the list
10-25 20:06:21.464  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.464  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63ff9dc removed from the list
10-25 20:06:21.465  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 20:06:21.465  5515  5562 D io.jxcore.node.ConnectivityMonitor: stop
10-25 20:06:21.465  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-25 20:06:21.465  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 20:06:21.465  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.466  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.467  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.467  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.467  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.467  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:06:21.467  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:06:21.467  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-25 20:06:21.467  5515  5562 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63ff9dc not in the list
10-25 20:06:21.467  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.467  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.467  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.468  5754  5770 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-25 20:06:21.468  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.468  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 20:06:21.468  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.468  5515  5562 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-25 20:06:21.468  5754  5773 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-25 20:06:21.468  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-25 20:06:21.468  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-25 20:06:21.468  5515  5562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 20:06:21.468  5515  5562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e29606b removed from the list
,10-25 20:06:21.468  5515  5562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 20:06:21.468  5515  5562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 20:06:21.468  5515  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 20:06:21.468  5515  5562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 20:06:21.468  5515  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 20:06:21.469  5515  5562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59fe9ba removed from the list
,10-25 20:06:21.469  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-25 20:06:21.469  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-25 20:06:21.469  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-25 20:06:21.469  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 20:06:21.469  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-25 20:06:21.469  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-25 20:06:21.473  5754  5770 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-25 20:06:21.473  5754  5770 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 20:06:21.596   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:21.607  5814  5814 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-25 20:06:21.638  5814  5814 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
10-25 20:06:21.639  5814  5814 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-25 20:06:21.652   925  2918 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-25 20:06:21.652   925  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-25 20:06:21.652   925  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-25 20:06:21.664   925  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 20:06:21.673   508   919 D CommandListener: Setting iface cfg
,10-25 20:06:21.676   925  2918 D WifiStateMachine: Start Dhcp Watchdog 3
,10-25 20:06:21.679   925  2918 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-25 20:06:21.681   925  5819 D DhcpClient: Receive thread started
,10-25 20:06:21.763   925  2918 E native  : do suspend false
,10-25 20:06:21.772   925  5818 D DhcpClient: Broadcasting DHCPDISCOVER
,10-25 20:06:21.787   925  5819 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.111, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,10-25 20:06:21.788   925  5818 D DhcpClient: Got pending lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,10-25 20:06:21.790   925  5818 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.111 serverid=192.168.1.1
,10-25 20:06:21.803   925  5819 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.111, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-25 20:06:21.804   925  5818 D DhcpClient: Confirmed lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-25 20:06:21.806   508   919 D CommandListener: Setting iface cfg
,10-25 20:06:21.811   925  2918 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-25 20:06:21.812   925  2918 E native  : do suspend true
,10-25 20:06:21.812   925  5818 D DhcpClient: Scheduling renewal in 86399s
,10-25 20:06:21.823   925  2918 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-25 20:06:21.824   925  2918 D WifiConfigStore: No blacklist allowed without epno enabled
,10-25 20:06:21.824   925  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-25 20:06:21.827   925  2921 D ConnectivityService: Adding iface wlan0 to network 102
,10-25 20:06:21.829   925  2918 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-25 20:06:21.839  5515  5515 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-25 20:06:21.866   925  2921 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-25 20:06:21.867   925  2921 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-25 20:06:21.868   925  2921 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-25 20:06:21.869   925  2921 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-25 20:06:21.872   925  2921 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-25 20:06:21.878   925  2921 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-25 20:06:21.882   925  2921 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-25 20:06:21.882   925  2921 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,10-25 20:06:21.882   925  2921 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-25 20:06:21.882   925  2921 D ConnectivityService:    accepting network in place of null
10-25 20:06:21.882   925  2918 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-25 20:06:21.883   925  2918 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-25 20:06:21.884   925  2921 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-25 20:06:21.894   925  5817 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-25 20:06:21.905  5515  5515 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
10-25 20:06:21.905   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 20:06:21.925   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 20:06:21.928   925  2921 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-25 20:06:21.928   925  2921 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-25 20:06:21.928  3679  3820 W QCNEJ   : |CORE| network available: 102
10-25 20:06:21.929   925  2921 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-25 20:06:21.931   925   942 D Tethering: MasterInitialState.processMessage what=3
10-25 20:06:21.932  3679  3820 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-25 20:06:21.935  3679  3820 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-25 20:06:21.935  3679  3820 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-25 20:06:21.936  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:06:21.936  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:21.936  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:21.936  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:06:21.936  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:21.936  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:06:21.936  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:06:21.936  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 20:06:21.938  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 20:06:21.942  3910  3910 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-25 20:06:21.942  5515  5515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 20:06:21.942  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 20:06:21.942  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 20:06:21.942  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 20:06:21.942  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 20:06:21.942  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 20:06:21.942  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 20:06:21.942  5515  5515 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 20:06:21.945  5515  5515 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 20:06:21.940  4926  4959 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-25 20:06:21.945  4926  4959 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-25 20:06:21.945  4926  4959 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-25 20:06:21.945  4926  4959 E SarControlService: no key has been found,reset the power
10-25 20:06:21.946  4926  4993 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-25 20:06:21.946  4926  4993 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,10-25 20:06:21.946  4926  4993 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-25 20:06:21.946  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 20:06:21.946  4979  4979 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-25 20:06:21.948  4926  4993 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-25 20:06:21.948  4926  4993 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-25 20:06:21.948  4926  4993 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-25 20:06:21.949  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 20:06:21.949  4979  4979 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-25 20:06:21.950  5515  5515 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-25 20:06:21.951  3924  3924 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-25 20:06:21.954  3924  3924 D SystemUpdateService: onCreate
10-25 20:06:21.956  4979  5001 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c1e91f9 HexData = [00000000f003000000000000ffffffff]
10-25 20:06:21.956  4979  5001 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 20:06:21.956  4979  5001 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-25 20:06:21.956  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 20:06:21.957  4926  4936 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-25 20:06:21.959  3924  3924 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-25 20:06:21.961  4979  5001 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c1e91f9 HexData = [00000000f103000000000000ffffffff]
10-25 20:06:21.961  4979  5001 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 20:06:21.961  4979  5001 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-25 20:06:21.962  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 20:06:21.962  4926  4938 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-25 20:06:21.964   925  5816 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.211.46,2a00:1450:4016:805::200e
,10-25 20:06:21.974  3924  3924 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-25 20:06:21.979  3924  5309 I iu.UploadsManager: num queued entries: 0
10-25 20:06:21.979  3924  5309 I iu.UploadsManager: num updated entries: 0
10-25 20:06:21.979  3924  5309 I iu.SyncManager: NEXT; no task
,10-25 20:06:21.982  3924  5829 I SystemUpdateService: active receiver: enabled
,10-25 20:06:21.984  3924  3924 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-25 20:06:21.986  3924  3924 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-25 20:06:21.988  5620  5620 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-25 20:06:21.991  5620  5620 D SprintDMHelper: simOperator: 
10-25 20:06:21.991  5620  5620 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-25 20:06:22.015  3924  5829 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-25 20:06:22.027  3924  5829 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-25 20:06:22.027  3924  5829 I SystemUpdateService: now status is 0 (complete)
10-25 20:06:22.027  3924  5829 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-25 20:06:22.027  3924  5829 I SystemUpdateService: file has been verified
10-25 20:06:22.027  3924  5829 I SystemUpdateService: OTA package size = 21989297
,10-25 20:06:22.032  3924  5829 I SystemUpdateService: showing system update notification
,10-25 20:06:22.037   925  5816 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 25 Oct 2016 18:06:22 GMT], X-Android-Received-Millis=[1477418782036], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477418782002]}
,10-25 20:06:22.037   925  2921 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-25 20:06:22.037   925  2921 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,10-25 20:06:22.037   925  2921 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-25 20:06:22.039   925  2921 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-25 20:06:22.043   925   925 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-25 20:06:22.044  3924  3924 D SystemUpdateService: onDestroy
,10-25 20:06:22.119  4384  5833 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-25 20:06:22.596   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-25 20:06:23.600  5515  5841 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-25 20:06:23.600  5515  5841 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 20:06:24.391  5515  5841 W !!      : call onHalfStreamCopied
,10-25 20:06:24.391  5515  5841 I testCopyDataAndClose: closing input stream
,10-25 20:06:25.166  5515  5841 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 173, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-25 20:06:25.166  5515  5841 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 20:06:25.166  5515  5841 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-25 20:06:25.166  5515  5841 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 20:06:25.166  5515  5841 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-25 20:06:25.166  5515  5841 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-25 20:06:25.166  5515  5841 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-25 20:06:25.166  5515  5841 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-25 20:06:25.166  5515  5841 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-25 20:06:25.166  5515  5841 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-25 20:06:25.166  5515  5841 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-25 20:06:25.390  3521  5843 I VacuumService: Vacuum at: now=1477418785390 tag=VacuumService
,10-25 20:06:25.415  3521  5846 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,10-25 20:06:25.450  3521  5844 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,10-25 20:06:25.453  3521  5844 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-25 20:06:25.471  3521  5844 W Uploader:  no longer exists, so no auth token.
,10-25 20:06:25.477  3521  5846 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-25 20:06:25.885  3521  5844 W Uploader:  no longer exists, so no auth token.
,10-25 20:06:25.890  3521  5848 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-25 20:06:26.007  3521  5846 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-25 20:06:26.096  3521  5848 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-25 20:06:26.187  3521  5846 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-25 20:06:29.502  5515  5857 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
10-25 20:06:29.502  5515  5857 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 20:06:29.890   925  2921 D ConnectivityService: handlePromptUnvalidated 102
,10-25 20:06:31.503  5515  5562 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 176. Connection data: Peer properties: [null null].
10-25 20:06:31.503  5515  5562 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 20:06:31.503  5515  5562 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 176, name: My test thread name)
,10-25 20:06:31.571  5515  5857 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-25 20:06:31.571  5515  5857 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
10-25 20:06:31.571  5515  5857 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,10-25 20:06:31.632  5515  5858 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-25 20:06:31.632  5515  5858 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 20:06:33.240  5515  5858 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-25 20:06:33.240  5515  5858 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 20:06:33.240  5515  5858 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-25 20:06:33.240  5515  5858 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 20:06:33.240  5515  5858 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-25 20:06:33.240  5515  5858 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-25 20:06:33.240  5515  5858 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-25 20:06:33.240  5515  5858 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-25 20:06:33.241  5515  5858 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-25 20:06:33.241  5515  5858 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-25 20:06:33.241  5515  5858 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-25 20:06:37.386  5515  5859 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-25 20:06:37.386  5515  5859 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 20:06:37.387  5515  5859 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 180, thread name: My test thread name). Connection data: Peer properties: [null null].
10-25 20:06:37.387  5515  5859 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 20:06:37.387  5515  5859 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-25 20:06:37.387  5515  5859 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 20:06:37.387  5515  5859 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-25 20:06:37.387  5515  5859 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-25 20:06:37.387  5515  5859 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-25 20:06:37.387  5515  5859 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-25 20:06:37.388  5515  5859 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-25 20:06:37.388  5515  5859 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-25 20:06:37.388  5515  5859 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,10-25 20:06:37.398  5515  5562 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-25 20:06:37.404  5515  5860 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-25 20:06:37.404  5515  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 20:06:37.404  5515  5860 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 184, thread name: My test thread name): Test exception.
,10-25 20:06:37.404  5515  5860 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-25 20:06:37.404  5515  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-25 20:06:37.404  5515  5860 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,10-25 20:06:37.405  5515  5860 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-25 20:06:37.405  5515  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-25 20:06:37.408  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-25 20:06:37.408  5515  5562 I jxcore-log: 
,10-25 20:06:37.409  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-25 20:06:37.409  5515  5562 I jxcore-log: 
10-25 20:06:37.409  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-25 20:06:37.409  5515  5562 I jxcore-log: 
10-25 20:06:37.409  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-25 20:06:37.409  5515  5562 I jxcore-log: 
10-25 20:06:37.410  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG UnitTest_app: 'Total duration:  91745'
10-25 20:06:37.410  5515  5562 I jxcore-log: 
10-25 20:06:37.412  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-25 20:06:37.412  5515  5562 I jxcore-log: 
,10-25 20:06:37.427  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.427  5515  5562 I jxcore-log: 
,10-25 20:06:37.428  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.428  5515  5562 I jxcore-log: 
10-25 20:06:37.430  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.430  5515  5562 I jxcore-log: 
,10-25 20:06:37.430  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.430  5515  5562 I jxcore-log: 
10-25 20:06:37.431  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-25 20:06:37.431  5515  5562 I jxcore-log: 
10-25 20:06:37.432  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-25 20:06:37.432  5515  5562 I jxcore-log: 
10-25 20:06:37.432  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.432  5515  5562 I jxcore-log: 
10-25 20:06:37.432  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.432  5515  5562 I jxcore-log: 
,10-25 20:06:37.440  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-25 20:06:37.440  5515  5562 I jxcore-log: 
10-25 20:06:37.440  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-25 20:06:37.440  5515  5562 I jxcore-log: 
,10-25 20:06:37.440  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-25 20:06:37.440  5515  5562 I jxcore-log: 
10-25 20:06:37.440  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.440  5515  5562 I jxcore-log: 
10-25 20:06:37.441  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.441  5515  5562 I jxcore-log: 
10-25 20:06:37.441  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.441  5515  5562 I jxcore-log: 
,10-25 20:06:37.441  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.441  5515  5562 I jxcore-log: 
,10-25 20:06:37.446  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.446  5515  5562 I jxcore-log: 
,10-25 20:06:37.451  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.451  5515  5562 I jxcore-log: 
,10-25 20:06:37.451  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.451  5515  5562 I jxcore-log: 
10-25 20:06:37.451  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.451  5515  5562 I jxcore-log: 
10-25 20:06:37.452  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.452  5515  5562 I jxcore-log: 
10-25 20:06:37.452  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.452  5515  5562 I jxcore-log: 
10-25 20:06:37.452  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.452  5515  5562 I jxcore-log: 
10-25 20:06:37.452  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.452  5515  5562 I jxcore-log: 
,10-25 20:06:37.454  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.454  5515  5562 I jxcore-log: 
10-25 20:06:37.454  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.454  5515  5562 I jxcore-log: 
,10-25 20:06:37.454  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.454  5515  5562 I jxcore-log: 
10-25 20:06:37.455  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.455  5515  5562 I jxcore-log: 
10-25 20:06:37.455  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.455  5515  5562 I jxcore-log: 
10-25 20:06:37.455  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.455  5515  5562 I jxcore-log: 
10-25 20:06:37.455  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.455  5515  5562 I jxcore-log: 
10-25 20:06:37.456  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.456  5515  5562 I jxcore-log: 
,10-25 20:06:37.456  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.456  5515  5562 I jxcore-log: 
10-25 20:06:37.456  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.456  5515  5562 I jxcore-log: 
10-25 20:06:37.456  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.456  5515  5562 I jxcore-log: 
,10-25 20:06:37.456  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.456  5515  5562 I jxcore-log: 
10-25 20:06:37.457  5515  5515 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-25 20:06:37.457  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.457  5515  5562 I jxcore-log: 
10-25 20:06:37.457  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.457  5515  5562 I jxcore-log: 
10-25 20:06:37.457  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.457  5515  5562 I jxcore-log: 
10-25 20:06:37.457  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.457  5515  5562 I jxcore-log: 
10-25 20:06:37.458  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 20:06:37.458  5515  5562 I jxcore-log: 
10-25 20:06:37.458  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.458  5515  5562 I jxcore-log: 
,10-25 20:06:37.458  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.458  5515  5562 I jxcore-log: 
10-25 20:06:37.458  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.458  5515  5562 I jxcore-log: 
10-25 20:06:37.458  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.458  5515  5562 I jxcore-log: 
10-25 20:06:37.459  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.459  5515  5562 I jxcore-log: 
10-25 20:06:37.459  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 20:06:37.459  5515  5562 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,10-25 20:06:37.459  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.459  5515  5562 I jxcore-log: 
10-25 20:06:37.459  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.459  5515  5562 I jxcore-log: 
10-25 20:06:37.459  5515  5562 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 20:06:37.460  5515  5562 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,10-25 20:06:37.460  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 20:06:37.460  5515  5562 I jxcore-log: 
10-25 20:06:37.460  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-25 20:06:37.460  5515  5562 I jxcore-log: 
10-25 20:06:37.460  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-25 20:06:37.460  5515  5562 I jxcore-log: 
10-25 20:06:37.461  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.461  5515  5562 I jxcore-log: 
10-25 20:06:37.461  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 20:06:37.461  5515  5562 I jxcore-log: 
,10-25 20:06:37.461  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-25 20:06:37.461  5515  5562 I jxcore-log: 
,10-25 20:06:37.466  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-25 20:06:37.466  5515  5562 I jxcore-log: 
10-25 20:06:37.467  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - WARN testUtils: 'myNameCallback not set!'
10-25 20:06:37.467  5515  5562 I jxcore-log: 
,10-25 20:06:37.468  5515  5562 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,10-25 20:06:37.468  5515  5562 I jxcore-log: 2016-10-25 18:06:37 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-25 20:06:37.468  5515  5562 I jxcore-log: 
,10-25 20:06:39.525  5515  5562 I jxcore-log: 2016-10-25 18:06:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-25 20:06:39.525  5515  5562 I jxcore-log: 
,10-25 20:06:39.857  5515  5562 I jxcore-log: 2016-10-25 18:06:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-25 20:06:39.857  5515  5562 I jxcore-log: 
,10-25 20:06:39.872  5515  5562 I jxcore-log: 2016-10-25 18:06:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-25 20:06:39.872  5515  5562 I jxcore-log: 
,10-25 20:06:40.969  5515  5562 I jxcore-log: 2016-10-25 18:06:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-25 20:06:40.969  5515  5562 I jxcore-log: 
,10-25 20:06:41.133  5515  5562 I jxcore-log: 2016-10-25 18:06:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-25 20:06:41.133  5515  5562 I jxcore-log: 
,10-25 20:06:41.138  5515  5562 I jxcore-log: 2016-10-25 18:06:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-25 20:06:41.138  5515  5562 I jxcore-log: 
,10-25 20:06:41.143  5515  5562 I jxcore-log: 2016-10-25 18:06:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-25 20:06:41.143  5515  5562 I jxcore-log: 
,10-25 20:06:41.613  5515  5562 I jxcore-log: 2016-10-25 18:06:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-25 20:06:41.613  5515  5562 I jxcore-log: 
,10-25 20:06:41.656  5515  5562 I jxcore-log: 2016-10-25 18:06:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-25 20:06:41.656  5515  5562 I jxcore-log: 
,10-25 20:06:41.669  5515  5562 I jxcore-log: 2016-10-25 18:06:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-25 20:06:41.669  5515  5562 I jxcore-log: 
,10-25 20:06:41.673  5515  5562 I jxcore-log: 2016-10-25 18:06:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-25 20:06:41.673  5515  5562 I jxcore-log: 
,10-25 20:06:41.952  5515  5562 I jxcore-log: 2016-10-25 18:06:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-25 20:06:41.952  5515  5562 I jxcore-log: 
,10-25 20:06:42.076  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-25 20:06:42.076  5515  5562 I jxcore-log: 
,10-25 20:06:42.454  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-25 20:06:42.454  5515  5562 I jxcore-log: 
,10-25 20:06:42.462  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-25 20:06:42.462  5515  5562 I jxcore-log: 
,10-25 20:06:42.465  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-25 20:06:42.465  5515  5562 I jxcore-log: 
,10-25 20:06:42.470  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-25 20:06:42.470  5515  5562 I jxcore-log: 
,10-25 20:06:42.475  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-25 20:06:42.475  5515  5562 I jxcore-log: 
,10-25 20:06:42.501  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-25 20:06:42.501  5515  5562 I jxcore-log: 
,10-25 20:06:42.537  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-25 20:06:42.537  5515  5562 I jxcore-log: 
,10-25 20:06:42.544  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-25 20:06:42.544  5515  5562 I jxcore-log: 
,10-25 20:06:42.551  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-25 20:06:42.551  5515  5562 I jxcore-log: 
,10-25 20:06:42.567  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-25 20:06:42.567  5515  5562 I jxcore-log: 
,10-25 20:06:42.571  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-25 20:06:42.571  5515  5562 I jxcore-log: 
,10-25 20:06:42.577  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-25 20:06:42.577  5515  5562 I jxcore-log: 
,10-25 20:06:42.582  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-25 20:06:42.582  5515  5562 I jxcore-log: 
,10-25 20:06:42.595  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-25 20:06:42.595  5515  5562 I jxcore-log: 
,10-25 20:06:42.597   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:42.617  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-25 20:06:42.617  5515  5562 I jxcore-log: 
,10-25 20:06:42.628  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-25 20:06:42.628  5515  5562 I jxcore-log: 
,10-25 20:06:42.640  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-25 20:06:42.640  5515  5562 I jxcore-log: 
,10-25 20:06:42.651  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-25 20:06:42.651  5515  5562 I jxcore-log: 
,10-25 20:06:42.664  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-25 20:06:42.664  5515  5562 I jxcore-log: 
,10-25 20:06:42.674  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-25 20:06:42.674  5515  5562 I jxcore-log: 
,10-25 20:06:42.678  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-25 20:06:42.678  5515  5562 I jxcore-log: 
,10-25 20:06:42.700  5515  5562 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-25 20:06:42.701  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - INFO testUtils: 'BLE multiple advertisement supported'
10-25 20:06:42.701  5515  5562 I jxcore-log: 
,10-25 20:06:42.774  5515  5562 I jxcore-log: 2016-10-25 18:06:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:42.774  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:42.774  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:42.774  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:42.774  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:42.774  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:42.774  5515  5562 I jxcore-log: 
,10-25 20:06:43.026  5515  5562 I jxcore-log: 2016-10-25 18:06:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:43.026  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:43.026  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:43.026  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:43.026  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:43.026  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:43.026  5515  5562 I jxcore-log: 
,10-25 20:06:43.029  5515  5562 I jxcore-log: 2016-10-25 18:06:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:43.029  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:43.029  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:43.029  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:43.029  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:43.029  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:43.029  5515  5562 I jxcore-log: 
,10-25 20:06:43.543  5515  5562 I jxcore-log: 2016-10-25 18:06:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:43.543  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:43.543  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:43.543  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:43.543  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:43.543  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:43.543  5515  5562 I jxcore-log: 
,10-25 20:06:43.547  5515  5562 I jxcore-log: 2016-10-25 18:06:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:43.547  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:43.547  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:43.547  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:43.547  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:43.547  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:43.547  5515  5562 I jxcore-log: 
,10-25 20:06:43.598   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:44.362  5515  5562 I jxcore-log: 2016-10-25 18:06:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:44.362  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:44.362  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:44.362  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:44.362  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:44.362  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:44.362  5515  5562 I jxcore-log: 
,10-25 20:06:44.365  5515  5562 I jxcore-log: 2016-10-25 18:06:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:44.365  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:44.365  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:44.365  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:44.365  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:44.365  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:44.365  5515  5562 I jxcore-log: 
,10-25 20:06:44.599   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:45.315  5515  5562 I jxcore-log: 2016-10-25 18:06:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:45.315  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:45.315  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:45.315  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:45.315  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:45.315  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:45.315  5515  5562 I jxcore-log: 
,10-25 20:06:45.324  5515  5562 I jxcore-log: 2016-10-25 18:06:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:45.324  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:45.324  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:45.324  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:45.324  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:45.324  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:45.324  5515  5562 I jxcore-log: 
,10-25 20:06:45.601   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:46.602   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 20:06:47.602   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-25 20:06:48.563  5515  5562 I jxcore-log: 2016-10-25 18:06:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:48.563  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:48.563  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:48.563  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:48.563  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:48.563  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:48.563  5515  5562 I jxcore-log: 
,10-25 20:06:48.569  5515  5562 I jxcore-log: 2016-10-25 18:06:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:48.569  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:48.569  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:48.569  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:48.569  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:48.569  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:48.569  5515  5562 I jxcore-log: 
,10-25 20:06:49.626  5515  5562 I jxcore-log: 2016-10-25 18:06:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:49.626  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:49.626  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:49.626  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:49.626  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:49.626  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:49.626  5515  5562 I jxcore-log: 
,10-25 20:06:49.630  5515  5562 I jxcore-log: 2016-10-25 18:06:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:49.630  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:49.630  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:49.630  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:49.630  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:49.630  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:49.630  5515  5562 I jxcore-log: 
,10-25 20:06:50.736  5515  5562 I jxcore-log: 2016-10-25 18:06:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:50.736  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:50.736  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:50.736  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:50.736  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:50.736  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:50.736  5515  5562 I jxcore-log: 
,10-25 20:06:50.742  5515  5562 I jxcore-log: 2016-10-25 18:06:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:50.742  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:50.742  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:50.742  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:50.742  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:50.742  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:50.742  5515  5562 I jxcore-log: 
,10-25 20:06:51.788  5515  5562 I jxcore-log: 2016-10-25 18:06:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:51.788  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:51.788  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:51.788  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:51.788  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:51.788  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:51.788  5515  5562 I jxcore-log: 
,10-25 20:06:51.793  5515  5562 I jxcore-log: 2016-10-25 18:06:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:51.793  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:51.793  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:51.793  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:51.793  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:51.793  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:51.793  5515  5562 I jxcore-log: 
,10-25 20:06:52.829  5515  5562 I jxcore-log: 2016-10-25 18:06:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:52.829  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:52.829  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:52.829  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:52.829  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:52.829  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:52.829  5515  5562 I jxcore-log: 
,10-25 20:06:52.834  5515  5562 I jxcore-log: 2016-10-25 18:06:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:52.834  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:52.834  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:52.834  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:52.834  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:52.834  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:52.834  5515  5562 I jxcore-log: 
,10-25 20:06:53.906  5515  5562 I jxcore-log: 2016-10-25 18:06:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:53.906  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:53.906  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:53.906  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:53.906  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:53.906  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:53.906  5515  5562 I jxcore-log: 
,10-25 20:06:53.910  5515  5562 I jxcore-log: 2016-10-25 18:06:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:53.910  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:53.910  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:53.910  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:53.910  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:53.910  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:53.910  5515  5562 I jxcore-log: 
,10-25 20:06:54.944  5515  5562 I jxcore-log: 2016-10-25 18:06:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:54.944  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:54.944  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:54.944  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:54.944  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:54.944  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:54.944  5515  5562 I jxcore-log: 
,10-25 20:06:54.949  5515  5562 I jxcore-log: 2016-10-25 18:06:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:54.949  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:54.949  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:54.949  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:54.949  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:54.949  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:54.949  5515  5562 I jxcore-log: 
,10-25 20:06:55.988  5515  5562 I jxcore-log: 2016-10-25 18:06:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:55.988  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:55.988  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:55.988  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:55.988  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:55.988  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:55.988  5515  5562 I jxcore-log: 
,10-25 20:06:55.992  5515  5562 I jxcore-log: 2016-10-25 18:06:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:55.992  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:55.992  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:55.992  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:55.992  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:55.992  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:55.992  5515  5562 I jxcore-log: 
,10-25 20:06:57.044  5515  5562 I jxcore-log: 2016-10-25 18:06:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:57.044  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:57.044  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:57.044  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:57.044  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:57.044  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:57.044  5515  5562 I jxcore-log: 
,10-25 20:06:57.048  5515  5562 I jxcore-log: 2016-10-25 18:06:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:57.048  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:57.048  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:57.048  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:57.048  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:57.048  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:57.048  5515  5562 I jxcore-log: 
,10-25 20:06:58.078  5515  5562 I jxcore-log: 2016-10-25 18:06:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:58.078  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:58.078  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:58.078  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:58.078  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:58.078  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:58.078  5515  5562 I jxcore-log: 
,10-25 20:06:58.083  5515  5562 I jxcore-log: 2016-10-25 18:06:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:58.083  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:58.083  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:58.083  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:58.083  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:58.083  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:58.083  5515  5562 I jxcore-log: 
,10-25 20:06:59.118  5515  5562 I jxcore-log: 2016-10-25 18:06:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-25 20:06:59.118  5515  5562 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-25 20:06:59.118  5515  5562 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-25 20:06:59.118  5515  5562 I jxcore-log: emit@events.js:82:1
10-25 20:06:59.118  5515  5562 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-25 20:06:59.118  5515  5562 I jxcore-log: emit@events.js:82:1'
10-25 20:06:59.118  5515  5562 I jxcore-log: 
,10-25 20:06:59.127  5515  5562 E jxcore  : Error!: error is undefined
10-25 20:06:59.127  5515  5562 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-25 20:06:59.133  5515  5562 I jxcore-log: 2016-10-25 18:06:59 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-25 20:06:59.133  5515  5562 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
10-25 20:06:59.133  5515  5562 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-25 20:06:59.133  5515  5562 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-25 20:06:59.133  5515  5562 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-25 20:06:59.133  5515  5562 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-25 20:06:59.133  5515  5562 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-25 20:06:59.133  5515  5562 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,10-25 20:06:59.135  5515  5562 I jxcore-log: 2016-10-25 18:06:59 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-25 20:06:59.135  5515  5562 I jxcore-log: 
,10-25 20:06:59.137  5515  5562 E jxcore-log: TypeError: 
10-25 20:06:59.137  5515  5562 E jxcore-log: error is undefined
10-25 20:06:59.137  5515  5562 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
10-25 20:06:59.137  5515  5562 E jxcore-log: 
,10-25 20:06:59.226   925  3103 I WindowState: WIN DEATH: Window{728f77e u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-25 20:06:59.226   925  2920 D WifiService: Client connection lost with reason: 4
,10-25 20:06:59.226   925  3979 D GraphicsStats: Buffer count: 2
,10-25 20:06:59.247   528   528 I Zygote  : Process 5515 exited cleanly (139)
,10-25 20:06:59.247   925  3763 I ActivityManager: Process com.test.thalitest (pid 5515) has died
,10-25 20:06:59.260   925  3763 I ActivityManager: Start proc 5863:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-25 20:06:59.337  5863  5863 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-25 20:06:59.355  5863  5863 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-25 20:06:59.360  5863  5863 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5808-5810)
,10-25 20:06:59.360  5863  5863 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-25 20:06:59.368  5863  5863 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {914353e}
,10-25 20:06:59.369  5863  5863 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-25 20:06:59.369  5863  5863 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-25 20:06:59.372  5863  5863 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-25 20:06:59.373  5863  5863 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-25 20:06:59.383  5863  5863 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-25 20:06:59.390  5863  5863 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-25 20:06:59.391  5863  5863 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-25 20:06:59.391  5863  5863 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-25 20:06:59.391  5863  5863 I Adreno  : Build Date                       : 12/06/15
10-25 20:06:59.391  5863  5863 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-25 20:06:59.391  5863  5863 I Adreno  : Local Branch                     : mybranch17112971
10-25 20:06:59.391  5863  5863 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-25 20:06:59.391  5863  5863 I Adreno  : Remote Branch                    : NONE
10-25 20:06:59.391  5863  5863 I Adreno  : Reconstruct Branch               : NOTHING
,10-25 20:06:59.423   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@73487b9:true
,10-25 20:06:59.435   948   948 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[25409]" dev="sockfs" ino=25409 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 20:06:59.435   948   948 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[25409]" dev="sockfs" ino=25409 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 20:06:59.449  5863  5863 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-25 20:06:59.457  5863  5863 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-25 20:06:59.487  5863  5899 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-25 20:06:59.485  3379  3379 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[37988]" dev="sockfs" ino=37988 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-25 20:06:59.485  3379  3379 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[37988]" dev="sockfs" ino=37988 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 20:06:59.488  3757  3757 W Binder_8: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[25421]" dev="sockfs" ino=25421 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 20:06:59.488  3757  3757 W Binder_8: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[25421]" dev="sockfs" ino=25421 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-25 20:06:59.492  5863  5886 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-25 20:06:59.532  5863  5899 I OpenGLRenderer: Initialized EGL, version 1.4
,10-25 20:06:59.570   925  3104 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5515 uid 10077
,10-25 20:06:59.568  3104  3104 W Binder_4: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[36114]" dev="sockfs" ino=36114 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-25 20:06:59.568  3104  3104 W Binder_4: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[36114]" dev="sockfs" ino=36114 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 20:06:59.573  3590  3590 I Keyboard.Facilitator: onFinishInput()
,10-25 20:06:59.573   925   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +293ms (total +325ms)
10-25 20:06:59.568  3554  3554 W Binder_6: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[36113]" dev="sockfs" ino=36113 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 20:06:59.568  3554  3554 W Binder_6: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[36113]" dev="sockfs" ino=36113 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 20:06:59.574  5863  5863 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5863
,10-25 20:06:59.631  5863  5863 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-25 20:06:59.656  5861  5861 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-25 20:06:59.672  5861  5861 D AndroidRuntime: CheckJNI is OFF
,10-25 20:06:59.696  5861  5861 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-25 20:06:59.722  5861  5861 I Radio-JNI: register_android_hardware_Radio DONE
,10-25 20:06:59.737  5861  5861 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-25 20:06:59.741   925   938 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-25 20:06:59.741   925   938 I ActivityManager: Killing 5863:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-25 20:06:59.753   925  2884 W InputDispatcher: channel 'c3425dc com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-25 20:06:59.753   925  2884 E InputDispatcher: channel 'c3425dc com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-25 20:06:59.755   925  3979 D GraphicsStats: Buffer count: 2
10-25 20:06:59.755   925   935 I WindowState: WIN DEATH: Window{c3425dc u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-25 20:06:59.755   925   935 W InputDispatcher: Attempted to unregister already unregistered input channel 'c3425dc com.test.thalitest/com.test.thalitest.MainActivity (server)'
,10-25 20:06:59.843   925   938 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
10-25 20:06:59.843   925   938 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-25 20:06:59.844   925   938 E ActivityManager: Failure starting process com.test.thalitest
10-25 20:06:59.844   925   938 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-25 20:06:59.844   925   938 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 20:06:59.844   925   938 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-25 20:06:59.844   925   938 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-25 20:06:59.844   925   938 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-25 20:06:59.845   925   938 I ActivityManager:   Force finishing activity ActivityRecord{5f54046 u0 com.test.thalitest/.MainActivity t66}
10-25 20:06:59.845   925   949 I art     : Starting a blocking GC Explicit
,10-25 20:06:59.851   925  3515 W ActivityManager: Spurious death for ProcessRecord{13df5ba 0:com.test.thalitest/u0a77}, curProc for 5863: null
,10-25 20:06:59.932   925   949 I art     : Explicit concurrent mark sweep GC freed 12863(856KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 2.040ms total 86.863ms
,10-25 20:06:59.955   925   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-25 20:06:59.959  5861  5861 I art     : System.exit called, status: 0
,10-25 20:06:59.960  5861  5861 I AndroidRuntime: VM exiting with result code 0.
,10-25 20:06:59.969   925   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-25 20:06:59.974   925   938 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-25 20:06:59.979  5754  5754 D BluetoothMapAppObserver: onReceive
10-25 20:06:59.979  5754  5754 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-25 20:06:59.985  3658  4034 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-25 20:06:59.989   925  2885 I InputReader: Reconfiguring input devices.  changes=0x00000010
10-25 20:06:59.990  3590  3590 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-25 20:07:00.008  3590  5914 I Keyboard.Facilitator.DecoderInitializer: run()
,10-25 20:07:00.013  3703  3703 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-25 20:07:00.023  3344  5915 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-25 20:07:00.032  3590  5914 I Decoder : createOrResetDecoder
,10-25 20:07:00.064   925   925 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-25 20:07:00.071   494   494 W kworker/3:2: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 20:07:00.075   494   494 W kworker/3:2: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 20:07:00.075  3521  3521 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
10-25 20:07:00.076  3521  3521 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-25 20:07:00.087  3739  3874 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-25 20:07:00.091   494   494 W kworker/3:2: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 20:07:00.100   925  3104 I ActivityManager: Start proc 5920:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
10-25 20:07:00.100  3739  3874 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-25 20:07:00.100  3739  3874 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3739
10-25 20:07:00.100  3739  3874 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-25 20:07:00.100  3739  3874 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-25 20:07:00.100  3739  3874 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-25 20:07:00.100  3739  3874 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-25 20:07:00.100  3739  3874 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-25 20:07:00.100  3739  3874 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-25 20:07:00.100  3739  3874 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-25 20:07:00.100  3739  3874 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-25 20:07:00.100  3739  3874 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-25 20:07:00.100  3739  3874 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-25 20:07:00.100  3739  3874 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-25 20:07:00.100  3739  3874 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-25 20:07:00.105   925  3979 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-25 20:07:00.107   925  5929 E DropBoxManagerService: Can't write: system_app_crash
10-25 20:07:00.107   925  5929 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
10-25 20:07:00.107   925  5929 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-25 20:07:00.107   925  5929 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-25 20:07:00.107   925  5929 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-25 20:07:00.107   925  5929 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-25 20:07:00.107   925  5929 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-25 20:07:00.107   925  5929 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-25 20:07:00.107   925  5929 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-25 20:07:00.107   925  5929 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-25 20:07:00.107   925  5929 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-25 20:07:00.107   925  5929 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-25 20:07:00.107   925  5929 E DropBoxManagerService: 	... 5 more
,10-25 20:07:00.110  3739  3874 I Process : Sending signal. PID: 3739 SIG: 9
10-25 20:07:00.113  3521  3521 I ConfigService: onCreate
10-25 20:07:00.120  3344  5915 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-25 20:07:00.122  3521  5934 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java,:694)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-25 20:07:00.122  3521  5934 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
10-25 20:07:00.124  3521  5934 W SQLiteOpenHelper: Opened config.db in read-only mode
10-25 20:07:00.127  3344  5915 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
10-25 20:07:00.127  3344  5915 E AndroidRuntime: Process: android.process.acore, PID: 3344
10-25 20:07:00.127  3344  5915 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-25 20:07:00.127  3344  5915 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-25 20:07:00.134  3590  5914 I Keyboard.Facilitator.MainLanguageModelLoader: run()
10-25 20:07:00.151  3344  5915 I Process : Sending signal. PID: 3344 SIG: 9
10-25 20:07:00.152   925  5935 E DropBoxManagerService: Can't write: system_app_crash
10-25 20:07:00.152   925  5935 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
10-25 20:07:00.152   925  5935 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-25 20:07:00.152   925  5935 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-25 20:07:00.152   925  5935 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-25 20:07:00.152   925  5935 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-25 20:07:00.152   925  5935 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-25 20:07:00.152   925  5935 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-25 20:07:00.152   925  5935 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-25 20:07:00.152   925  5935 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-25 20:07:00.152   925  5935 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-25 20:07:00.152   925  5935 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-25 20:07:00.152   925  5935 E DropBoxManagerService: 	... 5 more
,10-25 20:07:00.171  3924  5933 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
10-25 20:07:00.175   381   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
