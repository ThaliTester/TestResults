#### Test 931424429bf0021_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-21 16:03:30.459   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:03:30.940  5681  5681 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-21 16:03:30.946  5681  5681 D AndroidRuntime: CheckJNI is OFF
11-21 16:03:30.974  5681  5681 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-21 16:03:31.009  5681  5681 I Radio-JNI: register_android_hardware_Radio DONE
11-21 16:03:31.027  5681  5681 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-21 16:03:31.034   928  3152 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-21 16:03:31.053  5681  5681 D AndroidRuntime: Shutting down VM
11-21 16:03:31.059  3950  5581 W SearchService: Abort, client detached.
11-21 16:03:31.072  3950  3950 I HotwordDetector: Closing mic
11-21 16:03:31.072  3950  4196 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ea40a35
11-21 16:03:31.073  3950  4202 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-21 16:03:31.089   928   939 I ActivityManager: Start proc 5690:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-21 16:03:31.142   514  4209 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-21 16:03:31.143   514  4209 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-21 16:03:31.151   514  4209 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-21 16:03:31.151   514  4209 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-21 16:03:31.152   514  3040 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-21 16:03:31.154  3950  4197 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-21 16:03:31.155  3950  4200 I MicroRecognitionRnrImpl: Detection finished
11-21 16:03:31.183  5690  5690 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-21 16:03:31.210  5690  5690 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-21 16:03:31.232  5690  5690 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 6754-6772)
11-21 16:03:31.232  5690  5690 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-21 16:03:31.248  5690  5690 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b54db06}
11-21 16:03:31.249  5690  5690 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-21 16:03:31.249  5690  5690 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-21 16:03:31.252  5690  5690 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-21 16:03:31.254  5690  5690 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-21 16:03:31.283  5690  5690 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-21 16:03:31.294  5690  5690 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-21 16:03:31.294  5690  5690 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-21 16:03:31.294  5690  5690 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-21 16:03:31.294  5690  5690 I Adreno  : Build Date                       : 12/06/15
11-21 16:03:31.294  5690  5690 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-21 16:03:31.294  5690  5690 I Adreno  : Local Branch                     : mybranch17112971
11-21 16:03:31.294  5690  5690 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-21 16:03:31.294  5690  5690 I Adreno  : Remote Branch                    : NONE
11-21 16:03:31.294  5690  5690 I Adreno  : Reconstruct Branch               : NOTHING
,11-21 16:03:31.325   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b96706b:true
,11-21 16:03:31.347   403   403 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[13893]" dev="sockfs" ino=13893 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:03:31.347   403   403 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[13893]" dev="sockfs" ino=13893 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:03:31.359  5690  5690 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-21 16:03:31.367  5690  5690 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-21 16:03:31.390  2979  2979 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33858]" dev="sockfs" ino=33858 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:03:31.393  5690  5727 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-21 16:03:31.390  2979  2979 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33858]" dev="sockfs" ino=33858 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:03:31.390   939   939 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[35960]" dev="sockfs" ino=35960 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:03:31.390   939   939 W Binder_2: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[35960]" dev="sockfs" ino=35960 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:03:31.396  5690  5714 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-21 16:03:31.420  5690  5727 I OpenGLRenderer: Initialized EGL, version 1.4
,11-21 16:03:31.460   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:03:31.483  3428  3428 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32950]" dev="sockfs" ino=32950 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:03:31.488   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +423ms
11-21 16:03:31.483  3428  3428 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32950]" dev="sockfs" ino=32950 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 16:03:31.487  3875  3875 W Binder_7: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32949]" dev="sockfs" ino=32949 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 16:03:31.487  3875  3875 W Binder_7: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32949]" dev="sockfs" ino=32949 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:03:31.492  3699  3699 I Keyboard.Facilitator: onFinishInput()
,11-21 16:03:31.541  5690  5690 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5690
,11-21 16:03:31.676  5690  5690 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-21 16:03:31.781  5690  5729 D jxcore_app_log: JniHelper::setJavaVM(0xf55fc000), pthread_self() = -575932112
,11-21 16:03:31.784  5690  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-21 16:03:31.784  5690  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-21 16:03:31.784  5690  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-21 16:03:31.784  5690  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-21 16:03:31.784  5690  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-21 16:03:31.785  5690  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d8ea95 added. We now have 1 listener(s)
11-21 16:03:31.787  5690  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
11-21 16:03:31.787  5690  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 16:03:31.788  5690  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-21 16:03:31.788  5690  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-21 16:03:31.790  5690  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f686f38 added. We now have 1 listener(s)
11-21 16:03:31.790  5690  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 16:03:31.794   928  2988 D WifiService: New client listening to asynchronous messages
,11-21 16:03:31.794  5690  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 16:03:31.794  5690  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-21 16:03:31.795  5690  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-21 16:03:31.795  5690  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-21 16:03:31.795  5690  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-21 16:03:31.795  5690  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-21 16:03:31.795  5690  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-21 16:03:31.796  5690  5729 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-21 16:03:31.852  5690  5690 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-21 16:03:31.883   928  3428 I ActivityManager: Killing 5049:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-21 16:03:31.915   928  3428 I ActivityManager: Killing 5248:com.android.settings/1000 (adj 15): empty #18
,11-21 16:03:32.342  5690  5736 W jxcore-log: Initializing JXcore engine
,11-21 16:03:32.342  5690  5736 W jxcore-log: JXcore engine is ready
,11-21 16:03:32.367  5736  5736 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1165 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-21 16:03:32.367  5736  5736 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14526]" dev="sockfs" ino=14526 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-21 16:03:32.367  5736  5736 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-21 16:03:32.367  5736  5736 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32927]" dev="sockfs" ino=32927 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-21 16:03:32.377  5690  5736 W jxcore-log: Starting JXcore engine
,11-21 16:03:32.429  5690  5736 W jxcore-log: Platform android
11-21 16:03:32.429  5690  5736 W jxcore-log: 
,11-21 16:03:32.429  5690  5736 W jxcore-log: Process ARCH arm
11-21 16:03:32.429  5690  5736 W jxcore-log: 
,11-21 16:03:32.461   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:03:32.571  5690  5736 I jxcore-log: JXcore Cordova bridge is ready!
11-21 16:03:32.571  5690  5736 I jxcore-log: 
,11-21 16:03:32.571  5690  5736 W jxcore-log: JXcore engine is started
,11-21 16:03:32.580  5690  5729 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-21 16:03:32.584  5690  5690 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-21 16:03:33.461   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 16:03:33.687   928  5365 D NetlinkSocketObserver: NeighborEvent{elapsedMs=169227, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:03:36.429   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 16:03:41.263   928  2988 D WifiService: New client listening to asynchronous messages
,11-21 16:03:41.275  3950  5738 W CronetSyncConnectionRcs: Upload content type not set.
,11-21 16:03:42.215  5690  5736 I jxcore-log: 2016-11-21 15:03:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-21 16:03:42.215  5690  5736 I jxcore-log: 
,11-21 16:03:42.216  5690  5736 I jxcore-log: 2016-11-21 15:03:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-21 16:03:42.216  5690  5736 I jxcore-log: 
11-21 16:03:42.217  5690  5736 I jxcore-log: 2016-11-21 15:03:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
11-21 16:03:42.217  5690  5736 I jxcore-log: 
11-21 16:03:42.222  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-21 16:03:42.222  5690  5736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 16:03:42.222  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:03:42.222  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:03:42.222  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:03:42.222  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:03:42.222  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:03:42.222  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:03:42.222  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:03:42.222  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 16:03:42.224  5690  5736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 16:03:42.227  5690  5736 I jxcore-log: 2016-11-21 15:03:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-21 16:03:42.227  5690  5736 I jxcore-log: 
11-21 16:03:42.228  5690  5736 I jxcore-log: 2016-11-21 15:03:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-21 16:03:42.228  5690  5736 I jxcore-log: 
,11-21 16:03:42.476   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 16:03:42.486  5690  5736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 16:03:42.486  5690  5736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8afe5aa added. We now have 2 listener(s)
,11-21 16:03:42.487  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:03:42.487  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 16:03:42.487  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-21 16:03:42.487  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 16:03:42.487  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65ac59b added. We now have 2 listener(s)
11-21 16:03:42.487  5690  5736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 16:03:42.490  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 16:03:42.491  5690  5736 D ExecuteNativeTests: Running unit tests
11-21 16:03:42.492  5690  5736 D BluetoothAdapter: enable(): BT is already enabled..!
11-21 16:03:42.492   928   938 D WifiService: setWifiEnabled: true pid=5690, uid=10077
11-21 16:03:42.492   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:03:46.314   928  5365 D NetlinkSocketObserver: NeighborEvent{elapsedMs=181854, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:03:46.317   928  2987 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 16:03:52.497  5690  5736 I com.test.thalitest.ThaliTestRunner: Running UT
,11-21 16:03:52.564  5690  5736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 16:03:52.564  5690  5736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@384ccac added. We now have 3 listener(s)
,11-21 16:03:52.565  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:03:52.565  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 16:03:52.565  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 16:03:52.565  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 16:03:52.565  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eefbd75 added. We now have 3 listener(s)
11-21 16:03:52.566  5690  5736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 16:03:52.567  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 16:03:52.572  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-21 16:03:52.572  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 16:03:52.573  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:03:52.573  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:03:52.573  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-21 16:03:52.574  5690  5736 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-21 16:03:52.574  5690  5736 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-21 16:03:52.574  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 16:03:52.574  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-21 16:03:52.574  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:03:52.574  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:03:52.575  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-21 16:03:52.576  5690  5736 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-21 16:03:52.577  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-21 16:03:52.581  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-21 16:03:52.581  5690  5736 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-21 16:03:52.583  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:03:52.584  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 16:03:52.602  5690  5736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 16:03:52.602  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:03:52.602  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:03:52.602  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:03:52.602  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:03:52.602  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:03:52.602  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:03:52.602  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:03:52.602  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 16:03:52.604  5690  5736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 16:03:52.604  5690  5736 D io.jxcore.node.ConnectivityMonitor: start: OK
11-21 16:03:52.605  5690  5736 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-21 16:03:52.605  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-21 16:03:52.605  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.605  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.605  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:52.605  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:03:52.605  5690  5736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 16:03:52.605  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:03:52.606  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 16:03:52.609  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 16:03:52.610  5690  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 16:03:52.610  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-21 16:03:52.611  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:03:52.611  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 16:03:52.611  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:03:52.611  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-21 16:03:52.611  5690  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:03:52.611  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:03:52.611  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 16:03:52.613  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:03:52.613  5690  5736 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:03:52.613  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 16:03:52.613  5690  5752 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:03:52.613  5690  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 16:03:52.614  5690  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:03:52.616  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.616  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:03:52.616  5690  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 16:03:52.617  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:03:52.610  4877  4877 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33095]" dev="sockfs" ino=33095 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:03:52.617  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:03:52.617  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-21 16:03:52.610  4877  4877 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33095]" dev="sockfs" ino=33095 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:03:52.618  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:52.618  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.618  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:03:52.618  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:03:52.618  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:03:52.618  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-21 16:03:52.619  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 16:03:52.619  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:03:52.619  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.619  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:03:52.619  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:03:52.619  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.619  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:52.619  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.620  5690  5736 D BluetoothAdapter: STATE_ON
,11-21 16:03:52.622  4663  4877 D BtGatt.GattService: registerClient() - UUID=1608f782-56e3-4034-9314-a29f0dfddf3e
,11-21 16:03:52.623  4663  4725 D BtGatt.GattService: onClientRegistered() - UUID=1608f782-56e3-4034-9314-a29f0dfddf3e, clientIf=5
,11-21 16:03:52.624  5690  5701 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 16:03:52.626  4663  4727 D BtGatt.AdvertiseManager: message : 0
,11-21 16:03:52.628  4663  4727 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:03:52.644  4663  4725 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:03:52.652  4663  4725 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:03:52.653  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:52.653  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.653  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:03:52.653  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.654  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.654  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.654  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:52.654  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.654  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:03:52.654  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:03:52.654  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.655  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.655  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.655  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:52.655  5690  5736 I io.jxcore.node.ConnectionHelper: start: OK
11-21 16:03:52.655  5690  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-21 16:03:52.656  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-21 16:03:52.656  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:03:52.656  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:03:52.656  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:03:52.657  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:52.657  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:03:52.657  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:03:52.657  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:03:52.658  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:03:52.658  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:03:52.658  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-21 16:03:52.658  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 16:03:52.658  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:03:52.661  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:03:52.661  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 16:03:52.661  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:52.661  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:52.661  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:03:52.662  5690  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:03:53.159  5690  5736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-21 16:03:53.159  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-21 16:03:53.159  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-21 16:03:53.159  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-21 16:03:53.159  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-21 16:03:53.159  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-21 16:03:53.159  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-21 16:03:53.160  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-21 16:03:53.160  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-21 16:03:53.160  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-21 16:03:53.160  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-21 16:03:53.160  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-21 16:03:53.160  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-21 16:03:53.160  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-21 16:03:53.160  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-21 16:03:53.161  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-21 16:03:53.161  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-21 16:03:53.161  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-21 16:03:53.161  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-21 16:03:53.161  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-21 16:03:53.161  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-21 16:03:53.161  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-21 16:03:53.161  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-21 16:03:53.161  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-21 16:03:53.162  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-21 16:03:53.162  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-21 16:03:53.162  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-21 16:03:53.162  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-21 16:03:53.162  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-21 16:03:53.162  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-21 16:03:53.162  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-21 16:03:53.162  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-21 16:03:53.163  5690  5736 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-21 16:03:53.163  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-21 16:03:53.163  5690  5736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 16:03:53.163  5690  5690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 16:03:53.163  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-21 16:03:53.163  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:03:53.164  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:03:53.164  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 16:03:53.164  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 16:03:53.164  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:03:53.164  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 16:03:53.164  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:03:53.165  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:03:53.165  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:03:53.165  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.165  5690  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:03:53.165  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.166  5690  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:03:53.166  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.166  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.166  5690  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:03:53.167  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:03:53.168  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:03:53.169  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:03:53.169  5690  5736 D BluetoothLeScanner: could not find callback wrapper
11-21 16:03:53.169  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-21 16:03:53.169  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.169  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.169  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.169  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:03:53.170  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.171  4663  4727 D BtGatt.AdvertiseManager: message : 1
11-21 16:03:53.172  4663  4727 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:03:53.182  4663  4725 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 16:03:53.182  4663  4725 D BtGatt.GattService: Client app is not null!
,11-21 16:03:53.183  4663  4861 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 16:03:53.184  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 16:03:53.184  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.184  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:03:53.184  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.185  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.185  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.185  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 16:03:53.185  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 16:03:53.186  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:03:53.186  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.189  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.189  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:03:53.189  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.189  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.190  5690  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 16:03:53.190  5690  5690 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 16:03:53.191  5690  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:03:53.191  5690  5736 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 16:03:53.191  5690  5736 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 16:03:53.191  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:03:53.191  5690  5736 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-21 16:03:53.191  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:03:53.191  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,11-21 16:03:53.191  5690  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-21 16:03:53.191  5690  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:03:53.191  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.191  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:03:53.191  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.191  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.192  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.192  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:03:53.192  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:03:53.192  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-21 16:03:53.192  5690  5736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 16:03:53.192  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-21 16:03:53.192  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:03:53.192  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:03:53.192  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.193  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 16:03:53.194  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:03:53.194  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:03:53.194  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 16:03:53.194  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:03:53.194  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 16:03:53.194  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:03:53.194  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 16:03:53.194  5690  5755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:03:53.194  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 16:03:53.195  5690  5755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:03:53.193  4678  4678 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33105]" dev="sockfs" ino=33105 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:03:53.193  4678  4678 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33105]" dev="sockfs" ino=33105 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:03:53.198  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:03:53.198  5690  5736 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:03:53.198  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 16:03:53.199  5690  5755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 16:03:53.203  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.203  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:03:53.204  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:03:53.204  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:03:53.204  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-21 16:03:53.207  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.207  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.207  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:03:53.207  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:03:53.207  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:03:53.207  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-21 16:03:53.208  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:03:53.208  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:03:53.208  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.208  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:03:53.208  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:03:53.208  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.208  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.208  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.210  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:03:53.213  4663  4861 D BtGatt.GattService: registerClient() - UUID=cbd60041-5ea0-4647-a6fe-a41d8ffe90f8
11-21 16:03:53.214  4663  4725 D BtGatt.GattService: onClientRegistered() - UUID=cbd60041-5ea0-4647-a6fe-a41d8ffe90f8, clientIf=5
11-21 16:03:53.214  5690  5701 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 16:03:53.216  4663  4727 D BtGatt.AdvertiseManager: message : 0
11-21 16:03:53.218  4663  4727 D BtGatt.AdvertiseManager: starting multi advertising
11-21 16:03:53.228  4663  4725 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-21 16:03:53.234  4663  4725 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-21 16:03:53.234  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.235  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.235  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:03:53.235  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.235  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.235  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.235  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.235  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.235  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:03:53.237  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:03:53.237  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.238  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.239  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.239  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.239  5690  5736 I io.jxcore.node.ConnectionHelper: start: OK
11-21 16:03:53.239  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.240  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.240  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.240  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.240  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.240  5690  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:03:53.240  5690  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:03:53.240  5690  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:03:53.241  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.241  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:03:53.241  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:03:53.241  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.241  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.241  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:03:53.241  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.241  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:03:53.241  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:03:53.241  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.241  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.241  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 16:03:53.241  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.244  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.244  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 16:03:53.244  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.244  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.244  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.244  5690  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:03:53.463   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:03:53.743  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-21 16:03:53.744  5690  5736 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 16:03:53.744  5690  5736 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 16:03:53.744  5690  5736 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-21 16:03:53.744  5690  5736 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-21 16:03:53.744  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-21 16:03:53.745  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.745  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.745  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.745  5690  5690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-21 16:03:53.749  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 16:03:53.749  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 16:03:53.749  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 16:03:53.749  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-21 16:03:53.749  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 16:03:53.749  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 16:03:53.749  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 16:03:53.749  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 16:03:53.749  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 16:03:53.749  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.750  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
,11-21 16:03:53.755  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.756  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.757  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.761  4663  4727 D BtGatt.AdvertiseManager: message : 1
,11-21 16:03:53.761  4663  4727 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:03:53.768  4663  4725 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 16:03:53.768  4663  4725 D BtGatt.GattService: Client app is not null!
11-21 16:03:53.769  4663  4877 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 16:03:53.769  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 16:03:53.770  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.770  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-21 16:03:53.770  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.770  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.770  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.770  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-21 16:03:53.770  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.770  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.770  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.770  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-21 16:03:53.770  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:03:53.770  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:03:53.771  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
,11-21 16:03:53.771  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:03:53.771  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:03:53.771  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.771  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:03:53.771  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:03:53.771  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.771  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.772  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.772  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:03:53.778  4663  4877 D BtGatt.GattService: registerClient() - UUID=662c36a2-2b85-45a8-9e8e-d140b8e7b88a
,11-21 16:03:53.778  4663  4725 D BtGatt.GattService: onClientRegistered() - UUID=662c36a2-2b85-45a8-9e8e-d140b8e7b88a, clientIf=5
11-21 16:03:53.779  5690  5700 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 16:03:53.780  4663  4727 D BtGatt.AdvertiseManager: message : 0
11-21 16:03:53.783  4663  4727 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:03:53.796  4663  4725 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:03:53.803  4663  4725 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:03:53.804  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.804  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.805  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:03:53.805  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.805  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.805  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.805  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.805  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.805  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.805  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:03:53.805  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.805  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-21 16:03:53.805  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 16:03:53.805  5690  5736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-21 16:03:53.806  5690  5736 I io.jxcore.node.ConnectionHelper: start: OK
11-21 16:03:53.806  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.806  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:03:53.806  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:03:53.806  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.806  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.806  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:03:53.806  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.806  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-21 16:03:53.806  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 16:03:53.806  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.806  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.806  5690  5736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-21 16:03:53.807  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 16:03:53.807  5690  5736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 16:03:53.807  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:03:53.807  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-21 16:03:53.807  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:03:53.807  5690  5755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:03:53.807  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 16:03:53.807  5690  5755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:03:53.807  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 16:03:53.807  5690  5755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:03:53.807  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:03:53.807  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 16:03:53.807  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:03:53.807  5690  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-21 16:03:53.807  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:03:53.808  5690  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:03:53.808  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:03:53.808  5690  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:03:53.808  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.808  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.808  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.808  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.809  5690  5736 D BluetoothAdapter: STATE_ON
,11-21 16:03:53.809  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:03:53.810  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:03:53.810  5690  5736 D BluetoothLeScanner: could not find callback wrapper
11-21 16:03:53.810  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:03:53.810  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.810  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.811  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.811  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:03:53.811  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.812  4663  4727 D BtGatt.AdvertiseManager: message : 1
11-21 16:03:53.812  4663  4727 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:03:53.818  4663  4725 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 16:03:53.818  4663  4725 D BtGatt.GattService: Client app is not null!
11-21 16:03:53.819  4663  4861 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 16:03:53.820  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 16:03:53.820  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.820  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:03:53.820  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.820  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.820  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.820  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-21 16:03:53.820  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 16:03:53.821  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:03:53.821  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.822  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.822  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:03:53.822  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.822  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.822  5690  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 16:03:53.822  5690  5690 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 16:03:53.822  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:03:53.822  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:03:53.823  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:03:53.823  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.823  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:03:53.823  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-21 16:03:53.823  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.823  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.823  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 16:03:53.823  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.824  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-21 16:03:53.824  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.824  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.824  5690  5736 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-21 16:03:53.824  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-21 16:03:53.824  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.825  5690  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 16:03:53.826  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,11-21 16:03:53.826  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 16:03:53.827  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-21 16:03:53.827  5690  5736 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-21 16:03:53.828  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-21 16:03:53.828  5690  5736 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-21 16:03:53.829  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-21 16:03:53.829  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 16:03:53.829  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:03:53.829  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:03:53.829  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:03:53.829  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 16:03:53.829  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:03:53.829  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:03:53.829  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:03:53.829  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 16:03:53.829  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-21 16:03:53.829  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-21 16:03:53.830  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:03:53.831  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-21 16:03:53.831  5690  5736 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 16:03:53.831  5690  5736 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-21 16:03:53.834  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,11-21 16:03:53.834  5690  5736 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-21 16:03:53.835  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-21 16:03:53.835  5690  5736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-21 16:03:53.836  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-21 16:03:53.836  5690  5736 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-21 16:03:53.836  5690  5736 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-21 16:03:53.836  5690  5736 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-21 16:03:53.836  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 16:03:53.836  5690  5736 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-21 16:03:53.836  5690  5736 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 16:03:53.837  5690  5736 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-21 16:03:53.837  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 16:03:53.837  5690  5736 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-21 16:03:53.837  5690  5736 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 16:03:53.837  5690  5736 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-21 16:03:53.837  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 16:03:53.837  5690  5736 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-21 16:03:53.838  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-21 16:03:53.838  5690  5736 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-21 16:03:53.838  5690  5736 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 16:03:53.838  5690  5736 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-21 16:03:53.838  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-21 16:03:53.838  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.838  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.838  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.838  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:03:53.838  5690  5736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 16:03:53.838  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:03:53.838  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:03:53.840  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 16:03:53.840  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-21 16:03:53.840  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:03:53.841  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 16:03:53.841  5690  5759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:03:53.841  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:03:53.841  5690  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:03:53.841  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 16:03:53.841  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:03:53.841  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 16:03:53.841  5690  5759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:03:53.840  4861  4861 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33894]" dev="sockfs" ino=33894 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:03:53.844  5690  5759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 16:03:53.844  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:03:53.845  5690  5736 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:03:53.845  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 16:03:53.840  4861  4861 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33894]" dev="sockfs" ino=33894 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:03:53.848  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.848  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-21 16:03:53.849  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-21 16:03:53.849  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:03:53.849  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
,11-21 16:03:53.851  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:53.851  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.851  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:03:53.851  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:03:53.851  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:03:53.851  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
,11-21 16:03:53.852  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:03:53.852  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:03:53.852  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.852  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:03:53.852  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 16:03:53.852  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.852  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.852  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.853  5690  5736 D BluetoothAdapter: STATE_ON
,11-21 16:03:53.855  4663  4861 D BtGatt.GattService: registerClient() - UUID=32a1c9ad-98cf-45b5-8b87-923b5f6186ef
11-21 16:03:53.855  4663  4725 D BtGatt.GattService: onClientRegistered() - UUID=32a1c9ad-98cf-45b5-8b87-923b5f6186ef, clientIf=5
,11-21 16:03:53.856  5690  5700 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 16:03:53.857  4663  4727 D BtGatt.AdvertiseManager: message : 0
,11-21 16:03:53.858  4663  4727 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:03:53.874  4663  4725 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:03:53.880  4663  4725 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:03:53.881  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.881  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.881  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:03:53.881  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.881  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.881  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.881  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.881  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.881  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:03:53.882  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:03:53.883  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.884  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.884  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.884  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:53.884  5690  5736 I io.jxcore.node.ConnectionHelper: start: OK
11-21 16:03:53.884  5690  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:03:53.884  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.884  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:03:53.884  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:03:53.884  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.884  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.885  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:03:53.885  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.885  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:03:53.885  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:03:53.885  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.885  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.885  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 16:03:53.885  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.887  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.887  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 16:03:53.887  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.887  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.887  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:03:53.888  5690  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:03:54.385  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-21 16:03:54.386  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:03:54.386  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:03:54.386  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:03:54.387  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 16:03:54.387  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-21 16:03:54.387  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-21 16:03:54.387  5690  5759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:03:54.387  5690  5759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 16:03:54.387  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 16:03:54.387  5690  5759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-21 16:03:54.388  5690  5736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@384ccac removed from the list
11-21 16:03:54.388  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 16:03:54.388  5690  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:03:54.388  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-21 16:03:54.388  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:03:54.388  5690  5690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 16:03:54.388  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:03:54.388  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.389  5690  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:03:54.389  5690  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:03:54.389  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.389  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:54.389  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.394  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:03:54.394  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:03:54.395  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:03:54.396  5690  5736 D BluetoothLeScanner: could not find callback wrapper
11-21 16:03:54.396  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-21 16:03:54.396  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.396  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.397  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.397  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:03:54.397  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.398  4663  4727 D BtGatt.AdvertiseManager: message : 1
11-21 16:03:54.400  4663  4727 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:03:54.410  4663  4725 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 16:03:54.410  4663  4725 D BtGatt.GattService: Client app is not null!
,11-21 16:03:54.411  4663  4677 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 16:03:54.412  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 16:03:54.412  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:54.412  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:03:54.412  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.412  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.412  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.412  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 16:03:54.412  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 16:03:54.413  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:03:54.413  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:03:54.414  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.415  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:03:54.415  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.415  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:54.415  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eefbd75 removed from the list
11-21 16:03:54.415  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:03:54.415  5690  5736 D io.jxcore.node.ConnectivityMonitor: stop
11-21 16:03:54.415  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 16:03:54.415  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:03:54.415  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:03:54.415  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:03:54.415  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:03:54.415  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 16:03:54.415  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:03:54.416  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:03:54.416  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 16:03:54.416  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:03:54.417  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:03:54.417  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:54.417  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:03:54.417  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:03:54.418  5690  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 16:03:54.464   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:03:54.919  5690  5690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 16:03:55.465   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:03:56.466   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:03:57.467   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:03:58.468   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 16:03:59.421  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-21 16:03:59.425  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:03:59.425  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:03:59.426  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 16:03:59.433  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 16:03:59.434  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-21 16:03:59.434  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-21 16:03:59.435  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-21 16:03:59.435  5690  5760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:03:59.435  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-21 16:03:59.435  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-21 16:03:59.435  5690  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:03:59.437  5690  5760 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:03:59.440  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-21 16:03:59.441  5690  5760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 16:03:59.437  4677  4677 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31900]" dev="sockfs" ino=31900 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:03:59.437  4677  4677 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31900]" dev="sockfs" ino=31900 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:03:59.442  5690  5736 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-21 16:03:59.443  5690  5736 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-21 16:03:59.443  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 16:03:59.444  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:03:59.444  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-21 16:03:59.447  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-21 16:03:59.455  5690  5736 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-21 16:03:59.456  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 16:03:59.456  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:03:59.456  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:03:59.456  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-21 16:03:59.457  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 16:03:59.457  5690  5760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:03:59.457  5690  5760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:03:59.457  5690  5760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:03:59.457  5690  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:03:59.458  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-21 16:03:59.458  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:03:59.458  5690  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:03:59.458  5690  5736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@384ccac not in the list
11-21 16:03:59.458  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-21 16:03:59.458  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:03:59.458  5690  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:03:59.459  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:03:59.459  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-21 16:03:59.459  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:59.461  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:59.461  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 16:03:59.461  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:59.461  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:03:59.461  5690  5736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eefbd75 not in the list
11-21 16:03:59.461  5690  5736 D io.jxcore.node.ConnectivityMonitor: stop
11-21 16:03:59.461  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-21 16:03:59.461  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:03:59.461  5690  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:03:59.463  5690  5736 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-21 16:03:59.463  5690  5736 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-21 16:03:59.464  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 16:03:59.465  5690  5736 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-21 16:03:59.465  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 16:03:59.465  5690  5736 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-21 16:03:59.465  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 16:03:59.466  5690  5736 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-21 16:03:59.467  5690  5736 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-21 16:03:59.468  5690  5736 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-21 16:03:59.469  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 16:03:59.469  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-21 16:03:59.469  5690  5736 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-21 16:03:59.470  5690  5736 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-21 16:03:59.470  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-21 16:03:59.470  5690  5736 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-21 16:03:59.470  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 16:03:59.470  5690  5736 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-21 16:03:59.470  5690  5736 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-21 16:03:59.471  5690  5736 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-21 16:03:59.471  5690  5736 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-21 16:03:59.471  5690  5736 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-21 16:03:59.472  5690  5736 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-21 16:03:59.472  5690  5736 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-21 16:03:59.472  5690  5736 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-21 16:03:59.472  5690  5736 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-21 16:03:59.473  5690  5736 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-21 16:03:59.474  5690  5736 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-21 16:03:59.474  5690  5736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 16:03:59.474  5690  5736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e66b6b added. We now have 3 listener(s)
11-21 16:03:59.476  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:03:59.477  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 16:03:59.477  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-21 16:03:59.477  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 16:03:59.477  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9886c8 added. We now have 3 listener(s)
11-21 16:03:59.477  5690  5736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 16:03:59.478  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 16:03:59.481  5690  5736 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 16:03:59.481   928   938 D WifiService: setWifiEnabled: true pid=5690, uid=10077
11-21 16:03:59.481   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:03:59.483  5690  5736 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-21 16:03:59.487  5690  5736 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-21 16:03:59.487  5690  5736 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-21 16:03:59.490  5690  5736 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-21 16:03:59.491  5690  5736 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-21 16:03:59.497  5690  5736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:03:59.497  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:03:59.497  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:03:59.497  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:03:59.497  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:03:59.497  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:03:59.497  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:03:59.497  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:03:59.497  5690  5736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 16:03:59.499  4663  4721 D BluetoothAdapterState: Current state: ON, message: 23
11-21 16:03:59.499  4663  4721 D BluetoothAdapterProperties: Setting state to 13
11-21 16:03:59.499  4663  4721 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-21 16:03:59.500  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
11-21 16:03:59.500  5690  5736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 16:03:59.502  4663  4721 D BluetoothAdapterProperties: onBluetoothDisable()
11-21 16:03:59.503  4663  4721 I BluetoothAdapterState: Entering PendingCommandState
,11-21 16:03:59.504  4663  4663 D BluetoothMapService: onReceive
,11-21 16:03:59.504  4663  4663 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 16:03:59.505  4663  4663 D BluetoothMapService: STATE_TURNING_OFF
11-21 16:03:59.505  4663  4663 D BluetoothMapService: MAP Service closeService in
11-21 16:03:59.505  4663  4663 D BluetoothMapMasInstance0: MAP Service shutdown
11-21 16:03:59.505  4663  4663 D ObexServerSockets0: shutdown(block = true)
11-21 16:03:59.506  4663  4663 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-21 16:03:59.506  4663  4882 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-21 16:03:59.506  4663  4663 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-21 16:03:59.506  4663  4883 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-21 16:03:59.506  4663  4859 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-21 16:03:59.508  4663  4663 I BtOppRfcommListener: stopping Accept Thread
11-21 16:03:59.508  4663  5291 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-21 16:03:59.508  4663  5291 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-21 16:03:59.520   928   941 I ActivityManager: Start proc 5763:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-21 16:03:59.521  4663  4725 D BluetoothAdapterProperties: Scan Mode:20
,11-21 16:03:59.522  4663  4721 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-21 16:03:59.524  4663  4663 D HeadsetService: Received stop request...Stopping profile...
11-21 16:03:59.527  3144  3160 D BluetoothHeadset: Proxy object disconnected
,11-21 16:03:59.527  3802  3835 D BluetoothHeadset: Proxy object disconnected
11-21 16:03:59.527  4663  4663 D A2dpService: Received stop request...Stopping profile...
11-21 16:03:59.527  4663  4864 D A2dpStateMachine: Exit Disconnected: -1
,11-21 16:03:59.528   928   928 D BluetoothHeadset: Proxy object disconnected
,11-21 16:03:59.528   928   928 D BluetoothHeadset: Proxy object disconnected
11-21 16:03:59.528   928   928 D BluetoothHeadset: Proxy object disconnected
11-21 16:03:59.529   928   928 D BluetoothA2dp: Proxy object disconnected
11-21 16:03:59.529  4663  4663 V BluetoothAdapterState: isTurningOff()=true
11-21 16:03:59.530  4663  4663 V BluetoothAdapterState: isTurningOn()=false
11-21 16:03:59.530  4663  4663 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:03:59.530  4663  4663 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 16:03:59.533  3144  3144 D HeadsetProfile: Bluetooth service disconnected
,11-21 16:03:59.533  3144  3144 D BluetoothA2dp: Proxy object disconnected
11-21 16:03:59.533  4663  4663 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-21 16:03:59.533  4663  4663 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-21 16:03:59.534  4663  4853 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 16:03:59.534  4663  4725 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-21 16:03:59.535  4663  4853 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 16:03:59.535  4663  4853 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 16:03:59.535  4663  4725 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-21 16:03:59.536  4663  4663 D HidService: Received stop request...Stopping profile...
,11-21 16:03:59.536  4663  4663 D HidService: Stopping Bluetooth HidService
11-21 16:03:59.537  3144  3144 D BluetoothInputDevice: Proxy object disconnected
,11-21 16:03:59.537  4663  4663 V BluetoothAdapterState: isTurningOff()=true
,11-21 16:03:59.537  4663  4663 V BluetoothAdapterState: isTurningOn()=false
11-21 16:03:59.537  4663  4663 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:03:59.537  4663  4663 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:03:59.537  3144  3144 D HidProfile: Bluetooth service disconnected
,11-21 16:03:59.541  4663  4725 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-21 16:03:59.541  4663  4853 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 16:03:59.541  4663  4853 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 16:03:59.541  4663  4853 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-21 16:03:59.541  4663  4853 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-21 16:03:59.541  4663  4853 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-21 16:03:59.541  4663  4853 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-21 16:03:59.542  4663  4663 D HealthService: Received stop request...Stopping profile...
11-21 16:03:59.543  4663  4663 D PanService: Received stop request...Stopping profile...
11-21 16:03:59.544  4663  4663 D BluetoothMapService: Received stop request...Stopping profile...
11-21 16:03:59.545  4663  4663 D BluetoothMapService: stop()
11-21 16:03:59.545  4663  4663 D BluetoothMapAppObserver: deinitObservers()
11-21 16:03:59.545  4663  4663 D BluetoothMapAppObserver: removeReceiver()
11-21 16:03:59.547  4663  4663 D SapService: Received stop request...Stopping profile...
,11-21 16:03:59.547  4663  4663 V SapService: stop()
11-21 16:03:59.548  4663  4663 V BluetoothAdapterState: isTurningOff()=true
11-21 16:03:59.548  4663  4663 V BluetoothAdapterState: isTurningOn()=false
11-21 16:03:59.548  4663  4663 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:03:59.548  4663  4663 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:03:59.548  4663  4663 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-21 16:03:59.548  4663  4663 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-21 16:03:59.548  4663  4725 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-21 16:03:59.548  4663  4663 V BluetoothAdapterState: isTurningOff()=true
11-21 16:03:59.548  4663  4663 V BluetoothAdapterState: isTurningOn()=false
11-21 16:03:59.548  4663  4663 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:03:59.548  4663  4663 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:03:59.548  4663  4663 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-21 16:03:59.549  4663  4725 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-21 16:03:59.549  3144  3144 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-21 16:03:59.549  3144  3144 D PanProfile: Bluetooth service disconnected
11-21 16:03:59.549  3144  3144 D BluetoothMap: Proxy object disconnected
11-21 16:03:59.549  3144  3144 D MapProfile: Bluetooth service disconnected
11-21 16:03:59.549  4663  4663 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-21 16:03:59.550  4663  4663 V BluetoothAdapterState: isTurningOff()=true
11-21 16:03:59.550  4663  4663 V BluetoothAdapterState: isTurningOn()=false
11-21 16:03:59.550  4663  4663 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:03:59.550  4663  4663 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:03:59.550  4663  4663 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-21 16:03:59.550  4663  4663 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-21 16:03:59.551  4663  4663 D BluetoothMapService: MAP Service closeService in
11-21 16:03:59.551  4663  4663 V BluetoothAdapterState: isTurningOff()=true
11-21 16:03:59.551  4663  4663 V BluetoothAdapterState: isTurningOn()=false
11-21 16:03:59.551  4663  4663 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:03:59.551  4663  4663 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:03:59.552  4663  4663 D BluetoothMapService: cleanup()
11-21 16:03:59.552  4663  4663 D BluetoothMapService: MAP Service closeService in
11-21 16:03:59.552  4663  4663 V BluetoothAdapterState: isTurningOff()=true
11-21 16:03:59.552  4663  4663 V BluetoothAdapterState: isTurningOn()=false
11-21 16:03:59.552  4663  4663 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:03:59.552  4663  4663 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 16:03:59.554  4663  4721 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-21 16:03:59.554  4663  4721 D BluetoothAdapterProperties: Setting state to 15
11-21 16:03:59.554  4663  4721 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-21 16:03:59.554  4663  4721 I BluetoothAdapterState: Entering BleOnState
,11-21 16:03:59.558   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-21 16:03:59.558  3802  3978 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:03:59.559   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-21 16:03:59.559  3144  3156 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:03:59.559  3144  3380 D BluetoothPbap: onBluetoothStateChange: up=false
11-21 16:03:59.560  3144  3160 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-21 16:03:59.561   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:03:59.561  3144  3156 D BluetoothPan: onBluetoothStateChange on: false
11-21 16:03:59.561  3144  3380 D BluetoothMap: onBluetoothStateChange: up=false
11-21 16:03:59.562   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:03:59.562  3144  3160 D BluetoothA2dp: onBluetoothStateChange: up=false
11-21 16:03:59.563  4663  4721 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-21 16:03:59.563  4663  4721 D BluetoothAdapterProperties: Setting state to 16
11-21 16:03:59.563  4663  4721 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-21 16:03:59.563  4663  4721 D BluetoothAdapterProperties: onBleDisable
11-21 16:03:59.564  4663  4721 I BluetoothAdapterState: Entering PendingCommandState
11-21 16:03:59.564  4663  4722 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-21 16:03:59.565  4663  4853 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-21 16:03:59.565  4663  4853 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 16:03:59.566  4663  4725 D BluetoothAdapterProperties: Scan Mode:20
,11-21 16:03:59.580  5763  5763 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-21 16:03:59.593  5763  5763 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 16:03:59.597   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3828db3:true
,11-21 16:03:59.598  3595  3595 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 16:03:59.611   928  3152 I ActivityManager: Start proc 5775:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-21 16:03:59.624  5763  5763 D LocalBluetoothProfileManager: Adding local MAP profile
,11-21 16:03:59.626  5763  5763 D BluetoothMap: Create BluetoothMap proxy object
,11-21 16:03:59.639  5763  5763 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-21 16:03:59.646  5775  5775 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-21 16:03:59.657  5763  5763 D DockEventReceiver: finishStartingService: stopping service
,11-21 16:03:59.660   928  4935 I ActivityManager: Killing 5392:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-21 16:03:59.773  4663  4725 I bt_hci  : shut_down
,11-21 16:03:59.777  4663  4729 D bt_hwcfg: hw_epilog_process
,11-21 16:03:59.777  4663  4729 I bt_vendor: low_power_mode_cb
,11-21 16:03:59.780  4663  4729 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-21 16:03:59.780  4663  4729 I bt_vendor: epilog_cb
11-21 16:03:59.780  4663  4729 I bt_hci  : epilog_finished_callback
,11-21 16:03:59.782  4663  4725 I bt_hci_h4: hal_close
11-21 16:03:59.782  4663  4725 I bt_userial_vendor: device fd = 54 close
,11-21 16:03:59.861  5775  5775 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at java.io.File.exists(File.java:361)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-21 16:03:59.861  5775  5775 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:03:59.861  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:03:59.862  5775  5775 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:03:59.862  5775  5775 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.e.b(PG:170)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:03:59.862  5775  5775 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.k.d(PG:583)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.e.b(PG:170)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:03:59.862  5775  5775 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.io.File.exists(File.java:361)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:03:59.862  5775  5775 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.io.File.exists(File.java:361)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:03:59.862  5775  5775 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:03:59.862  5775  5775 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:03:59.867  5763  5763 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-21 16:03:59.873  3595  3595 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 16:03:59.875  5763  5763 D DockEventReceiver: finishStartingService: stopping service
11-21 16:03:59.878   928  3876 I ActivityManager: Killing 5404:com.android.chrome/u0a39 (adj 15): empty #17
,11-21 16:03:59.908  4663  4722 D bt_stack_manager: event_shut_down_stack finished.
11-21 16:03:59.908  4663  4721 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-21 16:03:59.909  4663  4663 D BtGatt.DebugUtils: handleDebugAction() action=null
11-21 16:03:59.909  4663  4721 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-21 16:03:59.910  4663  4663 D BtGatt.GattService: Received stop request...Stopping profile...
11-21 16:03:59.910  4663  4663 D BtGatt.GattService: stop()
11-21 16:03:59.910  4663  4663 D BtGatt.AdvertiseManager: advertise clients cleared
11-21 16:03:59.911  4663  4663 V BluetoothAdapterState: isTurningOff()=false
11-21 16:03:59.911  4663  4663 V BluetoothAdapterState: isTurningOn()=false
11-21 16:03:59.911  4663  4663 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:03:59.911  4663  4663 V BluetoothAdapterState: isBleTurningOff()=true
11-21 16:03:59.912  4663  4721 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-21 16:03:59.912  4663  4721 D BluetoothAdapterProperties: Setting state to 10
11-21 16:03:59.912  4663  4721 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-21 16:03:59.912  4663  4721 I BluetoothAdapterState: Entering OffState
11-21 16:03:59.913   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-21 16:03:59.918  4663  4663 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-21 16:03:59.918  4663  4663 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-21 16:03:59.918  4663  4663 I BluetoothServiceJni: cleanupNative: return from cleanup
11-21 16:03:59.919  4663  4722 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-21 16:03:59.923  4663  4663 I art     : System.exit called, status: 0
11-21 16:03:59.923  4663  4663 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-21 16:03:59.963  5690  5690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 16:03:59.993   928   939 I ActivityManager: Process com.android.bluetooth (pid 4663) has died
,11-21 16:04:00.000  5690  5761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-21 16:04:00.001  5690  5761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:04:00.001  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:04:00.001  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
11-21 16:04:00.001  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:04:00.001  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-21 16:04:00.001  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:04:00.001  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:04:00.001  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:04:00.001  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 16:04:00.001  5690  5761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-21 16:04:00.001  5690  5761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 16:04:00.003  5690  5736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 16:04:00.015   928   945 I ActivityManager: Start proc 5807:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-21 16:04:00.075  5807  5807 D AdapterServiceConfig: Adding HeadsetService
,11-21 16:04:00.075  5807  5807 D AdapterServiceConfig: Adding A2dpService
11-21 16:04:00.075  5807  5807 D AdapterServiceConfig: Adding HidService
11-21 16:04:00.075  5807  5807 D AdapterServiceConfig: Adding HealthService
11-21 16:04:00.076  5807  5807 D AdapterServiceConfig: Adding PanService
11-21 16:04:00.076  5807  5807 D AdapterServiceConfig: Adding GattService
11-21 16:04:00.076  5807  5807 D AdapterServiceConfig: Adding BluetoothMapService
,11-21 16:04:00.076  5807  5807 D AdapterServiceConfig: Adding SapService
,11-21 16:04:00.085   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e9ef7b8:true
,11-21 16:04:00.085  5807  5807 D BluetoothAdapterState: make() - Creating AdapterState
,11-21 16:04:00.087  5807  5807 I bt_bluedroid: init
,11-21 16:04:00.087  5807  5819 I BluetoothAdapterState: Entering OffState
,11-21 16:04:00.089  5807  5820 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-21 16:04:00.089  5807  5820 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-21 16:04:00.089  5807  5820 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-21 16:04:00.089  5807  5820 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-21 16:04:00.089  5807  5807 I bt_bluedroid: get_profile_interface socket
,11-21 16:04:00.091  5807  5823 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-21 16:04:00.091  5807  5807 I bt_bluedroid: get_profile_interface sdp
11-21 16:04:00.092  5807  5823 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-21 16:04:00.094  5807  5818 I bt_bluedroid: config_hci_snoop_log
,11-21 16:04:00.095   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-21 16:04:00.099  5807  5819 D BluetoothAdapterState: Current state: OFF, message: 0
,11-21 16:04:00.099  5807  5819 D BluetoothAdapterProperties: Setting state to 14
11-21 16:04:00.099  5807  5819 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-21 16:04:00.100  5807  5819 D BluetoothBondStateMachine: make
,11-21 16:04:00.102  5807  5824 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-21 16:04:00.104  5807  5819 I BluetoothAdapterState: Entering PendingCommandState
,11-21 16:04:00.105  5807  5807 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-21 16:04:00.106  5775  5798 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-21 16:04:00.107  5807  5807 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4969c19
11-21 16:04:00.107  5807  5807 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-21 16:04:00.108  5807  5807 D BtGatt.GattService: Received start request. Starting profile...
,11-21 16:04:00.108  5807  5807 D BtGatt.GattService: start()
11-21 16:04:00.108  5807  5807 I bt_bluedroid: get_profile_interface gatt
11-21 16:04:00.109  5807  5807 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4969c19
11-21 16:04:00.109  5807  5807 D BtGatt.AdvertiseManager: advertise manager created
,11-21 16:04:00.113  5807  5807 V BluetoothAdapterState: isTurningOff()=false
,11-21 16:04:00.113  5807  5807 V BluetoothAdapterState: isTurningOn()=false
11-21 16:04:00.113  5807  5807 V BluetoothAdapterState: isBleTurningOn()=true
11-21 16:04:00.113  5807  5807 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:04:00.113  5807  5819 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-21 16:04:00.114  5807  5819 I bt_bluedroid: bt_bluedroid
11-21 16:04:00.114  5807  5820 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-21 16:04:00.115  5807  5820 I bt_hci  : start_up
,11-21 16:04:00.118   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fa109c9:true
,11-21 16:04:00.119  5807  5820 I bt_vendor: alloc value 0xf42b1871
,11-21 16:04:00.119  5807  5820 I bt_vendor: init
11-21 16:04:00.119  5807  5820 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-21 16:04:00.120  5807  5820 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-21 16:04:00.228  5807  5820 D bt_hci  : start_up starting async portion
,11-21 16:04:00.228  5807  5828 I bt_hci  : event_finish_startup
11-21 16:04:00.228  5807  5828 I bt_hci_h4: hal_open
,11-21 16:04:00.227  5830  5830 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 16:04:00.228  5807  5828 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-21 16:04:00.231  5807  5828 I bt_userial_vendor: device fd = 54 open
,11-21 16:04:00.243  5807  5828 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-21 16:04:00.245  5807  5828 D bt_hwcfg: Chipset BCM4358A3
,11-21 16:04:00.245  5807  5828 D bt_hwcfg: Target name = [BCM4358A3]
11-21 16:04:00.245  5807  5828 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-21 16:04:00.510  5807  5819 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-21 16:04:00.644   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 16:04:00.652  5807  5828 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-21 16:04:00.652  5807  5828 D bt_hwcfg: Settlement delay -- 100 ms
11-21 16:04:00.652  5807  5828 I bt_hwcfg: Setting fw settlement delay to 100 
,11-21 16:04:00.776  5807  5828 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-21 16:04:00.776  5807  5828 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-21 16:04:00.778  5807  5828 I bt_hwcfg: vendor lib fwcfg completed
11-21 16:04:00.778  5807  5828 I bt_vendor: firmware callback
11-21 16:04:00.779  5807  5828 I bt_hci  : firmware_config_callback
,11-21 16:04:00.786  5807  5832 I bt_btu  : btu_task pending for preload complete event
,11-21 16:04:00.787  5807  5832 I bt_btu_task: Bluetooth chip preload is complete
,11-21 16:04:00.787  5807  5832 I bt_btu  : btu_task received preload complete event
,11-21 16:04:00.793  5807  5832 I         : BTE_InitTraceLevels -- TRC_HCI
,11-21 16:04:00.794  5807  5832 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-21 16:04:00.794  5807  5832 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-21 16:04:00.794  5807  5832 I         : BTE_InitTraceLevels -- TRC_AVDT
11-21 16:04:00.794  5807  5832 I         : BTE_InitTraceLevels -- TRC_AVRC
11-21 16:04:00.794  5807  5832 I         : BTE_InitTraceLevels -- TRC_A2D
,11-21 16:04:00.794  5807  5832 I         : BTE_InitTraceLevels -- TRC_BNEP
11-21 16:04:00.794  5807  5832 I         : BTE_InitTraceLevels -- TRC_BTM
11-21 16:04:00.795  5807  5832 I         : BTE_InitTraceLevels -- TRC_GAP
11-21 16:04:00.795  5807  5832 I         : BTE_InitTraceLevels -- TRC_PAN
,11-21 16:04:00.795  5807  5832 I         : BTE_InitTraceLevels -- TRC_SDP
11-21 16:04:00.795  5807  5832 I         : BTE_InitTraceLevels -- TRC_GATT
11-21 16:04:00.795  5807  5832 I         : BTE_InitTraceLevels -- TRC_SMP
11-21 16:04:00.795  5807  5832 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-21 16:04:00.795  5807  5832 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-21 16:04:00.875  5807  5832 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf422f549
,11-21 16:04:00.875  5807  5832 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf422f549 
,11-21 16:04:00.888  5807  5823 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-21 16:04:00.889  5807  5823 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-21 16:04:00.890  5807  5823 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-21 16:04:00.892  5807  5823 D BluetoothAdapterProperties: Name is: Nexus 6P
11-21 16:04:00.894  5807  5823 D BluetoothAdapterProperties: Scan Mode:20
11-21 16:04:00.894  5807  5823 D BluetoothAdapterProperties: Discoverable Timeout:120
11-21 16:04:00.895  5807  5823 D bt_hci  : do_postload posting postload work item
,11-21 16:04:00.895  5807  5828 I bt_hci  : event_postload
11-21 16:04:00.895  5807  5828 I bt_vendor: sco_config_cb
,11-21 16:04:00.895  5807  5828 I bt_hci  : sco_config_callback postload finished.
11-21 16:04:00.897  5807  5823 D bt_bte_conf: Device ID record 1 : primary
11-21 16:04:00.897  5807  5823 D bt_bte_conf:   vendorId            = 000f
11-21 16:04:00.897  5807  5823 D bt_bte_conf:   vendorIdSource      = 0001
11-21 16:04:00.897  5807  5823 D bt_bte_conf:   product             = 1200
11-21 16:04:00.897  5807  5823 D bt_bte_conf:   version             = 1436
,11-21 16:04:00.898  5807  5823 D bt_bte_conf:   clientExecutableURL = 
11-21 16:04:00.898  5807  5823 D bt_bte_conf:   serviceDescription  = 
11-21 16:04:00.898  5807  5823 D bt_bte_conf:   documentationURL    = 
11-21 16:04:00.898  5807  5823 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-21 16:04:00.898  5807  5820 D bt_stack_manager: event_start_up_stack finished
11-21 16:04:00.899  5807  5819 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-21 16:04:00.900  5807  5819 D BluetoothAdapterProperties: Setting state to 15
11-21 16:04:00.900  5807  5819 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-21 16:04:00.901  5807  5819 I BluetoothAdapterState: Entering BleOnState
,11-21 16:04:00.906  5807  5828 I bt_vendor: low_power_mode_cb
,11-21 16:04:00.907  5807  5819 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-21 16:04:00.908  5807  5819 D BluetoothAdapterProperties: Setting state to 11
11-21 16:04:00.908  5807  5819 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-21 16:04:00.917  5807  5807 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4969c19
11-21 16:04:00.917  5807  5807 D HeadsetService: Received start request. Starting profile...
,11-21 16:04:00.920  5807  5807 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-21 16:04:00.921  5807  5807 D HeadsetStateMachine: make
,11-21 16:04:00.930  5807  5807 D HeadsetStateMachine: max_hf_connections = 1
,11-21 16:04:00.930  5807  5807 I bt_bluedroid: get_profile_interface handsfree
11-21 16:04:00.931  5807  5823 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-21 16:04:00.931  5807  5823 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-21 16:04:00.933  5807  5819 I BluetoothAdapterState: Entering PendingCommandState
,11-21 16:04:00.935  5807  5807 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4969c19
,11-21 16:04:00.935  5807  5807 D A2dpService: Received start request. Starting profile...
,11-21 16:04:00.936  5807  5807 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-21 16:04:00.937  5807  5807 I bt_bluedroid: get_profile_interface avrcp
11-21 16:04:00.937  3595  3595 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 16:04:00.942  5807  5807 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-21 16:04:00.942  5807  5807 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-21 16:04:00.943  5807  5807 D A2dpStateMachine: make
,11-21 16:04:00.944  5807  5807 I bt_bluedroid: get_profile_interface a2dp
,11-21 16:04:00.945  5807  5823 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-21 16:04:00.946  5807  5841 D A2dpStateMachine: Enter Disconnected: -2
,11-21 16:04:00.946  5807  5807 I BluetoothHidServiceJni: classInitNative: succeeds
,11-21 16:04:00.947  5807  5807 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4969c19
,11-21 16:04:00.948  5807  5807 D HidService: Received start request. Starting profile...
,11-21 16:04:00.948  5807  5807 I bt_bluedroid: get_profile_interface hidhost
11-21 16:04:00.948  5807  5823 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf421056d
11-21 16:04:00.948  5807  5807 D HidService: setHidService(): set to: null
11-21 16:04:00.949  5807  5823 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-21 16:04:00.949  5807  5807 I BluetoothHealthServiceJni: classInitNative: succeeds
11-21 16:04:00.950  5807  5807 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4969c19
11-21 16:04:00.950  5807  5807 D HealthService: Received start request. Starting profile...
,11-21 16:04:00.952  5807  5807 I bt_bluedroid: get_profile_interface health
,11-21 16:04:00.952  5763  5763 D BluetoothInputDevice: Proxy object connected
,11-21 16:04:00.952  5763  5763 D HidProfile: Bluetooth service connected
11-21 16:04:00.952  5807  5807 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-21 16:04:00.953  5807  5807 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4969c19
11-21 16:04:00.954  5807  5807 D PanService: Received start request. Starting profile...
11-21 16:04:00.954  5763  5763 D BluetoothPan: BluetoothPAN Proxy object connected
11-21 16:04:00.954  5807  5807 D BluetoothPanServiceJni: initializeNative(L110): pan
11-21 16:04:00.954  5807  5807 I bt_bluedroid: get_profile_interface pan
11-21 16:04:00.955  5763  5763 D PanProfile: Bluetooth service connected
11-21 16:04:00.955  5807  5823 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-21 16:04:00.958  5807  5807 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4969c19
,11-21 16:04:00.960  5807  5807 D BluetoothMapService: Received start request. Starting profile...
,11-21 16:04:00.960  5807  5807 D BluetoothMapService: start()
11-21 16:04:00.962  5807  5807 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-21 16:04:00.963  5807  5807 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-21 16:04:00.963  5807  5807 D BluetoothMapAppObserver: createReceiver()
11-21 16:04:00.965  5807  5807 D BluetoothMapAppObserver: initObservers()
11-21 16:04:00.965  5807  5807 D BluetoothMapAppObserver: getEnabledAccountItems()
11-21 16:04:00.970  5807  5807 V SapService: SapBinder()
11-21 16:04:00.970  5807  5807 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4969c19
11-21 16:04:00.971  5763  5763 D BluetoothMap: Proxy object connected
11-21 16:04:00.971  5763  5763 D MapProfile: Bluetooth service connected
11-21 16:04:00.971  5763  5763 D BluetoothMap: getConnectedDevices()
11-21 16:04:00.972  5807  5807 D SapService: Received start request. Starting profile...
11-21 16:04:00.972  5807  5807 V SapService: start()
11-21 16:04:00.973  5763  5763 D BluetoothMap: Bluetooth is Not enabled
11-21 16:04:00.973  5807  5807 V BluetoothAdapterState: isTurningOff()=false
11-21 16:04:00.973  5807  5807 V BluetoothAdapterState: isTurningOn()=true
11-21 16:04:00.973  5807  5807 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:04:00.973  5807  5807 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:04:00.973  5807  5839 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-21 16:04:00.974  5807  5807 V BluetoothAdapterState: isTurningOff()=false
11-21 16:04:00.974  5807  5807 V BluetoothAdapterState: isTurningOn()=true
11-21 16:04:00.974  5807  5807 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:04:00.974  5807  5807 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:04:00.974  5807  5807 V BluetoothAdapterState: isTurningOff()=false
11-21 16:04:00.974  5807  5807 V BluetoothAdapterState: isTurningOn()=true
11-21 16:04:00.974  5807  5807 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:04:00.974  5807  5807 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:04:00.974  5807  5807 V BluetoothAdapterState: isTurningOff()=false
11-21 16:04:00.974  5807  5807 V BluetoothAdapterState: isTurningOn()=true
11-21 16:04:00.974  5807  5807 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:04:00.975  5807  5807 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:04:00.975  5807  5807 V BluetoothAdapterState: isTurningOff()=false
11-21 16:04:00.975  5807  5807 V BluetoothAdapterState: isTurningOn()=true
11-21 16:04:00.975  5807  5807 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:04:00.975  5807  5807 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:04:00.975  5807  5807 V BluetoothAdapterState: isTurningOff()=false
11-21 16:04:00.975  5807  5807 V BluetoothAdapterState: isTurningOn()=true
11-21 16:04:00.975  5807  5807 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:04:00.975  5807  5807 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:04:00.976  5807  5807 V BluetoothAdapterState: isTurningOff()=false
11-21 16:04:00.976  5807  5807 V BluetoothAdapterState: isTurningOn()=true
11-21 16:04:00.976  5807  5807 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:04:00.976  5807  5807 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:04:00.976  5807  5819 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-21 16:04:00.976  5807  5819 D BluetoothAdapterProperties: ScanMode =  20
11-21 16:04:00.976  5807  5819 D BluetoothAdapterProperties: State =  11
11-21 16:04:00.977  5807  5819 D BluetoothAdapterProperties: Setting state to 12
11-21 16:04:00.977  5807  5819 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-21 16:04:00.977   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-21 16:04:00.977  5807  5819 I BluetoothAdapterState: Entering OnState
11-21 16:04:00.977  5807  5823 D BluetoothAdapterProperties: Scan Mode:21
11-21 16:04:00.977  3802  3830 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 16:04:00.977  5807  5823 D BluetoothAdapterProperties: Discoverable Timeout:120
11-21 16:04:00.979  5763  5773 D BluetoothMap: onBluetoothStateChange: up=true
,11-21 16:04:00.980  5763  5774 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-21 16:04:00.980   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-21 16:04:00.981  3144  3160 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 16:04:00.982   928   928 D BluetoothA2dp: Proxy object connected
11-21 16:04:00.982  3144  3156 D BluetoothPbap: onBluetoothStateChange: up=true
11-21 16:04:00.983  3144  3380 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-21 16:04:00.986  3144  3144 D BluetoothInputDevice: Proxy object connected
11-21 16:04:00.986  3144  3144 D HidProfile: Bluetooth service connected
11-21 16:04:00.986   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 16:04:00.986  5763  5773 D BluetoothPan: onBluetoothStateChange on: true
11-21 16:04:00.986  3144  3156 D BluetoothPan: onBluetoothStateChange on: true
11-21 16:04:00.988  3144  3144 D BluetoothPan: BluetoothPAN Proxy object connected
11-21 16:04:00.988  3144  3144 D PanProfile: Bluetooth service connected
11-21 16:04:00.988  5763  5774 D BluetoothPbap: onBluetoothStateChange: up=true
11-21 16:04:00.990  5807  5807 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-21 16:04:00.990  3144  3380 D BluetoothMap: onBluetoothStateChange: up=true
11-21 16:04:00.990  5807  5807 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-21 16:04:00.991  3144  3144 D BluetoothMap: Proxy object connected
11-21 16:04:00.991  3144  3144 D MapProfile: Bluetooth service connected
11-21 16:04:00.991  3144  3144 D BluetoothMap: getConnectedDevices()
11-21 16:04:00.992  5807  5807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:04:00.992   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 16:04:00.992  3144  3160 D BluetoothA2dp: onBluetoothStateChange: up=true
11-21 16:04:00.993  5807  5807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:04:00.994  3144  3144 D BluetoothA2dp: Proxy object connected
11-21 16:04:00.995   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-21 16:04:00.997  5807  5807 D ObexServerSockets: Succeed to create listening sockets 
11-21 16:04:00.997  5807  5807 D ObexServerSockets0: startAccept()
11-21 16:04:00.997  5807  5807 D ObexServerSockets0: prepareForNewConnect()
11-21 16:04:00.998  5763  5763 D LocalBluetoothProfileManager: Adding local A2DP profile
11-21 16:04:00.999  5807  5807 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-21 16:04:00.999  5807  5807 D BluetoothSdpJni: SDP Create record success - handle: 0
11-21 16:04:01.000  5807  5847 D ObexServerSockets0: Accepting socket connection...
11-21 16:04:01.000  5807  5848 D ObexServerSockets0: Accepting socket connection...
11-21 16:04:01.000  5807  5807 D BluetoothMapService: onReceive
11-21 16:04:01.000  5807  5807 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 16:04:01.000  5807  5807 D BluetoothMapService: STATE_ON
11-21 16:04:01.002  5807  5849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:04:01.002  5763  5763 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-21 16:04:01.003  5807  5849 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-21 16:04:01.003  5807  5849 D BluetoothSdpJni: SDP Create record success - handle: 1
11-21 16:04:01.012  5763  5763 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-21 16:04:01.013  5763  5763 D BluetoothA2dp: Proxy object connected
,11-21 16:04:01.016  5690  5761 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-21 16:04:01.016  5690  5761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:04:01.016  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:04:01.016  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:04:01.016  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:04:01.016  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:04:01.016  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:04:01.016  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:04:01.016  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:04:01.016  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 16:04:01.018  5690  5761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 16:04:01.018  3595  3595 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 16:04:01.019  5690  5736 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-21 16:04:01.020   928  3876 D WifiService: setWifiEnabled: false pid=5690, uid=10077
11-21 16:04:01.020   928  3876 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 16:04:01.021  5690  5736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 16:04:01.025   928  2987 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-21 16:04:01.025   928  2987 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-21 16:04:01.026   928  2987 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-21 16:04:01.026   928  2987 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-21 16:04:01.027  5807  5807 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-21 16:04:01.027  5807  5807 D ObexServerSockets0: prepareForNewConnect()
11-21 16:04:01.031  5763  5763 D DockEventReceiver: finishStartingService: stopping service
,11-21 16:04:01.032  5763  5763 D BluetoothPbap: Proxy object connected
11-21 16:04:01.034  3144  3144 D BluetoothPbap: Proxy object connected
11-21 16:04:01.034  3144  3144 D PbapServerProfile: Bluetooth service connected
11-21 16:04:01.034  5763  5763 D PbapServerProfile: Bluetooth service connected
,11-21 16:04:01.037   928  5366 D DhcpClient: Clearing IP address
,11-21 16:04:01.038  5807  5854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:04:01.038   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-21 16:04:01.045   509   923 D CommandListener: Setting iface cfg
,11-21 16:04:01.047  3595  5419 V NativeCrypto: Read error: ssl=0x7f7c2c9380: I/O error during system call, Connection timed out
11-21 16:04:01.048  3595  5419 V NativeCrypto: SSL shutdown failed: ssl=0x7f7c2c9380: I/O error during system call, Broken pipe
11-21 16:04:01.049   928  5367 D DhcpClient: Receive thread stopped
11-21 16:04:01.051   928  3428 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-21 16:04:01.051   928  5364 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-21 16:04:01.056   928  5364 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-21 16:04:01.057   928  2989 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-21 16:04:01.057   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-21 16:04:01.058   928  2989 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-21 16:04:01.060   928  2989 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-21 16:04:01.060   928  2989 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-21 16:04:01.062   542   542 E Parcel  : Reading a NULL string not supported here.
,11-21 16:04:01.064   928   928 D RttService: SCAN_AVAILABLE : 1
11-21 16:04:01.064   928  3097 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-21 16:04:01.068  5807  5860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:04:01.068   928  2989 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-21 16:04:01.071  3769  3887 W QCNEJ   : |CORE| network lost: 100
,11-21 16:04:01.071  5807  5860 I BtOppRfcommListener: Accept thread started.
11-21 16:04:01.071  3769  3887 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-21 16:04:01.078  3144  3380 D BluetoothHeadset: Proxy object connected
,11-21 16:04:01.079  3802  4024 D BluetoothHeadset: Proxy object connected
11-21 16:04:01.079  3802  3835 D BluetoothHeadset: Proxy object connected
11-21 16:04:01.079   928   928 D BluetoothHeadset: Proxy object connected
11-21 16:04:01.079   928   928 D BluetoothHeadset: Proxy object connected
,11-21 16:04:01.079   928   928 D BluetoothHeadset: Proxy object connected
11-21 16:04:01.080   928  2987 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-21 16:04:01.082  3144  3156 D BluetoothHeadset: Proxy object connected
11-21 16:04:01.083  3144  3144 D HeadsetProfile: Bluetooth service connected
,11-21 16:04:01.086   928   945 D BluetoothHeadset: Proxy object connected
,11-21 16:04:01.091   928  2987 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-21 16:04:01.092   928   945 D BluetoothHeadset: Proxy object connected
,11-21 16:04:01.099  3144  3144 D HeadsetProfile: Bluetooth service connected
,11-21 16:04:01.104   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 16:04:01.108  5763  5774 D BluetoothHeadset: Proxy object connected
,11-21 16:04:01.108  5763  5763 D HeadsetProfile: Bluetooth service connected
,11-21 16:04:01.125   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 16:04:01.125   509   923 D CommandListener: Clearing all IP addresses on wlan0
11-21 16:04:01.125   509   923 D TetherController: Setting IP forward enable = 0
11-21 16:04:01.127   928  2989 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-21 16:04:01.127   928  2989 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-21 16:04:01.130   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-21 16:04:01.131   928  2987 D DhcpClient: doQuit
11-21 16:04:01.131   928  2987 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-21 16:04:01.132   928  5366 D DhcpClient: onQuitting
11-21 16:04:01.132  5264  5264 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7f9d801 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-21 16:04:01.133  3488  3488 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-21 16:04:01.142  3950  3950 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-21 16:04:01.147  3979  3979 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-21 16:04:01.147  3488  3488 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-21 16:04:01.148  5037  5057 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-21 16:04:01.148  5037  5057 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 16:04:01.149  5037  5057 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-21 16:04:01.149  5037  5057 E SarControlService: no key has been found,reset the power
11-21 16:04:01.149  5037  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-21 16:04:01.149  5037  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 16:04:01.149  5037  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-21 16:04:01.150  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-21 16:04:01.150  5062  5062 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-21 16:04:01.151  3488  3488 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-21 16:04:01.152  5037  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-21 16:04:01.152  5037  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-21 16:04:01.152  5037  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 16:04:01.154  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 16:04:01.154  5062  5062 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-21 16:04:01.158  5062  5076 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9bbf72f HexData = [00000000ea03000000000000ffffffff]
11-21 16:04:01.158  5062  5076 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-21 16:04:01.158  5062  5076 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-21 16:04:01.160  3979  3979 D SystemUpdateService: onCreate
11-21 16:04:01.160  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 16:04:01.162  5037  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-21 16:04:01.165  3488  3488 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-21 16:04:01.165  3979  3979 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-21 16:04:01.166  5062  5076 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9bbf72f HexData = [00000000eb03000000000000ffffffff]
11-21 16:04:01.167  5062  5076 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 16:04:01.167  5062  5076 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-21 16:04:01.168  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 16:04:01.168  5037  5048 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-21 16:04:01.176  3979  3979 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-21 16:04:01.177   509   923 E Netd    : netlink response contains error (No such file or directory)
11-21 16:04:01.178   509   923 D TetherController: Setting IP forward enable = 0
11-21 16:04:01.178   928  2989 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-21 16:04:01.178   928  2989 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-21 16:04:01.181  3979  5879 I SystemUpdateService: active receiver: enabled
,11-21 16:04:01.182  3979  5390 I iu.UploadsManager: num queued entries: 0
,11-21 16:04:01.184  3979  3979 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-21 16:04:01.185  3979  3979 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-21 16:04:01.186  3488  3488 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-21 16:04:01.188  3979  5390 I iu.UploadsManager: num updated entries: 0
,11-21 16:04:01.189  3979  5390 I iu.SyncManager: NEXT; no task
11-21 16:04:01.191  3979  5879 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-21 16:04:01.192  3979  5879 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-21 16:04:01.192  3979  5879 I SystemUpdateService: now status is 0 (complete)
11-21 16:04:01.192  3979  5879 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 16:04:01.192  3979  5879 I SystemUpdateService: file has been verified
11-21 16:04:01.193  3979  5879 I SystemUpdateService: OTA package size = 21989297
11-21 16:04:01.198   928  3152 I ActivityManager: Start proc 5883:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-21 16:04:01.203  3979  5879 I SystemUpdateService: showing system update notification
,11-21 16:04:01.212   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 16:04:01.213  3979  3979 D SystemUpdateService: onDestroy
,11-21 16:04:01.232  5883  5883 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-21 16:04:01.234  5883  5883 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-21 16:04:01.241  5883  5883 D SprintDMHelper: simOperator: 
,11-21 16:04:01.241  5883  5883 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 16:04:01.253   928   938 I ActivityManager: Start proc 5895:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-21 16:04:01.254   928   938 I ActivityManager: Killing 5423:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-21 16:04:01.289   928  2987 D wifi    : In wifi stop Hal
,11-21 16:04:01.289  5012  5012 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-21 16:04:01.289   928  2987 D wifi    : halHandle = 0x7f69acd180, mVM = 0x7f8614d140, mCls = 0x100a02
11-21 16:04:01.289   928  3487 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-21 16:04:01.290   928  3487 D WifiHAL : Got a signal to exit!!!
11-21 16:04:01.290   928  3487 I WifiHAL : Exit wifi_event_loop
11-21 16:04:01.290   928  2987 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-21 16:04:01.290   928  2987 E WifiHAL : Event processing terminated
,11-21 16:04:01.290   928  2987 D wifi    : In wifi cleaned up handler
11-21 16:04:01.290   928  2987 I WifiHAL : Internal cleanup completed
11-21 16:04:01.291  4138  4238 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 16:04:01.312   928  3487 D wifi    : set interface wlan0 flags (DOWN)
,11-21 16:04:01.312   928  2987 D WifiNative-HAL: HAL event thread stopped successfully
,11-21 16:04:01.339  5012  5909 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-21 16:04:01.348   928  4935 I ActivityManager: Start proc 5910:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-21 16:04:01.350   928  3428 I ActivityManager: Killing 5264:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-21 16:04:01.396  5910  5910 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-21 16:04:01.515   928   945 D Tethering: InitialState.processMessage what=4
,11-21 16:04:01.520   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-21 16:04:01.530  5690  5761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:04:01.530  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:04:01.530  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:04:01.530  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-21 16:04:01.530  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:04:01.530  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 16:04:01.530  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 16:04:01.530  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 16:04:01.530  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 16:04:01.535  5690  5761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 16:04:01.536   928   938 D WifiService: setWifiEnabled: true pid=5690, uid=10077
,11-21 16:04:01.536   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 16:04:01.537  5690  5736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 16:04:01.539   509   923 D SoftapController: Softap fwReload - Ok
,11-21 16:04:01.541   509   923 D CommandListener: Setting iface cfg
,11-21 16:04:01.541   509   923 D CommandListener: Trying to bring down wlan0
11-21 16:04:01.542   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-21 16:04:01.545   928  2987 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-21 16:04:01.575   928  3611 I ActivityManager: Killing 3890:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-21 16:04:01.606   928  3428 I ActivityManager: Start proc 5924:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-21 16:04:01.638  5924  5924 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-21 16:04:01.645   928  3569 I ActivityManager: Killing 5470:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-21 16:04:02.039   928   939 D WifiService: setWifiEnabled: true pid=5690, uid=10077
,11-21 16:04:02.043   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:04:02.148   928  2987 D wifi    : set interface wlan0 flags (UP)
,11-21 16:04:02.148   928  2987 I WifiHAL : Initializing wifi
,11-21 16:04:02.148   928  2987 I WifiHAL : Creating socket
11-21 16:04:02.155   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-21 16:04:02.158   928  2987 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-21 16:04:02.158   928  2987 D wifi    : Did set static halHandle = 0x7f69acd180
,11-21 16:04:02.158   928  2987 D wifi    : halHandle = 0x7f69acd180, mVM = 0x7f8614d140, mCls = 0x2013e2
,11-21 16:04:02.158   928  2987 D wifi    : array field set
,11-21 16:04:02.159   928  2987 I WifiNative-HAL: interface[0] = wlan0
,11-21 16:04:02.165   928  5942 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547233780096
11-21 16:04:02.167   928  5942 D wifi    : waitForHalEvents called, vm = 0x7f8614d140, obj = 0x2013e2, env = 0x7f69e83140
11-21 16:04:02.167   928  2987 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-21 16:04:02.170   928  2987 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-21 16:04:02.233  5943  5943 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-21 16:04:02.297  5943  5943 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-21 16:04:02.318  5943  5943 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-21 16:04:02.318  5943  5943 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-21 16:04:02.547   928  5922 D WifiService: setWifiEnabled: true pid=5690, uid=10077
,11-21 16:04:02.547   928  5922 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:04:03.052   928  3875 D WifiService: setWifiEnabled: true pid=5690, uid=10077
,11-21 16:04:03.053   928  3875 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:04:03.184   928  2987 D WifiConfigStore: Loading config and enabling all networks 
,11-21 16:04:03.217   928  2987 D WifiConfigStore: loaded 0 passpoint configs
,11-21 16:04:03.218   928  2987 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-21 16:04:03.218   928  2987 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-21 16:04:03.219   928  2987 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-21 16:04:03.220   928  2987 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-21 16:04:03.220   928  2987 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-21 16:04:03.221   928  2987 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-21 16:04:03.222   928  2987 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-21 16:04:03.222   928  2987 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-21 16:04:03.222   928  2987 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-21 16:04:03.222   928  2987 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-21 16:04:03.222   928  2987 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-21 16:04:03.222   928  2987 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-21 16:04:03.226   928  2987 D WifiNative-HAL: Setting external_sim to 1
,11-21 16:04:03.226   928  2987 D wifi    : setting dfs flag to true, 0x7f6d53fea0
11-21 16:04:03.227   928  2987 D WifiStateMachine: Setting OUI to DA-A1-19
11-21 16:04:03.227   928  2987 D wifi    : setting scan oui 0x7f6d53fea0
11-21 16:04:03.227   928  2987 D WifiHAL : Sending mac address OUI
,11-21 16:04:03.229  5012  5012 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 16:04:03.232   928  2987 E native  : do suspend false
,11-21 16:04:03.239   928  2987 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-21 16:04:03.239   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-21 16:04:03.240   928   928 D RttService: SCAN_AVAILABLE : 3
11-21 16:04:03.240   928  3097 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-21 16:04:03.241   509   923 D CommandListener: Setting iface cfg
,11-21 16:04:03.245   928  2986 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
11-21 16:04:03.245   928  2986 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-21 16:04:03.253   928  2986 D WifiNative-HAL: p2pGetDeviceAddress
11-21 16:04:03.254   928  2986 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-21 16:04:03.259   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=198799 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-21 16:04:03.564  5690  5761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:04:03.564  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:04:03.564  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:04:03.564  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:04:03.564  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:04:03.564  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 16:04:03.564  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 16:04:03.564  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 16:04:03.564  5690  5761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 16:04:03.571  5690  5761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 16:04:03.574  5690  5736 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 16:04:03.575   928  3875 D WifiService: setWifiEnabled: true pid=5690, uid=10077
11-21 16:04:03.575   928  3875 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 16:04:03.576  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 16:04:03.576  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:04:03.576  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 16:04:03.576  5690  5736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e66b6b removed from the list
11-21 16:04:03.577  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-21 16:04:03.577  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9886c8 removed from the list
11-21 16:04:03.577  5690  5736 D io.jxcore.node.ConnectivityMonitor: stop
,11-21 16:04:03.581  5690  5736 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-21 16:04:03.582  5690  5736 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-21 16:04:03.582  5690  5736 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-21 16:04:03.585  5690  5736 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-21 16:04:03.587  5690  5736 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
11-21 16:04:03.588  5690  5736 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-21 16:04:03.589  5690  5736 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-21 16:04:03.589  5690  5736 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-21 16:04:03.589  5690  5736 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
11-21 16:04:03.591  5690  5736 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-21 16:04:03.592  5690  5736 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@857e18c Bundle[{}]
11-21 16:04:03.592  5690  5736 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-21 16:04:03.592  5690  5736 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-21 16:04:03.592  5690  5736 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-21 16:04:03.595  5690  5736 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-21 16:04:03.595  5690  5736 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-21 16:04:03.596  5690  5736 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,11-21 16:04:03.596  5690  5736 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-21 16:04:03.598  5690  5736 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-21 16:04:03.598  5690  5736 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-21 16:04:03.598  5690  5736 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-21 16:04:03.599  5690  5736 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-21 16:04:03.601  5690  5736 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-21 16:04:03.603  5690  5736 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-21 16:04:03.605  5690  5736 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-21 16:04:03.605  5690  5736 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-21 16:04:03.606  5690  5736 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-21 16:04:03.606  5690  5736 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-21 16:04:03.607  5690  5736 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
11-21 16:04:03.608  5690  5736 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-21 16:04:03.609  5690  5736 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-21 16:04:03.611  5690  5736 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-21 16:04:03.613  5690  5736 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-21 16:04:03.614  5690  5736 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-21 16:04:03.614  5690  5736 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
11-21 16:04:03.615  5690  5736 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-21 16:04:03.615  5690  5736 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-21 16:04:03.615  5690  5736 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
,11-21 16:04:03.616  5690  5736 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-21 16:04:03.617  5690  5736 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-21 16:04:03.618  5690  5736 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-21 16:04:03.618  5690  5736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 16:04:03.618  5690  5736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10fae86 added. We now have 3 listener(s)
11-21 16:04:03.620  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:04:03.620  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 16:04:03.620  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 16:04:03.620  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-21 16:04:03.620  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7e5347 added. We now have 3 listener(s)
11-21 16:04:03.620  5690  5736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 16:04:03.621  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 16:04:03.625  5690  5736 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-21 16:04:03.625  5690  5736 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-21 16:04:03.625  5690  5736 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-21 16:04:03.625  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-21 16:04:03.626  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.626  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.626  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:03.626  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:04:03.626  5690  5736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 16:04:03.626  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:04:03.626  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:04:03.626  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 16:04:03.628  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 16:04:03.629  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:04:03.629  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:04:03.629  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 16:04:03.629  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:04:03.629  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-21 16:04:03.629  5690  5946 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:04:03.629  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:04:03.629  5690  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:04:03.629  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 16:04:03.630  5690  5946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:04:03.627  5817  5817 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33271]" dev="sockfs" ino=33271 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0,
11-21 16:04:03.633  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:04:03.633  5690  5946 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 16:04:03.633  5690  5736 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:04:03.633  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 16:04:03.627  5817  5817 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33271]" dev="sockfs" ino=33271 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:04:03.637  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:03.637  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:04:03.638  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:04:03.638  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:04:03.638  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-21 16:04:03.641  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:03.641  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.641  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:04:03.641  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:04:03.641  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:04:03.641  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
,11-21 16:04:03.641  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:04:03.642  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:04:03.642  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.642  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:04:03.642  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 16:04:03.642  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.642  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.642  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:03.643  5690  5736 D BluetoothAdapter: STATE_ON
,11-21 16:04:03.647  5807  5846 D BtGatt.GattService: registerClient() - UUID=498f36d7-3342-4440-9ebe-3217c49bf212
,11-21 16:04:03.647  5807  5823 D BtGatt.GattService: onClientRegistered() - UUID=498f36d7-3342-4440-9ebe-3217c49bf212, clientIf=5
,11-21 16:04:03.648  5690  5701 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 16:04:03.650  5807  5825 D BtGatt.AdvertiseManager: message : 0
,11-21 16:04:03.652  5807  5825 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:04:03.660  5807  5823 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:04:03.665  5807  5823 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:04:03.666  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:03.666  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.666  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:04:03.666  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.666  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.666  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.666  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.666  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.666  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 16:04:03.667  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-21 16:04:03.667  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:03.668  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.668  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.668  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:03.669  5690  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:04:03.669  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:04:03.669  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:04:03.669  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:04:03.669  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:04:03.669  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-21 16:04:03.669  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-21 16:04:03.670  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:04:03.670  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:04:03.670  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:04:03.670  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:04:03.670  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:04:03.670  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 16:04:03.670  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:04:03.672  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:04:03.672  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:04:03.672  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:04:03.672  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:04:03.672  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:04:03.672  5690  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:04:04.173  5690  5690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-21 16:04:04.174  5690  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 16:04:04.174  5690  5690 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 16:04:06.306  5943  5943 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 16:04:06.307  5943  5943 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-21 16:04:06.308  5943  5943 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 16:04:06.333   928  2987 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-21 16:04:06.334   928  2987 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 11, 12 -> obsolete
11-21 16:04:06.334   928  2987 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-21 16:04:06.334   928  2987 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 16:04:06.343   928  2987 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-21 16:04:06.376   928  2987 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-21 16:04:06.381  5943  5943 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-21 16:04:06.805  5943  5943 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-21 16:04:06.842  5943  5943 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
11-21 16:04:06.843  5943  5943 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-21 16:04:06.852   928  2987 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-21 16:04:06.853   928  2987 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-21 16:04:06.853   928  2989 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-21 16:04:06.872   928  2987 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 16:04:06.884   509   923 D CommandListener: Setting iface cfg
,11-21 16:04:06.890   928  2987 D WifiStateMachine: Start Dhcp Watchdog 2
,11-21 16:04:06.898   928  5951 D DhcpClient: Receive thread started
,11-21 16:04:06.901   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:04:06.902   928  2987 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-21 16:04:06.902   928  2989 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-21 16:04:06.984   928  2987 E native  : do suspend false
,11-21 16:04:06.995   928  5950 D DhcpClient: Broadcasting DHCPDISCOVER
,11-21 16:04:07.015   928  5951 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172639, domain null
,11-21 16:04:07.017   928  5950 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172639 seconds
,11-21 16:04:07.020   928  5950 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-21 16:04:07.034   928  5951 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-21 16:04:07.034   928  5950 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-21 16:04:07.039   509   923 D CommandListener: Setting iface cfg
,11-21 16:04:07.044   928  2987 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-21 16:04:07.050   928  5950 D DhcpClient: Scheduling renewal in 86399s
,11-21 16:04:07.058   928  2987 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-21 16:04:07.059   928  2987 D WifiConfigStore: No blacklist allowed without epno enabled
,11-21 16:04:07.060   928  2989 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-21 16:04:07.067   928  2989 D ConnectivityService: Adding iface wlan0 to network 101
,11-21 16:04:07.068   928  2987 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-21 16:04:07.110   928  2989 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-21 16:04:07.110   928  2989 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-21 16:04:07.112   928  2989 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-21 16:04:07.113   928  2989 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-21 16:04:07.115   928  2989 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-21 16:04:07.122   928  2989 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:04:07.127   928  2989 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-21 16:04:07.127   928  2989 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-21 16:04:07.127   928  2989 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-21 16:04:07.127   928  2989 D ConnectivityService:    accepting network in place of null
11-21 16:04:07.128   928  2987 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-21 16:04:07.128   928  2989 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -56]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-21 16:04:07.128   928  2987 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-21 16:04:07.150   928  5949 D NetlinkSocketObserver: NeighborEvent{elapsedMs=202690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:04:07.154   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 16:04:07.170  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-21 16:04:07.171  5690  5736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 16:04:07.171  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:04:07.171  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:04:07.171  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:04:07.171  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:04:07.171  5690  5946 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:04:07.171  5690  5946 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:04:07.171  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 16:04:07.171  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-21 16:04:07.171  5690  5946 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:04:07.171  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 16:04:07.171  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:04:07.171  5690  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:04:07.171  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:04:07.171  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:04:07.171  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.171  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.171  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:07.171  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.172  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:04:07.172  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:04:07.173  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:04:07.173  5690  5736 D BluetoothLeScanner: could not find callback wrapper
11-21 16:04:07.173  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:04:07.173  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.173  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.173  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.173  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:04:07.173  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.174   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-21 16:04:07.174  5807  5825 D BtGatt.AdvertiseManager: message : 1
11-21 16:04:07.175  5807  5825 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:04:07.180   928  2989 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-21 16:04:07.180   928  2989 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-21 16:04:07.180  3769  3887 W QCNEJ   : |CORE| network available: 101
11-21 16:04:07.181   928  2989 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-21 16:04:07.182   928   945 D Tethering: MasterInitialState.processMessage what=3
11-21 16:04:07.182  5807  5823 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 16:04:07.182  5807  5823 D BtGatt.GattService: Client app is not null!
11-21 16:04:07.183  5807  5837 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 16:04:07.184  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 16:04:07.184  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.184  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:04:07.184  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.184  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.184  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.184  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 16:04:07.185  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-21 16:04:07.186  3769  3887 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-21 16:04:07.188  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 16:04:07.188  3769  3887 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-21 16:04:07.189  3769  3887 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-21 16:04:07.190  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.192  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.192  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 16:04:07.192  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:07.192  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.193  5690  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 16:04:07.193  5690  5690 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 16:04:07.193  5690  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:04:07.193  5690  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:04:07.193  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:04:07.193  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:04:07.193  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:04:07.193  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.193  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-21 16:04:07.193  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 16:04:07.193  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.193  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.193  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 16:04:07.193  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.194  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.194  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.194  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.194  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.195  5690  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 16:04:07.196  5690  5736 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-21 16:04:07.196  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 16:04:07.197  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 16:04:07.197  5690  5736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-21 16:04:07.197  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-21 16:04:07.197  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:04:07.197  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-21 16:04:07.199  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 16:04:07.200  5037  5057 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-21 16:04:07.200  5037  5057 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 16:04:07.200  5037  5057 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-21 16:04:07.200  5037  5057 E SarControlService: no key has been found,reset the power
11-21 16:04:07.200  5037  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-21 16:04:07.200  5037  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 16:04:07.200  5037  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 16:04:07.201  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 16:04:07.201  5062  5062 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-21 16:04:07.202  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:04:07.202  5690  5736 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:04:07.202  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 16:04:07.202  5037  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-21 16:04:07.202  5037  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-21 16:04:07.202  5037  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 16:04:07.203  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 16:04:07.203  3950  3950 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-21 16:04:07.205  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.205  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:04:07.203  5062  5062 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-21 16:04:07.206  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:04:07.206  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSetti,ngs: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:04:07.206  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-21 16:04:07.206  3979  3979 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-21 16:04:07.208  5062  5076 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9bbf72f HexData = [00000000ec03000000000000ffffffff]
,11-21 16:04:07.208  5062  5076 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 16:04:07.208  5062  5076 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-21 16:04:07.209  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-21 16:04:07.211  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-21 16:04:07.212  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.212  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-21 16:04:07.212  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-21 16:04:07.212  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-21 16:04:07.212  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-21 16:04:07.213  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.213  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 16:04:07.213  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:04:07.214  5037  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-21 16:04:07.214  3979  3979 D SystemUpdateService: onCreate
11-21 16:04:07.215  5062  5076 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9bbf72f HexData = [00000000ed03000000000000ffffffff]
11-21 16:04:07.215  5807  5846 D BtGatt.GattService: registerClient() - UUID=629f5c60-719b-4ba4-8e8c-1d4e06923af6
11-21 16:04:07.216  5807  5823 D BtGatt.GattService: onClientRegistered() - UUID=629f5c60-719b-4ba4-8e8c-1d4e06923af6, clientIf=5
11-21 16:04:07.216  5690  5700 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-21 16:04:07.216  5062  5076 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 16:04:07.216  5062  5076 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-21 16:04:07.217  5807  5818 D BtGatt.GattService: start scan with filters
11-21 16:04:07.217  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 16:04:07.217  5037  5048 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-21 16:04:07.220  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-21 16:04:07.220  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.220  5807  5826 D BtGatt.ScanManager: handling starting scan
11-21 16:04:07.220  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-21 16:04:07.221  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.221  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:04:07.221  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:04:07.221  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.221  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 16:04:07.221  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:04:07.221  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.221  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.222  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-21 16:04:07.222  5807  5826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4969c19
11-21 16:04:07.222  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:04:07.222  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.225  3979  3979 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-21 16:04:07.228  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.228  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-21 16:04:07.228  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:07.228  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:07.228  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.228  5807  5823 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-21 16:04:07.229  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:04:07.229  5807  5826 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-21 16:04:07.232  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-21 16:04:07.232  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.232  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.232  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.232  5690  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-21 16:04:07.236  5807  5823 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-21 16:04:07.236  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:04:07.236  5807  5826 D BtGatt.ScanManager: Starting BLE batch scan
11-21 16:04:07.236  5807  5826 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-21 16:04:07.240  3979  3979 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-21 16:04:07.244  3979  5390 I iu.UploadsManager: num queued entries: 0
,11-21 16:04:07.245  3979  5390 I iu.UploadsManager: num updated entries: 0
11-21 16:04:07.245  3979  5390 I iu.SyncManager: NEXT; no task
,11-21 16:04:07.249  3979  5964 I SystemUpdateService: active receiver: enabled
,11-21 16:04:07.251  3979  3979 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-21 16:04:07.251  5807  5823 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-21 16:04:07.251  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:04:07.252  3979  3979 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-21 16:04:07.254  5883  5883 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-21 16:04:07.257  5807  5823 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-21 16:04:07.257  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:04:07.259  5883  5883 D SprintDMHelper: simOperator: 
,11-21 16:04:07.259  5883  5883 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 16:04:07.288  3979  5964 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-21 16:04:07.297  3979  5964 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-21 16:04:07.297  3979  5964 I SystemUpdateService: now status is 0 (complete)
11-21 16:04:07.297  3979  5964 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 16:04:07.297  3979  5964 I SystemUpdateService: file has been verified
11-21 16:04:07.298  3979  5964 I SystemUpdateService: OTA package size = 21989297
,11-21 16:04:07.305  3979  5964 I SystemUpdateService: showing system update notification
,11-21 16:04:07.313   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 16:04:07.314  3979  3979 D SystemUpdateService: onDestroy
,11-21 16:04:07.381   928  5948 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-21 16:04:07.448  5012  5968 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-21 16:04:07.448   928  5948 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Nov 2016 15:04:07 GMT], X-Android-Received-Millis=[1479740647446], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479740647420]}
,11-21 16:04:07.449   928  2989 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-21 16:04:07.450   928  2989 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-21 16:04:07.450   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-21 16:04:07.453   928  2989 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-21 16:04:07.734  5690  5690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-21 16:04:07.734  5690  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 16:04:07.734  5690  5690 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 16:04:07.760  5807  5807 D BtGatt.ScanManager: awakened up at time 203300
,11-21 16:04:07.762  5807  5826 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 16:04:07.790  5807  5823 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-21 16:04:07.791  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:04:07.791  5807  5823 D BtGatt.GattService: current time is 203331864413
,11-21 16:04:07.792  5807  5823 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,11-21 16:04:07.795  5807  5823 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
11-21 16:04:07.801  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 1. Current thread: Thread[main,5,main], id: 1
11-21 16:04:07.801  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=203182708945}
,11-21 16:04:07.801  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=203182708945}
,11-21 16:04:08.181   928  2989 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-21 16:04:10.230  5690  5736 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-21 16:04:10.231  5690  5736 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-21 16:04:10.231  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-21 16:04:10.232  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.232  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:10.232  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.232  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 16:04:10.232  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 16:04:10.232  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 16:04:10.232  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-21 16:04:10.232  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 16:04:10.232  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 16:04:10.232  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 16:04:10.232  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 16:04:10.232  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 16:04:10.232  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.233  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
,11-21 16:04:10.233  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.233  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.233  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:04:10.233  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-21 16:04:10.234  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.234  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:10.238  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:10.241  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:04:10.242  5807  5846 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-21 16:04:10.243  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-21 16:04:10.244  5807  5826 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 16:04:10.245  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:04:10.247  5807  5818 D BtGatt.GattService: stopScan() - queue size =1
,11-21 16:04:10.248  5807  5838 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 16:04:10.249  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:04:10.249  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.249  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 16:04:10.249  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.249  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:04:10.250  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.250  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.250  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-21 16:04:10.250  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-21 16:04:10.250  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-21 16:04:10.250  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-21 16:04:10.250  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:10.250  5807  5807 D BtGatt.ScanManager: awakened up at time 205790
,11-21 16:04:10.251  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:04:10.255  5807  5837 D BtGatt.GattService: registerClient() - UUID=35b475db-c095-4d11-b968-e31b460b2647
11-21 16:04:10.255  5807  5823 D BtGatt.GattService: onClientRegistered() - UUID=35b475db-c095-4d11-b968-e31b460b2647, clientIf=5
,11-21 16:04:10.256  5690  5701 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-21 16:04:10.257  5807  5818 D BtGatt.GattService: start scan with filters
11-21 16:04:10.262  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-21 16:04:10.262  5807  5823 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-21 16:04:10.262  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:04:10.262  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.262  5807  5823 D BtGatt.GattService: current time is 205802382427
,11-21 16:04:10.262  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-21 16:04:10.262  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.262  5807  5823 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -79, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -92, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 16:04:10.262  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.262  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:04:10.262  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 16:04:10.262  5807  5823 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-21 16:04:10.262  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:04:10.262  5690  5736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 16:04:10.262  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 16:04:10.262  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:04:10.262  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 16:04:10.262  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:04:10.262  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:04:10.263  5807  5823 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 16:04:10.263  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 16:04:10.264  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
11-21 16:04:10.264  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-92, mTimestampNanos=204202647187}
11-21 16:04:10.264  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-92, mTimestampNanos=204202647187}
11-21 16:04:10.265  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
11-21 16:04:10.265  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-21 16:04:10.265  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=204152647187}
11-21 16:04:10.266  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 16:04:10.266  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=204152647187}
11-21 16:04:10.266  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
11-21 16:04:10.266  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-21 16:04:10.266  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-21 16:04:10.266  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:04:10.266  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 16:04:10.266  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:04:10.266  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-21 16:04:10.266  5690  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:04:10.268  5690  5977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:04:10.268  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:04:10.268  5690  5736 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:04:10.269  5690  5977 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:04:10.267  5818  5818 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[32065]" dev="sockfs" ino=32065 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:04:10.267  5818  5818 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32065]" dev="sockfs" ino=32065 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:04:10.271  5690  5977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 16:04:10.272  5807  5823 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-21 16:04:10.272  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:04:10.272  5807  5826 D BtGatt.ScanManager: stopping BLe Batch
,11-21 16:04:10.277  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:10.277  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.277  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.277  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:04:10.277  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:04:10.277  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:04:10.277  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-21 16:04:10.277  5690  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 16:04:10.277  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:04:10.277  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.278  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:04:10.278  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:04:10.278  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.278  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.278  5807  5823 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-21 16:04:10.278  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:04:10.278  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.278  5807  5826 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 16:04:10.279  5690  5736 D BluetoothAdapter: STATE_ON
,11-21 16:04:10.284  5807  5823 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-21 16:04:10.284  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:04:10.286  5807  5846 D BtGatt.GattService: registerClient() - UUID=38818d63-c0f1-4686-9b51-8f5b2360685b
11-21 16:04:10.287  5807  5823 D BtGatt.GattService: onClientRegistered() - UUID=38818d63-c0f1-4686-9b51-8f5b2360685b, clientIf=6
,11-21 16:04:10.287  5690  5701 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-21 16:04:10.288  5807  5826 D BtGatt.ScanManager: handling starting scan
11-21 16:04:10.288  5807  5825 D BtGatt.AdvertiseManager: message : 0
,11-21 16:04:10.292  5807  5825 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:04:10.294  5807  5823 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-21 16:04:10.294  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:04:10.294  5807  5826 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-21 16:04:10.304  5807  5823 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-21 16:04:10.309  5807  5823 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-21 16:04:10.309  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:04:10.309  5807  5826 D BtGatt.ScanManager: Starting BLE batch scan
11-21 16:04:10.309  5807  5826 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-21 16:04:10.314  5807  5823 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-21 16:04:10.314  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:10.314  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.314  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:04:10.315  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.315  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.315  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.315  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.315  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:10.315  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.315  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.315  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.315  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-21 16:04:10.315  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-21 16:04:10.315  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 16:04:10.316  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:04:10.317  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:10.319  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.319  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:10.319  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:10.320  5690  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-21 16:04:10.320  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:04:10.320  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:04:10.320  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:04:10.320  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:04:10.320  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:04:10.320  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:04:10.320  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:04:10.320  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-21 16:04:10.320  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 16:04:10.320  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:04:10.320  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:04:10.321  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-21 16:04:10.321  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 16:04:10.324  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:04:10.324  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-21 16:04:10.324  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:04:10.324  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:04:10.324  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 16:04:10.324  5690  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-21 16:04:10.325  5807  5823 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-21 16:04:10.325  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:04:10.330  5807  5823 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-21 16:04:10.330  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:04:10.826  5690  5690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-21 16:04:10.826  5690  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 16:04:10.826  5690  5690 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 16:04:13.323  5690  5736 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-21 16:04:13.324  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 16:04:13.324  5690  5736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:04:13.324  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-21 16:04:13.324  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:04:13.325  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-21 16:04:13.325  5690  5977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-21 16:04:13.325  5690  5977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:04:13.325  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 16:04:13.325  5690  5977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:04:13.325  5690  5736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:04:13.325  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 16:04:13.325  5690  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:04:13.325  5690  5736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10fae86 removed from the list
11-21 16:04:13.326  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 16:04:13.326  5690  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:04:13.326  5690  5736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:04:13.326  5690  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:04:13.326  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:04:13.326  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:04:13.328  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.328  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.329  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.329  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-21 16:04:13.329  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.331  5690  5736 D BluetoothAdapter: STATE_ON
,11-21 16:04:13.332  5807  5846 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-21 16:04:13.332  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:04:13.334  5807  5826 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-21 16:04:13.334  5690  5736 D BluetoothAdapter: STATE_ON
11-21 16:04:13.336  5807  5817 D BtGatt.GattService: stopScan() - queue size =1
11-21 16:04:13.338  5807  5818 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 16:04:13.339  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-21 16:04:13.339  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.339  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 16:04:13.340  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.340  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:13.340  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.340  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:04:13.340  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.342  5807  5825 D BtGatt.AdvertiseManager: message : 1
,11-21 16:04:13.342  5807  5807 D BtGatt.ScanManager: awakened up at time 208882
11-21 16:04:13.343  5807  5825 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-21 16:04:13.356  5807  5823 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-21 16:04:13.357  5807  5823 D BtGatt.GattService: Client app is not null!
,11-21 16:04:13.358  5807  5817 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-21 16:04:13.359  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 16:04:13.360  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.360  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:04:13.360  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:13.360  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.360  5690  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.360  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 16:04:13.361  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 16:04:13.362  5690  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 16:04:13.363  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:13.365  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-21 16:04:13.365  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:04:13.365  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.366  5690  5736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-21 16:04:13.366  5690  5736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7e5347 removed from the list
11-21 16:04:13.366  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:04:13.366  5690  5736 D io.jxcore.node.ConnectivityMonitor: stop
11-21 16:04:13.366  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:04:13.366  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:04:13.366  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 16:04:13.366  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:04:13.367  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-21 16:04:13.367  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:04:13.367  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:04:13.367  5690  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-21 16:04:13.367  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:04:13.367  5690  5736 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,11-21 16:04:13.368  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 16:04:13.368  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 16:04:13.368  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 16:04:13.368  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 16:04:13.368  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-21 16:04:13.368  5690  5736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-21 16:04:13.368  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:04:13.369  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:04:13.369  5690  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-21 16:04:13.369  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:04:13.369  5690  5736 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-21 16:04:13.369  5690  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:04:13.369  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:04:13.369  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:04:13.369  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:04:13.369  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:04:13.370  5690  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:04:13.370  5690  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:04:13.370  5690  5736 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-21 16:04:13.371  5690  5736 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-21 16:04:13.372  5690  5736 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-21 16:04:13.373  5690  5736 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-21 16:04:13.374  5690  5736 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-21 16:04:13.375  5690  5736 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-21 16:04:13.375  5690  5736 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-21 16:04:13.388  5807  5823 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-21 16:04:13.388  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:04:13.389  5807  5823 D BtGatt.GattService: current time is 208929134285
11-21 16:04:13.389  5807  5823 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -88, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -96, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -81, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -93, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -100, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 16:04:13.389  5807  5823 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-21 16:04:13.389  5807  5823 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-21 16:04:13.390  5807  5823 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-21 16:04:13.390  5807  5823 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-21 16:04:13.390  5807  5823 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-21 16:04:13.390  5807  5823 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-21 16:04:13.396  5807  5823 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-21 16:04:13.396  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:04:13.396  5807  5826 D BtGatt.ScanManager: stopping BLe Batch
,11-21 16:04:13.403  5807  5823 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-21 16:04:13.404  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:04:13.404  5807  5826 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 16:04:13.409  5807  5823 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-21 16:04:13.409  5807  5823 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:04:13.871  5690  5690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 16:04:15.132   928  2989 D ConnectivityService: handlePromptUnvalidated 101
,11-21 16:04:15.380  5690  5736 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-21 16:04:15.521  5690  5979 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 16:04:15.521  5690  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:04:16.318  5690  5979 W !!      : call onHalfStreamCopied
,11-21 16:04:16.318  5690  5979 I testCopyDataAndClose: closing input stream
,11-21 16:04:17.090  5690  5979 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 16:04:17.090  5690  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:04:17.090  5690  5979 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 16:04:17.090  5690  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:04:17.090  5690  5979 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 16:04:17.090  5690  5979 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 16:04:17.090  5690  5979 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 16:04:17.090  5690  5979 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-21 16:04:17.090  5690  5979 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 16:04:17.090  5690  5979 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 16:04:17.090  5690  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 16:04:18.255   928  2987 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,11-21 16:04:21.280  5690  5736 I StreamCopyingThreadTest: Starting test: testRun
,11-21 16:04:21.286  5690  5980 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:04:21.286  5690  5980 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:04:22.008   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:04:23.469   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 16:04:23.469   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 16:04:25.048   928  2989 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:04:26.294  5690  5981 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-21 16:04:26.297  5690  5736 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-21 16:04:26.410  5690  5982 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 16:04:26.410  5690  5982 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:04:28.114  5690  5982 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 16:04:28.114  5690  5982 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:04:28.114  5690  5982 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 16:04:28.114  5690  5982 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:04:28.114  5690  5982 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 16:04:28.114  5690  5982 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 16:04:28.114  5690  5982 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 16:04:28.114  5690  5982 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 16:04:28.114  5690  5982 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 16:04:28.114  5690  5982 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 16:04:28.114  5690  5982 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 16:04:31.493  3699  3869 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-21 16:04:31.494  3699  3869 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-21 16:04:31.529  3595  3595 I ConfigService: onCreate
,11-21 16:04:32.243  5690  5736 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-21 16:04:32.247  5690  5984 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:04:32.247  5690  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:04:32.247  5690  5984 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:04:32.247  5690  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:04:32.247  5690  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 16:04:32.247  5690  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:04:32.247  5690  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 16:04:32.247  5690  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-21 16:04:32.248  5690  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 16:04:32.248  5690  5984 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-21 16:04:32.248  5690  5984 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 16:04:32.248  5690  5984 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:04:32.248  5690  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-21 16:04:32.249  5690  5736 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-21 16:04:32.250  5690  5736 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-21 16:04:32.251  5690  5736 I StreamCopyingThreadTest: Starting test: testRunWithException
11-21 16:04:32.253  5690  5985 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:04:32.253  5690  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:04:32.253  5690  5985 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
11-21 16:04:32.254  5690  5985 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:04:32.254  5690  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-21 16:04:32.254  5690  5985 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-21 16:04:32.254  5690  5985 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:04:32.254  5690  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-21 16:04:32.256  5690  5736 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-21 16:04:32.256  5690  5736 E com.test.thalitest.ThaliTestRunner: 
11-21 16:04:32.256  5690  5736 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-21 16:04:32.256  5690  5736 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.,runLeaf(ParentRunner.java:325)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58),
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
,11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 16:04:32.257  5690  5736 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native ,Method)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:,04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-21 16:04:32.258  5690  5,736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(Parent,Runner.java:363)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:04:32.258  5690  5736 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-21 16:04:32.261  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG UnitTest_app: 'Running unit tests'
11-21 16:04:32.261  5690  5736 I jxcore-log: 
11-21 16:04:32.261  5690  5736 I jxcore-log: *Native tests were executed*
11-21 16:04:32.261  5690  5736 I jxcore-log: 
11-21 16:04:32.261  5690  5736 I jxcore-log: Total number of executed tests:  82
11-21 16:04:32.261  5690  5736 I jxcore-log: 
11-21 16:04:32.261  5690  5736 I jxcore-log: Number of passed tests:  79
11-21 16:04:32.261  5690  5736 I jxcore-log: 
11-21 16:04:32.261  5690  5736 I jxcore-log: Number of failed tests:  3
11-21 16:04:32.261  5690  5736 I jxcore-log: 
11-21 16:04:32.261  5690  5736 I jxcore-log: Number of ignored tests:  0
11-21 16:04:32.261  5690  5736 I jxcore-log: 
11-21 16:04:32.261  5690  5736 I jxcore-log: Total duration:  39693
11-21 16:04:32.261  5690  5736 I jxcore-log: 
11-21 16:04:32.261  5690  5736 I jxcore-log: Failed to execute UT.
11-21 16:04:32.261  5690  5736 I jxcore-log: 
11-21 16:04:32.262  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-21 16:04:32.262  5690  5736 I jxcore-log: 
11-21 16:04:32.263  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-21 16:04:32.263  5690  5736 I jxcore-log: 
11-21 16:04:32.266  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:04:32.266  5690  5736 I jxcore-log: 
11-21 16:04:32.266  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:04:32.266  5690  5736 I jxcore-log: 
11-21 16:04:32.268  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:04:32.268  5690  5736 I jxcore-log: 
11-21 16:04:32.268  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:04:32.268  5690  5736 I jx,core-log: 
11-21 16:04:32.269  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 16:04:32.269  5690  5736 I jxcore-log: 
11-21 16:04:32.269  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:04:32.269  5690  5736 I jxcore-log: 
11-21 16:04:32.269  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:04:32.269  5690  5736 I jxcore-log: 
11-21 16:04:32.269  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 16:04:32.269  5690  5736 I jxcore-log: 
11-21 16:04:32.270  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:04:32.270  5690  5736 I jxcore-log: 
11-21 16:04:32.270  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:04:32.270  5690  5736 I jxcore-log: 
11-21 16:04:32.270  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 16:04:32.270  5690  5736 I jxcore-log: 
11-21 16:04:32.270  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:04:32.270  5690  5736 I jxcore-log: 
11-21 16:04:32.271  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:04:32.271  5690  5736 I jxcore-log: 
11-21 16:04:32.271  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 16:04:32.271  5690  5736 I jxcore-log: 
11-21 16:04:32.271  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:04:32.271  5690  5736 I jxcore-log: 
11-21 16:04:32.271  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:04:32.271  5690  5736 I jxcore-log: 
11-21 16:04:32.271  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:04:32.271  5690  5736 I jxcore-log: 
11-21 16:04:32.272  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 16:04:32.272  5690  5736 I jxcore-log: 
11-21 16:04:32.272  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:04:32.272  5690  5736 I jxcore-log: 
11-21 16:04:32.272  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:04:32.272  5690  5736 I jxcore-log: 
,11-21 16:04:32.272  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:04:32.272  5690  5736 I jxcore-log: 
11-21 16:04:32.272  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:04:32.272  5690  5736 I jxcore-log: 
11-21 16:04:32.273  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:04:32.273  5690  5736 I jxcore-log: 
11-21 16:04:32.273  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-21 16:04:32.273  5690  5736 I jxcore-log: 
11-21 16:04:32.273  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:04:32.273  5690  5736 I jxcore-log: 
11-21 16:04:32.273  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-21 16:04:32.273  5690  5736 I jxcore-log: 
11-21 16:04:32.274  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:04:32.274  5690  5736 I jxcore-log: 
11-21 16:04:32.275  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 16:04:32.275  5690  5736 I jxcore-log: 
,11-21 16:04:32.275  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:04:32.275  5690  5736 I jxcore-log: 
11-21 16:04:32.275  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:04:32.275  5690  5736 I jxcore-log: 
11-21 16:04:32.276  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-21 16:04:32.276  5690  5736 I jxcore-log: 
11-21 16:04:32.276  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:04:32.276  5690  5736 I jxcore-log: 
11-21 16:04:32.276  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:04:32.276  5690  5736 I jxcore-log: 
11-21 16:04:32.276  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-21 16:04:32.276  5690  5736 I jxcore-log: 
,11-21 16:04:32.276  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:04:32.276  5690  5736 I jxcore-log: 
11-21 16:04:32.277  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:04:32.277  5690  5736 I jxcore-log: 
11-21 16:04:32.277  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 16:04:32.277  5690  5736 I jxcore-log: 
11-21 16:04:32.277  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:04:32.277  5690  5736 I jxcore-log: 
11-21 16:04:32.282  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-21 16:04:32.282  5690  5736 I jxcore-log: 
,11-21 16:04:32.282  5690  5736 I jxcore-log: 2016-11-21 15:04:32 - WARN testUtils: 'myNameCallback not set!'
11-21 16:04:32.282  5690  5736 I jxcore-log: 
11-21 16:04:32.288  5690  5690 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-21 16:04:33.470   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:04:34.241   928  5949 D NetlinkSocketObserver: NeighborEvent{elapsedMs=229780, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:04:34.345  5690  5736 I jxcore-log: 2016-11-21 15:04:34 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-21 16:04:34.345  5690  5736 I jxcore-log: 
,11-21 16:04:34.347  5690  5736 I jxcore-log: 2016-11-21 15:04:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-21 16:04:34.347  5690  5736 I jxcore-log: 
,11-21 16:04:34.472   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:04:34.688  5690  5736 I jxcore-log: 2016-11-21 15:04:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-21 16:04:34.688  5690  5736 I jxcore-log: 
,11-21 16:04:34.700  5690  5736 I jxcore-log: 2016-11-21 15:04:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-21 16:04:34.700  5690  5736 I jxcore-log: 
,11-21 16:04:35.473   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:04:35.795  5690  5736 I jxcore-log: 2016-11-21 15:04:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-21 16:04:35.795  5690  5736 I jxcore-log: 
,11-21 16:04:35.959  5690  5736 I jxcore-log: 2016-11-21 15:04:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-21 16:04:35.959  5690  5736 I jxcore-log: 
,11-21 16:04:35.965  5690  5736 I jxcore-log: 2016-11-21 15:04:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-21 16:04:35.965  5690  5736 I jxcore-log: 
,11-21 16:04:35.977  5690  5736 I jxcore-log: 2016-11-21 15:04:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-21 16:04:35.977  5690  5736 I jxcore-log: 
,11-21 16:04:36.466  5690  5736 I jxcore-log: 2016-11-21 15:04:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-21 16:04:36.466  5690  5736 I jxcore-log: 
,11-21 16:04:36.474   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:04:36.511  5690  5736 I jxcore-log: 2016-11-21 15:04:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-21 16:04:36.511  5690  5736 I jxcore-log: 
,11-21 16:04:36.524  5690  5736 I jxcore-log: 2016-11-21 15:04:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-21 16:04:36.524  5690  5736 I jxcore-log: 
,11-21 16:04:36.528  5690  5736 I jxcore-log: 2016-11-21 15:04:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-21 16:04:36.528  5690  5736 I jxcore-log: 
,11-21 16:04:36.564  3595  3595 I ConfigService: onDestroy
,11-21 16:04:36.798  5690  5736 I jxcore-log: 2016-11-21 15:04:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-21 16:04:36.798  5690  5736 I jxcore-log: 
,11-21 16:04:36.924  5690  5736 I jxcore-log: 2016-11-21 15:04:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-21 16:04:36.924  5690  5736 I jxcore-log: 
,11-21 16:04:37.309  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-21 16:04:37.309  5690  5736 I jxcore-log: 
,11-21 16:04:37.316  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-21 16:04:37.316  5690  5736 I jxcore-log: 
,11-21 16:04:37.320  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-21 16:04:37.320  5690  5736 I jxcore-log: 
,11-21 16:04:37.324  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-21 16:04:37.324  5690  5736 I jxcore-log: 
,11-21 16:04:37.330  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-21 16:04:37.330  5690  5736 I jxcore-log: 
,11-21 16:04:37.368  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-21 16:04:37.368  5690  5736 I jxcore-log: 
,11-21 16:04:37.374  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-21 16:04:37.374  5690  5736 I jxcore-log: 
,11-21 16:04:37.402  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-21 16:04:37.402  5690  5736 I jxcore-log: 
,11-21 16:04:37.441  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-21 16:04:37.441  5690  5736 I jxcore-log: 
,11-21 16:04:37.448  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-21 16:04:37.448  5690  5736 I jxcore-log: 
,11-21 16:04:37.455  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-21 16:04:37.455  5690  5736 I jxcore-log: 
,11-21 16:04:37.470  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-21 16:04:37.470  5690  5736 I jxcore-log: 
,11-21 16:04:37.474   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:04:37.485  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-21 16:04:37.485  5690  5736 I jxcore-log: 
,11-21 16:04:37.491  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-21 16:04:37.491  5690  5736 I jxcore-log: 
,11-21 16:04:37.496  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-21 16:04:37.496  5690  5736 I jxcore-log: 
,11-21 16:04:37.509  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-21 16:04:37.509  5690  5736 I jxcore-log: 
,11-21 16:04:37.527  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-21 16:04:37.527  5690  5736 I jxcore-log: 
,11-21 16:04:37.542  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-21 16:04:37.542  5690  5736 I jxcore-log: 
,11-21 16:04:37.552  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-21 16:04:37.552  5690  5736 I jxcore-log: 
,11-21 16:04:37.565  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-21 16:04:37.565  5690  5736 I jxcore-log: 
,11-21 16:04:37.576  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-21 16:04:37.576  5690  5736 I jxcore-log: 
,11-21 16:04:37.589  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-21 16:04:37.589  5690  5736 I jxcore-log: 
,11-21 16:04:37.599  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-21 16:04:37.599  5690  5736 I jxcore-log: 
,11-21 16:04:37.606  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-21 16:04:37.606  5690  5736 I jxcore-log: 
,11-21 16:04:37.626  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-21 16:04:37.626  5690  5736 I jxcore-log: 
,11-21 16:04:37.633  5690  5736 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-21 16:04:37.634  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - INFO testUtils: 'BLE multiple advertisement supported'
11-21 16:04:37.634  5690  5736 I jxcore-log: 
,11-21 16:04:37.910  5690  5736 I jxcore-log: 2016-11-21 15:04:37 - DEBUG CoordinatedClient: 'connected to the test server'
11-21 16:04:37.910  5690  5736 I jxcore-log: 
,11-21 16:04:38.173  5690  5736 I jxcore-log: 2016-11-21 15:04:38 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
11-21 16:04:38.173  5690  5736 I jxcore-log: 
,11-21 16:04:38.175  5690  5736 I jxcore-log: 2016-11-21 15:04:38 - DEBUG CoordinatedClient: 'test client failed'
11-21 16:04:38.175  5690  5736 I jxcore-log: 
,11-21 16:04:38.180  5690  5736 I jxcore-log: 2016-11-21 15:04:38 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-21 16:04:38.180  5690  5736 I jxcore-log: 
,11-21 16:04:38.187  5690  5736 I jxcore-log: 2016-11-21 15:04:38 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:187:20
11-21 16:04:38.187  5690  5736 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-21 16:04:38.187  5690  5736 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-21 16:04:38.187  5690  5736 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-21 16:04:38.187  5690  5736 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-21 16:04:38.187  5690  5736 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
11-21 16:04:38.187  5690  5736 I jxcore-log: 
,11-21 16:04:38.188  5690  5736 I jxcore-log: 2016-11-21 15:04:38 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-21 16:04:38.188  5690  5736 I jxcore-log: 
,11-21 16:04:38.192  5690  5736 I jxcore-log: 2016-11-21 15:04:38 - ERROR runTests: 'Test client failed: Native unit tests failed
11-21 16:04:38.192  5690  5736 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:187:20
11-21 16:04:38.192  5690  5736 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-21 16:04:38.192  5690  5736 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-21 16:04:38.192  5690  5736 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-21 16:04:38.192  5690  5736 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-21 16:04:38.192  5690  5736 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
11-21 16:04:38.192  5690  5736 I jxcore-log: 
,11-21 16:04:38.475   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-21 16:04:38.703  5994  5994 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-21 16:04:38.709  5994  5994 D AndroidRuntime: CheckJNI is OFF
,11-21 16:04:38.741  5994  5994 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-21 16:04:38.776  5994  5994 I Radio-JNI: register_android_hardware_Radio DONE
,11-21 16:04:38.792  5994  5994 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-21 16:04:38.801   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-21 16:04:38.802   928   941 I ActivityManager: Killing 5690:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-21 16:04:38.888   928  3611 D GraphicsStats: Buffer count: 2
11-21 16:04:38.888   928  2988 D WifiService: Client connection lost with reason: 4
,11-21 16:04:38.888   928   938 I WindowState: WIN DEATH: Window{d84a5b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-21 16:04:38.907   928   941 W ActivityManager: Force removing ActivityRecord{8746980 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-21 16:04:38.943   928   951 I art     : Starting a blocking GC Explicit
,11-21 16:04:38.949   928  3611 W ActivityManager: Spurious death for ProcessRecord{525c1b2 0:com.test.thalitest/u0a77}, curProc for 5690: null
,11-21 16:04:38.987   928  3876 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5690 uid 10077
,11-21 16:04:38.983  3876  3876 W Binder_8: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[26085]" dev="sockfs" ino=26085 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 16:04:38.983  3876  3876 W Binder_8: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[26085]" dev="sockfs" ino=26085 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:04:39.008  3699  3699 I Keyboard.Facilitator: onFinishInput()
,11-21 16:04:39.023   928   951 I art     : Explicit concurrent mark sweep GC freed 27719(1767KB) AllocSpace objects, 7(192KB) LOS objects, 33% free, 28MB/43MB, paused 1.984ms total 79.805ms
,11-21 16:04:39.052   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-21 16:04:39.054  5994  5994 I art     : System.exit called, status: 0
,11-21 16:04:39.054  5994  5994 I AndroidRuntime: VM exiting with result code 0.
,11-21 16:04:39.065  3950  6007 I MicroRecognitionRnrImpl: Starting detection.
,11-21 16:04:39.067  3950  6009 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@ee7eadc
11-21 16:04:39.068   514  6013 I AudioFlinger: AudioFlinger's thread 0xf2200000 ready to run
,11-21 16:04:39.072   514  3040 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-21 16:04:39.073  3950  6009 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@ee7eadc
11-21 16:04:39.074   928   951 I ActivityManager: Start proc 6008:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-21 16:04:39.075   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-21 16:04:39.082  5807  5807 D BluetoothMapAppObserver: onReceive
,11-21 16:04:39.082  5807  5807 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-21 16:04:39.084   514  6013 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-21 16:04:39.084   514  6013 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-21 16:04:39.084   514  6013 I ACDB-LOADER: ACDB AFE returned = -19
11-21 16:04:39.084   514  6013 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-21 16:04:39.084   514  6013 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-21 16:04:39.084   514  6013 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-21 16:04:39.089  4138  4195 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-21 16:04:39.091   514  6013 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-21 16:04:39.093  3699  3699 I Keyboard.Facilitator: resetDictionaries() : en_US
11-21 16:04:39.094   928  2978 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-21 16:04:39.100  3699  6023 I Keyboard.Facilitator.DecoderInitializer: run()
,11-21 16:04:39.108  3699  6023 I Decoder : createOrResetDecoder
,11-21 16:04:39.146   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-21 16:04:39.157  3802  3802 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-21 16:04:39.163  3595  3595 I ConfigService: onCreate
,11-21 16:04:39.173  3950  3950 I HotwordWorkerImpl: onReady
,11-21 16:04:39.180    29    29 W kworker/3:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 16:04:39.183    29    29 W kworker/3:1: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 16:04:39.190  3699  6023 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-21 16:04:39.198  3595  3595 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-21 16:04:39.199  3595  3595 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
11-21 16:04:39.200  3595  3595 E AndroidRuntime: FATAL EXCEPTION: main
11-21 16:04:39.200  3595  3595 E AndroidRuntime: Process: com.google.process.gapps, PID: 3595
11-21 16:04:39.200  3595  3595 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-21 16:04:39.200  3595  3595 E AndroidRuntime: 	... 8 more
,11-21 16:04:39.207    29    29 W kworker/3:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 16:04:39.217  3415  6027 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-21 16:04:39.220   407   407 W Binder_2: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[13931]" dev="sockfs" ino=13931 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:04:39.220   407   407 W Binder_2: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[13931]" dev="sockfs" ino=13931 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:04:39.228   928  6033 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-21 16:04:39.223   407   407 W Binder_2: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[34239]" dev="sockfs" ino=34239 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 16:04:39.223   407   407 W Binder_2: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[34239]" dev="sockfs" ino=34239 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:04:39.239  3415  3450 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj3892E8979) - 
,11-21 16:04:39.255  3699  6023 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-21 16:04:39.257  3699  6023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-21 16:04:39.257  3699  6023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-21 16:04:39.259  3699  6023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-21 16:04:39.259  3699  6023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,11-21 16:04:39.260  3699  6023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-21 16:04:39.261  3699  6023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,11-21 16:04:39.268  3415  3450 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-21 16:04:39.268  3415  3450 E AndroidRuntime: Process: android.process.acore, PID: 3415
11-21 16:04:39.268  3415  3450 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-21 16:04:39.268  3415  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-21 16:04:39.268  3415  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-21 16:04:39.268  3415  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-21 16:04:39.268  3415  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-21 16:04:39.268  3415  3450 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-21 16:04:39.268  3415  3450 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-21 16:04:39.268  3415  3450 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-21 16:04:39.268  3415  3450 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-21 16:04:39.268  3415  3450 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-21 16:04:39.268  3415  3450 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:04:39.268  3415  3450 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:04:39.268  3415  3450 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-21 16:04:39.274  3415  6027 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-21 16:04:39.274  3415  6027 I Process : Sending signal. PID: 3415 SIG: 9
,11-21 16:04:39.277  3699  6023 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,11-21 16:04:39.277  3699  6023 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-21 16:04:39.277  3699  6023 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-21 16:04:39.278  3699  6023 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-21 16:04:39.278  3699  6023 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-21 16:04:39.278  3699  6023 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-21 16:04:39.283   928  6036 E DropBoxManagerService: Can't write: system_app_crash
11-21 16:04:39.283   928  6036 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
11-21 16:04:39.283   928  6036 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 16:04:39.283   928  6036 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 16:04:39.283   928  6036 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 16:04:39.283   928  6036 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 16:04:39.283   928  6036 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 16:04:39.283   928  6036 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 16:04:39.283   928  6036 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 16:04:39.283   928  6036 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 16:04:39.283   928  6036 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 16:04:39.283   928  6036 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 16:04:39.283   928  6036 E DropBoxManagerService: 	... 5 more
,11-21 16:04:39.295   928  6033 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-21 16:04:39.295   928  6033 I Adreno  : Build Date                       : 12/06/15
11-21 16:04:39.295   928  6033 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-21 16:04:39.295   928  6033 I Adreno  : Local Branch                     : mybranch17112971
11-21 16:04:39.295   928  6033 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-21 16:04:39.295   928  6033 I Adreno  : Remote Branch                    : NONE
11-21 16:04:39.295   928  6033 I Adreno  : Reconstruct Branch               : NOTHING
,11-21 16:04:39.309   928  3611 I ActivityManager: Process android.process.acore (pid 3415) has died
11-21 16:04:39.309   928  3611 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-21 16:04:39.517  3836  4077 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-21 16:04:39.577   384   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
