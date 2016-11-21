#### Test 931424420cf4179_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-21 14:29:49.767   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:29:50.229  5666  5666 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-21 14:29:50.235  5666  5666 D AndroidRuntime: CheckJNI is OFF
11-21 14:29:50.265  5666  5666 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-21 14:29:50.301  5666  5666 I Radio-JNI: register_android_hardware_Radio DONE
11-21 14:29:50.316  5666  5666 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-21 14:29:50.320   930   940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-21 14:29:50.344  3900  3912 W SearchService: Abort, client detached.
11-21 14:29:50.349  3900  3900 I HotwordDetector: Closing mic
11-21 14:29:50.349  5666  5666 D AndroidRuntime: Shutting down VM
11-21 14:29:50.349  3900  4131 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@452723f
11-21 14:29:50.349  3900  4138 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-21 14:29:50.373   930  3105 I ActivityManager: Start proc 5675:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-21 14:29:50.420   513  4142 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-21 14:29:50.421   513  4142 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-21 14:29:50.425   513  4142 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-21 14:29:50.425   513  4142 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-21 14:29:50.426   513  2969 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-21 14:29:50.428  3900  4132 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-21 14:29:50.429  3900  4133 I MicroRecognitionRnrImpl: Detection finished
11-21 14:29:50.464  5675  5675 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-21 14:29:50.485  5675  5675 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-21 14:29:50.507  5675  5675 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 7319-7338)
11-21 14:29:50.507  5675  5675 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-21 14:29:50.522  5675  5675 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4289812}
11-21 14:29:50.522  5675  5675 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-21 14:29:50.522  5675  5675 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-21 14:29:50.525  5675  5675 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-21 14:29:50.526  5675  5675 E SysUtils: ApplicationContext is null in ApplicationStatus
11-21 14:29:50.555  5675  5675 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
11-21 14:29:50.565  5675  5675 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-21 14:29:50.565  5675  5675 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-21 14:29:50.565  5675  5675 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-21 14:29:50.565  5675  5675 I Adreno  : Build Date                       : 12/06/15
11-21 14:29:50.565  5675  5675 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-21 14:29:50.565  5675  5675 I Adreno  : Local Branch                     : mybranch17112971
11-21 14:29:50.565  5675  5675 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-21 14:29:50.565  5675  5675 I Adreno  : Remote Branch                    : NONE
11-21 14:29:50.565  5675  5675 I Adreno  : Reconstruct Branch               : NOTHING
,11-21 14:29:50.596   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a407d44:true
,11-21 14:29:50.615   407   407 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[33860]" dev="sockfs" ino=33860 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 14:29:50.615   407   407 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33860]" dev="sockfs" ino=33860 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 14:29:50.629  5675  5675 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-21 14:29:50.637  5675  5675 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-21 14:29:50.655  3940  3940 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[30546]" dev="sockfs" ino=30546 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 14:29:50.662  5675  5712 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-21 14:29:50.659  3940  3940 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30546]" dev="sockfs" ino=30546 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 14:29:50.665  5675  5699 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
11-21 14:29:50.659  3105  3105 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[16017]" dev="sockfs" ino=16017 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 14:29:50.659  3105  3105 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[16017]" dev="sockfs" ino=16017 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 14:29:50.685  5675  5712 I OpenGLRenderer: Initialized EGL, version 1.4
,11-21 14:29:50.752  3105  3105 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[30550]" dev="sockfs" ino=30550 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 14:29:50.755   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +404ms
11-21 14:29:50.752  3105  3105 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[30550]" dev="sockfs" ino=30550 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 14:29:50.758  3605  3605 I Keyboard.Facilitator: onFinishInput()
,11-21 14:29:50.752  3805  3805 W Binder_8: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[30549]" dev="sockfs" ino=30549 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 14:29:50.752  3805  3805 W Binder_8: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[30549]" dev="sockfs" ino=30549 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 14:29:50.768   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:29:50.814  5675  5675 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5675
,11-21 14:29:50.901  5675  5675 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-21 14:29:51.028  5675  5714 D jxcore_app_log: JniHelper::setJavaVM(0xf527c000), pthread_self() = -565446352
,11-21 14:29:51.031  5675  5714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-21 14:29:51.031  5675  5714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-21 14:29:51.031  5675  5714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-21 14:29:51.031  5675  5714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-21 14:29:51.031  5675  5714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-21 14:29:51.031  5675  5714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d91d9b8 added. We now have 1 listener(s)
,11-21 14:29:51.033  5675  5714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
11-21 14:29:51.034  5675  5714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 14:29:51.034  5675  5714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-21 14:29:51.034  5675  5714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-21 14:29:51.036  5675  5714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@266d964 added. We now have 1 listener(s)
11-21 14:29:51.036  5675  5714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 14:29:51.040   930  2925 D WifiService: New client listening to asynchronous messages
,11-21 14:29:51.041  5675  5714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 14:29:51.041  5675  5714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-21 14:29:51.041  5675  5714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-21 14:29:51.041  5675  5714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-21 14:29:51.042  5675  5714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-21 14:29:51.042  5675  5714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-21 14:29:51.042  5675  5714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-21 14:29:51.043  5675  5714 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-21 14:29:51.156  5675  5675 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-21 14:29:51.174   930  3809 I ActivityManager: Killing 5016:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-21 14:29:51.205   930  3809 I ActivityManager: Killing 5244:com.android.settings/1000 (adj 15): empty #18
,11-21 14:29:51.461  5675  5722 W jxcore-log: Initializing JXcore engine
,11-21 14:29:51.461  5675  5722 W jxcore-log: JXcore engine is ready
,11-21 14:29:51.489  5722  5722 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12357 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-21 14:29:51.489  5722  5722 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15399]" dev="sockfs" ino=15399 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-21 14:29:51.489  5722  5722 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-21 14:29:51.489  5722  5722 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33695]" dev="sockfs" ino=33695 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-21 14:29:51.499  5675  5722 W jxcore-log: Starting JXcore engine
,11-21 14:29:51.554  5675  5722 W jxcore-log: Platform android
11-21 14:29:51.554  5675  5722 W jxcore-log: 
,11-21 14:29:51.554  5675  5722 W jxcore-log: Process ARCH arm
11-21 14:29:51.554  5675  5722 W jxcore-log: 
,11-21 14:29:51.700  5675  5722 I jxcore-log: JXcore Cordova bridge is ready!
11-21 14:29:51.700  5675  5722 I jxcore-log: 
,11-21 14:29:51.700  5675  5722 W jxcore-log: JXcore engine is started
,11-21 14:29:51.705  5675  5714 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-21 14:29:51.708  5675  5675 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-21 14:29:51.768   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:29:52.769   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 14:29:54.735   930  2926 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 14:29:57.761   930  2926 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 14:30:00.431  3900  5724 W CronetSyncConnectionRcs: Upload content type not set.
,11-21 14:30:00.771   930  2926 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 14:30:01.282  5675  5722 I jxcore-log: 2016-11-21 13:30:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-21 14:30:01.282  5675  5722 I jxcore-log: 
,11-21 14:30:01.284  5675  5722 I jxcore-log: 2016-11-21 13:30:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-21 14:30:01.284  5675  5722 I jxcore-log: 
11-21 14:30:01.285  5675  5722 I jxcore-log: 2016-11-21 13:30:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
11-21 14:30:01.285  5675  5722 I jxcore-log: 
,11-21 14:30:01.290  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-21 14:30:01.290  5675  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 14:30:01.290  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 14:30:01.290  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 14:30:01.290  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 14:30:01.290  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 14:30:01.290  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 14:30:01.290  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 14:30:01.290  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 14:30:01.290  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 14:30:01.291  5675  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 14:30:01.294  5675  5722 I jxcore-log: 2016-11-21 13:30:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-21 14:30:01.294  5675  5722 I jxcore-log: 
11-21 14:30:01.295  5675  5722 I jxcore-log: 2016-11-21 13:30:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-21 14:30:01.295  5675  5722 I jxcore-log: 
,11-21 14:30:01.545  5675  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 14:30:01.545  5675  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73060f6 added. We now have 2 listener(s)
,11-21 14:30:01.546  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 14:30:01.546  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 14:30:01.546  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 14:30:01.546  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-21 14:30:01.546  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1686cf7 added. We now have 2 listener(s)
11-21 14:30:01.546  5675  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 14:30:01.547  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 14:30:01.548  5675  5722 D ExecuteNativeTests: Running unit tests
11-21 14:30:01.548  5675  5722 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 14:30:01.549   930  3615 D WifiService: setWifiEnabled: true pid=5675, uid=10077
11-21 14:30:01.549   930  3615 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 14:30:04.797   930  2919 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 14:30:05.460   930  5334 D NetlinkSocketObserver: NeighborEvent{elapsedMs=182291, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 14:30:06.830   930  2926 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 14:30:11.554  5675  5722 I com.test.thalitest.ThaliTestRunner: Running UT
,11-21 14:30:11.622  5675  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 14:30:11.622  5675  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7cb218 added. We now have 3 listener(s)
,11-21 14:30:11.623  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 14:30:11.623  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 14:30:11.623  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 14:30:11.623  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 14:30:11.623  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5eb5471 added. We now have 3 listener(s)
,11-21 14:30:11.623  5675  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 14:30:11.624  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 14:30:11.633  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-21 14:30:11.634  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 14:30:11.634  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-21 14:30:11.634  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 14:30:11.634  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 14:30:11.635  5675  5722 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-21 14:30:11.635  5675  5722 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-21 14:30:11.635  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-21 14:30:11.635  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 14:30:11.635  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 14:30:11.635  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 14:30:11.636  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-21 14:30:11.637  5675  5722 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-21 14:30:11.638  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-21 14:30:11.640  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-21 14:30:11.640  5675  5722 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-21 14:30:11.642  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 14:30:11.643  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 14:30:11.650  5675  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 14:30:11.650  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 14:30:11.650  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 14:30:11.650  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 14:30:11.650  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 14:30:11.650  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 14:30:11.650  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 14:30:11.650  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 14:30:11.650  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 14:30:11.654  5675  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 14:30:11.655  5675  5722 D io.jxcore.node.ConnectivityMonitor: start: OK
11-21 14:30:11.656  5675  5722 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-21 14:30:11.656  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-21 14:30:11.656  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:11.656  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.656  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.656  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-21 14:30:11.656  5675  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 14:30:11.657  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 14:30:11.657  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 14:30:11.659  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 14:30:11.659  5675  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 14:30:11.659  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 14:30:11.660  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 14:30:11.660  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-21 14:30:11.660  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 14:30:11.660  5675  5728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 14:30:11.660  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 14:30:11.660  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 14:30:11.660  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 14:30:11.661  5675  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 14:30:11.662  5675  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-21 14:30:11.663  5675  5728 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 14:30:11.663  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 14:30:11.663  5675  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-21 14:30:11.664  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 14:30:11.662  4817  4817 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31193]" dev="sockfs" ino=31193 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 14:30:11.662  4817  4817 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31193]" dev="sockfs" ino=31193 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 14:30:11.670  5675  5728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 14:30:11.671  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.671  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-21 14:30:11.673  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-21 14:30:11.674  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-21 14:30:11.674  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-21 14:30:11.676  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.676  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.676  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 14:30:11.676  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 14:30:11.676  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 14:30:11.676  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-21 14:30:11.677  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 14:30:11.677  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:11.677  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.677  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 14:30:11.677  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:11.677  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.678  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.678  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:11.679  5675  5722 D BluetoothAdapter: STATE_ON
,11-21 14:30:11.683  4598  4614 D BtGatt.GattService: registerClient() - UUID=5bbb22dc-daf1-44a3-8cde-6d4cc9305ca6
,11-21 14:30:11.684  4598  4661 D BtGatt.GattService: onClientRegistered() - UUID=5bbb22dc-daf1-44a3-8cde-6d4cc9305ca6, clientIf=5
,11-21 14:30:11.685  5675  5685 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 14:30:11.687  4598  4663 D BtGatt.AdvertiseManager: message : 0
11-21 14:30:11.690  4598  4663 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 14:30:11.708  4598  4661 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 14:30:11.717  4598  4661 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 14:30:11.720  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:11.720  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.720  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 14:30:11.720  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.720  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.721  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.721  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.721  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.721  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 14:30:11.722  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 14:30:11.722  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:11.724  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:11.724  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.724  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:11.725  5675  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 14:30:11.725  5675  5722 I io.jxcore.node.ConnectionHelper: start: OK
11-21 14:30:11.725  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 14:30:11.726  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:11.726  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 14:30:11.726  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 14:30:11.726  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-21 14:30:11.727  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:11.727  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:11.727  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 14:30:11.727  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 14:30:11.727  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:11.727  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 14:30:11.728  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 14:30:11.728  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 14:30:11.732  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 14:30:11.733  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 14:30:11.733  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-21 14:30:11.733  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:11.733  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:11.733  5675  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 14:30:12.230  5675  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-21 14:30:12.230  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-21 14:30:12.230  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-21 14:30:12.231  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-21 14:30:12.231  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-21 14:30:12.231  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-21 14:30:12.231  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-21 14:30:12.231  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-21 14:30:12.231  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-21 14:30:12.231  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-21 14:30:12.232  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-21 14:30:12.232  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-21 14:30:12.232  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-21 14:30:12.232  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-21 14:30:12.232  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-21 14:30:12.233  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-21 14:30:12.233  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-21 14:30:12.233  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-21 14:30:12.233  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-21 14:30:12.233  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-21 14:30:12.233  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-21 14:30:12.234  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-21 14:30:12.234  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-21 14:30:12.234  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-21 14:30:12.234  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-21 14:30:12.238  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-21 14:30:12.238  5675  5675 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 14:30:12.238  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-21 14:30:12.238  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-21 14:30:12.238  5675  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 14:30:12.238  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-21 14:30:12.238  5675  5675 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 14:30:12.238  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-21 14:30:12.239  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-21 14:30:12.239  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-21 14:30:12.240  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 14:30:12.240  5675  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 14:30:12.240  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 14:30:12.241  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-21 14:30:12.241  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 14:30:12.242  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 14:30:12.242  5675  5728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 14:30:12.242  5675  5728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 14:30:12.242  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 14:30:12.242  5675  5728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-21 14:30:12.242  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 14:30:12.243  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 14:30:12.243  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 14:30:12.243  5675  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 14:30:12.243  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 14:30:12.243  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 14:30:12.247  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.247  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.248  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.248  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.250  5675  5722 D BluetoothAdapter: STATE_ON
,11-21 14:30:12.251  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 14:30:12.252  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:12.252  5675  5722 D BluetoothLeScanner: could not find callback wrapper
11-21 14:30:12.253  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 14:30:12.253  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.253  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.253  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.253  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 14:30:12.253  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.254  4598  4663 D BtGatt.AdvertiseManager: message : 1
11-21 14:30:12.255  4598  4663 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 14:30:12.265  4598  4661 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 14:30:12.265  4598  4661 D BtGatt.GattService: Client app is not null!
,11-21 14:30:12.266  4598  4614 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 14:30:12.267  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 14:30:12.267  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.268  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 14:30:12.268  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.268  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.268  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.268  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 14:30:12.268  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 14:30:12.269  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 14:30:12.269  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.270  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.271  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 14:30:12.271  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.271  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.271  5675  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 14:30:12.271  5675  5675 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 14:30:12.271  5675  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 14:30:12.271  5675  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 14:30:12.271  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 14:30:12.272  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 14:30:12.272  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:12.272  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.272  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 14:30:12.272  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 14:30:12.272  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.272  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.272  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 14:30:12.272  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 14:30:12.276  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.276  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.276  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.277  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.277  5675  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 14:30:12.277  5675  5722 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 14:30:12.278  5675  5722 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-21 14:30:12.278  5675  5722 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-21 14:30:12.278  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-21 14:30:12.278  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.278  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.278  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.278  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 14:30:12.278  5675  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 14:30:12.278  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 14:30:12.278  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 14:30:12.279  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 14:30:12.280  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-21 14:30:12.280  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 14:30:12.280  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 14:30:12.280  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 14:30:12.280  5675  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 14:30:12.280  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 14:30:12.280  5675  5731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 14:30:12.280  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 14:30:12.280  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 14:30:12.281  5675  5731 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 14:30:12.286  5675  5731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 14:30:12.286  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 14:30:12.286  5675  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-21 14:30:12.286  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 14:30:12.282  4611  4611 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31196]" dev="sockfs" ino=31196 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 14:30:12.282  4611  4611 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31196]" dev="sockfs" ino=31196 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 14:30:12.291  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.291  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-21 14:30:12.292  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 14:30:12.292  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-21 14:30:12.292  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
,11-21 14:30:12.294  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.294  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.294  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 14:30:12.294  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 14:30:12.294  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 14:30:12.294  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-21 14:30:12.294  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:12.294  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:12.294  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.294  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 14:30:12.295  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:12.295  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.295  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.295  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.296  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:12.298  4598  4817 D BtGatt.GattService: registerClient() - UUID=c6d167b0-d5c3-4c3b-8681-87dec87ea938
11-21 14:30:12.298  4598  4661 D BtGatt.GattService: onClientRegistered() - UUID=c6d167b0-d5c3-4c3b-8681-87dec87ea938, clientIf=5
11-21 14:30:12.299  5675  5715 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 14:30:12.300  4598  4663 D BtGatt.AdvertiseManager: message : 0
11-21 14:30:12.302  4598  4663 D BtGatt.AdvertiseManager: starting multi advertising
11-21 14:30:12.313  4598  4661 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-21 14:30:12.319  4598  4661 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-21 14:30:12.320  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.320  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.320  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 14:30:12.320  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.320  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.320  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.320  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.320  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.320  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 14:30:12.322  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 14:30:12.322  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.323  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.323  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.323  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.323  5675  5722 I io.jxcore.node.ConnectionHelper: start: OK
11-21 14:30:12.323  5675  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 14:30:12.323  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.323  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:12.324  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 14:30:12.324  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.324  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.324  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:12.324  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.324  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 14:30:12.324  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 14:30:12.324  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.324  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.324  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 14:30:12.324  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.327  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.327  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 14:30:12.327  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.327  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.327  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.327  5675  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 14:30:12.770   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:30:12.827  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-21 14:30:12.827  5675  5722 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 14:30:12.828  5675  5722 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-21 14:30:12.828  5675  5722 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-21 14:30:12.828  5675  5722 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-21 14:30:12.828  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,11-21 14:30:12.829  5675  5675 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 14:30:12.829  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.829  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.829  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.831  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 14:30:12.831  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 14:30:12.831  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 14:30:12.831  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-21 14:30:12.831  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 14:30:12.831  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 14:30:12.831  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 14:30:12.831  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 14:30:12.831  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 14:30:12.831  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.831  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-21 14:30:12.832  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.832  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.832  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.835  4598  4663 D BtGatt.AdvertiseManager: message : 1
11-21 14:30:12.836  4598  4663 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 14:30:12.850  4598  4661 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 14:30:12.850  4598  4661 D BtGatt.GattService: Client app is not null!
,11-21 14:30:12.852  4598  4614 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 14:30:12.852  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 14:30:12.853  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.853  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 14:30:12.853  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.853  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.853  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.854  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 14:30:12.854  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.854  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.854  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.854  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-21 14:30:12.854  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 14:30:12.854  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 14:30:12.855  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-21 14:30:12.855  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:12.855  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 14:30:12.855  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.855  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 14:30:12.856  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:12.856  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.856  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.856  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.857  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:12.862  4598  4611 D BtGatt.GattService: registerClient() - UUID=7e581789-3a3f-417d-8779-1293caff4b43
11-21 14:30:12.863  4598  4661 D BtGatt.GattService: onClientRegistered() - UUID=7e581789-3a3f-417d-8779-1293caff4b43, clientIf=5
11-21 14:30:12.863  5675  5715 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 14:30:12.864  4598  4663 D BtGatt.AdvertiseManager: message : 0
11-21 14:30:12.870  4598  4663 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 14:30:12.887  4598  4661 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 14:30:12.896  4598  4661 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 14:30:12.897  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.897  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.897  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 14:30:12.897  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.897  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.897  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.897  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.898  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.898  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.898  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-21 14:30:12.898  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.898  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 14:30:12.898  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 14:30:12.899  5675  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-21 14:30:12.899  5675  5722 I io.jxcore.node.ConnectionHelper: start: OK
11-21 14:30:12.899  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.899  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:12.899  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-21 14:30:12.899  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.899  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.899  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:12.900  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 14:30:12.900  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 14:30:12.900  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 14:30:12.900  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.900  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.900  5675  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-21 14:30:12.900  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 14:30:12.900  5675  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 14:30:12.900  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 14:30:12.900  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-21 14:30:12.900  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 14:30:12.901  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 14:30:12.901  5675  5731 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-21 14:30:12.901  5675  5731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 14:30:12.901  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-21 14:30:12.901  5675  5731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 14:30:12.901  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 14:30:12.901  5675  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 14:30:12.901  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 14:30:12.901  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 14:30:12.901  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 14:30:12.901  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 14:30:12.901  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.902  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.902  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.902  5675  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 14:30:12.902  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.902  5675  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 14:30:12.903  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:12.903  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 14:30:12.904  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:12.904  5675  5722 D BluetoothLeScanner: could not find callback wrapper
11-21 14:30:12.904  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 14:30:12.904  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.904  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.904  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.904  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 14:30:12.904  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.905  4598  4663 D BtGatt.AdvertiseManager: message : 1
,11-21 14:30:12.906  4598  4663 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 14:30:12.914  4598  4661 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 14:30:12.914  4598  4661 D BtGatt.GattService: Client app is not null!
,11-21 14:30:12.915  4598  4817 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 14:30:12.915  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 14:30:12.916  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.916  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 14:30:12.916  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.916  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.916  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.916  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 14:30:12.916  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 14:30:12.917  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 14:30:12.917  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.918  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.918  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 14:30:12.918  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.919  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.919  5675  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 14:30:12.919  5675  5675 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 14:30:12.919  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 14:30:12.919  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 14:30:12.919  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:12.919  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.919  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 14:30:12.920  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 14:30:12.920  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.920  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.920  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 14:30:12.920  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current, thread: Thread[main,5,main], id: 1
11-21 14:30:12.921  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-21 14:30:12.921  5675  5722 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-21 14:30:12.921  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.921  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.922  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.922  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.922  5675  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 14:30:12.922  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,11-21 14:30:12.923  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 14:30:12.924  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-21 14:30:12.924  5675  5722 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-21 14:30:12.925  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-21 14:30:12.925  5675  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-21 14:30:12.926  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-21 14:30:12.926  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 14:30:12.926  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 14:30:12.926  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 14:30:12.926  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-21 14:30:12.926  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 14:30:12.926  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 14:30:12.926  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 14:30:12.926  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 14:30:12.926  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 14:30:12.926  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 14:30:12.927  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 14:30:12.927  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 14:30:12.927  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-21 14:30:12.927  5675  5722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 14:30:12.928  5675  5722 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-21 14:30:12.931  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-21 14:30:12.931  5675  5722 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-21 14:30:12.932  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,11-21 14:30:12.933  5675  5722 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-21 14:30:12.934  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,11-21 14:30:12.936  5675  5722 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
,11-21 14:30:12.936  5675  5722 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-21 14:30:12.937  5675  5722 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-21 14:30:12.937  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 14:30:12.938  5675  5722 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-21 14:30:12.938  5675  5722 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 14:30:12.938  5675  5722 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,11-21 14:30:12.938  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-21 14:30:12.939  5675  5722 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-21 14:30:12.939  5675  5722 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 14:30:12.939  5675  5722 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-21 14:30:12.939  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 14:30:12.939  5675  5722 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-21 14:30:12.940  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-21 14:30:12.940  5675  5722 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 14:30:12.940  5675  5722 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 14:30:12.940  5675  5722 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-21 14:30:12.940  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,11-21 14:30:12.941  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.941  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.942  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.942  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 14:30:12.942  5675  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-21 14:30:12.942  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 14:30:12.942  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 14:30:12.943  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 14:30:12.944  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 14:30:12.944  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 14:30:12.944  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 14:30:12.945  5675  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 14:30:12.945  5675  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 14:30:12.945  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 14:30:12.946  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 14:30:12.946  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 14:30:12.946  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-21 14:30:12.947  5675  5735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 14:30:12.950  5675  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 14:30:12.945  4611  4611 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[30587]" dev="sockfs" ino=30587 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 14:30:12.945  4611  4611 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[30587]" dev="sockfs" ino=30587 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 14:30:12.951  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 14:30:12.951  5675  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 14:30:12.951  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 14:30:12.954  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.954  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 14:30:12.955  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 14:30:12.955  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 14:30:12.955  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-21 14:30:12.956  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.956  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.956  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 14:30:12.956  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 14:30:12.957  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 14:30:12.957  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-21 14:30:12.957  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:12.957  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:12.957  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.957  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 14:30:12.957  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:12.957  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.957  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.957  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.958  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:12.960  4598  4611 D BtGatt.GattService: registerClient() - UUID=5ee3fe9c-f5ab-4903-91e7-7d1d81f99bdf
11-21 14:30:12.960  4598  4661 D BtGatt.GattService: onClientRegistered() - UUID=5ee3fe9c-f5ab-4903-91e7-7d1d81f99bdf, clientIf=5
11-21 14:30:12.961  5675  5685 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 14:30:12.962  4598  4663 D BtGatt.AdvertiseManager: message : 0
11-21 14:30:12.964  4598  4663 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 14:30:12.973  4598  4661 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 14:30:12.979  4598  4661 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 14:30:12.980  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.980  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.980  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 14:30:12.980  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.980  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.980  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.980  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.980  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.980  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 14:30:12.981  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 14:30:12.982  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.983  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.983  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:12.983  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:12.983  5675  5722 I io.jxcore.node.ConnectionHelper: start: OK
11-21 14:30:12.983  5675  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 14:30:12.983  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.983  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:12.983  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 14:30:12.983  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.984  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.984  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:12.984  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.984  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-21 14:30:12.984  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 14:30:12.984  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.984  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.984  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 14:30:12.984  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 14:30:12.986  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.986  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 14:30:12.987  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-21 14:30:12.987  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.987  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:12.987  5675  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 14:30:13.485  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-21 14:30:13.485  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 14:30:13.485  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 14:30:13.485  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 14:30:13.486  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 14:30:13.486  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-21 14:30:13.486  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 14:30:13.486  5675  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 14:30:13.486  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 14:30:13.486  5675  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 14:30:13.487  5675  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-21 14:30:13.487  5675  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7cb218 removed from the list
11-21 14:30:13.487  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 14:30:13.487  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 14:30:13.487  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-21 14:30:13.487  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 14:30:13.487  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:13.488  5675  5675 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 14:30:13.488  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:13.488  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:13.488  5675  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 14:30:13.488  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:13.488  5675  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 14:30:13.489  5675  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 14:30:13.491  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:13.492  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 14:30:13.494  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:13.494  5675  5722 D BluetoothLeScanner: could not find callback wrapper
11-21 14:30:13.494  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-21 14:30:13.494  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:13.495  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:13.495  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:13.495  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 14:30:13.495  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:13.497  4598  4663 D BtGatt.AdvertiseManager: message : 1
11-21 14:30:13.498  4598  4663 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 14:30:13.513  4598  4661 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 14:30:13.513  4598  4661 D BtGatt.GattService: Client app is not null!
11-21 14:30:13.514  4598  4614 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 14:30:13.515  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 14:30:13.516  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:13.516  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 14:30:13.516  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:13.516  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:13.516  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:13.516  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 14:30:13.516  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 14:30:13.518  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 14:30:13.518  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:13.521  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:13.521  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 14:30:13.521  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:13.521  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:13.522  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5eb5471 removed from the list
11-21 14:30:13.522  5675  5722 D io.jxcore.node.ConnectivityMonitor: stop
11-21 14:30:13.522  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 14:30:13.522  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 14:30:13.522  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 14:30:13.523  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:13.523  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:13.523  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 14:30:13.523  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 14:30:13.523  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:13.524  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 14:30:13.524  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 14:30:13.524  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 14:30:13.526  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 14:30:13.526  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:13.526  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-21 14:30:13.527  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:13.527  5675  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 14:30:13.771   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:30:14.028  5675  5675 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 14:30:14.773   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:30:15.774   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:30:15.915   930  2926 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 14:30:16.774   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:30:17.775   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 14:30:18.526   930  5334 D NetlinkSocketObserver: NeighborEvent{elapsedMs=195357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 14:30:18.527  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-21 14:30:18.529  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 14:30:18.529  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 14:30:18.530  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-21 14:30:18.536  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 14:30:18.537  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 14:30:18.538  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 14:30:18.538  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 14:30:18.538  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 14:30:18.538  5675  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 14:30:18.538  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 14:30:18.539  5675  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-21 14:30:18.539  4817  4817 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[30591]" dev="sockfs" ino=30591 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 14:30:18.542  4817  4817 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[30591]" dev="sockfs" ino=30591 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 14:30:18.541  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-21 14:30:18.542  5675  5736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 14:30:18.543  5675  5722 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-21 14:30:18.543  5675  5722 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-21 14:30:18.543  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 14:30:18.543  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 14:30:18.543  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 14:30:18.545  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-21 14:30:18.545  5675  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 14:30:18.555  5675  5722 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-21 14:30:18.555  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 14:30:18.555  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 14:30:18.556  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 14:30:18.556  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-21 14:30:18.556  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 14:30:18.556  5675  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 14:30:18.556  5675  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 14:30:18.556  5675  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 14:30:18.556  5675  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-21 14:30:18.558  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 14:30:18.558  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-21 14:30:18.558  5675  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 14:30:18.558  5675  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7cb218 not in the list
11-21 14:30:18.558  5675  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 14:30:18.558  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 14:30:18.558  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 14:30:18.558  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 14:30:18.559  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-21 14:30:18.559  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:18.562  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:18.562  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 14:30:18.562  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:18.562  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:18.562  5675  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5eb5471 not in the list
11-21 14:30:18.562  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 14:30:18.562  5675  5722 D io.jxcore.node.ConnectivityMonitor: stop
11-21 14:30:18.563  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-21 14:30:18.563  5675  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 14:30:18.566  5675  5722 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-21 14:30:18.567  5675  5722 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-21 14:30:18.567  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 14:30:18.568  5675  5722 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-21 14:30:18.568  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 14:30:18.568  5675  5722 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-21 14:30:18.568  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-21 14:30:18.569  5675  5722 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-21 14:30:18.570  5675  5722 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-21 14:30:18.571  5675  5722 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-21 14:30:18.571  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 14:30:18.571  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-21 14:30:18.572  5675  5722 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-21 14:30:18.572  5675  5722 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-21 14:30:18.572  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 14:30:18.572  5675  5722 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-21 14:30:18.572  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 14:30:18.572  5675  5722 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-21 14:30:18.572  5675  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-21 14:30:18.573  5675  5722 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-21 14:30:18.573  5675  5722 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-21 14:30:18.573  5675  5722 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-21 14:30:18.573  5675  5722 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-21 14:30:18.573  5675  5722 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-21 14:30:18.574  5675  5722 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-21 14:30:18.574  5675  5722 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-21 14:30:18.574  5675  5722 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-21 14:30:18.574  5675  5722 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-21 14:30:18.574  5675  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 14:30:18.574  5675  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fecffc7 added. We now have 3 listener(s)
11-21 14:30:18.576  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 14:30:18.576  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 14:30:18.576  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 14:30:18.577  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-21 14:30:18.577  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1b9f4 added. We now have 3 listener(s)
11-21 14:30:18.577  5675  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 14:30:18.578  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 14:30:18.580  5675  5722 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 14:30:18.581   930   940 D WifiService: setWifiEnabled: true pid=5675, uid=10077
11-21 14:30:18.581   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 14:30:18.583  5675  5722 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-21 14:30:18.586  5675  5722 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-21 14:30:18.587  5675  5722 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-21 14:30:18.589  5675  5722 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-21 14:30:18.590  5675  5722 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-21 14:30:18.595  5675  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 14:30:18.595  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 14:30:18.595  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 14:30:18.595  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 14:30:18.595  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 14:30:18.595  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 14:30:18.595  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 14:30:18.595  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 14:30:18.595  5675  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 14:30:18.595  4598  4657 D BluetoothAdapterState: Current state: ON, message: 23
11-21 14:30:18.595  4598  4657 D BluetoothAdapterProperties: Setting state to 13
,11-21 14:30:18.595  4598  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-21 14:30:18.596  4598  4657 D BluetoothAdapterProperties: onBluetoothDisable()
11-21 14:30:18.597  4598  4657 I BluetoothAdapterState: Entering PendingCommandState
11-21 14:30:18.597  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
11-21 14:30:18.597  5675  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 14:30:18.598  4598  4598 D BluetoothMapService: onReceive
11-21 14:30:18.599  4598  4598 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 14:30:18.599  4598  4598 D BluetoothMapService: STATE_TURNING_OFF
11-21 14:30:18.599  4598  4598 D BluetoothMapService: MAP Service closeService in
11-21 14:30:18.599  4598  4598 D BluetoothMapMasInstance0: MAP Service shutdown
11-21 14:30:18.599  4598  4598 D ObexServerSockets0: shutdown(block = true)
11-21 14:30:18.600  4598  4598 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-21 14:30:18.600  4598  4820 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-21 14:30:18.600  4598  4807 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-21 14:30:18.600  4598  4598 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-21 14:30:18.600  4598  4821 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-21 14:30:18.605  4598  4598 I BtOppRfcommListener: stopping Accept Thread
11-21 14:30:18.605  4598  5264 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-21 14:30:18.606  4598  5264 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-21 14:30:18.614   930   943 I ActivityManager: Start proc 5739:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-21 14:30:18.615  4598  4661 D BluetoothAdapterProperties: Scan Mode:20
,11-21 14:30:18.618  4598  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-21 14:30:18.620  4598  4598 D HeadsetService: Received stop request...Stopping profile...
11-21 14:30:18.621   930   930 D BluetoothHeadset: Proxy object disconnected
11-21 14:30:18.622  3736  3752 D BluetoothHeadset: Proxy object disconnected
11-21 14:30:18.623  3080  3945 D BluetoothHeadset: Proxy object disconnected
11-21 14:30:18.624   930   930 D BluetoothHeadset: Proxy object disconnected
,11-21 14:30:18.624  3080  3080 D HeadsetProfile: Bluetooth service disconnected
11-21 14:30:18.624   930   930 D BluetoothHeadset: Proxy object disconnected
11-21 14:30:18.624  4598  4598 D A2dpService: Received stop request...Stopping profile...
,11-21 14:30:18.624  4598  4811 D A2dpStateMachine: Exit Disconnected: -1
11-21 14:30:18.625   930   930 D BluetoothA2dp: Proxy object disconnected
11-21 14:30:18.626  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-21 14:30:18.626  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-21 14:30:18.626  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:18.626  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:18.627  3080  3080 D BluetoothA2dp: Proxy object disconnected
,11-21 14:30:18.629  4598  4598 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-21 14:30:18.629  4598  4598 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-21 14:30:18.630  4598  4661 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-21 14:30:18.630  4598  4805 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 14:30:18.630  4598  4805 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 14:30:18.630  4598  4805 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 14:30:18.630  4598  4661 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-21 14:30:18.631  4598  4598 D HidService: Received stop request...Stopping profile...
11-21 14:30:18.631  4598  4598 D HidService: Stopping Bluetooth HidService
11-21 14:30:18.632  4598  4598 D HealthService: Received stop request...Stopping profile...
11-21 14:30:18.632  3080  3080 D BluetoothInputDevice: Proxy object disconnected
11-21 14:30:18.632  3080  3080 D HidProfile: Bluetooth service disconnected
,11-21 14:30:18.633  4598  4598 D PanService: Received stop request...Stopping profile...
11-21 14:30:18.634  3080  3080 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-21 14:30:18.634  3080  3080 D PanProfile: Bluetooth service disconnected
11-21 14:30:18.634  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-21 14:30:18.634  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-21 14:30:18.634  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:18.634  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 14:30:18.637  4598  4598 D BluetoothMapService: Received stop request...Stopping profile...
11-21 14:30:18.637  4598  4805 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 14:30:18.636  4598  4661 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-21 14:30:18.637  4598  4598 D BluetoothMapService: stop()
11-21 14:30:18.637  4598  4805 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 14:30:18.637  4598  4805 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-21 14:30:18.637  4598  4805 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-21 14:30:18.637  4598  4805 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-21 14:30:18.637  4598  4805 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-21 14:30:18.638  4598  4598 D BluetoothMapAppObserver: deinitObservers()
11-21 14:30:18.638  4598  4598 D BluetoothMapAppObserver: removeReceiver()
11-21 14:30:18.639  3080  3080 D BluetoothMap: Proxy object disconnected
11-21 14:30:18.640  3080  3080 D MapProfile: Bluetooth service disconnected
11-21 14:30:18.640  4598  4598 D SapService: Received stop request...Stopping profile...
11-21 14:30:18.640  4598  4598 V SapService: stop()
11-21 14:30:18.642  4598  4598 V BluetoothAdapterState: isTurningOff()=true
,11-21 14:30:18.642  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-21 14:30:18.642  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:18.642  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:18.642  4598  4598 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-21 14:30:18.642  4598  4598 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-21 14:30:18.642  4598  4661 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-21 14:30:18.642  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-21 14:30:18.642  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-21 14:30:18.642  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:18.642  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:18.643  4598  4598 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-21 14:30:18.643  4598  4661 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-21 14:30:18.643  4598  4598 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-21 14:30:18.643  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-21 14:30:18.643  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-21 14:30:18.643  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:18.643  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:18.643  4598  4598 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-21 14:30:18.644  4598  4598 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-21 14:30:18.644  4598  4598 D BluetoothMapService: MAP Service closeService in
11-21 14:30:18.644  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-21 14:30:18.645  4598  4598 V BluetoothAdapterState: isTurningOn()=false
,11-21 14:30:18.645  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:18.645  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:18.645  4598  4598 D BluetoothMapService: cleanup()
11-21 14:30:18.645  4598  4598 D BluetoothMapService: MAP Service closeService in
11-21 14:30:18.645  4598  4598 V BluetoothAdapterState: isTurningOff()=true
11-21 14:30:18.645  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-21 14:30:18.646  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:18.646  4598  4598 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:18.646  4598  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-21 14:30:18.646  4598  4657 D BluetoothAdapterProperties: Setting state to 15
11-21 14:30:18.646  4598  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-21 14:30:18.646  4598  4657 I BluetoothAdapterState: Entering BleOnState
11-21 14:30:18.646   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-21 14:30:18.647  3080  3092 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-21 14:30:18.648  3080  3093 D BluetoothPbap: onBluetoothStateChange: up=false
,11-21 14:30:18.649  3736  3753 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 14:30:18.649  3080  3943 D BluetoothMap: onBluetoothStateChange: up=false
11-21 14:30:18.651   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-21 14:30:18.651   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 14:30:18.651  3080  3945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-21 14:30:18.652  3080  3092 D BluetoothPan: onBluetoothStateChange on: false
,11-21 14:30:18.652  3080  3093 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-21 14:30:18.653   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 14:30:18.653  4598  4657 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-21 14:30:18.653  4598  4657 D BluetoothAdapterProperties: Setting state to 16
11-21 14:30:18.654  4598  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-21 14:30:18.654  4598  4657 D BluetoothAdapterProperties: onBleDisable
11-21 14:30:18.654  4598  4657 I BluetoothAdapterState: Entering PendingCommandState
11-21 14:30:18.654  4598  4658 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-21 14:30:18.655  4598  4661 D BluetoothAdapterProperties: Scan Mode:20
,11-21 14:30:18.656  4598  4805 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-21 14:30:18.656  4598  4805 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 14:30:18.669  5739  5739 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-21 14:30:18.684  5739  5739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 14:30:18.691  3533  3533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 14:30:18.691   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@734d472:true
,11-21 14:30:18.703   930   941 I ActivityManager: Start proc 5751:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-21 14:30:18.715  5739  5739 D LocalBluetoothProfileManager: Adding local MAP profile
,11-21 14:30:18.717  5739  5739 D BluetoothMap: Create BluetoothMap proxy object
,11-21 14:30:18.725  5739  5739 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-21 14:30:18.738  5751  5751 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-21 14:30:18.741  5739  5739 D DockEventReceiver: finishStartingService: stopping service
,11-21 14:30:18.749   930  3809 I ActivityManager: Killing 5363:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-21 14:30:18.861  4598  4661 I bt_hci  : shut_down
,11-21 14:30:18.865  4598  4667 D bt_hwcfg: hw_epilog_process
,11-21 14:30:18.865  4598  4667 I bt_vendor: low_power_mode_cb
,11-21 14:30:18.868  4598  4667 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-21 14:30:18.868  4598  4667 I bt_vendor: epilog_cb
11-21 14:30:18.868  4598  4667 I bt_hci  : epilog_finished_callback
,11-21 14:30:18.870  4598  4661 I bt_hci_h4: hal_close
,11-21 14:30:18.871  4598  4661 I bt_userial_vendor: device fd = 54 close
,11-21 14:30:18.921  5751  5751 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 14:30:18.921  5751  5751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at java.io.File.exists(File.java:361)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 14:30:18.921  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-21 14:30:18.922  5751  5751 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 14:30:18.922  5751  5751 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 14:30:18.922  5751  5751 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.e.b(PG:170)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 14:30:18.922  5751  5751 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.k.d(PG:583)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.e.b(PG:170)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 14:30:18.922  5751  5751 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.io.File.exists(File.java:361)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 14:30:18.922  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 14:30:18.923  5751  5751 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at java.io.File.exists(File.java:361)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 14:30:18.923  5751  5751 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 14:30:18.923  5751  5751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 14:30:18.927  5739  5739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-21 14:30:18.932  3533  3533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 14:30:18.946  5739  5739 D DockEventReceiver: finishStartingService: stopping service
11-21 14:30:18.949   930  3615 I ActivityManager: Killing 5378:com.android.chrome/u0a39 (adj 15): empty #17
,11-21 14:30:18.977  4598  4658 D bt_stack_manager: event_shut_down_stack finished.
11-21 14:30:18.977  4598  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-21 14:30:18.993  4598  4657 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-21 14:30:18.993  4598  4598 D BtGatt.DebugUtils: handleDebugAction() action=null
11-21 14:30:18.993  4598  4598 D BtGatt.GattService: Received stop request...Stopping profile...
11-21 14:30:18.993  4598  4598 D BtGatt.GattService: stop()
11-21 14:30:18.994  4598  4598 D BtGatt.AdvertiseManager: advertise clients cleared
11-21 14:30:18.995  4598  4598 V BluetoothAdapterState: isTurningOff()=false
11-21 14:30:18.995  4598  4598 V BluetoothAdapterState: isTurningOn()=false
11-21 14:30:18.995  4598  4598 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:18.995  4598  4598 V BluetoothAdapterState: isBleTurningOff()=true
11-21 14:30:18.995  4598  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-21 14:30:18.995  4598  4657 D BluetoothAdapterProperties: Setting state to 10
11-21 14:30:18.995  4598  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-21 14:30:18.996  4598  4657 I BluetoothAdapterState: Entering OffState
11-21 14:30:18.996   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-21 14:30:19.004  4598  4598 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-21 14:30:19.004  4598  4598 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-21 14:30:19.004  4598  4598 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-21 14:30:19.005  4598  4658 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-21 14:30:19.010  4598  4598 I art     : System.exit called, status: 0
,11-21 14:30:19.010  4598  4598 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-21 14:30:19.063   930  3615 I ActivityManager: Process com.android.bluetooth (pid 4598) has died
,11-21 14:30:19.064  5675  5675 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 14:30:19.095  5675  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-21 14:30:19.095  5675  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 14:30:19.095  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 14:30:19.095  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
11-21 14:30:19.095  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 14:30:19.095  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-21 14:30:19.095  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 14:30:19.095  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 14:30:19.095  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 14:30:19.095  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 14:30:19.095  5675  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-21 14:30:19.096  5675  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 14:30:19.099  5675  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 14:30:19.108  5751  5783 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,11-21 14:30:19.110   930   947 I ActivityManager: Start proc 5784:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-21 14:30:19.172  5784  5784 D AdapterServiceConfig: Adding HeadsetService
11-21 14:30:19.173  5784  5784 D AdapterServiceConfig: Adding A2dpService
11-21 14:30:19.173  5784  5784 D AdapterServiceConfig: Adding HidService
11-21 14:30:19.173  5784  5784 D AdapterServiceConfig: Adding HealthService
11-21 14:30:19.173  5784  5784 D AdapterServiceConfig: Adding PanService
11-21 14:30:19.173  5784  5784 D AdapterServiceConfig: Adding GattService
11-21 14:30:19.173  5784  5784 D AdapterServiceConfig: Adding BluetoothMapService
11-21 14:30:19.173  5784  5784 D AdapterServiceConfig: Adding SapService
,11-21 14:30:19.181   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@67c0946:true
,11-21 14:30:19.181  5784  5784 D BluetoothAdapterState: make() - Creating AdapterState
,11-21 14:30:19.183  5784  5784 I bt_bluedroid: init
,11-21 14:30:19.183  5784  5797 I BluetoothAdapterState: Entering OffState
,11-21 14:30:19.185  5784  5798 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-21 14:30:19.185  5784  5798 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-21 14:30:19.185  5784  5798 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-21 14:30:19.185  5784  5798 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-21 14:30:19.186  5784  5784 I bt_bluedroid: get_profile_interface socket
,11-21 14:30:19.187  5784  5784 I bt_bluedroid: get_profile_interface sdp
,11-21 14:30:19.187  5784  5801 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-21 14:30:19.188  5784  5801 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-21 14:30:19.189  5784  5796 I bt_bluedroid: config_hci_snoop_log
,11-21 14:30:19.190   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-21 14:30:19.194  5784  5797 D BluetoothAdapterState: Current state: OFF, message: 0
,11-21 14:30:19.194  5784  5797 D BluetoothAdapterProperties: Setting state to 14
11-21 14:30:19.194  5784  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-21 14:30:19.195  5784  5797 D BluetoothBondStateMachine: make
,11-21 14:30:19.196  5751  5769 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-21 14:30:19.197  5784  5802 I BluetoothBondStateMachine: StableState(): Entering Off State
11-21 14:30:19.199  5784  5797 I BluetoothAdapterState: Entering PendingCommandState
11-21 14:30:19.199  5784  5784 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-21 14:30:19.201  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e803155
11-21 14:30:19.202  5784  5784 D BtGatt.DebugUtils: handleDebugAction() action=null
11-21 14:30:19.202  5784  5784 D BtGatt.GattService: Received start request. Starting profile...
11-21 14:30:19.202  5784  5784 D BtGatt.GattService: start()
11-21 14:30:19.202  5784  5784 I bt_bluedroid: get_profile_interface gatt
,11-21 14:30:19.203  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e803155
,11-21 14:30:19.203  5784  5784 D BtGatt.AdvertiseManager: advertise manager created
,11-21 14:30:19.207  5784  5784 V BluetoothAdapterState: isTurningOff()=false
,11-21 14:30:19.207  5784  5784 V BluetoothAdapterState: isTurningOn()=false
11-21 14:30:19.207  5784  5784 V BluetoothAdapterState: isBleTurningOn()=true
11-21 14:30:19.207  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:19.207  5784  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-21 14:30:19.208  5784  5797 I bt_bluedroid: bt_bluedroid
11-21 14:30:19.208  5784  5798 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-21 14:30:19.209  5784  5798 I bt_hci  : start_up
,11-21 14:30:19.213  5784  5798 I bt_vendor: alloc value 0xf3f2f871
,11-21 14:30:19.213  5784  5798 I bt_vendor: init
11-21 14:30:19.213  5784  5798 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-21 14:30:19.213  5784  5798 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-21 14:30:19.250   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8e3fff:true
,11-21 14:30:19.322  5784  5798 D bt_hci  : start_up starting async portion
,11-21 14:30:19.322  5784  5805 I bt_hci  : event_finish_startup
11-21 14:30:19.322  5784  5805 I bt_hci_h4: hal_open
11-21 14:30:19.322  5784  5805 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-21 14:30:19.323  5784  5805 I bt_userial_vendor: device fd = 54 open
11-21 14:30:19.319  5809  5809 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 14:30:19.335  5784  5805 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-21 14:30:19.337  5784  5805 D bt_hwcfg: Chipset BCM4358A3
11-21 14:30:19.337  5784  5805 D bt_hwcfg: Target name = [BCM4358A3]
,11-21 14:30:19.337  5784  5805 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-21 14:30:19.606  5784  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-21 14:30:19.737  5784  5805 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-21 14:30:19.737  5784  5805 D bt_hwcfg: Settlement delay -- 100 ms
,11-21 14:30:19.737  5784  5805 I bt_hwcfg: Setting fw settlement delay to 100 
,11-21 14:30:19.853  3533  5813 V NQFileLogger: [141] e.a: about to write to file
,11-21 14:30:19.856  3533  5813 V ProcessReports: [141] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,11-21 14:30:19.861  5784  5805 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-21 14:30:19.861  5784  5805 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-21 14:30:19.862  5784  5805 I bt_hwcfg: vendor lib fwcfg completed
,11-21 14:30:19.862  5784  5805 I bt_vendor: firmware callback
11-21 14:30:19.862  5784  5805 I bt_hci  : firmware_config_callback
,11-21 14:30:19.867  5784  5815 I bt_btu  : btu_task pending for preload complete event
,11-21 14:30:19.867  5784  5815 I bt_btu_task: Bluetooth chip preload is complete
11-21 14:30:19.867  5784  5815 I bt_btu  : btu_task received preload complete event
,11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_HCI
11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_AVDT
11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_AVRC
11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_A2D
11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_BNEP
11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_BTM
11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_GAP
11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_PAN
,11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_SDP
11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_GATT
11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_SMP
11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-21 14:30:19.870  5784  5815 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-21 14:30:19.938  5784  5815 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ead549
,11-21 14:30:19.938  5784  5815 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ead549 
,11-21 14:30:19.954  5784  5801 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-21 14:30:19.955  5784  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-21 14:30:19.955  5784  5801 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-21 14:30:19.956  5784  5801 D BluetoothAdapterProperties: Name is: Nexus 6P
11-21 14:30:19.957  5784  5801 D BluetoothAdapterProperties: Scan Mode:20
11-21 14:30:19.957  5784  5801 D BluetoothAdapterProperties: Discoverable Timeout:120
11-21 14:30:19.957  5784  5801 D bt_hci  : do_postload posting postload work item
11-21 14:30:19.957  5784  5805 I bt_hci  : event_postload
11-21 14:30:19.957  5784  5805 I bt_vendor: sco_config_cb
11-21 14:30:19.957  5784  5805 I bt_hci  : sco_config_callback postload finished.
,11-21 14:30:19.959  5784  5801 D bt_bte_conf: Device ID record 1 : primary
11-21 14:30:19.959  5784  5801 D bt_bte_conf:   vendorId            = 000f
,11-21 14:30:19.959  5784  5801 D bt_bte_conf:   vendorIdSource      = 0001
11-21 14:30:19.959  5784  5801 D bt_bte_conf:   product             = 1200
11-21 14:30:19.959  5784  5801 D bt_bte_conf:   version             = 1436
11-21 14:30:19.959  5784  5801 D bt_bte_conf:   clientExecutableURL = 
11-21 14:30:19.959  5784  5801 D bt_bte_conf:   serviceDescription  = 
11-21 14:30:19.959  5784  5801 D bt_bte_conf:   documentationURL    = 
11-21 14:30:19.959  5784  5801 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-21 14:30:19.959  5784  5798 D bt_stack_manager: event_start_up_stack finished
11-21 14:30:19.960  5784  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-21 14:30:19.960  5784  5797 D BluetoothAdapterProperties: Setting state to 15
11-21 14:30:19.960  5784  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-21 14:30:19.960  5784  5797 I BluetoothAdapterState: Entering BleOnState
,11-21 14:30:19.963  5784  5797 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-21 14:30:19.963  5784  5797 D BluetoothAdapterProperties: Setting state to 11
11-21 14:30:19.963  5784  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-21 14:30:19.966  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e803155
,11-21 14:30:19.966  5784  5805 I bt_vendor: low_power_mode_cb
11-21 14:30:19.967  5784  5784 D HeadsetService: Received start request. Starting profile...
11-21 14:30:19.969  5784  5784 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-21 14:30:19.970  5784  5784 D HeadsetStateMachine: make
,11-21 14:30:19.978  5784  5784 D HeadsetStateMachine: max_hf_connections = 1
,11-21 14:30:19.978  5784  5784 I bt_bluedroid: get_profile_interface handsfree
11-21 14:30:19.979  5784  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-21 14:30:19.979  5784  5801 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-21 14:30:19.981  5784  5797 I BluetoothAdapterState: Entering PendingCommandState
,11-21 14:30:19.983  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e803155
,11-21 14:30:19.983  5784  5784 D A2dpService: Received start request. Starting profile...
,11-21 14:30:19.984  5784  5784 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-21 14:30:19.984  5784  5784 I bt_bluedroid: get_profile_interface avrcp
,11-21 14:30:19.990  5784  5784 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-21 14:30:19.990  5784  5784 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-21 14:30:19.990  5784  5784 D A2dpStateMachine: make
,11-21 14:30:19.991  5784  5784 I bt_bluedroid: get_profile_interface a2dp
11-21 14:30:19.992  5784  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-21 14:30:19.993  5784  5822 D A2dpStateMachine: Enter Disconnected: -2
,11-21 14:30:19.994  5784  5784 I BluetoothHidServiceJni: classInitNative: succeeds
,11-21 14:30:19.995  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e803155
,11-21 14:30:19.996  5739  5739 D BluetoothInputDevice: Proxy object connected
11-21 14:30:19.996  5784  5784 D HidService: Received start request. Starting profile...
,11-21 14:30:19.996  5784  5784 I bt_bluedroid: get_profile_interface hidhost
11-21 14:30:19.996  5784  5784 D HidService: setHidService(): set to: null
11-21 14:30:19.996  5784  5801 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e8e56d
11-21 14:30:19.997  5739  5739 D HidProfile: Bluetooth service connected
11-21 14:30:19.997  5784  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-21 14:30:19.997  5784  5784 I BluetoothHealthServiceJni: classInitNative: succeeds
11-21 14:30:19.998  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e803155
11-21 14:30:19.998  5784  5784 D HealthService: Received start request. Starting profile...
,11-21 14:30:19.999  5784  5784 I bt_bluedroid: get_profile_interface health
,11-21 14:30:20.000  5784  5784 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-21 14:30:20.001  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e803155
11-21 14:30:20.002  5739  5739 D BluetoothPan: BluetoothPAN Proxy object connected
,11-21 14:30:20.002  5784  5784 D PanService: Received start request. Starting profile...
11-21 14:30:20.002  5784  5784 D BluetoothPanServiceJni: initializeNative(L110): pan
11-21 14:30:20.002  5784  5784 I bt_bluedroid: get_profile_interface pan
11-21 14:30:20.002  5784  5801 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-21 14:30:20.003  5739  5739 D PanProfile: Bluetooth service connected
,11-21 14:30:20.006  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e803155
11-21 14:30:20.007  3533  3533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 14:30:20.009  5784  5784 D BluetoothMapService: Received start request. Starting profile...
11-21 14:30:20.009  5784  5784 D BluetoothMapService: start()
11-21 14:30:20.012  5739  5739 D BluetoothMap: Proxy object connected
11-21 14:30:20.012  5784  5784 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-21 14:30:20.012  5739  5739 D MapProfile: Bluetooth service connected
11-21 14:30:20.012  5739  5739 D BluetoothMap: getConnectedDevices()
11-21 14:30:20.013  5784  5784 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-21 14:30:20.013  5784  5784 D BluetoothMapAppObserver: createReceiver()
11-21 14:30:20.013  5739  5739 D BluetoothMap: Bluetooth is Not enabled
,11-21 14:30:20.014  5784  5784 D BluetoothMapAppObserver: initObservers()
,11-21 14:30:20.014  5784  5784 D BluetoothMapAppObserver: getEnabledAccountItems()
11-21 14:30:20.019  5784  5784 V SapService: SapBinder()
11-21 14:30:20.019  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e803155
11-21 14:30:20.020  5784  5784 D SapService: Received start request. Starting profile...
11-21 14:30:20.020  5784  5784 V SapService: start()
11-21 14:30:20.021  5784  5784 V BluetoothAdapterState: isTurningOff()=false
11-21 14:30:20.021  5784  5784 V BluetoothAdapterState: isTurningOn()=true
11-21 14:30:20.021  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:20.021  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 14:30:20.021  5784  5784 V BluetoothAdapterState: isTurningOff()=false
11-21 14:30:20.021  5784  5784 V BluetoothAdapterState: isTurningOn()=true
11-21 14:30:20.021  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:20.021  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:20.021  5784  5819 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-21 14:30:20.021  5784  5784 V BluetoothAdapterState: isTurningOff()=false
11-21 14:30:20.021  5784  5784 V BluetoothAdapterState: isTurningOn()=true
11-21 14:30:20.021  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:20.022  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:20.022  5784  5784 V BluetoothAdapterState: isTurningOff()=false
11-21 14:30:20.022  5784  5784 V BluetoothAdapterState: isTurningOn()=true
11-21 14:30:20.022  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:20.022  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:20.022  5784  5784 V BluetoothAdapterState: isTurningOff()=false
11-21 14:30:20.022  5784  5784 V BluetoothAdapterState: isTurningOn()=true
11-21 14:30:20.022  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:20.022  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:20.022  5784  5784 V BluetoothAdapterState: isTurningOff()=false
11-21 14:30:20.022  5784  5784 V BluetoothAdapterState: isTurningOn()=true
11-21 14:30:20.022  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:20.023  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:20.023  5784  5784 V BluetoothAdapterState: isTurningOff()=false
11-21 14:30:20.023  5784  5784 V BluetoothAdapterState: isTurningOn()=true
11-21 14:30:20.023  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
11-21 14:30:20.023  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
11-21 14:30:20.023  5784  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-21 14:30:20.023  5784  5797 D BluetoothAdapterProperties: ScanMode =  20
11-21 14:30:20.023  5784  5797 D BluetoothAdapterProperties: State =  11
11-21 14:30:20.024  5784  5797 D BluetoothAdapterProperties: Setting state to 12
11-21 14:30:20.024  5784  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-21 14:30:20.024   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-21 14:30:20.024  5784  5797 I BluetoothAdapterState: Entering OnState
11-21 14:30:20.026  3080  3945 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-21 14:30:20.028  3080  3080 D BluetoothInputDevice: Proxy object connected
11-21 14:30:20.028  3080  3080 D HidProfile: Bluetooth service connected
11-21 14:30:20.028   930   930 D BluetoothA2dp: Proxy object connected
11-21 14:30:20.029  5784  5801 D BluetoothAdapterProperties: Scan Mode:21
11-21 14:30:20.029  5784  5801 D BluetoothAdapterProperties: Discoverable Timeout:120
11-21 14:30:20.031  3080  3093 D BluetoothPbap: onBluetoothStateChange: up=true
11-21 14:30:20.033  3736  3752 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 14:30:20.033  3080  3943 D BluetoothMap: onBluetoothStateChange: up=true
11-21 14:30:20.035  3080  3080 D BluetoothMap: Proxy object connected
11-21 14:30:20.035  3080  3080 D MapProfile: Bluetooth service connected
11-21 14:30:20.035  3080  3080 D BluetoothMap: getConnectedDevices()
11-21 14:30:20.035  5739  5749 D BluetoothPan: onBluetoothStateChange on: true
11-21 14:30:20.037   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 14:30:20.037   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 14:30:20.037  3080  3945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 14:30:20.038  3080  3093 D BluetoothPan: onBluetoothStateChange on: true
11-21 14:30:20.038  5784  5784 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-21 14:30:20.038  5784  5784 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-21 14:30:20.040  3080  3080 D BluetoothPan: BluetoothPAN Proxy object connected
11-21 14:30:20.040  3080  3080 D PanProfile: Bluetooth service connected
11-21 14:30:20.040  5739  5750 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-21 14:30:20.040  5784  5784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 14:30:20.040  3080  3943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-21 14:30:20.042  5784  5784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 14:30:20.042  3080  3080 D BluetoothA2dp: Proxy object connected
11-21 14:30:20.042  5739  5749 D BluetoothPbap: onBluetoothStateChange: up=true
11-21 14:30:20.043  5784  5784 D ObexServerSockets: Succeed to create listening sockets 
11-21 14:30:20.043  5784  5784 D ObexServerSockets0: startAccept()
11-21 14:30:20.043  5784  5784 D ObexServerSockets0: prepareForNewConnect()
11-21 14:30:20.044   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 14:30:20.044  5739  5750 D BluetoothMap: onBluetoothStateChange: up=true
11-21 14:30:20.045   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-21 14:30:20.045  5784  5784 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-21 14:30:20.045  5784  5784 D BluetoothSdpJni: SDP Create record success - handle: 0
11-21 14:30:20.046  5784  5784 D BluetoothMapService: onReceive
11-21 14:30:20.046  5784  5784 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 14:30:20.046  5784  5784 D BluetoothMapService: STATE_ON
11-21 14:30:20.048  5784  5828 D ObexServerSockets0: Accepting socket connection...
11-21 14:30:20.048  5784  5829 D ObexServerSockets0: Accepting socket connection...
11-21 14:30:20.049  5739  5739 D LocalBluetoothProfileManager: Adding local A2DP profile
11-21 14:30:20.049  5784  5832 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 14:30:20.050  5784  5832 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-21 14:30:20.051  5784  5832 D BluetoothSdpJni: SDP Create record success - handle: 1
11-21 14:30:20.054  5739  5739 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-21 14:30:20.060  5739  5739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 14:30:20.064  5739  5739 D BluetoothA2dp: Proxy object connected
,11-21 14:30:20.067  5784  5784 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-21 14:30:20.067  5784  5784 D ObexServerSockets0: prepareForNewConnect()
11-21 14:30:20.068  3533  3533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 14:30:20.074  5739  5739 D DockEventReceiver: finishStartingService: stopping service
11-21 14:30:20.075  3080  3080 D BluetoothPbap: Proxy object connected
11-21 14:30:20.075  3080  3080 D PbapServerProfile: Bluetooth service connected
11-21 14:30:20.075  5739  5739 D BluetoothPbap: Proxy object connected
11-21 14:30:20.076  5739  5739 D PbapServerProfile: Bluetooth service connected
,11-21 14:30:20.083  5784  5836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 14:30:20.099  5784  5840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 14:30:20.100  5784  5840 I BtOppRfcommListener: Accept thread started.
,11-21 14:30:20.109  5675  5737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-21 14:30:20.109  5675  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 14:30:20.109  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 14:30:20.109  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 14:30:20.109  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 14:30:20.109  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 14:30:20.109  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 14:30:20.109  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 14:30:20.109  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 14:30:20.109  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 14:30:20.113  5675  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 14:30:20.115  5675  5722 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-21 14:30:20.116   930  3525 D WifiService: setWifiEnabled: false pid=5675, uid=10077
11-21 14:30:20.116   930  3525 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 14:30:20.118  5675  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 14:30:20.118   930  2919 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-21 14:30:20.118   930  2919 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-21 14:30:20.119   930  2919 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-21 14:30:20.119   930  2919 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 14:30:20.125   930  5335 D DhcpClient: Clearing IP address
,11-21 14:30:20.126   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-21 14:30:20.128   508   924 D CommandListener: Setting iface cfg
,11-21 14:30:20.130  3533  5393 V NativeCrypto: Read error: ssl=0x7f85db7000: I/O error during system call, Connection timed out
,11-21 14:30:20.131   930  5336 D DhcpClient: Receive thread stopped
,11-21 14:30:20.132   930  2926 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-21 14:30:20.132  3533  5393 V NativeCrypto: SSL shutdown failed: ssl=0x7f85db7000: I/O error during system call, Broken pipe
11-21 14:30:20.132   930  2926 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-21 14:30:20.135   930   930 D RttService: SCAN_AVAILABLE : 1
,11-21 14:30:20.136   930  3033 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-21 14:30:20.136   930   930 D BluetoothHeadset: Proxy object connected
11-21 14:30:20.137  3736  3752 D BluetoothHeadset: Proxy object connected
11-21 14:30:20.137   536   536 E Parcel  : Reading a NULL string not supported here.
,11-21 14:30:20.137   930   947 D BluetoothHeadset: Proxy object connected
,11-21 14:30:20.137   930   947 D BluetoothHeadset: Proxy object connected
,11-21 14:30:20.138  3080  3945 D BluetoothHeadset: Proxy object connected
11-21 14:30:20.138   930   930 D BluetoothHeadset: Proxy object connected
11-21 14:30:20.138   930   930 D BluetoothHeadset: Proxy object connected
11-21 14:30:20.139  3080  3092 D BluetoothHeadset: Proxy object connected
11-21 14:30:20.140   930  2926 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-21 14:30:20.141  3707  3818 W QCNEJ   : |CORE| network lost: 100
11-21 14:30:20.142  3707  3818 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-21 14:30:20.144   930   947 D BluetoothHeadset: Proxy object connected
,11-21 14:30:20.153  3080  3080 D HeadsetProfile: Bluetooth service connected
,11-21 14:30:20.156  3080  3080 D HeadsetProfile: Bluetooth service connected
,11-21 14:30:20.157  5739  5749 D BluetoothHeadset: Proxy object connected
,11-21 14:30:20.159  5739  5739 D HeadsetProfile: Bluetooth service connected
,11-21 14:30:20.170   930  2919 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-21 14:30:20.175   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 14:30:20.178   930  2919 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-21 14:30:20.194   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 14:30:20.194   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-21 14:30:20.195   508   924 D TetherController: Setting IP forward enable = 0
,11-21 14:30:20.196   930  2926 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-21 14:30:20.196   930  2926 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-21 14:30:20.199   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-21 14:30:20.201   930  2919 D DhcpClient: doQuit
,11-21 14:30:20.201   930  2919 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-21 14:30:20.202  3389  3389 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-21 14:30:20.202   930  5335 D DhcpClient: onQuitting
,11-21 14:30:20.203  5219  5219 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@cab5e1e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-21 14:30:20.208  3900  3900 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-21 14:30:20.212  3915  3915 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-21 14:30:20.213  5004  5028 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-21 14:30:20.213  5004  5028 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 14:30:20.213  5004  5028 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-21 14:30:20.213  5004  5028 E SarControlService: no key has been found,reset the power
11-21 14:30:20.213  5004  5041 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-21 14:30:20.213  5004  5041 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 14:30:20.213  5004  5041 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 14:30:20.214  5029  5029 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 14:30:20.214  5029  5029 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-21 14:30:20.215  3915  3915 D SystemUpdateService: onCreate
11-21 14:30:20.215  5004  5041 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-21 14:30:20.217  5004  5041 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-21 14:30:20.217  5004  5041 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 14:30:20.217  5029  5029 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 14:30:20.217  5029  5029 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-21 14:30:20.218  5029  5043 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2b4fa74 HexData = [00000000ea03000000000000ffffffff]
11-21 14:30:20.218  5029  5043 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 14:30:20.218  5029  5043 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-21 14:30:20.219  3915  3915 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-21 14:30:20.219  5029  5029 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 14:30:20.219  5004  5014 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-21 14:30:20.221  3915  5856 I SystemUpdateService: active receiver: enabled
,11-21 14:30:20.224  3915  5856 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-21 14:30:20.225  3389  3389 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-21 14:30:20.225  5029  5043 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2b4fa74 HexData = [00000000eb03000000000000ffffffff]
,11-21 14:30:20.226  5029  5043 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 14:30:20.226  5029  5043 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-21 14:30:20.226  5029  5029 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 14:30:20.226  5004  5015 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-21 14:30:20.227  3915  5856 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-21 14:30:20.228  3915  5856 I SystemUpdateService: now status is 0 (complete)
11-21 14:30:20.228  3915  5856 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-21 14:30:20.228  3915  5856 I SystemUpdateService: file has been verified
11-21 14:30:20.228  3915  5856 I SystemUpdateService: OTA package size = 21989297
11-21 14:30:20.230  3389  3389 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-21 14:30:20.231  3915  5856 I SystemUpdateService: showing system update notification
11-21 14:30:20.234  3915  3915 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-21 14:30:20.236  3915  5360 I iu.UploadsManager: num queued entries: 0
11-21 14:30:20.237  3915  5360 I iu.UploadsManager: num updated entries: 0
11-21 14:30:20.237  3915  5360 I iu.SyncManager: NEXT; no task
11-21 14:30:20.239   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-21 14:30:20.241  3915  3915 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-21 14:30:20.243  3915  3915 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-21 14:30:20.243  3915  3915 D SystemUpdateService: onDestroy
,11-21 14:30:20.254   930  3525 I ActivityManager: Start proc 5863:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-21 14:30:20.264   508   924 E Netd    : netlink response contains error (No such file or directory)
,11-21 14:30:20.267   930  2926 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-21 14:30:20.267  3389  3389 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-21 14:30:20.268   508   924 D TetherController: Setting IP forward enable = 0
,11-21 14:30:20.285  3389  3389 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-21 14:30:20.290  5863  5863 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-21 14:30:20.293  5863  5863 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-21 14:30:20.299  5863  5863 D SprintDMHelper: simOperator: 
,11-21 14:30:20.299  5863  5863 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 14:30:20.311   930  3525 I ActivityManager: Start proc 5877:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-21 14:30:20.383  4966  5891 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-21 14:30:20.397   930  3615 I ActivityManager: Start proc 5892:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-21 14:30:20.399   930  3615 I ActivityManager: Killing 5219:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-21 14:30:20.428  4045  4169 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 14:30:20.426   930  2919 D wifi    : In wifi stop Hal
11-21 14:30:20.428   930  2919 D wifi    : halHandle = 0x7f83f03400, mVM = 0x7fa058d140, mCls = 0x100a02
,11-21 14:30:20.428   930  3388 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-21 14:30:20.428   930  3388 D WifiHAL : Got a signal to exit!!!
11-21 14:30:20.428   930  3388 I WifiHAL : Exit wifi_event_loop
11-21 14:30:20.429   930  2919 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-21 14:30:20.429   930  2919 E WifiHAL : Event processing terminated
11-21 14:30:20.429   930  2919 D wifi    : In wifi cleaned up handler
11-21 14:30:20.429   930  2919 I WifiHAL : Internal cleanup completed
,11-21 14:30:20.430  4966  4966 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 14:30:20.446  5892  5892 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-21 14:30:20.452   930  3388 D wifi    : set interface wlan0 flags (DOWN)
,11-21 14:30:20.452   930  2919 D WifiNative-HAL: HAL event thread stopped successfully
,11-21 14:30:20.455   930  5438 I ActivityManager: Killing 3829:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-21 14:30:20.624  5675  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 14:30:20.624  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 14:30:20.624  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 14:30:20.624  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-21 14:30:20.624  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 14:30:20.624  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 14:30:20.624  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 14:30:20.624  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 14:30:20.624  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 14:30:20.629  5675  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 14:30:20.632   930  3104 D WifiService: setWifiEnabled: true pid=5675, uid=10077
,11-21 14:30:20.633   930  3104 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 14:30:20.636  5675  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 14:30:20.655   508   924 D SoftapController: Softap fwReload - Ok
,11-21 14:30:20.657   930   947 D Tethering: InitialState.processMessage what=4
,11-21 14:30:20.659   508   924 D CommandListener: Setting iface cfg
,11-21 14:30:20.660   508   924 D CommandListener: Trying to bring down wlan0
11-21 14:30:20.661   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-21 14:30:20.664   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-21 14:30:20.667   930  2919 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-21 14:30:21.136   930  3525 D WifiService: setWifiEnabled: true pid=5675, uid=10077
,11-21 14:30:21.136   930  3525 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 14:30:21.267   930  2919 D wifi    : set interface wlan0 flags (UP)
,11-21 14:30:21.267   930  2919 I WifiHAL : Initializing wifi
11-21 14:30:21.267   930  2919 I WifiHAL : Creating socket
,11-21 14:30:21.273   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-21 14:30:21.275   930  2919 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-21 14:30:21.276   930  2919 D wifi    : Did set static halHandle = 0x7f83f03400
,11-21 14:30:21.276   930  2919 D wifi    : halHandle = 0x7f83f03400, mVM = 0x7fa058d140, mCls = 0x189a
,11-21 14:30:21.276   930  2919 D wifi    : array field set
,11-21 14:30:21.276   930  2919 I WifiNative-HAL: interface[0] = wlan0
,11-21 14:30:21.284   930  5908 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547674403840
,11-21 14:30:21.284   930  5908 D wifi    : waitForHalEvents called, vm = 0x7fa058d140, obj = 0x189a, env = 0x7f86ccb240
,11-21 14:30:21.368  5909  5909 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-21 14:30:21.381   930  2919 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-21 14:30:21.446  5909  5909 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-21 14:30:21.477  5909  5909 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-21 14:30:21.477  5909  5909 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-21 14:30:21.491   930  2919 D WifiConfigStore: Loading config and enabling all networks 
,11-21 14:30:21.510   930  2919 D WifiConfigStore: loaded 0 passpoint configs
,11-21 14:30:21.511   930  2919 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-21 14:30:21.512   930  2919 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-21 14:30:21.512   930  2919 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-21 14:30:21.513   930  2919 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-21 14:30:21.513   930  2919 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-21 14:30:21.513   930  2919 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-21 14:30:21.514   930  2919 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-21 14:30:21.514   930  2919 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-21 14:30:21.514   930  2919 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-21 14:30:21.514   930  2919 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-21 14:30:21.514   930  2919 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-21 14:30:21.514   930  2919 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-21 14:30:21.516   930  2919 D WifiNative-HAL: Setting external_sim to 1
11-21 14:30:21.517   930  2919 D wifi    : setting dfs flag to true, 0x7f89bd1640
11-21 14:30:21.517   930  2919 D WifiStateMachine: Setting OUI to DA-A1-19
11-21 14:30:21.517   930  2919 D wifi    : setting scan oui 0x7f89bd1640
11-21 14:30:21.517   930  2919 D WifiHAL : Sending mac address OUI
,11-21 14:30:21.517  4966  4966 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-21 14:30:21.520   930  2919 E native  : do suspend false
,11-21 14:30:21.526   930  2919 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-21 14:30:21.526   930   930 D RttService: SCAN_AVAILABLE : 3
11-21 14:30:21.527   930  3033 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-21 14:30:21.530   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-21 14:30:21.531   508   924 D CommandListener: Setting iface cfg
,11-21 14:30:21.536   930  2897 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
11-21 14:30:21.537   930  2897 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-21 14:30:21.541   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=198372 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=10 mControllerEnergyUsed=38 }
,11-21 14:30:21.542   930  2897 D WifiNative-HAL: p2pGetDeviceAddress
,11-21 14:30:21.543   930  2897 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-21 14:30:21.644  5675  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 14:30:21.644  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 14:30:21.644  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 14:30:21.644  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 14:30:21.644  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 14:30:21.644  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 14:30:21.644  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 14:30:21.644  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 14:30:21.644  5675  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 14:30:21.650  5675  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 14:30:21.653  5675  5722 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 14:30:21.653   930  5438 D WifiService: setWifiEnabled: true pid=5675, uid=10077
,11-21 14:30:21.653   930  5438 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 14:30:21.654  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-21 14:30:21.654  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 14:30:21.654  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-21 14:30:21.654  5675  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fecffc7 removed from the list
,11-21 14:30:21.655  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-21 14:30:21.655  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1b9f4 removed from the list
11-21 14:30:21.655  5675  5722 D io.jxcore.node.ConnectivityMonitor: stop
,11-21 14:30:21.657  5675  5722 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-21 14:30:21.660  5675  5722 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-21 14:30:21.662  5675  5722 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-21 14:30:21.663  5675  5722 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-21 14:30:21.666  5675  5722 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-21 14:30:21.668  5675  5722 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-21 14:30:21.669  5675  5722 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-21 14:30:21.669  5675  5722 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-21 14:30:21.671  5675  5722 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-21 14:30:21.674  5675  5722 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-21 14:30:21.674  5675  5722 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@26274f8 Bundle[{}]
,11-21 14:30:21.675  5675  5722 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,11-21 14:30:21.676  5675  5722 I io.jxcore.node.LifeCycleMonitor: start: OK
11-21 14:30:21.676  5675  5722 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-21 14:30:21.677  5675  5722 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-21 14:30:21.678  5675  5722 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-21 14:30:21.679  5675  5722 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-21 14:30:21.679  5675  5722 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-21 14:30:21.680  5675  5722 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-21 14:30:21.680  5675  5722 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-21 14:30:21.682  5675  5722 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-21 14:30:21.683  5675  5722 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-21 14:30:21.685  5675  5722 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-21 14:30:21.687  5675  5722 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-21 14:30:21.689  5675  5722 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-21 14:30:21.690  5675  5722 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-21 14:30:21.691  5675  5722 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-21 14:30:21.691  5675  5722 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-21 14:30:21.694  5675  5722 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-21 14:30:21.695  5675  5722 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-21 14:30:21.696  5675  5722 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-21 14:30:21.699  5675  5722 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-21 14:30:21.700  5675  5722 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-21 14:30:21.701  5675  5722 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-21 14:30:21.701  5675  5722 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-21 14:30:21.702  5675  5722 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-21 14:30:21.702  5675  5722 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-21 14:30:21.702  5675  5722 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 143)
,11-21 14:30:21.703  5675  5722 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-21 14:30:21.704  5675  5722 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-21 14:30:21.706  5675  5722 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-21 14:30:21.706  5675  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 14:30:21.706  5675  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9962392 added. We now have 3 listener(s)
11-21 14:30:21.708  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 14:30:21.708  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 14:30:21.708  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 14:30:21.708  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 14:30:21.708  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8afd163 added. We now have 3 listener(s)
,11-21 14:30:21.709  5675  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 14:30:21.709  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 14:30:21.715  5675  5722 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-21 14:30:21.715  5675  5722 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-21 14:30:21.716  5675  5722 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-21 14:30:21.716  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-21 14:30:21.716  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.716  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.716  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.716  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 14:30:21.716  5675  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-21 14:30:21.716  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 14:30:21.716  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 14:30:21.716  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 14:30:21.721  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 14:30:21.722  5675  5912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 14:30:21.721  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 14:30:21.722  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 14:30:21.722  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-21 14:30:21.722  5675  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 14:30:21.722  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-21 14:30:21.722  5675  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 14:30:21.722  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 14:30:21.723  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 14:30:21.723  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 14:30:21.726  5675  5912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 14:30:21.722  5827  5827 W Binder_3: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[32378]" dev="sockfs" ino=32378 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 14:30:21.726  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 14:30:21.726  5675  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 14:30:21.726  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 14:30:21.722  5827  5827 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[32378]" dev="sockfs" ino=32378 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 14:30:21.729  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:21.729  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 14:30:21.730  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 14:30:21.730  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 14:30:21.730  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-21 14:30:21.732  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:21.732  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.733  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 14:30:21.733  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 14:30:21.733  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 14:30:21.733  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-21 14:30:21.733  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:21.733  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:21.733  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.733  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 14:30:21.733  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:21.733  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:21.733  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.733  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.734  5675  5722 D BluetoothAdapter: STATE_ON
,11-21 14:30:21.738  5784  5831 D BtGatt.GattService: registerClient() - UUID=1f0732b5-c573-4d3e-af58-6d21b97d7428
,11-21 14:30:21.739  5784  5801 D BtGatt.GattService: onClientRegistered() - UUID=1f0732b5-c573-4d3e-af58-6d21b97d7428, clientIf=5
,11-21 14:30:21.740  5675  5686 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 14:30:21.741  5784  5803 D BtGatt.AdvertiseManager: message : 0
,11-21 14:30:21.744  5784  5803 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 14:30:21.747  5784  5801 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 14:30:21.749  5784  5801 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 14:30:21.749  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.750  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:21.750  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 14:30:21.750  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.750  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.750  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.750  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.750  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.750  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 14:30:21.751  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-21 14:30:21.751  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:21.753  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.753  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.753  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:21.753  5675  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 14:30:21.753  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-21 14:30:21.753  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:21.753  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 14:30:21.753  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-21 14:30:21.754  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:21.754  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:21.754  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:21.754  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-21 14:30:21.754  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 14:30:21.754  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:21.754  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 14:30:21.754  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 14:30:21.754  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 14:30:21.757  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-21 14:30:21.757  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 14:30:21.757  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:21.757  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:21.757  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:21.757  5675  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 14:30:22.258  5675  5675 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-21 14:30:22.259  5675  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 14:30:22.259  5675  5675 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 14:30:24.611  5909  5909 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 14:30:24.616  5909  5909 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 14:30:24.621  5909  5909 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 14:30:24.626  5909  5909 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 14:30:24.660   930  2919 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-21 14:30:24.660   930  2919 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-21 14:30:24.660   930  2919 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 14:30:24.671   930  2919 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-21 14:30:24.702   930  2919 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-21 14:30:24.708  5909  5909 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-21 14:30:24.845   930  3104 I ActivityManager: Killing 5450:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-21 14:30:25.128  5909  5909 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-21 14:30:25.160  5909  5909 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-21 14:30:25.161  5909  5909 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-21 14:30:25.176   930  2919 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-21 14:30:25.177   930  2919 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-21 14:30:25.177   930  2926 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-21 14:30:25.195   930  2919 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 14:30:25.208   508   924 D CommandListener: Setting iface cfg
,11-21 14:30:25.214   930  2919 D WifiStateMachine: Start Dhcp Watchdog 2
,11-21 14:30:25.223   930  2926 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 14:30:25.223   930  2919 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-21 14:30:25.223   930  2926 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-21 14:30:25.227   930  5917 D DhcpClient: Receive thread started
,11-21 14:30:25.256  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 14:30:25.256  5675  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-21 14:30:25.256  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 14:30:25.256  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 14:30:25.256  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 14:30:25.257  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 14:30:25.257  5675  5912 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 14:30:25.257  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 14:30:25.257  5675  5912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 14:30:25.257  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 14:30:25.257  5675  5912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 14:30:25.257  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 14:30:25.257  5675  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 14:30:25.257  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 14:30:25.257  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 14:30:25.257  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 14:30:25.257  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.257  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.257  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.258  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.259  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:25.259  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 14:30:25.259  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:25.260  5675  5722 D BluetoothLeScanner: could not find callback wrapper
11-21 14:30:25.260  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 14:30:25.260  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.260  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.260  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.260  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 14:30:25.260  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.261  5784  5803 D BtGatt.AdvertiseManager: message : 1
11-21 14:30:25.262  5784  5803 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 14:30:25.270  5784  5801 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 14:30:25.270  5784  5801 D BtGatt.GattService: Client app is not null!
,11-21 14:30:25.271  5784  5796 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 14:30:25.273  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 14:30:25.273  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.274  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 14:30:25.274  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.274  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.274  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.274  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 14:30:25.274  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 14:30:25.275  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-21 14:30:25.277  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:25.279  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.279  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 14:30:25.280  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.280  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:25.280  5675  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 14:30:25.280  5675  5675 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 14:30:25.281  5675  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 14:30:25.281  5675  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 14:30:25.281  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-21 14:30:25.281  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 14:30:25.281  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:25.282  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.282  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 14:30:25.282  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 14:30:25.282  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-21 14:30:25.282  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-21 14:30:25.282  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 14:30:25.282  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.285  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.285  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.285  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.285  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.285  5675  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 14:30:25.286  5675  5722 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,11-21 14:30:25.287  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-21 14:30:25.289  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-21 14:30:25.289  5675  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-21 14:30:25.289  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-21 14:30:25.289  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 14:30:25.289  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 14:30:25.295  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-21 14:30:25.298  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-21 14:30:25.298  5675  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 14:30:25.298  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 14:30:25.301  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:25.302  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 14:30:25.302  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 14:30:25.302  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 14:30:25.302  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-21 14:30:25.304  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-21 14:30:25.307   930  2919 E native  : do suspend false
,11-21 14:30:25.309  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-21 14:30:25.309  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.309  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-21 14:30:25.309  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-21 14:30:25.309  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-21 14:30:25.310  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-21 14:30:25.310  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:25.311  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:25.314  5784  5827 D BtGatt.GattService: registerClient() - UUID=465719d8-0d20-446d-9a8a-4c371b8a2af2
11-21 14:30:25.315  5784  5801 D BtGatt.GattService: onClientRegistered() - UUID=465719d8-0d20-446d-9a8a-4c371b8a2af2, clientIf=5
,11-21 14:30:25.315  5675  5715 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-21 14:30:25.316  5784  5831 D BtGatt.GattService: start scan with filters
11-21 14:30:25.319   930  5916 D DhcpClient: Broadcasting DHCPDISCOVER
11-21 14:30:25.320  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-21 14:30:25.320  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:25.320  5784  5804 D BtGatt.ScanManager: handling starting scan
11-21 14:30:25.320  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-21 14:30:25.321  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.321  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 14:30:25.321  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:25.321  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.321  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 14:30:25.321  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-21 14:30:25.321  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.321  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.322  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-21 14:30:25.322  5784  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e803155
11-21 14:30:25.322  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 14:30:25.322  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.324  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.325  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-21 14:30:25.325  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:25.325  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:25.325  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.327  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.327  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.327  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.327  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:25.328  5675  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-21 14:30:25.328  5784  5801 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-21 14:30:25.328  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:25.328  5784  5804 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-21 14:30:25.330   930  5917 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172640, domain null
,11-21 14:30:25.330   930  5916 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172640 seconds
11-21 14:30:25.332   930  5916 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
11-21 14:30:25.335  5784  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-21 14:30:25.335  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:25.336  5784  5804 D BtGatt.ScanManager: Starting BLE batch scan
11-21 14:30:25.336  5784  5804 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-21 14:30:25.343   930  5917 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-21 14:30:25.343   930  5916 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-21 14:30:25.344   508   924 D CommandListener: Setting iface cfg
11-21 14:30:25.346  5784  5801 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-21 14:30:25.346  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:25.346   930  2919 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-21 14:30:25.349   930  5916 D DhcpClient: Scheduling renewal in 86399s
,11-21 14:30:25.352  5784  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-21 14:30:25.352  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 14:30:25.357   930  2919 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-21 14:30:25.358   930  2919 D WifiConfigStore: No blacklist allowed without epno enabled
11-21 14:30:25.358   930  2926 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-21 14:30:25.359   930  2926 D ConnectivityService: Adding iface wlan0 to network 101
,11-21 14:30:25.361   930  2919 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-21 14:30:25.384   930  2926 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-21 14:30:25.384   930  2926 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-21 14:30:25.386   930  2926 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-21 14:30:25.387   930  2926 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-21 14:30:25.388   930  2926 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-21 14:30:25.393   930  2926 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 14:30:25.397   930  2926 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-21 14:30:25.397   930  2926 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-21 14:30:25.397   930  2926 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-21 14:30:25.397   930  2926 D ConnectivityService:    accepting network in place of null
11-21 14:30:25.397   930  2919 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-21 14:30:25.397   930  2919 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-21 14:30:25.398   930  2926 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-21 14:30:25.416   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 14:30:25.435   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 14:30:25.438   930  2926 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-21 14:30:25.438   930  2926 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-21 14:30:25.439  3707  3818 W QCNEJ   : |CORE| network available: 101
11-21 14:30:25.440   930  2926 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-21 14:30:25.441   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-21 14:30:25.443  3707  3818 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-21 14:30:25.444  3707  3818 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-21 14:30:25.445  3707  3818 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-21 14:30:25.456  5004  5028 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-21 14:30:25.456  5004  5028 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 14:30:25.456  5004  5028 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-21 14:30:25.456  5004  5028 E SarControlService: no key has been found,reset the power
11-21 14:30:25.456  5004  5041 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-21 14:30:25.456  5004  5041 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 14:30:25.456  5004  5041 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 14:30:25.457  5029  5029 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 14:30:25.457  5029  5029 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-21 14:30:25.458  3900  3900 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-21 14:30:25.459  5004  5041 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-21 14:30:25.459  5004  5041 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-21 14:30:25.459  5004  5041 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 14:30:25.459  5029  5029 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 14:30:25.460  5029  5029 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-21 14:30:25.462  3915  3915 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-21 14:30:25.463  5029  5043 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2b4fa74 HexData = [00000000ec03000000000000ffffffff]
,11-21 14:30:25.463  5029  5043 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 14:30:25.463  5029  5043 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-21 14:30:25.466  5029  5043 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2b4fa74 HexData = [00000000ed03000000000000ffffffff]
11-21 14:30:25.466  5029  5043 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 14:30:25.466  5029  5043 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-21 14:30:25.466  5029  5029 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 14:30:25.467  5004  5014 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-21 14:30:25.467  3915  3915 D SystemUpdateService: onCreate
11-21 14:30:25.468  5029  5029 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 14:30:25.468  5004  5015 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-21 14:30:25.472  3915  3915 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-21 14:30:25.483  3915  3915 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-21 14:30:25.493  3915  5360 I iu.UploadsManager: num queued entries: 0
,11-21 14:30:25.493  3915  5360 I iu.UploadsManager: num updated entries: 0
11-21 14:30:25.494  3915  5360 I iu.SyncManager: NEXT; no task
,11-21 14:30:25.498  3915  3915 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-21 14:30:25.499  3915  3915 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-21 14:30:25.501  5863  5863 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-21 14:30:25.505  5863  5863 D SprintDMHelper: simOperator: 
11-21 14:30:25.505  5863  5863 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 14:30:25.517  3915  5930 I SystemUpdateService: active receiver: enabled
,11-21 14:30:25.557  3915  5930 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-21 14:30:25.560  3915  5930 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-21 14:30:25.560  3915  5930 I SystemUpdateService: now status is 0 (complete)
11-21 14:30:25.560  3915  5930 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 14:30:25.560  3915  5930 I SystemUpdateService: file has been verified
11-21 14:30:25.561  3915  5930 I SystemUpdateService: OTA package size = 21989297
,11-21 14:30:25.567  3915  5930 I SystemUpdateService: showing system update notification
,11-21 14:30:25.574   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 14:30:25.581  3915  3915 D SystemUpdateService: onDestroy
,11-21 14:30:25.666   930  5915 D NetlinkSocketObserver: NeighborEvent{elapsedMs=202497, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 14:30:25.750  4966  5934 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-21 14:30:25.763   930  5914 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-21 14:30:25.826   930  5914 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Nov 2016 13:30:25 GMT], X-Android-Received-Millis=[1479735025824], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479735025792]}
,11-21 14:30:25.827   930  2926 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-21 14:30:25.827   930  2926 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-21 14:30:25.828   930  2926 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-21 14:30:25.828  5675  5675 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-21 14:30:25.828  5675  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 14:30:25.829  5675  5675 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 14:30:25.831   930  2926 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-21 14:30:25.857  5784  5784 D BtGatt.ScanManager: awakened up at time 202689
,11-21 14:30:25.859  5784  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 14:30:25.873  5784  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-21 14:30:25.873  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 14:30:25.876  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-21 14:30:26.379  5784  5784 D BtGatt.ScanManager: awakened up at time 203210
,11-21 14:30:26.382  5784  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 14:30:26.399  5784  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-21 14:30:26.399  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:26.401  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-21 14:30:26.440   930  2926 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-21 14:30:28.327  5675  5722 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-21 14:30:28.328  5675  5722 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-21 14:30:28.328  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,11-21 14:30:28.329  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.329  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.329  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.330  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 14:30:28.330  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 14:30:28.330  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 14:30:28.330  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-21 14:30:28.330  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 14:30:28.330  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 14:30:28.330  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 14:30:28.330  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 14:30:28.330  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 14:30:28.330  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.330  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-21 14:30:28.330  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.330  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.331  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-21 14:30:28.331  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 14:30:28.331  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.331  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.331  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.334  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:28.335  5784  5795 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-21 14:30:28.336  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 14:30:28.337  5784  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 14:30:28.338  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:28.340  5784  5830 D BtGatt.GattService: stopScan() - queue size =1
11-21 14:30:28.342  5784  5827 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 14:30:28.343  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 14:30:28.343  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.343  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 14:30:28.343  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.344  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 14:30:28.344  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.344  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.344  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-21 14:30:28.344  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-21 14:30:28.344  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-21 14:30:28.345  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-21 14:30:28.345  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.345  5784  5784 D BtGatt.ScanManager: awakened up at time 205176
,11-21 14:30:28.347  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:28.351  5784  5795 D BtGatt.GattService: registerClient() - UUID=36e68989-c66e-407f-940d-28d63eb9a7ff
11-21 14:30:28.352  5784  5801 D BtGatt.GattService: onClientRegistered() - UUID=36e68989-c66e-407f-940d-28d63eb9a7ff, clientIf=5
11-21 14:30:28.353  5675  5685 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-21 14:30:28.353  5784  5831 D BtGatt.GattService: start scan with filters
,11-21 14:30:28.362  5795  5795 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[35943]" dev="sockfs" ino=35943 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 14:30:28.362  5795  5795 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[35943]" dev="sockfs" ino=35943 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 14:30:28.358  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-21 14:30:28.359  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.359  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-21 14:30:28.359  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.359  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.359  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:28.359  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 14:30:28.360  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:28.360  5675  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 14:30:28.360  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 14:30:28.360  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 14:30:28.360  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 14:30:28.360  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 14:30:28.360  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:28.360  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 14:30:28.361  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 14:30:28.362  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 14:30:28.362  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 14:30:28.362  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 14:30:28.362  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 14:30:28.362  5675  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 14:30:28.362  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,11-21 14:30:28.362  5675  5942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 14:30:28.363  5675  5942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 14:30:28.365  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 14:30:28.365  5675  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 14:30:28.368  5675  5942 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 14:30:28.369  5784  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-21 14:30:28.370  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:28.370  5784  5801 D BtGatt.GattService: current time is 205201564130
11-21 14:30:28.370  5784  5801 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -81, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -91, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -80, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -79, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-21 14:30:28.372  5784  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-21 14:30:28.373  5784  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 14:30:28.374  5784  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-21 14:30:28.374  5784  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-21 14:30:28.376  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.376  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.376  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.376  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 14:30:28.377  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 14:30:28.377  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 14:30:28.377  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-21 14:30:28.377  5675  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:28.377  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:28.377  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.378  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 14:30:28.378  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 14:30:28.378  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.378  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.379  5,675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.381  5675  5722 D BluetoothAdapter: STATE_ON
,11-21 14:30:28.383  5784  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-21 14:30:28.385  5784  5796 D BtGatt.GattService: registerClient() - UUID=067d0a89-54ff-49a1-a272-76a12e92a0ec
,11-21 14:30:28.395  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:28.395  5784  5804 D BtGatt.ScanManager: stopping BLe Batch
11-21 14:30:28.396  5784  5801 D BtGatt.GattService: onClientRegistered() - UUID=067d0a89-54ff-49a1-a272-76a12e92a0ec, clientIf=6
11-21 14:30:28.396  5675  5685 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-21 14:30:28.397  5784  5803 D BtGatt.AdvertiseManager: message : 0
,11-21 14:30:28.400  5784  5803 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 14:30:28.406  5784  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-21 14:30:28.406  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:28.406  5784  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 14:30:28.416  5784  5801 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-21 14:30:28.421  5784  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-21 14:30:28.422  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:28.427  5784  5804 D BtGatt.ScanManager: handling starting scan
11-21 14:30:28.427  5784  5801 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
11-21 14:30:28.428  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:28.428  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.428  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-21 14:30:28.428  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.428  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.428  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:28.429  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.429  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.429  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.429  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.429  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.429  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-21 14:30:28.429  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-21 14:30:28.429  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 14:30:28.431  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 14:30:28.431  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.434  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.434  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.434  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:28.434  5675  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 14:30:28.435  5784  5801 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-21 14:30:28.435  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 14:30:28.435  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:28.435  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:28.435  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 14:30:28.435  5784  5804 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-21 14:30:28.435  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 14:30:28.435  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:28.435  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:28.435  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:28.435  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-21 14:30:28.436  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: s,tateSet: [SCANNING]
11-21 14:30:28.436  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:28.436  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 14:30:28.436  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-21 14:30:28.436  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 14:30:28.439  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 14:30:28.439  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-21 14:30:28.439  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-21 14:30:28.440  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:28.440  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:28.440  5675  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-21 14:30:28.441  5784  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-21 14:30:28.441  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:28.441  5784  5804 D BtGatt.ScanManager: Starting BLE batch scan
,11-21 14:30:28.441  5784  5804 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-21 14:30:28.452  5784  5801 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-21 14:30:28.452  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 14:30:28.457  5784  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-21 14:30:28.457  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 14:30:28.941  5675  5675 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-21 14:30:28.941  5675  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 14:30:28.941  5675  5675 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 14:30:31.257   930  2926 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 14:30:31.443  5675  5722 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-21 14:30:31.443  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 14:30:31.443  5675  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 14:30:31.443  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 14:30:31.444  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 14:30:31.444  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 14:30:31.444  5675  5942 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 14:30:31.444  5675  5942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 14:30:31.444  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 14:30:31.445  5675  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 14:30:31.445  5675  5942 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-21 14:30:31.445  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 14:30:31.445  5675  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 14:30:31.445  5675  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9962392 removed from the list
,11-21 14:30:31.445  5675  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 14:30:31.445  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 14:30:31.446  5675  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 14:30:31.446  5675  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 14:30:31.446  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 14:30:31.446  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 14:30:31.446  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.446  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.447  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.447  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-21 14:30:31.447  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.450  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:31.451  5784  5796 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-21 14:30:31.452  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 14:30:31.452  5784  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-21 14:30:31.453  5675  5722 D BluetoothAdapter: STATE_ON
11-21 14:30:31.455  5784  5830 D BtGatt.GattService: stopScan() - queue size =1
11-21 14:30:31.457  5784  5827 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 14:30:31.457  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 14:30:31.458  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.458  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 14:30:31.458  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.458  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.459  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.459  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 14:30:31.459  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.460  5784  5803 D BtGatt.AdvertiseManager: message : 1
11-21 14:30:31.461  5784  5784 D BtGatt.ScanManager: awakened up at time 208292
11-21 14:30:31.462  5784  5803 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-21 14:30:31.474  5784  5801 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-21 14:30:31.474  5784  5801 D BtGatt.GattService: Client app is not null!
,11-21 14:30:31.482  5784  5795 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-21 14:30:31.483  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 14:30:31.483  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:31.483  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 14:30:31.484  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:31.484  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.484  5675  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:31.484  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 14:30:31.484  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 14:30:31.485  5675  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-21 14:30:31.486  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.487  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-21 14:30:31.487  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 14:30:31.487  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.487  5675  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 14:30:31.487  5675  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8afd163 removed from the list
,11-21 14:30:31.487  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 14:30:31.488  5675  5722 D io.jxcore.node.ConnectivityMonitor: stop
11-21 14:30:31.488  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 14:30:31.488  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:31.488  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:31.488  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 14:30:31.488  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-21 14:30:31.488  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:31.488  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 14:30:31.488  5675  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-21 14:30:31.488  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 14:30:31.489  5675  5722 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-21 14:30:31.489  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 14:30:31.489  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 14:30:31.490  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-21 14:30:31.490  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 14:30:31.490  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-21 14:30:31.490  5675  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-21 14:30:31.491  5675  5722 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-21 14:30:31.491  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 14:30:31.491  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:31.491  5675  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 14:30:31.491  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:31.491  5675  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 14:30:31.491  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 14:30:31.492  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 14:30:31.492  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 14:30:31.492  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 14:30:31.492  5675  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 14:30:31.492  5675  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 14:30:31.493  5675  5722 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-21 14:30:31.494  5675  5722 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-21 14:30:31.495  5675  5722 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-21 14:30:31.496  5675  5722 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-21 14:30:31.497  5675  5722 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-21 14:30:31.498  5675  5722 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-21 14:30:31.499  5675  5722 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-21 14:30:31.506  5784  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-21 14:30:31.506  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:31.506  5784  5801 D BtGatt.GattService: current time is 208337652830
11-21 14:30:31.506  5784  5801 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -93, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -94, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -79, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -94, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-21 14:30:31.506  5784  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-21 14:30:31.507  5784  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-21 14:30:31.507  5784  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 14:30:31.507  5784  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-21 14:30:31.507  5784  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-21 14:30:31.508  5784  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-21 14:30:31.513  5784  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-21 14:30:31.514  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:31.514  5784  5804 D BtGatt.ScanManager: stopping BLe Batch
,11-21 14:30:31.519  5784  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-21 14:30:31.519  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 14:30:31.520  5784  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 14:30:31.524  5784  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-21 14:30:31.524  5784  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 14:30:31.993  5675  5675 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 14:30:33.399   930  2926 D ConnectivityService: handlePromptUnvalidated 101
,11-21 14:30:33.504  5675  5722 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-21 14:30:33.665  5675  5944 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 14:30:33.665  5675  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 14:30:34.274   930  2926 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 14:30:34.460  5675  5944 W !!      : call onHalfStreamCopied
,11-21 14:30:34.460  5675  5944 I testCopyDataAndClose: closing input stream
,11-21 14:30:35.256  5675  5944 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 14:30:35.256  5675  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 14:30:35.256  5675  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 14:30:35.256  5675  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 14:30:35.256  5675  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 14:30:35.256  5675  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-21 14:30:35.256  5675  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 14:30:35.257  5675  5944 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 14:30:35.257  5675  5944 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 14:30:35.257  5675  5944 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 14:30:35.257  5675  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 14:30:35.723   930  2919 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,11-21 14:30:36.542   930  2919 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,11-21 14:30:39.993  5675  5722 I StreamCopyingThreadTest: Starting test: testRun
,11-21 14:30:39.999  5675  5945 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-21 14:30:39.999  5675  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 14:30:42.776   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 14:30:42.776   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 14:30:43.986   930  5915 D NetlinkSocketObserver: NeighborEvent{elapsedMs=220817, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 14:30:45.006  5675  5946 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-21 14:30:45.009  5675  5722 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-21 14:30:45.130  5675  5947 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 14:30:45.130  5675  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 14:30:46.802  5675  5947 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 14:30:46.802  5675  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 14:30:46.802  5675  5947 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 14:30:46.802  5675  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 14:30:46.802  5675  5947 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 14:30:46.803  5675  5947 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 14:30:46.803  5675  5947 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-21 14:30:46.803  5675  5947 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 14:30:46.803  5675  5947 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 14:30:46.803  5675  5947 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 14:30:46.803  5675  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 14:30:50.759  3605  5427 I Keyboard.Facilitator.LanguageModelFlusher: run()
11-21 14:30:50.759  3605  5427 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-21 14:30:50.791  3533  3533 I ConfigService: onCreate
,11-21 14:30:51.533  5675  5722 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-21 14:30:51.536  5675  5949 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-21 14:30:51.536  5675  5949 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 14:30:51.536  5675  5949 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
11-21 14:30:51.536  5675  5949 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 14:30:51.536  5675  5949 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 14:30:51.536  5675  5949 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 14:30:51.536  5675  5949 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 14:30:51.536  5675  5949 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 14:30:51.537  5675  5949 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 14:30:51.537  5675  5949 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-21 14:30:51.537  5675  5949 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 14:30:51.537  5675  5949 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-21 14:30:51.537  5675  5949 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-21 14:30:51.539  5675  5722 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-21 14:30:51.539  5675  5722 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-21 14:30:51.540  5675  5722 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-21 14:30:51.542  5675  5950 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-21 14:30:51.542  5675  5950 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 14:30:51.543  5675  5950 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
11-21 14:30:51.543  5675  5950 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-21 14:30:51.543  5675  5950 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-21 14:30:51.543  5675  5950 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-21 14:30:51.544  5675  5950 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-21 14:30:51.544  5675  5950 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-21 14:30:51.545  5675  5722 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-21 14:30:51.545  5675  5722 E com.test.thalitest.ThaliTestRunner: 
11-21 14:30:51.545  5675  5722 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-21 14:30:51.545  5675  5722 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 14:30:51.546  5675,  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 14:30:51.546  5675  5722 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTe,stRunner: Expected: is <true>
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.,java:268)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 14:30:51.547  5675  5722 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.,Method.invoke(Native Method)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
,11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
,11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:51.548  5675  5722 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,11-21 14:30:51.552  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG UnitTest_app: 'Running unit tests'
11-21 14:30:51.552  5675  5722 I jxcore-log: 
11-21 14:30:51.552  5675  5722 I jxcore-log: *Native tests were executed*
11-21 14:30:51.552  5675  5722 I jxcore-log: 
11-21 14:30:51.552  5675  5722 I jxcore-log: Total number of executed tests:  82
11-21 14:30:51.552  5675  5722 I jxcore-log: 
11-21 14:30:51.552  5675  5722 I jxcore-log: Number of passed tests:  79
11-21 14:30:51.552  5675  5722 I jxcore-log: 
11-21 14:30:51.552  5675  5722 I jxcore-log: Number of failed tests:  3
,11-21 14:30:51.552  5675  5722 I jxcore-log: 
11-21 14:30:51.553  5675  5722 I jxcore-log: Number of ignored tests:  0
11-21 14:30:51.553  5675  5722 I jxcore-log: 
11-21 14:30:51.553  5675  5722 I jxcore-log: Total duration:  39925
11-21 14:30:51.553  5675  5722 I jxcore-log: 
11-21 14:30:51.553  5675  5722 I jxcore-log: Failed to execute UT.
11-21 14:30:51.553  5675  5722 I jxcore-log: 
11-21 14:30:51.553  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-21 14:30:51.553  5675  5722 I jxcore-log: 
11-21 14:30:51.555  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-21 14:30:51.555  5675  5722 I jxcore-log: 
11-21 14:30:51.558  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 14:30:51.558  5675  5722 I jxcore-log: 
11-21 14:30:51.558  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 14:30:51.558  5675  5722 I jxcore-log: 
,11-21 14:30:51.559  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 14:30:51.559  5675  5722 I jxcore-log: 
11-21 14:30:51.560  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 14:30:51.560  5675  5722 I jxcore-log: 
11-21 14:30:51.560  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 14:30:51.560  5675  5722 I jxcore-log: 
11-21 14:30:51.561  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 14:30:51.561  5675  5722 I jxcore-log: 
11-21 14:30:51.561  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 14:30:51.561  5675  5722 I jxcore-log: 
,11-21 14:30:51.561  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 14:30:51.561  5675  5722 I jxcore-log: 
11-21 14:30:51.561  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 14:30:51.561  5675  5722 I jxcore-log: 
11-21 14:30:51.562  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 14:30:51.562  5675  5722 I jxcore-log: 
11-21 14:30:51.562  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 14:30:51.562  5675  5722 I jxcore-log: 
,11-21 14:30:51.562  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 14:30:51.562  5675  5722 I jxcore-log: 
11-21 14:30:51.563  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 14:30:51.563  5675  5722 I jxcore-log: 
11-21 14:30:51.563  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 14:30:51.563  5675  5722 I jxcore-log: 
11-21 14:30:51.563  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 14:30:51.563  5675  5722 I jxcore-log: 
11-21 14:30:51.563  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 14:30:51.563  5675  5722 I jxcore-log: 
,11-21 14:30:51.563  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 14:30:51.563  5675  5722 I jxcore-log: 
11-21 14:30:51.564  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 14:30:51.564  5675  5722 I jxcore-log: 
11-21 14:30:51.564  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 14:30:51.564  5675  5722 I jxcore-log: 
11-21 14:30:51.564  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 14:30:51.564  5675  5722 I jxcore-log: 
11-21 14:30:51.564  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 14:30:51.564  5675  5722 I jxcore-log: 
,11-21 14:30:51.564  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 14:30:51.564  5675  5722 I jxcore-log: 
11-21 14:30:51.565  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 14:30:51.565  5675  5722 I jxcore-log: 
11-21 14:30:51.565  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-21 14:30:51.565  5675  5722 I jxcore-log: 
,11-21 14:30:51.565  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 14:30:51.565  5675  5722 I jxcore-log: 
11-21 14:30:51.565  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-21 14:30:51.565  5675  5722 I jxcore-log: 
11-21 14:30:51.566  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 14:30:51.566  5675  5722 I jxcore-log: 
11-21 14:30:51.567  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 14:30:51.567  5675  5722 I jxcore-log: 
,11-21 14:30:51.567  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 14:30:51.567  5675  5722 I jxcore-log: 
11-21 14:30:51.567  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 14:30:51.567  5675  5722 I jxcore-log: 
11-21 14:30:51.568  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-21 14:30:51.568  5675  5722 I jxcore-log: 
11-21 14:30:51.568  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 14:30:51.568  5675  5722 I jxcore-log: 
,11-21 14:30:51.568  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 14:30:51.568  5675  5722 I jxcore-log: 
11-21 14:30:51.568  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-21 14:30:51.568  5675  5722 I jxcore-log: 
11-21 14:30:51.568  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 14:30:51.568  5675  5722 I jxcore-log: 
11-21 14:30:51.569  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 14:30:51.569  5675  5722 I jxcore-log: 
,11-21 14:30:51.569  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 14:30:51.569  5675  5722 I jxcore-log: 
11-21 14:30:51.569  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 14:30:51.569  5675  5722 I jxcore-log: 
11-21 14:30:51.574  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-21 14:30:51.574  5675  5722 I jxcore-log: 
11-21 14:30:51.574  5675  5675 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-21 14:30:51.574  5675  5722 I jxcore-log: 2016-11-21 13:30:51 - WARN testUtils: 'myNameCallback not set!'
11-21 14:30:51.574  5675  5722 I jxcore-log: 
,11-21 14:30:52.777   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:30:53.613  5675  5722 I jxcore-log: 2016-11-21 13:30:53 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-21 14:30:53.613  5675  5722 I jxcore-log: 
,11-21 14:30:53.614  5675  5722 I jxcore-log: 2016-11-21 13:30:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-21 14:30:53.614  5675  5722 I jxcore-log: 
,11-21 14:30:53.778   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:30:53.947  5675  5722 I jxcore-log: 2016-11-21 13:30:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-21 14:30:53.947  5675  5722 I jxcore-log: 
,11-21 14:30:53.961  5675  5722 I jxcore-log: 2016-11-21 13:30:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-21 14:30:53.961  5675  5722 I jxcore-log: 
,11-21 14:30:54.779   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:30:55.063  5675  5722 I jxcore-log: 2016-11-21 13:30:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-21 14:30:55.063  5675  5722 I jxcore-log: 
,11-21 14:30:55.227  5675  5722 I jxcore-log: 2016-11-21 13:30:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-21 14:30:55.227  5675  5722 I jxcore-log: 
,11-21 14:30:55.233  5675  5722 I jxcore-log: 2016-11-21 13:30:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-21 14:30:55.233  5675  5722 I jxcore-log: 
,11-21 14:30:55.245  5675  5722 I jxcore-log: 2016-11-21 13:30:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-21 14:30:55.245  5675  5722 I jxcore-log: 
,11-21 14:30:55.447   930  2926 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 14:30:55.725  5675  5722 I jxcore-log: 2016-11-21 13:30:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-21 14:30:55.725  5675  5722 I jxcore-log: 
,11-21 14:30:55.769  5675  5722 I jxcore-log: 2016-11-21 13:30:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-21 14:30:55.769  5675  5722 I jxcore-log: 
,11-21 14:30:55.780   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:30:55.782  5675  5722 I jxcore-log: 2016-11-21 13:30:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-21 14:30:55.782  5675  5722 I jxcore-log: 
,11-21 14:30:55.787  5675  5722 I jxcore-log: 2016-11-21 13:30:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-21 14:30:55.787  5675  5722 I jxcore-log: 
,11-21 14:30:55.823  3533  3533 I ConfigService: onDestroy
,11-21 14:30:56.058  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-21 14:30:56.058  5675  5722 I jxcore-log: 
,11-21 14:30:56.182  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-21 14:30:56.182  5675  5722 I jxcore-log: 
,11-21 14:30:56.559  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-21 14:30:56.559  5675  5722 I jxcore-log: 
,11-21 14:30:56.566  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-21 14:30:56.566  5675  5722 I jxcore-log: 
,11-21 14:30:56.570  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-21 14:30:56.570  5675  5722 I jxcore-log: 
,11-21 14:30:56.574  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-21 14:30:56.574  5675  5722 I jxcore-log: 
,11-21 14:30:56.579  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-21 14:30:56.579  5675  5722 I jxcore-log: 
,11-21 14:30:56.617  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-21 14:30:56.617  5675  5722 I jxcore-log: 
,11-21 14:30:56.623  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-21 14:30:56.623  5675  5722 I jxcore-log: 
,11-21 14:30:56.651  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-21 14:30:56.651  5675  5722 I jxcore-log: 
,11-21 14:30:56.690  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-21 14:30:56.690  5675  5722 I jxcore-log: 
,11-21 14:30:56.697  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-21 14:30:56.697  5675  5722 I jxcore-log: 
,11-21 14:30:56.703  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-21 14:30:56.703  5675  5722 I jxcore-log: 
,11-21 14:30:56.719  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-21 14:30:56.719  5675  5722 I jxcore-log: 
,11-21 14:30:56.733  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-21 14:30:56.733  5675  5722 I jxcore-log: 
,11-21 14:30:56.739  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-21 14:30:56.739  5675  5722 I jxcore-log: 
,11-21 14:30:56.745  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-21 14:30:56.745  5675  5722 I jxcore-log: 
,11-21 14:30:56.758  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-21 14:30:56.758  5675  5722 I jxcore-log: 
,11-21 14:30:56.775  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-21 14:30:56.775  5675  5722 I jxcore-log: 
,11-21 14:30:56.781   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 14:30:56.790  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-21 14:30:56.790  5675  5722 I jxcore-log: 
,11-21 14:30:56.801  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-21 14:30:56.801  5675  5722 I jxcore-log: 
,11-21 14:30:56.813  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-21 14:30:56.813  5675  5722 I jxcore-log: 
,11-21 14:30:56.824  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-21 14:30:56.824  5675  5722 I jxcore-log: 
,11-21 14:30:56.837  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-21 14:30:56.837  5675  5722 I jxcore-log: 
,11-21 14:30:56.847  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-21 14:30:56.847  5675  5722 I jxcore-log: 
,11-21 14:30:56.853  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-21 14:30:56.853  5675  5722 I jxcore-log: 
,11-21 14:30:56.874  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-21 14:30:56.874  5675  5722 I jxcore-log: 
,11-21 14:30:56.880  5675  5722 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-21 14:30:56.881  5675  5722 I jxcore-log: 2016-11-21 13:30:56 - INFO testUtils: 'BLE multiple advertisement supported'
11-21 14:30:56.881  5675  5722 I jxcore-log: 
,11-21 14:30:57.071  5675  5722 I jxcore-log: 2016-11-21 13:30:57 - DEBUG CoordinatedClient: 'connected to the test server'
11-21 14:30:57.071  5675  5722 I jxcore-log: 
,11-21 14:30:57.222  5675  5722 I jxcore-log: 2016-11-21 13:30:57 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
11-21 14:30:57.222  5675  5722 I jxcore-log: 
,11-21 14:30:57.224  5675  5722 I jxcore-log: 2016-11-21 13:30:57 - DEBUG CoordinatedClient: 'test client failed'
11-21 14:30:57.224  5675  5722 I jxcore-log: 
,11-21 14:30:57.231  5675  5722 I jxcore-log: 2016-11-21 13:30:57 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-21 14:30:57.231  5675  5722 I jxcore-log: 
,11-21 14:30:57.235  5675  5722 I jxcore-log: 2016-11-21 13:30:57 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:187:20
11-21 14:30:57.235  5675  5722 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-21 14:30:57.235  5675  5722 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-21 14:30:57.235  5675  5722 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-21 14:30:57.235  5675  5722 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-21 14:30:57.235  5675  5722 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
11-21 14:30:57.235  5675  5722 I jxcore-log: 
,11-21 14:30:57.235  5675  5722 I jxcore-log: 2016-11-21 13:30:57 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-21 14:30:57.235  5675  5722 I jxcore-log: 
,11-21 14:30:57.238  5675  5722 I jxcore-log: 2016-11-21 13:30:57 - ERROR runTests: 'Test client failed: Native unit tests failed
11-21 14:30:57.238  5675  5722 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:187:20
11-21 14:30:57.238  5675  5722 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-21 14:30:57.238  5675  5722 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-21 14:30:57.238  5675  5722 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-21 14:30:57.238  5675  5722 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-21 14:30:57.238  5675  5722 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
11-21 14:30:57.238  5675  5722 I jxcore-log: 
,11-21 14:30:57.708  5959  5959 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-21 14:30:57.730  5959  5959 D AndroidRuntime: CheckJNI is OFF
,11-21 14:30:57.755  5959  5959 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-21 14:30:57.782   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-21 14:30:57.783  5959  5959 I Radio-JNI: register_android_hardware_Radio DONE
,11-21 14:30:57.798  5959  5959 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-21 14:30:57.805   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-21 14:30:57.806   930   943 I ActivityManager: Killing 5675:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-21 14:30:57.921   930   941 D GraphicsStats: Buffer count: 2
,11-21 14:30:57.921   930  3104 I WindowState: WIN DEATH: Window{ddfbf74 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-21 14:30:57.922   930  2925 D WifiService: Client connection lost with reason: 4
,11-21 14:30:57.933   930   943 W ActivityManager: Force removing ActivityRecord{ce9a105 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-21 14:30:57.943   930   953 I art     : Starting a blocking GC Explicit
,11-21 14:30:57.948   930  3105 W ActivityManager: Spurious death for ProcessRecord{802205a 0:com.test.thalitest/u0a77}, curProc for 5675: null
,11-21 14:30:57.982   930  3105 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5675 uid 10077
11-21 14:30:57.983  3605  3605 I Keyboard.Facilitator: onFinishInput()
11-21 14:30:57.979  3105  3105 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[26385]" dev="sockfs" ino=26385 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 14:30:57.979  3105  3105 W Binder_4: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[26385]" dev="sockfs" ino=26385 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 14:30:58.020   930   953 I art     : Explicit concurrent mark sweep GC freed 27175(1722KB) AllocSpace objects, 7(172KB) LOS objects, 33% free, 28MB/43MB, paused 1.604ms total 77.196ms
,11-21 14:30:58.043  3900  5972 I MicroRecognitionRnrImpl: Starting detection.
,11-21 14:30:58.044  3900  5973 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@10aee3c
,11-21 14:30:58.046   513  5975 I AudioFlinger: AudioFlinger's thread 0xf1c40000 ready to run
,11-21 14:30:58.047   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-21 14:30:58.049  5959  5959 I art     : System.exit called, status: 0
11-21 14:30:58.049  5959  5959 I AndroidRuntime: VM exiting with result code 0.
,11-21 14:30:58.054   513  2969 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-21 14:30:58.055  3900  5973 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@10aee3c
,11-21 14:30:58.064   930   953 I ActivityManager: Start proc 5977:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-21 14:30:58.064   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
11-21 14:30:58.066   513  5975 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-21 14:30:58.066   513  5975 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-21 14:30:58.066   513  5975 I ACDB-LOADER: ACDB AFE returned = -19
11-21 14:30:58.066   513  5975 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-21 14:30:58.066   513  5975 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-21 14:30:58.066   513  5975 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
11-21 14:30:58.073   513  5975 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-21 14:30:58.081  3605  3605 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-21 14:30:58.084  5784  5784 D BluetoothMapAppObserver: onReceive
,11-21 14:30:58.084  5784  5784 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-21 14:30:58.086  4045  4130 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-21 14:30:58.087   930  2890 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-21 14:30:58.089  3605  5989 I Keyboard.Facilitator.DecoderInitializer: run()
,11-21 14:30:58.096  3605  5989 I Decoder : createOrResetDecoder
,11-21 14:30:58.143  3353  5993 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-21 14:30:58.144  3533  3533 I ConfigService: onCreate
,11-21 14:30:58.147  3736  3736 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
11-21 14:30:58.155   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-21 14:30:58.155  5647  5647 W kworker/3:3: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-21 14:30:58.161  3900  3900 I HotwordWorkerImpl: onReady
,11-21 14:30:58.162  5647  5647 W kworker/3:3: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 14:30:58.173  3605  5989 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-21 14:30:58.179  5647  5647 W kworker/3:3: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 14:30:58.196  3533  3533 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-21 14:30:58.197  3533  3533 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-21 14:30:58.198  3533  3533 E AndroidRuntime: FATAL EXCEPTION: main
11-21 14:30:58.198  3533  3533 E AndroidRuntime: Process: com.google.process.gapps, PID: 3533
11-21 14:30:58.198  3533  3533 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-21 14:30:58.198  3533  3533 E AndroidRuntime: 	... 8 more
,11-21 14:30:58.203   930  5999 E DropBoxManagerService: Can't write: system_app_crash
11-21 14:30:58.203   930  5999 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
11-21 14:30:58.203   930  5999 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 14:30:58.203   930  5999 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 14:30:58.203   930  5999 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 14:30:58.203   930  5999 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 14:30:58.203   930  5999 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 14:30:58.203   930  5999 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 14:30:58.203   930  5999 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 14:30:58.203   930  5999 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 14:30:58.203   930  5999 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 14:30:58.203   930  5999 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 14:30:58.203   930  5999 E DropBoxManagerService: 	... 5 more
,11-21 14:30:58.211  3353  5993 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-21 14:30:58.212  3353  5993 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-21 14:30:58.212  3353  5993 E AndroidRuntime: Process: android.process.acore, PID: 3353
11-21 14:30:58.212  3353  5993 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 14:30:58.212  3353  5993 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-21 14:30:58.219   761   761 W Binder_3: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[33985]" dev="sockfs" ino=33985 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 14:30:58.219   761   761 W Binder_3: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[33985]" dev="sockfs" ino=33985 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 14:30:58.222   761   761 W Binder_3: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[33988]" dev="sockfs" ino=33988 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 14:30:58.225   930  6000 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-21 14:30:58.222   761   761 W Binder_3: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[33988]" dev="sockfs" ino=33988 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 14:30:58.230   930  6001 E DropBoxManagerService: Can't write: system_app_crash
11-21 14:30:58.230   930  6001 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-21 14:30:58.230   930  6001 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 14:30:58.230   930  6001 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 14:30:58.230   930  6001 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 14:30:58.230   930  6001 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 14:30:58.230   930  6001 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 14:30:58.230   930  6001 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 14:30:58.230   930  6001 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 14:30:58.230   930  6001 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 14:30:58.230   930  6001 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 14:30:58.230   930  6001 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 14:30:58.230   930  6001 E DropBoxManagerService: 	... 5 more
,11-21 14:30:58.270   930  6000 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-21 14:30:58.270   930  6000 I Adreno  : Build Date                       : 12/06/15
11-21 14:30:58.270   930  6000 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-21 14:30:58.270   930  6000 I Adreno  : Local Branch                     : mybranch17112971
11-21 14:30:58.270   930  6000 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-21 14:30:58.270   930  6000 I Adreno  : Remote Branch                    : NONE
11-21 14:30:58.270   930  6000 I Adreno  : Reconstruct Branch               : NOTHING
,11-21 14:30:58.271  3605  5989 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-21 14:30:58.273  3605  5989 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,11-21 14:30:58.273  3605  5989 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-21 14:30:58.277  3605  5989 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-21 14:30:58.277  3605  5989 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-21 14:30:58.278  3605  5989 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-21 14:30:58.278  3605  5989 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-21 14:30:58.278  3605  5989 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-21 14:30:58.278  3605  5989 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-21 14:30:58.278  3605  5989 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-21 14:30:58.279  3605  5989 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-21 14:30:58.279  3605  5989 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,11-21 14:30:58.279  3605  5989 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-21 14:30:58.471   930  2926 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 14:30:58.501  3754  3962 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-21 14:30:58.563   384   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
