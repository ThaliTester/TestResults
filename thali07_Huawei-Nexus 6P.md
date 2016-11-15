#### Test 9376531715755df_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-15 18:29:04.553  3882  4244 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-15 18:29:04.631  3882  4244 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-15 18:29:04.947  5614  5614 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-15 18:29:04.952  5614  5614 D AndroidRuntime: CheckJNI is OFF
11-15 18:29:04.977  5614  5614 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-15 18:29:05.009  5614  5614 I Radio-JNI: register_android_hardware_Radio DONE
11-15 18:29:05.024  5614  5614 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-15 18:29:05.038   928  3173 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-15 18:29:05.062  3993  4003 W SearchService: Abort, client detached.
11-15 18:29:05.065  5614  5614 D AndroidRuntime: Shutting down VM
11-15 18:29:05.065  3993  3993 I HotwordDetector: Closing mic
11-15 18:29:05.066  3993  4212 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a285f35
11-15 18:29:05.069  3993  4232 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-15 18:29:05.096   928  3885 I ActivityManager: Start proc 5623:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-15 18:29:05.149   513  4234 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-15 18:29:05.150   513  4234 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-15 18:29:05.155   513  4234 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-15 18:29:05.155   513  4234 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-15 18:29:05.156   513  3017 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-15 18:29:05.158  3993  4224 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-15 18:29:05.160  3993  4228 I MicroRecognitionRnrImpl: Detection finished
11-15 18:29:05.188  5623  5623 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-15 18:29:05.216  5623  5623 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-15 18:29:05.276  5623  5623 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 4881-4936)
11-15 18:29:05.276  5623  5623 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-15 18:29:05.311  5623  5623 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6f4e741}
,11-15 18:29:05.311  5623  5623 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-15 18:29:05.311  5623  5623 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-15 18:29:05.314  5623  5623 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-15 18:29:05.315  5623  5623 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-15 18:29:05.363  5623  5623 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-15 18:29:05.372  5623  5623 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-15 18:29:05.372  5623  5623 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-15 18:29:05.372  5623  5623 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-15 18:29:05.372  5623  5623 I Adreno  : Build Date                       : 12/06/15
11-15 18:29:05.372  5623  5623 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-15 18:29:05.372  5623  5623 I Adreno  : Local Branch                     : mybranch17112971
11-15 18:29:05.372  5623  5623 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-15 18:29:05.372  5623  5623 I Adreno  : Remote Branch                    : NONE
11-15 18:29:05.372  5623  5623 I Adreno  : Reconstruct Branch               : NOTHING
,11-15 18:29:05.413   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@840a96f:true
,11-15 18:29:05.447   405   405 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[21330]" dev="sockfs" ino=21330 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 18:29:05.447   405   405 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[21330]" dev="sockfs" ino=21330 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 18:29:05.461  5623  5623 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-15 18:29:05.470  5623  5623 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-15 18:29:05.494   405   405 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33232]" dev="sockfs" ino=33232 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 18:29:05.497  5623  5660 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-15 18:29:05.494   405   405 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33232]" dev="sockfs" ino=33232 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 18:29:05.497  3893  3893 W Binder_F: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33801]" dev="sockfs" ino=33801 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 18:29:05.497  3893  3893 W Binder_F: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33801]" dev="sockfs" ino=33801 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 18:29:05.501  5623  5647 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-15 18:29:05.530  5623  5660 I OpenGLRenderer: Initialized EGL, version 1.4
,11-15 18:29:05.619  3679  3679 I Keyboard.Facilitator: onFinishInput()
,11-15 18:29:05.619   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +540ms
,11-15 18:29:05.614  3616  3616 W Binder_6: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32090]" dev="sockfs" ino=32090 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 18:29:05.614  3616  3616 W Binder_6: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32090]" dev="sockfs" ino=32090 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 18:29:05.614  3851  3851 W Binder_9: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32089]" dev="sockfs" ino=32089 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 18:29:05.614  3851  3851 W Binder_9: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32089]" dev="sockfs" ino=32089 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 18:29:05.651  5623  5623 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5623
,11-15 18:29:05.747  5623  5623 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-15 18:29:06.081  5623  5662 D jxcore_app_log: JniHelper::setJavaVM(0xf4f3c000), pthread_self() = -583796432
,11-15 18:29:06.098  5623  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-15 18:29:06.098  5623  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-15 18:29:06.098  5623  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-15 18:29:06.098  5623  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-15 18:29:06.098  5623  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-15 18:29:06.099  5623  5662 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1fa1f5 added. We now have 1 listener(s)
,11-15 18:29:06.106  5623  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
11-15 18:29:06.108  5623  5662 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 18:29:06.109  5623  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 18:29:06.110  5623  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-15 18:29:06.121  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-15 18:29:06.122  5623  5662 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f29618 added. We now have 1 listener(s)
11-15 18:29:06.122  5623  5662 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 18:29:06.128   928  2986 D WifiService: New client listening to asynchronous messages
,11-15 18:29:06.130  5623  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 18:29:06.130  5623  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-15 18:29:06.130  5623  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-15 18:29:06.131  5623  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-15 18:29:06.131  5623  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-15 18:29:06.131  5623  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-15 18:29:06.131  5623  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-15 18:29:06.136  5623  5662 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-15 18:29:06.339  5623  5623 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-15 18:29:06.735  5623  5632 I art     : Background sticky concurrent mark sweep GC freed 79346(7MB) AllocSpace objects, 16(1476KB) LOS objects, 26% free, 24MB/32MB, paused 1.806ms total 292.828ms
,11-15 18:29:07.567  5623  5670 W jxcore-log: Initializing JXcore engine
11-15 18:29:07.567  5623  5670 W jxcore-log: JXcore engine is ready
,11-15 18:29:07.587  5670  5670 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11870 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-15 18:29:07.587  5670  5670 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[16408]" dev="sockfs" ino=16408 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-15 18:29:07.587  5670  5670 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-15 18:29:07.587  5670  5670 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32064]" dev="sockfs" ino=32064 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-15 18:29:07.604  5623  5670 W jxcore-log: Starting JXcore engine
,11-15 18:29:07.655  5623  5670 W jxcore-log: Platform android
11-15 18:29:07.655  5623  5670 W jxcore-log: 
,11-15 18:29:07.655  5623  5670 W jxcore-log: Process ARCH arm
11-15 18:29:07.655  5623  5670 W jxcore-log: 
,11-15 18:29:07.793  5623  5670 I jxcore-log: JXcore Cordova bridge is ready!
11-15 18:29:07.793  5623  5670 I jxcore-log: 
,11-15 18:29:07.794  5623  5670 W jxcore-log: JXcore engine is started
,11-15 18:29:07.800  5623  5662 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-15 18:29:07.808  5623  5623 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-15 18:29:09.014  3602  3602 I ConfigService: onDestroy
,11-15 18:29:10.077   928   938 I ActivityManager: Killing 5068:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-15 18:29:11.738   928  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 18:29:14.968   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:29:15.162  3993  5671 W CronetSyncConnectionRcs: Upload content type not set.
,11-15 18:29:15.970   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:29:16.971   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:29:17.666  5623  5670 I jxcore-log: 2016-11-15 17:29:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-15 18:29:17.666  5623  5670 I jxcore-log: 
,11-15 18:29:17.668  5623  5670 I jxcore-log: 2016-11-15 17:29:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-15 18:29:17.668  5623  5670 I jxcore-log: 
,11-15 18:29:17.673  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-15 18:29:17.674  5623  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 18:29:17.674  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 18:29:17.674  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 18:29:17.674  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 18:29:17.674  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 18:29:17.674  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 18:29:17.674  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 18:29:17.674  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 18:29:17.674  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 18:29:17.675  5623  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 18:29:17.676  5623  5670 I jxcore-log: 2016-11-15 17:29:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-15 18:29:17.676  5623  5670 I jxcore-log: 
,11-15 18:29:17.677  5623  5670 I jxcore-log: 2016-11-15 17:29:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-15 18:29:17.677  5623  5670 I jxcore-log: 
,11-15 18:29:17.931  5623  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-15 18:29:17.931  5623  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc0c16 added. We now have 2 listener(s)
,11-15 18:29:17.931  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 18:29:17.932  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 18:29:17.932  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 18:29:17.932  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 18:29:17.932  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c940997 added. We now have 2 listener(s)
11-15 18:29:17.932  5623  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 18:29:17.933  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-15 18:29:17.934  5623  5670 D ExecuteNativeTests: Running unit tests
11-15 18:29:17.934  5623  5670 D BluetoothAdapter: enable(): BT is already enabled..!
11-15 18:29:17.935   928   938 D WifiService: setWifiEnabled: true pid=5623, uid=10077
,11-15 18:29:17.935   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 18:29:17.972   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:29:18.346  4866  4909 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-15 18:29:18.348  4866  4866 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-15 18:29:18.351   928  3887 I ActivityManager: Killing 5410:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-15 18:29:18.973   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:29:19.974   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-15 18:29:27.940  5623  5670 I com.test.thalitest.ThaliTestRunner: Running UT
,11-15 18:29:28.007  5623  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 18:29:28.007  5623  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebbf038 added. We now have 3 listener(s)
11-15 18:29:28.008  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 18:29:28.008  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-15 18:29:28.009  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 18:29:28.009  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 18:29:28.009  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c868811 added. We now have 3 listener(s)
11-15 18:29:28.009  5623  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 18:29:28.010  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 18:29:28.015  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-15 18:29:28.015  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 18:29:28.016  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 18:29:28.016  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 18:29:28.016  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 18:29:28.017  5623  5670 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-15 18:29:28.017  5623  5670 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-15 18:29:28.017  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 18:29:28.017  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 18:29:28.017  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 18:29:28.017  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 18:29:28.018  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-15 18:29:28.019  5623  5670 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-15 18:29:28.020  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-15 18:29:28.022  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-15 18:29:28.022  5623  5670 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-15 18:29:28.025  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 18:29:28.025  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 18:29:28.030  5623  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 18:29:28.030  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 18:29:28.030  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 18:29:28.030  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 18:29:28.030  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 18:29:28.030  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 18:29:28.030  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 18:29:28.030  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 18:29:28.030  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 18:29:28.031  5623  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-15 18:29:28.031  5623  5670 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-15 18:29:28.031  5623  5670 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-15 18:29:28.031  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-15 18:29:28.032  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.032  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.032  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.032  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 18:29:28.032  5623  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 18:29:28.032  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 18:29:28.032  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 18:29:28.032  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-15 18:29:28.033  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 18:29:28.033  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 18:29:28.033  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 18:29:28.033  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 18:29:28.033  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 18:29:28.033  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 18:29:28.033  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 18:29:28.034  5623  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-15 18:29:28.038  5623  5623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 18:29:28.038  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 18:29:28.038  5623  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 18:29:28.038  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 18:29:28.040  5623  5677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 18:29:28.043  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:28.043  5623  5623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 18:29:28.043  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 18:29:28.043  5623  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 18:29:28.043  5623  5623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 18:29:28.037  4684  4684 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29579]" dev="sockfs" ino=29579 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 18:29:28.044  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 18:29:28.037  4684  4684 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[29579]" dev="sockfs" ino=29579 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 18:29:28.044  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-15 18:29:28.044  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-15 18:29:28.045  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.045  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.045  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 18:29:28.045  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 18:29:28.046  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 18:29:28.046  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-15 18:29:28.046  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:28.046  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 18:29:28.046  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.046  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 18:29:28.046  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:28.046  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.046  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.047  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.047  5623  5670 D BluetoothAdapter: STATE_ON
,11-15 18:29:28.051  4670  5678 D BtGatt.GattService: registerClient() - UUID=6ff7243c-0245-4f9d-ac91-9842c0e8c028
,11-15 18:29:28.052  4670  4743 D BtGatt.GattService: onClientRegistered() - UUID=6ff7243c-0245-4f9d-ac91-9842c0e8c028, clientIf=5
,11-15 18:29:28.053  5623  5633 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-15 18:29:28.055  4670  4745 D BtGatt.AdvertiseManager: message : 0
,11-15 18:29:28.058  4670  4745 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 18:29:28.069  4670  4743 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 18:29:28.076  4670  4743 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 18:29:28.077  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.077  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.077  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 18:29:28.078  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.078  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:28.078  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.079  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.079  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.079  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-15 18:29:28.080  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 18:29:28.080  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.080  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:28.080  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.080  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.081  5623  5670 I io.jxcore.node.ConnectionHelper: start: OK
,11-15 18:29:28.081  5623  5623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-15 18:29:28.081  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.081  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:28.081  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 18:29:28.082  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.082  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.082  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:28.082  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.082  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 18:29:28.082  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-15 18:29:28.082  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.082  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.083  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 18:29:28.083  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.085  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.085  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 18:29:28.085  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.085  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.085  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.086  5623  5623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 18:29:28.584  5623  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 18:29:28.584  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-15 18:29:28.584  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-15 18:29:28.584  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-15 18:29:28.584  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-15 18:29:28.584  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-15 18:29:28.585  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-15 18:29:28.585  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-15 18:29:28.585  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-15 18:29:28.585  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-15 18:29:28.585  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-15 18:29:28.585  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-15 18:29:28.585  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-15 18:29:28.585  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-15 18:29:28.585  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-15 18:29:28.585  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-15 18:29:28.586  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-15 18:29:28.586  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-15 18:29:28.586  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-15 18:29:28.586  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-15 18:29:28.586  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-15 18:29:28.586  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-15 18:29:28.586  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-15 18:29:28.586  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-15 18:29:28.586  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-15 18:29:28.587  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-15 18:29:28.587  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-15 18:29:28.587  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-15 18:29:28.587  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-15 18:29:28.587  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-15 18:29:28.587  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-15 18:29:28.587  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-15 18:29:28.587  5623  5623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-15 18:29:28.587  5623  5670 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-15 18:29:28.588  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-15 18:29:28.588  5623  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 18:29:28.589  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 18:29:28.589  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-15 18:29:28.589  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 18:29:28.590  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 18:29:28.590  5623  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-15 18:29:28.590  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 18:29:28.590  5623  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-15 18:29:28.590  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 18:29:28.590  5623  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 18:29:28.590  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 18:29:28.590  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-15 18:29:28.590  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 18:29:28.591  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 18:29:28.591  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.592  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.592  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.592  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.594  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:28.595  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 18:29:28.597  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:28.597  5623  5670 D BluetoothLeScanner: could not find callback wrapper
11-15 18:29:28.597  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 18:29:28.598  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.598  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.598  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.599  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 18:29:28.599  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.601  4670  4745 D BtGatt.AdvertiseManager: message : 1
11-15 18:29:28.602  4670  4745 D BtGatt.AdvertiseManager: stop advertise for client 5
11-15 18:29:28.613  4670  4743 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-15 18:29:28.613  4670  4743 D BtGatt.GattService: Client app is not null!
,11-15 18:29:28.615  4670  4880 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 18:29:28.616  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 18:29:28.616  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.616  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 18:29:28.616  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.616  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.617  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.617  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 18:29:28.617  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 18:29:28.618  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 18:29:28.618  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.621  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.621  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 18:29:28.621  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.621  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.621  5623  5623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 18:29:28.621  5623  5623 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-15 18:29:28.623  5623  5623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 18:29:28.623  5623  5623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 18:29:28.623  5623  5623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 18:29:28.623  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 18:29:28.623  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 18:29:28.623  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:28.624  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.624  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 18:29:28.624  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 18:29:28.624  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.624  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.624  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 18:29:28.624  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.624  5623  5670 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-15 18:29:28.624  5623  5670 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-15 18:29:28.625  5623  5670 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-15 18:29:28.625  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-15 18:29:28.625  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.625  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.625  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.625  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 18:29:28.625  5623  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 18:29:28.625  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 18:29:28.625  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 18:29:28.626  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.626  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 18:29:28.627  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.627  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.627  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.627  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 18:29:28.627  5623  5623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 18:29:28.627  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 18:29:28.627  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 18:29:28.627  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 18:29:28.627  5623  5623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 18:29:28.627  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 18:29:28.628  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 18:29:28.628  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 18:29:28.628  5623  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 18:29:28.628  5623  5681 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 18:29:28.627  4687  4687 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31147]" dev="sockfs" ino=31147 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 18:29:28.633  5623  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 18:29:28.633  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 18:29:28.633  5623  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 18:29:28.633  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 18:29:28.630  4687  4687 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31147]" dev="sockfs" ino=31147 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 18:29:28.638  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.638  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 18:29:28.639  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 18:29:28.639  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 18:29:28.639  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-15 18:29:28.643  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.643  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.644  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 18:29:28.644  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 18:29:28.644  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 18:29:28.644  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-15 18:29:28.644  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:28.644  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:28.644  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.644  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 18:29:28.645  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:28.645  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.645  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.645  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.646  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:28.649  4670  4880 D BtGatt.GattService: registerClient() - UUID=41d108c4-ae9a-42d1-8fde-e7bcef61dcd1
11-15 18:29:28.650  4670  4743 D BtGatt.GattService: onClientRegistered() - UUID=41d108c4-ae9a-42d1-8fde-e7bcef61dcd1, clientIf=5
11-15 18:29:28.650  5623  5633 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-15 18:29:28.651  4670  4745 D BtGatt.AdvertiseManager: message : 0
,11-15 18:29:28.654  4670  4745 D BtGatt.AdvertiseManager: starting multi advertising
11-15 18:29:28.667  4670  4743 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-15 18:29:28.674  4670  4743 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-15 18:29:28.675  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.675  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.675  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 18:29:28.675  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.675  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.675  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.675  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.676  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.676  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 18:29:28.677  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 18:29:28.677  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.679  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.679  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.679  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:28.679  5623  5670 I io.jxcore.node.ConnectionHelper: start: OK
11-15 18:29:28.679  5623  5623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 18:29:28.679  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.679  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:28.680  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 18:29:28.680  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.680  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.680  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:28.680  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.680  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 18:29:28.680  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 18:29:28.680  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.680  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.680  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 18:29:28.681  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.684  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.685  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 18:29:28.685  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.685  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.685  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:28.685  5623  5623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 18:29:28.933   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 18:29:29.184  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-15 18:29:29.184  5623  5670 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-15 18:29:29.184  5623  5670 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-15 18:29:29.184  5623  5670 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-15 18:29:29.184  5623  5670 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-15 18:29:29.185  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,11-15 18:29:29.185  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.185  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.185  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.186  5623  5623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-15 18:29:29.187  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-15 18:29:29.187  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-15 18:29:29.187  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-15 18:29:29.187  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-15 18:29:29.187  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-15 18:29:29.187  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-15 18:29:29.187  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-15 18:29:29.187  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-15 18:29:29.187  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-15 18:29:29.187  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.187  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-15 18:29:29.188  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.189  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.189  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.192  4670  4745 D BtGatt.AdvertiseManager: message : 1
11-15 18:29:29.194  4670  4745 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 18:29:29.209  4670  4743 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-15 18:29:29.209  4670  4743 D BtGatt.GattService: Client app is not null!
11-15 18:29:29.211  4670  5678 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 18:29:29.211  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 18:29:29.212  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.212  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 18:29:29.212  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.212  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.213  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 18:29:29.213  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.213  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.213  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 18:29:29.213  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 18:29:29.214  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 18:29:29.214  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
,11-15 18:29:29.214  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 18:29:29.214  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:29.215  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.215  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 18:29:29.215  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:29.215  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.215  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.215  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.218  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:29.222  4670  5678 D BtGatt.GattService: registerClient() - UUID=2fb43b90-180b-46e0-87f4-61ea45a332da
11-15 18:29:29.223  4670  4743 D BtGatt.GattService: onClientRegistered() - UUID=2fb43b90-180b-46e0-87f4-61ea45a332da, clientIf=5
11-15 18:29:29.224  5623  5634 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-15 18:29:29.225  4670  4745 D BtGatt.AdvertiseManager: message : 0
,11-15 18:29:29.231  4670  4745 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 18:29:29.244  4670  4743 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 18:29:29.251  4670  4743 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 18:29:29.252  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.252  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.252  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 18:29:29.252  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.252  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.252  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.252  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.252  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.252  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.253  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-15 18:29:29.253  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.253  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 18:29:29.253  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-15 18:29:29.253  5623  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 18:29:29.253  5623  5670 I io.jxcore.node.ConnectionHelper: start: OK
11-15 18:29:29.254  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.254  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:29.254  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 18:29:29.254  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.254  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.254  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:29.254  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-15 18:29:29.254  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 18:29:29.254  5623  5670 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 18:29:29.254  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 18:29:29.255  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-15 18:29:29.255  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.255  5623  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 18:29:29.255  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.255  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 18:29:29.255  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 18:29:29.255  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 18:29:29.255  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 18:29:29.255  5623  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-15 18:29:29.255  5623  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 18:29:29.255  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 18:29:29.255  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 18:29:29.255  5623  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 18:29:29.255  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 18:29:29.255  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 18:29:29.255  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 18:29:29.255  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 18:29:29.255  5623  5623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 18:29:29.255  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.255  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.256  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.256  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.257  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:29.257  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 18:29:29.257  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:29.257  5623  5670 D BluetoothLeScanner: could not find callback wrapper
11-15 18:29:29.257  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 18:29:29.257  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.258  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.258  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.258  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 18:29:29.258  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.258  4670  4745 D BtGatt.AdvertiseManager: message : 1
11-15 18:29:29.259  4670  4745 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 18:29:29.266  4670  4743 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-15 18:29:29.266  4670  4743 D BtGatt.GattService: Client app is not null!
,11-15 18:29:29.267  4670  4684 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 18:29:29.267  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 18:29:29.268  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.268  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-15 18:29:29.268  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.268  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.268  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.268  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 18:29:29.268  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 18:29:29.269  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 18:29:29.269  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.270  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.270  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 18:29:29.270  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.270  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.271  5623  5623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 18:29:29.271  5623  5623 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-15 18:29:29.271  5623  5623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 18:29:29.271  5623  5623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 18:29:29.271  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 18:29:29.271  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-15 18:29:29.271  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-15 18:29:29.271  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.271  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 18:29:29.271  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 18:29:29.271  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.272  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.272  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-15 18:29:29.272  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.273  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.273  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.273  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.273  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.273  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-15 18:29:29.273  5623  5623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 18:29:29.274  5623  5670 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-15 18:29:29.275  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,11-15 18:29:29.276  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-15 18:29:29.277  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-15 18:29:29.277  5623  5670 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-15 18:29:29.278  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-15 18:29:29.278  5623  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-15 18:29:29.278  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-15 18:29:29.278  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 18:29:29.279  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 18:29:29.279  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 18:29:29.279  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 18:29:29.279  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 18:29:29.279  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-15 18:29:29.279  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 18:29:29.279  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 18:29:29.279  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 18:29:29.279  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 18:29:29.279  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 18:29:29.279  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-15 18:29:29.280  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
,11-15 18:29:29.281  5623  5670 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 18:29:29.281  5623  5670 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-15 18:29:29.286  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-15 18:29:29.286  5623  5670 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-15 18:29:29.289  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,11-15 18:29:29.289  5623  5670 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-15 18:29:29.290  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-15 18:29:29.290  5623  5670 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-15 18:29:29.290  5623  5670 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-15 18:29:29.290  5623  5670 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-15 18:29:29.290  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 18:29:29.291  5623  5670 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-15 18:29:29.291  5623  5670 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-15 18:29:29.291  5623  5670 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-15 18:29:29.292  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 18:29:29.292  5623  5670 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-15 18:29:29.292  5623  5670 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-15 18:29:29.292  5623  5670 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-15 18:29:29.292  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 18:29:29.292  5623  5670 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-15 18:29:29.293  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-15 18:29:29.293  5623  5670 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-15 18:29:29.293  5623  5670 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-15 18:29:29.293  5623  5670 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-15 18:29:29.293  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-15 18:29:29.293  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.293  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.294  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.294  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 18:29:29.294  5623  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 18:29:29.294  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 18:29:29.294  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 18:29:29.295  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-15 18:29:29.296  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 18:29:29.296  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 18:29:29.296  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 18:29:29.296  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 18:29:29.296  5623  5623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 18:29:29.296  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 18:29:29.296  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 18:29:29.296  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-15 18:29:29.296  5623  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 18:29:29.297  5623  5685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 18:29:29.294  4880  4880 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[21350]" dev="sockfs" ino=21350 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 18:29:29.297  4880  4880 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[21350]" dev="sockfs" ino=21350 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 18:29:29.300  5623  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 18:29:29.301  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 18:29:29.301  5623  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 18:29:29.301  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-15 18:29:29.304  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.304  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 18:29:29.304  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 18:29:29.304  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 18:29:29.304  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-15 18:29:29.305  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.306  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.306  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 18:29:29.306  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 18:29:29.306  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 18:29:29.306  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
,11-15 18:29:29.306  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:29.306  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:29.306  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.306  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 18:29:29.306  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:29.306  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.306  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.306  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.307  5623  5670 D BluetoothAdapter: STATE_ON
,11-15 18:29:29.310  4670  4880 D BtGatt.GattService: registerClient() - UUID=b632f69c-caa5-4fcd-9ceb-d5032eebfea6
,11-15 18:29:29.310  4670  4743 D BtGatt.GattService: onClientRegistered() - UUID=b632f69c-caa5-4fcd-9ceb-d5032eebfea6, clientIf=5
11-15 18:29:29.310  5623  5633 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-15 18:29:29.311  4670  4745 D BtGatt.AdvertiseManager: message : 0
,11-15 18:29:29.313  4670  4745 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 18:29:29.322  4670  4743 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 18:29:29.327  4670  4743 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 18:29:29.328  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.328  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.328  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 18:29:29.328  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.328  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.328  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.328  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.328  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.328  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 18:29:29.329  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 18:29:29.330  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.330  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.330  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.331  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.331  5623  5670 I io.jxcore.node.ConnectionHelper: start: OK
11-15 18:29:29.331  5623  5623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-15 18:29:29.331  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-15 18:29:29.331  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:29.331  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 18:29:29.331  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.331  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.331  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:29.331  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.331  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 18:29:29.332  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 18:29:29.332  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.332  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.332  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 18:29:29.332  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-15 18:29:29.334  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.334  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 18:29:29.334  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.334  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.334  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.334  5623  5623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 18:29:29.832  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 18:29:29.833  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 18:29:29.833  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 18:29:29.833  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 18:29:29.833  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 18:29:29.834  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 18:29:29.834  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 18:29:29.834  5623  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-15 18:29:29.834  5623  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 18:29:29.834  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 18:29:29.834  5623  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 18:29:29.834  5623  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebbf038 removed from the list
,11-15 18:29:29.834  5623  5623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 18:29:29.835  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 18:29:29.835  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 18:29:29.835  5623  5623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-15 18:29:29.835  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-15 18:29:29.835  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 18:29:29.835  5623  5623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 18:29:29.835  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.835  5623  5623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 18:29:29.835  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.836  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.836  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.838  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:29.838  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 18:29:29.840  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:29.840  5623  5670 D BluetoothLeScanner: could not find callback wrapper
11-15 18:29:29.840  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 18:29:29.841  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.841  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.841  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.841  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 18:29:29.841  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.843  4670  4745 D BtGatt.AdvertiseManager: message : 1
11-15 18:29:29.844  4670  4745 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 18:29:29.858  4670  4743 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-15 18:29:29.858  4670  4743 D BtGatt.GattService: Client app is not null!
11-15 18:29:29.860  4670  4684 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 18:29:29.861  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 18:29:29.862  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.862  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 18:29:29.862  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.862  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.862  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.862  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-15 18:29:29.863  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 18:29:29.864  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-15 18:29:29.864  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.866  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.866  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 18:29:29.867  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:29.867  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:29.867  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c868811 removed from the list
11-15 18:29:29.867  5623  5670 D io.jxcore.node.ConnectivityMonitor: stop
11-15 18:29:29.867  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-15 18:29:29.867  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 18:29:29.867  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 18:29:29.868  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:29.868  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.868  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-15 18:29:29.868  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 18:29:29.868  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.868  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.869  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 18:29:29.869  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-15 18:29:29.872  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.872  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.873  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:29.873  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-15 18:29:29.873  5623  5623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 18:29:30.374  5623  5623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 18:29:31.949   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 18:29:34.873  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-15 18:29:34.875  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 18:29:34.876  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 18:29:34.876  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 18:29:34.882  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-15 18:29:34.883  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 18:29:34.883  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 18:29:34.883  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 18:29:34.884  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 18:29:34.884  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 18:29:34.884  5623  5623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-15 18:29:34.884  5623  5686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 18:29:34.886  5623  5686 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 18:29:34.887  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-15 18:29:34.889  5623  5670 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-15 18:29:34.890  5623  5670 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-15 18:29:34.891  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 18:29:34.891  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 18:29:34.891  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-15 18:29:34.890  4684  4684 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32132]" dev="sockfs" ino=32132 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 18:29:34.894  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-15 18:29:34.896  5623  5686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 18:29:34.894  4684  4684 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32132]" dev="sockfs" ino=32132 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 18:29:34.904  5623  5670 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-15 18:29:34.905  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 18:29:34.905  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-15 18:29:34.905  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 18:29:34.905  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 18:29:34.906  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 18:29:34.906  5623  5686 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 18:29:34.906  5623  5686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-15 18:29:34.906  5623  5686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 18:29:34.906  5623  5623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 18:29:34.907  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 18:29:34.907  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 18:29:34.907  5623  5670 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebbf038 not in the list
11-15 18:29:34.907  5623  5623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 18:29:34.907  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-15 18:29:34.907  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 18:29:34.907  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 18:29:34.907  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 18:29:34.907  5623  5623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 18:29:34.907  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:34.909  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:34.909  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 18:29:34.910  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:34.910  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:34.910  5623  5670 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c868811 not in the list
11-15 18:29:34.910  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 18:29:34.910  5623  5670 D io.jxcore.node.ConnectivityMonitor: stop
11-15 18:29:34.910  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-15 18:29:34.910  5623  5623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 18:29:34.912  5623  5670 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-15 18:29:34.912  5623  5670 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-15 18:29:34.913  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-15 18:29:34.914  5623  5670 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-15 18:29:34.914  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 18:29:34.914  5623  5670 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-15 18:29:34.915  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 18:29:34.916  5623  5670 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-15 18:29:34.917  5623  5670 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-15 18:29:34.919  5623  5670 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-15 18:29:34.919  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-15 18:29:34.920  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-15 18:29:34.921  5623  5670 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-15 18:29:34.921  5623  5670 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-15 18:29:34.921  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-15 18:29:34.921  5623  5670 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-15 18:29:34.922  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-15 18:29:34.922  5623  5670 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-15 18:29:34.922  5623  5670 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-15 18:29:34.924  5623  5670 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,11-15 18:29:34.924  5623  5670 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-15 18:29:34.924  5623  5670 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-15 18:29:34.925  5623  5670 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-15 18:29:34.925  5623  5670 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-15 18:29:34.925  5623  5670 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-15 18:29:34.926  5623  5670 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-15 18:29:34.926  5623  5670 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-15 18:29:34.926  5623  5670 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-15 18:29:34.927  5623  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-15 18:29:34.927  5623  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@727d467 added. We now have 3 listener(s)
11-15 18:29:34.929  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 18:29:34.929  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 18:29:34.929  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 18:29:34.929  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-15 18:29:34.929  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d570214 added. We now have 3 listener(s)
11-15 18:29:34.929  5623  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 18:29:34.930  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 18:29:34.932  5623  5670 D BluetoothAdapter: enable(): BT is already enabled..!
11-15 18:29:34.933   928  3616 D WifiService: setWifiEnabled: true pid=5623, uid=10077
11-15 18:29:34.933   928  3616 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 18:29:34.935  5623  5670 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-15 18:29:34.938  5623  5670 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-15 18:29:34.939  5623  5670 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-15 18:29:34.944  5623  5670 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-15 18:29:34.945  5623  5670 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-15 18:29:34.951  4670  4739 D BluetoothAdapterState: Current state: ON, message: 23
11-15 18:29:34.951  4670  4739 D BluetoothAdapterProperties: Setting state to 13
,11-15 18:29:34.951  4670  4739 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-15 18:29:34.951  5623  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 18:29:34.951  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 18:29:34.951  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 18:29:34.951  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 18:29:34.951  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 18:29:34.951  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 18:29:34.951  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 18:29:34.951  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 18:29:34.951  5623  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 18:29:34.952  4670  4739 D BluetoothAdapterProperties: onBluetoothDisable()
11-15 18:29:34.953  4670  4739 I BluetoothAdapterState: Entering PendingCommandState
,11-15 18:29:34.953  5623  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 18:29:34.953  5623  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-15 18:29:34.954  4670  4743 D BluetoothAdapterProperties: Scan Mode:20
,11-15 18:29:34.955  4670  4670 D BluetoothMapService: onReceive
11-15 18:29:34.955  4670  4670 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 18:29:34.955  4670  4670 D BluetoothMapService: STATE_TURNING_OFF
11-15 18:29:34.955  4670  4670 D BluetoothMapService: MAP Service closeService in
11-15 18:29:34.955  4670  4670 D BluetoothMapMasInstance0: MAP Service shutdown
11-15 18:29:34.956  4670  4670 D ObexServerSockets0: shutdown(block = true)
,11-15 18:29:34.956  4670  4739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-15 18:29:34.957  4670  4670 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 18:29:34.957  4670  4670 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 18:29:34.957  4670  4889 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-15 18:29:34.957  4670  4878 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-15 18:29:34.957  4670  4890 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-15 18:29:34.959  4670  4670 I BtOppRfcommListener: stopping Accept Thread
11-15 18:29:34.959  4670  5313 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-15 18:29:34.960  4670  5313 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-15 18:29:34.972   928   941 I ActivityManager: Start proc 5689:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-15 18:29:34.977  4670  4670 D HeadsetService: Received stop request...Stopping profile...
,11-15 18:29:34.980   928   928 D BluetoothHeadset: Proxy object disconnected
11-15 18:29:34.981  4670  4670 D A2dpService: Received stop request...Stopping profile...
11-15 18:29:34.981  3160  4017 D BluetoothHeadset: Proxy object disconnected
11-15 18:29:34.981  4670  4883 D A2dpStateMachine: Exit Disconnected: -1
11-15 18:29:34.982  3781  4015 D BluetoothHeadset: Proxy object disconnected
,11-15 18:29:34.983   928   928 D BluetoothHeadset: Proxy object disconnected
11-15 18:29:34.983   928   928 D BluetoothHeadset: Proxy object disconnected
11-15 18:29:34.983   928   928 D BluetoothA2dp: Proxy object disconnected
11-15 18:29:34.983  4670  4670 V BluetoothAdapterState: isTurningOff()=true
11-15 18:29:34.983  4670  4670 V BluetoothAdapterState: isTurningOn()=false
11-15 18:29:34.983  4670  4670 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:34.983  4670  4670 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:34.984  4670  4670 D HidService: Received stop request...Stopping profile...
11-15 18:29:34.984  4670  4670 D HidService: Stopping Bluetooth HidService
,11-15 18:29:34.990  4670  4670 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-15 18:29:34.990  4670  4670 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-15 18:29:34.991  4670  4670 D HealthService: Received stop request...Stopping profile...
11-15 18:29:34.991  4670  4743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-15 18:29:34.992  4670  4670 V BluetoothAdapterState: isTurningOff()=true
11-15 18:29:34.991  4670  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 18:29:34.992  4670  4670 V BluetoothAdapterState: isTurningOn()=false
11-15 18:29:34.992  4670  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 18:29:34.992  4670  4670 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:34.992  4670  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 18:29:34.993  4670  4670 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:34.993  4670  4743 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-15 18:29:34.993  4670  4670 D PanService: Received stop request...Stopping profile...
,11-15 18:29:34.995  4670  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-15 18:29:34.995  4670  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 18:29:34.996  4670  4864 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 18:29:34.996  4670  4670 D BluetoothMapService: Received stop request...Stopping profile...
11-15 18:29:34.996  4670  4864 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 18:29:34.996  4670  4670 D BluetoothMapService: stop()
11-15 18:29:34.996  4670  4864 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 18:29:34.996  4670  4864 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 18:29:34.996  4670  4743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-15 18:29:34.997  4670  4670 D BluetoothMapAppObserver: deinitObservers()
11-15 18:29:34.997  4670  4670 D BluetoothMapAppObserver: removeReceiver()
11-15 18:29:34.999  4670  4670 V BluetoothAdapterState: isTurningOff()=true
11-15 18:29:34.999  4670  4670 V BluetoothAdapterState: isTurningOn()=false
11-15 18:29:34.999  4670  4670 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:34.999  4670  4670 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:35.000  3160  3160 D HeadsetProfile: Bluetooth service disconnected
11-15 18:29:35.000  3160  3160 D BluetoothA2dp: Proxy object disconnected
11-15 18:29:35.000  3160  3160 D BluetoothInputDevice: Proxy object disconnected
11-15 18:29:35.000  3160  3160 D HidProfile: Bluetooth service disconnected
11-15 18:29:35.000  3160  3160 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-15 18:29:35.001  3160  3160 D PanProfile: Bluetooth service disconnected
11-15 18:29:35.001  3160  3160 D BluetoothMap: Proxy object disconnected
11-15 18:29:35.001  3160  3160 D MapProfile: Bluetooth service disconnected
,11-15 18:29:35.002  4670  4670 D SapService: Received stop request...Stopping profile...
11-15 18:29:35.002  4670  4670 V SapService: stop()
11-15 18:29:35.003  4670  4670 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-15 18:29:35.003  4670  4670 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-15 18:29:35.003  4670  4743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-15 18:29:35.003  4670  4670 V BluetoothAdapterState: isTurningOff()=true
,11-15 18:29:35.004  4670  4670 V BluetoothAdapterState: isTurningOn()=false
11-15 18:29:35.004  4670  4670 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:35.004  4670  4670 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:35.004  4670  4670 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-15 18:29:35.004  4670  4743 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-15 18:29:35.004  4670  4670 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-15 18:29:35.004  4670  4670 V BluetoothAdapterState: isTurningOff()=true
11-15 18:29:35.004  4670  4670 V BluetoothAdapterState: isTurningOn()=false
11-15 18:29:35.004  4670  4670 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:35.004  4670  4670 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:35.005  4670  4670 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-15 18:29:35.005  4670  4670 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-15 18:29:35.006  4670  4670 D BluetoothMapService: MAP Service closeService in
11-15 18:29:35.006  4670  4670 V BluetoothAdapterState: isTurningOff()=true
11-15 18:29:35.006  4670  4670 V BluetoothAdapterState: isTurningOn()=false
11-15 18:29:35.006  4670  4670 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:35.006  4670  4670 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:35.006  4670  4670 D BluetoothMapService: cleanup()
11-15 18:29:35.006  4670  4670 D BluetoothMapService: MAP Service closeService in
11-15 18:29:35.007  4670  4670 V BluetoothAdapterState: isTurningOff()=true
,11-15 18:29:35.007  4670  4670 V BluetoothAdapterState: isTurningOn()=false
11-15 18:29:35.007  4670  4670 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:35.007  4670  4670 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:35.007  4670  4739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-15 18:29:35.007  4670  4739 D BluetoothAdapterProperties: Setting state to 15
11-15 18:29:35.007  4670  4739 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-15 18:29:35.008   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 18:29:35.008  3160  3174 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 18:29:35.009  3160  3175 D BluetoothMap: onBluetoothStateChange: up=false
11-15 18:29:35.009  4670  4739 I BluetoothAdapterState: Entering BleOnState
,11-15 18:29:35.010  3160  5700 D BluetoothPan: onBluetoothStateChange on: false
,11-15 18:29:35.013   928  3597 I ActivityManager: Killing 5422:com.android.chrome/u0a39 (adj 15): empty #17
,11-15 18:29:35.029   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 18:29:35.029   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 18:29:35.030  3160  3174 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 18:29:35.030   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-15 18:29:35.031  3160  3175 D BluetoothPbap: onBluetoothStateChange: up=false
11-15 18:29:35.031  3160  4017 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-15 18:29:35.032  3781  3808 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 18:29:35.033  4670  4739 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-15 18:29:35.033  4670  4739 D BluetoothAdapterProperties: Setting state to 16
11-15 18:29:35.033  4670  4739 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-15 18:29:35.035  4670  4739 D BluetoothAdapterProperties: onBleDisable
11-15 18:29:35.035  4670  4739 I BluetoothAdapterState: Entering PendingCommandState
11-15 18:29:35.036  4670  4740 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-15 18:29:35.038  4670  4864 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-15 18:29:35.038  4670  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 18:29:35.038  4670  4743 D BluetoothAdapterProperties: Scan Mode:20
11-15 18:29:35.043  5689  5689 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-15 18:29:35.062  5689  5689 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 18:29:35.067   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f86a75b:true
,11-15 18:29:35.069  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 18:29:35.083   928  3819 I ActivityManager: Start proc 5702:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-15 18:29:35.090  5689  5689 D LocalBluetoothProfileManager: Adding local MAP profile
11-15 18:29:35.094  5689  5689 D BluetoothMap: Create BluetoothMap proxy object
,11-15 18:29:35.101  5689  5689 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-15 18:29:35.115  5689  5689 D DockEventReceiver: finishStartingService: stopping service
,11-15 18:29:35.121  5702  5702 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-15 18:29:35.124   928   939 I ActivityManager: Killing 4496:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-15 18:29:35.190   928  3813 D ConnectivityService: Returning blocked NetworkInfo to uid=10058
,11-15 18:29:35.245  4670  4743 I bt_hci  : shut_down
,11-15 18:29:35.249  4670  4747 D bt_hwcfg: hw_epilog_process
,11-15 18:29:35.249  4670  4747 I bt_vendor: low_power_mode_cb
,11-15 18:29:35.251  4670  4747 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-15 18:29:35.251  4670  4747 I bt_vendor: epilog_cb
11-15 18:29:35.251  4670  4747 I bt_hci  : epilog_finished_callback
,11-15 18:29:35.254  4670  4743 I bt_hci_h4: hal_close
,11-15 18:29:35.255  4670  4743 I bt_userial_vendor: device fd = 54 close
,11-15 18:29:35.321  5702  5702 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 18:29:35.321  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at java.io.File.exists(File.java:361)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 18:29:35.321  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-15 18:29:35.322  5702  5702 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 18:29:35.322  5702  5702 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 18:29:35.322  5702  5702 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.e.b(PG:170)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 18:29:35.322  5702  5702 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.k.d(PG:583)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.e.b(PG:170)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 18:29:35.322  5702  5702 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.File.exists(File.java:361)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 18:29:35.322  5702  5702 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.File.exists(File.java:361)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 18:29:35.322  5702  5702 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 18:29:35.322  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 18:29:35.351  5689  5689 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 18:29:35.357  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 18:29:35.361  4670  4740 D bt_stack_manager: event_shut_down_stack finished.
11-15 18:29:35.361  4670  4739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-15 18:29:35.363  4670  4670 D BtGatt.DebugUtils: handleDebugAction() action=null
11-15 18:29:35.363  4670  4739 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-15 18:29:35.363  4670  4670 D BtGatt.GattService: Received stop request...Stopping profile...
11-15 18:29:35.363  4670  4670 D BtGatt.GattService: stop()
11-15 18:29:35.363  4670  4670 D BtGatt.AdvertiseManager: advertise clients cleared
11-15 18:29:35.364  5689  5689 D DockEventReceiver: finishStartingService: stopping service
11-15 18:29:35.365  4670  4670 V BluetoothAdapterState: isTurningOff()=false
11-15 18:29:35.365  4670  4670 V BluetoothAdapterState: isTurningOn()=false
11-15 18:29:35.365  4670  4670 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:35.365  4670  4670 V BluetoothAdapterState: isBleTurningOff()=true
11-15 18:29:35.365  4670  4739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-15 18:29:35.365   928  3178 I ActivityManager: Killing 5131:com.google.android.deskclock/u0a66 (adj 15): empty #17
11-15 18:29:35.365  4670  4739 D BluetoothAdapterProperties: Setting state to 10
11-15 18:29:35.365  4670  4739 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-15 18:29:35.365  4670  4739 I BluetoothAdapterState: Entering OffState
11-15 18:29:35.366   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-15 18:29:35.400  4670  4670 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-15 18:29:35.400  4670  4670 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-15 18:29:35.400  4670  4670 I BluetoothServiceJni: cleanupNative: return from cleanup
11-15 18:29:35.401  4670  4740 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-15 18:29:35.408  4670  4670 I art     : System.exit called, status: 0
,11-15 18:29:35.408  4670  4670 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-15 18:29:35.411  5623  5623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 18:29:35.452  5623  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 18:29:35.452  5623  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 18:29:35.452  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 18:29:35.452  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 18:29:35.452  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 18:29:35.452  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 18:29:35.452  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 18:29:35.452  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 18:29:35.452  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 18:29:35.452  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 18:29:35.452  5623  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 18:29:35.452  5623  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 18:29:35.454   380   380 E lowmemorykiller: Error writing /proc/4670/oom_score_adj; errno=22
,11-15 18:29:35.454   928   945 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
11-15 18:29:35.455  5623  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 18:29:35.455   928   945 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1308)
11-15 18:29:35.455   928   945 W ActivityManager: Application dead when creating service ServiceRecord{d204672 u0 com.android.bluetooth/.btservice.AdapterService}
,11-15 18:29:35.461   928   945 I ActivityManager: Process com.android.bluetooth (pid 4670) has died
,11-15 18:29:35.462   928   945 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
11-15 18:29:35.462   928   945 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
,11-15 18:29:35.463   928   945 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
11-15 18:29:35.463   928   945 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-15 18:29:35.463   928   945 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
11-15 18:29:35.463   928   945 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
11-15 18:29:35.463   928   945 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
11-15 18:29:35.463   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
11-15 18:29:35.463   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
11-15 18:29:35.463   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
11-15 18:29:35.463   928   945 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
11-15 18:29:35.463   928   945 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
11-15 18:29:35.463   928   945 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
11-15 18:29:35.463   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1588)
11-15 18:29:35.463   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1544)
11-15 18:29:35.463   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
11-15 18:29:35.463   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1215)
11-15 18:29:35.463   928   945 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 18:29:35.463   928   945 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:29:35.463   928   945 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-15 18:29:35.463   928   945 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-15 18:29:35.463   928   938 W ActivityManager: Spurious death for ProcessRecord{56eb163 0:com.android.bluetooth/1002}, curProc for 4670: null
,11-15 18:29:35.550  5702  5725 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-15 18:29:35.559   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@89d8f40:true
,11-15 18:29:38.455   928   945 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,11-15 18:29:38.499   928   945 I ActivityManager: Start proc 5736:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-15 18:29:38.569  5736  5736 D AdapterServiceConfig: Adding HeadsetService
,11-15 18:29:38.569  5736  5736 D AdapterServiceConfig: Adding A2dpService
11-15 18:29:38.569  5736  5736 D AdapterServiceConfig: Adding HidService
11-15 18:29:38.569  5736  5736 D AdapterServiceConfig: Adding HealthService
11-15 18:29:38.570  5736  5736 D AdapterServiceConfig: Adding PanService
11-15 18:29:38.570  5736  5736 D AdapterServiceConfig: Adding GattService
,11-15 18:29:38.570  5736  5736 D AdapterServiceConfig: Adding BluetoothMapService
11-15 18:29:38.570  5736  5736 D AdapterServiceConfig: Adding SapService
,11-15 18:29:38.583   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c5a096:true
,11-15 18:29:38.584  5736  5736 D BluetoothAdapterState: make() - Creating AdapterState
,11-15 18:29:38.586  5736  5736 I bt_bluedroid: init
11-15 18:29:38.586  5736  5748 I BluetoothAdapterState: Entering OffState
,11-15 18:29:38.588  5736  5749 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-15 18:29:38.588  5736  5749 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-15 18:29:38.588  5736  5749 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-15 18:29:38.588  5736  5749 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-15 18:29:38.589  5736  5736 I bt_bluedroid: get_profile_interface socket
,11-15 18:29:38.590  5736  5736 I bt_bluedroid: get_profile_interface sdp
,11-15 18:29:38.590  5736  5752 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-15 18:29:38.593  5736  5752 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 18:29:38.594  5736  5747 I bt_bluedroid: config_hci_snoop_log
,11-15 18:29:38.595   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-15 18:29:38.599  5736  5748 D BluetoothAdapterState: Current state: OFF, message: 0
,11-15 18:29:38.599  5736  5748 D BluetoothAdapterProperties: Setting state to 14
11-15 18:29:38.599  5736  5748 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-15 18:29:38.600  5736  5748 D BluetoothBondStateMachine: make
,11-15 18:29:38.602  5736  5753 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-15 18:29:38.604  5736  5748 I BluetoothAdapterState: Entering PendingCommandState
,11-15 18:29:38.605  5736  5736 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-15 18:29:38.608  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e4fa40
,11-15 18:29:38.608  5736  5736 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-15 18:29:38.609  5736  5736 D BtGatt.GattService: Received start request. Starting profile...
11-15 18:29:38.609  5736  5736 D BtGatt.GattService: start()
11-15 18:29:38.609  5736  5736 I bt_bluedroid: get_profile_interface gatt
,11-15 18:29:38.611  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e4fa40
,11-15 18:29:38.611  5736  5736 D BtGatt.AdvertiseManager: advertise manager created
,11-15 18:29:38.615  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-15 18:29:38.615  5736  5736 V BluetoothAdapterState: isTurningOn()=false
,11-15 18:29:38.615  5736  5736 V BluetoothAdapterState: isBleTurningOn()=true
11-15 18:29:38.615  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 18:29:38.616  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-15 18:29:38.617  5736  5748 I bt_bluedroid: bt_bluedroid
,11-15 18:29:38.617  5736  5749 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-15 18:29:38.617  5736  5749 I bt_hci  : start_up
,11-15 18:29:38.622  5736  5749 I bt_vendor: alloc value 0xf3beb871
11-15 18:29:38.622  5736  5749 I bt_vendor: init
11-15 18:29:38.622  5736  5749 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-15 18:29:38.622  5736  5749 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-15 18:29:38.733  5736  5749 D bt_hci  : start_up starting async portion
,11-15 18:29:38.733  5736  5756 I bt_hci  : event_finish_startup
11-15 18:29:38.733  5736  5756 I bt_hci_h4: hal_open
11-15 18:29:38.734  5736  5756 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-15 18:29:38.730  5757  5757 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-15 18:29:38.736  5736  5756 I bt_userial_vendor: device fd = 54 open
,11-15 18:29:38.751  5736  5756 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 18:29:38.753  5736  5756 D bt_hwcfg: Chipset BCM4358A3
,11-15 18:29:38.754  5736  5756 D bt_hwcfg: Target name = [BCM4358A3]
11-15 18:29:38.754  5736  5756 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-15 18:29:38.978  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-15 18:29:39.149  5736  5756 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-15 18:29:39.150  5736  5756 D bt_hwcfg: Settlement delay -- 100 ms
,11-15 18:29:39.150  5736  5756 I bt_hwcfg: Setting fw settlement delay to 100 
,11-15 18:29:39.275  5736  5756 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 18:29:39.275  5736  5756 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-15 18:29:39.277  5736  5756 I bt_hwcfg: vendor lib fwcfg completed
,11-15 18:29:39.277  5736  5756 I bt_vendor: firmware callback
11-15 18:29:39.277  5736  5756 I bt_hci  : firmware_config_callback
,11-15 18:29:39.285  5736  5759 I bt_btu  : btu_task pending for preload complete event
,11-15 18:29:39.285  5736  5759 I bt_btu_task: Bluetooth chip preload is complete
11-15 18:29:39.285  5736  5759 I bt_btu  : btu_task received preload complete event
,11-15 18:29:39.295  5736  5759 I         : BTE_InitTraceLevels -- TRC_HCI
,11-15 18:29:39.295  5736  5759 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-15 18:29:39.295  5736  5759 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-15 18:29:39.295  5736  5759 I         : BTE_InitTraceLevels -- TRC_AVDT
11-15 18:29:39.295  5736  5759 I         : BTE_InitTraceLevels -- TRC_AVRC
11-15 18:29:39.296  5736  5759 I         : BTE_InitTraceLevels -- TRC_A2D
11-15 18:29:39.296  5736  5759 I         : BTE_InitTraceLevels -- TRC_BNEP
11-15 18:29:39.296  5736  5759 I         : BTE_InitTraceLevels -- TRC_BTM
11-15 18:29:39.296  5736  5759 I         : BTE_InitTraceLevels -- TRC_GAP
11-15 18:29:39.296  5736  5759 I         : BTE_InitTraceLevels -- TRC_PAN
,11-15 18:29:39.296  5736  5759 I         : BTE_InitTraceLevels -- TRC_SDP
11-15 18:29:39.296  5736  5759 I         : BTE_InitTraceLevels -- TRC_GATT
11-15 18:29:39.297  5736  5759 I         : BTE_InitTraceLevels -- TRC_SMP
11-15 18:29:39.297  5736  5759 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-15 18:29:39.297  5736  5759 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-15 18:29:39.385  5736  5759 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b69549
11-15 18:29:39.385  5736  5759 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b69549 
,11-15 18:29:39.409  5736  5752 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-15 18:29:39.411  5736  5752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-15 18:29:39.411  5736  5752 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-15 18:29:39.413  5736  5752 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 18:29:39.415  5736  5752 D BluetoothAdapterProperties: Scan Mode:20
11-15 18:29:39.415  5736  5752 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 18:29:39.415  5736  5752 D bt_hci  : do_postload posting postload work item
11-15 18:29:39.415  5736  5756 I bt_hci  : event_postload
11-15 18:29:39.415  5736  5756 I bt_vendor: sco_config_cb
11-15 18:29:39.415  5736  5756 I bt_hci  : sco_config_callback postload finished.
,11-15 18:29:39.417  5736  5752 D bt_bte_conf: Device ID record 1 : primary
11-15 18:29:39.418  5736  5752 D bt_bte_conf:   vendorId            = 000f
11-15 18:29:39.418  5736  5752 D bt_bte_conf:   vendorIdSource      = 0001
11-15 18:29:39.418  5736  5752 D bt_bte_conf:   product             = 1200
,11-15 18:29:39.418  5736  5752 D bt_bte_conf:   version             = 1436
11-15 18:29:39.418  5736  5752 D bt_bte_conf:   clientExecutableURL = 
11-15 18:29:39.418  5736  5752 D bt_bte_conf:   serviceDescription  = 
11-15 18:29:39.418  5736  5752 D bt_bte_conf:   documentationURL    = 
,11-15 18:29:39.418  5736  5752 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-15 18:29:39.418  5736  5749 D bt_stack_manager: event_start_up_stack finished
11-15 18:29:39.419  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-15 18:29:39.419  5736  5748 D BluetoothAdapterProperties: Setting state to 15
,11-15 18:29:39.420  5736  5748 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-15 18:29:39.420  5736  5748 I BluetoothAdapterState: Entering BleOnState
,11-15 18:29:39.423  5736  5756 I bt_vendor: low_power_mode_cb
11-15 18:29:39.424  5736  5748 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-15 18:29:39.424  5736  5748 D BluetoothAdapterProperties: Setting state to 11
11-15 18:29:39.424  5736  5748 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-15 18:29:39.430  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e4fa40
11-15 18:29:39.431  5736  5736 D HeadsetService: Received start request. Starting profile...
,11-15 18:29:39.434  5736  5736 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-15 18:29:39.434  5736  5736 D HeadsetStateMachine: make
,11-15 18:29:39.447  5736  5748 I BluetoothAdapterState: Entering PendingCommandState
,11-15 18:29:39.448  5736  5736 D HeadsetStateMachine: max_hf_connections = 1
,11-15 18:29:39.448  5736  5736 I bt_bluedroid: get_profile_interface handsfree
11-15 18:29:39.448  5736  5752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-15 18:29:39.449  5736  5752 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-15 18:29:39.452  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e4fa40
11-15 18:29:39.452  5736  5736 D A2dpService: Received start request. Starting profile...
,11-15 18:29:39.453  5736  5736 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-15 18:29:39.454  5736  5736 I bt_bluedroid: get_profile_interface avrcp
,11-15 18:29:39.463  5736  5736 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-15 18:29:39.463  5736  5736 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-15 18:29:39.463  5736  5736 D A2dpStateMachine: make
,11-15 18:29:39.464  5736  5736 I bt_bluedroid: get_profile_interface a2dp
,11-15 18:29:39.465  5736  5752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-15 18:29:39.466  5736  5767 D A2dpStateMachine: Enter Disconnected: -2
,11-15 18:29:39.467  5736  5736 I BluetoothHidServiceJni: classInitNative: succeeds
11-15 18:29:39.468  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e4fa40
,11-15 18:29:39.469  5689  5689 D BluetoothInputDevice: Proxy object connected
11-15 18:29:39.469  5736  5736 D HidService: Received start request. Starting profile...
11-15 18:29:39.470  5736  5736 I bt_bluedroid: get_profile_interface hidhost
11-15 18:29:39.470  5736  5736 D HidService: setHidService(): set to: null
11-15 18:29:39.470  5736  5752 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b4a56d
11-15 18:29:39.471  5736  5752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-15 18:29:39.471  5736  5736 I BluetoothHealthServiceJni: classInitNative: succeeds
11-15 18:29:39.472  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e4fa40
,11-15 18:29:39.473  5736  5736 D HealthService: Received start request. Starting profile...
,11-15 18:29:39.474  5689  5689 D HidProfile: Bluetooth service connected
,11-15 18:29:39.474  5736  5736 I bt_bluedroid: get_profile_interface health
11-15 18:29:39.475  5736  5736 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-15 18:29:39.476  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e4fa40
,11-15 18:29:39.477  5689  5689 D BluetoothPan: BluetoothPAN Proxy object connected
,11-15 18:29:39.478  5736  5736 D PanService: Received start request. Starting profile...
11-15 18:29:39.478  5689  5689 D PanProfile: Bluetooth service connected
11-15 18:29:39.478  5736  5736 D BluetoothPanServiceJni: initializeNative(L110): pan
11-15 18:29:39.478  5736  5736 I bt_bluedroid: get_profile_interface pan
11-15 18:29:39.479  5736  5752 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-15 18:29:39.481  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e4fa40
,11-15 18:29:39.482  5689  5689 D BluetoothMap: Proxy object connected
11-15 18:29:39.483  5736  5736 D BluetoothMapService: Received start request. Starting profile...
11-15 18:29:39.483  5736  5736 D BluetoothMapService: start()
11-15 18:29:39.483  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
11-15 18:29:39.484  5689  5689 D MapProfile: Bluetooth service connected
11-15 18:29:39.484  5689  5689 D BluetoothMap: getConnectedDevices()
11-15 18:29:39.484  5689  5689 D BluetoothMap: Bluetooth is Not enabled
,11-15 18:29:39.486  5736  5736 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-15 18:29:39.487  5736  5736 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-15 18:29:39.487  5736  5736 D BluetoothMapAppObserver: createReceiver()
11-15 18:29:39.489  5736  5736 D BluetoothMapAppObserver: initObservers()
11-15 18:29:39.489  5736  5736 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-15 18:29:39.497  5736  5736 V SapService: SapBinder()
11-15 18:29:39.497  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e4fa40
11-15 18:29:39.498  5736  5736 D SapService: Received start request. Starting profile...
11-15 18:29:39.498  5736  5736 V SapService: start()
11-15 18:29:39.498  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 18:29:39.500  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-15 18:29:39.500  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-15 18:29:39.500  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:39.500  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:39.500  5736  5763 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
11-15 18:29:39.500  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-15 18:29:39.500  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-15 18:29:39.500  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:39.500  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:39.501  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:39.503  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-15 18:29:39.503  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-15 18:29:39.503  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-15 18:29:39.503  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-15 18:29:39.503  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-15 18:29:39.503  5736  5748 D BluetoothAdapterProperties: ScanMode =  20
11-15 18:29:39.503  5736  5748 D BluetoothAdapterProperties: State =  11
11-15 18:29:39.504  5736  5748 D BluetoothAdapterProperties: Setting state to 12
11-15 18:29:39.504  5736  5748 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-15 18:29:39.504  5689  5699 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-15 18:29:39.505  5736  5748 I BluetoothAdapterState: Entering OnState
11-15 18:29:39.505   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 18:29:39.505  3160  5700 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 18:29:39.506  3160  4017 D BluetoothMap: onBluetoothStateChange: up=true
11-15 18:29:39.509  3160  3160 D BluetoothMap: Proxy object connected
11-15 18:29:39.509  3160  3160 D MapProfile: Bluetooth service connected
11-15 18:29:39.509  3160  3160 D BluetoothMap: getConnectedDevices()
11-15 18:29:39.509  3160  3174 D BluetoothPan: onBluetoothStateChange on: true
11-15 18:29:39.510  5736  5752 D BluetoothAdapterProperties: Scan Mode:21
11-15 18:29:39.511  5736  5752 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 18:29:39.511  3160  3160 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 18:29:39.511  3160  3160 D PanProfile: Bluetooth service connected
11-15 18:29:39.512   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 18:29:39.513   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 18:29:39.513  3160  4017 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 18:29:39.513   928   928 D BluetoothA2dp: Proxy object connected
11-15 18:29:39.514  5736  5736 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 18:29:39.514   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 18:29:39.514  3160  3160 D BluetoothA2dp: Proxy object connected
11-15 18:29:39.515  5736  5736 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-15 18:29:39.515  3160  5700 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 18:29:39.516  5736  5736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 18:29:39.517  5689  5701 D BluetoothPan: onBluetoothStateChange on: true
11-15 18:29:39.517  5689  5699 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 18:29:39.518  5736  5736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 18:29:39.519  3160  3174 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-15 18:29:39.519  5736  5736 D ObexServerSockets: Succeed to create listening sockets 
11-15 18:29:39.520  5736  5736 D ObexServerSockets0: startAccept()
11-15 18:29:39.520  5736  5736 D ObexServerSockets0: prepareForNewConnect()
11-15 18:29:39.520  3160  3160 D BluetoothInputDevice: Proxy object connected
11-15 18:29:39.520  5689  5701 D BluetoothMap: onBluetoothStateChange: up=true
11-15 18:29:39.520  3160  3160 D HidProfile: Bluetooth service connected
11-15 18:29:39.521  3781  3806 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 18:29:39.522   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-15 18:29:39.525  5736  5736 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-15 18:29:39.525  5736  5736 D BluetoothSdpJni: SDP Create record success - handle: 0
11-15 18:29:39.525  5736  5773 D ObexServerSockets0: Accepting socket connection...
11-15 18:29:39.525  5736  5736 D BluetoothMapService: onReceive
11-15 18:29:39.525  5736  5736 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 18:29:39.525  5736  5736 D BluetoothMapService: STATE_ON
11-15 18:29:39.526  5736  5775 D ObexServerSockets0: Accepting socket connection...
11-15 18:29:39.526  5689  5689 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-15 18:29:39.528  5736  5776 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 18:29:39.529  5736  5776 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-15 18:29:39.529  5736  5776 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-15 18:29:39.531  5689  5689 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-15 18:29:39.537  5689  5689 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 18:29:39.540  5689  5689 D BluetoothA2dp: Proxy object connected
,11-15 18:29:39.544  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 18:29:39.549  5689  5689 D DockEventReceiver: finishStartingService: stopping service
11-15 18:29:39.550  3160  3160 D BluetoothPbap: Proxy object connected
11-15 18:29:39.550  3160  3160 D PbapServerProfile: Bluetooth service connected
11-15 18:29:39.550  5736  5736 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 18:29:39.550  5689  5689 D BluetoothPbap: Proxy object connected
11-15 18:29:39.550  5736  5736 D ObexServerSockets0: prepareForNewConnect()
11-15 18:29:39.551  5689  5689 D PbapServerProfile: Bluetooth service connected
,11-15 18:29:39.557  5736  5780 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 18:29:39.569  5736  5784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 18:29:39.570  5736  5784 I BtOppRfcommListener: Accept thread started.
,11-15 18:29:39.606   928   928 D BluetoothHeadset: Proxy object connected
,11-15 18:29:39.607  3160  3175 D BluetoothHeadset: Proxy object connected
11-15 18:29:39.607  3160  3160 D HeadsetProfile: Bluetooth service connected
11-15 18:29:39.607  3781  4016 D BluetoothHeadset: Proxy object connected
11-15 18:29:39.607   928   928 D BluetoothHeadset: Proxy object connected
11-15 18:29:39.608   928   928 D BluetoothHeadset: Proxy object connected
,11-15 18:29:39.613   928   945 D BluetoothHeadset: Proxy object connected
11-15 18:29:39.615   928   945 D BluetoothHeadset: Proxy object connected
,11-15 18:29:39.621  3781  4015 D BluetoothHeadset: Proxy object connected
,11-15 18:29:39.634  5689  5701 D BluetoothHeadset: Proxy object connected
,11-15 18:29:39.636  5689  5689 D HeadsetProfile: Bluetooth service connected
,11-15 18:29:39.997  5623  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 18:29:39.997  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 18:29:39.997  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 18:29:39.997  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 18:29:39.997  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 18:29:39.997  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 18:29:39.997  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 18:29:39.997  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 18:29:39.997  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 18:29:40.002  5623  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 18:29:40.005  5623  5670 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-15 18:29:40.007   928  3893 D WifiService: setWifiEnabled: false pid=5623, uid=10077
11-15 18:29:40.007   928  3893 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-15 18:29:40.011  5623  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 18:29:40.011   928  2976 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-15 18:29:40.012   928  2976 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-15 18:29:40.012   928  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 18:29:40.012   928  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 18:29:40.029   928  5384 D DhcpClient: Clearing IP address
,11-15 18:29:40.030   508   921 D CommandListener: Clearing all IP addresses on wlan0
,11-15 18:29:40.037   508   921 D CommandListener: Setting iface cfg
,11-15 18:29:40.041  3602  5436 V NativeCrypto: Read error: ssl=0x7f9dbb0000: I/O error during system call, Connection timed out
,11-15 18:29:40.043  3602  5436 V NativeCrypto: SSL shutdown failed: ssl=0x7f9dbb0000: I/O error during system call, Broken pipe
,11-15 18:29:40.045   928  3597 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-15 18:29:40.046   928  5382 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-15 18:29:40.049   928  5382 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-15 18:29:40.050   928  2989 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,11-15 18:29:40.050   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 18:29:40.052   928  2989 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-15 18:29:40.052   928  2989 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-15 18:29:40.052   928  2989 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-15 18:29:40.055   928   928 D RttService: SCAN_AVAILABLE : 1
11-15 18:29:40.056   928  3090 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-15 18:29:40.057   535   535 E Parcel  : Reading a NULL string not supported here.
11-15 18:29:40.058   928  2989 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-15 18:29:40.060  3750  3908 W QCNEJ   : |CORE| network lost: 100
,11-15 18:29:40.061  3750  3908 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-15 18:29:40.066   928  2976 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-15 18:29:40.072   928  5385 D DhcpClient: Receive thread stopped
,11-15 18:29:40.074   928  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-15 18:29:40.082   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 18:29:40.101   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-15 18:29:40.101   508   921 D CommandListener: Clearing all IP addresses on wlan0
,11-15 18:29:40.101   508   921 D TetherController: Setting IP forward enable = 0
11-15 18:29:40.102   928  2989 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-15 18:29:40.103   928  2989 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-15 18:29:40.104   928  2976 D DhcpClient: doQuit
,11-15 18:29:40.104   928  2976 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-15 18:29:40.105  3470  3470 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-15 18:29:40.106   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-15 18:29:40.106   928  5384 D DhcpClient: onQuitting
11-15 18:29:40.109  5266  5266 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5f6a83d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-15 18:29:40.115  3993  3993 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-15 18:29:40.119  3882  3882 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-15 18:29:40.124  3470  3470 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-15 18:29:40.126  3882  3882 D SystemUpdateService: onCreate
11-15 18:29:40.129  3470  3470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-15 18:29:40.133  3882  3882 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-15 18:29:40.147  3882  3882 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-15 18:29:40.156   508   921 E Netd    : netlink response contains error (No such file or directory)
,11-15 18:29:40.157   928  2989 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-15 18:29:40.159  3882  5800 I SystemUpdateService: active receiver: enabled
,11-15 18:29:40.161  3882  5407 I iu.UploadsManager: num queued entries: 0
,11-15 18:29:40.161  3470  3470 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-15 18:29:40.161  3882  5407 I iu.UploadsManager: num updated entries: 0
11-15 18:29:40.162  3882  5407 I iu.SyncManager: NEXT; no task
,11-15 18:29:40.163  3882  3882 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-15 18:29:40.164  3882  3882 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-15 18:29:40.175   928  3173 I ActivityManager: Start proc 5803:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-15 18:29:40.179  3882  5800 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 18:29:40.180  3470  3470 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-15 18:29:40.190  3882  5800 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-15 18:29:40.191  3882  5800 I SystemUpdateService: now status is 0 (complete)
11-15 18:29:40.191  3882  5800 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-15 18:29:40.191  3882  5800 I SystemUpdateService: file has been verified
11-15 18:29:40.192  3882  5800 I SystemUpdateService: OTA package size = 21989297
,11-15 18:29:40.217  5803  5803 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-15 18:29:40.220  5803  5803 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 18:29:40.228  5803  5803 D SprintDMHelper: simOperator: 
,11-15 18:29:40.228  5803  5803 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 18:29:40.233  3882  5800 I SystemUpdateService: showing system update notification
,11-15 18:29:40.240   928  3178 I ActivityManager: Start proc 5815:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-15 18:29:40.251   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 18:29:40.253  3882  3882 D SystemUpdateService: onDestroy
11-15 18:29:40.255   928  3813 I ActivityManager: Killing 5455:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-15 18:29:40.284  5022  5022 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-15 18:29:40.285   928  2976 D wifi    : In wifi stop Hal
11-15 18:29:40.285   928  2976 D wifi    : halHandle = 0x7f8c0e19a0, mVM = 0x7fa86cd140, mCls = 0x100a02
11-15 18:29:40.285   928  3469 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-15 18:29:40.285   928  3469 D WifiHAL : Got a signal to exit!!!
11-15 18:29:40.285   928  3469 I WifiHAL : Exit wifi_event_loop
11-15 18:29:40.285   928  2976 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-15 18:29:40.285   928  2976 E WifiHAL : Event processing terminated
11-15 18:29:40.286   928  2976 D wifi    : In wifi cleaned up handler
11-15 18:29:40.286   928  2976 I WifiHAL : Internal cleanup completed
11-15 18:29:40.286  4062  4243 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 18:29:40.308   928  3469 D wifi    : set interface wlan0 flags (DOWN)
,11-15 18:29:40.308   928  2976 D WifiNative-HAL: HAL event thread stopped successfully
,11-15 18:29:40.346   928   939 I ActivityManager: Killing 5266:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-15 18:29:40.379   928   939 I ActivityManager: Start proc 5830:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-15 18:29:40.411  5830  5830 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-15 18:29:40.419   928  3597 I ActivityManager: Killing 3925:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-15 18:29:40.512   928   945 D Tethering: InitialState.processMessage what=4
,11-15 18:29:40.516   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-15 18:29:40.517  5623  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 18:29:40.517  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 18:29:40.517  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 18:29:40.517  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 18:29:40.517  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 18:29:40.517  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 18:29:40.517  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 18:29:40.517  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 18:29:40.517  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 18:29:40.520  5623  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 18:29:40.521   928   938 D WifiService: setWifiEnabled: true pid=5623, uid=10077
,11-15 18:29:40.521   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 18:29:40.523  5623  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 18:29:40.524   508   921 D SoftapController: Softap fwReload - Ok
,11-15 18:29:40.527   508   921 D CommandListener: Setting iface cfg
,11-15 18:29:40.527   508   921 D CommandListener: Trying to bring down wlan0
11-15 18:29:40.527   508   921 D CommandListener: Clearing all IP addresses on wlan0
,11-15 18:29:40.530   928  2976 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-15 18:29:41.025   928  3887 D WifiService: setWifiEnabled: true pid=5623, uid=10077
,11-15 18:29:41.029   928  3887 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 18:29:41.131   928  2976 D wifi    : set interface wlan0 flags (UP)
11-15 18:29:41.131   928  2976 I WifiHAL : Initializing wifi
11-15 18:29:41.131   928  2976 I WifiHAL : Creating socket
,11-15 18:29:41.144   928  2976 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-15 18:29:41.145   928  2976 D wifi    : Did set static halHandle = 0x7f8c0e19a0
,11-15 18:29:41.145   928  2976 D wifi    : halHandle = 0x7f8c0e19a0, mVM = 0x7fa86cd140, mCls = 0x18ae
,11-15 18:29:41.145   928  2976 D wifi    : array field set
,11-15 18:29:41.145   928  2976 I WifiNative-HAL: interface[0] = wlan0
11-15 18:29:41.146   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-15 18:29:41.149   928  5849 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547810580896
,11-15 18:29:41.149   928  5849 D wifi    : waitForHalEvents called, vm = 0x7fa86cd140, obj = 0x18ae, env = 0x7f8a366980
,11-15 18:29:41.178   508   921 D TetherController: Setting IP forward enable = 0
,11-15 18:29:41.221  5850  5850 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-15 18:29:41.249   928  2976 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-15 18:29:41.290  5850  5850 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 18:29:41.324  5850  5850 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 18:29:41.324  5850  5850 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-15 18:29:41.344   928  2976 D WifiConfigStore: Loading config and enabling all networks 
,11-15 18:29:41.365   928  2976 D WifiConfigStore: loaded 0 passpoint configs
,11-15 18:29:41.366   928  2976 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-15 18:29:41.366   928  2976 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-15 18:29:41.367   928  2976 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-15 18:29:41.367   928  2976 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-15 18:29:41.368   928  2976 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-15 18:29:41.368   928  2976 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-15 18:29:41.369   928  2976 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-15 18:29:41.369   928  2976 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-15 18:29:41.369   928  2976 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-15 18:29:41.369   928  2976 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-15 18:29:41.369   928  2976 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-15 18:29:41.369   928  2976 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-15 18:29:41.372   928  2976 D WifiNative-HAL: Setting external_sim to 1
,11-15 18:29:41.372   928  2976 D wifi    : setting dfs flag to true, 0x7f907fa5c0
11-15 18:29:41.372  5022  5022 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-15 18:29:41.373   928  2976 D WifiStateMachine: Setting OUI to DA-A1-19
11-15 18:29:41.373   928  2976 D wifi    : setting scan oui 0x7f907fa5c0
,11-15 18:29:41.373   928  2976 D WifiHAL : Sending mac address OUI
,11-15 18:29:41.376   928  2976 E native  : do suspend false
,11-15 18:29:41.382   928  2976 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-15 18:29:41.382   928   928 D RttService: SCAN_AVAILABLE : 3
11-15 18:29:41.382   928  3090 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-15 18:29:41.383   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-15 18:29:41.384   508   921 D CommandListener: Setting iface cfg
,11-15 18:29:41.388   928  2965 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '123 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 123 Failed to set address (No such device)'
,11-15 18:29:41.388   928  2965 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-15 18:29:41.395   928  2965 D WifiNative-HAL: p2pGetDeviceAddress
,11-15 18:29:41.400   928  2965 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-15 18:29:41.400   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=111060 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-15 18:29:41.538  5623  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 18:29:41.538  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 18:29:41.538  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 18:29:41.538  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 18:29:41.538  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 18:29:41.538  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 18:29:41.538  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 18:29:41.538  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 18:29:41.538  5623  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-15 18:29:41.540  5623  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 18:29:41.543  5623  5670 D BluetoothAdapter: enable(): BT is already enabled..!
,11-15 18:29:41.544   928  3597 D WifiService: setWifiEnabled: true pid=5623, uid=10077
11-15 18:29:41.545   928  3597 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 18:29:41.545  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 18:29:41.546  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 18:29:41.546  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 18:29:41.547  5623  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@727d467 removed from the list
11-15 18:29:41.547  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 18:29:41.547  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d570214 removed from the list
11-15 18:29:41.547  5623  5670 D io.jxcore.node.ConnectivityMonitor: stop
11-15 18:29:41.549  5623  5670 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-15 18:29:41.551  5623  5670 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-15 18:29:41.551  5623  5670 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-15 18:29:41.552  5623  5670 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-15 18:29:41.553  5623  5670 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-15 18:29:41.554  5623  5670 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-15 18:29:41.555  5623  5670 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-15 18:29:41.555  5623  5670 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-15 18:29:41.556  5623  5670 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-15 18:29:41.558  5623  5670 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-15 18:29:41.559  5623  5670 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e3f7a6c Bundle[{}]
11-15 18:29:41.559  5623  5670 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-15 18:29:41.559  5623  5670 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-15 18:29:41.559  5623  5670 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-15 18:29:41.560  5623  5670 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-15 18:29:41.560  5623  5670 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-15 18:29:41.561  5623  5670 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-15 18:29:41.561  5623  5670 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-15 18:29:41.562  5623  5670 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,11-15 18:29:41.562  5623  5670 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-15 18:29:41.562  5623  5670 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-15 18:29:41.563  5623  5670 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-15 18:29:41.564  5623  5670 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-15 18:29:41.566  5623  5670 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-15 18:29:41.567  5623  5670 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-15 18:29:41.567  5623  5670 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-15 18:29:41.568  5623  5670 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-15 18:29:41.568  5623  5670 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-15 18:29:41.570  5623  5670 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-15 18:29:41.571  5623  5670 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-15 18:29:41.572  5623  5670 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
11-15 18:29:41.573  5623  5670 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
11-15 18:29:41.574  5623  5670 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-15 18:29:41.574  5623  5670 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-15 18:29:41.574  5623  5670 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
,11-15 18:29:41.574  5623  5670 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-15 18:29:41.575  5623  5670 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-15 18:29:41.575  5623  5670 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-15 18:29:41.575  5623  5670 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-15 18:29:41.575  5623  5670 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-15 18:29:41.576  5623  5670 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-15 18:29:41.576  5623  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 18:29:41.576  5623  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c73f8b2 added. We now have 3 listener(s)
11-15 18:29:41.578  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 18:29:41.578  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 18:29:41.578  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 18:29:41.578  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 18:29:41.578  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed35003 added. We now have 3 listener(s)
11-15 18:29:41.578  5623  5670 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 18:29:41.579  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 18:29:41.584  5623  5670 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-15 18:29:41.584  5623  5670 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-15 18:29:41.584  5623  5670 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-15 18:29:41.584  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,11-15 18:29:41.585  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.585  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.585  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.585  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 18:29:41.585  5623  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 18:29:41.585  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-15 18:29:41.585  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 18:29:41.585  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-15 18:29:41.588  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-15 18:29:41.590  5623  5855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-15 18:29:41.590  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 18:29:41.590  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 18:29:41.590  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 18:29:41.590  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 18:29:41.590  5623  5623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 18:29:41.590  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 18:29:41.590  5623  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 18:29:41.590  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 18:29:41.591  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-15 18:29:41.590  5765  5765 W Binder_3: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[31325]" dev="sockfs" ino=31325 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 18:29:41.590  5765  5765 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[31325]" dev="sockfs" ino=31325 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 18:29:41.594  5623  5855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-15 18:29:41.594  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-15 18:29:41.594  5623  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 18:29:41.594  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-15 18:29:41.598  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:41.598  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 18:29:41.598  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 18:29:41.599  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 18:29:41.599  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-15 18:29:41.600  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:41.601  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.601  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 18:29:41.601  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 18:29:41.601  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 18:29:41.601  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-15 18:29:41.601  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:41.601  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:41.601  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.601  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 18:29:41.601  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 18:29:41.601  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.601  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.601  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.602  5623  5670 D BluetoothAdapter: STATE_ON
,11-15 18:29:41.605  5736  5774 D BtGatt.GattService: registerClient() - UUID=66c198f0-c981-412a-8434-aad5ac3fd77d
,11-15 18:29:41.606  5736  5752 D BtGatt.GattService: onClientRegistered() - UUID=66c198f0-c981-412a-8434-aad5ac3fd77d, clientIf=5
,11-15 18:29:41.607  5623  5634 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-15 18:29:41.609  5736  5754 D BtGatt.AdvertiseManager: message : 0
,11-15 18:29:41.611  5736  5754 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 18:29:41.621  5736  5752 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 18:29:41.629  5736  5752 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 18:29:41.629  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:41.629  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.629  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 18:29:41.630  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.630  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.630  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.630  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:41.630  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.630  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-15 18:29:41.631  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-15 18:29:41.631  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.632  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.632  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.632  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:41.633  5623  5623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-15 18:29:41.633  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-15 18:29:41.633  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:41.633  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 18:29:41.633  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 18:29:41.633  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:41.633  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:41.633  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:41.633  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 18:29:41.633  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 18:29:41.633  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-15 18:29:41.633  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 18:29:41.634  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 18:29:41.634  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 18:29:41.636  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 18:29:41.636  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 18:29:41.636  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:41.636  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:41.636  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:41.636  5623  5623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 18:29:42.137  5623  5623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-15 18:29:42.138  5623  5623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-15 18:29:42.138  5623  5623 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 18:29:44.458  5850  5850 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 18:29:44.462  5850  5850 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 18:29:44.467  5850  5850 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 18:29:44.471  5850  5850 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 18:29:44.510   928  2976 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-15 18:29:44.512   928  2976 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-15 18:29:44.512   928  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 18:29:44.524   928  2976 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-15 18:29:44.560   928  2976 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-15 18:29:44.565  5850  5850 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-15 18:29:44.975   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-15 18:29:44.975   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-15 18:29:45.026  5850  5850 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-15 18:29:45.084  5850  5850 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-15 18:29:45.086  5850  5850 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-15 18:29:45.098   928  2976 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-15 18:29:45.098   928  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 18:29:45.099   928  2989 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-15 18:29:45.121   928  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 18:29:45.135  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-15 18:29:45.135  5623  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-15 18:29:45.135  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 18:29:45.135  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-15 18:29:45.135  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 18:29:45.136  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 18:29:45.136  5623  5855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 18:29:45.136  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 18:29:45.136  5623  5855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 18:29:45.136  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 18:29:45.136  5623  5855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 18:29:45.136  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 18:29:45.136  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 18:29:45.136  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 18:29:45.136  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 18:29:45.136  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.137  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.137  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.137  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.137  5623  5623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 18:29:45.138  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:45.139   508   921 D CommandListener: Setting iface cfg
11-15 18:29:45.139  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 18:29:45.140  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:45.140  5623  5670 D BluetoothLeScanner: could not find callback wrapper
,11-15 18:29:45.140  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 18:29:45.141  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.141  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.141  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.141  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 18:29:45.141  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.143  5736  5754 D BtGatt.AdvertiseManager: message : 1
11-15 18:29:45.144  5736  5754 D BtGatt.AdvertiseManager: stop advertise for client 5
11-15 18:29:45.145   928  2976 D WifiStateMachine: Start Dhcp Watchdog 2
,11-15 18:29:45.152   928  5862 D DhcpClient: Receive thread started
,11-15 18:29:45.155  5736  5752 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-15 18:29:45.155  5736  5752 D BtGatt.GattService: Client app is not null!
11-15 18:29:45.156  5736  5746 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 18:29:45.158  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 18:29:45.158  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.158  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-15 18:29:45.158  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.158  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:45.158  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.158  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 18:29:45.159  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 18:29:45.160   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-15 18:29:45.160   928  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-15 18:29:45.160   928  2989 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
11-15 18:29:45.160  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 18:29:45.161  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:45.163  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.163  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 18:29:45.163  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.163  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.163  5623  5623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 18:29:45.164  5623  5623 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-15 18:29:45.164  5623  5623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 18:29:45.164  5623  5623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 18:29:45.164  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 18:29:45.164  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 18:29:45.164  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:45.164  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.164  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 18:29:45.164  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 18:29:45.164  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.164  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.164  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-15 18:29:45.165  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.166  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.167  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-15 18:29:45.168  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.168  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.168  5623  5623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 18:29:45.170  5623  5670 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-15 18:29:45.170  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-15 18:29:45.171  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-15 18:29:45.171  5623  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-15 18:29:45.171  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-15 18:29:45.171  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 18:29:45.171  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-15 18:29:45.173  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 18:29:45.177  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 18:29:45.177  5623  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-15 18:29:45.177  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 18:29:45.181  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.182  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 18:29:45.182  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 18:29:45.182  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 18:29:45.182  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-15 18:29:45.186  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-15 18:29:45.190  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-15 18:29:45.190  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.190  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 18:29:45.190  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-15 18:29:45.190  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 18:29:45.191  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 18:29:45.191  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.192  5623  5670 D BluetoothAdapter: STATE_ON
,11-15 18:29:45.197  5736  5747 D BtGatt.GattService: registerClient() - UUID=ea0de53b-3d26-4c49-aea2-757397b4d890
11-15 18:29:45.197  5736  5752 D BtGatt.GattService: onClientRegistered() - UUID=ea0de53b-3d26-4c49-aea2-757397b4d890, clientIf=5
11-15 18:29:45.198  5623  5633 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-15 18:29:45.199  5736  5774 D BtGatt.GattService: start scan with filters
11-15 18:29:45.202  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-15 18:29:45.202  5736  5755 D BtGatt.ScanManager: handling starting scan
11-15 18:29:45.203  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:45.203  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 18:29:45.203  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.204  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 18:29:45.204  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:45.204  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.204  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 18:29:45.204  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 18:29:45.204  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.204  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.204  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-15 18:29:45.205  5736  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e4fa40
11-15 18:29:45.205  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 18:29:45.206  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.208  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.209  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 18:29:45.209  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.209  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:45.209  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.212  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-15 18:29:45.212  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.212  5736  5752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-15 18:29:45.212  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.212  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 18:29:45.212  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:45.212  5623  5623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-15 18:29:45.213  5736  5755 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-15 18:29:45.219  5736  5752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-15 18:29:45.220  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 18:29:45.220  5736  5755 D BtGatt.ScanManager: Starting BLE batch scan
11-15 18:29:45.220  5736  5755 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-15 18:29:45.231  5736  5752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-15 18:29:45.231  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 18:29:45.238  5736  5752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-15 18:29:45.238  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 18:29:45.243   928  2976 E native  : do suspend false
,11-15 18:29:45.250   928  5861 D DhcpClient: Broadcasting DHCPDISCOVER
,11-15 18:29:45.315   928  5862 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172726, domain null
,11-15 18:29:45.315   928  5861 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172726 seconds
11-15 18:29:45.316   928  5861 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-15 18:29:45.328   928  5862 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-15 18:29:45.328   928  5861 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-15 18:29:45.329   508   921 D CommandListener: Setting iface cfg
,11-15 18:29:45.331   928  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-15 18:29:45.334   928  5861 D DhcpClient: Scheduling renewal in 86399s
,11-15 18:29:45.339   928  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-15 18:29:45.339   928  2976 D WifiConfigStore: No blacklist allowed without epno enabled
,11-15 18:29:45.340   928  2989 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-15 18:29:45.341   928  2989 D ConnectivityService: Adding iface wlan0 to network 101
,11-15 18:29:45.343   928  2976 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-15 18:29:45.368   928  2989 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-15 18:29:45.369   928  2989 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-15 18:29:45.370   928  2989 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-15 18:29:45.372   928  2989 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-15 18:29:45.373   928  2989 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-15 18:29:45.379   928  2989 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 18:29:45.383   928  2989 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-15 18:29:45.383   928  2989 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-15 18:29:45.383   928  2989 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-15 18:29:45.383   928  2976 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-15 18:29:45.383   928  2989 D ConnectivityService:    accepting network in place of null
11-15 18:29:45.383   928  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 18:29:45.384   928  2989 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -56]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-15 18:29:45.397   928  5860 D NetlinkSocketObserver: NeighborEvent{elapsedMs=115057, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-15 18:29:45.404   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 18:29:45.426   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 18:29:45.429   928  2989 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-15 18:29:45.429   928  2989 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-15 18:29:45.429  3750  3908 W QCNEJ   : |CORE| network available: 101
11-15 18:29:45.430   928  2989 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-15 18:29:45.430   928   945 D Tethering: MasterInitialState.processMessage what=3
11-15 18:29:45.431  3750  3908 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-15 18:29:45.432  3750  3908 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-15 18:29:45.433  3750  3908 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-15 18:29:45.442  3993  3993 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-15 18:29:45.445  3882  3882 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-15 18:29:45.448  3882  3882 D SystemUpdateService: onCreate
,11-15 18:29:45.451  3882  3882 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-15 18:29:45.463  3882  3882 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-15 18:29:45.467   928  5859 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.211.46,2a00:1450:4016:805::200e
,11-15 18:29:45.470  3882  5407 I iu.UploadsManager: num queued entries: 0
,11-15 18:29:45.471  3882  5407 I iu.UploadsManager: num updated entries: 0
11-15 18:29:45.471  3882  5407 I iu.SyncManager: NEXT; no task
11-15 18:29:45.471  3882  5872 I SystemUpdateService: active receiver: enabled
,11-15 18:29:45.475  3882  3882 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-15 18:29:45.476  3882  3882 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-15 18:29:45.478  5803  5803 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 18:29:45.482  5803  5803 D SprintDMHelper: simOperator: 
,11-15 18:29:45.482  5803  5803 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 18:29:45.493  3882  5872 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 18:29:45.508  3882  5872 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-15 18:29:45.508  3882  5872 I SystemUpdateService: now status is 0 (complete)
11-15 18:29:45.508  3882  5872 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-15 18:29:45.508  3882  5872 I SystemUpdateService: file has been verified
11-15 18:29:45.508  3882  5872 I SystemUpdateService: OTA package size = 21989297
,11-15 18:29:45.515  3882  5872 I SystemUpdateService: showing system update notification
,11-15 18:29:45.522   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 18:29:45.523  3882  3882 D SystemUpdateService: onDestroy
,11-15 18:29:45.543   928  5859 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 15 Nov 2016 17:29:45 GMT], X-Android-Received-Millis=[1479230985543], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479230985502]}
,11-15 18:29:45.544   928  2989 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-15 18:29:45.544   928  2989 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-15 18:29:45.544   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-15 18:29:45.545   928  2989 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-15 18:29:45.713  5623  5623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-15 18:29:45.713  5623  5623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 18:29:45.713  5623  5623 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 18:29:45.741  5736  5736 D BtGatt.ScanManager: awakened up at time 115401
11-15 18:29:45.742  5736  5755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 18:29:45.763  5736  5752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,11-15 18:29:45.763  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 18:29:45.764  5736  5752 D BtGatt.GattService: current time is 115424447271
11-15 18:29:45.764  5736  5752 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 18:29:45.766  5736  5752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 18:29:45.772  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 1. Current thread: Thread[main,5,main], id: 1
,11-15 18:29:45.773  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=115275104823}
,11-15 18:29:45.773  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=115275104823}
,11-15 18:29:45.775  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 61:7E:A4:16:C8:B6, provideBluetoothMacAddressRequestId = nullextra info = 35]
,11-15 18:29:45.776  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,11-15 18:29:46.269  5736  5736 D BtGatt.ScanManager: awakened up at time 115930
,11-15 18:29:46.273  5736  5755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 18:29:46.293  5736  5752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,11-15 18:29:46.293  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 18:29:46.293  5736  5752 D BtGatt.GattService: current time is 115954171461
,11-15 18:29:46.293  5736  5752 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,11-15 18:29:46.294  5736  5752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-15 18:29:46.294  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 1. Current thread: Thread[main,5,main], id: 1
,11-15 18:29:46.295  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-81, mTimestampNanos=115904368912}
11-15 18:29:46.295  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-81, mTimestampNanos=115904368912}
,11-15 18:29:46.430   928  2989 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-15 18:29:48.179   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 18:29:48.211  5623  5670 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-15 18:29:48.211  5623  5670 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-15 18:29:48.211  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-15 18:29:48.212  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:48.212  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:48.212  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-15 18:29:48.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-15 18:29:48.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-15 18:29:48.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-15 18:29:48.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-15 18:29:48.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-15 18:29:48.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-15 18:29:48.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-15 18:29:48.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-15 18:29:48.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:48.213  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-15 18:29:48.213  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.213  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:48.213  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 18:29:48.214  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 18:29:48.214  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.214  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.214  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.216  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:48.217  5736  5746 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-15 18:29:48.218  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 18:29:48.219  5736  5755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 18:29:48.220  5623  5670 D BluetoothAdapter: STATE_ON
,11-15 18:29:48.222  5736  5747 D BtGatt.GattService: stopScan() - queue size =1
11-15 18:29:48.225  5736  5774 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 18:29:48.226  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 18:29:48.227  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.227  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-15 18:29:48.227  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.227  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 18:29:48.228  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.228  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:48.228  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 18:29:48.228  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 18:29:48.228  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 18:29:48.229  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 18:29:48.229  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.231  5736  5736 D BtGatt.ScanManager: awakened up at time 117891
11-15 18:29:48.231  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:48.236  5736  5774 D BtGatt.GattService: registerClient() - UUID=2ac4a3c6-0d7e-4ca7-9b0e-09e59e41c179
11-15 18:29:48.237  5736  5752 D BtGatt.GattService: onClientRegistered() - UUID=2ac4a3c6-0d7e-4ca7-9b0e-09e59e41c179, clientIf=5
11-15 18:29:48.238  5623  5634 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-15 18:29:48.239  5736  5746 D BtGatt.GattService: start scan with filters
,11-15 18:29:48.245  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-15 18:29:48.245  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.245  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 18:29:48.245  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.246  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.246  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-15 18:29:48.246  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-15 18:29:48.246  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.246  5623  5670 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 18:29:48.246  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 18:29:48.246  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 18:29:48.246  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 18:29:48.246  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 18:29:48.246  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.246  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.247  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 18:29:48.248  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 18:29:48.248  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 18:29:48.248  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 18:29:48.248  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 18:29:48.248  5736  5752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-15 18:29:48.248  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-15 18:29:48.248  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 18:29:48.249  5623  5880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 18:29:48.249  5736  5752 D BtGatt.GattService: current time is 117909552440
11-15 18:29:48.249  5736  5752 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -81, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 18:29:48.249  5623  5623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 18:29:48.250  5736  5752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 18:29:48.250  5736  5752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 18:29:48.250  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 18:29:48.250  5623  5670 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 18:29:48.251  5623  5880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 18:29:48.254  5774  5774 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34849]" dev="sockfs" ino=34849 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 18:29:48.258  5623  5880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-15 18:29:48.254  5774  5774 W Binder_5: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34849]" dev="sockfs" ino=34849 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 18:29:48.262  5736  5752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-15 18:29:48.262  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.262  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 18:29:48.263  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.263  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.263  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 18:29:48.263  5736  5755 D BtGatt.ScanManager: stopping BLe Batch
11-15 18:29:48.263  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,11-15 18:29:48.263  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 18:29:48.263  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-15 18:29:48.263  5623  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:48.263  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:48.264  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.264  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-15 18:29:48.264  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 18:29:48.264  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.264  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.264  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.265  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:48.269  5736  5774 D BtGatt.GattService: registerClient() - UUID=da1b3f78-6226-493f-9ff5-266d88c61ed6
,11-15 18:29:48.272  5736  5752 D BtGatt.GattService: onClientRegistered() - UUID=da1b3f78-6226-493f-9ff5-266d88c61ed6, clientIf=6
11-15 18:29:48.273  5623  5634 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-15 18:29:48.274  5736  5752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-15 18:29:48.274  5736  5754 D BtGatt.AdvertiseManager: message : 0
,11-15 18:29:48.274  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 18:29:48.275  5736  5755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 18:29:48.277  5736  5754 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 18:29:48.281  5736  5752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-15 18:29:48.281  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 18:29:48.284  5736  5755 D BtGatt.ScanManager: handling starting scan
,11-15 18:29:48.291  5736  5752 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-15 18:29:48.295  5736  5752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-15 18:29:48.295  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 18:29:48.296  5736  5755 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-15 18:29:48.300  5736  5752 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-15 18:29:48.301  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.301  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.301  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-15 18:29:48.301  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.301  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.301  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.301  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.301  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:48.301  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.302  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.302  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.302  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-15 18:29:48.302  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-15 18:29:48.302  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-15 18:29:48.303  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 18:29:48.303  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:48.305  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.305  5736  5752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-15 18:29:48.305  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 18:29:48.305  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.305  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:48.305  5736  5755 D BtGatt.ScanManager: Starting BLE batch scan
11-15 18:29:48.305  5736  5755 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-15 18:29:48.306  5623  5623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-15 18:29:48.306  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
,11-15 18:29:48.306  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=116209936134}
,11-15 18:29:48.307  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=116209936134}
11-15 18:29:48.307  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
11-15 18:29:48.307  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-15 18:29:48.307  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=116409936134}
11-15 18:29:48.307  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=116409936134}
11-15 18:29:48.307  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
11-15 18:29:48.307  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-15 18:29:48.307  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.307  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:48.308  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-15 18:29:48.308  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.308  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.308  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:48.308  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.308  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-15 18:29:48.308  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 18:29:48.308  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.308  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.308  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-15 18:29:48.308  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.310  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-15 18:29:48.310  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-15 18:29:48.310  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.310  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.311  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:48.311  5623  5623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-15 18:29:48.315  5736  5752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-15 18:29:48.315  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 18:29:48.321  5736  5752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-15 18:29:48.321  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 18:29:48.812  5623  5623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
11-15 18:29:48.812  5623  5623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-15 18:29:48.812  5623  5623 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 18:29:49.977   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:29:50.978   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:29:51.309  5623  5670 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-15 18:29:51.310  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 18:29:51.310  5623  5670 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-15 18:29:51.310  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-15 18:29:51.311  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 18:29:51.311  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-15 18:29:51.311  5623  5880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 18:29:51.311  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-15 18:29:51.311  5623  5880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 18:29:51.311  5623  5670 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-15 18:29:51.311  5623  5880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 18:29:51.312  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 18:29:51.312  5623  5623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 18:29:51.312  5623  5670 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c73f8b2 removed from the list
,11-15 18:29:51.312  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 18:29:51.312  5623  5623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 18:29:51.312  5623  5670 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 18:29:51.312  5623  5623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 18:29:51.312  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 18:29:51.313  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-15 18:29:51.313  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.313  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.313  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.314  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-15 18:29:51.314  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.316  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:51.316  5736  5772 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-15 18:29:51.317  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 18:29:51.318  5736  5755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 18:29:51.318  5623  5670 D BluetoothAdapter: STATE_ON
11-15 18:29:51.320  5736  5747 D BtGatt.GattService: stopScan() - queue size =1
11-15 18:29:51.322  5736  5746 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 18:29:51.323  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 18:29:51.324  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:51.324  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-15 18:29:51.324  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.324  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.324  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.325  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-15 18:29:51.325  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:51.325  5736  5736 D BtGatt.ScanManager: awakened up at time 120986
,11-15 18:29:51.327  5736  5754 D BtGatt.AdvertiseManager: message : 1
,11-15 18:29:51.328  5736  5754 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-15 18:29:51.341  5736  5752 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-15 18:29:51.342  5736  5752 D BtGatt.GattService: Client app is not null!
,11-15 18:29:51.342  5736  5747 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-15 18:29:51.343  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 18:29:51.343  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.343  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 18:29:51.343  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:51.343  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.343  5623  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.344  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 18:29:51.344  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 18:29:51.344  5623  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 18:29:51.345  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-15 18:29:51.347  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.347  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 18:29:51.347  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.348  5623  5670 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-15 18:29:51.348  5623  5670 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed35003 removed from the list
11-15 18:29:51.348  5623  5670 D io.jxcore.node.ConnectivityMonitor: stop
11-15 18:29:51.348  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 18:29:51.348  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 18:29:51.348  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:51.348  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:51.348  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 18:29:51.348  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-15 18:29:51.348  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:51.348  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 18:29:51.349  5623  5623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-15 18:29:51.349  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 18:29:51.349  5623  5670 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-15 18:29:51.349  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-15 18:29:51.349  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-15 18:29:51.349  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-15 18:29:51.350  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 18:29:51.350  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-15 18:29:51.350  5623  5670 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-,15 18:29:51.350  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 18:29:51.350  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:51.350  5623  5623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 18:29:51.350  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:51.350  5623  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 18:29:51.350  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 18:29:51.350  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 18:29:51.350  5623  5670 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-15 18:29:51.350  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 18:29:51.351  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 18:29:51.351  5623  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 18:29:51.351  5623  5623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 18:29:51.351  5623  5670 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-15 18:29:51.352  5623  5670 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-15 18:29:51.353  5623  5670 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-15 18:29:51.354  5623  5670 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-15 18:29:51.354  5623  5670 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-15 18:29:51.355  5623  5670 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-15 18:29:51.356  5623  5670 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-15 18:29:51.364  5736  5752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-15 18:29:51.364  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 18:29:51.364  5736  5752 D BtGatt.GattService: current time is 121025389573
11-15 18:29:51.365  5736  5752 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -92, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -84, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -86, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -86, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 18:29:51.365  5736  5752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 18:29:51.365  5736  5752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 18:29:51.365  5736  5752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-15 18:29:51.366  5736  5752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 18:29:51.366  5736  5752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 18:29:51.366  5736  5752 E BtGatt.ContextMap: Context not found for ID 5
,11-15 18:29:51.371  5736  5752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-15 18:29:51.371  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 18:29:51.372  5736  5755 D BtGatt.ScanManager: stopping BLe Batch
,11-15 18:29:51.376  5736  5752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-15 18:29:51.376  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 18:29:51.376  5736  5755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 18:29:51.382  5736  5752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-15 18:29:51.382  5736  5752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 18:29:51.742   928  2976 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-15 18:29:51.852  5623  5623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 18:29:51.978   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:29:52.979   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:29:53.360  5623  5670 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-15 18:29:53.388   928  2989 D ConnectivityService: handlePromptUnvalidated 101
,11-15 18:29:53.511  5623  5882 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-15 18:29:53.511  5623  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 18:29:53.980   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:29:54.301  5623  5882 W !!      : call onHalfStreamCopied
,11-15 18:29:54.301  5623  5882 I testCopyDataAndClose: closing input stream
,11-15 18:29:54.981   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-15 18:29:55.080  5623  5882 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-15 18:29:55.080  5623  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 18:29:55.080  5623  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-15 18:29:55.080  5623  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 18:29:55.080  5623  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-15 18:29:55.080  5623  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-15 18:29:55.080  5623  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-15 18:29:55.080  5623  5882 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-15 18:29:55.080  5623  5882 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-15 18:29:55.080  5623  5882 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-15 18:29:55.080  5623  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-15 18:29:56.403   928  2976 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-15 18:29:59.226  5623  5670 I StreamCopyingThreadTest: Starting test: testRun
,11-15 18:29:59.230  5623  5883 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
11-15 18:29:59.230  5623  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 18:29:59.982   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:30:00.253   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 18:30:00.983   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:30:01.035   928   941 I ActivityManager: Start proc 5885:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,11-15 18:30:01.101  5885  5885 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,11-15 18:30:01.134  5885  5885 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
11-15 18:30:01.134  5885  5885 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
11-15 18:30:01.134  5885  5885 I GAv4    :   adb logcat -s GAv4
,11-15 18:30:01.149  5885  5885 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,11-15 18:30:01.155  5885  5885 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,11-15 18:30:01.174  5885  5900 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,11-15 18:30:01.181   928   939 I ActivityManager: Killing 5498:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-15 18:30:01.985   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:30:02.986   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:30:03.289   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 18:30:03.988   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:30:04.237  5623  5884 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-15 18:30:04.240  5623  5670 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-15 18:30:04.353  5623  5902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-15 18:30:04.353  5623  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 18:30:04.989   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-15 18:30:05.620  3679  3870 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-15 18:30:05.621  3679  3870 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-15 18:30:05.654  3602  3602 I ConfigService: onCreate
,11-15 18:30:06.038  5623  5902 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-15 18:30:06.038  5623  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 18:30:06.038  5623  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-15 18:30:06.038  5623  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 18:30:06.038  5623  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-15 18:30:06.038  5623  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-15 18:30:06.038  5623  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-15 18:30:06.038  5623  5902 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-15 18:30:06.038  5623  5902 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-15 18:30:06.038  5623  5902 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-15 18:30:06.038  5623  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-15 18:30:06.311   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 18:30:09.344   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 18:30:10.182  5623  5670 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-15 18:30:10.185  5623  5904 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-15 18:30:10.185  5623  5904 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 18:30:10.185  5623  5904 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
11-15 18:30:10.185  5623  5904 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 18:30:10.185  5623  5904 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-15 18:30:10.185  5623  5904 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 18:30:10.185  5623  5904 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-15 18:30:10.185  5623  5904 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-15 18:30:10.186  5623  5904 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-15 18:30:10.186  5623  5904 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-15 18:30:10.186  5623  5904 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-15 18:30:10.186  5623  5904 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-15 18:30:10.186  5623  5904 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-15 18:30:10.188  5623  5670 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-15 18:30:10.188  5623  5670 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-15 18:30:10.189  5623  5670 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-15 18:30:10.191  5623  5905 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-15 18:30:10.191  5623  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 18:30:10.192  5623  5905 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
11-15 18:30:10.192  5623  5905 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-15 18:30:10.192  5623  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-15 18:30:10.192  5623  5905 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-15 18:30:10.193  5623  5905 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-15 18:30:10.193  5623  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-15 18:30:10.194  5623  5670 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-15 18:30:10.194  5623  5670 E com.test.thalitest.ThaliTestRunner: 
11-15 18:30:10.194  5623  5670 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-15 18:30:10.194  5623  5670 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 18:30:10.195  5623,  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:30:10.195  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.ru,nners.ParentRunner.access$000(ParentRunner.java:58)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
,11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 18:30:10.196  5623  5670 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.juni,t.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:30:10.197  5623  5670 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-15 18:30:10.200  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG UnitTest_app: 'Running unit tests'
11-15 18:30:10.200  5623  5670 I jxcore-log: 
11-15 18:30:10.200  5623  5670 I jxcore-log: *Native tests were executed*
11-15 18:30:10.200  5623  5670 I jxcore-log: 
11-15 18:30:10.200  5623  5670 I jxcore-log: Total number of executed tests:  82
11-15 18:30:10.200  5623  5670 I jxcore-log: 
11-15 18:30:10.200  5623  5670 I jxcore-log: Number of passed tests:  79
11-15 18:30:10.200  5623  5670 I jxcore-log: 
11-15 18:30:10.200  5623  5670 I jxcore-log: Number of failed tests:  3
11-15 18:30:10.200  5623  5670 I jxcore-log: 
11-15 18:30:10.200  5623  5670 I jxcore-log: Number of ignored tests:  0
11-15 18:30:10.200  5623  5670 I jxcore-log: 
11-15 18:,30:10.201  5623  5670 I jxcore-log: Total duration:  42188
11-15 18:30:10.201  5623  5670 I jxcore-log: 
11-15 18:30:10.201  5623  5670 I jxcore-log: Failed to execute UT.
11-15 18:30:10.201  5623  5670 I jxcore-log: 
11-15 18:30:10.202  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-15 18:30:10.202  5623  5670 I jxcore-log: 
11-15 18:30:10.203  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-15 18:30:10.203  5623  5670 I jxcore-log: 
11-15 18:30:10.206  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 18:30:10.206  5623  5670 I jxcore-log: 
11-15 18:30:10.206  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 18:30:10.206  5623  5670 I jxcore-log: 
11-15 18:30:10.207  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 18:30:10.207  5623  5670 I jxcore-log: 
11-15 18:30:10.208  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 18:30:10.208  5623  5670 I jxcore-log: 
11-15 18:30:10.208  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 18:30:10.208  5623  5670 I jxcore-log: 
11-15 18:30:10.209  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 18:30:10.209  5623  5670 I jxcore-log: 
11-15 18:30:10.209  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 18:30:10.209  5623  5670 I jxcore-log: 
11-15 18:30:10.209  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 18:30:10.209  5623  5670 I jxcore-log: 
11-15 18:30:10.210  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 18:30:10.210  5623  5670 I jxcore-log: 
11-15 18:30:10.210  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 18:30:10.210  5623  5670 I jxcore-log: 
11-15 18:30:10.210  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 18:30:10.210  5623  5670 I jxcore-log: 
11-15 18:30:10.210  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 18:30:10.210  5623  5670 I jxcore-log: 
11-15 18:30:10.210  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 18:30:10.210  5623  5670 I jxcore-log: 
11-15 18:30:10.211  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-15 18:30:10.211  5623  5670 I jxcore-log: 
11-15 18:30:10.211  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 18:30:10.211  5623  5670 I jxcore-log: 
11-15 18:30:10.211  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 18:30:10.211  5623  5670 I jxcore-log: 
11-15 18:30:10.211  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 18:30:10.211  5623  5670 I jxcore-log: 
11-15 18:30:10.212  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-15 18:30:10.212  5623  5670 I jxcore-log: 
11-15 18:30:10.212  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 18:30:10.212  5623  5670 I jxcore-log: 
11-15 18:30:10.212  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 18:30:10.212  5623  5670 I jxcore-log: 
11-15 18:30:10.212  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 18:30:10.212  5623  5670 I jxcore-log: 
11-15 18:30:10.212  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 18:30:10.212  5623  5670 I jxcore-log: 
11-15 18:30:10.213  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 18:30:10.213  5623  5670 I jxcore-log: 
11-15 18:30:10.213  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-15 18:30:10.213  5623  5670 I jxcore-log: 
11-15 18:30:10.213  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 18:30:10.213  5623  5670 I jxcore-log: 
,11-15 18:30:10.213  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 18:30:10.213  5623  5670 I jxcore-log: 
11-15 18:30:10.214  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 18:30:10.214  5623  5670 I jxcore-log: 
11-15 18:30:10.214  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 18:30:10.214  5623  5670 I jxcore-log: 
11-15 18:30:10.215  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 18:30:10.215  5623  5670 I jxcore-log: 
11-15 18:30:10.215  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 18:30:10.215  5623  5670 I jxcore-log: 
11-15 18:30:10.216  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-15 18:30:10.216  5623  5670 I jxcore-log: 
11-15 18:30:10.216  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 18:30:10.216  5623  5670 I jxcore-log: 
,11-15 18:30:10.216  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 18:30:10.216  5623  5670 I jxcore-log: 
11-15 18:30:10.216  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-15 18:30:10.216  5623  5670 I jxcore-log: 
11-15 18:30:10.217  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 18:30:10.217  5623  5670 I jxcore-log: 
11-15 18:30:10.217  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 18:30:10.217  5623  5670 I jxcore-log: 
11-15 18:30:10.217  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}',
11-15 18:30:10.217  5623  5670 I jxcore-log: 
11-15 18:30:10.217  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 18:30:10.217  5623  5670 I jxcore-log: 
11-15 18:30:10.222  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-15 18:30:10.222  5623  5670 I jxcore-log: 
11-15 18:30:10.222  5623  5670 I jxcore-log: 2016-11-15 17:30:10 - WARN testUtils: 'myNameCallback not set!'
11-15 18:30:10.222  5623  5670 I jxcore-log: 
,11-15 18:30:10.225  5623  5623 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-15 18:30:10.692  3602  3602 I ConfigService: onDestroy
,11-15 18:30:12.334  5623  5670 I jxcore-log: 2016-11-15 17:30:12 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-15 18:30:12.334  5623  5670 I jxcore-log: 
,11-15 18:30:12.336  5623  5670 I jxcore-log: 2016-11-15 17:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-15 18:30:12.336  5623  5670 I jxcore-log: 
,11-15 18:30:12.692  5623  5670 I jxcore-log: 2016-11-15 17:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-15 18:30:12.692  5623  5670 I jxcore-log: 
,11-15 18:30:12.706  5623  5670 I jxcore-log: 2016-11-15 17:30:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-15 18:30:12.706  5623  5670 I jxcore-log: 
,11-15 18:30:13.843  5623  5670 I jxcore-log: 2016-11-15 17:30:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-15 18:30:13.843  5623  5670 I jxcore-log: 
,11-15 18:30:14.014  5623  5670 I jxcore-log: 2016-11-15 17:30:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-15 18:30:14.014  5623  5670 I jxcore-log: 
,11-15 18:30:14.019  5623  5670 I jxcore-log: 2016-11-15 17:30:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-15 18:30:14.019  5623  5670 I jxcore-log: 
,11-15 18:30:14.032  5623  5670 I jxcore-log: 2016-11-15 17:30:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-15 18:30:14.032  5623  5670 I jxcore-log: 
,11-15 18:30:14.531  5623  5670 I jxcore-log: 2016-11-15 17:30:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-15 18:30:14.531  5623  5670 I jxcore-log: 
,11-15 18:30:14.577  5623  5670 I jxcore-log: 2016-11-15 17:30:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-15 18:30:14.577  5623  5670 I jxcore-log: 
,11-15 18:30:14.591  5623  5670 I jxcore-log: 2016-11-15 17:30:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-15 18:30:14.591  5623  5670 I jxcore-log: 
,11-15 18:30:14.595  5623  5670 I jxcore-log: 2016-11-15 17:30:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-15 18:30:14.595  5623  5670 I jxcore-log: 
,11-15 18:30:14.885  5623  5670 I jxcore-log: 2016-11-15 17:30:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-15 18:30:14.885  5623  5670 I jxcore-log: 
,11-15 18:30:14.990   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:30:15.017  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-15 18:30:15.017  5623  5670 I jxcore-log: 
,11-15 18:30:15.396  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-15 18:30:15.396  5623  5670 I jxcore-log: 
,11-15 18:30:15.402  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-15 18:30:15.402  5623  5670 I jxcore-log: 
,11-15 18:30:15.407  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-15 18:30:15.407  5623  5670 I jxcore-log: 
,11-15 18:30:15.410  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-15 18:30:15.410  5623  5670 I jxcore-log: 
,11-15 18:30:15.415  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-15 18:30:15.415  5623  5670 I jxcore-log: 
,11-15 18:30:15.453  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-15 18:30:15.453  5623  5670 I jxcore-log: 
,11-15 18:30:15.459  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-15 18:30:15.459  5623  5670 I jxcore-log: 
,11-15 18:30:15.488  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-15 18:30:15.488  5623  5670 I jxcore-log: 
,11-15 18:30:15.524  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-15 18:30:15.524  5623  5670 I jxcore-log: 
,11-15 18:30:15.531  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-15 18:30:15.531  5623  5670 I jxcore-log: 
,11-15 18:30:15.538  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-15 18:30:15.538  5623  5670 I jxcore-log: 
,11-15 18:30:15.554  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-15 18:30:15.554  5623  5670 I jxcore-log: 
,11-15 18:30:15.569  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-15 18:30:15.569  5623  5670 I jxcore-log: 
,11-15 18:30:15.575  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-15 18:30:15.575  5623  5670 I jxcore-log: 
,11-15 18:30:15.581  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-15 18:30:15.581  5623  5670 I jxcore-log: 
,11-15 18:30:15.595  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-15 18:30:15.595  5623  5670 I jxcore-log: 
,11-15 18:30:15.612  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-15 18:30:15.612  5623  5670 I jxcore-log: 
,11-15 18:30:15.627  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-15 18:30:15.627  5623  5670 I jxcore-log: 
,11-15 18:30:15.638  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-15 18:30:15.638  5623  5670 I jxcore-log: 
,11-15 18:30:15.651  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-15 18:30:15.651  5623  5670 I jxcore-log: 
,11-15 18:30:15.661  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-15 18:30:15.661  5623  5670 I jxcore-log: 
,11-15 18:30:15.675  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-15 18:30:15.675  5623  5670 I jxcore-log: 
,11-15 18:30:15.685  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-15 18:30:15.685  5623  5670 I jxcore-log: 
,11-15 18:30:15.692  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-15 18:30:15.692  5623  5670 I jxcore-log: 
,11-15 18:30:15.713  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-15 18:30:15.713  5623  5670 I jxcore-log: 
,11-15 18:30:15.719  5623  5670 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-15 18:30:15.720  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - INFO testUtils: 'BLE multiple advertisement supported'
11-15 18:30:15.720  5623  5670 I jxcore-log: 
,11-15 18:30:15.798  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:15.798  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:15.798  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:15.798  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:15.798  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:15.798  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:15.798  5623  5670 I jxcore-log: 
,11-15 18:30:15.963  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:15.963  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:15.963  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:15.963  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:15.963  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:15.963  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:15.963  5623  5670 I jxcore-log: 
,11-15 18:30:15.966  5623  5670 I jxcore-log: 2016-11-15 17:30:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:15.966  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:15.966  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:15.966  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:15.966  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:15.966  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:15.966  5623  5670 I jxcore-log: 
11-15 18:30:15.991   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:30:16.348  5623  5670 I jxcore-log: 2016-11-15 17:30:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:16.348  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:16.348  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:16.348  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:16.348  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:16.348  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:16.348  5623  5670 I jxcore-log: 
,11-15 18:30:16.351  5623  5670 I jxcore-log: 2016-11-15 17:30:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:16.351  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:16.351  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:16.351  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:16.351  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:16.351  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:16.351  5623  5670 I jxcore-log: 
,11-15 18:30:16.993   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:30:17.013  5623  5670 I jxcore-log: 2016-11-15 17:30:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:17.013  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:17.013  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:17.013  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:17.013  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:17.013  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:17.013  5623  5670 I jxcore-log: 
,11-15 18:30:17.017  5623  5670 I jxcore-log: 2016-11-15 17:30:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:17.017  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:17.017  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:17.017  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:17.017  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:17.017  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:17.017  5623  5670 I jxcore-log: 
,11-15 18:30:17.994   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:30:18.054  5623  5670 I jxcore-log: 2016-11-15 17:30:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:18.054  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:18.054  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:18.054  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:18.054  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:18.054  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:18.054  5623  5670 I jxcore-log: 
,11-15 18:30:18.059  5623  5670 I jxcore-log: 2016-11-15 17:30:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:18.059  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:18.059  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:18.059  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:18.059  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:18.059  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:18.059  5623  5670 I jxcore-log: 
,11-15 18:30:18.995   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 18:30:19.101  5623  5670 I jxcore-log: 2016-11-15 17:30:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:19.101  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:19.101  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:19.101  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:19.101  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:19.101  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:19.101  5623  5670 I jxcore-log: 
,11-15 18:30:19.105  5623  5670 I jxcore-log: 2016-11-15 17:30:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:19.105  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:19.105  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:19.105  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:19.105  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:19.105  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:19.105  5623  5670 I jxcore-log: 
,11-15 18:30:19.995   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-15 18:30:20.135  5623  5670 I jxcore-log: 2016-11-15 17:30:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:20.135  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:20.135  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:20.135  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:20.135  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:20.135  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:20.135  5623  5670 I jxcore-log: 
,11-15 18:30:20.139  5623  5670 I jxcore-log: 2016-11-15 17:30:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:20.139  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:20.139  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:20.139  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:20.139  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:20.139  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:20.139  5623  5670 I jxcore-log: 
,11-15 18:30:21.168  5623  5670 I jxcore-log: 2016-11-15 17:30:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:21.168  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:21.168  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:21.168  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:21.168  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:21.168  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:21.168  5623  5670 I jxcore-log: 
,11-15 18:30:21.172  5623  5670 I jxcore-log: 2016-11-15 17:30:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:21.172  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:21.172  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:21.172  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:21.172  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:21.172  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:21.172  5623  5670 I jxcore-log: 
,11-15 18:30:22.144   928  5860 D NetlinkSocketObserver: NeighborEvent{elapsedMs=151803, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-15 18:30:22.198  5623  5670 I jxcore-log: 2016-11-15 17:30:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:22.198  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:22.198  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:22.198  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:22.198  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:22.198  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:22.198  5623  5670 I jxcore-log: 
,11-15 18:30:22.203  5623  5670 I jxcore-log: 2016-11-15 17:30:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:22.203  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:22.203  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:22.203  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:22.203  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:22.203  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:22.203  5623  5670 I jxcore-log: 
,11-15 18:30:23.235  5623  5670 I jxcore-log: 2016-11-15 17:30:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:23.235  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:23.235  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:23.235  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:23.235  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:23.235  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:23.235  5623  5670 I jxcore-log: 
,11-15 18:30:23.238  5623  5670 I jxcore-log: 2016-11-15 17:30:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:23.238  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:23.238  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:23.238  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:23.238  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:23.238  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:23.238  5623  5670 I jxcore-log: 
,11-15 18:30:24.308  5623  5670 I jxcore-log: 2016-11-15 17:30:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:24.308  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:24.308  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:24.308  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:24.308  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:24.308  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:24.308  5623  5670 I jxcore-log: 
,11-15 18:30:24.312  5623  5670 I jxcore-log: 2016-11-15 17:30:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:24.312  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:24.312  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:24.312  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:24.312  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:24.312  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:24.312  5623  5670 I jxcore-log: 
,11-15 18:30:25.344  5623  5670 I jxcore-log: 2016-11-15 17:30:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:25.344  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:25.344  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:25.344  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:25.344  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:25.344  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:25.344  5623  5670 I jxcore-log: 
,11-15 18:30:25.351  5623  5670 I jxcore-log: 2016-11-15 17:30:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:25.351  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:25.351  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:25.351  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:25.351  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:25.351  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:25.351  5623  5670 I jxcore-log: 
,11-15 18:30:25.371   928  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 18:30:26.387  5623  5670 I jxcore-log: 2016-11-15 17:30:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:26.387  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:26.387  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:26.387  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:26.387  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:26.387  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:26.387  5623  5670 I jxcore-log: 
,11-15 18:30:26.391  5623  5670 I jxcore-log: 2016-11-15 17:30:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:26.391  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:26.391  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:26.391  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:26.391  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:26.391  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:26.391  5623  5670 I jxcore-log: 
,11-15 18:30:27.191   928  5860 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-15 18:30:27.421  5623  5670 I jxcore-log: 2016-11-15 17:30:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:27.421  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:27.421  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:27.421  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:27.421  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:27.421  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:27.421  5623  5670 I jxcore-log: 
,11-15 18:30:27.427  5623  5670 I jxcore-log: 2016-11-15 17:30:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:27.427  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:27.427  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:27.427  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:27.427  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:27.427  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:27.427  5623  5670 I jxcore-log: 
,11-15 18:30:27.468   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 18:30:28.452  5623  5670 I jxcore-log: 2016-11-15 17:30:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:28.452  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:28.452  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:28.452  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:28.452  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:28.452  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:28.452  5623  5670 I jxcore-log: 
,11-15 18:30:28.455  5623  5670 I jxcore-log: 2016-11-15 17:30:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:28.455  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:28.455  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:28.455  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:28.455  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:28.455  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:28.455  5623  5670 I jxcore-log: 
,11-15 18:30:28.531  4062  4494 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-15 18:30:29.471  5623  5670 I jxcore-log: 2016-11-15 17:30:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 18:30:29.471  5623  5670 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 18:30:29.471  5623  5670 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 18:30:29.471  5623  5670 I jxcore-log: emit@events.js:82:1
11-15 18:30:29.471  5623  5670 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 18:30:29.471  5623  5670 I jxcore-log: emit@events.js:82:1'
11-15 18:30:29.471  5623  5670 I jxcore-log: 
,11-15 18:30:29.474  5623  5670 E jxcore  : Error!: error is undefined
11-15 18:30:29.474  5623  5670 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
11-15 18:30:29.475  5623  5670 I jxcore-log: 2016-11-15 17:30:29 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-15 18:30:29.475  5623  5670 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-15 18:30:29.475  5623  5670 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-15 18:30:29.475  5623  5670 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-15 18:30:29.475  5623  5670 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-15 18:30:29.475  5623  5670 I jxcore-log:     at Manager.prototype.reconn,ect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-15 18:30:29.475  5623  5670 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-15 18:30:29.475  5623  5670 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
11-15 18:30:29.476  5623  5670 I jxcore-log: 2016-11-15 17:30:29 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-15 18:30:29.476  5623  5670 I jxcore-log: 
11-15 18:30:29.477  5623  5670 E jxcore-log: TypeError: 
11-15 18:30:29.477  5623  5670 E jxcore-log: error is undefined
,11-15 18:30:29.477  5623  5670 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-15 18:30:29.477  5623  5670 E jxcore-log: 
,11-15 18:30:29.539   928  2957 W InputDispatcher: channel 'ad4cc5f com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-15 18:30:29.540   928  2957 E InputDispatcher: channel 'ad4cc5f com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-15 18:30:29.546   928  3885 I WindowState: WIN DEATH: Window{ad4cc5f u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-15 18:30:29.546   928  3885 W InputDispatcher: Attempted to unregister already unregistered input channel 'ad4cc5f com.test.thalitest/com.test.thalitest.MainActivity (server)'
11-15 18:30:29.547   928  3889 D GraphicsStats: Buffer count: 2
11-15 18:30:29.547   928  2986 D WifiService: Client connection lost with reason: 4
11-15 18:30:29.549   528   528 I Zygote  : Process 5623 exited cleanly (139)
11-15 18:30:29.551   928  3851 I ActivityManager: Process com.test.thalitest (pid 5623) has died
11-15 18:30:29.552   928  3851 W ActivityManager: Force removing ActivityRecord{f74e0b4 u0 com.test.thalitest/.MainActivity t68}: app died, no saved state
,11-15 18:30:29.590  3813  3813 W Binder_7: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[27271]" dev="sockfs" ino=27271 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 18:30:29.594  3813  3813 W Binder_7: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[27271]" dev="sockfs" ino=27271 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 18:30:29.595   928  3813 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5623 uid 10077
,11-15 18:30:29.596  3679  3679 I Keyboard.Facilitator: onFinishInput()
11-15 18:30:29.597  3602  5910 I VacuumService: Vacuum at: now=1479231029597 tag=VacuumService
,11-15 18:30:29.648  3993  5915 I MicroRecognitionRnrImpl: Starting detection.
,11-15 18:30:29.655  3993  5916 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@931cc0c
,11-15 18:30:29.657   513  5918 I AudioFlinger: AudioFlinger's thread 0xf1b00000 ready to run
,11-15 18:30:29.661   513  3017 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-15 18:30:29.663  3993  5916 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@931cc0c
,11-15 18:30:29.669  3602  5919 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-15 18:30:29.673   513  5918 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-15 18:30:29.673   513  5918 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-15 18:30:29.674   513  5918 I ACDB-LOADER: ACDB AFE returned = -19
11-15 18:30:29.674   513  5918 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-15 18:30:29.674   513  5918 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-15 18:30:29.674   513  5918 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-15 18:30:29.680   513  5918 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-15 18:30:29.704  3602  5911 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-15 18:30:29.707  3602  5911 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-15 18:30:29.722  3602  5911 W Uploader:  no longer exists, so no auth token.
,11-15 18:30:29.727  3602  5919 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 18:30:29.758  3993  3993 I HotwordWorkerImpl: onReady
,11-15 18:30:29.837  5907  5907 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-15 18:30:29.840  5907  5907 D AndroidRuntime: CheckJNI is OFF
,11-15 18:30:29.864  5907  5907 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-15 18:30:29.891  5907  5907 I Radio-JNI: register_android_hardware_Radio DONE
,11-15 18:30:29.907  5907  5907 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-15 18:30:29.918   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-15 18:30:30.059   928   951 I art     : Starting a blocking GC Explicit
,11-15 18:30:30.086  3602  5921 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 18:30:30.121  3820  4030 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-15 18:30:30.142   928   951 I art     : Explicit concurrent mark sweep GC freed 14711(932KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.596ms total 82.420ms
,11-15 18:30:30.159   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-15 18:30:30.162  5907  5907 I art     : System.exit called, status: 0
,11-15 18:30:30.162  5907  5907 I AndroidRuntime: VM exiting with result code 0.
,11-15 18:30:30.175   928   951 I ActivityManager: Start proc 5933:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-15 18:30:30.176   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-15 18:30:30.186  5736  5736 D BluetoothMapAppObserver: onReceive
,11-15 18:30:30.187  5736  5736 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-15 18:30:30.195   928  2958 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-15 18:30:30.195  3679  3679 I Keyboard.Facilitator: resetDictionaries() : en_US
11-15 18:30:30.196  4062  4199 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-15 18:30:30.206  3679  5945 I Keyboard.Facilitator.DecoderInitializer: run()
,11-15 18:30:30.215  3679  5945 I Decoder : createOrResetDecoder
,11-15 18:30:30.247  3417  5948 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-15 18:30:30.258  3781  3781 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-15 18:30:30.268  3602  5919 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-15 18:30:30.270   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-15 18:30:30.277    17    17 W kworker/2:0: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-15 18:30:30.271  3602  3602 I ConfigService: onCreate
,11-15 18:30:30.290    17    17 W kworker/2:0: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 18:30:30.311  3679  5945 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-15 18:30:30.314    17    17 W kworker/2:0: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 18:30:30.324  3417  5948 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
11-15 18:30:30.325  3417  5948 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-15 18:30:30.325  3417  5948 E AndroidRuntime: Process: android.process.acore, PID: 3417
11-15 18:30:30.325  3417  5948 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:30:30.325  3417  5948 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-15 18:30:30.329   928  5953 E DropBoxManagerService: Can't write: system_app_crash
11-15 18:30:30.329   928  5953 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
11-15 18:30:30.329   928  5953 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 18:30:30.329   928  5953 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 18:30:30.329   928  5953 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-15 18:30:30.329   928  5953 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-15 18:30:30.329   928  5953 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-15 18:30:30.329   928  5953 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-15 18:30:30.329   928  5953 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 18:30:30.329   928  5953 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-15 18:30:30.329   928  5953 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 18:30:30.329   928  5953 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 18:30:30.329   928  5953 E DropBoxManagerService: 	... 5 more
,11-15 18:30:30.333  3602  3602 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-15 18:30:30.334  3602  3602 D AndroidRuntime: Shutting down VM
,11-15 18:30:30.334  3602  3602 E AndroidRuntime: FATAL EXCEPTION: main
11-15 18:30:30.334  3602  3602 E AndroidRuntime: Process: com.google.process.gapps, PID: 3602
11-15 18:30:30.334  3602  3602 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-15 18:30:30.334  3602  3602 E AndroidRuntime: 	... 8 more
,11-15 18:30:30.347   405   405 W Binder_2: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[36031]" dev="sockfs" ino=36031 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 18:30:30.347   405   405 W Binder_2: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[36031]" dev="sockfs" ino=36031 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 18:30:30.350   403   403 W Binder_1: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[31474]" dev="sockfs" ino=31474 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 18:30:30.350   403   403 W Binder_1: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[31474]" dev="sockfs" ino=31474 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 18:30:30.353   928  5954 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-15 18:30:30.364   928  5955 E DropBoxManagerService: Can't write: system_app_crash
11-15 18:30:30.364   928  5955 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
11-15 18:30:30.364   928  5955 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 18:30:30.364   928  5955 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 18:30:30.364   928  5955 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-15 18:30:30.364   928  5955 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-15 18:30:30.364   928  5955 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-15 18:30:30.364   928  5955 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-15 18:30:30.364   928  5955 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 18:30:30.364   928  5955 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-15 18:30:30.364   928  5955 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 18:30:30.364   928  5955 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 18:30:30.364   928  5955 E DropBoxManagerService: 	... 5 more
,11-15 18:30:30.365  3679  5945 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-15 18:30:30.367  3679  5945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-15 18:30:30.368  3679  5945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-15 18:30:30.369  3679  5945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-15 18:30:30.369  3679  5945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,11-15 18:30:30.371  3679  5945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-15 18:30:30.371  3679  5945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,11-15 18:30:30.372  3679  5945 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,11-15 18:30:30.372  3679  5945 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-15 18:30:30.373  3679  5945 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-15 18:30:30.373  3679  5945 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-15 18:30:30.373  3679  5945 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,11-15 18:30:30.373  3679  5945 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-15 18:30:30.477   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 18:30:30.697   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
