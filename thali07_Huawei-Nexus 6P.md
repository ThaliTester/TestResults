#### Test 935721679a8c53b_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-21 17:14:24.888  3746  4406 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-21 17:14:25.382  5578  5578 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-21 17:14:25.387  5578  5578 D AndroidRuntime: CheckJNI is OFF
11-21 17:14:25.416  5578  5578 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-21 17:14:25.450  5578  5578 I Radio-JNI: register_android_hardware_Radio DONE
11-21 17:14:25.467  5578  5578 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-21 17:14:25.473   931  3820 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-21 17:14:25.510  3961  3973 W SearchService: Abort, client detached.
11-21 17:14:25.513  5578  5578 D AndroidRuntime: Shutting down VM
11-21 17:14:25.519  3961  4235 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@97807e0
11-21 17:14:25.519  3961  3961 I HotwordDetector: Closing mic
11-21 17:14:25.519  3961  4241 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-21 17:14:25.536   931  3603 I ActivityManager: Start proc 5587:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-21 17:14:25.593   514  4243 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-21 17:14:25.594   514  4243 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-21 17:14:25.597   514  4243 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-21 17:14:25.597   514  4243 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-21 17:14:25.598   514  2987 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-21 17:14:25.599  3961  4237 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-21 17:14:25.600  3961  4240 I MicroRecognitionRnrImpl: Detection finished
11-21 17:14:25.641  5587  5587 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-21 17:14:25.663  5587  5587 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-21 17:14:25.730  5587  5587 I LibraryLoader: Time to load native libraries: 63 ms (timestamps 7162-7225)
11-21 17:14:25.730  5587  5587 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-21 17:14:25.763  5587  5587 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {aab75ae}
,11-21 17:14:25.763  5587  5587 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-21 17:14:25.763  5587  5587 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-21 17:14:25.769  5587  5587 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-21 17:14:25.770  5587  5587 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-21 17:14:25.812  5587  5587 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-21 17:14:25.826  5587  5587 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-21 17:14:25.826  5587  5587 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-21 17:14:25.826  5587  5587 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-21 17:14:25.826  5587  5587 I Adreno  : Build Date                       : 12/06/15
11-21 17:14:25.826  5587  5587 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-21 17:14:25.826  5587  5587 I Adreno  : Local Branch                     : mybranch17112971
11-21 17:14:25.826  5587  5587 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-21 17:14:25.826  5587  5587 I Adreno  : Remote Branch                    : NONE
11-21 17:14:25.826  5587  5587 I Adreno  : Reconstruct Branch               : NOTHING
,11-21 17:14:25.871   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e780997:true
,11-21 17:14:25.904   778   778 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[14067]" dev="sockfs" ino=14067 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 17:14:25.904   778   778 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14067]" dev="sockfs" ino=14067 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 17:14:25.917  5587  5587 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-21 17:14:25.926  5587  5587 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-21 17:14:25.953  5587  5624 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-21 17:14:25.951   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32404]" dev="sockfs" ino=32404 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 17:14:25.951   408   408 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32404]" dev="sockfs" ino=32404 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 17:14:25.954  3782  3782 W Binder_8: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14078]" dev="sockfs" ino=14078 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 17:14:25.957  5587  5611 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
11-21 17:14:25.954  3782  3782 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14078]" dev="sockfs" ino=14078 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 17:14:25.988  5587  5624 I OpenGLRenderer: Initialized EGL, version 1.4
,11-21 17:14:26.073   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +560ms
,11-21 17:14:26.071  3421  3421 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[29428]" dev="sockfs" ino=29428 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 17:14:26.071  3421  3421 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[29428]" dev="sockfs" ino=29428 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 17:14:26.074  3602  3602 W Binder_6: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[29427]" dev="sockfs" ino=29427 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 17:14:26.074  3602  3602 W Binder_6: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[29427]" dev="sockfs" ino=29427 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 17:14:26.076  3650  3650 I Keyboard.Facilitator: onFinishInput()
,11-21 17:14:26.100  5587  5587 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5587
,11-21 17:14:26.189  5587  5587 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-21 17:14:26.322  5587  5627 D jxcore_app_log: JniHelper::setJavaVM(0xf507c000), pthread_self() = -583005904
,11-21 17:14:26.327   931  3142 I ActivityManager: Killing 5023:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-21 17:14:26.332  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-21 17:14:26.332  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-21 17:14:26.332  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-21 17:14:26.332  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-21 17:14:26.332  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-21 17:14:26.332  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1c9634 added. We now have 1 listener(s)
,11-21 17:14:26.334  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-21 17:14:26.334  5587  5627 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:14:26.335  5587  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-21 17:14:26.335  5587  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-21 17:14:26.337  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ec8aa3 added. We now have 1 listener(s)
11-21 17:14:26.337  5587  5627 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 17:14:26.341   931  2952 D WifiService: New client listening to asynchronous messages
,11-21 17:14:26.341  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 17:14:26.341  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-21 17:14:26.341  5587  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-21 17:14:26.341  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-21 17:14:26.341  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-21 17:14:26.342  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-21 17:14:26.342  5587  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-21 17:14:26.343  5587  5627 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-21 17:14:26.364   931  3142 I ActivityManager: Killing 5243:com.android.settings/1000 (adj 15): empty #18
,11-21 17:14:26.457  5587  5587 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-21 17:14:26.748  5587  5635 W jxcore-log: Initializing JXcore engine
,11-21 17:14:26.749  5587  5635 W jxcore-log: JXcore engine is ready
,11-21 17:14:26.777  5635  5635 W Thread-58: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10836 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-21 17:14:26.777  5635  5635 W Thread-58: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13387]" dev="sockfs" ino=13387 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-21 17:14:26.777  5635  5635 W Thread-58: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-21 17:14:26.777  5635  5635 W Thread-58: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32383]" dev="sockfs" ino=32383 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-21 17:14:26.787  5587  5635 W jxcore-log: Starting JXcore engine
,11-21 17:14:26.844  5587  5635 W jxcore-log: Platform android
11-21 17:14:26.844  5587  5635 W jxcore-log: 
,11-21 17:14:26.845  5587  5635 W jxcore-log: Process ARCH arm
11-21 17:14:26.845  5587  5635 W jxcore-log: 
,11-21 17:14:26.995  5587  5635 I jxcore-log: JXcore Cordova bridge is ready!
11-21 17:14:26.995  5587  5635 I jxcore-log: 
,11-21 17:14:26.995  5587  5635 W jxcore-log: JXcore engine is started
,11-21 17:14:27.002  5587  5627 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-21 17:14:27.005  5587  5587 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-21 17:14:32.082   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:14:33.083   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:14:34.084   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:14:35.086   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:14:35.703   931  2952 D WifiService: New client listening to asynchronous messages
,11-21 17:14:35.707  3961  5636 W CronetSyncConnectionRcs: Upload content type not set.
,11-21 17:14:36.086   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:14:36.206   931  2955 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 17:14:36.974  5587  5635 I jxcore-log: 2016-11-21 16:14:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-21 17:14:36.974  5587  5635 I jxcore-log: 
,11-21 17:14:36.976  5587  5635 I jxcore-log: 2016-11-21 16:14:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-21 17:14:36.976  5587  5635 I jxcore-log: 
,11-21 17:14:36.981  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-21 17:14:36.982  5587  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 17:14:36.982  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:14:36.982  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:14:36.982  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 17:14:36.982  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 17:14:36.982  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 17:14:36.982  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 17:14:36.982  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 17:14:36.982  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 17:14:36.983  5587  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 17:14:36.986  5587  5635 I jxcore-log: 2016-11-21 16:14:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-21 17:14:36.986  5587  5635 I jxcore-log: 
,11-21 17:14:36.988  5587  5635 I jxcore-log: 2016-11-21 16:14:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-21 17:14:36.988  5587  5635 I jxcore-log: 
,11-21 17:14:37.087   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 17:14:37.243  5587  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 17:14:37.244  5587  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e9a7d2 added. We now have 2 listener(s)
,11-21 17:14:37.244  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 17:14:37.244  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-21 17:14:37.245  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 17:14:37.245  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-21 17:14:37.245  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aa0a3 added. We now have 2 listener(s)
11-21 17:14:37.245  5587  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 17:14:37.245  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 17:14:37.246  5587  5635 D ExecuteNativeTests: Running unit tests
,11-21 17:14:37.247  5587  5635 D BluetoothAdapter: enable(): BT is already enabled..!
11-21 17:14:37.247   931  3820 D WifiService: setWifiEnabled: true pid=5587, uid=10077
,11-21 17:14:37.247   931  3820 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 17:14:39.240   931  2955 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 17:14:40.757   931  5332 D NetlinkSocketObserver: NeighborEvent{elapsedMs=172251, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:14:47.253  5587  5635 I com.test.thalitest.ThaliTestRunner: Running UT
,11-21 17:14:47.320  5587  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 17:14:47.321  5587  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58933d added. We now have 3 listener(s)
,11-21 17:14:47.322  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 17:14:47.322  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-21 17:14:47.322  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-21 17:14:47.322  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-21 17:14:47.322  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c17732 added. We now have 3 listener(s)
11-21 17:14:47.322  5587  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 17:14:47.323  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 17:14:47.328  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-21 17:14:47.328  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-21 17:14:47.329  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:14:47.329  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:14:47.329  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:14:47.330  5587  5635 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-21 17:14:47.330  5587  5635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-21 17:14:47.330  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 17:14:47.330  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:14:47.330  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:14:47.330  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:14:47.331  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-21 17:14:47.332  5587  5635 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-21 17:14:47.334  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-21 17:14:47.336  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-21 17:14:47.336  5587  5635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 17:14:47.338  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:14:47.339  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 17:14:47.354  5587  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 17:14:47.354  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:14:47.354  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:14:47.354  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 17:14:47.354  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 17:14:47.354  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 17:14:47.354  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 17:14:47.354  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 17:14:47.354  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 17:14:47.358  5587  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 17:14:47.358  5587  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
11-21 17:14:47.359  5587  5635 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-21 17:14:47.359  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-21 17:14:47.359  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.359  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.359  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.360  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-21 17:14:47.360  5587  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 17:14:47.360  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 17:14:47.360  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 17:14:47.363  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 17:14:47.363  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 17:14:47.364  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 17:14:47.364  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 17:14:47.364  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 17:14:47.364  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 17:14:47.364  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 17:14:47.364  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:14:47.364  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 17:14:47.365  5587  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 17:14:47.366  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 17:14:47.367  5587  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 17:14:47.367  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 17:14:47.367  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 17:14:47.367  5587  5650 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:14:47.367  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-21 17:14:47.371  4643  4643 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29436]" dev="sockfs" ino=29436 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:14:47.373  5587  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 17:14:47.371  4643  4643 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[29436]" dev="sockfs" ino=29436 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 17:14:47.373  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.373  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 17:14:47.375  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 17:14:47.376  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:14:47.376  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
,11-21 17:14:47.377  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.377  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.377  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 17:14:47.377  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,11-21 17:14:47.377  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:14:47.377  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-21 17:14:47.377  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:47.377  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:47.377  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:47.377  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 17:14:47.378  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:47.378  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.378  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.378  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:47.378  5587  5635 D BluetoothAdapter: STATE_ON
,11-21 17:14:47.381  4628  4875 D BtGatt.GattService: registerClient() - UUID=4567a133-3fb2-4965-ab64-77753cbb08f7
,11-21 17:14:47.382  4628  4705 D BtGatt.GattService: onClientRegistered() - UUID=4567a133-3fb2-4965-ab64-77753cbb08f7, clientIf=5
11-21 17:14:47.382  5587  5597 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 17:14:47.385  4628  4707 D BtGatt.AdvertiseManager: message : 0
,11-21 17:14:47.388  4628  4707 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 17:14:47.408  4628  4705 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 17:14:47.417  4628  4705 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 17:14:47.418  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:47.418  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.418  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 17:14:47.419  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.419  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.419  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.419  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.419  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:47.419  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 17:14:47.421  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-21 17:14:47.421  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:47.422  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.422  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.422  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:47.423  5587  5635 I io.jxcore.node.ConnectionHelper: start: OK
11-21 17:14:47.423  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-21 17:14:47.424  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-21 17:14:47.424  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:47.424  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 17:14:47.424  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.425  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.425  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:47.425  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.425  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-21 17:14:47.425  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 17:14:47.425  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.426  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.426  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 17:14:47.426  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 17:14:47.429  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.429  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 17:14:47.429  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.430  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-21 17:14:47.430  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.430  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 17:14:47.927  5587  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-21 17:14:47.928  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-21 17:14:47.929  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-21 17:14:47.929  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-21 17:14:47.929  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-21 17:14:47.929  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-21 17:14:47.929  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-21 17:14:47.929  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-21 17:14:47.930  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-21 17:14:47.930  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-21 17:14:47.930  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-21 17:14:47.931  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-21 17:14:47.931  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-21 17:14:47.931  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-21 17:14:47.931  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-21 17:14:47.931  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 17:14:47.931  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-21 17:14:47.931  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-21 17:14:47.932  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 17:14:47.932  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-21 17:14:47.932  5587  5587 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 17:14:47.932  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-21 17:14:47.932  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-21 17:14:47.932  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-21 17:14:47.932  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-21 17:14:47.932  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-21 17:14:47.933  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-21 17:14:47.933  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-21 17:14:47.933  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-21 17:14:47.933  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-21 17:14:47.933  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-21 17:14:47.933  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-21 17:14:47.934  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-21 17:14:47.934  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-21 17:14:47.934  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-21 17:14:47.935  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 17:14:47.935  5587  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 17:14:47.935  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 17:14:47.936  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 17:14:47.936  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 17:14:47.937  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 17:14:47.937  5587  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 17:14:47.937  5587  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 17:14:47.937  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 17:14:47.937  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 17:14:47.937  5587  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 17:14:47.938  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 17:14:47.938  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 17:14:47.938  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 17:14:47.939  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 17:14:47.939  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 17:14:47.940  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.941  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.942  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.943  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.946  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:14:47.947  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 17:14:47.949  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:14:47.949  5587  5635 D BluetoothLeScanner: could not find callback wrapper
11-21 17:14:47.949  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 17:14:47.949  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.949  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.949  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.950  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 17:14:47.950  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.951  4628  4707 D BtGatt.AdvertiseManager: message : 1
11-21 17:14:47.952  4628  4707 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 17:14:47.961  4628  4705 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 17:14:47.961  4628  4705 D BtGatt.GattService: Client app is not null!
,11-21 17:14:47.962  4628  4876 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 17:14:47.963  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 17:14:47.963  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.963  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 17:14:47.963  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.963  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.964  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.964  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-21 17:14:47.964  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 17:14:47.965  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 17:14:47.965  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.966  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.966  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:14:47.967  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.967  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.967  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 17:14:47.967  5587  5587 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 17:14:47.967  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 17:14:47.967  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:14:47.967  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:14:47.967  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:14:47.967  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:47.967  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.967  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 17:14:47.967  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-21 17:14:47.968  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.969  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.969  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 17:14:47.969  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.969  5587  5635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 17:14:47.969  5587  5635 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 17:14:47.969  5587  5635 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-21 17:14:47.969  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-21 17:14:47.969  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.969  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.969  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.969  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 17:14:47.969  5587  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 17:14:47.970  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 17:14:47.970  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:14:47.970  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.970  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.970  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.970  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 17:14:47.971  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:14:47.971  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:14:47.971  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 17:14:47.971  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 17:14:47.971  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 17:14:47.971  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 17:14:47.971  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 17:14:47.971  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:14:47.971  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 17:14:47.971  5587  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 17:14:47.972  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 17:14:47.972  5587  5653 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:14:47.975  5587  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 17:14:47.971  4867  4867 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[27342]" dev="sockfs" ino=27342 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:14:47.974  4867  4867 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[27342]" dev="sockfs" ino=27342 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:14:47.977  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 17:14:47.977  5587  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 17:14:47.977  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 17:14:47.980  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.981  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 17:14:47.981  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 17:14:47.981  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:14:47.982  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-21 17:14:47.984  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.984  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.984  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 17:14:47.984  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 17:14:47.984  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:14:47.984  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-21 17:14:47.984  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:47.984  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:47.984  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.985  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 17:14:47.985  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:47.985  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.985  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.985  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:47.986  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:14:47.988  4628  4875 D BtGatt.GattService: registerClient() - UUID=d060d102-06f5-4886-bb5a-f23e68fffc76
11-21 17:14:47.988  4628  4705 D BtGatt.GattService: onClientRegistered() - UUID=d060d102-06f5-4886-bb5a-f23e68fffc76, clientIf=5
11-21 17:14:47.989  5587  5628 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 17:14:47.990  4628  4707 D BtGatt.AdvertiseManager: message : 0
11-21 17:14:47.992  4628  4707 D BtGatt.AdvertiseManager: starting multi advertising
11-21 17:14:48.000  4628  4705 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-21 17:14:48.005  4628  4705 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-21 17:14:48.006  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 17:14:48.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.006  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:48.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 17:14:48.007  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 17:14:48.007  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.008  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.008  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.009  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.009  5587  5635 I io.jxcore.node.ConnectionHelper: start: OK
11-21 17:14:48.009  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 17:14:48.009  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.009  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:48.009  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 17:14:48.009  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.009  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.009  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:48.009  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.009  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 17:14:48.009  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 17:14:48.009  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.009  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.010  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 17:14:48.010  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.012  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.012  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 17:14:48.012  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.012  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.013  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.013  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 17:14:48.513  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-21 17:14:48.513  5587  5635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 17:14:48.513  5587  5635 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 17:14:48.513  5587  5635 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-21 17:14:48.513  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 17:14:48.514  5587  5635 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-21 17:14:48.514  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-21 17:14:48.514  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.515  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.515  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:48.518  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 17:14:48.518  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 17:14:48.518  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 17:14:48.518  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-21 17:14:48.518  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 17:14:48.518  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 17:14:48.518  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 17:14:48.518  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 17:14:48.518  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 17:14:48.518  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.519  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-21 17:14:48.519  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.520  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.520  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.522  4628  4707 D BtGatt.AdvertiseManager: message : 1
11-21 17:14:48.523  4628  4707 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 17:14:48.535  4628  4705 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 17:14:48.535  4628  4705 D BtGatt.GattService: Client app is not null!
,11-21 17:14:48.537  4628  4875 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 17:14:48.537  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 17:14:48.537  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.538  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-21 17:14:48.538  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.538  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:48.538  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.538  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 17:14:48.538  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:48.538  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.539  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.539  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-21 17:14:48.539  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 17:14:48.539  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:14:48.539  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
,11-21 17:14:48.539  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:48.540  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:48.540  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.540  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 17:14:48.540  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:48.540  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.540  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:48.541  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.542  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:14:48.546  4628  4643 D BtGatt.GattService: registerClient() - UUID=ec187717-c2c1-4de2-9b2d-1b1ab176f917
11-21 17:14:48.547  4628  4705 D BtGatt.GattService: onClientRegistered() - UUID=ec187717-c2c1-4de2-9b2d-1b1ab176f917, clientIf=5
11-21 17:14:48.548  5587  5628 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 17:14:48.551  4628  4707 D BtGatt.AdvertiseManager: message : 0
,11-21 17:14:48.556  4628  4707 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 17:14:48.573  4628  4705 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 17:14:48.582  4628  4705 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 17:14:48.584  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.584  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:48.584  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 17:14:48.584  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.584  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.584  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.584  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.584  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:48.585  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.585  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-21 17:14:48.585  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.585  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:14:48.585  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 17:14:48.585  5587  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-21 17:14:48.585  5587  5635 I io.jxcore.node.ConnectionHelper: start: OK
,11-21 17:14:48.586  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.586  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:48.586  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 17:14:48.586  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-21 17:14:48.586  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.586  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:48.586  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.587  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 17:14:48.587  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 17:14:48.587  5587  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-21 17:14:48.587  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.587  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 17:14:48.587  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.587  5587  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-21 17:14:48.587  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 17:14:48.587  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 17:14:48.587  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 17:14:48.587  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-21 17:14:48.587  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 17:14:48.588  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 17:14:48.588  5587  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 17:14:48.588  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 17:14:48.588  5587  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 17:14:48.588  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 17:14:48.588  5587  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 17:14:48.588  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 17:14:48.588  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 17:14:48.588  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-21 17:14:48.588  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.588  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.588  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.588  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.589  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:14:48.590  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 17:14:48.591  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:14:48.591  5587  5635 D BluetoothLeScanner: could not find callback wrapper
11-21 17:14:48.591  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-21 17:14:48.592  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.592  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.592  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.592  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 17:14:48.592  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.594  4628  4707 D BtGatt.AdvertiseManager: message : 1
,11-21 17:14:48.594  4628  4707 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 17:14:48.603  4628  4705 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 17:14:48.603  4628  4705 D BtGatt.GattService: Client app is not null!
,11-21 17:14:48.604  4628  4643 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 17:14:48.604  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 17:14:48.605  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.605  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-21 17:14:48.605  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.605  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.605  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.605  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 17:14:48.605  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 17:14:48.606  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 17:14:48.606  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:48.608  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.608  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:14:48.608  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.608  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.609  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 17:14:48.610  5587  5587 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 17:14:48.610  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 17:14:48.610  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:14:48.610  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:14:48.610  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:14:48.610  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:48.610  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.610  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 17:14:48.610  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 17:14:48.610  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.611  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.611  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 17:14:48.611  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.612  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-21 17:14:48.612  5587  5635 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-21 17:14:48.612  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.612  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.612  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.612  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.612  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 17:14:48.613  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-21 17:14:48.614  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 17:14:48.615  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,11-21 17:14:48.615  5587  5635 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-21 17:14:48.616  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-21 17:14:48.616  5587  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-21 17:14:48.617  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-21 17:14:48.617  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 17:14:48.617  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:14:48.617  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:14:48.617  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:14:48.617  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 17:14:48.617  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:14:48.617  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:14:48.618  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:14:48.618  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 17:14:48.618  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:14:48.618  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:14:48.618  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 17:14:48.619  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-21 17:14:48.619  5587  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 17:14:48.619  5587  5635 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-21 17:14:48.619  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-21 17:14:48.623  5587  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 17:14:48.623  5587  5635 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-21 17:14:48.623  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-21 17:14:48.623  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-21 17:14:48.623  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-21 17:14:48.623  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-21 17:14:48.624  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-21 17:14:48.625  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-21 17:14:48.625  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-21 17:14:48.625  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-21 17:14:48.625  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-21 17:14:48.625  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-21 17:14:48.625  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-21 17:14:48.625  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-21 17:14:48.625  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-21 17:14:48.625  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-21 17:14:48.625  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-21 17:14:48.625  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-21 17:14:48.625  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-21 17:14:48.625  5587  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-21 17:14:48.626  5587  5635 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-21 17:14:48.626  5587  5635 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-21 17:14:48.626  5587  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 17:14:48.626  5587  5635 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-21 17:14:48.626  5587  5635 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,11-21 17:14:48.626  5587  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 17:14:48.626  5587  5635 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-21 17:14:48.626  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-21 17:14:48.631  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-21 17:14:48.631  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
11-21 17:14:48.631  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-21 17:14:48.632  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,11-21 17:14:48.632  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-21 17:14:48.632  5587  5635 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-21 17:14:48.632  5587  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 17:14:48.633  5587  5635 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-21 17:14:48.633  5587  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 130)
11-21 17:14:48.633  5587  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-21 17:14:48.633  5587  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-21 17:14:48.633  5587  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
11-21 17:14:48.633  5587  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
11-21 17:14:48.633  5587  5657 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-21 17:14:48.633  5587  5657 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 17:14:48.634  4875  4875 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[29440]" dev="sockfs" ino=29440 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 17:14:48.636  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-21 17:14:48.637  5587  5635 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-21 17:14:48.634  4875  4875 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[29440]" dev="sockfs" ino=29440 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 17:14:48.638  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-21 17:14:48.638  5587  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-21 17:14:48.639  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,11-21 17:14:48.639  5587  5635 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-21 17:14:48.639  5587  5635 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-21 17:14:48.639  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 17:14:48.639  5587  5635 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-21 17:14:48.639  5587  5635 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 17:14:48.639  5587  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-21 17:14:48.640  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 17:14:48.640  5587  5635 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-21 17:14:48.640  5587  5635 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-21 17:14:48.640  5587  5635 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-21 17:14:48.640  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 17:14:48.640  5587  5635 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-21 17:14:48.640  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-21 17:14:48.641  5587  5635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 17:14:48.641  5587  5635 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 17:14:48.641  5587  5635 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-21 17:14:48.641  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,11-21 17:14:48.641  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.641  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.642  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.642  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 17:14:48.642  5587  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 17:14:48.642  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 17:14:48.642  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:14:48.642  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 17:14:48.643  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 17:14:48.643  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 17:14:48.643  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 17:14:48.643  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 17:14:48.643  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 17:14:48.643  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 17:14:48.643  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:14:48.643  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 17:14:48.644  5587  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 17:14:48.645  5587  5658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:14:48.647  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-21 17:14:48.647  5587  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 17:14:48.647  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 17:14:48.647  4648  4648 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32938]" dev="sockfs" ino=32938 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 17:14:48.651  4648  4648 W Binder_2: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32938]" dev="sockfs" ino=32938 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:14:48.651  5587  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 17:14:48.651  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:48.651  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 17:14:48.652  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 17:14:48.652  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:14:48.652  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-21 17:14:48.655  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.655  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.655  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 17:14:48.655  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 17:14:48.655  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:14:48.655  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-21 17:14:48.655  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:48.655  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:48.655  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.655  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 17:14:48.655  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:48.655  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.655  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.656  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.656  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:14:48.658  4628  4875 D BtGatt.GattService: registerClient() - UUID=32be878a-c71f-4d80-8683-7d608b4c28a2
11-21 17:14:48.658  4628  4705 D BtGatt.GattService: onClientRegistered() - UUID=32be878a-c71f-4d80-8683-7d608b4c28a2, clientIf=5
11-21 17:14:48.659  5587  5598 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 17:14:48.660  4628  4707 D BtGatt.AdvertiseManager: message : 0
11-21 17:14:48.662  4628  4707 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 17:14:48.671  4628  4705 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 17:14:48.676  4628  4705 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 17:14:48.677  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.677  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.677  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 17:14:48.677  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:48.677  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.677  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.677  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:48.677  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.677  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 17:14:48.679  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 17:14:48.679  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.680  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.680  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.681  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:48.681  5587  5635 I io.jxcore.node.ConnectionHelper: start: OK
11-21 17:14:48.681  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 17:14:48.681  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.681  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:48.681  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 17:14:48.681  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.681  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.681  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:48.681  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.682  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 17:14:48.682  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 17:14:48.682  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.682  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.682  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 17:14:48.682  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 17:14:48.684  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.684  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 17:14:48.684  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.684  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.684  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:14:48.684  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 17:14:49.182  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-21 17:14:49.183  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 17:14:49.183  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 17:14:49.183  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 17:14:49.183  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-21 17:14:49.183  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 17:14:49.184  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 17:14:49.184  5587  5658 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 17:14:49.184  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-21 17:14:49.184  5587  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 17:14:49.184  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-21 17:14:49.184  5587  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 17:14:49.185  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 17:14:49.185  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 17:14:49.185  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 17:14:49.186  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:14:49.187  5587  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58933d removed from the list
11-21 17:14:49.188  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 17:14:49.188  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 17:14:49.188  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 17:14:49.188  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 17:14:49.189  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.189  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.189  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.189  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.191  5587  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 130
11-21 17:14:49.191  5587  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-21 17:14:49.191  5587  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 130)
,11-21 17:14:49.192  5587  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 130)
11-21 17:14:49.192  5587  5657 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-21 17:14:49.192  4628  4865 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
11-21 17:14:49.193  5587  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
,11-21 17:14:49.193  5587  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 130)
,11-21 17:14:49.193  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:14:49.193  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 17:14:49.196  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:14:49.196  5587  5635 D BluetoothLeScanner: could not find callback wrapper
11-21 17:14:49.196  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 17:14:49.199  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.200  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.200  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.200  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-21 17:14:49.200  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.202  4628  4707 D BtGatt.AdvertiseManager: message : 1
11-21 17:14:49.203  4628  4707 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 17:14:49.211  4628  4705 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 17:14:49.211  4628  4705 D BtGatt.GattService: Client app is not null!
,11-21 17:14:49.212  4628  4643 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 17:14:49.212  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 17:14:49.213  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.213  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 17:14:49.213  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.213  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.213  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.213  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 17:14:49.213  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 17:14:49.214  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 17:14:49.214  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.215  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.215  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:14:49.216  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:49.216  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:49.216  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c17732 removed from the list
11-21 17:14:49.216  5587  5635 D io.jxcore.node.ConnectivityMonitor: stop
11-21 17:14:49.216  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 17:14:49.216  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:14:49.216  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:14:49.216  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:49.216  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:14:49.217  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 17:14:49.217  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 17:14:49.217  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:14:49.218  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 17:14:49.218  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 17:14:49.218  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:14:49.219  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:14:49.220  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:49.220  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:49.220  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:14:49.220  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 17:14:49.277   931  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:14:49.721  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 17:14:51.062   931  5332 D NetlinkSocketObserver: NeighborEvent{elapsedMs=182557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:14:53.764  4628  4852 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-21 17:14:53.764  4628  4852 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,11-21 17:14:54.220  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-21 17:14:54.222  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-21 17:14:54.222  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 17:14:54.223  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 17:14:54.229  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 17:14:54.230  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 17:14:54.230  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 17:14:54.230  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 17:14:54.231  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 17:14:54.231  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-21 17:14:54.231  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 17:14:54.231  5587  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 17:14:54.233  5587  5660 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:14:54.233  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-21 17:14:54.236  5587  5635 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-21 17:14:54.237  5587  5635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-21 17:14:54.237  5587  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 17:14:54.237  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-21 17:14:54.234  4643  4643 W Binder_1: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[34025]" dev="sockfs" ino=34025 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 17:14:54.234  4643  4643 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[34025]" dev="sockfs" ino=34025 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 17:14:54.237  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-21 17:14:54.237  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 17:14:54.239  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-21 17:14:54.249  5587  5635 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-21 17:14:54.250  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 17:14:54.250  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-21 17:14:54.250  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 17:14:54.250  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 17:14:54.250  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 17:14:54.250  5587  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 17:14:54.250  5587  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 17:14:54.250  5587  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 17:14:54.250  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 17:14:54.251  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:14:54.251  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 17:14:54.251  5587  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58933d not in the list
,11-21 17:14:54.251  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:14:54.251  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 17:14:54.251  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 17:14:54.251  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 17:14:54.251  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 17:14:54.251  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 17:14:54.252  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:54.253  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:54.253  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:14:54.253  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:54.253  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:54.253  5587  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c17732 not in the list
11-21 17:14:54.254  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:14:54.254  5587  5635 D io.jxcore.node.ConnectivityMonitor: stop
11-21 17:14:54.254  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:14:54.254  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:14:54.256  5587  5635 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-21 17:14:54.256  5587  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-21 17:14:54.256  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 17:14:54.256  5587  5635 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-21 17:14:54.256  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 17:14:54.256  5587  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-21 17:14:54.256  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 17:14:54.257  5587  5635 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-21 17:14:54.257  5587  5635 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-21 17:14:54.258  5587  5635 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-21 17:14:54.258  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 17:14:54.259  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-21 17:14:54.259  5587  5635 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-21 17:14:54.259  5587  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-21 17:14:54.259  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 17:14:54.260  5587  5635 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-21 17:14:54.260  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 17:14:54.260  5587  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-21 17:14:54.260  5587  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-21 17:14:54.260  5587  5635 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-21 17:14:54.260  5587  5635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-21 17:14:54.260  5587  5635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-21 17:14:54.261  5587  5635 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-21 17:14:54.261  5587  5635 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-21 17:14:54.261  5587  5635 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-21 17:14:54.261  5587  5635 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-21 17:14:54.261  5587  5635 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-21 17:14:54.262  5587  5635 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-21 17:14:54.262  5587  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 17:14:54.262  5587  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a40f730 added. We now have 3 listener(s)
11-21 17:14:54.263  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:14:54.263  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 17:14:54.263  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 17:14:54.264  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 17:14:54.264  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81a0fa9 added. We now have 3 listener(s)
,11-21 17:14:54.264  5587  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 17:14:54.264  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 17:14:54.268  5587  5635 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 17:14:54.268   931  3603 D WifiService: setWifiEnabled: true pid=5587, uid=10077
11-21 17:14:54.268   931  3603 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 17:14:54.270  5587  5635 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-21 17:14:54.273  5587  5635 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-21 17:14:54.274  5587  5635 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-21 17:14:54.275  5587  5635 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-21 17:14:54.280  5587  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 17:14:54.280  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:14:54.280  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:14:54.280  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 17:14:54.280  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 17:14:54.280  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 17:14:54.280  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 17:14:54.280  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 17:14:54.280  5587  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 17:14:54.281  4628  4701 D BluetoothAdapterState: Current state: ON, message: 23
,11-21 17:14:54.282  4628  4701 D BluetoothAdapterProperties: Setting state to 13
11-21 17:14:54.282  4628  4701 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-21 17:14:54.282  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
11-21 17:14:54.282  4628  4701 D BluetoothAdapterProperties: onBluetoothDisable()
11-21 17:14:54.282  5587  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 17:14:54.283  4628  4701 I BluetoothAdapterState: Entering PendingCommandState
,11-21 17:14:54.284  4628  4705 D BluetoothAdapterProperties: Scan Mode:20
11-21 17:14:54.285  4628  4701 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-21 17:14:54.286  4628  4628 D BluetoothMapService: onReceive
11-21 17:14:54.287  4628  4628 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 17:14:54.287  4628  4628 D BluetoothMapService: STATE_TURNING_OFF
11-21 17:14:54.288  4628  4628 D BluetoothMapService: MAP Service closeService in
11-21 17:14:54.288  4628  4628 D BluetoothMapMasInstance0: MAP Service shutdown
11-21 17:14:54.289  4628  4628 D ObexServerSockets0: shutdown(block = true)
11-21 17:14:54.289  4628  4878 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-21 17:14:54.290  4628  4628 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-21 17:14:54.290  4628  4628 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-21 17:14:54.290  4628  4865 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-21 17:14:54.290  4628  4879 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-21 17:14:54.291  4628  4628 I BtOppRfcommListener: stopping Accept Thread
11-21 17:14:54.291  4628  5263 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-21 17:14:54.291  4628  5263 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-21 17:14:54.301   931   944 I ActivityManager: Start proc 5663:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-21 17:14:54.304  4628  4628 D HeadsetService: Received stop request...Stopping profile...
,11-21 17:14:54.306   931   931 D BluetoothHeadset: Proxy object disconnected
,11-21 17:14:54.307   931   931 D BluetoothHeadset: Proxy object disconnected
,11-21 17:14:54.307  3123  3997 D BluetoothHeadset: Proxy object disconnected
11-21 17:14:54.307  3790  4011 D BluetoothHeadset: Proxy object disconnected
11-21 17:14:54.308   931   931 D BluetoothHeadset: Proxy object disconnected
11-21 17:14:54.309  4628  4628 D A2dpService: Received stop request...Stopping profile...
11-21 17:14:54.309  4628  4870 D A2dpStateMachine: Exit Disconnected: -1
11-21 17:14:54.310  3123  3123 D HeadsetProfile: Bluetooth service disconnected
11-21 17:14:54.311   931   931 D BluetoothA2dp: Proxy object disconnected
11-21 17:14:54.311  3123  3123 D BluetoothA2dp: Proxy object disconnected
,11-21 17:14:54.311  4628  4628 V BluetoothAdapterState: isTurningOff()=true
11-21 17:14:54.311  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-21 17:14:54.312  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:54.312  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:54.312  4628  4628 D HidService: Received stop request...Stopping profile...
11-21 17:14:54.313  4628  4628 D HidService: Stopping Bluetooth HidService
,11-21 17:14:54.314  3123  3123 D BluetoothInputDevice: Proxy object disconnected
11-21 17:14:54.314  3123  3123 D HidProfile: Bluetooth service disconnected
,11-21 17:14:54.316  4628  4628 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-21 17:14:54.316  4628  4628 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-21 17:14:54.317  4628  4852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 17:14:54.317  4628  4852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 17:14:54.317  4628  4852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 17:14:54.317  4628  4705 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-21 17:14:54.317  4628  4628 D HealthService: Received stop request...Stopping profile...
11-21 17:14:54.317  4628  4705 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-21 17:14:54.318  4628  4628 D PanService: Received stop request...Stopping profile...
11-21 17:14:54.319  3123  3123 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-21 17:14:54.319  3123  3123 D PanProfile: Bluetooth service disconnected
,11-21 17:14:54.320  4628  4628 V BluetoothAdapterState: isTurningOff()=true
,11-21 17:14:54.320  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-21 17:14:54.320  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:54.320  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:54.320  4628  4628 D BluetoothMapService: Received stop request...Stopping profile...
11-21 17:14:54.321  4628  4628 D BluetoothMapService: stop()
11-21 17:14:54.322  4628  4628 D BluetoothMapAppObserver: deinitObservers()
11-21 17:14:54.322  4628  4628 D BluetoothMapAppObserver: removeReceiver()
11-21 17:14:54.325  3123  3123 D BluetoothMap: Proxy object disconnected
11-21 17:14:54.326  3123  3123 D MapProfile: Bluetooth service disconnected
11-21 17:14:54.326  4628  4852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 17:14:54.327  4628  4628 V BluetoothAdapterState: isTurningOff()=true
,11-21 17:14:54.327  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-21 17:14:54.327  4628  4852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 17:14:54.327  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:54.327  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:54.327  4628  4705 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-21 17:14:54.327  4628  4628 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-21 17:14:54.327  4628  4852 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-21 17:14:54.327  4628  4852 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-21 17:14:54.327  4628  4628 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-21 17:14:54.327  4628  4852 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-21 17:14:54.327  4628  4852 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-21 17:14:54.327  4628  4705 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-21 17:14:54.327  4628  4628 V BluetoothAdapterState: isTurningOff()=true
11-21 17:14:54.327  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-21 17:14:54.328  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:54.328  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 17:14:54.328  4628  4628 D SapService: Received stop request...Stopping profile...
,11-21 17:14:54.329  4628  4628 V SapService: stop()
11-21 17:14:54.330  4628  4628 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-21 17:14:54.330  4628  4705 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-21 17:14:54.330  4628  4628 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-21 17:14:54.330  4628  4628 V BluetoothAdapterState: isTurningOff()=true
11-21 17:14:54.330  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-21 17:14:54.331  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:54.331  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:54.331  4628  4628 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-21 17:14:54.331  4628  4628 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-21 17:14:54.331  4628  4628 D BluetoothMapService: MAP Service closeService in
11-21 17:14:54.332  4628  4628 V BluetoothAdapterState: isTurningOff()=true
11-21 17:14:54.332  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-21 17:14:54.332  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
,11-21 17:14:54.332  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:54.332  4628  4628 D BluetoothMapService: cleanup()
11-21 17:14:54.332  4628  4628 D BluetoothMapService: MAP Service closeService in
11-21 17:14:54.332  4628  4628 V BluetoothAdapterState: isTurningOff()=true
11-21 17:14:54.332  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-21 17:14:54.332  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:54.332  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:54.332  4628  4701 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-21 17:14:54.333  4628  4701 D BluetoothAdapterProperties: Setting state to 15
11-21 17:14:54.333  4628  4701 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-21 17:14:54.333  4628  4701 I BluetoothAdapterState: Entering BleOnState
,11-21 17:14:54.338  3123  3137 D BluetoothPan: onBluetoothStateChange on: false
11-21 17:14:54.338  3123  3134 D BluetoothPbap: onBluetoothStateChange: up=false
11-21 17:14:54.340  3123  3997 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-21 17:14:54.343  3123  3137 D BluetoothMap: onBluetoothStateChange: up=false
,11-21 17:14:54.344   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-21 17:14:54.344   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-21 17:14:54.344  3123  3134 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 17:14:54.344  3790  4012 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 17:14:54.345   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 17:14:54.345   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
11-21 17:14:54.345  3123  3997 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-21 17:14:54.347  4628  4701 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-21 17:14:54.347  4628  4701 D BluetoothAdapterProperties: Setting state to 16
11-21 17:14:54.347  4628  4701 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-21 17:14:54.348  4628  4701 D BluetoothAdapterProperties: onBleDisable
11-21 17:14:54.348  4628  4701 I BluetoothAdapterState: Entering PendingCommandState
,11-21 17:14:54.348  4628  4702 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-21 17:14:54.348  4628  4705 D BluetoothAdapterProperties: Scan Mode:20
11-21 17:14:54.349  4628  4852 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-21 17:14:54.349  4628  4852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 17:14:54.358  5663  5663 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-21 17:14:54.371  5663  5663 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 17:14:54.377   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e94e95f:true
,11-21 17:14:54.378  3587  3587 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 17:14:54.390   931  4041 I ActivityManager: Start proc 5675:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-21 17:14:54.402  5663  5663 D LocalBluetoothProfileManager: Adding local MAP profile
,11-21 17:14:54.405  5663  5663 D BluetoothMap: Create BluetoothMap proxy object
,11-21 17:14:54.419  5663  5663 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-21 17:14:54.428  5675  5675 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-21 17:14:54.432  5663  5663 D DockEventReceiver: finishStartingService: stopping service
,11-21 17:14:54.440   931  3782 I ActivityManager: Killing 5362:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-21 17:14:54.554  4628  4705 I bt_hci  : shut_down
,11-21 17:14:54.559  4628  4709 D bt_hwcfg: hw_epilog_process
,11-21 17:14:54.559  4628  4709 I bt_vendor: low_power_mode_cb
,11-21 17:14:54.562  4628  4709 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-21 17:14:54.562  4628  4709 I bt_vendor: epilog_cb
11-21 17:14:54.562  4628  4709 I bt_hci  : epilog_finished_callback
,11-21 17:14:54.565  4628  4705 I bt_hci_h4: hal_close
,11-21 17:14:54.565  4628  4705 I bt_userial_vendor: device fd = 54 close
,11-21 17:14:54.646  5675  5675 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.io.File.exists(File.java:361)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-21 17:14:54.646  5675  5675 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 17:14:54.646  5675  5675 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 17:14:54.646  5675  5675 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.e.b(PG:170)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 17:14:54.646  5675  5675 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.k.d(PG:583)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.e.b(PG:170)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 17:14:54.646  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 17:14:54.647  5675  5675 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at java.io.File.exists(File.java:361)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 17:14:54.647  5675  5675 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at java.io.File.exists(File.java:361)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 17:14:54.647  5675  5675 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 17:14:54.647  5675  5675 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 17:14:54.650  5663  5663 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-21 17:14:54.657  3587  3587 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 17:14:54.662  5663  5663 D DockEventReceiver: finishStartingService: stopping service
11-21 17:14:54.664   931  3782 I ActivityManager: Killing 5377:com.android.chrome/u0a39 (adj 15): empty #17
,11-21 17:14:54.693  4628  4702 D bt_stack_manager: event_shut_down_stack finished.
11-21 17:14:54.694  4628  4701 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-21 17:14:54.695  4628  4701 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-21 17:14:54.695  4628  4628 D BtGatt.DebugUtils: handleDebugAction() action=null
11-21 17:14:54.696  4628  4628 D BtGatt.GattService: Received stop request...Stopping profile...
11-21 17:14:54.696  4628  4628 D BtGatt.GattService: stop()
11-21 17:14:54.696  4628  4628 D BtGatt.AdvertiseManager: advertise clients cleared
11-21 17:14:54.698  4628  4628 V BluetoothAdapterState: isTurningOff()=false
11-21 17:14:54.698  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-21 17:14:54.698  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:54.698  4628  4628 V BluetoothAdapterState: isBleTurningOff()=true
11-21 17:14:54.699  4628  4701 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-21 17:14:54.699  4628  4701 D BluetoothAdapterProperties: Setting state to 10
11-21 17:14:54.699  4628  4701 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-21 17:14:54.699  4628  4701 I BluetoothAdapterState: Entering OffState
11-21 17:14:54.700   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-21 17:14:54.706  4628  4628 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-21 17:14:54.706  4628  4628 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-21 17:14:54.706  4628  4628 I BluetoothServiceJni: cleanupNative: return from cleanup
11-21 17:14:54.707  4628  4702 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-21 17:14:54.715  4628  4628 I art     : System.exit called, status: 0
11-21 17:14:54.715  4628  4628 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-21 17:14:54.742   931   941 I ActivityManager: Process com.android.bluetooth (pid 4628) has died
,11-21 17:14:54.754  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 17:14:54.782  5587  5661 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-21 17:14:54.782  5587  5661 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 17:14:54.782  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:14:54.782  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
11-21 17:14:54.782  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 17:14:54.782  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-21 17:14:54.782  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 17:14:54.782  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 17:14:54.782  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 17:14:54.782  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 17:14:54.782  5587  5661 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-21 17:14:54.782  5587  5661 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 17:14:54.786  5587  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 17:14:54.795   931   948 I ActivityManager: Start proc 5707:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-21 17:14:54.853  5675  5701 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-21 17:14:54.858  5707  5707 D AdapterServiceConfig: Adding HeadsetService
,11-21 17:14:54.859  5707  5707 D AdapterServiceConfig: Adding A2dpService
11-21 17:14:54.859  5707  5707 D AdapterServiceConfig: Adding HidService
11-21 17:14:54.859  5707  5707 D AdapterServiceConfig: Adding HealthService
,11-21 17:14:54.859  5707  5707 D AdapterServiceConfig: Adding PanService
11-21 17:14:54.859  5707  5707 D AdapterServiceConfig: Adding GattService
11-21 17:14:54.859  5707  5707 D AdapterServiceConfig: Adding BluetoothMapService
,11-21 17:14:54.859  5707  5707 D AdapterServiceConfig: Adding SapService
,11-21 17:14:54.869   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bd91a74:true
,11-21 17:14:54.870  5707  5707 D BluetoothAdapterState: make() - Creating AdapterState
,11-21 17:14:54.872   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f39b812:true
,11-21 17:14:54.872  5707  5707 I bt_bluedroid: init
,11-21 17:14:54.873  5707  5720 I BluetoothAdapterState: Entering OffState
,11-21 17:14:54.874  5707  5721 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-21 17:14:54.875  5707  5721 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-21 17:14:54.875  5707  5721 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-21 17:14:54.875  5707  5721 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-21 17:14:54.875  5707  5707 I bt_bluedroid: get_profile_interface socket
,11-21 17:14:54.877  5707  5707 I bt_bluedroid: get_profile_interface sdp
11-21 17:14:54.877  5707  5724 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-21 17:14:54.878  5707  5724 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-21 17:14:54.881  5707  5718 I bt_bluedroid: config_hci_snoop_log
,11-21 17:14:54.882   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-21 17:14:54.886  5707  5720 D BluetoothAdapterState: Current state: OFF, message: 0
,11-21 17:14:54.886  5707  5720 D BluetoothAdapterProperties: Setting state to 14
11-21 17:14:54.886  5707  5720 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-21 17:14:54.887  5707  5720 D BluetoothBondStateMachine: make
,11-21 17:14:54.889  5707  5726 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-21 17:14:54.891  5707  5720 I BluetoothAdapterState: Entering PendingCommandState
,11-21 17:14:54.892  5707  5707 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-21 17:14:54.893  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2341961
11-21 17:14:54.894  5707  5707 D BtGatt.DebugUtils: handleDebugAction() action=null
11-21 17:14:54.894  5707  5707 D BtGatt.GattService: Received start request. Starting profile...
,11-21 17:14:54.895  5707  5707 D BtGatt.GattService: start()
11-21 17:14:54.895  5707  5707 I bt_bluedroid: get_profile_interface gatt
,11-21 17:14:54.895  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2341961
,11-21 17:14:54.895  5707  5707 D BtGatt.AdvertiseManager: advertise manager created
,11-21 17:14:54.899  5707  5707 V BluetoothAdapterState: isTurningOff()=false
,11-21 17:14:54.899  5707  5707 V BluetoothAdapterState: isTurningOn()=false
11-21 17:14:54.899  5707  5707 V BluetoothAdapterState: isBleTurningOn()=true
11-21 17:14:54.899  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:54.900  5707  5720 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-21 17:14:54.901  5707  5720 I bt_bluedroid: bt_bluedroid
11-21 17:14:54.901  5707  5721 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-21 17:14:54.901  5707  5721 I bt_hci  : start_up
,11-21 17:14:54.906  5707  5721 I bt_vendor: alloc value 0xf3d35871
,11-21 17:14:54.906  5707  5721 I bt_vendor: init
11-21 17:14:54.906  5707  5721 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-21 17:14:54.906  5707  5721 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-21 17:14:55.015  5707  5721 D bt_hci  : start_up starting async portion
11-21 17:14:55.015  5707  5729 I bt_hci  : event_finish_startup
11-21 17:14:55.015  5707  5729 I bt_hci_h4: hal_open
11-21 17:14:55.015  5707  5729 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-21 17:14:55.014  5730  5730 W irq/448-msm_hs_: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-21 17:14:55.017  5707  5729 I bt_userial_vendor: device fd = 54 open
,11-21 17:14:55.030  5707  5729 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-21 17:14:55.032  5707  5729 D bt_hwcfg: Chipset BCM4358A3
,11-21 17:14:55.032  5707  5729 D bt_hwcfg: Target name = [BCM4358A3]
11-21 17:14:55.032  5707  5729 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-21 17:14:55.290  5707  5720 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-21 17:14:55.414  5707  5729 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-21 17:14:55.415  5707  5729 D bt_hwcfg: Settlement delay -- 100 ms
11-21 17:14:55.415  5707  5729 I bt_hwcfg: Setting fw settlement delay to 100 
,11-21 17:14:55.540  5707  5729 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-21 17:14:55.540  5707  5729 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-21 17:14:55.542  5707  5729 I bt_hwcfg: vendor lib fwcfg completed
,11-21 17:14:55.542  5707  5729 I bt_vendor: firmware callback
11-21 17:14:55.542  5707  5729 I bt_hci  : firmware_config_callback
,11-21 17:14:55.551  5707  5732 I bt_btu  : btu_task pending for preload complete event
11-21 17:14:55.551  5707  5732 I bt_btu_task: Bluetooth chip preload is complete
11-21 17:14:55.551  5707  5732 I bt_btu  : btu_task received preload complete event
,11-21 17:14:55.559  5707  5732 I         : BTE_InitTraceLevels -- TRC_HCI
,11-21 17:14:55.559  5707  5732 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-21 17:14:55.559  5707  5732 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-21 17:14:55.559  5707  5732 I         : BTE_InitTraceLevels -- TRC_AVDT
11-21 17:14:55.559  5707  5732 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-21 17:14:55.559  5707  5732 I         : BTE_InitTraceLevels -- TRC_A2D
11-21 17:14:55.559  5707  5732 I         : BTE_InitTraceLevels -- TRC_BNEP
11-21 17:14:55.560  5707  5732 I         : BTE_InitTraceLevels -- TRC_BTM
11-21 17:14:55.560  5707  5732 I         : BTE_InitTraceLevels -- TRC_GAP
,11-21 17:14:55.560  5707  5732 I         : BTE_InitTraceLevels -- TRC_PAN
11-21 17:14:55.560  5707  5732 I         : BTE_InitTraceLevels -- TRC_SDP
11-21 17:14:55.560  5707  5732 I         : BTE_InitTraceLevels -- TRC_GATT
11-21 17:14:55.560  5707  5732 I         : BTE_InitTraceLevels -- TRC_SMP
,11-21 17:14:55.560  5707  5732 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-21 17:14:55.560  5707  5732 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-21 17:14:55.645  5707  5732 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cb3549
11-21 17:14:55.646  5707  5732 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cb3549 
,11-21 17:14:55.663  5707  5724 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-21 17:14:55.665  5707  5724 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-21 17:14:55.665  5707  5724 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-21 17:14:55.668  5707  5724 D BluetoothAdapterProperties: Name is: Nexus 6P
11-21 17:14:55.670  5707  5724 D BluetoothAdapterProperties: Scan Mode:20
11-21 17:14:55.670  5707  5724 D BluetoothAdapterProperties: Discoverable Timeout:120
11-21 17:14:55.670  5707  5724 D bt_hci  : do_postload posting postload work item
11-21 17:14:55.671  5707  5729 I bt_hci  : event_postload
,11-21 17:14:55.671  5707  5729 I bt_vendor: sco_config_cb
11-21 17:14:55.671  5707  5729 I bt_hci  : sco_config_callback postload finished.
11-21 17:14:55.673  5707  5724 D bt_bte_conf: Device ID record 1 : primary
11-21 17:14:55.673  5707  5724 D bt_bte_conf:   vendorId            = 000f
11-21 17:14:55.673  5707  5724 D bt_bte_conf:   vendorIdSource      = 0001
11-21 17:14:55.673  5707  5724 D bt_bte_conf:   product             = 1200
11-21 17:14:55.674  5707  5724 D bt_bte_conf:   version             = 1436
11-21 17:14:55.674  5707  5724 D bt_bte_conf:   clientExecutableURL = 
11-21 17:14:55.674  5707  5724 D bt_bte_conf:   serviceDescription  = 
11-21 17:14:55.674  5707  5724 D bt_bte_conf:   documentationURL    = 
11-21 17:14:55.674  5707  5724 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-21 17:14:55.674  5707  5721 D bt_stack_manager: event_start_up_stack finished
11-21 17:14:55.675  5707  5720 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-21 17:14:55.676  5707  5720 D BluetoothAdapterProperties: Setting state to 15
,11-21 17:14:55.676  5707  5720 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-21 17:14:55.677  5707  5720 I BluetoothAdapterState: Entering BleOnState
,11-21 17:14:55.682  5707  5729 I bt_vendor: low_power_mode_cb
,11-21 17:14:55.683  5707  5720 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-21 17:14:55.683  5707  5720 D BluetoothAdapterProperties: Setting state to 11
11-21 17:14:55.683  5707  5720 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-21 17:14:55.689  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2341961
,11-21 17:14:55.693  5707  5707 D HeadsetService: Received start request. Starting profile...
,11-21 17:14:55.696  5707  5707 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-21 17:14:55.697  5707  5707 D HeadsetStateMachine: make
,11-21 17:14:55.710  5707  5720 I BluetoothAdapterState: Entering PendingCommandState
,11-21 17:14:55.711  5707  5707 D HeadsetStateMachine: max_hf_connections = 1
,11-21 17:14:55.711  5707  5707 I bt_bluedroid: get_profile_interface handsfree
,11-21 17:14:55.711  5707  5724 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-21 17:14:55.711  5707  5724 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-21 17:14:55.715  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2341961
,11-21 17:14:55.715  5707  5707 D A2dpService: Received start request. Starting profile...
11-21 17:14:55.716  5707  5707 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-21 17:14:55.717  5707  5707 I bt_bluedroid: get_profile_interface avrcp
,11-21 17:14:55.723  5707  5707 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-21 17:14:55.723  5707  5707 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-21 17:14:55.723  5707  5707 D A2dpStateMachine: make
,11-21 17:14:55.725  5707  5707 I bt_bluedroid: get_profile_interface a2dp
,11-21 17:14:55.726  5707  5724 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-21 17:14:55.727  5707  5739 D A2dpStateMachine: Enter Disconnected: -2
,11-21 17:14:55.727  5707  5707 I BluetoothHidServiceJni: classInitNative: succeeds
,11-21 17:14:55.728  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2341961
,11-21 17:14:55.730  5707  5707 D HidService: Received start request. Starting profile...
,11-21 17:14:55.730  5707  5707 I bt_bluedroid: get_profile_interface hidhost
11-21 17:14:55.730  5707  5707 D HidService: setHidService(): set to: null
,11-21 17:14:55.730  5707  5724 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c9456d
11-21 17:14:55.731  5707  5707 I BluetoothHealthServiceJni: classInitNative: succeeds
11-21 17:14:55.731  5707  5724 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-21 17:14:55.732  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2341961
11-21 17:14:55.732  5707  5707 D HealthService: Received start request. Starting profile...
,11-21 17:14:55.733  5663  5663 D BluetoothInputDevice: Proxy object connected
11-21 17:14:55.733  5663  5663 D HidProfile: Bluetooth service connected
,11-21 17:14:55.733  5707  5707 I bt_bluedroid: get_profile_interface health
11-21 17:14:55.734  5707  5707 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-21 17:14:55.735  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2341961
11-21 17:14:55.736  5663  5663 D BluetoothPan: BluetoothPAN Proxy object connected
,11-21 17:14:55.736  5707  5707 D PanService: Received start request. Starting profile...
,11-21 17:14:55.736  5707  5707 D BluetoothPanServiceJni: initializeNative(L110): pan
11-21 17:14:55.736  5707  5707 I bt_bluedroid: get_profile_interface pan
11-21 17:14:55.736  5663  5663 D PanProfile: Bluetooth service connected
,11-21 17:14:55.737  5707  5724 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-21 17:14:55.739  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2341961
11-21 17:14:55.740  5663  5663 D BluetoothMap: Proxy object connected
11-21 17:14:55.740  5663  5663 D MapProfile: Bluetooth service connected
11-21 17:14:55.741  5663  5663 D BluetoothMap: getConnectedDevices()
11-21 17:14:55.742  5707  5707 D BluetoothMapService: Received start request. Starting profile...
11-21 17:14:55.742  5707  5707 D BluetoothMapService: start()
11-21 17:14:55.745  5707  5707 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-21 17:14:55.745  5707  5707 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-21 17:14:55.746  5707  5707 D BluetoothMapAppObserver: createReceiver()
11-21 17:14:55.747  5707  5707 D BluetoothMapAppObserver: initObservers()
11-21 17:14:55.747  5707  5707 D BluetoothMapAppObserver: getEnabledAccountItems()
11-21 17:14:55.753  5707  5707 V SapService: SapBinder()
,11-21 17:14:55.753  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2341961
11-21 17:14:55.753  5707  5707 D SapService: Received start request. Starting profile...
11-21 17:14:55.753  5707  5707 V SapService: start()
,11-21 17:14:55.757  5707  5707 V BluetoothAdapterState: isTurningOff()=false
11-21 17:14:55.757  5707  5707 V BluetoothAdapterState: isTurningOn()=true
11-21 17:14:55.757  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:55.757  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:55.757  5707  5707 V BluetoothAdapterState: isTurningOff()=false
11-21 17:14:55.757  5707  5707 V BluetoothAdapterState: isTurningOn()=true
11-21 17:14:55.757  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:55.757  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:55.758  5707  5737 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isTurningOff()=false
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isTurningOn()=true
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isTurningOff()=false
,11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isTurningOn()=true
11-21 17:14:55.758  3587  3587 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isTurningOff()=false
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isTurningOn()=true
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isTurningOff()=false
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isTurningOn()=true
11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
,11-21 17:14:55.758  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:55.759  5707  5707 V BluetoothAdapterState: isTurningOff()=false
11-21 17:14:55.759  5707  5707 V BluetoothAdapterState: isTurningOn()=true
11-21 17:14:55.759  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
11-21 17:14:55.759  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
11-21 17:14:55.759  5707  5720 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-21 17:14:55.760  5707  5720 D BluetoothAdapterProperties: ScanMode =  20
11-21 17:14:55.760  5707  5720 D BluetoothAdapterProperties: State =  11
11-21 17:14:55.760  5663  5663 D BluetoothMap: Bluetooth is Not enabled
11-21 17:14:55.762  5707  5724 D BluetoothAdapterProperties: Scan Mode:21
11-21 17:14:55.762  5707  5720 D BluetoothAdapterProperties: Setting state to 12
11-21 17:14:55.762  5707  5720 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-21 17:14:55.762  5707  5724 D BluetoothAdapterProperties: Discoverable Timeout:120
11-21 17:14:55.762  5707  5720 I BluetoothAdapterState: Entering OnState
11-21 17:14:55.762  3123  3134 D BluetoothPan: onBluetoothStateChange on: true
11-21 17:14:55.764  3123  3123 D BluetoothPan: BluetoothPAN Proxy object connected
11-21 17:14:55.764  3123  3134 D BluetoothPbap: onBluetoothStateChange: up=true
11-21 17:14:55.764  3123  3123 D PanProfile: Bluetooth service connected
11-21 17:14:55.766  3123  3137 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-21 17:14:55.768  5663  5674 D BluetoothPbap: onBluetoothStateChange: up=true
,11-21 17:14:55.770  3123  3123 D BluetoothA2dp: Proxy object connected
11-21 17:14:55.770  3123  3134 D BluetoothMap: onBluetoothStateChange: up=true
11-21 17:14:55.771  5663  5673 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-21 17:14:55.772  3123  3123 D BluetoothMap: Proxy object connected
11-21 17:14:55.772  3123  3123 D MapProfile: Bluetooth service connected
11-21 17:14:55.772   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 17:14:55.772  3123  3123 D BluetoothMap: getConnectedDevices()
11-21 17:14:55.772   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 17:14:55.772  5663  5674 D BluetoothMap: onBluetoothStateChange: up=true
11-21 17:14:55.772  3123  3134 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 17:14:55.772  5707  5707 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-21 17:14:55.772  3790  4011 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 17:14:55.773  5707  5707 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-21 17:14:55.773   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 17:14:55.773  5663  5673 D BluetoothPan: onBluetoothStateChange on: true
11-21 17:14:55.773   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
11-21 17:14:55.774   931   931 D BluetoothA2dp: Proxy object connected
11-21 17:14:55.774  3123  3997 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-21 17:14:55.774  5707  5707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:14:55.776  3123  3123 D BluetoothInputDevice: Proxy object connected
11-21 17:14:55.776  3123  3123 D HidProfile: Bluetooth service connected
11-21 17:14:55.777   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
,11-21 17:14:55.779  5707  5707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 17:14:55.780  5663  5663 D LocalBluetoothProfileManager: Adding local A2DP profile
11-21 17:14:55.781  5707  5707 D ObexServerSockets: Succeed to create listening sockets 
11-21 17:14:55.781  5707  5707 D ObexServerSockets0: startAccept()
11-21 17:14:55.781  5707  5707 D ObexServerSockets0: prepareForNewConnect()
,11-21 17:14:55.783  5707  5707 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-21 17:14:55.783  5707  5707 D BluetoothSdpJni: SDP Create record success - handle: 0
11-21 17:14:55.784  5707  5707 D BluetoothMapService: onReceive
11-21 17:14:55.784  5707  5707 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 17:14:55.784  5663  5663 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-21 17:14:55.784  5707  5707 D BluetoothMapService: STATE_ON
11-21 17:14:55.786  5707  5747 D ObexServerSockets0: Accepting socket connection...
11-21 17:14:55.787  5707  5748 D ObexServerSockets0: Accepting socket connection...
11-21 17:14:55.787  5707  5749 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:14:55.790  5707  5749 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-21 17:14:55.791  5707  5749 D BluetoothSdpJni: SDP Create record success - handle: 1
11-21 17:14:55.793  5663  5663 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-21 17:14:55.794  5587  5661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-21 17:14:55.794  5587  5661 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 17:14:55.794  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:14:55.794  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:14:55.794  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 17:14:55.794  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 17:14:55.794  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 17:14:55.794  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 17:14:55.794  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 17:14:55.794  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 17:14:55.795  5663  5663 D BluetoothA2dp: Proxy object connected
11-21 17:14:55.797  5587  5661 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 17:14:55.799  5587  5635 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-21 17:14:55.802   931  3142 D WifiService: setWifiEnabled: false pid=5587, uid=10077
11-21 17:14:55.802   931  3142 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 17:14:55.802  5587  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 17:14:55.803  3587  3587 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 17:14:55.804   931  2941 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-21 17:14:55.804   931  2941 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-21 17:14:55.804   931  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-21 17:14:55.804   931  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-21 17:14:55.808  3123  3123 D BluetoothPbap: Proxy object connected
11-21 17:14:55.808  3123  3123 D PbapServerProfile: Bluetooth service connected
11-21 17:14:55.808  5663  5663 D DockEventReceiver: finishStartingService: stopping service
11-21 17:14:55.808  5707  5707 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-21 17:14:55.808  5707  5707 D ObexServerSockets0: prepareForNewConnect()
11-21 17:14:55.809  5663  5663 D BluetoothPbap: Proxy object connected
11-21 17:14:55.810  5663  5663 D PbapServerProfile: Bluetooth service connected
11-21 17:14:55.810  5707  5752 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:14:55.814   931  5333 D DhcpClient: Clearing IP address
11-21 17:14:55.814   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-21 17:14:55.823   509   923 D CommandListener: Setting iface cfg
,11-21 17:14:55.829  3587  5390 V NativeCrypto: Read error: ssl=0x7f5b002700: I/O error during system call, Connection timed out
11-21 17:14:55.831  3587  5390 V NativeCrypto: SSL shutdown failed: ssl=0x7f5b002700: I/O error during system call, Broken pipe
,11-21 17:14:55.833   931  4041 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-21 17:14:55.833   931  5331 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-21 17:14:55.836  5707  5758 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:14:55.836   931  5331 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-21 17:14:55.836   931  2955 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-21 17:14:55.837   931  2955 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-21 17:14:55.837  5707  5758 I BtOppRfcommListener: Accept thread started.
11-21 17:14:55.838   931  2955 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-21 17:14:55.840   931  2955 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-21 17:14:55.840   931  2955 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-21 17:14:55.846   535   535 E Parcel  : Reading a NULL string not supported here.
,11-21 17:14:55.848   931   931 D RttService: SCAN_AVAILABLE : 1
,11-21 17:14:55.849   931  2955 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-21 17:14:55.849   931  3054 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler },
11-21 17:14:55.850  3762  3883 W QCNEJ   : |CORE| network lost: 100
,11-21 17:14:55.851  3762  3883 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-21 17:14:55.854   931  5334 D DhcpClient: Receive thread stopped
,11-21 17:14:55.858   931  2941 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-21 17:14:55.865   931  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-21 17:14:55.874   931   931 D BluetoothHeadset: Proxy object connected
,11-21 17:14:55.875   931   931 D BluetoothHeadset: Proxy object connected
11-21 17:14:55.875  3123  3997 D BluetoothHeadset: Proxy object connected
11-21 17:14:55.876  3790  3806 D BluetoothHeadset: Proxy object connected
11-21 17:14:55.876   931   931 D BluetoothHeadset: Proxy object connected
11-21 17:14:55.880   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 17:14:55.887  5663  5673 D BluetoothHeadset: Proxy object connected
,11-21 17:14:55.888  3123  3123 D HeadsetProfile: Bluetooth service connected
11-21 17:14:55.888  5663  5663 D HeadsetProfile: Bluetooth service connected
,11-21 17:14:55.902   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 17:14:55.903   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-21 17:14:55.903   931  2955 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-21 17:14:55.903   931  2955 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-21 17:14:55.903   509   923 D TetherController: Setting IP forward enable = 0
11-21 17:14:55.905   931   948 D Tethering: MasterInitialState.processMessage what=3
,11-21 17:14:55.907   931  2941 D DhcpClient: doQuit
11-21 17:14:55.907   931  2941 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-21 17:14:55.908  3443  3443 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-21 17:14:55.908   931  5333 D DhcpClient: onQuitting
,11-21 17:14:55.911  5220  5220 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@52d357a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-21 17:14:55.914  3961  3961 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-21 17:14:55.917  4996  5022 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-21 17:14:55.919  4996  5022 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 17:14:55.919  4996  5022 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-21 17:14:55.919  4996  5022 E SarControlService: no key has been found,reset the power
11-21 17:14:55.919  4996  5047 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-21 17:14:55.919  4996  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-21 17:14:55.919  4996  5047 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 17:14:55.920  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 17:14:55.920  5035  5035 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-21 17:14:55.921  4996  5047 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-21 17:14:55.921  4996  5047 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-21 17:14:55.921  4996  5047 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 17:14:55.921  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 17:14:55.921  5035  5035 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-21 17:14:55.924  3982  3982 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-21 17:14:55.925  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6e9fb0 HexData = [00000000ea03000000000000ffffffff]
11-21 17:14:55.925  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 17:14:55.925  5035  5049 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-21 17:14:55.926  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 17:14:55.926  4996  5007 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-21 17:14:55.929  3982  3982 D SystemUpdateService: onCreate
11-21 17:14:55.930  3443  3443 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-21 17:14:55.932  3982  3982 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-21 17:14:55.933  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6e9fb0 HexData = [00000000eb03000000000000ffffffff]
11-21 17:14:55.933  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 17:14:55.933  5035  5049 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-21 17:14:55.934  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 17:14:55.934  4996  5008 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-21 17:14:55.936  3443  3443 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-21 17:14:55.946  3982  3982 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-21 17:14:55.952  3982  5359 I iu.UploadsManager: num queued entries: 0
,11-21 17:14:55.953  3982  5359 I iu.UploadsManager: num updated entries: 0
11-21 17:14:55.953  3982  5359 I iu.SyncManager: NEXT; no task
,11-21 17:14:55.958  3982  3982 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-21 17:14:55.959  3982  3982 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-21 17:14:55.961  3982  5779 I SystemUpdateService: active receiver: enabled
,11-21 17:14:55.962   509   923 E Netd    : netlink response contains error (No such file or directory)
,11-21 17:14:55.963   509   923 D TetherController: Setting IP forward enable = 0
11-21 17:14:55.963   931  2955 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-21 17:14:55.967  3982  5779 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-21 17:14:55.971   931  3602 I ActivityManager: Start proc 5784:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
11-21 17:14:55.972  3443  3443 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-21 17:14:55.980  3982  5779 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-21 17:14:55.983  3982  5779 I SystemUpdateService: now status is 0 (complete)
,11-21 17:14:55.983  3982  5779 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 17:14:55.984  3982  5779 I SystemUpdateService: file has been verified
,11-21 17:14:55.985  3982  5779 I SystemUpdateService: OTA package size = 21989297
,11-21 17:14:55.988  3443  3443 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-21 17:14:56.014  5784  5784 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-21 17:14:56.015  3982  5779 I SystemUpdateService: showing system update notification
,11-21 17:14:56.017  5784  5784 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-21 17:14:56.024  5784  5784 D SprintDMHelper: simOperator: 
11-21 17:14:56.024  5784  5784 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 17:14:56.030   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 17:14:56.038   931  3603 I ActivityManager: Start proc 5797:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-21 17:14:56.043  3982  3982 D SystemUpdateService: onDestroy
,11-21 17:14:56.048   931   942 I ActivityManager: Killing 5220:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-21 17:14:56.093  4441  4441 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 17:14:56.093   931  2941 D wifi    : In wifi stop Hal
11-21 17:14:56.093   931  2941 D wifi    : halHandle = 0x7f59448a40, mVM = 0x7f75b0d140, mCls = 0x100a02
11-21 17:14:56.093   931  3442 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-21 17:14:56.094   931  3442 D WifiHAL : Got a signal to exit!!!
,11-21 17:14:56.094   931  3442 I WifiHAL : Exit wifi_event_loop
11-21 17:14:56.094   931  2941 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-21 17:14:56.094   931  2941 E WifiHAL : Event processing terminated
,11-21 17:14:56.095   931  2941 D wifi    : In wifi cleaned up handler
11-21 17:14:56.095   931  2941 I WifiHAL : Internal cleanup completed
11-21 17:14:56.095  3746  4190 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 17:14:56.111   931  3442 D wifi    : set interface wlan0 flags (DOWN)
,11-21 17:14:56.111   931  2941 D WifiNative-HAL: HAL event thread stopped successfully
,11-21 17:14:56.134  4441  5811 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-21 17:14:56.146   931   942 I ActivityManager: Start proc 5812:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-21 17:14:56.149   931  3421 I ActivityManager: Killing 3884:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-21 17:14:56.185  5812  5812 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-21 17:14:56.192   931  3421 I ActivityManager: Killing 5445:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-21 17:14:56.309  5587  5661 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 17:14:56.309  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:14:56.309  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:14:56.309  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-21 17:14:56.309  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 17:14:56.309  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 17:14:56.309  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 17:14:56.309  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 17:14:56.309  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 17:14:56.310  5587  5661 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 17:14:56.312   931  3142 D WifiService: setWifiEnabled: true pid=5587, uid=10077
11-21 17:14:56.312   931  3142 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 17:14:56.314  5587  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 17:14:56.317   931   948 D Tethering: InitialState.processMessage what=4
,11-21 17:14:56.317   509   923 D SoftapController: Softap fwReload - Ok
11-21 17:14:56.321   509   923 D CommandListener: Setting iface cfg
11-21 17:14:56.321   509   923 D CommandListener: Trying to bring down wlan0
11-21 17:14:56.321   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-21 17:14:56.323   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-21 17:14:56.327   931  2941 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-21 17:14:56.816   931  3782 D WifiService: setWifiEnabled: true pid=5587, uid=10077
,11-21 17:14:56.820   931  3782 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 17:14:56.931   931  2941 D wifi    : set interface wlan0 flags (UP)
,11-21 17:14:56.931   931  2941 I WifiHAL : Initializing wifi
,11-21 17:14:56.932   931  2941 I WifiHAL : Creating socket
,11-21 17:14:56.937   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-21 17:14:56.939   931  2941 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-21 17:14:56.939   931  2941 D wifi    : Did set static halHandle = 0x7f59448a40
11-21 17:14:56.939   931  2941 D wifi    : halHandle = 0x7f59448a40, mVM = 0x7f75b0d140, mCls = 0x2012f2
11-21 17:14:56.940   931  2941 D wifi    : array field set
,11-21 17:14:56.940   931  2941 I WifiNative-HAL: interface[0] = wlan0
11-21 17:14:56.943   931  5828 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546958510656
11-21 17:14:56.943   931  5828 D wifi    : waitForHalEvents called, vm = 0x7f75b0d140, obj = 0x2012f2, env = 0x7f597396c0
,11-21 17:14:57.033  5829  5829 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-21 17:14:57.044   931  2941 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-21 17:14:57.088   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:14:57.106  5829  5829 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-21 17:14:57.130  5829  5829 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-21 17:14:57.130  5829  5829 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-21 17:14:57.144   931  2941 D WifiConfigStore: Loading config and enabling all networks 
,11-21 17:14:57.160   931  2941 D WifiConfigStore: loaded 0 passpoint configs
,11-21 17:14:57.160   931  2941 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-21 17:14:57.161   931  2941 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-21 17:14:57.161   931  2941 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-21 17:14:57.161   931  2941 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-21 17:14:57.162   931  2941 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-21 17:14:57.162   931  2941 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-21 17:14:57.162   931  2941 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-21 17:14:57.162   931  2941 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-21 17:14:57.162   931  2941 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-21 17:14:57.162   931  2941 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-21 17:14:57.163   931  2941 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-21 17:14:57.163   931  2941 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-21 17:14:57.165   931  2941 D WifiNative-HAL: Setting external_sim to 1
11-21 17:14:57.165   931  2941 D wifi    : setting dfs flag to true, 0x7f5e5ff9a0
,11-21 17:14:57.165   931  2941 D WifiStateMachine: Setting OUI to DA-A1-19
11-21 17:14:57.165   931  2941 D wifi    : setting scan oui 0x7f5e5ff9a0
11-21 17:14:57.166   931  2941 D WifiHAL : Sending mac address OUI
11-21 17:14:57.166  4441  4441 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-21 17:14:57.168   931  2941 E native  : do suspend false
,11-21 17:14:57.175   931  2941 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-21 17:14:57.176   931   931 D RttService: SCAN_AVAILABLE : 3
11-21 17:14:57.176   931  3054 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-21 17:14:57.180   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-21 17:14:57.182   509   923 D CommandListener: Setting iface cfg
,11-21 17:14:57.188   931  2938 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,11-21 17:14:57.188   931  2938 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-21 17:14:57.193   931  2938 D WifiNative-HAL: p2pGetDeviceAddress
,11-21 17:14:57.198   931  2938 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-21 17:14:57.198   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=188694 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-21 17:14:57.331  5587  5661 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 17:14:57.331  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 17:14:57.331  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 17:14:57.331  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 17:14:57.331  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 17:14:57.331  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 17:14:57.331  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 17:14:57.331  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 17:14:57.331  5587  5661 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 17:14:57.339  5587  5661 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 17:14:57.342  5587  5635 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 17:14:57.343   931  3782 D WifiService: setWifiEnabled: true pid=5587, uid=10077
11-21 17:14:57.343   931  3782 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 17:14:57.344  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 17:14:57.345  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-21 17:14:57.345  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-21 17:14:57.345  5587  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a40f730 removed from the list
,11-21 17:14:57.345  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 17:14:57.345  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81a0fa9 removed from the list
11-21 17:14:57.345  5587  5635 D io.jxcore.node.ConnectivityMonitor: stop
,11-21 17:14:57.349  5587  5635 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-21 17:14:57.352  5587  5635 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-21 17:14:57.353  5587  5635 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-21 17:14:57.355  5587  5635 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
11-21 17:14:57.357  5587  5635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-21 17:14:57.359  5587  5635 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-21 17:14:57.360  5587  5635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-21 17:14:57.360  5587  5635 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-21 17:14:57.362  5587  5635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-21 17:14:57.366  5587  5635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-21 17:14:57.366  5587  5635 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@cda5574 Bundle[{}]
11-21 17:14:57.367  5587  5635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,11-21 17:14:57.367  5587  5635 I io.jxcore.node.LifeCycleMonitor: start: OK
11-21 17:14:57.368  5587  5635 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-21 17:14:57.369  5587  5635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-21 17:14:57.369  5587  5635 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-21 17:14:57.370  5587  5635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-21 17:14:57.370  5587  5635 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-21 17:14:57.371  5587  5635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-21 17:14:57.371  5587  5635 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-21 17:14:57.372  5587  5635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-21 17:14:57.372  5587  5635 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-21 17:14:57.374  5587  5635 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-21 17:14:57.377  5587  5635 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
11-21 17:14:57.379  5587  5635 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-21 17:14:57.380  5587  5635 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-21 17:14:57.382  5587  5635 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-21 17:14:57.383  5587  5635 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-21 17:14:57.385  5587  5635 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-21 17:14:57.387  5587  5635 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,11-21 17:14:58.089   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:14:58.392  5587  5635 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-21 17:14:58.394  5587  5635 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-21 17:14:58.398  5587  5635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-21 17:14:58.400  5587  5635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-21 17:14:58.401  5587  5635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-21 17:14:58.402  5587  5635 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 173)
,11-21 17:14:58.404  5587  5635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-21 17:14:58.404  5587  5635 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-21 17:14:58.405  5587  5635 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 174)
,11-21 17:14:58.406  5587  5635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-21 17:14:58.408  5587  5635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-21 17:14:58.410  5587  5635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-21 17:14:58.410  5587  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 17:14:58.411  5587  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eea2ccf added. We now have 3 listener(s)
,11-21 17:14:58.413  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 17:14:58.413  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 17:14:58.413  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 17:14:58.413  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 17:14:58.413  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a76565c added. We now have 3 listener(s)
11-21 17:14:58.413  5587  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 17:14:58.414  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 17:14:58.421  5587  5635 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation,
,11-21 17:14:58.422  5587  5635 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation,
11-21 17:14:58.422  5587  5635 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,11-21 17:14:58.422  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-21 17:14:58.423  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:58.423  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:58.423  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:58.423  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-21 17:14:58.423  5587  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 17:14:58.423  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-21 17:14:58.423  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:14:58.423  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-21 17:14:58.427  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 17:14:58.427  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 17:14:58.428  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 17:14:58.428  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 17:14:58.428  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-21 17:14:58.428  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 17:14:58.428  5587  5833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 17:14:58.428  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:14:58.428  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 17:14:58.428  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 17:14:58.431  5587  5833 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:14:58.434  5744  5744 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[29568]" dev="sockfs" ino=29568 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:14:58.434  5744  5744 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[29568]" dev="sockfs" ino=29568 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:14:58.435  5587  5833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 17:14:58.437  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 17:14:58.437  5587  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 17:14:58.437  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 17:14:58.441  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:58.441  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-21 17:14:58.442  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 17:14:58.442  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:14:58.443  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-21 17:14:58.445  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:58.445  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.445  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 17:14:58.445  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 17:14:58.446  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 17:14:58.446  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-21 17:14:58.446  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:58.446  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 17:14:58.446  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.446  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 17:14:58.446  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:14:58.446  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.446  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.446  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.447  5587  5635 D BluetoothAdapter: STATE_ON
,11-21 17:14:58.451  5707  5746 D BtGatt.GattService: registerClient() - UUID=4ce6dc44-c884-42b5-a487-82262c2c4a42
,11-21 17:14:58.452  5707  5724 D BtGatt.GattService: onClientRegistered() - UUID=4ce6dc44-c884-42b5-a487-82262c2c4a42, clientIf=5
,11-21 17:14:58.453  5587  5598 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 17:14:58.455  5707  5727 D BtGatt.AdvertiseManager: message : 0
,11-21 17:14:58.456  5707  5727 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 17:14:58.466  5707  5724 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 17:14:58.472  5707  5724 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 17:14:58.473  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.473  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.473  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 17:14:58.473  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:58.473  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.473  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.473  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.473  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.473  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 17:14:58.474  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 17:14:58.474  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:14:58.475  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.475  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.476  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:14:58.476  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 17:14:58.476  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 17:14:58.476  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:58.476  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 17:14:58.476  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 17:14:58.476  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-21 17:14:58.477  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:14:58.477  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:14:58.477  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 17:14:58.477  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 17:14:58.477  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:14:58.477  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 17:14:58.477  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 17:14:58.477  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 17:14:58.479  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-21 17:14:58.480  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 17:14:58.480  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:58.480  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:14:58.480  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:14:58.480  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 17:14:58.981  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-21 17:14:58.981  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 17:14:58.981  5587  5587 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 17:14:59.089   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:00.090   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:00.250  5829  5829 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 17:15:00.254  5829  5829 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 17:15:00.260  5829  5829 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 17:15:00.315   931  2941 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-21 17:15:00.316   931  2941 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-21 17:15:00.317   931  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 17:15:00.330   931  2941 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-21 17:15:00.363   931  2941 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-21 17:15:00.369  5829  5829 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-21 17:15:00.803  5829  5829 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-21 17:15:00.840  5829  5829 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-21 17:15:00.840  5829  5829 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-21 17:15:00.850   931  2941 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-21 17:15:00.850   931  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 17:15:00.851   931  2955 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-21 17:15:00.870   931  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 17:15:00.883   509   923 D CommandListener: Setting iface cfg
,11-21 17:15:00.888   931  2941 D WifiStateMachine: Start Dhcp Watchdog 2
,11-21 17:15:00.894   931  5838 D DhcpClient: Receive thread started
,11-21 17:15:00.898   931  2955 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:15:00.898   931  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-21 17:15:00.898   931  2955 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-21 17:15:00.978   931  2941 E native  : do suspend false
,11-21 17:15:00.990   931  5837 D DhcpClient: Broadcasting DHCPDISCOVER
,11-21 17:15:01.015   931  5838 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172648, domain null
,11-21 17:15:01.016   931  5837 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172648 seconds
,11-21 17:15:01.018   931  5837 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-21 17:15:01.036   931  5838 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-21 17:15:01.037   931  5837 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-21 17:15:01.039   509   923 D CommandListener: Setting iface cfg
,11-21 17:15:01.042   931  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-21 17:15:01.046   931  5837 D DhcpClient: Scheduling renewal in 86399s
,11-21 17:15:01.054   931  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-21 17:15:01.054   931  2941 D WifiConfigStore: No blacklist allowed without epno enabled
,11-21 17:15:01.055   931  2955 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-21 17:15:01.058   931  2955 D ConnectivityService: Adding iface wlan0 to network 101
,11-21 17:15:01.060   931  2941 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-21 17:15:01.091   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:01.092   931  2955 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-21 17:15:01.092   931  2955 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-21 17:15:01.093   931  2955 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-21 17:15:01.095   931  2955 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-21 17:15:01.097   931  2955 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-21 17:15:01.102   931  2955 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:15:01.107   931  2955 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-21 17:15:01.107   931  2955 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-21 17:15:01.107   931  2955 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-21 17:15:01.107   931  2955 D ConnectivityService:    accepting network in place of null
11-21 17:15:01.108   931  2955 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -57]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-21 17:15:01.109   931  2941 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-21 17:15:01.109   931  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-21 17:15:01.125   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=192620, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:15:01.129   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 17:15:01.147   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 17:15:01.150   931  2955 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-21 17:15:01.150   931  2955 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-21 17:15:01.150  3762  3883 W QCNEJ   : |CORE| network available: 101
11-21 17:15:01.151   931  2955 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-21 17:15:01.151   931   948 D Tethering: MasterInitialState.processMessage what=3
,11-21 17:15:01.152  3762  3883 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-21 17:15:01.154  3762  3883 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-21 17:15:01.154  3762  3883 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-21 17:15:01.164  3961  3961 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-21 17:15:01.166  4996  5022 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-21 17:15:01.167  4996  5022 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 17:15:01.167  4996  5022 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-21 17:15:01.167  4996  5022 E SarControlService: no key has been found,reset the power
11-21 17:15:01.167  4996  5047 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-21 17:15:01.167  4996  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 17:15:01.167  4996  5047 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 17:15:01.167  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 17:15:01.168  5035  5035 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-21 17:15:01.169  4996  5047 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-21 17:15:01.169  4996  5047 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-21 17:15:01.169  4996  5047 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 17:15:01.169  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 17:15:01.169  5035  5035 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-21 17:15:01.173  3982  3982 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-21 17:15:01.174  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6e9fb0 HexData = [00000000ec03000000000000ffffffff]
11-21 17:15:01.174  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 17:15:01.174  5035  5049 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-21 17:15:01.178  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6e9fb0 HexData = [00000000ed03000000000000ffffffff]
11-21 17:15:01.178  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 17:15:01.178  5035  5049 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-21 17:15:01.179  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-21 17:15:01.179  4996  5007 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-21 17:15:01.179  3982  3982 D SystemUpdateService: onCreate
11-21 17:15:01.180  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 17:15:01.181  4996  5008 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-21 17:15:01.188  3982  3982 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-21 17:15:01.193   931  5835 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-21 17:15:01.197  3982  3982 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-21 17:15:01.199  3982  5359 I iu.UploadsManager: num queued entries: 0
11-21 17:15:01.200  3982  5359 I iu.UploadsManager: num updated entries: 0
11-21 17:15:01.200  3982  5359 I iu.SyncManager: NEXT; no task
,11-21 17:15:01.212  3982  3982 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-21 17:15:01.213  3982  3982 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-21 17:15:01.215  5784  5784 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-21 17:15:01.219  5784  5784 D SprintDMHelper: simOperator: 
11-21 17:15:01.219  5784  5784 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 17:15:01.239   931  5835 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Nov 2016 16:15:01 GMT], X-Android-Received-Millis=[1479744901239], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479744901218]}
,11-21 17:15:01.240   931  2955 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-21 17:15:01.240   931  2955 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-21 17:15:01.240   931  2955 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:15:01.241   931  2955 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-21 17:15:01.246  3982  5850 I SystemUpdateService: active receiver: enabled
,11-21 17:15:01.274  3982  5850 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-21 17:15:01.276  3982  5850 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-21 17:15:01.276  3982  5850 I SystemUpdateService: now status is 0 (complete)
11-21 17:15:01.276  3982  5850 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 17:15:01.276  3982  5850 I SystemUpdateService: file has been verified
11-21 17:15:01.277  3982  5850 I SystemUpdateService: OTA package size = 21989297
,11-21 17:15:01.285  3982  5850 I SystemUpdateService: showing system update notification
,11-21 17:15:01.292   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 17:15:01.293  3982  3982 D SystemUpdateService: onDestroy
,11-21 17:15:01.331  4441  5855 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-21 17:15:01.978  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-21 17:15:01.978  5587  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-21 17:15:01.979  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 17:15:01.979  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 17:15:01.979  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-21 17:15:01.979  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 17:15:01.980  5587  5833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 17:15:01.980  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-21 17:15:01.980  5587  5833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 17:15:01.980  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-21 17:15:01.980  5587  5833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 17:15:01.980  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-21 17:15:01.980  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-21 17:15:01.980  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-21 17:15:01.980  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 17:15:01.980  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-21 17:15:01.981  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:01.981  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:01.982  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:01.982  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:01.987  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:15:01.988  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 17:15:01.990  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:15:01.991  5587  5635 D BluetoothLeScanner: could not find callback wrapper
11-21 17:15:01.991  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 17:15:01.992  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:01.992  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:01.992  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:01.993  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 17:15:01.993  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:01.995  5707  5727 D BtGatt.AdvertiseManager: message : 1
,11-21 17:15:01.996  5707  5727 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 17:15:02.004  5707  5724 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 17:15:02.004  5707  5724 D BtGatt.GattService: Client app is not null!
11-21 17:15:02.005  5707  5718 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 17:15:02.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 17:15:02.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:02.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 17:15:02.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:02.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:02.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:02.006  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 17:15:02.007  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 17:15:02.007  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-21 17:15:02.009  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:02.010  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:02.010  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:15:02.010  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:02.010  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:02.011  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 17:15:02.011  5587  5587 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 17:15:02.011  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 17:15:02.011  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:15:02.011  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:15:02.011  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:15:02.011  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 17:15:02.011  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 17:15:02.017  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-21 17:15:02.017  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 17:15:02.017  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:15:02.018  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-21 17:15:02.018  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-21 17:15:02.018  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:15:02.019  5587  5635 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-21 17:15:02.019  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 17:15:02.020  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:15:02.020  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:15:02.020  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-21 17:15:02.020  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 17:15:02.020  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:15:02.020  5587  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-21 17:15:02.020  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-21 17:15:02.020  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:15:02.020  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 17:15:02.020  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-21 17:15:02.022  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-21 17:15:02.026  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-21 17:15:02.026  5587  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 17:15:02.026  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 17:15:02.031  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:02.031  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 17:15:02.032  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-21 17:15:02.032  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-21 17:15:02.032  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-21 17:15:02.036  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-21 17:15:02.040  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-21 17:15:02.040  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:02.040  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-21 17:15:02.040  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-21 17:15:02.040  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-21 17:15:02.041  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-21 17:15:02.041  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:02.042  5587  5635 D BluetoothAdapter: STATE_ON
,11-21 17:15:02.046  5707  5745 D BtGatt.GattService: registerClient() - UUID=0e7df0ff-a87e-4724-b8c2-91dbf1b7cba1
,11-21 17:15:02.049  5707  5724 D BtGatt.GattService: onClientRegistered() - UUID=0e7df0ff-a87e-4724-b8c2-91dbf1b7cba1, clientIf=5
,11-21 17:15:02.049  5587  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-21 17:15:02.050  5707  5717 D BtGatt.GattService: start scan with filters
,11-21 17:15:02.055  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-21 17:15:02.055  5707  5728 D BtGatt.ScanManager: handling starting scan
11-21 17:15:02.055  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:02.055  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-21 17:15:02.055  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:02.056  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 17:15:02.056  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:15:02.056  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:15:02.056  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 17:15:02.056  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 17:15:02.057  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:15:02.057  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-21 17:15:02.057  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-21 17:15:02.058  5707  5728 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2341961
11-21 17:15:02.058  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 17:15:02.058  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:02.062  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:02.062  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-21 17:15:02.062  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:02.062  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:02.063  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 17:15:02.066  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:15:02.067  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-21 17:15:02.067  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:15:02.067  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:15:02.067  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-21 17:15:02.068  5707  5724 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-21 17:15:02.068  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:15:02.069  5707  5728 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-21 17:15:02.076  5707  5724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-21 17:15:02.076  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:15:02.076  5707  5728 D BtGatt.ScanManager: Starting BLE batch scan
,11-21 17:15:02.077  5707  5728 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-21 17:15:02.089  5707  5724 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-21 17:15:02.089  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:15:02.091   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 17:15:02.096  5707  5724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-21 17:15:02.096  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:15:02.151   931  2955 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-21 17:15:02.568  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-21 17:15:02.568  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-21 17:15:02.569  5587  5587 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 17:15:03.916   931  2955 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:15:05.065  5587  5635 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-21 17:15:05.066  5587  5635 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-21 17:15:05.066  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-21 17:15:05.066  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.067  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.067  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.067  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 17:15:05.067  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 17:15:05.067  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 17:15:05.067  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-21 17:15:05.067  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 17:15:05.067  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 17:15:05.067  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 17:15:05.067  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 17:15:05.067  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 17:15:05.067  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:05.067  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-21 17:15:05.068  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.068  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.068  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-21 17:15:05.068  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-21 17:15:05.069  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.069  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.069  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.072  5587  5635 D BluetoothAdapter: STATE_ON
,11-21 17:15:05.073  5707  5717 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-21 17:15:05.074  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-21 17:15:05.075  5707  5728 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-21 17:15:05.076  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:15:05.077  5707  5744 D BtGatt.GattService: stopScan() - queue size =1
,11-21 17:15:05.079  5707  5746 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 17:15:05.080  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-21 17:15:05.080  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:05.081  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 17:15:05.081  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.081  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 17:15:05.081  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.082  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.082  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-21 17:15:05.082  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-21 17:15:05.082  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-21 17:15:05.082  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-21 17:15:05.082  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.085  5707  5707 D BtGatt.ScanManager: awakened up at time 196580
11-21 17:15:05.085  5587  5635 D BluetoothAdapter: STATE_ON
,11-21 17:15:05.090  5707  5745 D BtGatt.GattService: registerClient() - UUID=ee2319c6-e9d1-4c2c-b0ae-e5b5be208c6c
,11-21 17:15:05.093  5707  5724 D BtGatt.GattService: onClientRegistered() - UUID=ee2319c6-e9d1-4c2c-b0ae-e5b5be208c6c, clientIf=5
,11-21 17:15:05.094  5587  5628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-21 17:15:05.099  5707  5717 D BtGatt.GattService: start scan with filters
11-21 17:15:05.102  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-21 17:15:05.103  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.103  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-21 17:15:05.103  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.103  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.103  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:15:05.103  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 17:15:05.103  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:15:05.104  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 17:15:05.104  5587  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 17:15:05.104  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 17:15:05.104  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 17:15:05.104  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 17:15:05.104  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-21 17:15:05.104  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 17:15:05.105  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 17:15:05.106  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 17:15:05.106  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 17:15:05.106  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 17:15:05.106  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 17:15:05.106  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-21 17:15:05.106  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-21 17:15:05.106  5587  5863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 17:15:05.107  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-21 17:15:05.108  5587  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 17:15:05.113  5707  5724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-21 17:15:05.113  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:15:05.113  5707  5724 D BtGatt.GattService: current time is 196608693178
11-21 17:15:05.113  5587  5863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 17:15:05.114  5717  5717 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34859]" dev="sockfs" ino=34859 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 17:15:05.114  5707  5724 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -88, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -95, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -83, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-21 17:15:05.115  5707  5724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-21 17:15:05.116  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.116  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.116  5587  5863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 17:15:05.116  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:05.114  5717  5717 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[34859]" dev="sockfs" ino=34859 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 17:15:05.116  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 17:15:05.117  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 17:15:05.117  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 17:15:05.117  5707  5724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 17:15:05.117  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-21 17:15:05.117  5707  5724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-21 17:15:05.117  5587  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:15:05.117  5707  5724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
11-21 17:15:05.117  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:15:05.117  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.117  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 17:15:05.117  5707  5724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-21 17:15:05.118  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 17:15:05.118  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:05.118  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.118  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.120  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:15:05.121  5707  5724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-21 17:15:05.124  5707  5717 D BtGatt.GattService: registerClient() - UUID=fce698ff-1b5e-4216-a3d8-370b6d127bb4
11-21 17:15:05.128  5707  5724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-21 17:15:05.128  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:15:05.129  5707  5724 D BtGatt.GattService: onClientRegistered() - UUID=fce698ff-1b5e-4216-a3d8-370b6d127bb4, clientIf=6
11-21 17:15:05.129  5707  5728 D BtGatt.ScanManager: stopping BLe Batch
11-21 17:15:05.129  5587  5597 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-21 17:15:05.130  5707  5727 D BtGatt.AdvertiseManager: message : 0
,11-21 17:15:05.133  5707  5727 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 17:15:05.141  5707  5724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-21 17:15:05.142  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:15:05.142  5707  5728 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 17:15:05.152  5707  5724 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-21 17:15:05.157  5707  5724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-21 17:15:05.157  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:15:05.159  5707  5728 D BtGatt.ScanManager: handling starting scan
,11-21 17:15:05.162  5707  5724 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-21 17:15:05.163  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.163  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.163  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-21 17:15:05.163  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.163  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.163  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.163  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.163  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.163  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.163  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.163  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:05.164  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-21 17:15:05.164  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-21 17:15:05.164  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 17:15:05.165  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-21 17:15:05.165  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:05.167  5707  5724 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-21 17:15:05.167  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:15:05.167  5707  5728 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-21 17:15:05.168  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.168  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.168  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:05.168  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 17:15:05.168  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 17:15:05.169  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-21 17:15:05.169  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 17:15:05.169  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 17:15:05.169  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 17:15:05.169  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 17:15:05.169  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:15:05.169  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-21 17:15:05.169  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 17:15:05.169  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:15:05.169  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-21 17:15:05.170  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-21 17:15:05.170  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 17:15:05.173  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-21 17:15:05.173  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-21 17:15:05.173  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:15:05.173  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:15:05.173  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:15:05.173  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-21 17:15:05.175  5707  5724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-21 17:15:05.175  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:15:05.175  5707  5728 D BtGatt.ScanManager: Starting BLE batch scan
11-21 17:15:05.175  5707  5728 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-21 17:15:05.185  5707  5724 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-21 17:15:05.185  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:15:05.190  5707  5724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-21 17:15:05.190  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:15:05.675  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-21 17:15:05.675  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 17:15:05.675  5587  5587 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 17:15:06.945   931  2955 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:15:08.173  5587  5635 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-21 17:15:08.173  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-21 17:15:08.173  5587  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 17:15:08.173  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 17:15:08.174  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-21 17:15:08.174  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 17:15:08.174  5587  5863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 17:15:08.174  5587  5863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 17:15:08.174  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 17:15:08.175  5587  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-21 17:15:08.175  5587  5863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 17:15:08.175  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-21 17:15:08.175  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 17:15:08.175  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 17:15:08.175  5587  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eea2ccf removed from the list
,11-21 17:15:08.175  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-21 17:15:08.176  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 17:15:08.176  5587  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 17:15:08.176  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-21 17:15:08.176  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 17:15:08.176  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.176  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.177  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.177  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-21 17:15:08.177  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.179  5587  5635 D BluetoothAdapter: STATE_ON
11-21 17:15:08.180  5707  5717 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-21 17:15:08.180  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 17:15:08.181  5707  5728 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 17:15:08.182  5587  5635 D BluetoothAdapter: STATE_ON
,11-21 17:15:08.184  5707  5745 D BtGatt.GattService: stopScan() - queue size =1
,11-21 17:15:08.186  5707  5744 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 17:15:08.187  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 17:15:08.187  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.187  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-21 17:15:08.187  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.189  5707  5707 D BtGatt.ScanManager: awakened up at time 199684
11-21 17:15:08.189  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.189  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.189  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 17:15:08.189  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:08.192  5707  5727 D BtGatt.AdvertiseManager: message : 1
11-21 17:15:08.194  5707  5727 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-21 17:15:08.208  5707  5724 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-21 17:15:08.208  5707  5724 D BtGatt.GattService: Client app is not null!
,11-21 17:15:08.210  5707  5745 D BtGatt.GattService: unregisterClient() - clientIf=6
11-21 17:15:08.211  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 17:15:08.211  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-21 17:15:08.211  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 17:15:08.212  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.212  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.212  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.213  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 17:15:08.213  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 17:15:08.213  5587  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 17:15:08.214  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.215  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.215  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:15:08.215  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.216  5587  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-21 17:15:08.216  5587  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a76565c removed from the list
11-21 17:15:08.216  5587  5635 D io.jxcore.node.ConnectivityMonitor: stop
11-21 17:15:08.216  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-21 17:15:08.216  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 17:15:08.216  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-21 17:15:08.216  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:15:08.216  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 17:15:08.217  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-21 17:15:08.217  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 17:15:08.217  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-21 17:15:08.217  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-21 17:15:08.217  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 17:15:08.217  5587  5635 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-21 17:15:08.217  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 17:15:08.217  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 17:15:08.217  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 17:15:08.218  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 17:15:08.218  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-21 17:15:08.218  5587  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-21 17:15:08.218  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 17:15:08.219  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 17:15:08.219  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 17:15:08.219  5587  5635 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-21 17:15:08.219  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 17:15:08.219  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 17:15:08.219  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 17:15:08.219  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 17:15:08.219  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 17:15:08.219  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-21 17:15:08.219  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 17:15:08.219  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 17:15:08.220  5587  5635 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-21 17:15:08.221  5587  5635 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-21 17:15:08.223  5587  5635 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,11-21 17:15:08.224  5587  5635 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-21 17:15:08.225  5587  5635 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,11-21 17:15:08.226  5587  5635 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-21 17:15:08.227  5587  5635 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-21 17:15:08.235  5707  5724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-21 17:15:08.235  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:15:08.235  5707  5724 D BtGatt.GattService: current time is 199731011880
,11-21 17:15:08.235  5707  5724 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -93, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -88, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -85, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -93, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-21 17:15:08.236  5707  5724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 17:15:08.236  5707  5724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-21 17:15:08.236  5707  5724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-21 17:15:08.236  5707  5724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-21 17:15:08.236  5707  5724 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-21 17:15:08.237  5707  5724 E BtGatt.ContextMap: Context not found for ID 5
,11-21 17:15:08.244  5707  5724 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-21 17:15:08.244  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:15:08.244  5707  5728 D BtGatt.ScanManager: stopping BLe Batch
,11-21 17:15:08.249  5707  5724 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-21 17:15:08.250  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 17:15:08.250  5707  5728 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 17:15:08.255  5707  5724 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-21 17:15:08.255  5707  5724 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 17:15:08.720  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 17:15:09.109   931  2955 D ConnectivityService: handlePromptUnvalidated 101
,11-21 17:15:09.280   931  2941 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,11-21 17:15:09.961   931  2955 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:15:10.231  5587  5635 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-21 17:15:10.415  5587  5865 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 17:15:10.415  5587  5865 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 17:15:11.234  5587  5865 W !!      : call onHalfStreamCopied
,11-21 17:15:11.234  5587  5865 I testCopyDataAndClose: closing input stream
,11-21 17:15:12.008  5587  5865 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 17:15:12.008  5587  5865 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 17:15:12.008  5587  5865 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 17:15:12.008  5587  5865 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 17:15:12.008  5587  5865 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-21 17:15:12.008  5587  5865 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-21 17:15:12.009  5587  5865 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 17:15:12.009  5587  5865 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 17:15:12.009  5587  5865 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 17:15:12.009  5587  5865 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 17:15:12.009  5587  5865 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 17:15:12.201   931  2941 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,11-21 17:15:16.682   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=208177, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:15:16.785  5587  5635 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-21 17:15:16.882  5587  5866 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 17:15:16.882  5587  5866 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 17:15:18.551  5587  5866 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 17:15:18.551  5587  5866 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 17:15:18.551  5587  5866 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 17:15:18.551  5587  5866 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 17:15:18.552  5587  5866 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 17:15:18.552  5587  5866 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 17:15:18.552  5587  5866 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 17:15:18.552  5587  5866 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-21 17:15:18.552  5587  5866 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 17:15:18.552  5587  5866 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 17:15:18.552  5587  5866 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 17:15:23.222  5587  5635 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-21 17:15:23.225  5587  5867 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
11-21 17:15:23.225  5587  5867 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 17:15:23.225  5587  5867 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 192, thread name: My test thread name). Connection data: Peer properties: [null null].
11-21 17:15:23.225  5587  5867 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 17:15:23.226  5587  5867 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 17:15:23.226  5587  5867 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 17:15:23.226  5587  5867 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 17:15:23.226  5587  5867 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 17:15:23.226  5587  5867 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 17:15:23.226  5587  5867 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-21 17:15:23.226  5587  5867 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 17:15:23.226  5587  5867 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
11-21 17:15:23.226  5587  5867 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-21 17:15:23.228  5587  5635 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-21 17:15:23.229  5587  5635 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-21 17:15:23.230  5587  5635 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-21 17:15:23.232  5587  5868 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-21 17:15:23.232  5587  5868 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 17:15:23.232  5587  5868 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 196, thread name: My test thread name): Test exception.
11-21 17:15:23.233  5587  5868 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-21 17:15:23.233  5587  5868 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-21 17:15:23.233  5587  5868 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-21 17:15:23.233  5587  5868 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-21 17:15:23.233  5587  5868 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-21 17:15:23.238  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG UnitTest_app: 'Running unit tests'
11-21 17:15:23.238  5587  5635 I jxcore-log: 
,11-21 17:15:23.238  5587  5635 I jxcore-log: *Native tests were executed*
11-21 17:15:23.238  5587  5635 I jxcore-log: 
11-21 17:15:23.238  5587  5635 I jxcore-log: Total number of executed tests:  81
11-21 17:15:23.238  5587  5635 I jxcore-log: 
11-21 17:15:23.238  5587  5635 I jxcore-log: Number of passed tests:  79
11-21 17:15:23.238  5587  5635 I jxcore-log: 
11-21 17:15:23.238  5587  5635 I jxcore-log: Number of failed tests:  0
11-21 17:15:23.238  5587  5635 I jxcore-log: 
,11-21 17:15:23.238  5587  5635 I jxcore-log: Number of ignored tests:  2
11-21 17:15:23.238  5587  5635 I jxcore-log: 
11-21 17:15:23.239  5587  5635 I jxcore-log: Total duration:  35916
11-21 17:15:23.239  5587  5635 I jxcore-log: 
11-21 17:15:23.241  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-21 17:15:23.241  5587  5635 I jxcore-log: 
,11-21 17:15:23.243  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 17:15:23.243  5587  5635 I jxcore-log: 
11-21 17:15:23.244  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:15:23.244  5587  5635 I jxcore-log: 
,11-21 17:15:23.245  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 17:15:23.245  5587  5635 I jxcore-log: 
11-21 17:15:23.245  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:15:23.245  5587  5635 I jxcore-log: 
11-21 17:15:23.246  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 17:15:23.246  5587  5635 I jxcore-log: 
,11-21 17:15:23.247  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 17:15:23.247  5587  5635 I jxcore-log: 
11-21 17:15:23.247  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:15:23.247  5587  5635 I jxcore-log: 
11-21 17:15:23.247  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 17:15:23.247  5587  5635 I jxcore-log: 
11-21 17:15:23.247  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 17:15:23.247  5587  5635 I jxcore-log: 
,11-21 17:15:23.248  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:15:23.248  5587  5635 I jxcore-log: 
11-21 17:15:23.248  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 17:15:23.248  5587  5635 I jxcore-log: 
11-21 17:15:23.248  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 17:15:23.248  5587  5635 I jxcore-log: 
,11-21 17:15:23.248  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:15:23.248  5587  5635 I jxcore-log: 
11-21 17:15:23.249  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 17:15:23.249  5587  5635 I jxcore-log: 
11-21 17:15:23.249  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:15:23.249  5587  5635 I jxcore-log: 
,11-21 17:15:23.249  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 17:15:23.249  5587  5635 I jxcore-log: 
,11-21 17:15:23.249  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:15:23.249  5587  5635 I jxcore-log: 
11-21 17:15:23.250  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 17:15:23.250  5587  5635 I jxcore-log: 
11-21 17:15:23.250  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:15:23.250  5587  5635 I jxcore-log: 
11-21 17:15:23.250  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 17:15:23.250  5587  5635 I jxcore-log: 
11-21 17:15:23.250  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:15:23.250  5587  5635 I jxcore-log: 
11-21 17:15:23.250  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 17:15:23.250  5587  5635 I jxcore-log: 
11-21 17:15:23.250  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:15:23.250  5587  5635 I jxcore-log: 
11-21 17:15:23.251  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-21 17:15:23.251  5587  5635 I jxcore-log: 
11-21 17:15:23.251  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:15:23.251  5587  5635 I jxcore-log: 
11-21 17:15:23.251  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-21 17:15:23.251  5587  5635 I jxcore-log: 
11-21 17:15:23.251  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 17:15:23.251  5587  5635 I jxcore-log: 
11-21 17:15:23.252  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 17:15:23.252  5587  5635 I jxcore-log: 
11-21 17:15:23.252  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 17:15:23.252  5587  5635 I jxcore-log: 
11-21 17:15:23.253  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:15:23.253  5587  5635 I jxcore-log: 
11-21 17:15:23.253  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-21 17:15:23.253  5587  5635 I jxcore-log: 
,11-21 17:15:23.254  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 17:15:23.254  5587  5635 I jxcore-log: 
11-21 17:15:23.254  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:15:23.254  5587  5635 I jxcore-log: 
11-21 17:15:23.254  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-21 17:15:23.254  5587  5635 I jxcore-log: 
11-21 17:15:23.254  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 17:15:23.254  5587  5635 I jxcore-log: 
11-21 17:15:23.255  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:15:23.255  5587  5635 I jxcore-log: 
11-21 17:15:23.255  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 17:15:23.255  5587  5635 I jxcore-log: 
11-21 17:15:23.255  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 17:15:23.255  5587  5635 I jxcore-log: 
,11-21 17:15:23.260  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-21 17:15:23.260  5587  5635 I jxcore-log: 
11-21 17:15:23.260  5587  5635 I jxcore-log: 2016-11-21 16:15:23 - WARN testUtils: 'myNameCallback not set!'
11-21 17:15:23.260  5587  5635 I jxcore-log: 
,11-21 17:15:23.264  5587  5587 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-21 17:15:25.370  5587  5635 I jxcore-log: 2016-11-21 16:15:25 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-21 17:15:25.370  5587  5635 I jxcore-log: 
,11-21 17:15:25.372  5587  5635 I jxcore-log: 2016-11-21 16:15:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-21 17:15:25.372  5587  5635 I jxcore-log: 
,11-21 17:15:25.724  5587  5635 I jxcore-log: 2016-11-21 16:15:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-21 17:15:25.724  5587  5635 I jxcore-log: 
,11-21 17:15:25.738  5587  5635 I jxcore-log: 2016-11-21 16:15:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-21 17:15:25.738  5587  5635 I jxcore-log: 
,11-21 17:15:26.077  3650  3864 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-21 17:15:26.077  3650  3864 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-21 17:15:26.109  3587  3587 I ConfigService: onCreate
,11-21 17:15:26.861  5587  5635 I jxcore-log: 2016-11-21 16:15:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-21 17:15:26.861  5587  5635 I jxcore-log: 
,11-21 17:15:27.032  5587  5635 I jxcore-log: 2016-11-21 16:15:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-21 17:15:27.032  5587  5635 I jxcore-log: 
,11-21 17:15:27.038  5587  5635 I jxcore-log: 2016-11-21 16:15:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-21 17:15:27.038  5587  5635 I jxcore-log: 
,11-21 17:15:27.050  5587  5635 I jxcore-log: 2016-11-21 16:15:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-21 17:15:27.050  5587  5635 I jxcore-log: 
,11-21 17:15:27.092   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 17:15:27.092   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 17:15:27.552  5587  5635 I jxcore-log: 2016-11-21 16:15:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-21 17:15:27.552  5587  5635 I jxcore-log: 
,11-21 17:15:27.599  5587  5635 I jxcore-log: 2016-11-21 16:15:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-21 17:15:27.599  5587  5635 I jxcore-log: 
,11-21 17:15:27.612  5587  5635 I jxcore-log: 2016-11-21 16:15:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-21 17:15:27.612  5587  5635 I jxcore-log: 
,11-21 17:15:27.616  5587  5635 I jxcore-log: 2016-11-21 16:15:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-21 17:15:27.616  5587  5635 I jxcore-log: 
,11-21 17:15:27.898  5587  5635 I jxcore-log: 2016-11-21 16:15:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-21 17:15:27.898  5587  5635 I jxcore-log: 
,11-21 17:15:28.029  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-21 17:15:28.029  5587  5635 I jxcore-log: 
,11-21 17:15:28.412  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-21 17:15:28.412  5587  5635 I jxcore-log: 
,11-21 17:15:28.419  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-21 17:15:28.419  5587  5635 I jxcore-log: 
,11-21 17:15:28.423  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-21 17:15:28.423  5587  5635 I jxcore-log: 
,11-21 17:15:28.427  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-21 17:15:28.427  5587  5635 I jxcore-log: 
,11-21 17:15:28.432  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-21 17:15:28.432  5587  5635 I jxcore-log: 
,11-21 17:15:28.471  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-21 17:15:28.471  5587  5635 I jxcore-log: 
,11-21 17:15:28.477  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-21 17:15:28.477  5587  5635 I jxcore-log: 
,11-21 17:15:28.507  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-21 17:15:28.507  5587  5635 I jxcore-log: 
,11-21 17:15:28.546  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-21 17:15:28.546  5587  5635 I jxcore-log: 
,11-21 17:15:28.553  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-21 17:15:28.553  5587  5635 I jxcore-log: 
,11-21 17:15:28.560  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-21 17:15:28.560  5587  5635 I jxcore-log: 
,11-21 17:15:28.576  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-21 17:15:28.576  5587  5635 I jxcore-log: 
,11-21 17:15:28.591  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-21 17:15:28.591  5587  5635 I jxcore-log: 
,11-21 17:15:28.597  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-21 17:15:28.597  5587  5635 I jxcore-log: 
,11-21 17:15:28.602  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-21 17:15:28.602  5587  5635 I jxcore-log: 
,11-21 17:15:28.615  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-21 17:15:28.615  5587  5635 I jxcore-log: 
,11-21 17:15:28.633  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-21 17:15:28.633  5587  5635 I jxcore-log: 
,11-21 17:15:28.648  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-21 17:15:28.648  5587  5635 I jxcore-log: 
,11-21 17:15:28.659  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-21 17:15:28.659  5587  5635 I jxcore-log: 
,11-21 17:15:28.671  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-21 17:15:28.671  5587  5635 I jxcore-log: 
,11-21 17:15:28.682  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-21 17:15:28.682  5587  5635 I jxcore-log: 
,11-21 17:15:28.695  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-21 17:15:28.695  5587  5635 I jxcore-log: 
,11-21 17:15:28.705  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-21 17:15:28.705  5587  5635 I jxcore-log: 
,11-21 17:15:28.712  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-21 17:15:28.712  5587  5635 I jxcore-log: 
,11-21 17:15:28.733  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-21 17:15:28.733  5587  5635 I jxcore-log: 
,11-21 17:15:28.740  5587  5635 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-21 17:15:28.741  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - INFO testUtils: 'BLE multiple advertisement supported'
11-21 17:15:28.741  5587  5635 I jxcore-log: 
,11-21 17:15:28.990  5587  5635 I jxcore-log: 2016-11-21 16:15:28 - DEBUG CoordinatedClient: 'connected to the test server'
11-21 17:15:28.990  5587  5635 I jxcore-log: 
,11-21 17:15:31.139  3587  3587 I ConfigService: onDestroy
,11-21 17:15:33.808   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=225303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:15:37.094   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:38.095   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:39.096   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:40.098   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:41.093   931  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:15:41.099   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:42.100   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-21 17:15:43.969   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=235464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:15:47.102   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:48.103   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:49.104   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:50.106   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:51.107   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:15:52.108   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-21 17:15:58.982   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=250477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:16:02.109   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:03.111   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:04.112   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:05.114   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:06.115   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:07.116   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-21 17:16:09.142   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=260637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:16:21.099   931  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:16:22.117   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:23.119   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:24.120   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:24.129   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=275623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:16:25.121   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:26.122   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:27.123   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 17:16:34.209   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=285704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:16:39.862   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=291357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:16:41.100   931  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:16:47.124   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:48.126   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:49.127   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:50.129   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:51.130   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:16:52.131   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 17:16:59.222   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=310717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:17:07.422   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=318917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-21 17:17:17.132   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 17:17:17.132   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 17:17:21.105   931  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:17:24.256   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=335750, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:17:32.133   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:33.135   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:34.136   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:35.138   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:36.139   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:37.140   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-21 17:17:39.249   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=350744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:17:41.109   931  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:17:42.141   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:43.142   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:44.143   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:45.144   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:46.145   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:47.146   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-21 17:17:49.302   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=360797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:17:57.147   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:58.149   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:59.150   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:17:59.461   931  2955 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:18:00.151   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:18:01.110   931  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:18:01.153   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:18:02.154   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-21 17:18:02.496   931  2955 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 17:18:04.289   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=375783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:18:14.342   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=385837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:18:17.155   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:18:18.156   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:18:19.158   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:18:20.159   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:18:21.160   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:18:22.161   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 17:18:29.316   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=400810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:18:39.436   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=410930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:18:41.113   931  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:18:42.163   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:18:43.164   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:18:44.165   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:18:45.167   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:18:46.168   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:18:47.169   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 17:18:54.396   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=425890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 17:19:01.114   931  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:19:12.170   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 17:19:12.170   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 17:19:21.115   931  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:19:26.424  5587  5635 I jxcore-log: 2016-11-21 16:19:26 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-21 17:19:26.424  5587  5635 I jxcore-log: 
,11-21 17:19:26.754  5587  5635 I jxcore-log: 2016-11-21 16:19:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:26.754  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:26.754  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:26.754  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:26.754  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:26.754  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:26.754  5587  5635 I jxcore-log: 
,11-21 17:19:26.760  5587  5635 I jxcore-log: 2016-11-21 16:19:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:26.760  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:26.760  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:26.760  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:26.760  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:26.760  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:26.760  5587  5635 I jxcore-log: 
,11-21 17:19:27.346  5587  5635 I jxcore-log: 2016-11-21 16:19:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:27.346  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:27.346  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:27.346  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:27.346  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:27.346  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:27.346  5587  5635 I jxcore-log: 
,11-21 17:19:27.350  5587  5635 I jxcore-log: 2016-11-21 16:19:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:27.350  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:27.350  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:27.350  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:27.350  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:27.350  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:27.350  5587  5635 I jxcore-log: 
,11-21 17:19:27.934  5587  5635 I jxcore-log: 2016-11-21 16:19:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:27.934  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:27.934  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:27.934  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:27.934  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:27.934  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:27.934  5587  5635 I jxcore-log: 
11-21 17:19:27.937  5587  5635 I jxcore-log: 2016-11-21 16:19:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:27.937  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:27.937  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:27.937  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:27.937  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:27.937  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:27.937  5587  5635 I jxcore-log: 
,11-21 17:19:29.168  5587  5635 I jxcore-log: 2016-11-21 16:19:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:29.168  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:29.168  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:29.168  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:29.168  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:29.168  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:29.168  5587  5635 I jxcore-log: 
,11-21 17:19:29.174  5587  5635 I jxcore-log: 2016-11-21 16:19:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:29.174  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:29.174  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:29.174  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:29.174  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:29.174  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:29.174  5587  5635 I jxcore-log: 
,11-21 17:19:29.489   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=460984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 17:19:30.211  5587  5635 I jxcore-log: 2016-11-21 16:19:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:30.211  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:30.211  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:30.211  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:30.211  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:30.211  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:30.211  5587  5635 I jxcore-log: 
,11-21 17:19:30.216  5587  5635 I jxcore-log: 2016-11-21 16:19:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:30.216  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:30.216  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:30.216  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:30.216  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:30.216  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:30.216  5587  5635 I jxcore-log: 
,11-21 17:19:31.252  5587  5635 I jxcore-log: 2016-11-21 16:19:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:31.252  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:31.252  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:31.252  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:31.252  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:31.252  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:31.252  5587  5635 I jxcore-log: 
,11-21 17:19:31.256  5587  5635 I jxcore-log: 2016-11-21 16:19:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:31.256  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:31.256  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:31.256  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:31.256  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:31.256  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:31.256  5587  5635 I jxcore-log: 
,11-21 17:19:32.172   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:19:32.295  5587  5635 I jxcore-log: 2016-11-21 16:19:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:32.295  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:32.295  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:32.295  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:32.295  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:32.295  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:32.295  5587  5635 I jxcore-log: 
,11-21 17:19:32.298  5587  5635 I jxcore-log: 2016-11-21 16:19:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:32.298  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:32.298  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:32.298  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:32.298  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:32.298  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:32.298  5587  5635 I jxcore-log: 
,11-21 17:19:33.173   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:19:33.331  5587  5635 I jxcore-log: 2016-11-21 16:19:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:33.331  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:33.331  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:33.331  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:33.331  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:33.331  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:33.331  5587  5635 I jxcore-log: 
,11-21 17:19:33.334  5587  5635 I jxcore-log: 2016-11-21 16:19:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:33.334  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:33.334  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:33.334  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:33.334  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:33.334  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:33.334  5587  5635 I jxcore-log: 
,11-21 17:19:34.175   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:19:34.373  5587  5635 I jxcore-log: 2016-11-21 16:19:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:34.373  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:34.373  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:34.373  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:34.373  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:34.373  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:34.373  5587  5635 I jxcore-log: 
,11-21 17:19:34.378  5587  5635 I jxcore-log: 2016-11-21 16:19:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:34.378  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:34.378  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:34.378  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:34.378  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:34.378  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:34.378  5587  5635 I jxcore-log: 
,11-21 17:19:35.176   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:19:35.196   931  5836 D NetlinkSocketObserver: NeighborEvent{elapsedMs=466690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-21 17:19:35.445  5587  5635 I jxcore-log: 2016-11-21 16:19:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:35.445  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:35.445  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:35.445  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:35.445  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:35.445  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:35.445  5587  5635 I jxcore-log: 
,11-21 17:19:35.450  5587  5635 I jxcore-log: 2016-11-21 16:19:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:35.450  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:35.450  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:35.450  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:35.450  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:35.450  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:35.450  5587  5635 I jxcore-log: 
,11-21 17:19:36.178   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:19:36.490  5587  5635 I jxcore-log: 2016-11-21 16:19:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:36.490  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:36.490  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:36.490  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:36.490  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:36.490  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:36.490  5587  5635 I jxcore-log: 
,11-21 17:19:36.497  5587  5635 I jxcore-log: 2016-11-21 16:19:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:36.497  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:36.497  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:36.497  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:36.497  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:36.497  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:36.497  5587  5635 I jxcore-log: 
,11-21 17:19:37.179   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-21 17:19:37.526  5587  5635 I jxcore-log: 2016-11-21 16:19:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:37.526  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:37.526  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:37.526  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:37.526  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:37.526  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:37.526  5587  5635 I jxcore-log: 
,11-21 17:19:37.531  5587  5635 I jxcore-log: 2016-11-21 16:19:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:37.531  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:37.531  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:37.531  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:37.531  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:37.531  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:37.531  5587  5635 I jxcore-log: 
,11-21 17:19:39.193  5587  5635 I jxcore-log: 2016-11-21 16:19:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:39.193  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:39.193  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:39.193  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:39.193  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:39.193  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:39.193  5587  5635 I jxcore-log: 
,11-21 17:19:39.201  5587  5635 I jxcore-log: 2016-11-21 16:19:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:39.201  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:39.201  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:39.201  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:39.201  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:39.201  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:39.201  5587  5635 I jxcore-log: 
,11-21 17:19:40.231  5587  5635 I jxcore-log: 2016-11-21 16:19:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:40.231  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:40.231  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:40.231  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:40.231  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:40.231  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:40.231  5587  5635 I jxcore-log: 
,11-21 17:19:40.236  5587  5635 I jxcore-log: 2016-11-21 16:19:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:40.236  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:40.236  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:40.236  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:40.236  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:40.236  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:40.236  5587  5635 I jxcore-log: 
,11-21 17:19:41.118   931  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 17:19:41.435  5587  5635 I jxcore-log: 2016-11-21 16:19:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 17:19:41.435  5587  5635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 17:19:41.435  5587  5635 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 17:19:41.435  5587  5635 I jxcore-log: emit@events.js:82:1
11-21 17:19:41.435  5587  5635 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 17:19:41.435  5587  5635 I jxcore-log: emit@events.js:82:1'
11-21 17:19:41.435  5587  5635 I jxcore-log: 
,11-21 17:19:41.447  5587  5635 E jxcore  : Error!: error is undefined
11-21 17:19:41.447  5587  5635 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-21 17:19:41.451  5587  5635 I jxcore-log: 2016-11-21 16:19:41 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-21 17:19:41.451  5587  5635 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-21 17:19:41.451  5587  5635 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-21 17:19:41.451  5587  5635 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-21 17:19:41.451  5587  5635 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-21 17:19:41.451  5587  5635 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-21 17:19:41.451  5587  5635 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-21 17:19:41.451  5587  5635 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-21 17:19:41.453  5587  5635 I jxcore-log: 2016-11-21 16:19:41 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-21 17:19:41.453  5587  5635 I jxcore-log: 
,11-21 17:19:41.455  5587  5635 E jxcore-log: TypeError: 
11-21 17:19:41.456  5587  5635 E jxcore-log: error is undefined
11-21 17:19:41.456  5587  5635 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-21 17:19:41.456  5587  5635 E jxcore-log: 
,11-21 17:19:41.520   931  2930 W InputDispatcher: channel '7d88687 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-21 17:19:41.520   931  2930 E InputDispatcher: channel '7d88687 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-21 17:19:41.530   931  3421 D GraphicsStats: Buffer count: 2
11-21 17:19:41.530   931  3807 I WindowState: WIN DEATH: Window{7d88687 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-21 17:19:41.530   931  3807 W InputDispatcher: Attempted to unregister already unregistered input channel '7d88687 com.test.thalitest/com.test.thalitest.MainActivity (server)'
11-21 17:19:41.531   931  2952 D WifiService: Client connection lost with reason: 4
11-21 17:19:41.536   931  3421 I ActivityManager: Process com.test.thalitest (pid 5587) has died
11-21 17:19:41.534   529   529 I Zygote  : Process 5587 exited cleanly (139)
11-21 17:19:41.538   931  3421 W ActivityManager: Force removing ActivityRecord{58376bc u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-21 17:19:41.597  3142  3142 W Binder_3: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[29812]" dev="sockfs" ino=29812 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 17:19:41.597  3142  3142 W Binder_3: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[29812]" dev="sockfs" ino=29812 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 17:19:41.597   931  3142 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5587 uid 10077
,11-21 17:19:41.604  3650  3650 I Keyboard.Facilitator: onFinishInput()
,11-21 17:19:41.659  3961  5888 I MicroRecognitionRnrImpl: Starting detection.
,11-21 17:19:41.661  3961  5889 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@fb2b402
,11-21 17:19:41.664   514  5891 I AudioFlinger: AudioFlinger's thread 0xf2280000 ready to run
,11-21 17:19:41.671   514  2987 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-21 17:19:41.672  3961  5889 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@fb2b402
,11-21 17:19:41.683   514  5891 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-21 17:19:41.683   514  5891 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-21 17:19:41.683   514  5891 I ACDB-LOADER: ACDB AFE returned = -19
11-21 17:19:41.683   514  5891 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-21 17:19:41.683   514  5891 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-21 17:19:41.683   514  5891 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-21 17:19:41.690   514  5891 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-21 17:19:41.769  3961  3961 I HotwordWorkerImpl: onReady
,11-21 17:19:41.951  5882  5882 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-21 17:19:41.956  5882  5882 D AndroidRuntime: CheckJNI is OFF
,11-21 17:19:41.980  5882  5882 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-21 17:19:42.010  5882  5882 I Radio-JNI: register_android_hardware_Radio DONE
,11-21 17:19:42.026  5882  5882 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-21 17:19:42.035   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-21 17:19:42.125  3812  4044 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-21 17:19:42.176   931   954 I art     : Starting a blocking GC Explicit
,11-21 17:19:42.179   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 17:19:42.259   931   954 I art     : Explicit concurrent mark sweep GC freed 22784(1287KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.494ms total 83.079ms
,11-21 17:19:42.280   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-21 17:19:42.284  5882  5882 I art     : System.exit called, status: 0
11-21 17:19:42.284  5882  5882 I AndroidRuntime: VM exiting with result code 0.
,11-21 17:19:42.300   931   954 I ActivityManager: Start proc 5902:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-21 17:19:42.300   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-21 17:19:42.309  5707  5707 D BluetoothMapAppObserver: onReceive
,11-21 17:19:42.310  5707  5707 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-21 17:19:42.310  3746  4092 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-21 17:19:42.315  3650  3650 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-21 17:19:42.321   931  2931 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-21 17:19:42.331  3407  5915 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-21 17:19:42.338  3650  5913 I Keyboard.Facilitator.DecoderInitializer: run()
,11-21 17:19:42.345  3650  5913 I Decoder : createOrResetDecoder
,11-21 17:19:42.363  3790  3790 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-21 17:19:42.380  3587  3587 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-21 17:19:42.380  3587  3587 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
11-21 17:19:42.381   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-21 17:19:42.395  3587  3587 I ConfigService: onCreate
,11-21 17:19:42.397  3982  5921 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-21 17:19:42.397  3982  5921 D AccountUtils: Clearing selected account for com.test.thalitest
,11-21 17:19:42.401    29    29 W kworker/3:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 17:19:42.410  3982  5921 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-21 17:19:42.411    29    29 W kworker/3:1: type=1400 audit(0.0:131): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 17:19:42.420  3650  5913 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-21 17:19:42.428  3982  3982 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-21 17:19:42.428  3982  3982 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-21 17:19:42.424    29    29 W kworker/3:1: type=1400 audit(0.0:132): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 17:19:42.434  3982  3982 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-21 17:19:42.434  3982  3982 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-21 17:19:42.439  3961  5931 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,11-21 17:19:42.450  3982  5927 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/metrics.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,11-21 17:19:42.451  3982  5927 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
,11-21 17:19:42.451  3982  5927 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
,11-21 17:19:42.451  3982  5927 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
,11-21 17:19:42.451  3982  5927 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/help_responses.db'.
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.b.a(SourceFile:108)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.b.d(SourceFile:529)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:19:42.453  3982  5927 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: Couldn't open help_responses.db for writing (will try read-only):
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.b.a(SourceFile:108)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.b.d(SourceFile:529)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:19:42.453  3982  5927 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 17:19:42.454  3407  5915 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-21 17:19:42.455  3982  5927 W SQLiteOpenHelper: Opened help_responses.db in read-only mode
11-21 17:19:42.455  3982  5927 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db, release reference: 1
11-21 17:19:42.455  3982  5927 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 2
,11-21 17:19:42.455  3982  5927 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 1
--------- beginning of crash
11-21 17:19:42.455  3407  5915 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-21 17:19:42.455  3407  5915 E AndroidRuntime: Process: android.process.acore, PID: 3407
11-21 17:19:42.455  3407  5915 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:19:42.455  3407  5915 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db'.
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.search.b.a(SourceFile:42)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:102)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:19:42.459  3982  5927 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: Couldn't open auto_complete_suggestions.db for writing (will try read-only):
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.search.b.a(SourceFile:42)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:102)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:19:42.459  3982  5927 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 17:19:42.461  3982  5927 W SQLiteOpenHelper: Opened auto_complete_suggestions.db in read-only mode
11-21 17:19:42.462  3982  5927 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
11-21 17:19:42.462  3982  5927 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 2
11-21 17:19:42.462  3982  5927 E SQLiteLog: (8) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-21 17:19:42.462  3982  5927 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 1
11-21 17:19:42.463  3982  5927 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-21 17:19:42.463  3982  5927 E AndroidRuntime: Process: com.google.android.gms, PID: 3982
11-21 17:19:42.463  3982  5927 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-21 17:19:42.463  3982  5927 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 17:19:42.463  3982  5927 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 17:19:42.463  3982  5927 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 17:19:42.463  3982  5927 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 17:19:42.463  3982  5927 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 17:19:42.463  3982  5927 E AndroidRuntime: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
11-21 17:19:42.463  3982  5927 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
11-21 17:19:42.463  3982  5927 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 17:19:42.463  3982  5927 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 17:19:42.463  3982  5927 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 17:19:42.463  3982  5927 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 17:19:42.467   931  5932 E DropBoxManagerService: Can't write: system_app_crash
11-21 17:19:42.467   931  5932 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
11-21 17:19:42.467   931  5932 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 17:19:42.467   931  5932 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 17:19:42.467   931  5932 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 17:19:42.467   931  5932 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 17:19:42.467   931  5932 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 17:19:42.467   931  5932 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 17:19:42.467   931  5932 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 17:19:42.467   931  5932 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 17:19:42.467   931  5932 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 17:19:42.467   931  5932 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 17:19:42.467   931  5932 E DropBoxManagerService: 	... 5 more
11-21 17:19:42.468  3812  4021 E ReflectionEngine: Failed to save models
11-21 17:19:42.468  3812  4021 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 17:19:42.468  3812  4021 E ReflectionEngine: 	... 16 more
11-21 17:19:42.469  3961  5931 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
11-21 17:19:42.476   931  5934 E DropBoxManagerService: Can't write: system_app_crash
11-21 17:19:42.476   931  5934 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
11-21 17:19:42.476   931  5934 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 17:19:42.476   931  5934 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 17:19:42.476   931  5934 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 17:19:42.476   931  5934 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 17:19:42.476   931  5934 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 17:19:42.476   931  5934 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 17:19:42.476   931  5934 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 17:19:42.476   931  5934 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 17:19:42.476   931  5934 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 17:19:42.476   931  5934 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 17:19:42.476   931  5934 E DropBoxManagerService: 	... 5 more
11-21 17:19:42.484   778   778 W Binder_4: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[27463]" dev="sockfs" ino=27463 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 17:19:42.484   778   778 W Binder_4: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[27463]" dev="sockfs" ino=27463 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 17:19:42.489   931  5936 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-21 17:19:42.487   406   406 W Binder_1: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[27465]" dev="sockfs" ino=27465 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 17:19:42.487   406   406 W Binder_1: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[27465]" dev="sockfs" ino=27465 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: Failed to write the stream file
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2439: open failed: EROFS (Read-only file system)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 17:19:42.491  3812  4021 E ObservedEventLogger: 	... 16 more
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: Failed to write the stream file
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2440: open failed: EROFS (Read-only file system)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 17:19:42.492  3812  4021 E ObservedEventLogger: 	... 16 more
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: Failed to write the stream file
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2441: open failed: EROFS (Read-only file system)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 17:19:42.493  3812  4021 E ObservedEventLogger: 	... 16 more
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: Failed to write the stream file
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2442: open failed: EROFS (Read-only file system)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor,.java:269)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 17:19:42.494  3812  4021 E ObservedEventLogger: 	... 16 more
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: Failed to write the stream file
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2443: open failed: EROFS (Read-only file system)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 17:19:42.495  3812  4021 E ObservedEventLogger: 	... 16 more
11-21 17:19:42.498  3650  5913 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-21 17:19:42.502  3650  5913 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-21 17:19:42.502  3650  5913 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-21 17:19:42.505  3650  5913 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-21 17:19:42.505  3650  5913 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-21 17:19:42.506  3650  5913 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-21 17:19:42.506  3650  5913 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-21 17:19:42.506  3650  5913 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-21 17:19:42.507  3650  5913 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-21 17:19:42.507  3650  5913 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-21 17:19:42.507  3650  5913 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-21 17:19:42.507  3650  5913 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-21 17:19:42.507  3650  5913 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-21 17:19:42.512   931   941 I ActivityManager: Start proc 5937:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
11-21 17:19:42.524   931  3603 I ActivityManager: Start proc 5942:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-21 17:19:42.534  3982  5929 W BaseAppContext: Using Auth Proxy for data requests.
,11-21 17:19:42.537  3982  5929 W BaseAppContext: Using Auth Proxy for data requests.
,11-21 17:19:42.571   931   944 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{1e012d3 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{31a5d0d 3982 com.google.android.gms/10012/u0 remote:dae4ba4}: process crashing
,11-21 17:19:42.577   931  3820 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3982 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-21 17:19:42.636  3982  5926 W DriveInitializer: Awaiting to be initialized
,11-21 17:19:42.636  3982  5949 W DriveInitializer: Background init thread started
,11-21 17:19:42.812   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
