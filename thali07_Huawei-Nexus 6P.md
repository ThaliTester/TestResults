#### Test 949972298f8f84a_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-23 14:13:58.629  3784  4167 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-23 14:13:58.715  3784  4167 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-23 14:13:59.115  5550  5550 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-23 14:13:59.120  5550  5550 D AndroidRuntime: CheckJNI is OFF
11-23 14:13:59.144  5550  5550 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-23 14:13:59.174  5550  5550 I Radio-JNI: register_android_hardware_Radio DONE
11-23 14:13:59.190  5550  5550 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-23 14:13:59.192   931  3093 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-23 14:13:59.220  5550  5550 D AndroidRuntime: Shutting down VM
11-23 14:13:59.220  3909  3925 W SearchService: Abort, client detached.
11-23 14:13:59.225  3909  3909 I HotwordDetector: Closing mic
11-23 14:13:59.226  3909  4132 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3d56048
11-23 14:13:59.226  3909  4163 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-23 14:13:59.248   931  3358 I ActivityManager: Start proc 5560:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-23 14:13:59.298   515  4166 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-23 14:13:59.301   515  4166 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-23 14:13:59.306   515  4166 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-23 14:13:59.306   515  4166 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-23 14:13:59.307   515  2934 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-23 14:13:59.309  3909  4153 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-23 14:13:59.309  3909  4160 I MicroRecognitionRnrImpl: Detection finished
11-23 14:13:59.360  5560  5560 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-23 14:13:59.384  5560  5560 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-23 14:13:59.439  5560  5560 I LibraryLoader: Time to load native libraries: 51 ms (timestamps 8818-8869)
,11-23 14:13:59.439  5560  5560 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-23 14:13:59.464  5560  5560 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8b99dfb},
11-23 14:13:59.464  5560  5560 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-23 14:13:59.464  5560  5560 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-23 14:13:59.468  5560  5560 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-23 14:13:59.468  5560  5560 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-23 14:13:59.524  5560  5560 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-23 14:13:59.533  5560  5560 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-23 14:13:59.534  5560  5560 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-23 14:13:59.534  5560  5560 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 14:13:59.534  5560  5560 I Adreno  : Build Date                       : 12/06/15
11-23 14:13:59.534  5560  5560 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 14:13:59.534  5560  5560 I Adreno  : Local Branch                     : mybranch17112971
11-23 14:13:59.534  5560  5560 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 14:13:59.534  5560  5560 I Adreno  : Remote Branch                    : NONE
11-23 14:13:59.534  5560  5560 I Adreno  : Reconstruct Branch               : NOTHING
,11-23 14:13:59.567   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9f0e7a4:true
,11-23 14:13:59.595   786   786 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[26298]" dev="sockfs" ino=26298 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 14:13:59.595   786   786 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[26298]" dev="sockfs" ino=26298 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 14:13:59.607  5560  5560 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-23 14:13:59.615  5560  5560 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-23 14:13:59.639  5560  5597 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 14:13:59.638   787   787 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32800]" dev="sockfs" ino=32800 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 14:13:59.638   787   787 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32800]" dev="sockfs" ino=32800 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 14:13:59.638   941   941 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14196]" dev="sockfs" ino=14196 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 14:13:59.638   941   941 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14196]" dev="sockfs" ino=14196 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 14:13:59.643  5560  5584 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-23 14:13:59.665  5560  5597 I OpenGLRenderer: Initialized EGL, version 1.4
,11-23 14:13:59.725   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +498ms
,11-23 14:13:59.722  3358  3358 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[29593]" dev="sockfs" ino=29593 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 14:13:59.722  3358  3358 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[29593]" dev="sockfs" ino=29593 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 14:13:59.725  3093  3093 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[29592]" dev="sockfs" ino=29592 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 14:13:59.725  3093  3093 W Binder_3: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[29592]" dev="sockfs" ino=29592 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 14:13:59.733  3607  3607 I Keyboard.Facilitator: onFinishInput()
,11-23 14:13:59.774  5560  5560 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5560
,11-23 14:13:59.891  5560  5560 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-23 14:14:00.008  5560  5599 D jxcore_app_log: JniHelper::setJavaVM(0xf55fc000), pthread_self() = -576718544
,11-23 14:14:00.012  5560  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-23 14:14:00.012  5560  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-23 14:14:00.012  5560  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-23 14:14:00.012  5560  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-23 14:14:00.012  5560  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-23 14:14:00.012  5560  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45d3cee added. We now have 1 listener(s)
,11-23 14:14:00.015  5560  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-23 14:14:00.015  5560  5599 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 14:14:00.016  5560  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-23 14:14:00.016  5560  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-23 14:14:00.018  5560  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e50425 added. We now have 1 listener(s)
11-23 14:14:00.018  5560  5599 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 14:14:00.023   931  2932 D WifiService: New client listening to asynchronous messages
,11-23 14:14:00.024  5560  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 14:14:00.024  5560  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-23 14:14:00.024  5560  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-23 14:14:00.024  5560  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-23 14:14:00.024  5560  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-23 14:14:00.024  5560  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-23 14:14:00.024  5560  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-23 14:14:00.026  5560  5599 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-23 14:14:00.067  5560  5560 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-23 14:14:00.623  5560  5606 W jxcore-log: Initializing JXcore engine
,11-23 14:14:00.623  5560  5606 W jxcore-log: JXcore engine is ready
,11-23 14:14:00.645  5606  5606 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12104 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-23 14:14:00.645  5606  5606 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[1776]" dev="sockfs" ino=1776 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-23 14:14:00.645  5606  5606 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-23 14:14:00.645  5606  5606 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31424]" dev="sockfs" ino=31424 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-23 14:14:00.656  5560  5606 W jxcore-log: Starting JXcore engine
,11-23 14:14:00.706  5560  5606 W jxcore-log: Platform android
11-23 14:14:00.706  5560  5606 W jxcore-log: 
,11-23 14:14:00.706  5560  5606 W jxcore-log: Process ARCH arm
11-23 14:14:00.706  5560  5606 W jxcore-log: 
,11-23 14:14:00.892  5560  5606 I jxcore-log: JXcore Cordova bridge is ready!
11-23 14:14:00.892  5560  5606 I jxcore-log: 
,11-23 14:14:00.892  5560  5606 W jxcore-log: JXcore engine is started
,11-23 14:14:00.901  5560  5599 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-23 14:14:00.908  5560  5560 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-23 14:14:02.799  3527  3527 I ConfigService: onDestroy
,11-23 14:14:04.234   931  3791 I ActivityManager: Killing 5071:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-23 14:14:09.348  3909  5609 W CronetSyncConnectionRcs: Upload content type not set.
,11-23 14:14:09.533   931  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 14:14:10.546  5560  5606 I jxcore-log: 2016-11-23 13:14:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-23 14:14:10.546  5560  5606 I jxcore-log: 
,11-23 14:14:10.548  5560  5606 I jxcore-log: 2016-11-23 13:14:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-23 14:14:10.548  5560  5606 I jxcore-log: 
,11-23 14:14:10.553  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-23 14:14:10.553  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 14:14:10.553  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:10.553  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:10.553  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 14:14:10.553  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 14:14:10.553  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 14:14:10.553  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 14:14:10.553  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 14:14:10.553  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 14:14:10.555  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 14:14:10.557  5560  5606 I jxcore-log: 2016-11-23 13:14:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-23 14:14:10.557  5560  5606 I jxcore-log: 
11-23 14:14:10.558  5560  5606 I jxcore-log: 2016-11-23 13:14:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-23 14:14:10.558  5560  5606 I jxcore-log: 
,11-23 14:14:10.804  5560  5606 I jxcore-log: 2016-11-23 13:14:10 - DEBUG UnitTest_app: 'Running unit tests'
11-23 14:14:10.804  5560  5606 I jxcore-log: 
,11-23 14:14:10.805  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 14:14:10.805  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b90891 added. We now have 2 listener(s)
11-23 14:14:10.806  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 14:14:10.806  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 14:14:10.806  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 14:14:10.806  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 14:14:10.806  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88b03f6 added. We now have 2 listener(s)
,11-23 14:14:10.806  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 14:14:10.807  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 14:14:10.808  5560  5606 D executeNativeTests: Running unit tests
,11-23 14:14:10.848  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 14:14:10.848  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 added. We now have 3 listener(s)
11-23 14:14:10.849  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 14:14:10.849  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 14:14:10.849  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 14:14:10.849  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 14:14:10.849  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 added. We now have 3 listener(s)
,11-23 14:14:10.849  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 14:14:10.850  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 14:14:10.852  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 14:14:10.852  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 14:14:10.852  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 14:14:10.852  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-23 14:14:10.853  5560  5606 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-23 14:14:10.853  5560  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 14:14:10.853  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 14:14:10.853  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-23 14:14:10.853  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 14:14:10.854  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 14:14:10.854  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:10.855  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:10.855  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:10.855  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:10.855  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:10.855  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 14:14:10.855  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 removed from the list
11-23 14:14:10.855  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:10.855  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 removed from the list
11-23 14:14:10.855  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:10.855  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.855  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.857  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.857  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.857  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:10.857  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:10.857  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:10.857  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:10.857  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:10.858  5560  5606 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-23 14:14:10.858  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:10.858  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:10.858  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 14:14:10.858  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:10.858  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:10.858  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:10.858  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:10.859  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:10.859  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:10.859  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.859  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.860  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:10.860  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.860  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.860  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:10.860  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:10.860  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:10.860  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:10.862  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemo,veAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 14:14:10.863  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 14:14:10.864  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 14:14:10.864  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-23 14:14:10.864  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 14:14:10.864  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:10.864  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:10.864  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:10.864  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:10.864  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:10.864  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:10.864  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 14:14:10.864  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:10.864  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:10.864  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.864  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.865  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.865  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:10.865  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.865  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:10.865  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:10.865  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:10.865  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
,11-23 14:14:10.865  5560  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 14:14:10.867  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 14:14:10.867  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 14:14:10.872  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 14:14:10.872  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:10.872  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:10.872  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 14:14:10.872  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 14:14:10.872  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 14:14:10.872  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 14:14:10.872  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 14:14:10.872  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 14:14:10.873  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 14:14:10.873  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 14:14:10.873  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 14:14:10.873  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-23 14:14:10.874  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 14:14:10.874  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 14:14:10.874  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 14:14:10.877  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 14:14:10.877  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-23 14:14:10.877  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 14:14:10.879  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 14:14:10.880  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.880  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 14:14:10.881  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 14:14:10.881  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 14:14:10.881  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 14:14:10.882  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-23 14:14:10.884  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-23 14:14:10.884  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:10.884  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 14:14:10.884  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 14:14:10.884  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 14:14:10.884  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 14:14:10.884  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.887  5560  5606 D BluetoothAdapter: STATE_ON
,11-23 14:14:10.887  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:14:10.889  4548  4562 D BtGatt.GattService: registerClient() - UUID=1074bc3b-33c6-4eb9-98b7-6938938e75f5
,11-23 14:14:10.892  4548  4610 D BtGatt.GattService: onClientRegistered() - UUID=1074bc3b-33c6-4eb9-98b7-6938938e75f5, clientIf=5
,11-23 14:14:10.893  5560  5607 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 14:14:10.894  4548  4755 D BtGatt.GattService: start scan with filters
,11-23 14:14:10.899  4548  4615 D BtGatt.ScanManager: handling starting scan
,11-23 14:14:10.899  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 14:14:10.899  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:10.899  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 14:14:10.899  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.899  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 14:14:10.899  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 14:14:10.900  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 14:14:10.900  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 14:14:10.900  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-23 14:14:10.900  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 14:14:10.900  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.900  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 14:14:10.900  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-23 14:14:10.900  4548  4615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:14:10.900  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.900  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 14:14:10.900  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.900  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:10.901  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 14:14:10.901  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 14:14:10.901  5560  5606 I io.jxcore.node.ConnectionHelper: start: OK
11-23 14:14:10.905  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 14:14:10.905  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 14:14:10.905  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 14:14:10.906  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 14:14:10.906  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 14:14:10.909  4548  4610 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 14:14:10.909  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 14:14:10.910  4548  4615 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 14:14:10.920  4548  4610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 14:14:10.920  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 14:14:10.920  4548  4615 D BtGatt.ScanManager: Starting BLE batch scan
,11-23 14:14:10.921  4548  4615 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 14:14:10.932  4548  4610 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 14:14:10.932  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 14:14:10.938  4548  4610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 14:14:10.938  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 14:14:11.408  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-23 14:14:11.408  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 14:14:11.408  5560  5560 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 14:14:11.637   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 14:14:11.640   931  2933 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-23 14:14:13.791   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:14:14.660   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 14:14:14.668   931  2933 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-23 14:14:14.792   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:14:15.793   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:14:15.905  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 14:14:15.905  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:15.906  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-23 14:14:15.906  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 14:14:15.906  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 14:14:15.906  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:15.906  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 14:14:15.906  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 14:14:15.906  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.906  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-23 14:14:15.907  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 14:14:15.907  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.907  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.908  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.908  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 14:14:15.908  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.909  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:14:15.909  4548  4562 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 14:14:15.910  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 14:14:15.911  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:14:15.912  4548  4611 D BtGatt.GattService: stopScan() - queue size =1
11-23 14:14:15.912  4548  4615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 14:14:15.913  4548  4561 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 14:14:15.913  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 14:14:15.913  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.913  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-23 14:14:15.914  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.914  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.914  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.914  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.914  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 14:14:15.915  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.915  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.915  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.915  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 14:14:15.915  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 14:14:15.916  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 14:14:15.916  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.918  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.918  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:14:15.918  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.918  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:15.919  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:15.919  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 14:14:15.919  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 14:14:15.919  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:15.919  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-23 14:14:15.919  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:15.920  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:15.920  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:15.920  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:14:15.920  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 14:14:15.920  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 14:14:15.920  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 14:14:15.920  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 14:14:15.921  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 14:14:15.921  4548  4548 D BtGatt.ScanManager: awakened up at time 85351
11-23 14:14:15.921  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 14:14:15.921  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 14:14:15.921  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 14:14:15.922  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 14:14:15.922  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:14:15.922  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 14:14:15.923  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 14:14:15.925  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 14:14:15.925  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 14:14:15.925  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 14:14:15.970  4548  4610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,11-23 14:14:15.970  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:15.970  4548  4610 D BtGatt.GattService: current time is 85401078278
11-23 14:14:15.971  4548  4610 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -89, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -84, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -95, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 64, -88, -14, -83, -127, 67, 1, -128, -87, 6, 0, 27, 2, 1, 26, 23, -1, 76, 0, 12, 14, 0, -25, 102, -108, 41, -12, 99, 29, -18, 13, 96, 124, -65, -103, 16, 2, 11, 0, 0, 37, -47, 14, -113, 116, -46, 1, -128, -87, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 64, -88, -14, -83, -127, 67, 1, -128, -97, 1, 0, 27, 2, 1, 26, 23, -1, 76, 0, 12, 14, 0, -24, 102, -96, -93, 34, 39, -90, 100, 68, 79, 37, 127, -126, 16, 2, 11, 0, 0]
11-23 14:14:15.972  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 14:14:15.973  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 14:14:15.973  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 14:14:15.973  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 14:14:15.973  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 14:14:15.973  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 26, 23, -1, 76, 0, 12, 14, 0, -25, 102, -108, 41, -12, 99, 29, -18, 13, 96, 124, -65, -103, 16, 2, 11, 0]
11-23 14:14:15.974 , 4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 14:14:15.974  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 26, 23, -1, 76, 0, 12, 14, 0, -24, 102, -96, -93, 34, 39, -90, 100, 68, 79, 37, 127, -126, 16, 2, 11, 0]
11-23 14:14:15.979  4548  4610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 14:14:15.979  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:15.979  4548  4615 D BtGatt.ScanManager: stopping BLe Batch
11-23 14:14:15.985  4548  4610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 14:14:15.985  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:15.985  4548  4615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 14:14:15.994  4548  4610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-23 14:14:15.995  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:15.995  4548  4610 D BtGatt.GattService: current time is 85425602564
11-23 14:14:15.995  4548  4610 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -87, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 14:14:15.995  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-23 14:14:16.038  4730  4775 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-23 14:14:16.039  4730  4730 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-23 14:14:16.042   931  3358 I ActivityManager: Killing 5190:org.codeaurora.ims/1001 (adj 15): empty #17
,11-23 14:14:16.423  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 14:14:16.794   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:14:17.795   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:14:18.795   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 14:14:20.921  5560  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 14:14:20.928  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 14:14:20.928  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 14:14:20.944  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 14:14:20.944  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:20.944  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:20.944  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 14:14:20.944  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 14:14:20.944  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 14:14:20.944  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 14:14:20.944  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 14:14:20.944  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 14:14:20.947  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 14:14:20.947  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 14:14:20.948  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 14:14:20.948  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 14:14:20.948  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 14:14:20.948  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 14:14:20.948  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 14:14:20.952  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:14:20.953  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 14:14:20.954  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 14:14:20.954  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 14:14:20.956  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:14:20.960  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:20.960  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 14:14:20.961  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 14:14:20.961  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 14:14:20.962  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 14:14:20.966  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:20.966  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 14:14:20.966  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 14:14:20.966  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 14:14:20.966  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-23 14:14:20.966  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.967  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:14:20.969  4548  4611 D BtGatt.GattService: registerClient() - UUID=0df249a8-8d17-4500-af45-6d255200d81e
11-23 14:14:20.970  4548  4610 D BtGatt.GattService: onClientRegistered() - UUID=0df249a8-8d17-4500-af45-6d255200d81e, clientIf=5
,11-23 14:14:20.970  5560  5570 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 14:14:20.971  4548  4562 D BtGatt.GattService: start scan with filters
11-23 14:14:20.974  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 14:14:20.975  4548  4615 D BtGatt.ScanManager: handling starting scan
,11-23 14:14:20.975  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:20.975  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 14:14:20.975  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.975  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 14:14:20.975  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 14:14:20.975  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.976  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 14:14:20.976  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 14:14:20.976  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.976  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.976  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.976  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.977  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 14:14:20.977  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.980  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:20.980  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 14:14:20.980  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.980  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.980  5560  5606 I io.jxcore.node.ConnectionHelper: start: OK
11-23 14:14:20.980  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.982  4548  4610 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 14:14:20.982  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:20.982  4548  4615 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 14:14:20.985  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-23 14:14:20.985  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.985  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.985  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 14:14:20.986  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 14:14:20.986  5560  5606 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 14:14:20.986  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:20.986  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 14:14:20.987  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 14:14:20.987  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 14:14:20.987  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:20.987  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 14:14:20.987  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 14:14:20.987  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.987  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 14:14:20.987  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 14:14:20.987  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.987  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.987  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.987  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 14:14:20.987  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.988  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:14:20.988  4548  4561 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 14:14:20.988  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 14:14:20.988  4548  4610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 14:14:20.988  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:20.989  4548  4615 D BtGatt.ScanManager: Starting BLE batch scan
11-23 14:14:20.989  4548  4615 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 14:14:20.989  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:14:20.989  4548  4755 D BtGatt.GattService: stopScan() - queue size =1
11-23 14:14:20.990  4548  4611 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 14:14:20.990  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 14:14:20.990  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.990  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 14:14:20.991  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.991  5560  56,06 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.991  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.991  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.991  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 14:14:20.991  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.991  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.991  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.991  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 14:14:20.991  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 14:14:20.992  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 14:14:20.992  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.993  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.993  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:14:20.993  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.993  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:20.993  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:14:20.993  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:14:20.993  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 14:14:20.993  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.994  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 14:14:20.994  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 14:14:20.994  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.994  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.994  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.994  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:14:20.994  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.994  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.995  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.995  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.995  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 14:14:20.996  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:20.996  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 14:14:20.996  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 14:14:20.996  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:20.996  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:20.996  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:20.996  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:20.996  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:20.996  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 14:14:21.000  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.000  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.000  4548  4610 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 14:14:21.000  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:21.001  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.001  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.001  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.001  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:21.001  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:21.001  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:21.002  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:21.002  5560  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 14:14:21.004  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 14:14:21.004  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 14:14:21.007  4548  4610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 14:14:21.007  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:21.008  4548  4615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 14:14:21.010  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 14:14:21.010  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:21.010  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:21.010  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 14:14:21.010  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 14:14:21.010  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 14:14:21.010  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 14:14:21.010  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 14:14:21.010  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 14:14:21.012  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 14:14:21.012  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 14:14:21.012  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 14:14:21.012  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 14:14:21.013  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 14:14:21.013  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 14:14:21.013  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 14:14:21.013  4548  4610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 14:14:21.013  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:21.014  4548  4610 E BtGatt.ContextMap: Context not found for ID 5
11-23 14:14:21.015  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 14:14:21.016  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 14:14:21.016  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 14:14:21.016  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 14:14:21.018  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 14:14:21.019  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.020  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 14:14:21.020  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 14:14:21.020  4548  4610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 14:14:21.020  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 14:14:21.020  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:21.020  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 14:14:21.021  4548  4615 D BtGatt.ScanManager: stopping BLe Batch
11-23 14:14:21.023  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.024  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 14:14:21.024  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 14:14:21.024  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 14:14:21.024  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 14:14:21.024  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.024  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:14:21.025  4548  4610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 14:14:21.025  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:21.026  4548  4615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 14:14:21.026  4548  4755 D BtGatt.GattService: registerClient() - UUID=fcc623fd-8cb7-453d-a8bf-d92aa15fd6ca
11-23 14:14:21.027  4548  4610 D BtGatt.GattService: onClientRegistered() - UUID=fcc623fd-8cb7-453d-a8bf-d92aa15fd6ca, clientIf=5
11-23 14:14:21.027  5560  5571 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 14:14:21.027  4548  4611 D BtGatt.GattService: start scan with filters
11-23 14:14:21.029  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 14:14:21.029  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.029  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 14:14:21.030  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.030  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 14:14:21.030  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 14:14:21.030  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 14:14:21.030  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 14:14:21.030  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 14:14:21.030  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 14:14:21.030  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 14:14:21.030  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 14:14:21.030  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 14:14:21.031  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 14:14:21.031  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.031  4548  4610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 14:14:21.031  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:21.032  4548  4615 D BtGatt.ScanManager: handling starting scan
11-23 14:14:21.033  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.033  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 14:14:21.033  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.033  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:21.033  5560  5606 I io.jxcore.node.ConnectionHelper: start: OK
11-23 14:14:21.033  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 14:14:21.036  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 14:14:21.036  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 14:14:21.036  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 14:14:21.036  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 14:14:21.038  4548  4610 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 14:14:21.038  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:21.038  4548  4615 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 14:14:21.042  4548  4610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 14:14:21.042  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:21.042  4548  4615 D BtGatt.ScanManager: Starting BLE batch scan
11-23 14:14:21.042  4548  4615 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 14:14:21.051  4548  4610 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 14:14:21.051  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:21.055  4548  4610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 14:14:21.055  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 14:14:21.537  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-23 14:14:21.537  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 14:14:21.538  5560  5560 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 14:14:23.730   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 14:14:26.034  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 14:14:26.034  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:26.034  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 14:14:26.035  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 14:14:26.035  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-23 14:14:26.035  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:26.035  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 14:14:26.035  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 14:14:26.035  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.036  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-23 14:14:26.036  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-23 14:14:26.036  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:26.037  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.037  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.037  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 14:14:26.037  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.039  5560  5606 D BluetoothAdapter: STATE_ON
,11-23 14:14:26.040  4548  4611 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 14:14:26.040  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 14:14:26.042  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:14:26.042  4548  4615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 14:14:26.043  4548  4562 D BtGatt.GattService: stopScan() - queue size =1
11-23 14:14:26.045  4548  4755 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-23 14:14:26.046  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 14:14:26.046  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.046  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 14:14:26.047  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.047  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.047  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.047  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.047  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-23 14:14:26.048  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.048  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.048  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.048  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 14:14:26.048  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 14:14:26.049  4548  4548 D BtGatt.ScanManager: awakened up at time 95479
11-23 14:14:26.050  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 14:14:26.050  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.052  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.053  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:14:26.053  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.053  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:26.053  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:14:26.054  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:14:26.054  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 14:14:26.054  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-23 14:14:26.054  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 14:14:26.054  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 14:14:26.054  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 14:14:26.054  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 14:14:26.054  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 14:14:26.054  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:14:26.055  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-23 14:14:26.055  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 14:14:26.056  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 14:14:26.056  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 14:14:26.056  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 14:14:26.057   931  3140 I ActivityManager: Killing 5227:com.android.settings/1000 (adj 15): empty #17
,11-23 14:14:26.096  4548  4610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
,11-23 14:14:26.096  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:26.096  4548  4610 D BtGatt.GattService: current time is 95527330393
11-23 14:14:26.097  4548  4610 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -86, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -84, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 64, -88, -14, -83, -127, 67, 1, -128, -98, 97, 0, 27, 2, 1, 26, 23, -1, 76, 0, 12, 14, 0, -24, 102, -96, -93, 34, 39, -90, 100, 68, 79, 37, 127, -126, 16, 2, 3, 0, 0, 64, -88, -14, -83, -127, 67, 1, -128, -98, 72, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -24, 102, -96, -93, 34, 39, -90, 100, 68, 79, 37, 127, -126, 0, 71, -122, -77, 84, 69, -12, 1, -128, -97, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -91, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -87, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 64, -88, -14, -83, -127, 67, 1, -128, -95, 1, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -23, 102, -25, 60, -62, 55, -97, -91, 61, 76, 29, -119, -38, 0]
11-23 14:14:26.097  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 14:14:26.097  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 14:14:26.097  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 26, 23, -1, 76, 0, 12, 14, 0, -24, 102, -96, -93, 34, 39, -90, 100, 68, 79, 37, 127, -126, 16, 2, 3, 0]
11-23 14:14:26.097  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -24, 102, -96, -93, 34, 39, -90, 100, 68, 79, 37, 127, -126]
,11-23 14:14:26.098  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 14:14:26.098  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 14:14:26.098  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 14:14:26.098  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 14:14:26.098  4548  4610 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -23, 102, -25, 60, -62, 55, -97, -91, 61, 76, 29, -119, -38]
,11-23 14:14:26.104  4548  4610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 14:14:26.104  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:26.104  4548  4615 D BtGatt.ScanManager: stopping BLe Batch
,11-23 14:14:26.110  4548  4610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 14:14:26.110  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:14:26.110  4548  4615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 14:14:26.116  4548  4610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 14:14:26.116  4548  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 14:14:26.555  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
11-23 14:14:26.556  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:26.556  5560  5560 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 14:14:26.757   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 14:14:29.580   931  5298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=99010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:14:29.783   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 14:14:31.055  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:31.055  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 14:14:31.055  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:31.056  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 14:14:31.056  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 14:14:31.056  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 14:14:31.056  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 14:14:31.057  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
,11-23 14:14:31.057  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.057  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
,11-23 14:14:31.057  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:31.057  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 14:14:31.060  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.060  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:31.064  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.064  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:31.064  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.064  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 14:14:31.065  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 14:14:31.065  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.065  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
,11-23 14:14:31.067  5560  5606 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-23 14:14:31.068  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:31.069  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:31.069  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:31.070  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 14:14:31.070  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:31.070  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:31.070  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.070  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.070  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 14:14:31.071  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.071  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.073  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.074  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:31.074  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.074  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:31.074  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:31.074  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 14:14:31.074  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.075  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 14:14:31.075  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:31.076  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 14:14:31.076  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:31.076  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:31.076  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:31.076  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:31.076  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.076  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.076  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:31.076  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.076  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.078  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.078  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.078  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.078  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:31.078  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:31.079  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.079  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.079  5560  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-23 14:14:31.080  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 14:14:31.080  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:31.080  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:31.080  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:31.080  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:31.080  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:31.080  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.080  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
,11-23 14:14:31.080  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:31.081  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.081  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:31.082  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.082  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.082  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.082  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:31.082  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:31.082  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 14:14:31.083  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.083  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-23 14:14:31.084  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:31.084  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:31.084  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:31.084  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 14:14:31.084  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:31.084  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:31.084  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 14:14:31.084  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.084  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:31.084  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.084  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:31.086  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.086  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.086  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.086  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:31.086  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:31.086  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.086  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.087  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 14:14:31.087  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 14:14:31.088  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 14:14:31.088  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 14:14:31.088  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 14:14:31.088  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 14:14:31.088  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 14:14:31.088  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 14:14:31.088  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 14:14:31.088  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:31.088  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:31.088  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:31.088  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:31.089  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 14:14:31.089  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:31.089  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.089  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.089  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:31.089  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.089  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.090  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.091  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.091  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.091  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:31.091  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:31.091  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 14:14:31.091  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.092  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 14:14:31.092  5560  5606 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 14:14:31.092  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 14:14:31.095  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 14:14:31.095  5560  5606 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-23 14:14:31.095  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 14:14:31.095  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 14:14:31.095  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-23 14:14:31.095  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 14:14:31.095  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 14:14:31.095  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 14:14:31.095  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 14:14:31.096  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 14:14:31.096  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 14:14:31.096  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 14:14:31.096  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 14:14:31.096  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 14:14:31.096  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 14:14:31.096  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-23 14:14:31.096  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 14:14:31.096  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 14:14:31.097  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-23 14:14:31.097  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,11-23 14:14:31.098  5560  5606 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 14:14:31.098  5560  5606 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-23 14:14:31.098  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 14:14:31.098  5560  5606 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-23 14:14:31.098  5560  5606 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-23 14:14:31.098  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 14:14:31.098  5560  5606 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 14:14:31.098  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-23 14:14:31.102  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-23 14:14:31.103  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-23 14:14:31.103  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-23 14:14:31.104  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-23 14:14:31.104  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-23 14:14:31.104  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-23 14:14:31.104  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 14:14:31.104  5560  5606 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-23 14:14:31.105  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:31.105  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 14:14:31.105  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:31.105  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:31.105  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:31.105  5560  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 122)
11-23 14:14:31.105  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-23 14:14:31.105  5560  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-23 14:14:31.106  5560  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-23 14:14:31.106  5560  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,11-23 14:14:31.106  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:31.106  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.106  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.106  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:31.106  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.107  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.108  5560  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 122
11-23 14:14:31.108  5560  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,11-23 14:14:31.109  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.109  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.109  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.109  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:31.109  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:31.109  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.109  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.110  5560  5606 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-23 14:14:31.111  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:31.111  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:31.111  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 14:14:31.111  5560  5613 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-23 14:14:31.112  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:31.112  5560  5613 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 14:14:31.112  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:31.112  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
,11-23 14:14:31.112  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.112  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.112  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:31.112  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.112  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:31.112  4611  4611 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31632]" dev="sockfs" ino=31632 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 14:14:31.112  4611  4611 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31632]" dev="sockfs" ino=31632 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 14:14:31.114  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.114  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.114  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:31.114  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:31.114  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:31.114  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.114  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.115  5560  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-23 14:14:31.115  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:31.115  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:31.115  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:31.115  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:31.115  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:31.115  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
,11-23 14:14:31.115  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.115  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.115  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:31.115  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.115  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.118  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.118  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.119  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.119  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:31.119  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 14:14:31.119  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.119  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
,11-23 14:14:31.121  5560  5606 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-23 14:14:31.121  5560  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-23 14:14:31.122  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-23 14:14:31.122  5560  5606 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-23 14:14:31.122  5560  5606 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 14:14:31.122  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-23 14:14:31.122  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 14:14:31.122  5560  5606 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,11-23 14:14:31.122  5560  5606 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 14:14:31.122  5560  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 14:14:31.122  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 14:14:31.122  5560  5606 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-23 14:14:31.122  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:31.122  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:31.122  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:31.122  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:31.122  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 14:14:31.122  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:31.123  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.123  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.123  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:31.123  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.123  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.124  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.124  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.124  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:31.124  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:31.124  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:31.124  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.124  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.125  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 14:14:31.125  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:31.125  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:31.125  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:31.125  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:31.125  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 14:14:32.824   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 14:14:36.126  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:36.126  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
,11-23 14:14:36.127  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:36.127  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:36.127  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:36.127  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 14:14:36.127  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:36.127  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:36.128  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:36.128  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:36.128  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:36.128  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:36.128  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:36.129  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:36.129  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.129  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:36.134  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:36.134  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:36.135  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.135  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:36.135  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 14:14:36.135  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:36.136  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:36.138  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-23 14:14:36.139  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 14:14:36.140  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 14:14:36.147  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-23 14:14:36.152  4562  4562 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32835]" dev="sockfs" ino=32835 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 14:14:36.152  4562  4562 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32835]" dev="sockfs" ino=32835 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 14:14:36.149  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-23 14:14:36.149  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-23 14:14:36.149  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-23 14:14:36.149  5560  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-23 14:14:36.149  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-23 14:14:36.150  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 14:14:36.150  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-23 14:14:36.150  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:36.150  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-23 14:14:36.150  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-23 14:14:36.150  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-23 14:14:36.151  5560  5615 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 14:14:36.151  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 14:14:36.151  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 14:14:36.151  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-23 14:14:36.152  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:36.152  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-23 14:14:36.152  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:36.152  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 14:14:36.152  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.152  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 14:14:36.152  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 14:14:36.152  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.154  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:36.154  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:14:36.154  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.154  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.155  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:36.155  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:14:36.155  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:36.155  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:14:36.155  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:36.155  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:14:36.155  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:36.155  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:36.155  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-23 14:14:36.155  5560  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-23 14:14:36.155  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:36.156  5560  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-23 14:14:36.156  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:36.156  5560  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-23 14:14:36.156  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:36.156  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 14:14:36.156  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.157  5560  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-23 14:14:36.157  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.157  5560  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:36.158  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.159  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.159  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.159  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 14:14:36.159  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:36.159  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:36.159  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:36.161  5560  5606 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-23 14:14:36.161  5560  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 14:14:36.161  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 14:14:36.162  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 14:14:36.162  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-23 14:14:36.162  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:14:36.162  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:36.162  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:36.162  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:36.162  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:36.163  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:36.163  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 14:14:36.163  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:36.163  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:36.163  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.163  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.165  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.165  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:36.165  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.165  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:36.165  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:36.165  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:36.166  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
,11-23 14:14:36.171  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 14:14:36.172  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:36.172  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:36.172  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:36.172  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:36.172  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
11-23 14:14:36.172  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 14:14:36.172  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:36.172  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:36.173  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.173  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.174  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.174  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:36.175  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.175  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:36.175  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:36.175  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:36.175  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:36.176  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 14:14:36.176  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:14:36.176  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:14:36.176  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:14:36.176  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:14:36.177  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1a8e7 not in the list
,11-23 14:14:36.177  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:36.177  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
11-23 14:14:36.177  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:14:36.177  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.177  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.180  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:14:36.180  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.180  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:14:36.180  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:14:36.180  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:14:36.180  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:14:36.180  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b957c94 not in the list
,11-23 14:14:36.183  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-23 14:14:36.183  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 14:14:36.183  5560  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-23 14:14:36.183  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-23 14:14:36.183  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-23 14:14:36.183  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-23 14:14:36.186  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-23 14:14:36.186  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-23 14:14:36.186  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-23 14:14:36.187  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-23 14:14:36.187  5560  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-23 14:14:36.187  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 14:14:36.187  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-23 14:14:36.187  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-23 14:14:36.187  5560  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-23 14:14:36.188  5560  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-23 14:14:36.188  5560  5606 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-23 14:14:36.188  5560  5606 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-23 14:14:36.188  5560  5606 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-23 14:14:36.188  5560  5606 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-23 14:14:36.190  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 14:14:36.190  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@de485ad added. We now have 3 listener(s)
11-23 14:14:36.190  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 14:14:36.192  5560  5606 D BluetoothAdapter: enable(): BT is already enabled..!
11-23 14:14:36.192   931  3670 D WifiService: setWifiEnabled: true pid=5560, uid=10077
,11-23 14:14:36.192   931  3670 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 14:14:36.243  4548  4742 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-23 14:14:36.243  4548  4744 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-23 14:14:36.243  5560  5613 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
,11-23 14:14:36.243  5560  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-23 14:14:36.243  5560  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 122)
,11-23 14:14:36.655  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 14:14:41.197  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 14:14:41.198  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd5d0e2 added. We now have 4 listener(s)
11-23 14:14:41.198  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 14:14:41.211  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 14:14:41.212  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd5d0e2 removed from the list
,11-23 14:14:41.212  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 14:14:41.213  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 14:14:41.214  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7afc73 added. We now have 4 listener(s)
,11-23 14:14:41.214  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 14:14:41.217  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 14:14:41.218  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7afc73 removed from the list
,11-23 14:14:41.218  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 14:14:41.221  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 14:14:41.222  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13ab730 added. We now have 4 listener(s)
11-23 14:14:41.222  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 14:14:41.225   931  3140 D WifiService: setWifiEnabled: false pid=5560, uid=10077
11-23 14:14:41.226   931  3140 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 14:14:41.235   931  2931 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-23 14:14:41.236   931  2931 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-23 14:14:41.236   931  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 14:14:41.236   931  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 14:14:41.243  4548  4606 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 14:14:41.243  4548  4606 D BluetoothAdapterProperties: Setting state to 13
,11-23 14:14:41.243  4548  4606 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 14:14:41.244  4548  4606 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 14:14:41.245  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 14:14:41.245  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 14:14:41.246  4548  4606 I BluetoothAdapterState: Entering PendingCommandState
11-23 14:14:41.248  4548  4548 D BluetoothMapService: onReceive
11-23 14:14:41.248  4548  4548 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 14:14:41.249  4548  4548 D BluetoothMapService: STATE_TURNING_OFF
,11-23 14:14:41.249  4548  4548 D BluetoothMapService: MAP Service closeService in
11-23 14:14:41.249  4548  4548 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 14:14:41.249  4548  4548 D ObexServerSockets0: shutdown(block = true)
11-23 14:14:41.250  4548  4548 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 14:14:41.250  4548  4548 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 14:14:41.250  4548  4757 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-23 14:14:41.251  4548  4744 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 14:14:41.251  4548  4758 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-23 14:14:41.254  4548  4548 I BtOppRfcommListener: stopping Accept Thread
11-23 14:14:41.257   931  5299 D DhcpClient: Clearing IP address
11-23 14:14:41.257  4548  5250 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 14:14:41.257   510   925 D CommandListener: Clearing all IP addresses on wlan0
11-23 14:14:41.257  4548  5250 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-23 14:14:41.265   510   925 D CommandListener: Setting iface cfg
,11-23 14:14:41.273  3527  5350 V NativeCrypto: Read error: ssl=0x7f66885e00: I/O error during system call, Connection timed out
,11-23 14:14:41.275  3527  5350 V NativeCrypto: SSL shutdown failed: ssl=0x7f66885e00: I/O error during system call, Broken pipe
,11-23 14:14:41.276   931  5300 D DhcpClient: Receive thread stopped
11-23 14:14:41.277   931  3542 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-23 14:14:41.277   931  5297 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-23 14:14:41.280   931  5297 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-23 14:14:41.280   931  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-23 14:14:41.281   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-23 14:14:41.282   931  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 14:14:41.291   931   944 I ActivityManager: Start proc 5619:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-23 14:14:41.295  4548  4610 D BluetoothAdapterProperties: Scan Mode:20
,11-23 14:14:41.292   931  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 14:14:41.295   931  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-23 14:14:41.296  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:41.296  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 14:14:41.296  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:41.296  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:41.296  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 14:14:41.296  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 14:14:41.296  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 14:14:41.296  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - SSID name: <unknown ssid>
11-23 14:14:41.296  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 14:14:41.296  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 14:14:41.297  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:41.297  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: <unknown ssid>
11-23 14:14:41.297  4548  4606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-23 14:14:41.297  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 14:14:41.298   562   562 E Parcel  : Reading a NULL string not supported here.
,11-23 14:14:41.300   931   931 D RttService: SCAN_AVAILABLE : 1
,11-23 14:14:41.300   931  2999 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 14:14:41.301  4548  4548 D HeadsetService: Received stop request...Stopping profile...
11-23 14:14:41.303  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:41.303  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 14:14:41.303  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:41.303  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:41.303  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 14:14:41.303  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 14:14:41.303  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 14:14:41.303  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 14:14:41.303  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 14:14:41.303  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 14:14:41.303   931   931 D BluetoothHeadset: Proxy object disconnected
11-23 14:14:41.303   931   931 D BluetoothHeadset: Proxy object disconnected
,11-23 14:14:41.303   931   931 D BluetoothHeadset: Proxy object disconnected
11-23 14:14:41.303  3061  3074 D BluetoothHeadset: Proxy object disconnected
11-23 14:14:41.304  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 14:14:41.304  3709  4065 D BluetoothHeadset: Proxy object disconnected
11-23 14:14:41.304  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 14:14:41.304  4548  4548 D A2dpService: Received stop request...Stopping profile...
11-23 14:14:41.305  4548  4748 D A2dpStateMachine: Exit Disconnected: -1
11-23 14:14:41.305  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 14:14:41.307  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:14:41.309   931   931 D BluetoothA2dp: Proxy object disconnected
,11-23 14:14:41.311  4548  4548 D HidService: Received stop request...Stopping profile...
11-23 14:14:41.311  4548  4548 D HidService: Stopping Bluetooth HidService
11-23 14:14:41.311   931  2933 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-23 14:14:41.312  4548  4548 V BluetoothAdapterState: isTurningOff()=true
,11-23 14:14:41.312  4548  4548 V BluetoothAdapterState: isTurningOn()=false
,11-23 14:14:41.312  4548  4548 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:41.312  4548  4548 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:14:41.313  3678  3819 W QCNEJ   : |CORE| network lost: 100
11-23 14:14:41.314  3678  3819 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-23 14:14:41.314  4548  4548 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 14:14:41.314  4548  4548 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 14:14:41.314  4548  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 14:14:41.315  4548  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 14:14:41.315  4548  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 14:14:41.315  4548  4610 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 14:14:41.315  4548  4548 D HealthService: Received stop request...Stopping profile...
11-23 14:14:41.315  4548  4610 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 14:14:41.319  4548  4548 D PanService: Received stop request...Stopping profile...
11-23 14:14:41.321  4548  4548 D BluetoothMapService: Received stop request...Stopping profile...
11-23 14:14:41.321  4548  4548 D BluetoothMapService: stop()
11-23 14:14:41.321  3061  3061 D HeadsetProfile: Bluetooth service disconnected
11-23 14:14:41.321   931  2931 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-23 14:14:41.322  3061  3061 D BluetoothA2dp: Proxy object disconnected
11-23 14:14:41.322  3061  3061 D BluetoothInputDevice: Proxy object disconnected
11-23 14:14:41.322  3061  3061 D HidProfile: Bluetooth service disconnected
11-23 14:14:41.322  4548  4548 D BluetoothMapAppObserver: deinitObservers()
11-23 14:14:41.322  4548  4548 D BluetoothMapAppObserver: removeReceiver()
,11-23 14:14:41.324  3061  3061 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 14:14:41.324  3061  3061 D PanProfile: Bluetooth service disconnected
11-23 14:14:41.324  4548  4548 V BluetoothAdapterState: isTurningOff()=true
11-23 14:14:41.324  3061  3061 D BluetoothMap: Proxy object disconnected
11-23 14:14:41.324  3061  3061 D MapProfile: Bluetooth service disconnected
,11-23 14:14:41.324  4548  4548 V BluetoothAdapterState: isTurningOn()=false
11-23 14:14:41.324  4548  4548 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:41.324  4548  4548 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 14:14:41.325  4548  4610 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 14:14:41.325  4548  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 14:14:41.326  4548  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 14:14:41.326  4548  4742 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 14:14:41.326  4548  4742 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-23 14:14:41.326  4548  4742 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 14:14:41.326  4548  4742 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 14:14:41.326  4548  4548 D SapService: Received stop request...Stopping profile...
,11-23 14:14:41.326  4548  4548 V SapService: stop()
,11-23 14:14:41.327  4548  4548 V BluetoothAdapterState: isTurningOff()=true
11-23 14:14:41.327  4548  4548 V BluetoothAdapterState: isTurningOn()=false
11-23 14:14:41.327  4548  4548 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:41.328  4548  4548 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:14:41.328   931  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 14:14:41.328  4548  4548 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 14:14:41.328  4548  4548 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-23 14:14:41.328  4548  4610 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 14:14:41.328  4548  4548 V BluetoothAdapterState: isTurningOff()=true
11-23 14:14:41.328  4548  4548 V BluetoothAdapterState: isTurningOn()=false
11-23 14:14:41.328  4548  4548 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:41.328  4548  4548 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:14:41.328  4548  4548 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 14:14:41.328  4548  4610 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 14:14:41.329  4548  4548 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 14:14:41.329  4548  4548 V BluetoothAdapterState: isTurningOff()=true
11-23 14:14:41.329  4548  4548 V BluetoothAdapterState: isTurningOn()=false
,11-23 14:14:41.329  4548  4548 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:41.329  4548  4548 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:14:41.329  4548  4548 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 14:14:41.330  4548  4548 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 14:14:41.331  4548  4548 D BluetoothMapService: MAP Service closeService in
11-23 14:14:41.331  4548  4548 V BluetoothAdapterState: isTurningOff()=true
11-23 14:14:41.331  4548  4548 V BluetoothAdapterState: isTurningOn()=false
11-23 14:14:41.331  4548  4548 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:41.331  4548  4548 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:14:41.331  4548  4548 D BluetoothMapService: cleanup()
11-23 14:14:41.331  4548  4548 D BluetoothMapService: MAP Service closeService in
11-23 14:14:41.331  4548  4548 V BluetoothAdapterState: isTurningOff()=true
11-23 14:14:41.331  4548  4548 V BluetoothAdapterState: isTurningOn()=false
11-23 14:14:41.332  4548  4548 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:41.332  4548  4548 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:14:41.332  4548  4606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 14:14:41.332  4548  4606 D BluetoothAdapterProperties: Setting state to 15
11-23 14:14:41.332  4548  4606 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-23 14:14:41.332  4548  4606 I BluetoothAdapterState: Entering BleOnState
11-23 14:14:41.333  3709  3737 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 14:14:41.333  3061  5559 D BluetoothMap: onBluetoothStateChange: up=false
11-23 14:14:41.334   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 14:14:41.334  3061  3074 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 14:14:41.335  5619  5619 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-23 14:14:41.335  3061  3929 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-23 14:14:41.336  3061  3072 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 14:14:41.337   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 14:14:41.337   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 14:14:41.337  3061  5559 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 14:14:41.338  3061  3074 D BluetoothPan: onBluetoothStateChange on: false
11-23 14:14:41.338   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 14:14:41.339  4548  4606 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 14:14:41.339  4548  4606 D BluetoothAdapterProperties: Setting state to 16
11-23 14:14:41.339  4548  4606 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 14:14:41.339  4548  4606 D BluetoothAdapterProperties: onBleDisable
11-23 14:14:41.340  4548  4606 I BluetoothAdapterState: Entering PendingCommandState
,11-23 14:14:41.340  4548  4607 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 14:14:41.341  4548  4610 D BluetoothAdapterProperties: Scan Mode:20
,11-23 14:14:41.343  4548  4742 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 14:14:41.343  4548  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 14:14:41.344  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:41.344  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 14:14:41.344  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:41.344  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:41.344  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 14:14:41.344  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 14:14:41.344  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 14:14:41.344  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 14:14:41.344  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 14:14:41.344  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 14:14:41.347  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:14:41.347   510   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 14:14:41.357  5619  5619 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 14:14:41.365   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@75391ce:true
,11-23 14:14:41.365  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 14:14:41.375   510   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-23 14:14:41.375   510   925 D CommandListener: Clearing all IP addresses on wlan0
,11-23 14:14:41.377   931  2933 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-23 14:14:41.377   931  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 14:14:41.378   931   948 D Tethering: MasterInitialState.processMessage what=3
,11-23 14:14:41.380   931  2931 D DhcpClient: doQuit
11-23 14:14:41.380   931  2931 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 14:14:41.381  5204  5204 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7d5fa97 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-23 14:14:41.381   931  5299 D DhcpClient: onQuitting
,11-23 14:14:41.381  3390  3390 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 14:14:41.382  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:14:41.384  4890  4912 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 14:14:41.384  4890  4912 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 14:14:41.384  4890  4912 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 14:14:41.384  4890  4912 E SarControlService: no key has been found,reset the power
11-23 14:14:41.384  4890  4934 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 14:14:41.384  4890  4934 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 14:14:41.384  4890  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 14:14:41.385  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 14:14:41.385  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:41.385  4925  4925 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 14:14:41.385  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 14:14:41.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:41.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:41.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 14:14:41.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 14:14:41.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 14:14:41.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 14:14:41.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 14:14:41.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 14:14:41.386  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:41.386  3909  3909 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-23 14:14:41.386  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 14:14:41.387  4890  4934 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 14:14:41.387  4890  4934 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 14:14:41.390  4890  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 14:14:41.391  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 14:14:41.391  4925  4925 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 14:14:41.394  4925  4939 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@45f99f5 HexData = [00000000ea03000000000000ffffffff]
11-23 14:14:41.394  4925  4939 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 14:14:41.394  4925  4939 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-23 14:14:41.394  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 14:14:41.395  4890  4901 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-23 14:14:41.400  4925  4939 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@45f99f5 HexData = [00000000eb03000000000000ffffffff]
,11-23 14:14:41.400  4925  4939 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-23 14:14:41.400  4925  4939 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-23 14:14:41.401  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 14:14:41.401  4890  4902 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-23 14:14:41.408  5619  5619 D LocalBluetoothProfileManager: Adding local MAP profile
,11-23 14:14:41.410  5619  5619 D BluetoothMap: Create BluetoothMap proxy object
,11-23 14:14:41.418  5619  5619 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-23 14:14:41.423  5619  5619 D DockEventReceiver: finishStartingService: stopping service
,11-23 14:14:41.426  3390  3390 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 14:14:41.426  5619  5619 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 14:14:41.430   510   925 E Netd    : netlink response contains error (No such file or directory)
,11-23 14:14:41.431   931  2933 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-23 14:14:41.431  3390  3390 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-23 14:14:41.431  5619  5619 D DockEventReceiver: finishStartingService: stopping service
,11-23 14:14:41.432  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 14:14:41.435   931  3358 I ActivityManager: Killing 5325:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-23 14:14:41.453  3784  3784 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 14:14:41.456  3784  3784 D SystemUpdateService: onCreate
,11-23 14:14:41.459  3784  3784 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 14:14:41.466  3784  3784 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 14:14:41.470  3784  5323 I iu.UploadsManager: num queued entries: 0
,11-23 14:14:41.470  3784  5323 I iu.UploadsManager: num updated entries: 0
11-23 14:14:41.471  3784  5323 I iu.SyncManager: NEXT; no task
,11-23 14:14:41.472  3784  5644 I SystemUpdateService: active receiver: enabled
,11-23 14:14:41.476  3784  3784 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 14:14:41.477  3390  3390 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 14:14:41.478  3784  3784 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 14:14:41.480  3784  5644 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 14:14:41.482  3784  5644 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 14:14:41.482  3784  5644 I SystemUpdateService: now status is 0 (complete)
11-23 14:14:41.482  3784  5644 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 14:14:41.482  3784  5644 I SystemUpdateService: file has been verified
11-23 14:14:41.482  3784  5644 I SystemUpdateService: OTA package size = 21989297
,11-23 14:14:41.489  3784  5644 I SystemUpdateService: showing system update notification
11-23 14:14:41.489   931  3670 I ActivityManager: Start proc 5646:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-23 14:14:41.496  3390  3390 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 14:14:41.503   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 14:14:41.504  3784  3784 D SystemUpdateService: onDestroy
,11-23 14:14:41.525  5646  5646 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-23 14:14:41.528  5646  5646 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 14:14:41.536  5646  5646 D SprintDMHelper: simOperator: 
11-23 14:14:41.536  5646  5646 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 14:14:41.548  4548  4610 I bt_hci  : shut_down
,11-23 14:14:41.551  4246  5658 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-23 14:14:41.551  4548  4617 D bt_hwcfg: hw_epilog_process
11-23 14:14:41.552  4548  4617 I bt_vendor: low_power_mode_cb
11-23 14:14:41.553   931  3791 I ActivityManager: Killing 5204:com.google.android.music:main/u0a59 (adj 15): empty #17
11-23 14:14:41.555  4548  4617 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-23 14:14:41.555  4548  4617 I bt_vendor: epilog_cb
11-23 14:14:41.555  4548  4617 I bt_hci  : epilog_finished_callback
11-23 14:14:41.581   931  3791 I ActivityManager: Start proc 5659:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-23 14:14:41.582  4548  4610 I bt_hci_h4: hal_close
11-23 14:14:41.583  4548  4610 I bt_userial_vendor: device fd = 54 close
,11-23 14:14:41.601   931  2931 D wifi    : In wifi stop Hal
,11-23 14:14:41.601   931  2931 D wifi    : halHandle = 0x7f6505d980, mVM = 0x7f8168d140, mCls = 0x100a02
,11-23 14:14:41.601   931  3389 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 14:14:41.601   931  3389 D WifiHAL : Got a signal to exit!!!
11-23 14:14:41.601   931  3389 I WifiHAL : Exit wifi_event_loop
,11-23 14:14:41.602  4246  4246 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 14:14:41.602   931  2931 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 14:14:41.602   931  2931 E WifiHAL : Event processing terminated
11-23 14:14:41.603   931  2931 D wifi    : In wifi cleaned up handler
11-23 14:14:41.603   931  2931 I WifiHAL : Internal cleanup completed
11-23 14:14:41.604  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 14:14:41.605  4035  4175 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 14:14:41.616  5659  5659 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-23 14:14:41.623   931  3389 D wifi    : set interface wlan0 flags (DOWN)
,11-23 14:14:41.623   931  3542 I ActivityManager: Killing 5397:com.android.defcontainer/u0a7 (adj 15): empty #17
11-23 14:14:41.623   931  2931 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 14:14:41.688  4548  4607 D bt_stack_manager: event_shut_down_stack finished.
,11-23 14:14:41.688  4548  4606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 14:14:41.689   510   925 E Netd    : netlink response contains error (No such file or directory)
,11-23 14:14:41.690  4548  4606 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-23 14:14:41.690  4548  4548 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 14:14:41.691  4548  4548 D BtGatt.GattService: Received stop request...Stopping profile...
11-23 14:14:41.691  4548  4548 D BtGatt.GattService: stop()
11-23 14:14:41.691  4548  4548 D BtGatt.AdvertiseManager: advertise clients cleared
11-23 14:14:41.692  4548  4548 V BluetoothAdapterState: isTurningOff()=false
11-23 14:14:41.693  4548  4548 V BluetoothAdapterState: isTurningOn()=false
11-23 14:14:41.693  4548  4548 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 14:14:41.693  4548  4548 V BluetoothAdapterState: isBleTurningOff()=true
11-23 14:14:41.693  4548  4606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 14:14:41.693  4548  4606 D BluetoothAdapterProperties: Setting state to 10
11-23 14:14:41.693  4548  4606 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 14:14:41.694  4548  4606 I BluetoothAdapterState: Entering OffState
11-23 14:14:41.694   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 14:14:41.700  4548  4548 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 14:14:41.700  4548  4548 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 14:14:41.700  4548  4548 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 14:14:41.702  4548  4607 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 14:14:41.705  4548  4548 I art     : System.exit called, status: 0
,11-23 14:14:41.705  4548  4548 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 14:14:41.728   931  3541 I ActivityManager: Process com.android.bluetooth (pid 4548) has died
,11-23 14:14:41.828   931   948 D Tethering: InitialState.processMessage what=4
,11-23 14:14:41.834   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 14:14:43.796   565   565 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 14:14:43.797   565   565 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 14:14:46.300   931  3670 D WifiService: setWifiEnabled: true pid=5560, uid=10077
11-23 14:14:46.300   931  3670 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 14:14:46.310   510   925 D SoftapController: Softap fwReload - Ok
,11-23 14:14:46.317   510   925 D CommandListener: Setting iface cfg
11-23 14:14:46.317   510   925 D CommandListener: Trying to bring down wlan0
,11-23 14:14:46.319   510   925 D CommandListener: Clearing all IP addresses on wlan0
,11-23 14:14:46.329   931  2931 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 14:14:46.915   931  2931 D wifi    : set interface wlan0 flags (UP)
,11-23 14:14:46.922   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 14:14:46.922   931  2931 I WifiHAL : Initializing wifi
,11-23 14:14:46.924   931  2931 I WifiHAL : Creating socket
,11-23 14:14:46.931   931  2931 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-23 14:14:46.931   931  2931 D wifi    : Did set static halHandle = 0x7f6505d980
11-23 14:14:46.931   931  2931 D wifi    : halHandle = 0x7f6505d980, mVM = 0x7f8168d140, mCls = 0x19a6
,11-23 14:14:46.931   931  2931 D wifi    : array field set
11-23 14:14:46.932   931  2931 I WifiNative-HAL: interface[0] = wlan0
11-23 14:14:46.933   931  5684 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547155728768
11-23 14:14:46.934   931  5684 D wifi    : waitForHalEvents called, vm = 0x7f8168d140, obj = 0x19a6, env = 0x7f66a98fc0
,11-23 14:14:46.998  5685  5685 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 14:14:47.035   931  2931 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 14:14:47.040  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:14:47.065  5685  5685 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 14:14:47.101  5685  5685 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 14:14:47.101  5685  5685 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 14:14:47.112   931  2931 D WifiConfigStore: Loading config and enabling all networks 
,11-23 14:14:47.112  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:47.112  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 14:14:47.112  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:47.112  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:47.112  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 14:14:47.112  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 14:14:47.112  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 14:14:47.112  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 14:14:47.112  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 14:14:47.112  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 14:14:47.112  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:47.112  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 14:14:47.144   931  2931 D WifiConfigStore: loaded 0 passpoint configs
,11-23 14:14:47.145   931  2931 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-23 14:14:47.145   931  2931 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-23 14:14:47.146   931  2931 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-23 14:14:47.147   931  2931 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-23 14:14:47.147   931  2931 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-23 14:14:47.148   931  2931 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-23 14:14:47.149   931  2931 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-23 14:14:47.149   931  2931 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-23 14:14:47.149   931  2931 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-23 14:14:47.149   931  2931 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-23 14:14:47.149   931  2931 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-23 14:14:47.149   931  2931 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-23 14:14:47.153   931  2931 D WifiNative-HAL: Setting external_sim to 1
,11-23 14:14:47.153  4246  4246 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 14:14:47.153   931  2931 D wifi    : setting dfs flag to true, 0x7f6282d860
11-23 14:14:47.154   931  2931 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 14:14:47.154   931  2931 D wifi    : setting scan oui 0x7f6282d860
11-23 14:14:47.154   931  2931 D WifiHAL : Sending mac address OUI
,11-23 14:14:47.158   931  2931 E native  : do suspend false
,11-23 14:14:47.166   931  2931 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-23 14:14:47.166   510   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-23 14:14:47.168   510   925 D CommandListener: Setting iface cfg
,11-23 14:14:47.168   931   931 D RttService: SCAN_AVAILABLE : 3
11-23 14:14:47.168   931  2999 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 14:14:47.171   931  2923 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-23 14:14:47.172   931  2923 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 14:14:47.181   931  2923 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 14:14:47.182   931  2923 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-23 14:14:47.205   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=116636 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=35 mControllerEnergyUsed=133 }
,11-23 14:14:48.798   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:14:49.539   931  2931 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 7, 8 -> obsolete
,11-23 14:14:49.798   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:14:50.223  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 14:14:50.229  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 14:14:50.234  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 14:14:50.286   931  2931 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-23 14:14:50.288   931  2931 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 14:14:50.288   931  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 14:14:50.300   931  2931 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 14:14:50.341   931  2931 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 14:14:50.348  5685  5685 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 14:14:50.774  5685  5685 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 14:14:50.799   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:14:50.805  5685  5685 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 14:14:50.806  5685  5685 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 14:14:50.820   931  2931 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 14:14:50.821   931  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 14:14:50.821   931  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 14:14:50.839   931  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 14:14:50.851   510   925 D CommandListener: Setting iface cfg
,11-23 14:14:50.856   931  2931 D WifiStateMachine: Start Dhcp Watchdog 2
,11-23 14:14:50.865   931  5700 D DhcpClient: Receive thread started
,11-23 14:14:50.865   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 14:14:50.865   931  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-23 14:14:50.865   931  2933 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-23 14:14:50.947   931  2931 E native  : do suspend false
,11-23 14:14:50.961   931  5699 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 14:14:50.989   931  5700 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172719, domain null
,11-23 14:14:50.990   931  5699 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172719 seconds
,11-23 14:14:50.992   931  5699 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-23 14:14:51.011   931  5700 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 14:14:51.012   931  5699 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 14:14:51.015   510   925 D CommandListener: Setting iface cfg
,11-23 14:14:51.020   931  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 14:14:51.026   931  5699 D DhcpClient: Scheduling renewal in 86399s
,11-23 14:14:51.040   931  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 14:14:51.042   931  2931 D WifiConfigStore: No blacklist allowed without epno enabled
,11-23 14:14:51.043   931  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-23 14:14:51.045   931  2933 D ConnectivityService: Adding iface wlan0 to network 101
,11-23 14:14:51.062   931  2931 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 14:14:51.093   931  2933 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-23 14:14:51.093   931  2933 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
11-23 14:14:51.094   931  2933 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-23 14:14:51.096   931  2933 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-23 14:14:51.097   931  2933 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
11-23 14:14:51.106   931  2933 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 14:14:51.111   931  2933 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-23 14:14:51.111   931  2933 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-23 14:14:51.111   931  2933 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-23 14:14:51.111   931  2933 D ConnectivityService:    accepting network in place of null
11-23 14:14:51.111   931  2931 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-23 14:14:51.111   931  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 14:14:51.112   931  2933 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 14:14:51.128   931  5698 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120558, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 14:14:51.132   510   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 14:14:51.152   510   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 14:14:51.156   931  2933 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-23 14:14:51.156   931  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 14:14:51.156  3678  3819 W QCNEJ   : |CORE| network available: 101
,11-23 14:14:51.157   931  2933 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-23 14:14:51.159  3678  3819 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 14:14:51.159   931   948 D Tethering: MasterInitialState.processMessage what=3
11-23 14:14:51.161  3678  3819 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 14:14:51.161  3678  3819 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 14:14:51.162  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:51.162  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 14:14:51.162  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:51.162  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:51.162  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 14:14:51.162  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 14:14:51.162  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 14:14:51.162  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 14:14:51.162  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 14:14:51.162  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 14:14:51.163  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:51.163  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 14:14:51.170  4890  4912 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 14:14:51.170  4890  4912 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 14:14:51.170  4890  4912 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 14:14:51.170  4890  4912 E SarControlService: no key has been found,reset the power
11-23 14:14:51.170  4890  4934 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 14:14:51.170  4890  4934 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 14:14:51.170  4890  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 14:14:51.171  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 14:14:51.171  4925  4925 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 14:14:51.172  4890  4934 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-23 14:14:51.172  4890  4934 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 14:14:51.172  4890  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 14:14:51.173  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 14:14:51.173  4925  4925 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-23 14:14:51.176  3909  3909 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-23 14:14:51.177  4925  4939 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@45f99f5 HexData = [00000000ec03000000000000ffffffff]
11-23 14:14:51.177  4925  4939 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 14:14:51.178  4925  4939 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-23 14:14:51.178  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 14:14:51.178  4890  4901 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 14:14:51.180  3784  3784 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 14:14:51.183  3784  3784 D SystemUpdateService: onCreate
11-23 14:14:51.187  3784  3784 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-23 14:14:51.188  4925  4939 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@45f99f5 HexData = [00000000ed03000000000000ffffffff]
11-23 14:14:51.188  4925  4939 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 14:14:51.188  4925  4939 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-23 14:14:51.188  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 14:14:51.189  4890  4902 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-23 14:14:51.197  3784  3784 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 14:14:51.202   931  5697 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:804::200e
,11-23 14:14:51.204  3784  5323 I iu.UploadsManager: num queued entries: 0
,11-23 14:14:51.204  3784  5323 I iu.UploadsManager: num updated entries: 0
11-23 14:14:51.205  3784  5323 I iu.SyncManager: NEXT; no task
,11-23 14:14:51.208  3784  5710 I SystemUpdateService: active receiver: enabled
,11-23 14:14:51.210  3784  3784 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 14:14:51.211  3784  3784 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-23 14:14:51.213  5646  5646 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-23 14:14:51.216  5646  5646 D SprintDMHelper: simOperator: 
11-23 14:14:51.216  5646  5646 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 14:14:51.240  3784  5710 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 14:14:51.251   931  5697 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 13:14:51 GMT], X-Android-Received-Millis=[1479906891250], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479906891227]}
,11-23 14:14:51.252   931  2933 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 14:14:51.252   931  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-23 14:14:51.252   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 14:14:51.253   931  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-23 14:14:51.254  3784  5710 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-23 14:14:51.254  3784  5710 I SystemUpdateService: now status is 0 (complete)
11-23 14:14:51.254  3784  5710 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 14:14:51.254  3784  5710 I SystemUpdateService: file has been verified
11-23 14:14:51.255  3784  5710 I SystemUpdateService: OTA package size = 21989297
,11-23 14:14:51.262  3784  5710 I SystemUpdateService: showing system update notification
,11-23 14:14:51.269   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 14:14:51.270  3784  3784 D SystemUpdateService: onDestroy
,11-23 14:14:51.305   931  3542 D WifiService: setWifiEnabled: false pid=5560, uid=10077
,11-23 14:14:51.305   931  3542 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 14:14:51.307   931  2931 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-23 14:14:51.307   931  2931 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-23 14:14:51.307   931  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 14:14:51.307   931  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 14:14:51.318   931  5699 D DhcpClient: Clearing IP address
,11-23 14:14:51.318   510   925 D CommandListener: Clearing all IP addresses on wlan0
,11-23 14:14:51.319   510   925 D CommandListener: Setting iface cfg
,11-23 14:14:51.324  4246  5715 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,11-23 14:14:51.325  3527  5721 V NativeCrypto: Read error: ssl=0x7f66885e00: I/O error during system call, Connection timed out
,11-23 14:14:51.326  3527  5721 V NativeCrypto: SSL shutdown failed: ssl=0x7f66885e00: I/O error during system call, Broken pipe
,11-23 14:14:51.331   931  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-23 14:14:51.331   931  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-23 14:14:51.335   562   562 E Parcel  : Reading a NULL string not supported here.
,11-23 14:14:51.338   931   931 D RttService: SCAN_AVAILABLE : 1
,11-23 14:14:51.338   931  2999 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 14:14:51.338   931  2933 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-23 14:14:51.339   931  5700 D DhcpClient: Receive thread stopped
11-23 14:14:51.341  3678  3819 W QCNEJ   : |CORE| network lost: 101
11-23 14:14:51.341  3678  3819 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-23 14:14:51.342   931  2931 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
11-23 14:14:51.345  ,4246  5715 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
11-23 14:14:51.345  4246  5715 W Babel_NetworkConnectionCheckingService: 	... 21 more
11-23 14:14:51.345  4246  5715 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-23 14:14:51.346   931  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 14:14:51.361   510   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 14:14:51.380   510   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 14:14:51.380   931  2933 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-23 14:14:51.380   510   925 D CommandListener: Clearing all IP addresses on wlan0
,11-23 14:14:51.380   931  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 14:14:51.381   931   948 D Tethering: MasterInitialState.processMessage what=3
,11-23 14:14:51.385  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 14:14:51.385  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 14:14:51.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:51.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:51.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 14:14:51.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 14:14:51.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 14:14:51.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 14:14:51.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 14:14:51.385  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 14:14:51.385  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:51.385  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 14:14:51.387  3909  3909 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-23 14:14:51.392  4890  4912 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 14:14:51.392  4890  4912 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 14:14:51.392  4890  4912 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 14:14:51.392  4890  4912 E SarControlService: no key has been found,reset the power
11-23 14:14:51.392  4890  4934 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 14:14:51.392  4890  4934 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 14:14:51.392  4890  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-23 14:14:51.393  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-23 14:14:51.393  4925  4925 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-23 14:14:51.395  4890  4934 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 14:14:51.395  4890  4934 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 14:14:51.395  4890  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 14:14:51.397  3784  3784 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 14:14:51.398  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 14:14:51.398  4925  4925 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-23 14:14:51.402  4925  4939 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@45f99f5 HexData = [00000000ee03000000000000ffffffff]
,11-23 14:14:51.402  4925  4939 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 14:14:51.402  4925  4939 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-23 14:14:51.402  4925  4939 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@45f99f5 HexData = [00000000ef03000000000000ffffffff]
11-23 14:14:51.402  4925  4939 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 14:14:51.402  4925  4939 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-23 14:14:51.403  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 14:14:51.403  4890  4902 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-23 14:14:51.403  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 14:14:51.403  4890  4901 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 14:14:51.404  3784  3784 D SystemUpdateService: onCreate
,11-23 14:14:51.407  3784  3784 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 14:14:51.413  3784  5730 I SystemUpdateService: active receiver: enabled
,11-23 14:14:51.415  3784  3784 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 14:14:51.421  3784  5323 I iu.UploadsManager: num queued entries: 0
,11-23 14:14:51.421  3784  5323 I iu.UploadsManager: num updated entries: 0
11-23 14:14:51.422  3784  5323 I iu.SyncManager: NEXT; no task
,11-23 14:14:51.424  3784  3784 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 14:14:51.425  3784  3784 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 14:14:51.427  5646  5646 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 14:14:51.429   510   925 E Netd    : netlink response contains error (No such file or directory)
11-23 14:14:51.430   931  2933 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-23 14:14:51.431   931  2931 D DhcpClient: doQuit
11-23 14:14:51.431   931  2931 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 14:14:51.431   931  5699 D DhcpClient: onQuitting
,11-23 14:14:51.432  5685  5685 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 14:14:51.433  5646  5646 D SprintDMHelper: simOperator: 
,11-23 14:14:51.433  5646  5646 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 14:14:51.435  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:51.435  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 14:14:51.435  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:51.435  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:51.435  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 14:14:51.435  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 14:14:51.435  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 14:14:51.435  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 14:14:51.435  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 14:14:51.435  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 14:14:51.435  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:14:51.435  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 14:14:51.441  3784  5730 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 14:14:51.445  5685  5685 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 14:14:51.446  4246  5733 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-23 14:14:51.448  5685  5685 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-23 14:14:51.451  3784  5730 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-23 14:14:51.451  3784  5730 I SystemUpdateService: now status is 0 (complete)
11-23 14:14:51.451  3784  5730 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 14:14:51.452  3784  5730 I SystemUpdateService: file has been verified
11-23 14:14:51.452  3784  5730 I SystemUpdateService: OTA package size = 21989297
,11-23 14:14:51.467  3784  5730 I SystemUpdateService: showing system update notification
,11-23 14:14:51.471  5685  5685 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 14:14:51.473   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 14:14:51.474  3784  3784 D SystemUpdateService: onDestroy
11-23 14:14:51.479  5685  5685 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 14:14:51.584   931  2931 D wifi    : In wifi stop Hal
,11-23 14:14:51.584   931  2931 D wifi    : halHandle = 0x7f6505d980, mVM = 0x7f8168d140, mCls = 0x19a6
11-23 14:14:51.587   931  5684 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 14:14:51.587   931  5684 D WifiHAL : Got a signal to exit!!!
11-23 14:14:51.587   931  5684 I WifiHAL : Exit wifi_event_loop
,11-23 14:14:51.587  4246  4246 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 14:14:51.589   931  2931 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 14:14:51.589   931  2931 E WifiHAL : Event processing terminated
11-23 14:14:51.589  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 14:14:51.590   931  2931 D wifi    : In wifi cleaned up handler
11-23 14:14:51.590   931  2931 I WifiHAL : Internal cleanup completed
11-23 14:14:51.591  4035  4175 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 14:14:51.613   931  5684 D wifi    : set interface wlan0 flags (DOWN)
,11-23 14:14:51.614   931  2931 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 14:14:51.676   510   925 E Netd    : netlink response contains error (No such file or directory)
,11-23 14:14:51.800   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:14:51.818   931   948 D Tethering: InitialState.processMessage what=4
,11-23 14:14:51.824   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 14:14:52.157   931  2933 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-23 14:14:52.801   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:14:53.801   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 14:14:56.347   931   948 I ActivityManager: Start proc 5741:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 14:14:56.435  5741  5741 D AdapterServiceConfig: Adding HeadsetService
,11-23 14:14:56.435  5741  5741 D AdapterServiceConfig: Adding A2dpService
11-23 14:14:56.436  5741  5741 D AdapterServiceConfig: Adding HidService
11-23 14:14:56.436  5741  5741 D AdapterServiceConfig: Adding HealthService
,11-23 14:14:56.436  5741  5741 D AdapterServiceConfig: Adding PanService
11-23 14:14:56.436  5741  5741 D AdapterServiceConfig: Adding GattService
11-23 14:14:56.436  5741  5741 D AdapterServiceConfig: Adding BluetoothMapService
11-23 14:14:56.436  5741  5741 D AdapterServiceConfig: Adding SapService
,11-23 14:14:56.449   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8fa99f0:true
,11-23 14:14:56.449  5741  5741 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 14:14:56.452  5741  5753 I BluetoothAdapterState: Entering OffState
,11-23 14:14:56.452  5741  5741 I bt_bluedroid: init
,11-23 14:14:56.454  5741  5754 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-23 14:14:56.454  5741  5754 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 14:14:56.455  5741  5754 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 14:14:56.455  5741  5754 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-23 14:14:56.455  5741  5741 I bt_bluedroid: get_profile_interface socket
,11-23 14:14:56.457  5741  5757 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 14:14:56.457  5741  5741 I bt_bluedroid: get_profile_interface sdp
11-23 14:14:56.458  5741  5757 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 14:14:56.462  5741  5752 I bt_bluedroid: config_hci_snoop_log
,11-23 14:14:56.463   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 14:14:56.466  5741  5753 D BluetoothAdapterState: Current state: OFF, message: 0
11-23 14:14:56.467  5741  5753 D BluetoothAdapterProperties: Setting state to 14
,11-23 14:14:56.467  5741  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-23 14:14:56.468  5741  5753 D BluetoothBondStateMachine: make
11-23 14:14:56.469  5741  5758 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 14:14:56.472  5741  5753 I BluetoothAdapterState: Entering PendingCommandState
,11-23 14:14:56.472  5741  5741 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 14:14:56.474  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:14:56.475  5741  5741 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 14:14:56.475  5741  5741 D BtGatt.GattService: Received start request. Starting profile...
11-23 14:14:56.475  5741  5741 D BtGatt.GattService: start()
11-23 14:14:56.475  5741  5741 I bt_bluedroid: get_profile_interface gatt
11-23 14:14:56.476  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:14:56.476  5741  5741 D BtGatt.AdvertiseManager: advertise manager created
,11-23 14:14:56.480  5741  5741 V BluetoothAdapterState: isTurningOff()=false
,11-23 14:14:56.480  5741  5741 V BluetoothAdapterState: isTurningOn()=false
11-23 14:14:56.480  5741  5741 V BluetoothAdapterState: isBleTurningOn()=true
11-23 14:14:56.480  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 14:14:56.481  5741  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 14:14:56.482  5741  5753 I bt_bluedroid: bt_bluedroid
11-23 14:14:56.482  5741  5754 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-23 14:14:56.483  5741  5754 I bt_hci  : start_up
,11-23 14:14:56.487  5741  5754 I bt_vendor: alloc value 0xf42ab871
,11-23 14:14:56.487  5741  5754 I bt_vendor: init
11-23 14:14:56.487  5741  5754 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 14:14:56.487  5741  5754 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 14:14:56.599  5741  5754 D bt_hci  : start_up starting async portion
,11-23 14:14:56.600  5741  5761 I bt_hci  : event_finish_startup
11-23 14:14:56.600  5741  5761 I bt_hci_h4: hal_open
11-23 14:14:56.600  5741  5761 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 14:14:56.603  5741  5761 I bt_userial_vendor: device fd = 54 open
,11-23 14:14:56.598  5762  5762 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 14:14:56.617  5741  5761 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 14:14:56.620  5741  5761 D bt_hwcfg: Chipset BCM4358A3
,11-23 14:14:56.620  5741  5761 D bt_hwcfg: Target name = [BCM4358A3]
11-23 14:14:56.621  5741  5761 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 14:14:57.027  5741  5761 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 14:14:57.028  5741  5761 D bt_hwcfg: Settlement delay -- 100 ms
11-23 14:14:57.028  5741  5761 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 14:14:57.162  5741  5761 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 14:14:57.162  5741  5761 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-23 14:14:57.164  5741  5761 I bt_hwcfg: vendor lib fwcfg completed
11-23 14:14:57.164  5741  5761 I bt_vendor: firmware callback
11-23 14:14:57.164  5741  5761 I bt_hci  : firmware_config_callback
,11-23 14:14:57.174  5741  5764 I bt_btu  : btu_task pending for preload complete event
,11-23 14:14:57.174  5741  5764 I bt_btu_task: Bluetooth chip preload is complete
11-23 14:14:57.174  5741  5764 I bt_btu  : btu_task received preload complete event
,11-23 14:14:57.180  5741  5764 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 14:14:57.180  5741  5764 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-23 14:14:57.180  5741  5764 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-23 14:14:57.180  5741  5764 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-23 14:14:57.180  5741  5764 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 14:14:57.181  5741  5764 I         : BTE_InitTraceLevels -- TRC_A2D
,11-23 14:14:57.181  5741  5764 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-23 14:14:57.181  5741  5764 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 14:14:57.181  5741  5764 I         : BTE_InitTraceLevels -- TRC_GAP
,11-23 14:14:57.181  5741  5764 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 14:14:57.181  5741  5764 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 14:14:57.181  5741  5764 I         : BTE_InitTraceLevels -- TRC_GATT
,11-23 14:14:57.181  5741  5764 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 14:14:57.182  5741  5764 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 14:14:57.182  5741  5764 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 14:14:57.268  5741  5764 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4229549
11-23 14:14:57.269  5741  5764 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4229549 
,11-23 14:14:57.288  5741  5757 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 14:14:57.290  5741  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 14:14:57.290  5741  5757 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 14:14:57.292  5741  5757 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 14:14:57.294  5741  5757 D BluetoothAdapterProperties: Scan Mode:20
11-23 14:14:57.295  5741  5757 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 14:14:57.295  5741  5757 D bt_hci  : do_postload posting postload work item
11-23 14:14:57.295  5741  5761 I bt_hci  : event_postload
11-23 14:14:57.295  5741  5761 I bt_vendor: sco_config_cb
,11-23 14:14:57.295  5741  5761 I bt_hci  : sco_config_callback postload finished.
11-23 14:14:57.299  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:14:57.302  5741  5757 D bt_bte_conf: Device ID record 1 : primary
,11-23 14:14:57.302  5741  5757 D bt_bte_conf:   vendorId            = 000f
11-23 14:14:57.302  5741  5757 D bt_bte_conf:   vendorIdSource      = 0001
11-23 14:14:57.302  5741  5757 D bt_bte_conf:   product             = 1200
11-23 14:14:57.302  5741  5757 D bt_bte_conf:   version             = 1436
11-23 14:14:57.303  5741  5757 D bt_bte_conf:   clientExecutableURL = 
,11-23 14:14:57.303  5741  5757 D bt_bte_conf:   serviceDescription  = 
11-23 14:14:57.303  5741  5757 D bt_bte_conf:   documentationURL    = 
,11-23 14:14:57.303  5741  5757 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-23 14:14:57.303  5741  5754 D bt_stack_manager: event_start_up_stack finished
,11-23 14:14:57.304  5741  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 14:14:57.304  5741  5753 D BluetoothAdapterProperties: Setting state to 15
11-23 14:14:57.304  5741  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 14:14:57.308  5741  5753 I BluetoothAdapterState: Entering BleOnState
11-23 14:14:57.309  5741  5761 I bt_vendor: low_power_mode_cb
,11-23 14:14:57.312  5741  5753 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 14:14:57.312  5741  5753 D BluetoothAdapterProperties: Setting state to 11
11-23 14:14:57.312  5741  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 14:14:57.319  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:14:57.320  5741  5741 D HeadsetService: Received start request. Starting profile...
,11-23 14:14:57.322  5741  5741 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 14:14:57.323  5741  5741 D HeadsetStateMachine: make
,11-23 14:14:57.326  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:14:57.334  5741  5741 D HeadsetStateMachine: max_hf_connections = 1
11-23 14:14:57.334  5741  5741 I bt_bluedroid: get_profile_interface handsfree
11-23 14:14:57.334  5741  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 14:14:57.334  5741  5757 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 14:14:57.339  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:14:57.340  5741  5741 D A2dpService: Received start request. Starting profile...
11-23 14:14:57.341  5741  5741 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 14:14:57.341  5741  5741 I bt_bluedroid: get_profile_interface avrcp
,11-23 14:14:57.344  5741  5753 I BluetoothAdapterState: Entering PendingCommandState
,11-23 14:14:57.346  5741  5741 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 14:14:57.347  5741  5741 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 14:14:57.347  5741  5741 D A2dpStateMachine: make
,11-23 14:14:57.348  5741  5741 I bt_bluedroid: get_profile_interface a2dp
11-23 14:14:57.349  5741  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-23 14:14:57.350  5741  5772 D A2dpStateMachine: Enter Disconnected: -2
,11-23 14:14:57.350  5741  5741 I BluetoothHidServiceJni: classInitNative: succeeds
,11-23 14:14:57.351  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
,11-23 14:14:57.352  5619  5619 D BluetoothInputDevice: Proxy object connected
11-23 14:14:57.352  5741  5741 D HidService: Received start request. Starting profile...
11-23 14:14:57.353  5741  5741 I bt_bluedroid: get_profile_interface hidhost
11-23 14:14:57.353  5741  5741 D HidService: setHidService(): set to: null
11-23 14:14:57.353  5741  5757 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf420a56d
11-23 14:14:57.353  5741  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 14:14:57.353  5619  5619 D HidProfile: Bluetooth service connected
11-23 14:14:57.354  5741  5741 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 14:14:57.355  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:14:57.355  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 14:14:57.357  5741  5741 D HealthService: Received start request. Starting profile...
,11-23 14:14:57.358  5741  5741 I bt_bluedroid: get_profile_interface health
,11-23 14:14:57.359  5741  5741 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 14:14:57.360  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
,11-23 14:14:57.361  5619  5619 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 14:14:57.361  5741  5741 D PanService: Received start request. Starting profile...
11-23 14:14:57.361  5741  5741 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-23 14:14:57.362  5741  5741 I bt_bluedroid: get_profile_interface pan
11-23 14:14:57.362  5741  5757 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 14:14:57.362  5619  5619 D PanProfile: Bluetooth service connected
11-23 14:14:57.364  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
,11-23 14:14:57.366  5619  5619 D BluetoothMap: Proxy object connected
,11-23 14:14:57.366  5741  5741 D BluetoothMapService: Received start request. Starting profile...
11-23 14:14:57.366  5741  5741 D BluetoothMapService: start()
11-23 14:14:57.367  5619  5619 D MapProfile: Bluetooth service connected
11-23 14:14:57.367  5619  5619 D BluetoothMap: getConnectedDevices()
11-23 14:14:57.368  5619  5619 D BluetoothMap: Bluetooth is Not enabled
,11-23 14:14:57.369  5741  5741 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-23 14:14:57.370  5741  5741 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-23 14:14:57.370  5741  5741 D BluetoothMapAppObserver: createReceiver()
,11-23 14:14:57.371  5741  5741 D BluetoothMapAppObserver: initObservers()
,11-23 14:14:57.371  5741  5741 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 14:14:57.376  5741  5741 V BluetoothAdapterState: isTurningOff()=false
,11-23 14:14:57.376  5741  5741 V BluetoothAdapterState: isTurningOn()=true
11-23 14:14:57.376  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:57.376  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:14:57.377  5741  5769 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 14:14:57.377  5741  5741 V SapService: SapBinder()
11-23 14:14:57.378  5741  5741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:14:57.378  5741  5741 D SapService: Received start request. Starting profile...
11-23 14:14:57.378  5741  5741 V SapService: start()
11-23 14:14:57.379  5741  5741 V BluetoothAdapterState: isTurningOff()=false
,11-23 14:14:57.379  5741  5741 V BluetoothAdapterState: isTurningOn()=true
11-23 14:14:57.379  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:57.379  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:14:57.379  5741  5741 V BluetoothAdapterState: isTurningOff()=false
11-23 14:14:57.379  5741  5741 V BluetoothAdapterState: isTurningOn()=true
11-23 14:14:57.380  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:57.380  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:14:57.380  5741  5741 V BluetoothAdapterState: isTurningOff()=false
11-23 14:14:57.380  5741  5741 V BluetoothAdapterState: isTurningOn()=true
11-23 14:14:57.380  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:57.380  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 14:14:57.381  5741  5741 V BluetoothAdapterState: isTurningOff()=false
11-23 14:14:57.381  5741  5741 V BluetoothAdapterState: isTurningOn()=true
11-23 14:14:57.381  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:57.381  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:14:57.381  5741  5741 V BluetoothAdapterState: isTurningOff()=false
11-23 14:14:57.381  5741  5741 V BluetoothAdapterState: isTurningOn()=true
11-23 14:14:57.381  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:14:57.381  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:14:57.382  5741  5741 V BluetoothAdapterState: isTurningOff()=false
11-23 14:14:57.382  5741  5741 V BluetoothAdapterState: isTurningOn()=true
,11-23 14:14:57.382  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 14:14:57.382  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:14:57.383  5741  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 14:14:57.383  5741  5753 D BluetoothAdapterProperties: ScanMode =  20
,11-23 14:14:57.383  5741  5753 D BluetoothAdapterProperties: State =  11
11-23 14:14:57.385  5741  5757 D BluetoothAdapterProperties: Scan Mode:21
11-23 14:14:57.385  5741  5757 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-23 14:14:57.385  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 14:14:57.385  5741  5753 D BluetoothAdapterProperties: Setting state to 12
11-23 14:14:57.385  5741  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 14:14:57.386  5741  5753 I BluetoothAdapterState: Entering OnState
11-23 14:14:57.386  5619  5629 D BluetoothPbap: onBluetoothStateChange: up=true
,11-23 14:14:57.387  3709  3731 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 14:14:57.388  3061  5559 D BluetoothMap: onBluetoothStateChange: up=true
11-23 14:14:57.388  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 14:14:57.388  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:14:57.388  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:14:57.388  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 14:14:57.388  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 14:14:57.388  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 14:14:57.388  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 14:14:57.388  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 14:14:57.388  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 14:14:57.390   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 14:14:57.390  3061  3061 D BluetoothMap: Proxy object connected
11-23 14:14:57.390  3061  3061 D MapProfile: Bluetooth service connected
11-23 14:14:57.390  3061  3061 D BluetoothMap: getConnectedDevices()
11-23 14:14:57.391  3061  3929 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 14:14:57.391  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 14:14:57.392   931   931 D BluetoothA2dp: Proxy object connected
11-23 14:14:57.392  3061  3061 D BluetoothInputDevice: Proxy object connected
11-23 14:14:57.392  3061  3061 D HidProfile: Bluetooth service connected
,11-23 14:14:57.392  5619  5631 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 14:14:57.393  3061  5559 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 14:14:57.394  3061  3929 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 14:14:57.395  5619  5629 D BluetoothMap: onBluetoothStateChange: up=true
11-23 14:14:57.395  5619  5631 D BluetoothPan: onBluetoothStateChange on: true
11-23 14:14:57.395   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 14:14:57.395   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 14:14:57.395  3061  3061 D BluetoothA2dp: Proxy object connected
11-23 14:14:57.395  3061  3074 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 14:14:57.396  5741  5741 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 14:14:57.396  5741  5741 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-23 14:14:57.397  3061  5559 D BluetoothPan: onBluetoothStateChange on: true
11-23 14:14:57.398  5741  5741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 14:14:57.399   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 14:14:57.399  3061  3061 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 14:14:57.399  3061  3061 D PanProfile: Bluetooth service connected
,11-23 14:14:57.400   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
,11-23 14:14:57.401  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 14:14:57.402  5741  5741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 14:14:57.402  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:14:57.403  5619  5619 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-23 14:14:57.403  5741  5741 D ObexServerSockets: Succeed to create listening sockets 
11-23 14:14:57.404  5741  5741 D ObexServerSockets0: startAccept()
11-23 14:14:57.404  5741  5741 D ObexServerSockets0: prepareForNewConnect()
11-23 14:14:57.407  5619  5619 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-23 14:14:57.407  5741  5741 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 14:14:57.408  5741  5741 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 14:14:57.408  5741  5779 D ObexServerSockets0: Accepting socket connection...
11-23 14:14:57.408  5741  5741 D BluetoothMapService: onReceive
11-23 14:14:57.408  5741  5780 D ObexServerSockets0: Accepting socket connection...
,11-23 14:14:57.409  5741  5741 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 14:14:57.409  5741  5741 D BluetoothMapService: STATE_ON
11-23 14:14:57.411  5741  5781 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 14:14:57.412  5741  5781 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-23 14:14:57.412  5741  5781 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 14:14:57.415  5619  5619 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 14:14:57.417  5619  5619 D BluetoothA2dp: Proxy object connected
,11-23 14:14:57.422  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 14:14:57.425  5619  5619 D DockEventReceiver: finishStartingService: stopping service
,11-23 14:14:57.428  5619  5619 D BluetoothPbap: Proxy object connected
,11-23 14:14:57.429  3061  3061 D BluetoothPbap: Proxy object connected
11-23 14:14:57.429  3061  3061 D PbapServerProfile: Bluetooth service connected
11-23 14:14:57.429  5619  5619 D PbapServerProfile: Bluetooth service connected
,11-23 14:14:57.434  5741  5741 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 14:14:57.435  5741  5741 D ObexServerSockets0: prepareForNewConnect()
11-23 14:14:57.437  5741  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 14:14:57.449  5741  5789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 14:14:57.451  5741  5789 I BtOppRfcommListener: Accept thread started.
,11-23 14:14:57.489   931   931 D BluetoothHeadset: Proxy object connected
,11-23 14:14:57.489   931   931 D BluetoothHeadset: Proxy object connected
11-23 14:14:57.489   931   931 D BluetoothHeadset: Proxy object connected
11-23 14:14:57.489  3061  3929 D BluetoothHeadset: Proxy object connected
11-23 14:14:57.490  3061  3061 D HeadsetProfile: Bluetooth service connected
11-23 14:14:57.490  3709  3737 D BluetoothHeadset: Proxy object connected
,11-23 14:14:57.495  3061  3074 D BluetoothHeadset: Proxy object connected
11-23 14:14:57.495  3061  3061 D HeadsetProfile: Bluetooth service connected
,11-23 14:14:57.496   931   948 D BluetoothHeadset: Proxy object connected
11-23 14:14:57.496   931   948 D BluetoothHeadset: Proxy object connected
,11-23 14:14:57.498   931   948 D BluetoothHeadset: Proxy object connected
,11-23 14:14:57.510  5619  5631 D BluetoothHeadset: Proxy object connected
,11-23 14:14:57.511  5619  5619 D HeadsetProfile: Bluetooth service connected
,11-23 14:14:58.803   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:14:59.118   931  2933 D ConnectivityService: handlePromptUnvalidated 101
,11-23 14:14:59.734  3607  3776 I Keyboard.Facilitator.LanguageModelFlusher: run()
11-23 14:14:59.734  3607  3776 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-23 14:14:59.764  3527  3527 I ConfigService: onCreate
,11-23 14:14:59.803   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:00.804   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:01.322  5741  5753 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 14:15:01.322  5741  5753 D BluetoothAdapterProperties: Setting state to 13
,11-23 14:15:01.322  5741  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 14:15:01.324  5741  5753 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 14:15:01.325  5741  5753 I BluetoothAdapterState: Entering PendingCommandState
,11-23 14:15:01.330  5741  5741 D BluetoothMapService: onReceive
11-23 14:15:01.332  5741  5741 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-23 14:15:01.333  5741  5741 D BluetoothMapService: STATE_TURNING_OFF
11-23 14:15:01.333  5741  5741 D BluetoothMapService: MAP Service closeService in
11-23 14:15:01.333  5741  5741 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 14:15:01.334  5741  5741 D ObexServerSockets0: shutdown(block = true)
11-23 14:15:01.336  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:15:01.336  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 14:15:01.336  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:15:01.336  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:15:01.336  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 14:15:01.336  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 14:15:01.336  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 14:15:01.336  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 14:15:01.336  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 14:15:01.336  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 14:15:01.337  5741  5757 D BluetoothAdapterProperties: Scan Mode:20
11-23 14:15:01.337  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 14:15:01.338  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 14:15:01.339  5741  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-23 14:15:01.341  5619  5619 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 14:15:01.341  5741  5779 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-23 14:15:01.342  5741  5741 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 14:15:01.342  5741  5766 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 14:15:01.342  5741  5741 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 14:15:01.342  5741  5780 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-23 14:15:01.343  5741  5741 I BtOppRfcommListener: stopping Accept Thread
11-23 14:15:01.344  5741  5789 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 14:15:01.345  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 14:15:01.351  5619  5619 D DockEventReceiver: finishStartingService: stopping service
,11-23 14:15:01.344  5741  5789 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-23 14:15:01.355  5741  5741 D HeadsetService: Received stop request...Stopping profile...
,11-23 14:15:01.356   931   931 D BluetoothHeadset: Proxy object disconnected
11-23 14:15:01.357  5619  5631 D BluetoothHeadset: Proxy object disconnected
,11-23 14:15:01.357  5741  5741 D A2dpService: Received stop request...Stopping profile...
11-23 14:15:01.357   931   931 D BluetoothHeadset: Proxy object disconnected
11-23 14:15:01.357   931   931 D BluetoothHeadset: Proxy object disconnected
11-23 14:15:01.357  5741  5772 D A2dpStateMachine: Exit Disconnected: -1
11-23 14:15:01.357  3061  3074 D BluetoothHeadset: Proxy object disconnected
11-23 14:15:01.358  3709  3940 D BluetoothHeadset: Proxy object disconnected
,11-23 14:15:01.358   931   931 D BluetoothA2dp: Proxy object disconnected
11-23 14:15:01.359  3061  3061 D HeadsetProfile: Bluetooth service disconnected
11-23 14:15:01.359  5619  5619 D HeadsetProfile: Bluetooth service disconnected
11-23 14:15:01.359  3061  3061 D BluetoothA2dp: Proxy object disconnected
11-23 14:15:01.359  5619  5619 D BluetoothA2dp: Proxy object disconnected
11-23 14:15:01.361  5741  5741 D HidService: Received stop request...Stopping profile...
11-23 14:15:01.361  5741  5741 D HidService: Stopping Bluetooth HidService
,11-23 14:15:01.363  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 14:15:01.364  5619  5619 D BluetoothInputDevice: Proxy object disconnected
11-23 14:15:01.364  3061  3061 D BluetoothInputDevice: Proxy object disconnected
11-23 14:15:01.365  5619  5619 D HidProfile: Bluetooth service disconnected
,11-23 14:15:01.365  3061  3061 D HidProfile: Bluetooth service disconnected
,11-23 14:15:01.366  5741  5741 D HealthService: Received stop request...Stopping profile...
,11-23 14:15:01.368  5741  5741 D PanService: Received stop request...Stopping profile...
11-23 14:15:01.370  3061  3061 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 14:15:01.370  3061  3061 D PanProfile: Bluetooth service disconnected
11-23 14:15:01.370  5741  5741 D BluetoothMapService: Received stop request...Stopping profile...
11-23 14:15:01.371  5741  5741 D BluetoothMapService: stop()
11-23 14:15:01.371  5741  5741 D BluetoothMapAppObserver: deinitObservers()
11-23 14:15:01.371  5741  5741 D BluetoothMapAppObserver: removeReceiver()
,11-23 14:15:01.373  5619  5619 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 14:15:01.373  5619  5619 D PanProfile: Bluetooth service disconnected
,11-23 14:15:01.373  5619  5619 D BluetoothMap: Proxy object disconnected
11-23 14:15:01.373  3061  3061 D BluetoothMap: Proxy object disconnected
11-23 14:15:01.373  5619  5619 D MapProfile: Bluetooth service disconnected
11-23 14:15:01.373  3061  3061 D MapProfile: Bluetooth service disconnected
,11-23 14:15:01.373  5741  5741 D SapService: Received stop request...Stopping profile...
,11-23 14:15:01.373  5741  5741 V SapService: stop()
11-23 14:15:01.375  5741  5741 V BluetoothAdapterState: isTurningOff()=true
11-23 14:15:01.375  5741  5741 V BluetoothAdapterState: isTurningOn()=false
11-23 14:15:01.375  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:01.375  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 14:15:01.377  5741  5741 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 14:15:01.377  5741  5741 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 14:15:01.377  5741  5764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 14:15:01.377  5741  5741 V BluetoothAdapterState: isTurningOff()=true
,11-23 14:15:01.377  5741  5764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 14:15:01.377  5741  5741 V BluetoothAdapterState: isTurningOn()=false
11-23 14:15:01.377  5741  5764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 14:15:01.377  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:01.377  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 14:15:01.378  5741  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 14:15:01.378  5741  5757 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 14:15:01.380  5741  5764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 14:15:01.380  5741  5764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 14:15:01.380  5741  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-23 14:15:01.381  5741  5764 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 14:15:01.381  5741  5764 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 14:15:01.381  5741  5764 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 14:15:01.381  5741  5764 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 14:15:01.382  5741  5741 V BluetoothAdapterState: isTurningOff()=true
11-23 14:15:01.382  5741  5741 V BluetoothAdapterState: isTurningOn()=false
11-23 14:15:01.382  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:01.382  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 14:15:01.382  5741  5741 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-23 14:15:01.384  5741  5741 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-23 14:15:01.384  3061  3061 D BluetoothPbap: Proxy object disconnected
11-23 14:15:01.384  3061  3061 D PbapServerProfile: Bluetooth service disconnected
11-23 14:15:01.384  5741  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 14:15:01.384  5619  5619 D BluetoothPbap: Proxy object disconnected
11-23 14:15:01.384  5741  5741 V BluetoothAdapterState: isTurningOff()=true
11-23 14:15:01.384  5741  5741 V BluetoothAdapterState: isTurningOn()=false
11-23 14:15:01.384  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:01.384  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:15:01.384  5619  5619 D PbapServerProfile: Bluetooth service disconnected
11-23 14:15:01.384  5741  5741 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 14:15:01.385  5741  5757 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 14:15:01.385  5741  5741 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 14:15:01.385  5741  5741 V BluetoothAdapterState: isTurningOff()=true
11-23 14:15:01.385  5741  5741 V BluetoothAdapterState: isTurningOn()=false
11-23 14:15:01.385  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:01.385  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:15:01.385  5741  5741 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 14:15:01.386  5741  5741 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 14:15:01.386  5741  5741 D BluetoothMapService: MAP Service closeService in
11-23 14:15:01.387  5741  5741 V BluetoothAdapterState: isTurningOff()=true
11-23 14:15:01.387  5741  5741 V BluetoothAdapterState: isTurningOn()=false
,11-23 14:15:01.387  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:01.387  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:15:01.387  5741  5741 D BluetoothMapService: cleanup()
11-23 14:15:01.387  5741  5741 D BluetoothMapService: MAP Service closeService in
11-23 14:15:01.387  5741  5741 V BluetoothAdapterState: isTurningOff()=true
11-23 14:15:01.387  5741  5741 V BluetoothAdapterState: isTurningOn()=false
11-23 14:15:01.387  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:01.387  5741  5741 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:15:01.387  5741  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 14:15:01.388  5741  5753 D BluetoothAdapterProperties: Setting state to 15
11-23 14:15:01.388  5741  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 14:15:01.388  5741  5753 I BluetoothAdapterState: Entering BleOnState
11-23 14:15:01.388  5619  5629 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 14:15:01.389  5619  5631 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-23 14:15:01.390  5619  5629 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 14:15:01.391  3709  4065 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 14:15:01.392  3061  3072 D BluetoothMap: onBluetoothStateChange: up=false
11-23 14:15:01.392   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 14:15:01.393  3061  3929 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 14:15:01.393  5619  5631 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 14:15:01.394  3061  5559 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 14:15:01.394  3061  3074 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 14:15:01.395  5619  5629 D BluetoothMap: onBluetoothStateChange: up=false
,11-23 14:15:01.395  5619  5631 D BluetoothPan: onBluetoothStateChange on: false
11-23 14:15:01.396   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 14:15:01.396   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 14:15:01.396  3061  3072 D BluetoothPbap: onBluetoothStateChange: up=false
,11-23 14:15:01.397  3061  3929 D BluetoothPan: onBluetoothStateChange on: false
,11-23 14:15:01.397   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 14:15:01.398  5741  5753 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 14:15:01.398  5741  5753 D BluetoothAdapterProperties: Setting state to 16
11-23 14:15:01.398  5741  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 14:15:01.398  5741  5753 D BluetoothAdapterProperties: onBleDisable
11-23 14:15:01.399  5741  5753 I BluetoothAdapterState: Entering PendingCommandState
11-23 14:15:01.399  5741  5754 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-23 14:15:01.400  5741  5764 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 14:15:01.401  5741  5764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 14:15:01.402  5741  5757 D BluetoothAdapterProperties: Scan Mode:20
,11-23 14:15:01.403  5619  5619 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 14:15:01.403  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 14:15:01.406  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:15:01.409  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 14:15:01.417  5619  5619 D DockEventReceiver: finishStartingService: stopping service
,11-23 14:15:01.608  5741  5757 I bt_hci  : shut_down
,11-23 14:15:01.612  5741  5761 D bt_hwcfg: hw_epilog_process
,11-23 14:15:01.613  5741  5761 I bt_vendor: low_power_mode_cb
,11-23 14:15:01.615  5741  5761 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 14:15:01.615  5741  5761 I bt_vendor: epilog_cb
11-23 14:15:01.615  5741  5761 I bt_hci  : epilog_finished_callback
,11-23 14:15:01.617  5741  5757 I bt_hci_h4: hal_close
,11-23 14:15:01.617  5741  5757 I bt_userial_vendor: device fd = 54 close
,11-23 14:15:01.723  5741  5754 D bt_stack_manager: event_shut_down_stack finished.
,11-23 14:15:01.724  5741  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-23 14:15:01.729  5741  5753 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-23 14:15:01.729  5741  5741 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 14:15:01.732  5741  5741 D BtGatt.GattService: Received stop request...Stopping profile...
,11-23 14:15:01.732  5741  5741 D BtGatt.GattService: stop()
11-23 14:15:01.732  5741  5741 D BtGatt.AdvertiseManager: advertise clients cleared
11-23 14:15:01.735  5741  5741 V BluetoothAdapterState: isTurningOff()=false
11-23 14:15:01.736  5741  5741 V BluetoothAdapterState: isTurningOn()=false
11-23 14:15:01.736  5741  5741 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:01.736  5741  5741 V BluetoothAdapterState: isBleTurningOff()=true
11-23 14:15:01.736  5741  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 14:15:01.737  5741  5753 D BluetoothAdapterProperties: Setting state to 10
11-23 14:15:01.737  5741  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 14:15:01.738  5741  5753 I BluetoothAdapterState: Entering OffState
,11-23 14:15:01.739   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 14:15:01.754  5741  5741 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 14:15:01.755  5741  5741 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 14:15:01.755  5741  5741 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-23 14:15:01.759  5741  5754 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 14:15:01.768  5741  5741 I art     : System.exit called, status: 0
,11-23 14:15:01.769  5741  5741 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 14:15:01.805   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:01.806   931  3979 I ActivityManager: Process com.android.bluetooth (pid 5741) has died
,11-23 14:15:02.806   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:03.806   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 14:15:04.795  3527  3527 I ConfigService: onDestroy
,11-23 14:15:06.318  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:15:06.319  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 14:15:06.325  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 14:15:06.326  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13ab730 removed from the list
,11-23 14:15:06.326  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 14:15:06.330  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 14:15:06.331  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@67eeccf added. We now have 4 listener(s)
,11-23 14:15:06.331  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 14:15:06.332  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 14:15:06.333  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@67eeccf removed from the list
,11-23 14:15:06.333  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 14:15:06.338  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 14:15:06.338  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@74c165c added. We now have 4 listener(s)
,11-23 14:15:06.338  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 14:15:11.345  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:15:11.378   931   948 I ActivityManager: Start proc 5798:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 14:15:11.466  5798  5798 D AdapterServiceConfig: Adding HeadsetService
,11-23 14:15:11.466  5798  5798 D AdapterServiceConfig: Adding A2dpService
,11-23 14:15:11.466  5798  5798 D AdapterServiceConfig: Adding HidService
11-23 14:15:11.466  5798  5798 D AdapterServiceConfig: Adding HealthService
11-23 14:15:11.467  5798  5798 D AdapterServiceConfig: Adding PanService
,11-23 14:15:11.467  5798  5798 D AdapterServiceConfig: Adding GattService
,11-23 14:15:11.467  5798  5798 D AdapterServiceConfig: Adding BluetoothMapService
,11-23 14:15:11.467  5798  5798 D AdapterServiceConfig: Adding SapService
,11-23 14:15:11.478   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6b58ddc:true
11-23 14:15:11.478  5798  5798 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 14:15:11.481  5798  5798 I bt_bluedroid: init
11-23 14:15:11.481  5798  5810 I BluetoothAdapterState: Entering OffState
,11-23 14:15:11.484  5798  5811 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 14:15:11.484  5798  5811 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 14:15:11.484  5798  5811 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 14:15:11.484  5798  5811 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-23 14:15:11.485  5798  5798 I bt_bluedroid: get_profile_interface socket
,11-23 14:15:11.487  5798  5814 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-23 14:15:11.487  5798  5798 I bt_bluedroid: get_profile_interface sdp
11-23 14:15:11.488  5798  5814 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 14:15:11.491  5798  5809 I bt_bluedroid: config_hci_snoop_log
11-23 14:15:11.492   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 14:15:11.496  5798  5810 D BluetoothAdapterState: Current state: OFF, message: 0
11-23 14:15:11.496  5798  5810 D BluetoothAdapterProperties: Setting state to 14
,11-23 14:15:11.496  5798  5810 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-23 14:15:11.498  5798  5810 D BluetoothBondStateMachine: make
,11-23 14:15:11.499  5798  5815 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 14:15:11.502  5798  5810 I BluetoothAdapterState: Entering PendingCommandState
,11-23 14:15:11.503  5798  5798 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-23 14:15:11.505  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:15:11.505  5798  5798 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 14:15:11.506  5798  5798 D BtGatt.GattService: Received start request. Starting profile...
11-23 14:15:11.506  5798  5798 D BtGatt.GattService: start()
11-23 14:15:11.506  5798  5798 I bt_bluedroid: get_profile_interface gatt
,11-23 14:15:11.507  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:15:11.507  5798  5798 D BtGatt.AdvertiseManager: advertise manager created
,11-23 14:15:11.512  5798  5798 V BluetoothAdapterState: isTurningOff()=false
11-23 14:15:11.512  5798  5798 V BluetoothAdapterState: isTurningOn()=false
11-23 14:15:11.512  5798  5798 V BluetoothAdapterState: isBleTurningOn()=true
11-23 14:15:11.512  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 14:15:11.513  5798  5810 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 14:15:11.514  5798  5810 I bt_bluedroid: bt_bluedroid
11-23 14:15:11.514  5798  5811 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-23 14:15:11.514  5798  5811 I bt_hci  : start_up
,11-23 14:15:11.519  5798  5811 I bt_vendor: alloc value 0xf42ab871
11-23 14:15:11.519  5798  5811 I bt_vendor: init
11-23 14:15:11.519  5798  5811 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 14:15:11.519  5798  5811 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 14:15:11.627  5798  5811 D bt_hci  : start_up starting async portion
,11-23 14:15:11.628  5798  5818 I bt_hci  : event_finish_startup
11-23 14:15:11.628  5798  5818 I bt_hci_h4: hal_open
11-23 14:15:11.628  5798  5818 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 14:15:11.628  5819  5819 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 14:15:11.632  5798  5818 I bt_userial_vendor: device fd = 54 open
,11-23 14:15:11.648  5798  5818 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 14:15:11.651  5798  5818 D bt_hwcfg: Chipset BCM4358A3
,11-23 14:15:11.652  5798  5818 D bt_hwcfg: Target name = [BCM4358A3]
11-23 14:15:11.652  5798  5818 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 14:15:12.162  5798  5818 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 14:15:12.162  5798  5818 D bt_hwcfg: Settlement delay -- 100 ms
11-23 14:15:12.164  5798  5818 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 14:15:12.296  5798  5818 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-23 14:15:12.296  5798  5818 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-23 14:15:12.298  5798  5818 I bt_hwcfg: vendor lib fwcfg completed
,11-23 14:15:12.298  5798  5818 I bt_vendor: firmware callback
,11-23 14:15:12.298  5798  5818 I bt_hci  : firmware_config_callback
,11-23 14:15:12.307  5798  5821 I bt_btu  : btu_task pending for preload complete event
,11-23 14:15:12.307  5798  5821 I bt_btu_task: Bluetooth chip preload is complete
11-23 14:15:12.308  5798  5821 I bt_btu  : btu_task received preload complete event
,11-23 14:15:12.313  5798  5821 I         : BTE_InitTraceLevels -- TRC_HCI
11-23 14:15:12.313  5798  5821 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-23 14:15:12.313  5798  5821 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 14:15:12.313  5798  5821 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 14:15:12.313  5798  5821 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 14:15:12.313  5798  5821 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 14:15:12.313  5798  5821 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-23 14:15:12.314  5798  5821 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 14:15:12.314  5798  5821 I         : BTE_InitTraceLevels -- TRC_GAP
11-23 14:15:12.314  5798  5821 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 14:15:12.314  5798  5821 I         : BTE_InitTraceLevels -- TRC_SDP
,11-23 14:15:12.314  5798  5821 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 14:15:12.314  5798  5821 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 14:15:12.314  5798  5821 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 14:15:12.314  5798  5821 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 14:15:12.405  5798  5821 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4229549
,11-23 14:15:12.405  5798  5821 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4229549 
,11-23 14:15:12.441  5798  5814 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 14:15:12.443  5798  5814 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 14:15:12.444  5798  5814 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 14:15:12.446  5798  5814 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 14:15:12.449  5798  5814 D BluetoothAdapterProperties: Scan Mode:20
11-23 14:15:12.450  5798  5814 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-23 14:15:12.450  5798  5814 D bt_hci  : do_postload posting postload work item
11-23 14:15:12.450  5798  5818 I bt_hci  : event_postload
11-23 14:15:12.451  5798  5818 I bt_vendor: sco_config_cb
11-23 14:15:12.451  5798  5818 I bt_hci  : sco_config_callback postload finished.
,11-23 14:15:12.454  5798  5814 D bt_bte_conf: Device ID record 1 : primary
,11-23 14:15:12.455  5798  5814 D bt_bte_conf:   vendorId            = 000f
,11-23 14:15:12.455  5798  5814 D bt_bte_conf:   vendorIdSource      = 0001
11-23 14:15:12.455  5798  5814 D bt_bte_conf:   product             = 1200
11-23 14:15:12.455  5798  5814 D bt_bte_conf:   version             = 1436
11-23 14:15:12.455  5798  5814 D bt_bte_conf:   clientExecutableURL = 
11-23 14:15:12.455  5798  5814 D bt_bte_conf:   serviceDescription  = 
,11-23 14:15:12.455  5798  5814 D bt_bte_conf:   documentationURL    = 
11-23 14:15:12.455  5798  5814 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 14:15:12.455  5798  5811 D bt_stack_manager: event_start_up_stack finished
11-23 14:15:12.456  5798  5810 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 14:15:12.457  5798  5810 D BluetoothAdapterProperties: Setting state to 15
11-23 14:15:12.457  5798  5810 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 14:15:12.457  5798  5818 I bt_vendor: low_power_mode_cb
11-23 14:15:12.458  5798  5810 I BluetoothAdapterState: Entering BleOnState
,11-23 14:15:12.464  5798  5810 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-23 14:15:12.464  5798  5810 D BluetoothAdapterProperties: Setting state to 11
11-23 14:15:12.464  5798  5810 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 14:15:12.481  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
,11-23 14:15:12.482  5798  5798 D HeadsetService: Received start request. Starting profile...
,11-23 14:15:12.486  5798  5798 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 14:15:12.486  5798  5798 D HeadsetStateMachine: make
,11-23 14:15:12.494  5798  5810 I BluetoothAdapterState: Entering PendingCommandState
,11-23 14:15:12.501  5798  5798 D HeadsetStateMachine: max_hf_connections = 1
,11-23 14:15:12.501  5798  5798 I bt_bluedroid: get_profile_interface handsfree
11-23 14:15:12.501  5798  5814 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 14:15:12.501  5798  5814 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 14:15:12.512  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:15:12.513  5798  5798 D A2dpService: Received start request. Starting profile...
11-23 14:15:12.513  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 14:15:12.515  5798  5798 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 14:15:12.515  5798  5798 I bt_bluedroid: get_profile_interface avrcp
,11-23 14:15:12.521  5798  5798 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 14:15:12.522  5798  5798 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 14:15:12.522  5798  5798 D A2dpStateMachine: make
11-23 14:15:12.523  5798  5798 I bt_bluedroid: get_profile_interface a2dp
11-23 14:15:12.524  5798  5814 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-23 14:15:12.525  5798  5829 D A2dpStateMachine: Enter Disconnected: -2
,11-23 14:15:12.526  5798  5798 I BluetoothHidServiceJni: classInitNative: succeeds
11-23 14:15:12.526  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
,11-23 14:15:12.527  5798  5798 D HidService: Received start request. Starting profile...
11-23 14:15:12.527  5798  5798 I bt_bluedroid: get_profile_interface hidhost
11-23 14:15:12.527  5798  5798 D HidService: setHidService(): set to: null
11-23 14:15:12.527  5798  5814 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf420a56d
11-23 14:15:12.528  5798  5798 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 14:15:12.528  5798  5814 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-23 14:15:12.528  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:15:12.529  5798  5798 D HealthService: Received start request. Starting profile...
11-23 14:15:12.530  5798  5798 I bt_bluedroid: get_profile_interface health
,11-23 14:15:12.531  5798  5798 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-23 14:15:12.532  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:15:12.532  5798  5798 D PanService: Received start request. Starting profile...
11-23 14:15:12.533  5798  5798 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 14:15:12.533  5798  5798 I bt_bluedroid: get_profile_interface pan
,11-23 14:15:12.533  5798  5814 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-23 14:15:12.535  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
,11-23 14:15:12.536  5798  5798 D BluetoothMapService: Received start request. Starting profile...
11-23 14:15:12.536  5798  5798 D BluetoothMapService: start()
,11-23 14:15:12.538  5798  5798 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-23 14:15:12.539  5798  5798 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 14:15:12.540  5798  5798 D BluetoothMapAppObserver: createReceiver()
11-23 14:15:12.541  5798  5798 D BluetoothMapAppObserver: initObservers()
,11-23 14:15:12.541  5798  5798 D BluetoothMapAppObserver: getEnabledAccountItems()
11-23 14:15:12.547  5798  5798 V SapService: SapBinder()
11-23 14:15:12.547  5798  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:15:12.548  5798  5798 D SapService: Received start request. Starting profile...
11-23 14:15:12.548  5798  5798 V SapService: start()
,11-23 14:15:12.551  5798  5798 V BluetoothAdapterState: isTurningOff()=false
11-23 14:15:12.551  5798  5798 V BluetoothAdapterState: isTurningOn()=true
,11-23 14:15:12.552  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:12.552  5798  5827 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 14:15:12.552  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:15:12.552  5798  5798 V BluetoothAdapterState: isTurningOff()=false
11-23 14:15:12.553  5798  5798 V BluetoothAdapterState: isTurningOn()=true
,11-23 14:15:12.553  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:12.553  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:15:12.553  5798  5798 V BluetoothAdapterState: isTurningOff()=false
11-23 14:15:12.553  5798  5798 V BluetoothAdapterState: isTurningOn()=true
11-23 14:15:12.553  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:12.553  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:15:12.553  5798  5798 V BluetoothAdapterState: isTurningOff()=false
11-23 14:15:12.553  5798  5798 V BluetoothAdapterState: isTurningOn()=true
11-23 14:15:12.553  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:12.554  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:15:12.554  5798  5798 V BluetoothAdapterState: isTurningOff()=false
11-23 14:15:12.554  5798  5798 V BluetoothAdapterState: isTurningOn()=true
11-23 14:15:12.554  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:12.554  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
11-23 14:15:12.554  5798  5798 V BluetoothAdapterState: isTurningOff()=false
11-23 14:15:12.554  5798  5798 V BluetoothAdapterState: isTurningOn()=true
11-23 14:15:12.554  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:12.554  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 14:15:12.555  5798  5798 V BluetoothAdapterState: isTurningOff()=false
11-23 14:15:12.555  5798  5798 V BluetoothAdapterState: isTurningOn()=true
11-23 14:15:12.555  5798  5798 V BluetoothAdapterState: isBleTurningOn()=false
11-23 14:15:12.555  5798  5798 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 14:15:12.556  5798  5810 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 14:15:12.556  5798  5810 D BluetoothAdapterProperties: ScanMode =  20
11-23 14:15:12.556  5798  5810 D BluetoothAdapterProperties: State =  11
,11-23 14:15:12.556  5798  5810 D BluetoothAdapterProperties: Setting state to 12
11-23 14:15:12.556  5798  5810 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 14:15:12.557  5798  5810 I BluetoothAdapterState: Entering OnState
11-23 14:15:12.557  5798  5814 D BluetoothAdapterProperties: Scan Mode:21
11-23 14:15:12.557  5619  5631 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 14:15:12.557  5798  5814 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-23 14:15:12.558  5619  5629 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-23 14:15:12.561  5619  5631 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 14:15:12.564  3709  3940 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 14:15:12.564  3061  3072 D BluetoothMap: onBluetoothStateChange: up=true
11-23 14:15:12.566   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-23 14:15:12.566   931   931 D BluetoothA2dp: Proxy object connected
,11-23 14:15:12.566  3061  3074 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 14:15:12.566  5798  5798 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 14:15:12.567  5798  5798 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 14:15:12.568  5798  5798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 14:15:12.568  5619  5619 D BluetoothA2dp: Proxy object connected
,11-23 14:15:12.569  5619  5629 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 14:15:12.571  5798  5798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 14:15:12.572  5798  5798 D ObexServerSockets: Succeed to create listening sockets 
11-23 14:15:12.572  5798  5798 D ObexServerSockets0: startAccept()
11-23 14:15:12.572  3061  3929 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 14:15:12.572  5798  5798 D ObexServerSockets0: prepareForNewConnect()
,11-23 14:15:12.574  3061  3061 D BluetoothA2dp: Proxy object connected
,11-23 14:15:12.574  3061  3072 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 14:15:12.574  5619  5631 D BluetoothMap: onBluetoothStateChange: up=true
,11-23 14:15:12.575  5798  5798 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 14:15:12.575  5798  5798 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 14:15:12.575  5798  5836 D ObexServerSockets0: Accepting socket connection...
11-23 14:15:12.576  5798  5835 D ObexServerSockets0: Accepting socket connection...
11-23 14:15:12.576  3061  3061 D BluetoothMap: Proxy object connected
11-23 14:15:12.576  3061  3061 D MapProfile: Bluetooth service connected
11-23 14:15:12.576  3061  3061 D BluetoothMap: getConnectedDevices()
11-23 14:15:12.577  5619  5631 D BluetoothPan: onBluetoothStateChange on: true
11-23 14:15:12.579  3061  3061 D BluetoothInputDevice: Proxy object connected
,11-23 14:15:12.579  3061  3061 D HidProfile: Bluetooth service connected
11-23 14:15:12.579   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 14:15:12.579   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 14:15:12.580  3061  5559 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 14:15:12.581  5619  5619 D BluetoothMap: Proxy object connected
11-23 14:15:12.581  5619  5619 D MapProfile: Bluetooth service connected
11-23 14:15:12.581  5619  5619 D BluetoothMap: getConnectedDevices()
11-23 14:15:12.582  3061  3072 D BluetoothPan: onBluetoothStateChange on: true
,11-23 14:15:12.587  5619  5619 D BluetoothInputDevice: Proxy object connected
11-23 14:15:12.587  5619  5619 D HidProfile: Bluetooth service connected
11-23 14:15:12.588  5619  5619 D BluetoothPan: BluetoothPAN Proxy object connected
,11-23 14:15:12.588  5619  5619 D PanProfile: Bluetooth service connected
,11-23 14:15:12.591   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 14:15:12.591  3061  3061 D BluetoothPan: BluetoothPAN Proxy object connected
,11-23 14:15:12.591  3061  3061 D PanProfile: Bluetooth service connected
,11-23 14:15:12.592   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 14:15:12.593  5798  5798 D BluetoothMapService: onReceive
11-23 14:15:12.593  5798  5798 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 14:15:12.593  5798  5798 D BluetoothMapService: STATE_ON
,11-23 14:15:12.596  5798  5838 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 14:15:12.598  5798  5838 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 14:15:12.598  5798  5838 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 14:15:12.601  5619  5619 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 14:15:12.607  5619  5619 D DockEventReceiver: finishStartingService: stopping service
,11-23 14:15:12.611  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 14:15:12.617  3061  3061 D BluetoothPbap: Proxy object connected
11-23 14:15:12.617  5619  5619 D BluetoothPbap: Proxy object connected
,11-23 14:15:12.617  5619  5619 D PbapServerProfile: Bluetooth service connected
11-23 14:15:12.617  3061  3061 D PbapServerProfile: Bluetooth service connected
,11-23 14:15:12.618  5798  5798 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 14:15:12.618  5798  5798 D ObexServerSockets0: prepareForNewConnect()
,11-23 14:15:12.628  5798  5843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 14:15:12.642  5798  5847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 14:15:12.644  5798  5847 I BtOppRfcommListener: Accept thread started.
,11-23 14:15:12.659   931   931 D BluetoothHeadset: Proxy object connected
,11-23 14:15:12.659  5619  5629 D BluetoothHeadset: Proxy object connected
,11-23 14:15:12.660   931   931 D BluetoothHeadset: Proxy object connected
11-23 14:15:12.660   931   931 D BluetoothHeadset: Proxy object connected
11-23 14:15:12.660  3061  3074 D BluetoothHeadset: Proxy object connected
11-23 14:15:12.660  3061  3061 D HeadsetProfile: Bluetooth service connected
11-23 14:15:12.661  3709  4065 D BluetoothHeadset: Proxy object connected
,11-23 14:15:12.662  5619  5619 D HeadsetProfile: Bluetooth service connected
,11-23 14:15:12.664  3709  3981 D BluetoothHeadset: Proxy object connected
,11-23 14:15:12.674  3061  5559 D BluetoothHeadset: Proxy object connected
,11-23 14:15:12.675  3061  3061 D HeadsetProfile: Bluetooth service connected
,11-23 14:15:12.680   931   948 D BluetoothHeadset: Proxy object connected
,11-23 14:15:12.680   931   948 D BluetoothHeadset: Proxy object connected
,11-23 14:15:12.690   931   948 D BluetoothHeadset: Proxy object connected
,11-23 14:15:13.808   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:14.809   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:15.810   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:16.360  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 14:15:16.360  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:15:16.360  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:15:16.360  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 14:15:16.360  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 14:15:16.360  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 14:15:16.360  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 14:15:16.360  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 14:15:16.360  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 14:15:16.364  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 14:15:16.365  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 14:15:16.365  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@74c165c removed from the list
,11-23 14:15:16.365  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 14:15:16.366  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 14:15:16.367  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15dbd65 added. We now have 4 listener(s)
,11-23 14:15:16.367  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 14:15:16.370   931  3791 D WifiService: setWifiEnabled: false pid=5560, uid=10077
11-23 14:15:16.370   931  3791 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 14:15:16.811   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:17.812   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:18.813   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 14:15:21.381  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 14:15:21.382   931   942 D WifiService: setWifiEnabled: true pid=5560, uid=10077
11-23 14:15:21.382   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 14:15:21.392   510   925 D SoftapController: Softap fwReload - Ok
,11-23 14:15:21.398   510   925 D CommandListener: Setting iface cfg
,11-23 14:15:21.398   510   925 D CommandListener: Trying to bring down wlan0
,11-23 14:15:21.401   510   925 D CommandListener: Clearing all IP addresses on wlan0
,11-23 14:15:21.406   931  2931 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 14:15:22.091   931  2931 D wifi    : set interface wlan0 flags (UP)
,11-23 14:15:22.098   931  2931 I WifiHAL : Initializing wifi
,11-23 14:15:22.098   931  2931 I WifiHAL : Creating socket
,11-23 14:15:22.099   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 14:15:22.104   931  2931 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-23 14:15:22.104   931  2931 D wifi    : Did set static halHandle = 0x7f6505d980
,11-23 14:15:22.104   931  2931 D wifi    : halHandle = 0x7f6505d980, mVM = 0x7f8168d140, mCls = 0x1876
11-23 14:15:22.104   931  2931 D wifi    : array field set
11-23 14:15:22.105   931  2931 I WifiNative-HAL: interface[0] = wlan0
11-23 14:15:22.107   931  5853 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547155728768
,11-23 14:15:22.107   931  5853 D wifi    : waitForHalEvents called, vm = 0x7f8168d140, obj = 0x1876, env = 0x7f66a9ae80
,11-23 14:15:22.155  5854  5854 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 14:15:22.208   931  2931 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 14:15:22.224  5854  5854 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 14:15:22.289  5854  5854 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 14:15:22.289  5854  5854 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 14:15:22.308   931  2931 D WifiConfigStore: Loading config and enabling all networks 
,11-23 14:15:22.337   931  2931 D WifiConfigStore: loaded 0 passpoint configs
,11-23 14:15:22.338   931  2931 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-23 14:15:22.338   931  2931 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-23 14:15:22.338   931  2931 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-23 14:15:22.339   931  2931 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-23 14:15:22.339   931  2931 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-23 14:15:22.340   931  2931 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-23 14:15:22.340   931  2931 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-23 14:15:22.340   931  2931 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-23 14:15:22.340   931  2931 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-23 14:15:22.340   931  2931 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-23 14:15:22.340   931  2931 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-23 14:15:22.340   931  2931 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-23 14:15:22.343   931  2931 D WifiNative-HAL: Setting external_sim to 1
11-23 14:15:22.343   931  2931 D wifi    : setting dfs flag to true, 0x7f6282d740
,11-23 14:15:22.343   931  2931 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 14:15:22.343   931  2931 D wifi    : setting scan oui 0x7f6282d740
11-23 14:15:22.343  4246  4246 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 14:15:22.343   931  2931 D WifiHAL : Sending mac address OUI
,11-23 14:15:22.347   931  2931 E native  : do suspend false
,11-23 14:15:22.353   931  2931 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-23 14:15:22.353   931   931 D RttService: SCAN_AVAILABLE : 3
,11-23 14:15:22.354   931  2999 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 14:15:22.357   510   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-23 14:15:22.358   510   925 D CommandListener: Setting iface cfg
,11-23 14:15:22.361   931  2923 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
11-23 14:15:22.361   931  2923 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 14:15:22.370   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=151801 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,11-23 14:15:22.370   931  2923 D WifiNative-HAL: p2pGetDeviceAddress
11-23 14:15:22.371   931  2923 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-23 14:15:24.973  4035  4425 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-23 14:15:25.401  5854  5854 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 14:15:25.407  5854  5854 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 14:15:25.458   931  2931 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-23 14:15:25.459   931  2931 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 14:15:25.459   931  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 14:15:25.471   931  2931 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 14:15:25.505   931  2931 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 14:15:25.511  5854  5854 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 14:15:25.944  5854  5854 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 14:15:25.974  5854  5854 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 14:15:25.975  5854  5854 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 14:15:25.987   931  2931 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 14:15:25.987   931  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 14:15:25.988   931  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 14:15:26.005   931  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 14:15:26.023   510   925 D CommandListener: Setting iface cfg
,11-23 14:15:26.028   931  2931 D WifiStateMachine: Start Dhcp Watchdog 3
,11-23 14:15:26.033   931  5868 D DhcpClient: Receive thread started
,11-23 14:15:26.037   931  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-23 14:15:26.037   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-23 14:15:26.037   931  2933 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-23 14:15:26.117   931  2931 E native  : do suspend false
,11-23 14:15:26.125   931  5867 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 14:15:26.141   931  5868 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-23 14:15:26.141   931  5867 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-23 14:15:26.143   931  5867 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-23 14:15:26.161   931  5868 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 14:15:26.162   931  5867 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 14:15:26.163   510   925 D CommandListener: Setting iface cfg
,11-23 14:15:26.168   931  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 14:15:26.172   931  5867 D DhcpClient: Scheduling renewal in 86399s
,11-23 14:15:26.180   931  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 14:15:26.181   931  2931 D WifiConfigStore: No blacklist allowed without epno enabled
11-23 14:15:26.182   931  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-23 14:15:26.184   931  2933 D ConnectivityService: Adding iface wlan0 to network 102
,11-23 14:15:26.193   931  2931 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 14:15:26.229   931  2933 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-23 14:15:26.229   931  2933 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-23 14:15:26.233   931  2933 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-23 14:15:26.238   931  2933 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-23 14:15:26.241   931  2933 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-23 14:15:26.248   931  2933 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:15:26.253   931  2933 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-23 14:15:26.253   931  2933 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-23 14:15:26.254   931  2933 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-23 14:15:26.254   931  2933 D ConnectivityService:    accepting network in place of null
11-23 14:15:26.254   931  2931 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 14:15:26.254   931  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 14:15:26.254   931  2933 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 14:15:26.276   510   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 14:15:26.298   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155728, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 14:15:26.298   510   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 14:15:26.302   931  2933 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-23 14:15:26.302   931  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 14:15:26.302  3678  3819 W QCNEJ   : |CORE| network available: 102
,11-23 14:15:26.304   931  2933 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-23 14:15:26.305  3678  3819 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 14:15:26.305   931   948 D Tethering: MasterInitialState.processMessage what=3
11-23 14:15:26.307  3678  3819 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 14:15:26.307  3678  3819 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 14:15:26.323  4890  4912 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 14:15:26.323  4890  4912 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 14:15:26.323  4890  4912 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 14:15:26.323  4890  4912 E SarControlService: no key has been found,reset the power
,11-23 14:15:26.327  4890  4934 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-23 14:15:26.327  4890  4934 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 14:15:26.327  4890  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 14:15:26.328  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 14:15:26.328  4925  4925 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-23 14:15:26.330  3909  3909 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-23 14:15:26.333  4890  4934 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 14:15:26.333  3784  3784 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 14:15:26.334  4925  4939 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@45f99f5 HexData = [00000000f003000000000000ffffffff]
11-23 14:15:26.335  4925  4939 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 14:15:26.335  4925  4939 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,11-23 14:15:26.335  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 14:15:26.336  4890  4902 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-23 14:15:26.339  4890  4934 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-23 14:15:26.339  4890  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 14:15:26.339  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 14:15:26.339  4925  4925 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-23 14:15:26.343  4925  4939 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@45f99f5 HexData = [00000000f103000000000000ffffffff]
,11-23 14:15:26.343  4925  4939 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 14:15:26.343  4925  4939 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-23 14:15:26.344  4925  4925 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 14:15:26.344  4890  4901 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 14:15:26.348  3784  3784 D SystemUpdateService: onCreate
,11-23 14:15:26.351  3784  3784 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 14:15:26.361   931  5865 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:804::200e
,11-23 14:15:26.364  3784  3784 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 14:15:26.374  3784  5323 I iu.UploadsManager: num queued entries: 0
,11-23 14:15:26.374  3784  5323 I iu.UploadsManager: num updated entries: 0
11-23 14:15:26.375  3784  5323 I iu.SyncManager: NEXT; no task
,11-23 14:15:26.378  3784  5879 I SystemUpdateService: active receiver: enabled
,11-23 14:15:26.380  3784  3784 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 14:15:26.381  3784  3784 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 14:15:26.384  5646  5646 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 14:15:26.391  5646  5646 D SprintDMHelper: simOperator: 
,11-23 14:15:26.391  5646  5646 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 14:15:26.399  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 14:15:26.399  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 14:15:26.399  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 14:15:26.399  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 14:15:26.399  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 14:15:26.399  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 14:15:26.399  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 14:15:26.399  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 14:15:26.399  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 14:15:26.401  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 14:15:26.401  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.401  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15dbd65 removed from the list
,11-23 14:15:26.401  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:15:26.405  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-23 14:15:26.406  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-23 14:15:26.408  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a62ca9 Bundle[{}]
,11-23 14:15:26.409  5560  5606 I io.jxcore.node.LifeCycleMonitor: start: OK
11-23 14:15:26.409  5560  5606 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-23 14:15:26.410  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-23 14:15:26.410   931  5865 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 13:15:26 GMT], X-Android-Received-Millis=[1479906926409], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479906926387]}
11-23 14:15:26.410  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-23 14:15:26.411   931  2933 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 14:15:26.411  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-23 14:15:26.411   931  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-23 14:15:26.411   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-23 14:15:26.411  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-23 14:15:26.412   931  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 14:15:26.419  5560  5606 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
11-23 14:15:26.419  5560  5606 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-23 14:15:26.419  5560  5606 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
11-23 14:15:26.421  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 14:15:26.421  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bc9a3a added. We now have 3 listener(s)
,11-23 14:15:26.423  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 14:15:26.423  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 14:15:26.423  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 14:15:26.424  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 14:15:26.424  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2786eb added. We now have 4 listener(s)
11-23 14:15:26.424  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 14:15:26.424  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 14:15:26.425  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 14:15:26.426  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb23c48 added. We now have 4 listener(s)
,11-23 14:15:26.427  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 14:15:26.427  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 14:15:26.427  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 14:15:26.427  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 14:15:26.428  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f1cae1 added. We now have 5 listener(s)
11-23 14:15:26.428  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 14:15:26.428  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:15:26.428  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:15:26.428  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 14:15:26.428  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:15:26.428  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:15:26.428  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 14:15:26.428  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bc9a3a removed from the list
11-23 14:15:26.428  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.429  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2786eb removed from the list
11-23 14:15:26.429  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:15:26.429  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.429  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.431  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.431  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.431  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.431  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:15:26.431  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:15:26.431  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.431  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2786eb not in the list
11-23 14:15:26.431  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.431  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.433  3784  5879 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 14:15:26.434  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.434  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.434  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.434  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 14:15:26.434  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:15:26.434  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.434  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f1cae1 removed from the list
11-23 14:15:26.434  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:15:26.434  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:15:26.434  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 14:15:26.434  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb23c48 removed from the list
11-23 14:15:26.435  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 14:15:26.435  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca2006 added. We now have 3 listener(s)
11-23 14:15:26.436  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 14:15:26.436  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 14:15:26.436  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 14:15:26.436  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 14:15:26.436  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@375a6c7 added. We now have 4 listener(s)
11-23 14:15:26.436  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 14:15:26.437  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 14:15:26.438  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 14:15:26.438  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d2d4f4 added. We now have 4 listener(s)
11-23 14:15:26.439  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 14:15:26.439  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 14:15:26.439  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 14:15:26.439  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 14:15:26.439  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5f341d added. We now have 5 listener(s)
11-23 14:15:26.439  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 14:15:26.440  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 14:15:26.440  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 14:15:26.440  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 14:15:26.440  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 14:15:26.440  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 14:15:26.441  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 14:15:26.442  3784  5879 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-23 14:15:26.442  3784  5879 I SystemUpdateService: now status is 0 (complete)
11-23 14:15:26.442  3784  5879 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 14:15:26.442  3784  5879 I SystemUpdateService: file has been verified
11-23 14:15:26.443  3784  5879 I SystemUpdateService: OTA package size = 21989297
11-23 14:15:26.443  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 14:15:26.443  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 14:15:26.443  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 14:15:26.446  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.446  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 14:15:26.446  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 14:15:26.447  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 14:15:26.447  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 14:15:26.448  3784  5879 I SystemUpdateService: showing system update notification
11-23 14:15:26.450  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.450  5560  5606 I org.thaliproject.,p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 14:15:26.450  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 14:15:26.450  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 14:15:26.450  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 14:15:26.450  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.451  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:15:26.454  5798  5809 D BtGatt.GattService: registerClient() - UUID=298d13e4-fbce-4b35-a10c-0aadb1a44083
,11-23 14:15:26.454  5798  5814 D BtGatt.GattService: onClientRegistered() - UUID=298d13e4-fbce-4b35-a10c-0aadb1a44083, clientIf=5
,11-23 14:15:26.455  5560  5607 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 14:15:26.456  5798  5839 D BtGatt.GattService: start scan with filters
,11-23 14:15:26.459   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 14:15:26.459  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 14:15:26.460  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.460  5798  5817 D BtGatt.ScanManager: handling starting scan
11-23 14:15:26.460  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 14:15:26.460  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.460  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 14:15:26.460  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 14:15:26.460  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.461  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 14:15:26.461  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 14:15:26.461  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.461  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 14:15:26.461  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.461  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.461  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-23 14:15:26.461  3784  3784 D SystemUpdateService: onDestroy
11-23 14:15:26.462  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-23 14:15:26.461  5798  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67cd9e2
11-23 14:15:26.464  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.464  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 14:15:26.464  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.464  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.464  5560  5606 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 14:15:26.464  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 14:15:26.464  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 14:15:26.464  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 14:15:26.464  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 14:15:26.464  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:15:26.465  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.467  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 14:15:26.467  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.468  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.468  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.468  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 14:15:26.468  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 14:15:26.468  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.468  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 14:15:26.468  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 14:15:26.469  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.469  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.469  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.469  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-23 14:15:26.469  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.470  5798  5814 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 14:15:26.470  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.470  3527  5889 I VacuumService: Vacuum at: now=1479906926470 tag=VacuumService
,11-23 14:15:26.470  5798  5817 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 14:15:26.470  5560  5606 D BluetoothAdapter: STATE_ON
,11-23 14:15:26.471  5798  5809 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 14:15:26.471  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 14:15:26.471  5560  5606 D BluetoothAdapter: STATE_ON
,11-23 14:15:26.472  5798  5837 D BtGatt.GattService: stopScan() - queue size =1
11-23 14:15:26.473  5798  5809 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 14:15:26.473  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 14:15:26.473  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.473  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 14:15:26.473  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.473  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.473  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.473  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.473  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 14:15:26.474  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.474  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.474  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.474  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 14:15:26.474  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 14:15:26.475  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 14:15:26.475  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.476  5798  5814 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 14:15:26.476  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.476  5798  5817 D BtGatt.ScanManager: Starting BLE batch scan
11-23 14:15:26.476  5798  5817 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 14:15:26.477  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.477  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:15:26.477  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.477  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.478  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:15:26.479  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:15:26.479  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thr,ead[main,5,main], id: 1
11-23 14:15:26.479  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.479  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 14:15:26.479  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 14:15:26.479  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.479  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.479  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.479  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:15:26.479  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.479  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.481  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.481  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.481  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.482  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:15:26.482  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 14:15:26.482  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:15:26.482  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:15:26.482  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:15:26.482  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 14:15:26.482  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca2006 removed from the list
11-23 14:15:26.482  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.483  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@375a6c7 removed from the list
11-23 14:15:26.483  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:15:26.483  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.483  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.484  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.485  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.485  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.485  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:15:26.485  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:15:26.485  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.485  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@375a6c7 not in the list
11-23 14:15:26.485  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.485  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.486  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.486  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.486  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.486  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:15:26.486  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:15:26.486  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.486  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5f341d removed from the list
11-23 14:15:26.486  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:15:26.487  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:15:26.487  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 14:15:26.487  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d2d4f4 removed from the list
11-23 14:15:26.487  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 14:15:26.487  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93f29de added. We now have 3 listener(s)
11-23 14:15:26.488  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 14:15:26.489  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 14:15:26.489  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 14:15:26.489  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 14:15:26.489  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5aa7bf added. We now have 4 listener(s)
11-23 14:15:26.489  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 14:15:26.490  5798  5814 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 14:15:26.490  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 14:15:26.490  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.491  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 14:15:26.491  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86fce8c added. We now have 4 listener(s)
11-23 14:15:26.492  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 14:15:26.492  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 14:15:26.492  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 14:15:26.492  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 14:15:26.492  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1c9d5 added. We now have 5 listener(s)
11-23 14:15:26.492  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 14:15:26.493  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 14:15:26.493  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 14:15:26.493  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 14:15:26.494  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 14:15:26.494  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 14:15:26.494  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 14:15:26.495  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 14:15:26.498  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 14:15:26.498  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 14:15:26.498  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 14:15:26.500  5798  5814 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 14:15:26.500  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 14:15:26.502  5798  5817 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 14:15:26.502  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.502  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 14:15:26.503  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 14:15:26.503  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 14:15:26.503  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 14:15:26.507  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.507  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 14:15:26.507  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 14:15:26.507  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 14:15:26.507  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 14:15:26.507  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.507  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:15:26.507  5798  5814 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 14:15:26.508  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.508  5798  5814 E BtGatt.ContextMap: Context not found for ID 5
,11-23 14:15:26.510  5798  5809 D BtGatt.GattService: registerClient() - UUID=2a5d23e7-9d39-4b26-90b6-b457d2c834e2
,11-23 14:15:26.511  5798  5814 D BtGatt.GattService: onClientRegistered() - UUID=2a5d23e7-9d39-4b26-90b6-b457d2c834e2, clientIf=5
,11-23 14:15:26.512  5560  5571 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 14:15:26.512  5798  5837 D BtGatt.GattService: start scan with filters
,11-23 14:15:26.514  5798  5814 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 14:15:26.514  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.514  5798  5817 D BtGatt.ScanManager: stopping BLe Batch
,11-23 14:15:26.515  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 14:15:26.515  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.515  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-23 14:15:26.515  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.515  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-23 14:15:26.515  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 14:15:26.515  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.516  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 14:15:26.516  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 14:15:26.516  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.516  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-23 14:15:26.516  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.516  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.516  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 14:15:26.516  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.518  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.518  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 14:15:26.518  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.518  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.519  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 14:15:26.519  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 14:15:26.519  5560  5606 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-23 14:15:26.519  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 14:15:26.519  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:15:26.519  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:15:26.519  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 14:15:26.519  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 14:15:26.519  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 14:15:26.519  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:15:26.519  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-23 14:15:26.519  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93f29de removed from the list
11-23 14:15:26.519  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.519  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5aa7bf removed from the list
,11-23 14:15:26.519  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:15:26.519  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 14:15:26.519  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 14:15:26.520  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.520  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 14:15:26.520  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 14:15:26.520  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 14:15:26.520  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 14:15:26.520  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.520  5798  5814 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 14:15:26.520  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.520  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.521  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.521  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.521  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:15:26.521  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:15:26.521  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.521  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.521  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5aa7bf not in the list
11-23 14:15:26.521  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.521  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.521  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 14:15:26.521  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 14:15:26.521  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.521  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-23 14:15:26.521  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-23 14:15:26.521  5798  5817 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 14:15:26.521  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.521  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.522  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.522  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 14:15:26.522  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.523  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:15:26.523  5798  5839 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 14:15:26.523  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 14:15:26.524  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:15:26.524  5798  5808 D BtGatt.GattService: stopScan() - queue size =0
11-23 14:15:26.525  5798  5837 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-23 14:15:26.525  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 14:15:26.525  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.525  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 14:15:26.525  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.525  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.525  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.525  5798  5814 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 14:15:26.525  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.525  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.525  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 14:15:26.525  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.526  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.526  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.526  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 14:15:26.526  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 14:15:26.526  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 14:15:26.527  4246  5884 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-23 14:15:26.527  5798  5817 D BtGatt.ScanManager: handling starting scan
11-23 14:15:26.528  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.529  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.529  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:15:26.529  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.529  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.529  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:15:26.529  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:15:26.529  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.529  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1c9d5 removed from the list
11-23 14:15:26.529  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:15:26.529  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:15:26.529  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:15:26.529  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:15:26.529  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 14:15:26.529  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86fce8c removed from the list
11-23 14:15:26.529  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 14:15:26.529  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,,main], id: 1
11-23 14:15:26.530  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 14:15:26.530  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 14:15:26.530  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.530  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.530  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.530  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:15:26.530  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 14:15:26.530  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.530  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6096b6 added. We now have 3 listener(s)
11-23 14:15:26.530  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 14:15:26.530  3527  5893 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-23 14:15:26.531  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 14:15:26.531  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 14:15:26.531  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 14:15:26.531  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 14:15:26.531  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcfcfb7 added. We now have 4 listener(s)
11-23 14:15:26.531  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 14:15:26.532  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 14:15:26.532  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.532  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-23 14:15:26.532  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.533  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 14:15:26.533  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4f6324 added. We now have 4 listener(s)
11-23 14:15:26.534  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 14:15:26.534  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 14:15:26.534  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 14:15:26.534  5798  5814 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 14:15:26.534  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 14:15:26.534  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.534  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da5e8d added. We now have 5 listener(s)
11-23 14:15:26.535  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 14:15:26.535  5798  5817 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 14:15:26.535  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 14:15:26.535  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 14:15:26.535  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 14:15:26.535  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 14:15:26.535  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 14:15:26.537  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 14:15:26.539  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 14:15:26.539  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 14:15:26.539  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 14:15:26.540  5798  5814 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 14:15:26.540  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.540  5798  5817 D BtGatt.ScanManager: Starting BLE batch scan
11-23 14:15:26.540  5798  5817 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 14:15:26.542  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.542  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 14:15:26.543  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 14:15:26.543  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 14:15:26.543  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 14:15:26.546  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.546  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 14:15:26.546  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 14:15:26.546  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 14:15:26.546  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 14:15:26.546  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.547  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:15:26.548  5798  5814 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 14:15:26.548  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.550  5798  5837 D BtGatt.GattService: registerClient() - UUID=c69468ba-0e2d-4ba0-9c02-ece0ecf4f8df
11-23 14:15:26.550  5798  5814 D BtGatt.GattService: onClientRegistered() - UUID=c69468ba-0e2d-4ba0-9c02-ece0ecf4f8df, clientIf=5
11-23 14:15:26.551  5560  5570 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 14:15:26.551  5798  5809 D BtGatt.GattService: start scan with filters
11-23 14:15:26.554  5798  5814 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 14:15:26.554  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.554  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 14:15:26.554  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.554  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-23 14:15:26.554  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.554  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-23 14:15:26.554  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-23 14:15:26.554  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.555  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 14:15:26.555  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 14:15:26.555  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-23 14:15:26.555  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.555  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-23 14:15:26.555  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.555  5798  5817 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 14:15:26.555  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 14:15:26.556  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.559  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.559  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 14:15:26.559  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.559  5798  5814 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 14:15:26.559  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.559  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.560  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.562  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:15:26.562  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:15:26.562  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:15:26.562  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:15:26.562  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 14:15:26.562  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 14:15:26.562  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:15:26.562  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 14:15:26.562  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6096b6 removed from the list
11-23 14:15:26.563  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.563  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcfcfb7 removed from the list
11-23 14:15:26.563  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 14:15:26.563  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 14:15:26.563  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 14:15:26.563  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.563  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 14:15:26.563  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 14:15:26.563  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 14:15:26.563  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 14:15:26.563  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.563  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-23 14:15:26.563  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.563  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.563  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 14:15:26.563  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.564  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.564  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.564  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.564  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:15:26.564  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:15:26.564  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.564  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcfcfb7 not in the list
11-23 14:15:26.564  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 14:15:26.564  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.564  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 14:15:26.564  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 14:15:26.564  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.564  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.564  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.564  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 14:15:26.564  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.565  5798  5814 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 14:15:26.565  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.565  5798  5817 D BtGatt.ScanManager: stopping BLe Batch
11-23 14:15:26.566  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:15:26.566  5798  5826 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 14:15:26.566  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 14:15:26.567  5560  5606 D BluetoothAdapter: STATE_ON
11-23 14:15:26.567  5798  5839 D BtGatt.GattService: stopScan() - queue size =0
11-23 14:15:26.568  5798  5837 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 14:15:26.568  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 14:15:26.568  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.568  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 14:15:26.568  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.568  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.568  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.568  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.568  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 14:15:26.568  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.569  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.569  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.569  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 14:15:26.569  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-23 14:15:26.569  5798  5814 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 14:15:26.569  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.569  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 14:15:26.569  5798  5817 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 14:15:26.570  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.571  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.571  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:15:26.571  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.571  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.571  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:15:26.572  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:15:26.572  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.572  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:15:26.572  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da5e8d removed from the list
,11-23 14:15:26.572  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:15:26.572  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 14:15:26.572  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 14:15:26.572  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:15:26.572  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.572  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 14:15:26.572  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-23 14:15:26.572  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 14:15:26.572  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.572  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4f6324 removed from the list
11-23 14:15:26.572  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.572  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.572  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 14:15:26.573  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 14:15:26.573  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.573  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.573  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf7c68e added. We now have 3 listener(s)
11-23 14:15:26.574  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.574  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 14:15:26.574  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 14:15:26.574  5798  5814 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 14:15:26.574  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.574  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 14:15:26.574  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 14:15:26.574  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 14:15:26.574  3527  5890 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-23 14:15:26.575  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 14:15:26.575  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d2feaf added. We now have 4 listener(s)
11-23 14:15:26.575  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 14:15:26.575  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 14:15:26.576  5798  5817 D BtGatt.ScanManager: handling starting scan
11-23 14:15:26.577  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 14:15:26.577  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc9f2bc added. We now have 4 listener(s)
11-23 14:15:26.577  3527  5890 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-23 14:15:26.578  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 14:15:26.578  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 14:15:26.578  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 14:15:26.578  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 14:15:26.578  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659d245 added. We now have 5 listener(s)
11-23 14:15:26.578  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 14:15:26.578  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 14:15:26.579  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:15:26.579  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 14:15:26.579  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:15:26.579  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:15:26.579  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 14:15:26.579  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf7c68e removed from the list
11-23 14:15:26.579  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.579  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d2feaf removed from the list
11-23 14:15:26.579  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
11-23 14:15:26.579  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.580  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.581  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.581  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.581  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.581  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:15:26.581  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 14:15:26.581  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.581  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d2feaf not in the list
11-23 14:15:26.581  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,11-23 14:15:26.581  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.583  5798  5814 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 14:15:26.583  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.583  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.583  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.583  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-23 14:15:26.583  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 14:15:26.583  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 14:15:26.583  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 14:15:26.583  5798  5817 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 14:15:26.583  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659d245 removed from the list
11-23 14:15:26.583  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 14:15:26.583  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 14:15:26.583  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-23 14:15:26.583  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc9f2bc removed from the list
11-23 14:15:26.584  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-23 14:15:26.584  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-23 14:15:26.584  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-23 14:15:26.584  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 14:15:26.584  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,11-23 14:15:26.584  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 14:15:26.588  5798  5814 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 14:15:26.588  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.588  5798  5817 D BtGatt.ScanManager: Starting BLE batch scan
11-23 14:15:26.588  5798  5817 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 14:15:26.597  5798  5814 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 14:15:26.597  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 14:15:26.602  5798  5814 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 14:15:26.602  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 14:15:26.604  3527  5890 W Uploader:  no longer exists, so no auth token.
11-23 14:15:26.604  5798  5817 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 14:15:26.609  3527  5893 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 14:15:26.610  5798  5814 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 14:15:26.610  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.611  5798  5814 E BtGatt.ContextMap: Context not found for ID 5
,11-23 14:15:26.617  5798  5814 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 14:15:26.618  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.618  5798  5817 D BtGatt.ScanManager: stopping BLe Batch
,11-23 14:15:26.623  5798  5814 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 14:15:26.623  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 14:15:26.623  5798  5817 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 14:15:26.627  5798  5814 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 14:15:26.627  5798  5814 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 14:15:26.873  3527  5896 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 14:15:26.980  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 14:15:27.013  3527  5890 W Uploader:  no longer exists, so no auth token.
,11-23 14:15:27.021  3527  5893 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 14:15:27.030  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 14:15:27.073  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 14:15:27.089  3527  5896 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 14:15:27.166  3527  5893 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 14:15:27.254  3527  5896 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 14:15:27.638   931  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,11-23 14:15:27.653   931  2933 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:15:27.659  3678  3819 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-23 14:15:27.660  3678  3819 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 14:15:28.720  5560  5901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 14:15:28.720  5560  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 14:15:29.522  5560  5901 W !!      : call onHalfStreamCopied
,11-23 14:15:29.522  5560  5901 I testCopyDataAndClose: closing input stream
,11-23 14:15:30.277  5560  5901 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 14:15:30.277  5560  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 14:15:30.277  5560  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 14:15:30.277  5560  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 14:15:30.278  5560  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 14:15:30.278  5560  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 14:15:30.278  5560  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-23 14:15:30.278  5560  5901 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 14:15:30.278  5560  5901 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 14:15:30.278  5560  5901 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 14:15:30.278  5560  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 14:15:33.814   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:34.259   931  2933 D ConnectivityService: handlePromptUnvalidated 102
,11-23 14:15:34.473  5560  5902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
11-23 14:15:34.473  5560  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 14:15:34.815   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:35.110   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:15:35.817   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:36.473  5560  5606 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 177. Connection data: Peer properties: [null null].
11-23 14:15:36.473  5560  5606 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 14:15:36.473  5560  5606 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 177, name: My test thread name)
,11-23 14:15:36.571  5560  5903 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 14:15:36.571  5560  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 14:15:36.657  5560  5902 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-23 14:15:36.657  5560  5902 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
11-23 14:15:36.657  5560  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,11-23 14:15:36.819   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:37.373   931  2931 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-23 14:15:37.820   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:38.262  5560  5903 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 14:15:38.262  5560  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 14:15:38.262  5560  5903 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 14:15:38.262  5560  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 14:15:38.263  5560  5903 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing,
11-23 14:15:38.263  5560  5903 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 14:15:38.263  5560  5903 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 14:15:38.263  5560  5903 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 14:15:38.263  5560  5903 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 14:15:38.263  5560  5903 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 14:15:38.263  5560  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 14:15:38.821   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 14:15:41.167   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:15:42.385  5560  5905 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-23 14:15:42.385  5560  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 14:15:42.385  5560  5905 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 181, thread name: My test thread name). Connection data: Peer properties: [null null].
11-23 14:15:42.385  5560  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 14:15:42.385  5560  5905 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 14:15:42.385  5560  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 14:15:42.385  5560  5905 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 14:15:42.385  5560  5905 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 14:15:42.386  5560  5905 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-23 14:15:42.386  5560  5905 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 14:15:42.386  5560  5905 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 14:15:42.386  5560  5905 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-23 14:15:42.386  5560  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-23 14:15:42.388  5560  5606 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-23 14:15:42.391  5560  5906 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-23 14:15:42.391  5560  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 14:15:42.392  5560  5906 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 185, thread name: My test thread name): Test exception.
,11-23 14:15:42.392  5560  5906 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-23 14:15:42.392  5560  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-23 14:15:42.392  5560  5906 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-23 14:15:42.392  5560  5906 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-23 14:15:42.392  5560  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-23 14:15:42.397  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-23 14:15:42.397  5560  5606 I jxcore-log: 
11-23 14:15:42.398  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-23 14:15:42.398  5560  5606 I jxcore-log: 
,11-23 14:15:42.398  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-23 14:15:42.398  5560  5606 I jxcore-log: 
11-23 14:15:42.398  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-23 14:15:42.398  5560  5606 I jxcore-log: 
11-23 14:15:42.399  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG UnitTest_app: 'Total duration:  91547'
11-23 14:15:42.399  5560  5606 I jxcore-log: 
,11-23 14:15:42.401  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-23 14:15:42.401  5560  5606 I jxcore-log: 
,11-23 14:15:42.406  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 14:15:42.406  5560  5606 I jxcore-log: 
,11-23 14:15:42.408  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 14:15:42.408  5560  5606 I jxcore-log: 
,11-23 14:15:42.408  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 14:15:42.408  5560  5606 I jxcore-log: 
11-23 14:15:42.408  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 14:15:42.408  5560  5606 I jxcore-log: 
,11-23 14:15:42.408  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 14:15:42.408  5560  5606 I jxcore-log: 
,11-23 14:15:42.409  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 14:15:42.409  5560  5606 I jxcore-log: 
,11-23 14:15:42.409  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 14:15:42.409  5560  5606 I jxcore-log: 
,11-23 14:15:42.409  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 14:15:42.409  5560  5606 I jxcore-log: 
11-23 14:15:42.410  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 14:15:42.410  5560  5606 I jxcore-log: 
11-23 14:15:42.410  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 14:15:42.410  5560  5606 I jxcore-log: 
11-23 14:15:42.410  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 14:15:42.410  5560  5606 I jxcore-log: 
,11-23 14:15:42.410  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 14:15:42.410  5560  5606 I jxcore-log: 
11-23 14:15:42.411  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 14:15:42.411  5560  5606 I jxcore-log: 
11-23 14:15:42.411  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 14:15:42.411  5560  5606 I jxcore-log: 
,11-23 14:15:42.411  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 14:15:42.411  5560  5606 I jxcore-log: 
11-23 14:15:42.411  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 14:15:42.411  5560  5606 I jxcore-log: 
11-23 14:15:42.411  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 14:15:42.411  5560  5606 I jxcore-log: 
11-23 14:15:42.412  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","ssidName":"<unknown ssid>"}'
11-23 14:15:42.412  5560  5606 I jxcore-log: 
11-23 14:15:42.412  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 14:15:42.412  5560  5606 I jxcore-log: 
,11-23 14:15:42.412  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 14:15:42.412  5560  5606 I jxcore-log: 
11-23 14:15:42.413  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 14:15:42.413  5560  5606 I jxcore-log: 
11-23 14:15:42.413  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 14:15:42.413  5560  5606 I jxcore-log: 
,11-23 14:15:42.413  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 14:15:42.413  5560  5606 I jxcore-log: 
11-23 14:15:42.414  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 14:15:42.414  5560  5606 I jxcore-log: 
11-23 14:15:42.415  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 14:15:42.415  5560  5606 I jxcore-log: 
,11-23 14:15:42.415  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 14:15:42.415  5560  5606 I jxcore-log: 
11-23 14:15:42.416  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 14:15:42.416  5560  5606 I jxcore-log: 
11-23 14:15:42.416  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 14:15:42.416  5560  5606 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,11-23 14:15:42.416  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 14:15:42.416  5560  5606 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-23 14:15:42.416  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 14:15:42.416  5560  5606 I jxcore-log: 
,11-23 14:15:42.417  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 14:15:42.417  5560  5606 I jxcore-log: 
11-23 14:15:42.417  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 14:15:42.417  5560  5606 I jxcore-log: 
11-23 14:15:42.417  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 14:15:42.417  5560  5606 I jxcore-log: 
,11-23 14:15:42.417  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 14:15:42.417  5560  5606 I jxcore-log: 
11-23 14:15:42.417  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 14:15:42.417  5560  5606 I jxcore-log: 
11-23 14:15:42.422  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-23 14:15:42.422  5560  5606 I jxcore-log: 
11-23 14:15:42.423  5560  5606 I jxcore-log: 2016-11-23 13:15:42 - WARN testUtils: 'myNameCallback not set!'
11-23 14:15:42.423  5560  5606 I jxcore-log: 
,11-23 14:15:42.425  5560  5560 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-23 14:15:44.496  5560  5606 I jxcore-log: 2016-11-23 13:15:44 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-23 14:15:44.496  5560  5606 I jxcore-log: 
,11-23 14:15:44.497  5560  5606 I jxcore-log: 2016-11-23 13:15:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-23 14:15:44.497  5560  5606 I jxcore-log: 
,11-23 14:15:44.843  5560  5606 I jxcore-log: 2016-11-23 13:15:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-23 14:15:44.843  5560  5606 I jxcore-log: 
,11-23 14:15:44.854  5560  5606 I jxcore-log: 2016-11-23 13:15:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-23 14:15:44.854  5560  5606 I jxcore-log: 
,11-23 14:15:45.960  5560  5606 I jxcore-log: 2016-11-23 13:15:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-23 14:15:45.960  5560  5606 I jxcore-log: 
,11-23 14:15:46.151  5560  5606 I jxcore-log: 2016-11-23 13:15:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-23 14:15:46.151  5560  5606 I jxcore-log: 
,11-23 14:15:46.157  5560  5606 I jxcore-log: 2016-11-23 13:15:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-23 14:15:46.157  5560  5606 I jxcore-log: 
,11-23 14:15:46.162  5560  5606 I jxcore-log: 2016-11-23 13:15:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-23 14:15:46.162  5560  5606 I jxcore-log: 
,11-23 14:15:46.648  5560  5606 I jxcore-log: 2016-11-23 13:15:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-23 14:15:46.648  5560  5606 I jxcore-log: 
,11-23 14:15:46.693  5560  5606 I jxcore-log: 2016-11-23 13:15:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-23 14:15:46.693  5560  5606 I jxcore-log: 
,11-23 14:15:46.706  5560  5606 I jxcore-log: 2016-11-23 13:15:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-23 14:15:46.706  5560  5606 I jxcore-log: 
,11-23 14:15:46.710  5560  5606 I jxcore-log: 2016-11-23 13:15:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-23 14:15:46.710  5560  5606 I jxcore-log: 
,11-23 14:15:46.980  5560  5606 I jxcore-log: 2016-11-23 13:15:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-23 14:15:46.980  5560  5606 I jxcore-log: 
,11-23 14:15:47.107  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-23 14:15:47.107  5560  5606 I jxcore-log: 
,11-23 14:15:47.260   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=176690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:15:47.493  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-23 14:15:47.493  5560  5606 I jxcore-log: 
,11-23 14:15:47.501  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-23 14:15:47.501  5560  5606 I jxcore-log: 
,11-23 14:15:47.505  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-23 14:15:47.505  5560  5606 I jxcore-log: 
,11-23 14:15:47.511  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-23 14:15:47.511  5560  5606 I jxcore-log: 
,11-23 14:15:47.517  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-23 14:15:47.517  5560  5606 I jxcore-log: 
,11-23 14:15:47.545  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-23 14:15:47.545  5560  5606 I jxcore-log: 
,11-23 14:15:47.580  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-23 14:15:47.580  5560  5606 I jxcore-log: 
,11-23 14:15:47.587  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-23 14:15:47.587  5560  5606 I jxcore-log: 
,11-23 14:15:47.594  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-23 14:15:47.594  5560  5606 I jxcore-log: 
,11-23 14:15:47.609  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-23 14:15:47.609  5560  5606 I jxcore-log: 
,11-23 14:15:47.625  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-23 14:15:47.625  5560  5606 I jxcore-log: 
,11-23 14:15:47.631  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-23 14:15:47.631  5560  5606 I jxcore-log: 
,11-23 14:15:47.637  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-23 14:15:47.637  5560  5606 I jxcore-log: 
,11-23 14:15:47.650  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-23 14:15:47.650  5560  5606 I jxcore-log: 
,11-23 14:15:47.667  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-23 14:15:47.667  5560  5606 I jxcore-log: 
,11-23 14:15:47.682  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-23 14:15:47.682  5560  5606 I jxcore-log: 
,11-23 14:15:47.693  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-23 14:15:47.693  5560  5606 I jxcore-log: 
,11-23 14:15:47.705  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-23 14:15:47.705  5560  5606 I jxcore-log: 
,11-23 14:15:47.716  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-23 14:15:47.716  5560  5606 I jxcore-log: 
,11-23 14:15:47.729  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-23 14:15:47.729  5560  5606 I jxcore-log: 
,11-23 14:15:47.739  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-23 14:15:47.739  5560  5606 I jxcore-log: 
,11-23 14:15:47.746  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-23 14:15:47.746  5560  5606 I jxcore-log: 
,11-23 14:15:47.768  5560  5606 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-23 14:15:47.769  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO testUtils: 'BLE multiple advertisement supported'
11-23 14:15:47.769  5560  5606 I jxcore-log: 
,11-23 14:15:47.804  5560  5606 I jxcore-log: 2016-11-23 13:15:47 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-23 14:15:47.804  5560  5606 I jxcore-log: 
,11-23 14:15:48.030  5560  5606 I jxcore-log: 2016-11-23 13:15:48 - DEBUG CoordinatedClient: 'connected to the test server'
11-23 14:15:48.030  5560  5606 I jxcore-log: 
,11-23 14:15:50.214   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:15:52.846   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=182277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 14:15:53.237   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:15:56.263   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:15:58.822   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:15:59.823   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:00.824   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:01.826   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:02.315   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:16:02.827   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:03.828   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 14:16:06.232   931  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 14:16:07.953   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=197384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:16:18.033   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=207463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 14:16:20.499   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:16:23.529   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:16:26.546   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:16:28.829   565   565 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 14:16:28.829   565   565 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 14:16:29.572   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:16:30.117  5854  5854 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 14:16:33.020   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=222450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:16:35.621   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:16:38.830   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:39.831   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:40.833   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:41.834   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:42.835   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:43.074   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=232504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-23 14:16:43.836   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 14:16:44.712   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:16:46.236   931  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 14:16:48.837   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:49.838   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:50.762   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:16:50.839   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:51.841   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:52.842   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:16:53.799   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:16:53.844   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 14:16:56.825   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:16:59.859   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:17:03.100   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=252530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:17:03.845   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:04.846   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:05.847   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:05.917   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:17:06.237   931  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 14:17:06.849   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:07.850   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:08.113   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=257543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-23 14:17:08.851   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 14:17:08.945   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:17:18.041   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:17:21.071   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:17:23.852   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:24.853   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:25.855   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:26.856   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:27.125   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:17:27.857   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:28.113   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=277544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:17:28.858   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 14:17:33.127   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=282557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 14:17:33.164   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:17:46.242   931  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 14:17:48.167   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=297597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:17:48.859   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:49.861   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:50.862   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:51.863   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:52.864   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:17:53.865   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 14:17:58.221   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307651, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 14:18:06.246   931  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 14:18:13.233   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=322663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:18:18.866   565   565 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 14:18:18.866   565   565 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 14:18:23.261   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=332690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 14:18:26.248   931  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 14:18:30.672   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:18:33.688   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:18:33.867   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:18:34.869   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:18:35.870   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:18:36.872   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:18:37.873   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:18:38.247   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=347677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:18:38.874   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 14:18:39.747   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:18:42.784   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:18:43.876   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:18:44.877   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:18:45.878   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:18:46.880   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:18:47.881   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:18:48.287   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=357717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 14:18:48.882   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 14:18:58.884   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:18:59.885   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:00.886   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:01.888   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:02.889   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:03.314   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=372744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:19:03.890   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 14:19:06.250   931  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 14:19:07.008   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:19:10.043   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:19:13.341   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=382771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-23 14:19:18.892   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:19.894   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:20.895   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:21.896   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:22.897   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:23.898   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 14:19:26.251   931  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 14:19:33.341   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=402771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:19:38.367   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=407797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 14:19:43.899   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:44.901   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:45.902   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:46.252   931  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 14:19:46.903   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:47.905   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:19:48.905   565   565 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 14:19:53.340   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=422770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:20:03.420   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=432850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 14:20:04.503   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:20:06.253   931  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 14:20:07.539   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:20:13.906   565   565 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 14:20:13.907   565   565 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 14:20:18.407   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=447837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 14:20:19.647   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:20:22.682   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:20:26.254   931  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 14:20:28.434   931  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=457864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 14:20:28.746   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:20:31.787   931  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 14:20:33.908   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:20:34.909   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:20:35.910   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:20:35.983  5560  5606 I jxcore-log: 2016-11-23 13:20:35 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-23 14:20:35.983  5560  5606 I jxcore-log: 
,11-23 14:20:36.314  5560  5606 I jxcore-log: 2016-11-23 13:20:36 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 14:20:36.314  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 14:20:36.314  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 14:20:36.314  5560  5606 I jxcore-log: emit@events.js:82:1
11-23 14:20:36.314  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 14:20:36.314  5560  5606 I jxcore-log: emit@events.js:82:1''
11-23 14:20:36.314  5560  5606 I jxcore-log: 
11-23 14:20:36.316  5560  5606 I jxcore-log: 2016-11-23 13:20:36 - DEBUG CoordinatedClient: 'test client failed'
11-23 14:20:36.316  5560  5606 I jxcore-log: 
,11-23 14:20:36.327  5560  5606 I jxcore-log: 2016-11-23 13:20:36 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 14:20:36.327  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 14:20:36.327  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 14:20:36.327  5560  5606 I jxcore-log: emit@events.js:82:1
11-23 14:20:36.327  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 14:20:36.327  5560  5606 I jxcore-log: emit@events.js:82:1''
11-23 14:20:36.327  5560  5606 I jxcore-log: 
,11-23 14:20:36.328  5560  5606 I jxcore-log: 2016-11-23 13:20:36 - DEBUG CoordinatedClient: 'test client failed'
11-23 14:20:36.328  5560  5606 I jxcore-log: 
,11-23 14:20:36.333  5560  5606 I jxcore-log: 2016-11-23 13:20:36 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 14:20:36.333  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 14:20:36.333  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 14:20:36.333  5560  5606 I jxcore-log: emit@events.js:82:1
11-23 14:20:36.333  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 14:20:36.333  5560  5606 I jxcore-log: emit@events.js:82:1''
11-23 14:20:36.333  5560  5606 I jxcore-log: 
,11-23 14:20:36.335  5560  5606 I jxcore-log: 2016-11-23 13:20:36 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-23 14:20:36.335  5560  5606 I jxcore-log: 
,11-23 14:20:36.912   565   565 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 14:20:36.913  5917  5917 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-23 14:20:36.917  5917  5917 D AndroidRuntime: CheckJNI is OFF
,11-23 14:20:36.941  5917  5917 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-23 14:20:36.970  5917  5917 I Radio-JNI: register_android_hardware_Radio DONE
,11-23 14:20:36.985  5917  5917 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-23 14:20:36.994   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-23 14:20:36.995   931   944 I ActivityManager: Killing 5560:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-23 14:20:37.093   931  3791 D GraphicsStats: Buffer count: 2
11-23 14:20:37.093   931  2932 D WifiService: Client connection lost with reason: 4
,11-23 14:20:37.094   931   941 I WindowState: WIN DEATH: Window{32f81d4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-23 14:20:37.110   931   944 W ActivityManager: Force removing ActivityRecord{4c5b7e5 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-23 14:20:37.137   931   954 I art     : Starting a blocking GC Explicit
,11-23 14:20:37.140   931  3140 W ActivityManager: Spurious death for ProcessRecord{ecb138d 0:com.test.thalitest/u0a77}, curProc for 5560: null
,11-23 14:20:37.168  3541  3541 W Binder_6: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28817]" dev="sockfs" ino=28817 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 14:20:37.170   931  3541 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5560 uid 10077
11-23 14:20:37.172  3607  3607 I Keyboard.Facilitator: onFinishInput()
11-23 14:20:37.168  3541  3541 W Binder_6: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[28817]" dev="sockfs" ino=28817 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 14:20:37.192  3909  3909 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,11-23 14:20:37.242  3909  5932 I MicroRecognitionRnrImpl: Starting detection.
,11-23 14:20:37.245  3909  5933 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@8e2b7cd
,11-23 14:20:37.247   515  5935 I AudioFlinger: AudioFlinger's thread 0xf2240000 ready to run
,11-23 14:20:37.252   515  2934 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-23 14:20:37.255  3909  5933 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@8e2b7cd
,11-23 14:20:37.258   931   954 I art     : Explicit concurrent mark sweep GC freed 133293(9MB) AllocSpace objects, 76(1980KB) LOS objects, 33% free, 29MB/44MB, paused 2.208ms total 120.210ms
,11-23 14:20:37.264   515  5935 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-23 14:20:37.265   515  5935 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-23 14:20:37.265   515  5935 I ACDB-LOADER: ACDB AFE returned = -19
11-23 14:20:37.265   515  5935 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-23 14:20:37.265   515  5935 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-23 14:20:37.265   515  5935 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-23 14:20:37.273   515  5935 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-23 14:20:37.278   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-23 14:20:37.280  5917  5917 I art     : System.exit called, status: 0
11-23 14:20:37.280  5917  5917 I AndroidRuntime: VM exiting with result code 0.
,11-23 14:20:37.298   931   954 I ActivityManager: Start proc 5939:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-23 14:20:37.299   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-23 14:20:37.306  5798  5798 D BluetoothMapAppObserver: onReceive
,11-23 14:20:37.306  5798  5798 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-23 14:20:37.307  4035  4110 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-23 14:20:37.310  3607  3607 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-23 14:20:37.314   931  2912 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-23 14:20:37.326  3607  5949 I Keyboard.Facilitator.DecoderInitializer: run()
,11-23 14:20:37.334  3607  5949 I Decoder : createOrResetDecoder
,11-23 14:20:37.339  3345  5954 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-23 14:20:37.352  3909  3909 I HotwordWorkerImpl: onReady
,11-23 14:20:37.383  3709  3709 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-23 14:20:37.386  3527  3527 I ConfigService: onCreate
,11-23 14:20:37.398    29    29 W kworker/3:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 14:20:37.405    29    29 W kworker/3:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 14:20:37.422   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-23 14:20:37.421  3607  5949 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-23 14:20:37.426  3745  3879 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-23 14:20:37.425    29    29 W kworker/3:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 14:20:37.429  3527  3527 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-23 14:20:37.430  3527  3527 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-23 14:20:37.431  3527  3527 E AndroidRuntime: FATAL EXCEPTION: main
11-23 14:20:37.431  3527  3527 E AndroidRuntime: Process: com.google.process.gapps, PID: 3527
11-23 14:20:37.431  3527  3527 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-23 14:20:37.431  3527  3527 E AndroidRuntime: 	... 8 more
,11-23 14:20:37.443   931  3358 I ActivityManager: Start proc 5959:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-23 14:20:37.443  3745  3879 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-23 14:20:37.443  3745  3879 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3745
11-23 14:20:37.443  3745  3879 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 14:20:37.443  3745  3879 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 14:20:37.443  3745  3879 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 14:20:37.443  3745  3879 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 14:20:37.443  3745  3879 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 14:20:37.443  3745  3879 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 14:20:37.443  3745  3879 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-23 14:20:37.443  3745  3879 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-23 14:20:37.443  3745  3879 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-23 14:20:37.443  3745  3879 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-23 14:20:37.443  3745  3879 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 14:20:37.443  3745  3879 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 14:20:37.451   931  3670 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-23 14:20:37.452   931  5964 E DropBoxManagerService: Can't write: system_app_crash
11-23 14:20:37.452   931  5964 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-23 14:20:37.452   931  5964 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 14:20:37.452   931  5964 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 14:20:37.452   931  5964 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 14:20:37.452   931  5964 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 14:20:37.452   931  5964 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 14:20:37.452   931  5964 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 14:20:37.452   931  5964 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 14:20:37.452   931  5964 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 14:20:37.452   931  5964 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 14:20:37.452   931  5964 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 14:20:37.452   931  5964 E DropBoxManagerService: 	... 5 more
,11-23 14:20:37.454   931  5965 E DropBoxManagerService: Can't write: system_app_crash
11-23 14:20:37.454   931  5965 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-23 14:20:37.454   931  5965 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 14:20:37.454   931  5965 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 14:20:37.454   931  5965 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 14:20:37.454   931  5965 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 14:20:37.454   931  5965 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 14:20:37.454   931  5965 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 14:20:37.454   931  5965 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 14:20:37.454   931  5965 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 14:20:37.454   931  5965 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 14:20:37.454   931  5965 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 14:20:37.454   931  5965 E DropBoxManagerService: 	... 5 more
11-23 14:20:37.455  3909  3924 W SearchService: Abort, client detached.
,11-23 14:20:37.457  3345  5954 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-23 14:20:37.457  3909  3909 I HotwordDetector: Closing mic
11-23 14:20:37.457  3909  4132 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8e2b7cd
11-23 14:20:37.457  3909  5933 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-23 14:20:37.458  3345  5954 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-23 14:20:37.458  3345  5954 E AndroidRuntime: Process: android.process.acore, PID: 3345
11-23 14:20:37.458  3345  5954 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 14:20:37.458  3345  5954 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 14:20:37.465   786   786 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[14279]" dev="sockfs" ino=14279 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 14:20:37.468   786   786 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[14279]" dev="sockfs" ino=14279 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 14:20:37.468   403   403 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[32453]" dev="sockfs" ino=32453 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 14:20:37.468   403   403 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32453]" dev="sockfs" ino=32453 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 14:20:37.471   931  5973 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 14:20:37.492   931  5974 E DropBoxManagerService: Can't write: system_app_crash
11-23 14:20:37.492   931  5974 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-23 14:20:37.492   931  5974 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 14:20:37.492   931  5974 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 14:20:37.492   931  5974 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 14:20:37.492   931  5974 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 14:20:37.492   931  5974 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 14:20:37.492   931  5974 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 14:20:37.492   931  5974 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 14:20:37.492   931  5974 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 14:20:37.492   931  5974 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 14:20:37.492   931  5974 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 14:20:37.492   931  5974 E DropBoxManagerService: 	... 5 more
,11-23 14:20:37.512   931  3979 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-23 14:20:37.530  3607  5949 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-23 14:20:37.533   515  5935 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-23 14:20:37.534   515  5935 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-23 14:20:37.534  3607  5949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-23 14:20:37.534  3607  5949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-23 14:20:37.537  3607  5949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,11-23 14:20:37.538  3607  5949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-23 14:20:37.539  3607  5949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-23 14:20:37.539  3607  5949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-23 14:20:37.540  3607  5949 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-23 14:20:37.540  3607  5949 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-23 14:20:37.540  3607  5949 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-23 14:20:37.541  3607  5949 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-23 14:20:37.541  3607  5949 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-23 14:20:37.541  3607  5949 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-23 14:20:37.543   515  5935 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-23 14:20:37.543   515  5935 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-23 14:20:37.544   515  2934 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-23 14:20:37.546   931  5973 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 14:20:37.546   931  5973 I Adreno  : Build Date                       : 12/06/15
11-23 14:20:37.546   931  5973 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 14:20:37.546   931  5973 I Adreno  : Local Branch                     : mybranch17112971
11-23 14:20:37.546   931  5973 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 14:20:37.546   931  5973 I Adreno  : Remote Branch                    : NONE
11-23 14:20:37.546   931  5973 I Adreno  : Reconstruct Branch               : NOTHING
11-23 14:20:37.547  3909  5932 I MicroRecognitionRnrImpl: Detection finished
11-23 14:20:37.548  3909  4153 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-23 14:20:37.838   382   484 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
