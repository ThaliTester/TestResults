#### Test 94187094ec0e7f2_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of system
11-22 14:22:21.858   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
11-22 14:22:22.327  5653  5653 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-22 14:22:22.332  5653  5653 D AndroidRuntime: CheckJNI is OFF
11-22 14:22:22.356  5653  5653 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-22 14:22:22.389  5653  5653 I Radio-JNI: register_android_hardware_Radio DONE
11-22 14:22:22.403  5653  5653 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-22 14:22:22.418   931  3893 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-22 14:22:22.436  5653  5653 D AndroidRuntime: Shutting down VM
11-22 14:22:22.440  4006  5633 W SearchService: Abort, client detached.
11-22 14:22:22.447  4006  4006 I HotwordDetector: Closing mic
11-22 14:22:22.447  4006  4247 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c6c628c
11-22 14:22:22.447  4006  4269 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-22 14:22:22.468   931  4995 I ActivityManager: Start proc 5662:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-22 14:22:22.531   513  4271 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-22 14:22:22.533   513  4271 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-22 14:22:22.542   513  4271 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-22 14:22:22.542   513  4271 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-22 14:22:22.544   513  3058 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-22 14:22:22.547  4006  4248 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-22 14:22:22.547  4006  4268 I MicroRecognitionRnrImpl: Detection finished
11-22 14:22:22.566  5662  5662 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-22 14:22:22.593  5662  5662 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-22 14:22:22.666  5662  5662 I LibraryLoader: Time to load native libraries: 69 ms (timestamps 6527-6596)
11-22 14:22:22.666  5662  5662 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-22 14:22:22.707  5662  5662 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bd5bd48}
,11-22 14:22:22.708  5662  5662 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-22 14:22:22.708  5662  5662 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-22 14:22:22.714  5662  5662 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-22 14:22:22.715  5662  5662 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-22 14:22:22.762  5662  5662 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-22 14:22:22.776  5662  5662 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-22 14:22:22.776  5662  5662 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-22 14:22:22.776  5662  5662 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-22 14:22:22.776  5662  5662 I Adreno  : Build Date                       : 12/06/15
11-22 14:22:22.776  5662  5662 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-22 14:22:22.776  5662  5662 I Adreno  : Local Branch                     : mybranch17112971
11-22 14:22:22.776  5662  5662 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-22 14:22:22.776  5662  5662 I Adreno  : Remote Branch                    : NONE
11-22 14:22:22.776  5662  5662 I Adreno  : Reconstruct Branch               : NOTHING
,11-22 14:22:22.841   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@896039c:true
,11-22 14:22:22.876   410   410 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[21343]" dev="sockfs" ino=21343 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 14:22:22.876   410   410 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[21343]" dev="sockfs" ino=21343 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 14:22:22.892  5662  5662 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-22 14:22:22.901  5662  5662 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-22 14:22:22.926   762   762 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33125]" dev="sockfs" ino=33125 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 14:22:22.926   762   762 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33125]" dev="sockfs" ino=33125 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 14:22:22.929  5662  5699 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-22 14:22:22.929  3893  3893 W Binder_8: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[21355]" dev="sockfs" ino=21355 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 14:22:22.929  3893  3893 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[21355]" dev="sockfs" ino=21355 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 14:22:22.935  5662  5686 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-22 14:22:22.965  5662  5699 I OpenGLRenderer: Initialized EGL, version 1.4
,11-22 14:22:23.049  3216  3216 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33128]" dev="sockfs" ino=33128 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 14:22:23.053  3216  3216 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33128]" dev="sockfs" ino=33128 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 14:22:23.056   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +612ms
11-22 14:22:23.059  3718  3718 I Keyboard.Facilitator: onFinishInput()
,11-22 14:22:23.053  4994  4994 W Binder_9: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33127]" dev="sockfs" ino=33127 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 14:22:23.053  4994  4994 W Binder_9: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33127]" dev="sockfs" ino=33127 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 14:22:23.095  5662  5662 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5662
,11-22 14:22:23.186  5662  5662 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-22 14:22:23.271   931  4994 I ActivityManager: Killing 5326:com.android.settings/1000 (adj 15): empty #17
,11-22 14:22:23.295   931  4994 I ActivityManager: Killing 5285:org.codeaurora.ims/1001 (adj 15): empty #18
,11-22 14:22:23.358  5662  5702 D jxcore_app_log: JniHelper::setJavaVM(0xf4ebc000), pthread_self() = -607385296
,11-22 14:22:23.361  5662  5702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-22 14:22:23.361  5662  5702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-22 14:22:23.361  5662  5702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-22 14:22:23.361  5662  5702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-22 14:22:23.361  5662  5702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-22 14:22:23.362  5662  5702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef1984c added. We now have 1 listener(s)
,11-22 14:22:23.364  5662  5702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-22 14:22:23.364  5662  5702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 14:22:23.365  5662  5702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 14:22:23.365  5662  5702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-22 14:22:23.367  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8a59b added. We now have 1 listener(s)
11-22 14:22:23.367  5662  5702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:22:23.371   931  3037 D WifiService: New client listening to asynchronous messages
,11-22 14:22:23.372  5662  5702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 14:22:23.372  5662  5702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-22 14:22:23.372  5662  5702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-22 14:22:23.372  5662  5702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-22 14:22:23.372  5662  5702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-22 14:22:23.372  5662  5702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-22 14:22:23.372  5662  5702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-22 14:22:23.374  5662  5702 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-22 14:22:23.473  5662  5662 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-22 14:22:23.961  5662  5709 W jxcore-log: Initializing JXcore engine
,11-22 14:22:23.961  5662  5709 W jxcore-log: JXcore engine is ready
,11-22 14:22:23.983  5709  5709 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12899 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-22 14:22:23.983  5709  5709 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14444]" dev="sockfs" ino=14444 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-22 14:22:23.983  5709  5709 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-22 14:22:23.983  5709  5709 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29564]" dev="sockfs" ino=29564 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-22 14:22:23.994  5662  5709 W jxcore-log: Starting JXcore engine
,11-22 14:22:24.045  5662  5709 W jxcore-log: Platform android
11-22 14:22:24.045  5662  5709 W jxcore-log: 
,11-22 14:22:24.045  5662  5709 W jxcore-log: Process ARCH arm
11-22 14:22:24.045  5662  5709 W jxcore-log: 
,11-22 14:22:24.231  5662  5709 I jxcore-log: JXcore Cordova bridge is ready!
11-22 14:22:24.231  5662  5709 I jxcore-log: 
,11-22 14:22:24.232  5662  5709 W jxcore-log: JXcore engine is started
,11-22 14:22:24.241  5662  5702 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-22 14:22:24.248  5662  5662 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-22 14:22:24.627   931  5421 D NetlinkSocketObserver: NeighborEvent{elapsedMs=178557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:22:30.929   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:22:32.616   931  3037 D WifiService: New client listening to asynchronous messages
,11-22 14:22:32.619  4006  5710 W CronetSyncConnectionRcs: Upload content type not set.
,11-22 14:22:34.120  5662  5709 I jxcore-log: 2016-11-22 13:22:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-22 14:22:34.120  5662  5709 I jxcore-log: 
,11-22 14:22:34.122  5662  5709 I jxcore-log: 2016-11-22 13:22:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-22 14:22:34.122  5662  5709 I jxcore-log: 
,11-22 14:22:34.127  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-22 14:22:34.127  5662  5709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 14:22:34.127  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:22:34.127  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:22:34.127  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:22:34.127  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:22:34.127  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 14:22:34.127  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 14:22:34.127  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 14:22:34.127  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 14:22:34.129  5662  5709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 14:22:34.131  5662  5709 I jxcore-log: 2016-11-22 13:22:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-22 14:22:34.131  5662  5709 I jxcore-log: 
11-22 14:22:34.132  5662  5709 I jxcore-log: 2016-11-22 13:22:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-22 14:22:34.132  5662  5709 I jxcore-log: 
,11-22 14:22:34.383  5662  5709 I jxcore-log: 2016-11-22 13:22:34 - DEBUG UnitTest_app: 'Running unit tests'
11-22 14:22:34.383  5662  5709 I jxcore-log: 
,11-22 14:22:34.384  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 14:22:34.384  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d54170b added. We now have 2 listener(s)
,11-22 14:22:34.385  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 14:22:34.385  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 14:22:34.385  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 14:22:34.385  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 14:22:34.385  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95559e8 added. We now have 2 listener(s)
,11-22 14:22:34.385  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:22:34.386  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 14:22:34.387  5662  5709 D executeNativeTests: Running unit tests
,11-22 14:22:34.427  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 14:22:34.427  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 added. We now have 3 listener(s)
,11-22 14:22:34.427  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 14:22:34.427  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:22:34.427  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:22:34.428  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:22:34.428  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 added. We now have 3 listener(s)
11-22 14:22:34.428  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:22:34.428  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 14:22:34.430  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 14:22:34.430  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-22 14:22:34.430  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 14:22:34.431  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 14:22:34.431  5662  5709 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-22 14:22:34.431  5662  5709 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 14:22:34.431  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 14:22:34.431  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 14:22:34.431  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 14:22:34.431  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 14:22:34.432  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:22:34.432  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:34.432  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:34.432  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:34.432  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:34.432  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:22:34.432  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 removed from the list
11-22 14:22:34.433  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:34.433  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 removed from the list
11-22 14:22:34.433  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:22:34.433  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.433  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.434  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.434  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.434  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.434  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:34.434  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:34.434  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:34.434  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:34.435  5662  5709 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-22 14:22:34.435  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:22:34.435  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:34.435  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:34.435  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:34.435  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:34.435  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:34.435  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:34.435  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:34.435  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:22:34.435  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.435  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.436  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.436  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.436  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:34.436  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:34.436  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:34.436  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:34.436  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-22 14:22:34.439  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 14:22:34.440  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 14:22:34.440  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:22:34.440  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:34.440  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:34.440  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 14:22:34.440  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:34.440  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:34.440  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:34.440  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:34.440  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:34.440  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.440  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:34.440  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.441  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.441  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.441  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:34.441  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 14:22:34.441  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:34.441  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:34.441  5662  5709 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-22 14:22:34.442  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:22:34.442  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 14:22:34.453  5662  5709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 14:22:34.453  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:22:34.453  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:22:34.453  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:22:34.453  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:22:34.453  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 14:22:34.453  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 14:22:34.453  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 14:22:34.453  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 14:22:34.456  5662  5709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 14:22:34.456  5662  5709 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 14:22:34.456  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:22:34.456  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-22 14:22:34.456  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 14:22:34.456  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:22:34.457  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 14:22:34.458  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-22 14:22:34.458  5662  5709 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 14:22:34.458  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 14:22:34.460  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:22:34.462  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:34.462  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 14:22:34.462  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 14:22:34.463  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 14:22:34.463  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 14:22:34.464  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:22:34.465  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-22 14:22:34.466  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-22 14:22:34.466  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:34.466  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-22 14:22:34.467  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 14:22:34.467  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 14:22:34.467  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 14:22:34.467  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.467  5662  5709 D BluetoothAdapter: STATE_ON
,11-22 14:22:34.469  4714  4727 D BtGatt.GattService: registerClient() - UUID=3735407f-e043-44c1-8165-2f985c946392
11-22 14:22:34.470  4714  4776 D BtGatt.GattService: onClientRegistered() - UUID=3735407f-e043-44c1-8165-2f985c946392, clientIf=5
11-22 14:22:34.470  5662  5672 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-22 14:22:34.472  4714  4932 D BtGatt.GattService: start scan with filters
,11-22 14:22:34.477  4714  4779 D BtGatt.ScanManager: handling starting scan
11-22 14:22:34.477  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 14:22:34.477  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.477  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 14:22:34.477  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.478  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 14:22:34.478  5662  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 14:22:34.478  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:22:34.478  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 14:22:34.478  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 14:22:34.478  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-22 14:22:34.478  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.478  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:22:34.478  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 14:22:34.479  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:22:34.479  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.479  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.479  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 14:22:34.479  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:34.479  4714  4779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
11-22 14:22:34.479  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:22:34.479  5662  5709 I io.jxcore.node.ConnectionHelper: start: OK
,11-22 14:22:34.482  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:22:34.482  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 14:22:34.483  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:22:34.483  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:22:34.483  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 14:22:34.487  4714  4776 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 14:22:34.487  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:22:34.487  4714  4779 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 14:22:34.494  4714  4776 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 14:22:34.494  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:22:34.495  4714  4779 D BtGatt.ScanManager: Starting BLE batch scan
11-22 14:22:34.495  4714  4779 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 14:22:34.508  4714  4776 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 14:22:34.508  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:22:34.514  4714  4776 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 14:22:34.514  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:22:34.984  5662  5662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-22 14:22:34.985  5662  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 14:22:34.985  5662  5662 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 14:22:35.877   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:22:36.878   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:22:37.667   931  5421 D NetlinkSocketObserver: NeighborEvent{elapsedMs=191597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:22:37.879   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:22:38.880   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:22:39.484  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:22:39.484  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-22 14:22:39.484  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 14:22:39.484  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:22:39.484  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 14:22:39.484  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:39.485  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 14:22:39.485  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:22:39.485  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.485  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:22:39.485  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 14:22:39.486  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.486  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.486  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.486  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 14:22:39.487  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.488  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:22:39.488  4714  4932 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-22 14:22:39.488  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 14:22:39.489  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:22:39.490  4714  4779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 14:22:39.491  4714  4924 D BtGatt.GattService: stopScan() - queue size =1
,11-22 14:22:39.494  4714  4727 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 14:22:39.495  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 14:22:39.497  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.497  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-22 14:22:39.497  4714  4714 D BtGatt.ScanManager: awakened up at time 193427
11-22 14:22:39.497  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.497  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.497  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.498  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.498  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-22 14:22:39.499  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.499  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.499  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.500  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 14:22:39.500  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-22 14:22:39.502  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:22:39.502  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.505  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.505  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:22:39.506  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:39.506  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:39.506  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:39.506  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:22:39.506  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:22:39.506  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:22:39.506  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:22:39.506  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:39.507  5662  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 14:22:39.507  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:22:39.507  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:39.507  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:39.507  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 14:22:39.507  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:39.507  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 14:22:39.507  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:39.507  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:22:39.507  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 14:22:39.507  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 14:22:39.507  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:22:39.508  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:22:39.508  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 14:22:39.508  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:22:39.511  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:22:39.511  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:22:39.511  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 14:22:39.525  4714  4776 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-22 14:22:39.525  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:22:39.525  4714  4776 D BtGatt.GattService: current time is 193456324557
11-22 14:22:39.526  4714  4776 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -99, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -90, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-22 14:22:39.527  4714  4776 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-22 14:22:39.529  4714  4776 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-22 14:22:39.529  4714  4776 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-22 14:22:39.529  4714  4776 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-22 14:22:39.537  4714  4776 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 14:22:39.537  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:22:39.537  4714  4779 D BtGatt.ScanManager: stopping BLe Batch
,11-22 14:22:39.544  4714  4776 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 14:22:39.545  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:22:39.545  4714  4779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 14:22:39.552  4714  4776 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 14:22:39.552  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:22:39.881   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:22:40.008  5662  5662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 14:22:40.017   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:22:40.882   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 14:22:44.513  5662  5709 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-22 14:22:44.518  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 14:22:44.519  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 14:22:44.532  5662  5709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 14:22:44.532  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:22:44.532  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:22:44.532  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:22:44.532  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:22:44.532  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 14:22:44.532  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 14:22:44.532  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 14:22:44.532  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 14:22:44.535  5662  5709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 14:22:44.535  5662  5709 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-22 14:22:44.536  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:22:44.536  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 14:22:44.536  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 14:22:44.536  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 14:22:44.536  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 14:22:44.540  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:22:44.542  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 14:22:44.542  5662  5709 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-22 14:22:44.542  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 14:22:44.545  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:22:44.549  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.549  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 14:22:44.550  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-22 14:22:44.550  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 14:22:44.550  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 14:22:44.556  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:44.556  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 14:22:44.556  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-22 14:22:44.556  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 14:22:44.556  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 14:22:44.556  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:44.557  5662  5709 D BluetoothAdapter: STATE_ON
,11-22 14:22:44.561  4714  4932 D BtGatt.GattService: registerClient() - UUID=769a31b7-fc15-43d3-9601-449db3879659
,11-22 14:22:44.562  4714  4776 D BtGatt.GattService: onClientRegistered() - UUID=769a31b7-fc15-43d3-9601-449db3879659, clientIf=5
,11-22 14:22:44.562  5662  5672 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 14:22:44.563  4714  4924 D BtGatt.GattService: start scan with filters
,11-22 14:22:44.567  4714  4779 D BtGatt.ScanManager: handling starting scan
11-22 14:22:44.568  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 14:22:44.568  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.569  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 14:22:44.569  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.569  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-22 14:22:44.569  5662  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 14:22:44.569  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.569  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 14:22:44.569  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 14:22:44.569  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.569  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.570  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.570  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-22 14:22:44.571  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 14:22:44.571  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.574  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.574  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 14:22:44.574  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.574  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.574  5662  5709 I io.jxcore.node.ConnectionHelper: start: OK
11-22 14:22:44.575  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.575  4714  4776 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 14:22:44.575  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:22:44.576  4714  4779 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 14:22:44.578  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:22:44.578  5662  5709 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 14:22:44.578  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:44.579  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 14:22:44.579  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:22:44.582  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.582  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.582  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 14:22:44.582  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:22:44.583  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 14:22:44.583  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:44.583  4714  4776 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 14:22:44.583  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 14:22:44.583  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:22:44.583  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:22:44.583  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.583  4714  4779 D BtGatt.ScanManager: Starting BLE batch scan
11-22 14:22:44.583  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:22:44.583  4714  4779 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 14:22:44.583  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 14:22:44.583  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.584  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.584  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.584  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 14:22:44.584  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.585  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:22:44.585  4714  4932 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 14:22:44.586  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 14:22:44.586  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:22:44.587  4714  4727 D BtGatt.GattService: stopScan() - queue size =1
,11-22 14:22:44.588  4714  4932 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 14:22:44.589  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-22 14:22:44.589  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.589  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 14:22:44.589  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.590  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.590  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.590  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.590  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 14:22:44.590  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.590  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.590  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.590  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 14:22:44.590  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-22 14:22:44.591  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:22:44.591  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.596  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.596  4714  4776 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 14:22:44.597  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:22:44.597  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:22:44.597  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.597  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:44.597  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:44.597  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:22:44.597  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:22:44.597  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:44.597  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:22:44.597  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:44.598  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:22:44.598  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:44.598  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:44.598  5662  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-22 14:22:44.598  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:44.598  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.598  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 14:22:44.598  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 14:22:44.598  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 14:22:44.598  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.598  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.598  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.598  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 14:22:44.598  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.598  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.600  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.600  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.600  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 14:22:44.600  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.601  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.602  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:44.602  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.602  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.602  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:44.602  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:44.602  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:22:44.602  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:44.603  5662  5709 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-22 14:22:44.604  4714  4776 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 14:22:44.604  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:22:44.605  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 14:22:44.605  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 14:22:44.606  4714  4779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:22:44.610  5662  5709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 14:22:44.610  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:22:44.610  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:22:44.610  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:22:44.610  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:22:44.610  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 14:22:44.610  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 14:22:44.610  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 14:22:44.610  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 14:22:44.612  4714  4776 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 14:22:44.612  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:22:44.612  4714  4776 E BtGatt.ContextMap: Context not found for ID 5
,11-22 14:22:44.613  5662  5709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 14:22:44.613  5662  5709 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 14:22:44.614  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:22:44.614  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 14:22:44.614  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-22 14:22:44.614  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:22:44.614  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 14:22:44.617  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:22:44.619  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 14:22:44.619  5662  5709 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-22 14:22:44.619  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 14:22:44.620  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:22:44.620  4714  4776 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 14:22:44.621  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:22:44.621  4714  4779 D BtGatt.ScanManager: stopping BLe Batch
,11-22 14:22:44.624  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.624  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 14:22:44.624  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 14:22:44.624  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 14:22:44.625  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 14:22:44.626  4714  4776 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 14:22:44.626  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:22:44.626  4714  4779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 14:22:44.627  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:44.628  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 14:22:44.628  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 14:22:44.628  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 14:22:44.628  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 14:22:44.628  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.628  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:22:44.631  4714  4727 D BtGatt.GattService: registerClient() - UUID=e7be64fc-ee99-4bb4-aa4c-c7301c19bc5c
11-22 14:22:44.631  4714  4776 D BtGatt.GattService: onClientRegistered() - UUID=e7be64fc-ee99-4bb4-aa4c-c7301c19bc5c, clientIf=5
11-22 14:22:44.631  5662  5673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 14:22:44.632  4714  4924 D BtGatt.GattService: start scan with filters
11-22 14:22:44.632  4714  4776 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 14:22:44.633  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:22:44.635  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 14:22:44.635  4714  4779 D BtGatt.ScanManager: handling starting scan
11-22 14:22:44.635  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.635  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 14:22:44.635  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.635  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 14:22:44.635  5662  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 14:22:44.635  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.635  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 14:22:44.635  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 14:22:44.635  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.635  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.635  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.636  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.636  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 14:22:44.636  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.639  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.639  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:22:44.639  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.639  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:44.639  5662  5709 I io.jxcore.node.ConnectionHelper: start: OK
11-22 14:22:44.639  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.641  4714  4776 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 14:22:44.641  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:22:44.641  4714  4779 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 14:22:44.641  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.641  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.641  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:22:44.642  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 14:22:44.646  4714  4776 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-22 14:22:44.646  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:22:44.646  4714  4779 D BtGatt.ScanManager: Starting BLE batch scan
11-22 14:22:44.646  4714  4779 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 14:22:44.655  4714  4776 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 14:22:44.655  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:22:44.660  4714  4776 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 14:22:44.660  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:22:45.143  5662  5662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-22 14:22:45.143  5662  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:22:45.143  5662  5662 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 14:22:46.071   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:22:46.078   931  3038 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-22 14:22:48.588   931  3036 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:22:49.100   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:22:49.106   931  3038 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-22 14:22:49.639  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:22:49.640  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:49.640  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 14:22:49.640  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:22:49.640  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 14:22:49.641  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:49.641  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 14:22:49.641  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:22:49.641  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.641  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:22:49.641  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 14:22:49.642  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.642  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.642  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.642  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 14:22:49.643  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.645  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:22:49.645  4714  4932 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 14:22:49.646  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 14:22:49.647  4714  4779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:22:49.647  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:22:49.649  4714  4727 D BtGatt.GattService: stopScan() - queue size =1
,11-22 14:22:49.650  4714  4924 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 14:22:49.651  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 14:22:49.651  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:49.651  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 14:22:49.652  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.652  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.652  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.653  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:49.653  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 14:22:49.653  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.653  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.653  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.653  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 14:22:49.654  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 14:22:49.654  4714  4714 D BtGatt.ScanManager: awakened up at time 203585
11-22 14:22:49.656  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:22:49.656  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.659  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.660  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:22:49.660  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.661  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:49.661  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:22:49.661  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:22:49.661  5662  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 14:22:49.661  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:22:49.661  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-22 14:22:49.661  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 14:22:49.661  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-22 14:22:49.661  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 14:22:49.661  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:22:49.662  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:22:49.662  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-22 14:22:49.662  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:22:49.666  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:22:49.666  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:22:49.666  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 14:22:49.674  4714  4776 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-22 14:22:49.674  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:22:49.674  4714  4776 D BtGatt.GattService: current time is 203605316891
11-22 14:22:49.675  4714  4776 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -91, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -82, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -87, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -97, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-22 14:22:49.675  4714  4776 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-22 14:22:49.675  4714  4776 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-22 14:22:49.676  4714  4776 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-22 14:22:49.676  4714  4776 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-22 14:22:49.676  4714  4776 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-22 14:22:49.676  4714  4776 E BtGatt.ContextMap: Context not found for ID 5
,11-22 14:22:49.683  4714  4776 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 14:22:49.683  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:22:49.683  4714  4779 D BtGatt.ScanManager: stopping BLe Batch
,11-22 14:22:49.688  4714  4776 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 14:22:49.688  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:22:49.688  4714  4779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 14:22:49.694  4714  4776 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 14:22:49.694  4714  4776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:22:50.162  5662  5662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 14:22:50.162  5662  5662 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:50.162  5662  5662 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 14:22:51.560   931  5421 D NetlinkSocketObserver: NeighborEvent{elapsedMs=205490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:22:54.662  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:22:54.663  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 14:22:54.663  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 14:22:54.663  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 14:22:54.663  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-22 14:22:54.663  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-22 14:22:54.663  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:22:54.664  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:54.664  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:22:54.664  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.664  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:54.664  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 14:22:54.668  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.668  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.671  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.671  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.672  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:54.672  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:54.672  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:54.673  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.673  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.675  5662  5709 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-22 14:22:54.678  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:22:54.679  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:54.679  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:54.679  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:54.680  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:54.680  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:54.680  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.680  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
,11-22 14:22:54.680  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:54.680  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.680  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.682  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.682  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:54.683  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.683  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 14:22:54.683  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:54.683  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.683  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
,11-22 14:22:54.684  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-22 14:22:54.685  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:22:54.685  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 14:22:54.685  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:54.685  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:54.685  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:54.685  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:54.685  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:22:54.686  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.686  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:54.686  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.686  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:54.688  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.688  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.688  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:54.688  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:54.688  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:54.688  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.688  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.689  5662  5709 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-22 14:22:54.690  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:22:54.690  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 14:22:54.690  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:54.690  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:54.690  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:54.690  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
,11-22 14:22:54.690  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.690  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.690  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:54.690  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.691  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:54.692  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.692  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.692  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.693  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:54.693  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 14:22:54.693  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.693  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
,11-22 14:22:54.694  5662  5709 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-22 14:22:54.694  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:22:54.694  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:54.694  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:54.694  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:54.694  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:22:54.694  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:54.694  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.694  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.694  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:54.694  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.695  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.696  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:54.696  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.696  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:54.696  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:54.696  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:54.696  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.696  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.697  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 14:22:54.697  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-22 14:22:54.698  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 14:22:54.698  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 14:22:54.698  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 14:22:54.698  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 14:22:54.698  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-22 14:22:54.698  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 14:22:54.698  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 14:22:54.698  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:22:54.698  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:54.698  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:54.698  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:54.699  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:22:54.699  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:54.699  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.699  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.699  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:54.699  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.700  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:54.702  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:54.702  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.702  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.703  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 14:22:54.703  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:54.703  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.703  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.703  5662  5709 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 14:22:54.703  5662  5709 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 14:22:54.704  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-22 14:22:54.706  5662  5709 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-22 14:22:54.707  5662  5709 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 14:22:54.707  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-22 14:22:54.708  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 14:22:54.708  5662  5709 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-22 14:22:54.709  5662  5709 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 14:22:54.709  5662  5709 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-22 14:22:54.709  5662  5709 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 14:22:54.709  5662  5709 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 14:22:54.709  5662  5709 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-22 14:22:54.709  5662  5709 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 14:22:54.709  5662  5709 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 14:22:54.709  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-22 14:22:54.713  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-22 14:22:54.713  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-22 14:22:54.714  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-22 14:22:54.714  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-22 14:22:54.714  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-22 14:22:54.714  5662  5709 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-22 14:22:54.714  5662  5709 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 14:22:54.715  5662  5709 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-22 14:22:54.715  5662  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-22 14:22:54.715  5662  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-22 14:22:54.715  5662  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-22 14:22:54.715  5662  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-22 14:22:54.716  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:22:54.716  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:54.716  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:54.716  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:54.716  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:54.716  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-22 14:22:54.716  4729  4729 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33197]" dev="sockfs" ino=33197 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 14:22:54.716  4729  4729 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33197]" dev="sockfs" ino=33197 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 14:22:54.718  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:54.718  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.718  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.718  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:54.718  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.718  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.718  5662  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-22 14:22:54.718  5662  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-22 14:22:54.719  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.719  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.720  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.720  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:54.720  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:54.720  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.720  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.719  5662  5722 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-22 14:22:54.720  5662  5722 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 14:22:54.721  5662  5709 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-22 14:22:54.721  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:22:54.721  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:54.721  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:54.721  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:54.721  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:54.722  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:54.722  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.722  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.722  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:54.722  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.722  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.724  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.724  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.724  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.724  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:54.725  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:54.725  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.725  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.725  5662  5709 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-22 14:22:54.726  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:22:54.726  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:54.726  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:54.726  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:54.726  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:54.726  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:54.726  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.726  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.726  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:54.726  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.726  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.728  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.728  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.728  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.728  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:54.728  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:54.728  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.728  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.729  5662  5709 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-22 14:22:54.729  5662  5709 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-22 14:22:54.729  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 14:22:54.729  5662  5709 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-22 14:22:54.729  5662  5709 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 14:22:54.729  5662  5709 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-22 14:22:54.729  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 14:22:54.729  5662  5709 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-22 14:22:54.729  5662  5709 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 14:22:54.729  5662  5709 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 14:22:54.729  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 14:22:54.729  5662  5709 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-22 14:22:54.730  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:22:54.730  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:54.730  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:54.730  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:54.730  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:54.730  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:54.730  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.730  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.730  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:54.730  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.730  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.731  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.731  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.731  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:54.731  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:54.732  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:54.732  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.732  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.732  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:54.732  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:54.732  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:54.732  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:54.733  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:54.733  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:22:59.733  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:22:59.734  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:59.734  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:59.734  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:59.734  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:59.734  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:22:59.735  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:59.735  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:59.735  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:59.735  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:59.735  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:59.736  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:59.736  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:59.736  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:22:59.736  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.737  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:59.740  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.741  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:59.741  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.741  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:59.741  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:59.741  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:22:59.741  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
,11-22 14:22:59.747  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-22 14:22:59.748  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:22:59.748  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 14:22:59.754  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-22 14:22:59.755  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-22 14:22:59.755  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-22 14:22:59.756  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-22 14:22:59.756  5662  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-22 14:22:59.756  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-22 14:22:59.756  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 14:22:59.756  5662  5662 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-22 14:22:59.757  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:59.757  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-22 14:22:59.757  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-22 14:22:59.757  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-22 14:22:59.757  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 14:22:59.758  5662  5724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 14:22:59.758  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-22 14:22:59.758  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-22 14:22:59.758  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:59.759  5662  5662 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-22 14:22:59.759  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:59.759  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:22:59.759  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:59.759  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:22:59.759  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 14:22:59.759  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:59.759  4924  4924 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29614]" dev="sockfs" ino=29614 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 14:22:59.759  4924  4924 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[29614]" dev="sockfs" ino=29614 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-22 14:22:59.761  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:59.761  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:22:59.761  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.762  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.762  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:59.762  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:22:59.762  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:22:59.762  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:59.762  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:59.762  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:22:59.762  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:59.762  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:22:59.762  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-22 14:22:59.763  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:59.763  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:59.763  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:59.763  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:59.763  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.763  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.764  5662  5724 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-22 14:22:59.764  5662  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-22 14:22:59.764  5662  5724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-22 14:22:59.765  5662  5662 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-22 14:22:59.765  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.765  5662  5662 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:59.765  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.765  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.765  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:59.765  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:59.765  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:22:59.766  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:59.767  5662  5709 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-22 14:22:59.768  5662  5709 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 14:22:59.768  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 14:22:59.768  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 14:22:59.768  5662  5709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 14:22:59.768  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:22:59.769  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:59.769  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:59.769  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:59.769  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:59.770  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
,11-22 14:22:59.770  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:59.771  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:59.771  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:59.773  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.774  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:59.777  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:59.777  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.778  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:59.778  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:59.778  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:59.778  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:59.778  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
,11-22 14:22:59.784  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:22:59.784  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:59.784  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:59.784  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:59.784  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:59.784  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:59.785  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:59.785  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:59.785  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:22:59.785  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.785  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:59.786  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:59.786  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.787  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.787  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:59.787  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:59.787  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:22:59.787  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:59.788  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:22:59.788  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:22:59.788  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:22:59.788  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:22:59.788  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:22:59.788  5662  5709 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e1371 not in the list
11-22 14:22:59.788  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:22:59.788  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
11-22 14:22:59.789  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:22:59.789  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.789  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.791  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.791  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:22:59.791  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:22:59.791  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:22:59.791  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:22:59.791  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:22:59.791  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250e556 not in the list
,11-22 14:22:59.793  5662  5709 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-22 14:22:59.793  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 14:22:59.793  5662  5709 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-22 14:22:59.794  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 14:22:59.794  5662  5709 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-22 14:22:59.794  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-22 14:22:59.796  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-22 14:22:59.796  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-22 14:22:59.797  5662  5709 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-22 14:22:59.797  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-22 14:22:59.797  5662  5709 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-22 14:22:59.797  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-22 14:22:59.797  5662  5709 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-22 14:22:59.797  5662  5709 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-22 14:22:59.798  5662  5709 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-22 14:22:59.798  5662  5709 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-22 14:22:59.798  5662  5709 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-22 14:22:59.798  5662  5709 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-22 14:22:59.799  5662  5709 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-22 14:22:59.799  5662  5709 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-22 14:22:59.800  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 14:22:59.800  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d716c7 added. We now have 3 listener(s)
11-22 14:22:59.800  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:22:59.801  5662  5709 D BluetoothAdapter: enable(): BT is already enabled..!
11-22 14:22:59.802   931  3200 D WifiService: setWifiEnabled: true pid=5662, uid=10077
11-22 14:22:59.802   931  3200 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 14:22:59.849  4714  4914 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-22 14:22:59.849  4714  4922 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-22 14:22:59.849  5662  5722 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
,11-22 14:22:59.850  5662  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-22 14:22:59.850  5662  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-22 14:23:00.263  5662  5662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 14:23:01.213   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:23:04.236   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 14:23:04.807  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 14:23:04.808  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36f84f4 added. We now have 4 listener(s)
11-22 14:23:04.808  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:23:04.820  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:23:04.820  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36f84f4 removed from the list
,11-22 14:23:04.820  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:23:04.822  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:23:04.823  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b6241d added. We now have 4 listener(s)
11-22 14:23:04.823  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:23:04.825  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:04.826  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b6241d removed from the list
11-22 14:23:04.826  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:23:04.827  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:23:04.828  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cfc6692 added. We now have 4 listener(s)
11-22 14:23:04.828  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:23:04.833   931  3200 D WifiService: setWifiEnabled: false pid=5662, uid=10077
,11-22 14:23:04.833   931  3200 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 14:23:04.838   931  3036 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-22 14:23:04.838   931  3036 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-22 14:23:04.839   931  3036 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 14:23:04.840   931  3036 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 14:23:04.846  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:23:04.846  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 14:23:04.851  4714  4772 D BluetoothAdapterState: Current state: ON, message: 23
,11-22 14:23:04.851  4714  4772 D BluetoothAdapterProperties: Setting state to 13
11-22 14:23:04.851  4714  4772 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-22 14:23:04.853  4714  4772 D BluetoothAdapterProperties: onBluetoothDisable()
11-22 14:23:04.854  4714  4772 I BluetoothAdapterState: Entering PendingCommandState
,11-22 14:23:04.856  4714  4776 D BluetoothAdapterProperties: Scan Mode:20
11-22 14:23:04.857  4714  4772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-22 14:23:04.862   931  5422 D DhcpClient: Clearing IP address
,11-22 14:23:04.862  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 14:23:04.863  5662  5709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 14:23:04.863  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:23:04.863  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:23:04.863  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:23:04.863  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:23:04.863  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 14:23:04.863  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 14:23:04.863  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 14:23:04.863  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 14:23:04.863   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-22 14:23:04.863  4714  4714 D BluetoothMapService: onReceive
11-22 14:23:04.864  4714  4714 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 14:23:04.864  4714  4714 D BluetoothMapService: STATE_TURNING_OFF
11-22 14:23:04.864  4714  4714 D BluetoothMapService: MAP Service closeService in
11-22 14:23:04.864  4714  4714 D BluetoothMapMasInstance0: MAP Service shutdown
11-22 14:23:04.864  4714  4714 D ObexServerSockets0: shutdown(block = true)
11-22 14:23:04.865  4714  4714 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 14:23:04.865  4714  4934 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-22 14:23:04.865  4714  4714 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 14:23:04.866  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:23:04.866  5662  5709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 14:23:04.866  4714  4935 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-22 14:23:04.866  4714  4922 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-22 14:23:04.866  5662  5709 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 14:23:04.870  4714  4714 I BtOppRfcommListener: stopping Accept Thread
11-22 14:23:04.870  4714  5348 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-22 14:23:04.870  4714  5348 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-22 14:23:04.871  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:04.872   508   924 D CommandListener: Setting iface cfg
11-22 14:23:04.874   931  5423 D DhcpClient: Receive thread stopped
11-22 14:23:04.875  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:04.878  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:23:04.882  3637  5473 V NativeCrypto: Read error: ssl=0x7f84a09380: I/O error during system call, Connection timed out
,11-22 14:23:04.883  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:04.884  3637  5473 V NativeCrypto: SSL shutdown failed: ssl=0x7f84a09380: I/O error during system call, Broken pipe
,11-22 14:23:04.887   931  3200 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-22 14:23:04.888   931   944 I ActivityManager: Start proc 5728:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-22 14:23:04.889   931  5420 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-22 14:23:04.890   931  3038 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-22 14:23:04.891   931  3038 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-22 14:23:04.891   931  5420 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-22 14:23:04.896   541   541 E Parcel  : Reading a NULL string not supported here.
,11-22 14:23:04.897  4714  4714 D HeadsetService: Received stop request...Stopping profile...
,11-22 14:23:04.899   931   931 D RttService: SCAN_AVAILABLE : 1
11-22 14:23:04.900   931  3145 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-22 14:23:04.901   931   931 D BluetoothHeadset: Proxy object disconnected
11-22 14:23:04.901  3205  3217 D BluetoothHeadset: Proxy object disconnected
11-22 14:23:04.902  4714  4714 D A2dpService: Received stop request...Stopping profile...
11-22 14:23:04.902  3842  4048 D BluetoothHeadset: Proxy object disconnected
11-22 14:23:04.902  4714  4927 D A2dpStateMachine: Exit Disconnected: -1
11-22 14:23:04.902   931   931 D BluetoothHeadset: Proxy object disconnected
11-22 14:23:04.903   931   931 D BluetoothHeadset: Proxy object disconnected
11-22 14:23:04.903   931   931 D BluetoothA2dp: Proxy object disconnected
11-22 14:23:04.904  4714  4714 D HidService: Received stop request...Stopping profile...
11-22 14:23:04.904  4714  4714 D HidService: Stopping Bluetooth HidService
,11-22 14:23:04.907   931  3038 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-22 14:23:04.909  4714  4714 D HealthService: Received stop request...Stopping profile...
,11-22 14:23:04.911  4714  4714 V BluetoothAdapterState: isTurningOff()=true
11-22 14:23:04.911  4714  4714 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:04.911  4714  4714 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:23:04.911  4714  4714 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:04.912  4714  4714 D PanService: Received stop request...Stopping profile...
11-22 14:23:04.912  3802  3934 W QCNEJ   : |CORE| network lost: 100
11-22 14:23:04.914  4714  4714 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-22 14:23:04.914  4714  4714 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-22 14:23:04.914  4714  4776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-22 14:23:04.915  4714  4914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:23:04.915  4714  4914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:23:04.915  4714  4914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:23:04.915  3802  3934 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-22 14:23:04.916  4714  4776 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-22 14:23:04.916  4714  4714 D BluetoothMapService: Received stop request...Stopping profile...
11-22 14:23:04.916  4714  4714 D BluetoothMapService: stop()
11-22 14:23:04.917  4714  4714 D BluetoothMapAppObserver: deinitObservers()
11-22 14:23:04.917  4714  4714 D BluetoothMapAppObserver: removeReceiver()
11-22 14:23:04.917   931  3036 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-22 14:23:04.918  4714  4714 V BluetoothAdapterState: isTurningOff()=true
11-22 14:23:04.918  4714  4714 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:04.918  4714  4714 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:04.918  4714  4714 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:04.919  4714  4776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-22 14:23:04.919  4714  4914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:23:04.920  4714  4914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:23:04.920  4714  4914 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 14:23:04.920  4714  4914 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 14:23:04.920  4714  4914 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 14:23:04.920  4714  4914 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 14:23:04.920  4714  4714 D SapService: Received stop request...Stopping profile...
11-22 14:23:04.920  4714  4714 V SapService: stop()
11-22 14:23:04.922  4714  4714 V BluetoothAdapterState: isTurningOff()=true
11-22 14:23:04.922  4714  4714 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:04.922  4714  4714 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:04.922  4714  4714 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:04.923  4714  4714 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-22 14:23:04.923  4714  4776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 14:23:04.923  4714  4714 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-22 14:23:04.924  3205  3205 D HeadsetProfile: Bluetooth service disconnected
11-22 14:23:04.925  3205  3205 D BluetoothA2dp: Proxy object disconnected
11-22 14:23:04.925  3205  3205 D BluetoothInputDevice: Proxy object disconnected
11-22 14:23:04.925  3205  3205 D HidProfile: Bluetooth service disconnected
,11-22 14:23:04.926   931  3036 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 14:23:04.927  3205  3205 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-22 14:23:04.927  4714  4714 V BluetoothAdapterState: isTurningOff()=true
,11-22 14:23:04.927  3205  3205 D PanProfile: Bluetooth service disconnected
11-22 14:23:04.927  4714  4714 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:04.927  4714  4714 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:04.927  4714  4714 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:04.927  3205  3205 D BluetoothMap: Proxy object disconnected
11-22 14:23:04.927  3205  3205 D MapProfile: Bluetooth service disconnected
11-22 14:23:04.927  4714  4714 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-22 14:23:04.928  4714  4776 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-22 14:23:04.928  4714  4714 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-22 14:23:04.928  4714  4714 V BluetoothAdapterState: isTurningOff()=true
11-22 14:23:04.928  4714  4714 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:04.928  4714  4714 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:04.928  4714  4714 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:04.928  4714  4714 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-22 14:23:04.929  4714  4714 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-22 14:23:04.929  4714  4714 D BluetoothMapService: MAP Service closeService in
11-22 14:23:04.929  4714  4714 V BluetoothAdapterState: isTurningOff()=true
11-22 14:23:04.930  4714  4714 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:04.930  4714  4714 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:23:04.930  4714  4714 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:04.930  4714  4714 D BluetoothMapService: cleanup()
11-22 14:23:04.930  4714  4714 D BluetoothMapService: MAP Service closeService in
11-22 14:23:04.930  4714  4714 V BluetoothAdapterState: isTurningOff()=true
,11-22 14:23:04.930  4714  4714 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:04.930  4714  4714 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:04.930  4714  4714 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:04.930  4714  4772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-22 14:23:04.930  4714  4772 D BluetoothAdapterProperties: Setting state to 15
11-22 14:23:04.931  4714  4772 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-22 14:23:04.931  4714  4772 I BluetoothAdapterState: Entering BleOnState
11-22 14:23:04.931   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:23:04.931  3205  3218 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 14:23:04.932   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 14:23:04.932  3205  3217 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:23:04.933  3205  4039 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 14:23:04.934  3205  3218 D BluetoothMap: onBluetoothStateChange: up=false
11-22 14:23:04.934  3205  3217 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 14:23:04.935  3205  4039 D BluetoothPan: onBluetoothStateChange on: false
11-22 14:23:04.936   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:23:04.936   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:23:04.936  3842  3862 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:23:04.939   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-22 14:23:04.937  4714  4772 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-22 14:23:04.940  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:23:04.940  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:23:04.940  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:23:04.940  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:23:04.940  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:23:04.940  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:23:04.940  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:23:04.940  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:23:04.940  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:23:04.940  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 14:23:04.940  4714  4772 D BluetoothAdapterProperties: Setting state to 16
11-22 14:23:04.941  4714  4772 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-22 14:23:04.941  4714  4772 D BluetoothAdapterProperties: onBleDisable
11-22 14:23:04.942  4714  4772 I BluetoothAdapterState: Entering PendingCommandState
11-22 14:23:04.942  4714  4773 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-22 14:23:04.942  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:23:04.942  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 14:23:04.942  4714  4914 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-22 14:23:04.943  4714  4914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:,23:04.945  4714  4776 D BluetoothAdapterProperties: Scan Mode:20
11-22 14:23:04.946  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:04.949  5728  5728 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-22 14:23:04.965   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-22 14:23:04.965   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-22 14:23:04.965   508   924 D TetherController: Setting IP forward enable = 0
,11-22 14:23:04.966   931  3038 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-22 14:23:04.967   931  3038 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-22 14:23:04.968   931   948 D Tethering: MasterInitialState.processMessage what=3
,11-22 14:23:04.970   931  3036 D DhcpClient: doQuit
11-22 14:23:04.970   931  3036 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-22 14:23:04.970  5301  5301 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@83426b4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-22 14:23:04.971   931  5422 D DhcpClient: onQuitting
11-22 14:23:04.971  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:04.971  3503  3503 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-22 14:23:04.973  4006  4006 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-22 14:23:04.975  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:23:04.976  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:23:04.976  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:23:04.976  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:23:04.976  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 14:23:04.976  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:23:04.976  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:23:04.976  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:23:04.976  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:23:04.976  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 14:23:04.976  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:23:04.976  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 14:23:04.977  5090  5112 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 14:23:04.977  5090  5112 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 14:23:04.977  5090  5112 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-22 14:23:04.977  5090  5112 E SarControlService: no key has been found,reset the power
,11-22 14:23:04.977  5090  5127 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 14:23:04.977  5090  5127 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 14:23:04.978  5090  5127 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 14:23:04.978  5115  5115 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-22 14:23:04.978  5115  5115 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-22 14:23:04.979  5090  5127 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 14:23:04.979  5090  5127 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 14:23:04.979  5090  5127 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 14:23:04.981  5115  5115 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 14:23:04.981  5115  5115 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 14:23:04.984  5728  5728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 14:23:04.990  5115  5129 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e9f33a HexData = [00000000ea03000000000000ffffffff]
,11-22 14:23:04.990  5115  5129 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 14:23:04.990  5115  5129 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-22 14:23:04.990  5115  5115 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 14:23:04.990  5090  5100 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 14:23:04.991  5115  5129 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e9f33a HexData = [00000000eb03000000000000ffffffff]
11-22 14:23:04.991  5115  5129 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 14:23:04.991  5115  5129 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-22 14:23:04.991  5115  5115 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 14:23:04.992  5090  5101 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-22 14:23:04.994  3503  3503 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-22 14:23:04.996   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@75f7319:true
,11-22 14:23:04.996  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 14:23:04.998  3503  3503 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-22 14:23:05.000   508   917 W SocketClient: write error (Broken pipe)
11-22 14:23:05.000   508   917 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-22 14:23:05.000   508   917 W SocketListener: Error sending broadcast (Broken pipe)
,11-22 14:23:05.022  5728  5728 D LocalBluetoothProfileManager: Adding local MAP profile
,11-22 14:23:05.024  5728  5728 D BluetoothMap: Create BluetoothMap proxy object
,11-22 14:23:05.030   508   924 E Netd    : netlink response contains error (No such file or directory)
,11-22 14:23:05.030  3503  3503 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-22 14:23:05.031   508   924 D TetherController: Setting IP forward enable = 0
11-22 14:23:05.032   931  3038 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-22 14:23:05.032   931  3038 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-22 14:23:05.033  5728  5728 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-22 14:23:05.039  3503  3503 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-22 14:23:05.040  5728  5728 D DockEventReceiver: finishStartingService: stopping service
,11-22 14:23:05.045  5728  5728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 14:23:05.050  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 14:23:05.050  5728  5728 D DockEventReceiver: finishStartingService: stopping service
11-22 14:23:05.052   931  3200 I ActivityManager: Killing 5448:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-22 14:23:05.075  4022  4022 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-22 14:23:05.078  4022  4022 D SystemUpdateService: onCreate
,11-22 14:23:05.081  4022  4022 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 14:23:05.088  4022  5764 I SystemUpdateService: active receiver: enabled
,11-22 14:23:05.090  4022  4022 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-22 14:23:05.094  4022  5446 I iu.UploadsManager: num queued entries: 0
,11-22 14:23:05.095  4022  5446 I iu.UploadsManager: num updated entries: 0
,11-22 14:23:05.100  4022  4022 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 14:23:05.102  4022  4022 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 14:23:05.104  4022  5446 I iu.SyncManager: NEXT; no task
,11-22 14:23:05.105  4022  5764 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 14:23:05.108  4022  5764 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-22 14:23:05.108  4022  5764 I SystemUpdateService: now status is 0 (complete)
11-22 14:23:05.108  4022  5764 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 14:23:05.108  4022  5764 I SystemUpdateService: file has been verified
11-22 14:23:05.108  4022  5764 I SystemUpdateService: OTA package size = 21989297
,11-22 14:23:05.114   931  3200 I ActivityManager: Start proc 5767:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-22 14:23:05.116  4022  5764 I SystemUpdateService: showing system update notification
,11-22 14:23:05.127   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 14:23:05.128  4022  4022 D SystemUpdateService: onDestroy
,11-22 14:23:05.142   931  3036 D wifi    : In wifi stop Hal
,11-22 14:23:05.142   931  3036 D wifi    : halHandle = 0x7f72291680, mVM = 0x7f8e88d140, mCls = 0x100a02
11-22 14:23:05.142  5065  5065 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 14:23:05.143   931  3501 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-22 14:23:05.143   931  3501 D WifiHAL : Got a signal to exit!!!
11-22 14:23:05.143   931  3501 I WifiHAL : Exit wifi_event_loop
11-22 14:23:05.143   931  3036 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-22 14:23:05.143   931  3036 E WifiHAL : Event processing terminated
11-22 14:23:05.143   931  3036 D wifi    : In wifi cleaned up handler
11-22 14:23:05.144   931  3036 I WifiHAL : Internal cleanup completed
11-22 14:23:05.145  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:05.145  4156  4281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 14:23:05.150  4714  4776 I bt_hci  : shut_down
11-22 14:23:05.152  4714  4780 D bt_hwcfg: hw_epilog_process
11-22 14:23:05.152  4714  4780 I bt_vendor: low_power_mode_cb
11-22 14:23:05.155  4714  4780 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-22 14:23:05.155  4714  4780 I bt_vendor: epilog_cb
11-22 14:23:05.155  4714  4780 I bt_hci  : epilog_finished_callback
11-22 14:23:05.161  4714  4776 I bt_hci_h4: hal_close
11-22 14:23:05.162  4714  4776 I bt_userial_vendor: device fd = 54 close
11-22 14:23:05.164  5767  5767 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
11-22 14:23:05.167  5767  5767 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-22 14:23:05.173  5767  5767 D SprintDMHelper: simOperator: 
11-22 14:23:05.173  5767  5767 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-22 14:23:05.175   931  3501 D wifi    : set interface wlan0 flags (DOWN)
11-22 14:23:05.175   931  3036 D WifiNative-HAL: HAL event thread stopped successfully
11-22 14:23:05.184  5065  5779 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-22 14:23:05.198   931  4995 I ActivityManager: Start proc 5780:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-22 14:23:05.199   931  4995 I ActivityManager: Killing 5301:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-22 14:23:05.245  5780  5780 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-22 14:23:05.253   931  3200 I ActivityManager: Killing 3940:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-22 14:23:05.274  4714  4773 D bt_stack_manager: event_shut_down_stack finished.
,11-22 14:23:05.275  4714  4772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-22 14:23:05.276  4714  4772 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-22 14:23:05.276  4714  4714 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 14:23:05.277  4714  4714 D BtGatt.GattService: Received stop request...Stopping profile...
,11-22 14:23:05.277  4714  4714 D BtGatt.GattService: stop()
11-22 14:23:05.277  4714  4714 D BtGatt.AdvertiseManager: advertise clients cleared
11-22 14:23:05.279  4714  4714 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:05.279  4714  4714 V BluetoothAdapterState: isTurningOn()=false
,11-22 14:23:05.279  4714  4714 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:23:05.279  4714  4714 V BluetoothAdapterState: isBleTurningOff()=true
11-22 14:23:05.279  4714  4772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-22 14:23:05.279  4714  4772 D BluetoothAdapterProperties: Setting state to 10
11-22 14:23:05.279  4714  4772 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-22 14:23:05.280  4714  4772 I BluetoothAdapterState: Entering OffState
11-22 14:23:05.280   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-22 14:23:05.287  4714  4714 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-22 14:23:05.287  4714  4714 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-22 14:23:05.288  4714  4714 I BluetoothServiceJni: cleanupNative: return from cleanup
11-22 14:23:05.289  4714  4773 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-22 14:23:05.292  4714  4714 I art     : System.exit called, status: 0
,11-22 14:23:05.292  4714  4714 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 14:23:05.318   931  3200 I ActivityManager: Process com.android.bluetooth (pid 4714) has died
,11-22 14:23:05.378   931   948 D Tethering: InitialState.processMessage what=4
,11-22 14:23:05.383   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-22 14:23:05.883   543   543 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 14:23:05.883   543   543 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 14:23:09.870   931  3893 D WifiService: setWifiEnabled: true pid=5662, uid=10077
,11-22 14:23:09.870   931  3893 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 14:23:09.877   508   924 D SoftapController: Softap fwReload - Ok
,11-22 14:23:09.883   508   924 D CommandListener: Setting iface cfg
,11-22 14:23:09.883   508   924 D CommandListener: Trying to bring down wlan0
,11-22 14:23:09.884   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-22 14:23:09.890   931  3036 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 14:23:10.491   931  3036 D wifi    : set interface wlan0 flags (UP)
,11-22 14:23:10.495   931  3036 I WifiHAL : Initializing wifi
,11-22 14:23:10.495   931  3036 I WifiHAL : Creating socket
,11-22 14:23:10.497   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-22 14:23:10.507   931  3036 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-22 14:23:10.507   931  3036 D wifi    : Did set static halHandle = 0x7f72291680
,11-22 14:23:10.507   931  3036 D wifi    : halHandle = 0x7f72291680, mVM = 0x7f8e88d140, mCls = 0x10194a
11-22 14:23:10.507   931  3036 D wifi    : array field set
11-22 14:23:10.507   931  3036 I WifiNative-HAL: interface[0] = wlan0
11-22 14:23:10.509   931  5796 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547376141952
11-22 14:23:10.509   931  5796 D wifi    : waitForHalEvents called, vm = 0x7f8e88d140, obj = 0x10194a, env = 0x7f7729e340
,11-22 14:23:10.595  5797  5797 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 14:23:10.610   931  3036 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-22 14:23:10.611   931  3036 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
11-22 14:23:10.615  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:23:10.670  5797  5797 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 14:23:10.698  5797  5797 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 14:23:10.698  5797  5797 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 14:23:11.626   931  3036 D WifiConfigStore: Loading config and enabling all networks 
,11-22 14:23:11.627  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:23:11.627  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:23:11.627  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:23:11.627  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:23:11.627  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:23:11.627  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:23:11.627  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:23:11.627  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:23:11.627  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:23:11.627  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 14:23:11.628  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:23:11.628  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 14:23:11.660   931  3036 D WifiConfigStore: loaded 0 passpoint configs
11-22 14:23:11.661   931  3036 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-22 14:23:11.662   931  3036 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-22 14:23:11.663   931  3036 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-22 14:23:11.663   931  3036 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-22 14:23:11.664   931  3036 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-22 14:23:11.665   931  3036 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-22 14:23:11.665   931  3036 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-22 14:23:11.666   931  3036 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-22 14:23:11.666   931  3036 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-22 14:23:11.666   931  3036 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-22 14:23:11.666   931  3036 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-22 14:23:11.666   931  3036 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-22 14:23:11.669   931  3036 D WifiNative-HAL: Setting external_sim to 1
,11-22 14:23:11.670  5065  5065 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 14:23:11.670   931  3036 D wifi    : setting dfs flag to true, 0x7f6fce0f20
,11-22 14:23:11.671   931  3036 D WifiStateMachine: Setting OUI to DA-A1-19
,11-22 14:23:11.671   931  3036 D wifi    : setting scan oui 0x7f6fce0f20
11-22 14:23:11.671   931  3036 D WifiHAL : Sending mac address OUI
,11-22 14:23:11.675   931  3036 E native  : do suspend false
,11-22 14:23:11.687   931  3036 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-22 14:23:11.687   931   931 D RttService: SCAN_AVAILABLE : 3
11-22 14:23:11.687   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-22 14:23:11.688   931  3145 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-22 14:23:11.689   508   924 D CommandListener: Setting iface cfg
,11-22 14:23:11.693   931  3025 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
11-22 14:23:11.693   931  3025 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 14:23:11.704   931  3025 D WifiNative-HAL: p2pGetDeviceAddress
,11-22 14:23:11.710   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=225641 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
11-22 14:23:11.711   931  3025 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-22 14:23:14.789  5797  5797 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 14:23:14.806  5797  5797 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 14:23:14.817  5797  5797 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 14:23:14.826  5797  5797 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 14:23:14.854   931  3036 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-22 14:23:14.856   931  3036 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-22 14:23:14.856   931  3036 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 14:23:14.871   931  3036 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-22 14:23:14.875   931  3476 D WifiService: setWifiEnabled: false pid=5662, uid=10077
,11-22 14:23:14.875   931  3476 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 14:23:14.910   931  3036 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-22 14:23:14.916  5797  5797 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-22 14:23:14.933   931   931 D RttService: SCAN_AVAILABLE : 1
,11-22 14:23:14.934   931  3145 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-22 14:23:14.946   931  3036 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 14:23:14.948   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-22 14:23:14.954   931  3036 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 14:23:14.956  5797  5797 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-22 14:23:14.964  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 14:23:14.964  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:23:14.964  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:23:14.964  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:23:14.964  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 14:23:14.964  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:23:14.964  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:23:14.964  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:23:14.964  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:23:14.964  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 14:23:14.965  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:23:14.965  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 14:23:14.970  5797  5797 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-22 14:23:14.975  5797  5797 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,11-22 14:23:14.986  5797  5797 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-22 14:23:14.990  5797  5797 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-22 14:23:15.094   931  3036 D wifi    : In wifi stop Hal
11-22 14:23:15.095   931  3036 D wifi    : halHandle = 0x7f72291680, mVM = 0x7f8e88d140, mCls = 0x10194a
,11-22 14:23:15.095   931  5796 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-22 14:23:15.095   931  5796 D WifiHAL : Got a signal to exit!!!
11-22 14:23:15.095   931  5796 I WifiHAL : Exit wifi_event_loop
11-22 14:23:15.096   931  3036 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-22 14:23:15.096   931  3036 E WifiHAL : Event processing terminated
11-22 14:23:15.097   931  3036 D wifi    : In wifi cleaned up handler
,11-22 14:23:15.097   931  3036 I WifiHAL : Internal cleanup completed
,11-22 14:23:15.104  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:23:15.104  5065  5065 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 14:23:15.105  4156  4281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 14:23:15.130   931  5796 D wifi    : set interface wlan0 flags (DOWN)
,11-22 14:23:15.130   931  3036 D WifiNative-HAL: HAL event thread stopped successfully
,11-22 14:23:15.337   931   948 D Tethering: InitialState.processMessage what=4
,11-22 14:23:15.343   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-22 14:23:15.884   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:16.886   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:17.887   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:18.888   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:19.889   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:19.916   931   948 I ActivityManager: Start proc 5803:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 14:23:20.026  5803  5803 D AdapterServiceConfig: Adding HeadsetService
,11-22 14:23:20.027  5803  5803 D AdapterServiceConfig: Adding A2dpService
11-22 14:23:20.027  5803  5803 D AdapterServiceConfig: Adding HidService
11-22 14:23:20.027  5803  5803 D AdapterServiceConfig: Adding HealthService
,11-22 14:23:20.027  5803  5803 D AdapterServiceConfig: Adding PanService
11-22 14:23:20.027  5803  5803 D AdapterServiceConfig: Adding GattService
,11-22 14:23:20.027  5803  5803 D AdapterServiceConfig: Adding BluetoothMapService
11-22 14:23:20.028  5803  5803 D AdapterServiceConfig: Adding SapService
,11-22 14:23:20.041   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e5c98ec:true
,11-22 14:23:20.043  5803  5803 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 14:23:20.046  5803  5803 I bt_bluedroid: init
11-22 14:23:20.046  5803  5815 I BluetoothAdapterState: Entering OffState
,11-22 14:23:20.049  5803  5816 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-22 14:23:20.049  5803  5816 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 14:23:20.049  5803  5816 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-22 14:23:20.049  5803  5816 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-22 14:23:20.050  5803  5803 I bt_bluedroid: get_profile_interface socket
,11-22 14:23:20.052  5803  5819 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 14:23:20.053  5803  5803 I bt_bluedroid: get_profile_interface sdp
11-22 14:23:20.054  5803  5819 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 14:23:20.059  5803  5814 I bt_bluedroid: config_hci_snoop_log
11-22 14:23:20.060   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 14:23:20.065  5803  5815 D BluetoothAdapterState: Current state: OFF, message: 0
,11-22 14:23:20.066  5803  5815 D BluetoothAdapterProperties: Setting state to 14
11-22 14:23:20.066  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-22 14:23:20.067  5803  5815 D BluetoothBondStateMachine: make
,11-22 14:23:20.069  5803  5820 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 14:23:20.071  5803  5815 I BluetoothAdapterState: Entering PendingCommandState
,11-22 14:23:20.073  5803  5803 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-22 14:23:20.075  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
11-22 14:23:20.075  5803  5803 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 14:23:20.076  5803  5803 D BtGatt.GattService: Received start request. Starting profile...
,11-22 14:23:20.076  5803  5803 D BtGatt.GattService: start()
11-22 14:23:20.076  5803  5803 I bt_bluedroid: get_profile_interface gatt
11-22 14:23:20.077  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
11-22 14:23:20.077  5803  5803 D BtGatt.AdvertiseManager: advertise manager created
,11-22 14:23:20.082  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:20.082  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:20.082  5803  5803 V BluetoothAdapterState: isBleTurningOn()=true
11-22 14:23:20.082  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:23:20.083  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-22 14:23:20.084  5803  5815 I bt_bluedroid: bt_bluedroid
11-22 14:23:20.084  5803  5816 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-22 14:23:20.084  5803  5816 I bt_hci  : start_up
,11-22 14:23:20.089  5803  5816 I bt_vendor: alloc value 0xf3b7f871
11-22 14:23:20.090  5803  5816 I bt_vendor: init
11-22 14:23:20.090  5803  5816 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-22 14:23:20.090  5803  5816 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 14:23:20.196  5803  5816 D bt_hci  : start_up starting async portion
11-22 14:23:20.197  5803  5823 I bt_hci  : event_finish_startup
,11-22 14:23:20.197  5803  5823 I bt_hci_h4: hal_open
11-22 14:23:20.197  5803  5823 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-22 14:23:20.200  5803  5823 I bt_userial_vendor: device fd = 54 open
,11-22 14:23:20.196  5824  5824 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 14:23:20.214  5803  5823 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 14:23:20.217  5803  5823 D bt_hwcfg: Chipset BCM4358A3
,11-22 14:23:20.217  5803  5823 D bt_hwcfg: Target name = [BCM4358A3]
11-22 14:23:20.217  5803  5823 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 14:23:20.633  5803  5823 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-22 14:23:20.633  5803  5823 D bt_hwcfg: Settlement delay -- 100 ms
11-22 14:23:20.633  5803  5823 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 14:23:20.766  5803  5823 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-22 14:23:20.767  5803  5823 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-22 14:23:20.769  5803  5823 I bt_hwcfg: vendor lib fwcfg completed
11-22 14:23:20.769  5803  5823 I bt_vendor: firmware callback
11-22 14:23:20.769  5803  5823 I bt_hci  : firmware_config_callback
,11-22 14:23:20.778  5803  5826 I bt_btu  : btu_task pending for preload complete event
,11-22 14:23:20.778  5803  5826 I bt_btu_task: Bluetooth chip preload is complete
11-22 14:23:20.778  5803  5826 I bt_btu  : btu_task received preload complete event
,11-22 14:23:20.785  5803  5826 I         : BTE_InitTraceLevels -- TRC_HCI
,11-22 14:23:20.785  5803  5826 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-22 14:23:20.786  5803  5826 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-22 14:23:20.786  5803  5826 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-22 14:23:20.786  5803  5826 I         : BTE_InitTraceLevels -- TRC_AVRC
11-22 14:23:20.786  5803  5826 I         : BTE_InitTraceLevels -- TRC_A2D
11-22 14:23:20.786  5803  5826 I         : BTE_InitTraceLevels -- TRC_BNEP
11-22 14:23:20.786  5803  5826 I         : BTE_InitTraceLevels -- TRC_BTM
,11-22 14:23:20.786  5803  5826 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 14:23:20.786  5803  5826 I         : BTE_InitTraceLevels -- TRC_PAN
11-22 14:23:20.787  5803  5826 I         : BTE_InitTraceLevels -- TRC_SDP
11-22 14:23:20.787  5803  5826 I         : BTE_InitTraceLevels -- TRC_GATT
,11-22 14:23:20.787  5803  5826 I         : BTE_InitTraceLevels -- TRC_SMP
11-22 14:23:20.787  5803  5826 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-22 14:23:20.787  5803  5826 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 14:23:20.871  5803  5826 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3afd549
11-22 14:23:20.871  5803  5826 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3afd549 
,11-22 14:23:20.890   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 14:23:20.892  5803  5819 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 14:23:20.894  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 14:23:20.894  5803  5819 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 14:23:20.897  5803  5819 D BluetoothAdapterProperties: Name is: Nexus 6P
11-22 14:23:20.899  5803  5819 D BluetoothAdapterProperties: Scan Mode:20
,11-22 14:23:20.899  5803  5819 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 14:23:20.899  5803  5819 D bt_hci  : do_postload posting postload work item
11-22 14:23:20.900  5803  5823 I bt_hci  : event_postload
11-22 14:23:20.900  5803  5823 I bt_vendor: sco_config_cb
11-22 14:23:20.900  5803  5823 I bt_hci  : sco_config_callback postload finished.
,11-22 14:23:20.903  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:20.906  5803  5819 D bt_bte_conf: Device ID record 1 : primary
11-22 14:23:20.906  5803  5819 D bt_bte_conf:   vendorId            = 000f
11-22 14:23:20.906  5803  5819 D bt_bte_conf:   vendorIdSource      = 0001
11-22 14:23:20.907  5803  5819 D bt_bte_conf:   product             = 1200
11-22 14:23:20.907  5803  5819 D bt_bte_conf:   version             = 1436
11-22 14:23:20.907  5803  5819 D bt_bte_conf:   clientExecutableURL = 
11-22 14:23:20.907  5803  5819 D bt_bte_conf:   serviceDescription  = 
11-22 14:23:20.907  5803  5819 D bt_bte_conf:   documentationURL    = 
,11-22 14:23:20.907  5803  5819 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-22 14:23:20.907  5803  5816 D bt_stack_manager: event_start_up_stack finished
11-22 14:23:20.907  5803  5823 I bt_vendor: low_power_mode_cb
11-22 14:23:20.908  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-22 14:23:20.908  5803  5815 D BluetoothAdapterProperties: Setting state to 15
11-22 14:23:20.908  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 14:23:20.909  5803  5815 I BluetoothAdapterState: Entering BleOnState
,11-22 14:23:20.913  5803  5815 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-22 14:23:20.913  5803  5815 D BluetoothAdapterProperties: Setting state to 11
11-22 14:23:20.913  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-22 14:23:20.920  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
,11-22 14:23:20.921  5803  5803 D HeadsetService: Received start request. Starting profile...
11-22 14:23:20.922  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:20.924  5803  5803 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-22 14:23:20.924  5803  5803 D HeadsetStateMachine: make
,11-22 14:23:20.932  5803  5815 I BluetoothAdapterState: Entering PendingCommandState
,11-22 14:23:20.933  5803  5803 D HeadsetStateMachine: max_hf_connections = 1
,11-22 14:23:20.934  5803  5803 I bt_bluedroid: get_profile_interface handsfree
11-22 14:23:20.934  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-22 14:23:20.934  5803  5819 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-22 14:23:20.938  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
,11-22 14:23:20.939  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 14:23:20.939  5803  5803 D A2dpService: Received start request. Starting profile...
11-22 14:23:20.940  5803  5803 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-22 14:23:20.940  5803  5803 I bt_bluedroid: get_profile_interface avrcp
,11-22 14:23:20.946  5803  5803 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-22 14:23:20.947  5803  5803 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-22 14:23:20.947  5803  5803 D A2dpStateMachine: make
,11-22 14:23:20.948  5803  5803 I bt_bluedroid: get_profile_interface a2dp
,11-22 14:23:20.949  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-22 14:23:20.950  5803  5834 D A2dpStateMachine: Enter Disconnected: -2
,11-22 14:23:20.950  5803  5803 I BluetoothHidServiceJni: classInitNative: succeeds
,11-22 14:23:20.951  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
,11-22 14:23:20.952  5728  5728 D BluetoothInputDevice: Proxy object connected
,11-22 14:23:20.953  5728  5728 D HidProfile: Bluetooth service connected
11-22 14:23:20.953  5803  5803 D HidService: Received start request. Starting profile...
11-22 14:23:20.953  5803  5803 I bt_bluedroid: get_profile_interface hidhost
11-22 14:23:20.953  5803  5819 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ade56d
,11-22 14:23:20.954  5803  5803 D HidService: setHidService(): set to: null
11-22 14:23:20.954  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-22 14:23:20.954  5803  5803 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-22 14:23:20.955  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
,11-22 14:23:20.956  5803  5803 D HealthService: Received start request. Starting profile...
,11-22 14:23:20.959  5803  5803 I bt_bluedroid: get_profile_interface health
,11-22 14:23:20.960  5803  5803 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-22 14:23:20.961  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
,11-22 14:23:20.962  5803  5803 D PanService: Received start request. Starting profile...
,11-22 14:23:20.962  5728  5728 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 14:23:20.963  5803  5803 D BluetoothPanServiceJni: initializeNative(L110): pan
11-22 14:23:20.963  5803  5803 I bt_bluedroid: get_profile_interface pan
11-22 14:23:20.964  5803  5819 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-22 14:23:20.965  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
11-22 14:23:20.965  5728  5728 D PanProfile: Bluetooth service connected
,11-22 14:23:20.966  5803  5803 D BluetoothMapService: Received start request. Starting profile...
,11-22 14:23:20.966  5803  5803 D BluetoothMapService: start()
,11-22 14:23:20.969  5803  5803 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-22 14:23:20.970  5803  5803 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-22 14:23:20.970  5803  5803 D BluetoothMapAppObserver: createReceiver()
11-22 14:23:20.971  5803  5803 D BluetoothMapAppObserver: initObservers()
11-22 14:23:20.971  5803  5803 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-22 14:23:20.976  5728  5728 D BluetoothMap: Proxy object connected
,11-22 14:23:20.977  5728  5728 D MapProfile: Bluetooth service connected
11-22 14:23:20.977  5728  5728 D BluetoothMap: getConnectedDevices()
11-22 14:23:20.977  5728  5728 D BluetoothMap: Bluetooth is Not enabled
,11-22 14:23:20.979  5803  5803 V SapService: SapBinder()
11-22 14:23:20.979  5803  5803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
,11-22 14:23:20.979  5803  5803 D SapService: Received start request. Starting profile...
,11-22 14:23:20.980  5803  5803 V SapService: start()
,11-22 14:23:20.982  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:20.982  5803  5803 V BluetoothAdapterState: isTurningOn()=true
11-22 14:23:20.982  5803  5832 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-22 14:23:20.982  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:20.982  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isTurningOn()=true
11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isTurningOff()=false
,11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isTurningOn()=true
11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isTurningOn()=true
,11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isTurningOn()=true
11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:20.983  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:20.984  5803  5803 V BluetoothAdapterState: isTurningOn()=true
11-22 14:23:20.984  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:23:20.984  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:20.985  5803  5803 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:20.985  5803  5803 V BluetoothAdapterState: isTurningOn()=true
11-22 14:23:20.985  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:20.985  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:20.985  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-22 14:23:20.985  5803  5815 D BluetoothAdapterProperties: ScanMode =  20
11-22 14:23:20.985  5803  5815 D BluetoothAdapterProperties: State =  11
11-22 14:23:20.986  5803  5819 D BluetoothAdapterProperties: Scan Mode:21
11-22 14:23:20.987  5803  5815 D BluetoothAdapterProperties: Setting state to 12
11-22 14:23:20.987  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 14:23:20.987  5803  5819 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-22 14:23:20.987   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:23:20.987  5803  5815 I BluetoothAdapterState: Entering OnState
,11-22 14:23:20.987  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-22 14:23:20.988  3205  4039 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 14:23:20.989   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 14:23:20.989  3205  3205 D BluetoothInputDevice: Proxy object connected
11-22 14:23:20.989  3205  3205 D HidProfile: Bluetooth service connected
11-22 14:23:20.990  3205  3217 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:23:20.991  3205  4039 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 14:23:20.991   931   931 D BluetoothA2dp: Proxy object connected
11-22 14:23:20.991  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:23:20.991  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:23:20.991  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:23:20.991  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 14:23:20.991  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:23:20.991  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:23:20.991  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:23:20.991  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:23:20.991  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 14:23:20.992  3205  3218 D BluetoothMap: onBluetoothStateChange: up=true
,11-22 14:23:20.993  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 14:23:20.995  3205  3205 D BluetoothMap: Proxy object connected
11-22 14:23:20.995  3205  4039 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 14:23:20.995  3205  3205 D MapProfile: Bluetooth service connected
11-22 14:23:20.995  3205  3205 D BluetoothMap: getConnectedDevices()
11-22 14:23:20.996  3205  3205 D BluetoothA2dp: Proxy object connected
11-22 14:23:20.996  5728  5739 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 14:23:20.997  5803  5803 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 14:23:20.997  5803  5803 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-22 14:23:20.998  5803  5803 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 14:23:21.000  5803  5803 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 14:23:21.001  5803  5803 D ObexServerSockets: Succeed to create listening sockets 
11-22 14:23:21.001  5803  5803 D ObexServerSockets0: startAccept()
11-22 14:23:21.001  5803  5803 D ObexServerSockets0: prepareForNewConnect()
11-22 14:23:21.002  5728  5741 D BluetoothPan: onBluetoothStateChange on: true
11-22 14:23:21.003  3205  3217 D BluetoothPan: onBluetoothStateChange on: true
11-22 14:23:21.004  5803  5803 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-22 14:23:21.004  5803  5803 D BluetoothSdpJni: SDP Create record success - handle: 0
11-22 14:23:21.004  5803  5840 D ObexServerSockets0: Accepting socket connection...
,11-22 14:23:21.005  3205  3205 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 14:23:21.005  3205  3205 D PanProfile: Bluetooth service connected
11-22 14:23:21.005  5728  5739 D BluetoothMap: onBluetoothStateChange: up=true
11-22 14:23:21.005   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:23:21.005   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:23:21.005  3842  3888 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:23:21.005  5803  5841 D ObexServerSockets0: Accepting socket connection...
11-22 14:23:21.006  5728  5741 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 14:23:21.007  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-22 14:23:21.008  5803  5803 D BluetoothMapService: onReceive
11-22 14:23:21.008   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
11-22 14:23:21.008  5803  5803 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 14:23:21.008  5803  5803 D BluetoothMapService: STATE_ON
11-22 14:23:21.009  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:21.009  5728  5728 D LocalBluetoothProfileManager: Adding local A2DP profile
11-22 14:23:21.011  5803  5843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 14:23:21.013  5803  5843 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-22 14:23:21.013  5803  5843 D BluetoothSdpJni: SDP Create record success - handle: 1
11-22 14:23:21.013  5728  5728 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-22 14:23:21.018  5728  5728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 14:23:21.020  5728  5728 D BluetoothA2dp: Proxy object connected
,11-22 14:23:21.025  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 14:23:21.026  5728  5728 D DockEventReceiver: finishStartingService: stopping service
,11-22 14:23:21.033  5803  5803 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-22 14:23:21.033  5803  5803 D ObexServerSockets0: prepareForNewConnect()
11-22 14:23:21.033  3205  3205 D BluetoothPbap: Proxy object connected
11-22 14:23:21.033  3205  3205 D PbapServerProfile: Bluetooth service connected
11-22 14:23:21.033  5728  5728 D BluetoothPbap: Proxy object connected
11-22 14:23:21.034  5728  5728 D PbapServerProfile: Bluetooth service connected
,11-22 14:23:21.039  5803  5847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 14:23:21.053  5803  5851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 14:23:21.054  5803  5851 I BtOppRfcommListener: Accept thread started.
,11-22 14:23:21.089   931   931 D BluetoothHeadset: Proxy object connected
,11-22 14:23:21.090  3205  4039 D BluetoothHeadset: Proxy object connected
11-22 14:23:21.090  3205  3205 D HeadsetProfile: Bluetooth service connected
,11-22 14:23:21.091  3842  3862 D BluetoothHeadset: Proxy object connected
11-22 14:23:21.091  3205  3217 D BluetoothHeadset: Proxy object connected
11-22 14:23:21.091   931   931 D BluetoothHeadset: Proxy object connected
11-22 14:23:21.092   931   931 D BluetoothHeadset: Proxy object connected
,11-22 14:23:21.093  3205  3205 D HeadsetProfile: Bluetooth service connected
,11-22 14:23:21.105   931   948 D BluetoothHeadset: Proxy object connected
,11-22 14:23:21.105   931   948 D BluetoothHeadset: Proxy object connected
11-22 14:23:21.106  3842  4048 D BluetoothHeadset: Proxy object connected
,11-22 14:23:21.115  5728  5741 D BluetoothHeadset: Proxy object connected
11-22 14:23:21.117  5728  5728 D HeadsetProfile: Bluetooth service connected
,11-22 14:23:23.060  3718  3918 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-22 14:23:23.060  3718  3918 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-22 14:23:23.097  3637  3637 I ConfigService: onCreate
,11-22 14:23:24.894  5803  5815 D BluetoothAdapterState: Current state: ON, message: 23
,11-22 14:23:24.894  5803  5815 D BluetoothAdapterProperties: Setting state to 13
,11-22 14:23:24.895  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-22 14:23:24.896  5803  5815 D BluetoothAdapterProperties: onBluetoothDisable()
,11-22 14:23:24.901  5803  5815 I BluetoothAdapterState: Entering PendingCommandState
11-22 14:23:24.902  5803  5803 D BluetoothMapService: onReceive
,11-22 14:23:24.902  5803  5819 D BluetoothAdapterProperties: Scan Mode:20
11-22 14:23:24.904  5803  5803 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 14:23:24.905  5803  5803 D BluetoothMapService: STATE_TURNING_OFF
,11-22 14:23:24.905  5803  5803 D BluetoothMapService: MAP Service closeService in
,11-22 14:23:24.905  5803  5803 D BluetoothMapMasInstance0: MAP Service shutdown
11-22 14:23:24.906  5803  5803 D ObexServerSockets0: shutdown(block = true)
,11-22 14:23:24.906  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-22 14:23:24.907  5728  5728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 14:23:24.907  5803  5803 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 14:23:24.908  5803  5840 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-22 14:23:24.908  5803  5803 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-22 14:23:24.909  5803  5841 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-22 14:23:24.910  5803  5828 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-22 14:23:24.913  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:23:24.913  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:23:24.913  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:23:24.913  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:23:24.913  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 14:23:24.913  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 14:23:24.913  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:23:24.913  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:23:24.913  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:23:24.913  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 14:23:24.917  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 14:23:24.917  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 14:23:24.917  5803  5803 I BtOppRfcommListener: stopping Accept Thread
11-22 14:23:24.918  5803  5851 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-22 14:23:24.919  5803  5851 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-22 14:23:24.922  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:24.923  5803  5803 D HeadsetService: Received stop request...Stopping profile...
11-22 14:23:24.925   931   931 D BluetoothHeadset: Proxy object disconnected
11-22 14:23:24.926  3205  3218 D BluetoothHeadset: Proxy object disconnected
,11-22 14:23:24.926  5728  5741 D BluetoothHeadset: Proxy object disconnected
11-22 14:23:24.927  3842  3888 D BluetoothHeadset: Proxy object disconnected
,11-22 14:23:24.927   931   931 D BluetoothHeadset: Proxy object disconnected
11-22 14:23:24.927   931   931 D BluetoothHeadset: Proxy object disconnected
11-22 14:23:24.928  5803  5803 D A2dpService: Received stop request...Stopping profile...
11-22 14:23:24.928  5803  5834 D A2dpStateMachine: Exit Disconnected: -1
,11-22 14:23:24.930   931   931 D BluetoothA2dp: Proxy object disconnected
,11-22 14:23:24.931  5728  5728 D DockEventReceiver: finishStartingService: stopping service
11-22 14:23:24.933  5728  5728 D HeadsetProfile: Bluetooth service disconnected
11-22 14:23:24.933  5803  5803 D HidService: Received stop request...Stopping profile...
11-22 14:23:24.933  5803  5803 D HidService: Stopping Bluetooth HidService
11-22 14:23:24.933  5728  5728 D BluetoothA2dp: Proxy object disconnected
11-22 14:23:24.934  5728  5728 D BluetoothInputDevice: Proxy object disconnected
11-22 14:23:24.934  5728  5728 D HidProfile: Bluetooth service disconnected
,11-22 14:23:24.934  5803  5803 D HealthService: Received stop request...Stopping profile...
11-22 14:23:24.937  3205  3205 D HeadsetProfile: Bluetooth service disconnected
11-22 14:23:24.938  3205  3205 D BluetoothA2dp: Proxy object disconnected
11-22 14:23:24.938  3205  3205 D BluetoothInputDevice: Proxy object disconnected
11-22 14:23:24.938  3205  3205 D HidProfile: Bluetooth service disconnected
,11-22 14:23:24.940  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 14:23:24.941  5803  5803 D PanService: Received stop request...Stopping profile...
11-22 14:23:24.943  5728  5728 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 14:23:24.943  5728  5728 D PanProfile: Bluetooth service disconnected
11-22 14:23:24.944  3205  3205 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-22 14:23:24.944  5803  5803 D BluetoothMapService: Received stop request...Stopping profile...
11-22 14:23:24.944  3205  3205 D PanProfile: Bluetooth service disconnected
11-22 14:23:24.944  5803  5803 D BluetoothMapService: stop()
,11-22 14:23:24.944  5803  5803 D BluetoothMapAppObserver: deinitObservers()
,11-22 14:23:24.945  5803  5803 D BluetoothMapAppObserver: removeReceiver()
11-22 14:23:24.946  3205  3205 D BluetoothMap: Proxy object disconnected
11-22 14:23:24.946  3205  3205 D MapProfile: Bluetooth service disconnected
11-22 14:23:24.946  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-22 14:23:24.946  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:24.946  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:24.946  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:24.947  5728  5728 D BluetoothMap: Proxy object disconnected
11-22 14:23:24.947  5728  5728 D MapProfile: Bluetooth service disconnected
11-22 14:23:24.948  5803  5803 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-22 14:23:24.948  5803  5803 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-22 14:23:24.948  5803  5826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:23:24.948  5803  5826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:23:24.948  5803  5826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:23:24.948  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-22 14:23:24.949  5803  5819 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-22 14:23:24.949  5803  5803 D SapService: Received stop request...Stopping profile...
11-22 14:23:24.949  5803  5803 V SapService: stop()
11-22 14:23:24.950  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-22 14:23:24.950  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:24.950  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:24.950  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:23:24.952  5803  5826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:23:24.952  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-22 14:23:24.952  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:24.952  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:24.952  5803  5826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:23:24.952  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:24.952  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-22 14:23:24.952  5803  5826 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 14:23:24.952  5803  5826 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 14:23:24.952  5803  5803 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-22 14:23:24.952  5803  5826 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 14:23:24.952  5803  5803 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-22 14:23:24.952  5803  5826 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 14:23:24.953  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-22 14:23:24.953  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:24.953  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:24.953  5803  5819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 14:23:24.953  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:24.953  5803  5803 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-22 14:23:24.953  5803  5819 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-22 14:23:24.953  5803  5803 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-22 14:23:24.955  3205  3205 D BluetoothPbap: Proxy object disconnected
11-22 14:23:24.955  3205  3205 D PbapServerProfile: Bluetooth service disconnected
11-22 14:23:24.955  5728  5728 D BluetoothPbap: Proxy object disconnected
11-22 14:23:24.955  5728  5728 D PbapServerProfile: Bluetooth service disconnected
,11-22 14:23:24.955  5803  5803 V BluetoothAdapterState: isTurningOff()=true
,11-22 14:23:24.955  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:24.955  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:24.955  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:24.956  5803  5803 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-22 14:23:24.956  5803  5803 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-22 14:23:24.958  5803  5803 D BluetoothMapService: MAP Service closeService in
,11-22 14:23:24.958  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-22 14:23:24.958  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:24.958  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:24.958  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:24.958  5803  5803 D BluetoothMapService: cleanup()
11-22 14:23:24.959  5803  5803 D BluetoothMapService: MAP Service closeService in
,11-22 14:23:24.959  5803  5803 V BluetoothAdapterState: isTurningOff()=true
11-22 14:23:24.959  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:24.959  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:24.959  5803  5803 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:24.959  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-22 14:23:24.959  5803  5815 D BluetoothAdapterProperties: Setting state to 15
11-22 14:23:24.959  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-22 14:23:24.961  5728  5739 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 14:23:24.962   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:23:24.962  5803  5815 I BluetoothAdapterState: Entering BleOnState
11-22 14:23:24.962  3205  3218 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-22 14:23:24.966   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 14:23:24.966  3205  3217 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:23:24.967  3205  4039 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 14:23:24.967  5728  5741 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:23:24.968  3205  3218 D BluetoothMap: onBluetoothStateChange: up=false
11-22 14:23:24.968  3205  3217 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 14:23:24.968  5728  5739 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 14:23:24.969  5728  5741 D BluetoothPan: onBluetoothStateChange on: false
11-22 14:23:24.970  3205  4039 D BluetoothPan: onBluetoothStateChange on: false
11-22 14:23:24.970  5728  5739 D BluetoothMap: onBluetoothStateChange: up=false
11-22 14:23:24.971   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 14:23:24.971   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-22 14:23:24.971  3842  3862 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-22 14:23:24.971  5728  5741 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-22 14:23:24.972  5803  5815 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-22 14:23:24.972  5803  5815 D BluetoothAdapterProperties: Setting state to 16
,11-22 14:23:24.972  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-22 14:23:24.973  5803  5815 D BluetoothAdapterProperties: onBleDisable
11-22 14:23:24.974  5803  5815 I BluetoothAdapterState: Entering PendingCommandState
11-22 14:23:24.974  5803  5816 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-22 14:23:24.974  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:24.974  5803  5819 D BluetoothAdapterProperties: Scan Mode:20
,11-22 14:23:24.975  5803  5826 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-22 14:23:24.975  5728  5728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 14:23:24.975  5803  5826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 14:23:24.976  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:24.980  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 14:23:24.988  5728  5728 D DockEventReceiver: finishStartingService: stopping service
,11-22 14:23:25.188  5803  5819 I bt_hci  : shut_down
,11-22 14:23:25.193  5803  5823 D bt_hwcfg: hw_epilog_process
,11-22 14:23:25.194  5803  5823 I bt_vendor: low_power_mode_cb
,11-22 14:23:25.197  5803  5823 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-22 14:23:25.197  5803  5823 I bt_vendor: epilog_cb
11-22 14:23:25.198  5803  5823 I bt_hci  : epilog_finished_callback
,11-22 14:23:25.202  5803  5819 I bt_hci_h4: hal_close
,11-22 14:23:25.203  5803  5819 I bt_userial_vendor: device fd = 54 close
,11-22 14:23:25.317  5803  5816 D bt_stack_manager: event_shut_down_stack finished.
,11-22 14:23:25.318  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-22 14:23:25.323  5803  5815 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-22 14:23:25.324  5803  5803 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 14:23:25.325  5803  5803 D BtGatt.GattService: Received stop request...Stopping profile...
,11-22 14:23:25.325  5803  5803 D BtGatt.GattService: stop()
11-22 14:23:25.325  5803  5803 D BtGatt.AdvertiseManager: advertise clients cleared
,11-22 14:23:25.329  5803  5803 V BluetoothAdapterState: isTurningOff()=false
,11-22 14:23:25.329  5803  5803 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:25.329  5803  5803 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 14:23:25.329  5803  5803 V BluetoothAdapterState: isBleTurningOff()=true
11-22 14:23:25.330  5803  5815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-22 14:23:25.330  5803  5815 D BluetoothAdapterProperties: Setting state to 10
,11-22 14:23:25.331  5803  5815 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-22 14:23:25.332  5803  5815 I BluetoothAdapterState: Entering OffState
,11-22 14:23:25.333   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-22 14:23:25.345  5803  5803 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-22 14:23:25.345  5803  5803 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-22 14:23:25.345  5803  5803 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-22 14:23:25.348  5803  5816 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-22 14:23:25.354  5803  5803 I art     : System.exit called, status: 0
,11-22 14:23:25.354  5803  5803 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 14:23:25.386   931  3893 I ActivityManager: Process com.android.bluetooth (pid 5803) has died
,11-22 14:23:25.891   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:26.892   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:27.893   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:28.135  3637  3637 I ConfigService: onDestroy
,11-22 14:23:28.894   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:29.892  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:23:29.892  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 14:23:29.895   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:29.900  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:23:29.900  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cfc6692 removed from the list
11-22 14:23:29.900  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:23:29.903  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 14:23:29.903  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@615e519 added. We now have 4 listener(s)
11-22 14:23:29.903  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:23:29.905  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:29.905  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@615e519 removed from the list
11-22 14:23:29.906  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:23:29.907  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:23:29.907  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7659de added. We now have 4 listener(s)
11-22 14:23:29.907  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:23:30.896   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 14:23:34.917  5662  5709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 14:23:34.950   931   948 I ActivityManager: Start proc 5860:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 14:23:35.040  5860  5860 D AdapterServiceConfig: Adding HeadsetService
,11-22 14:23:35.040  5860  5860 D AdapterServiceConfig: Adding A2dpService
11-22 14:23:35.040  5860  5860 D AdapterServiceConfig: Adding HidService
11-22 14:23:35.040  5860  5860 D AdapterServiceConfig: Adding HealthService
11-22 14:23:35.041  5860  5860 D AdapterServiceConfig: Adding PanService
11-22 14:23:35.041  5860  5860 D AdapterServiceConfig: Adding GattService
11-22 14:23:35.041  5860  5860 D AdapterServiceConfig: Adding BluetoothMapService
11-22 14:23:35.041  5860  5860 D AdapterServiceConfig: Adding SapService
,11-22 14:23:35.052   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fb22cf1:true
,11-22 14:23:35.052  5860  5860 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 14:23:35.055  5860  5860 I bt_bluedroid: init
,11-22 14:23:35.056  5860  5872 I BluetoothAdapterState: Entering OffState
,11-22 14:23:35.058  5860  5873 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-22 14:23:35.058  5860  5873 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 14:23:35.059  5860  5873 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-22 14:23:35.059  5860  5873 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-22 14:23:35.060  5860  5860 I bt_bluedroid: get_profile_interface socket
,11-22 14:23:35.062  5860  5876 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 14:23:35.062  5860  5860 I bt_bluedroid: get_profile_interface sdp
11-22 14:23:35.063  5860  5876 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 14:23:35.068  5860  5871 I bt_bluedroid: config_hci_snoop_log
,11-22 14:23:35.069   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 14:23:35.073  5860  5872 D BluetoothAdapterState: Current state: OFF, message: 0
11-22 14:23:35.074  5860  5872 D BluetoothAdapterProperties: Setting state to 14
11-22 14:23:35.074  5860  5872 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-22 14:23:35.075  5860  5872 D BluetoothBondStateMachine: make
,11-22 14:23:35.077  5860  5877 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 14:23:35.080  5860  5872 I BluetoothAdapterState: Entering PendingCommandState
,11-22 14:23:35.081  5860  5860 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-22 14:23:35.084  5860  5860 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
,11-22 14:23:35.085  5860  5860 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 14:23:35.085  5860  5860 D BtGatt.GattService: Received start request. Starting profile...
11-22 14:23:35.085  5860  5860 D BtGatt.GattService: start()
11-22 14:23:35.086  5860  5860 I bt_bluedroid: get_profile_interface gatt
,11-22 14:23:35.087  5860  5860 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
11-22 14:23:35.087  5860  5860 D BtGatt.AdvertiseManager: advertise manager created
,11-22 14:23:35.093  5860  5860 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:35.093  5860  5860 V BluetoothAdapterState: isTurningOn()=false
11-22 14:23:35.093  5860  5860 V BluetoothAdapterState: isBleTurningOn()=true
,11-22 14:23:35.093  5860  5860 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:35.094  5860  5872 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-22 14:23:35.095  5860  5872 I bt_bluedroid: bt_bluedroid
,11-22 14:23:35.095  5860  5873 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-22 14:23:35.096  5860  5873 I bt_hci  : start_up
,11-22 14:23:35.101  5860  5873 I bt_vendor: alloc value 0xf3b7f871
,11-22 14:23:35.101  5860  5873 I bt_vendor: init
11-22 14:23:35.101  5860  5873 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-22 14:23:35.102  5860  5873 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 14:23:35.212  5860  5873 D bt_hci  : start_up starting async portion
,11-22 14:23:35.209  5881  5881 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 14:23:35.213  5860  5880 I bt_hci  : event_finish_startup
11-22 14:23:35.213  5860  5880 I bt_hci_h4: hal_open
11-22 14:23:35.214  5860  5880 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-22 14:23:35.217  5860  5880 I bt_userial_vendor: device fd = 54 open
,11-22 14:23:35.233  5860  5880 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 14:23:35.237  5860  5880 D bt_hwcfg: Chipset BCM4358A3
,11-22 14:23:35.237  5860  5880 D bt_hwcfg: Target name = [BCM4358A3]
11-22 14:23:35.237  5860  5880 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 14:23:35.645  5860  5880 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-22 14:23:35.646  5860  5880 D bt_hwcfg: Settlement delay -- 100 ms
11-22 14:23:35.646  5860  5880 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 14:23:35.778  5860  5880 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-22 14:23:35.779  5860  5880 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-22 14:23:35.782  5860  5880 I bt_hwcfg: vendor lib fwcfg completed
11-22 14:23:35.782  5860  5880 I bt_vendor: firmware callback
11-22 14:23:35.782  5860  5880 I bt_hci  : firmware_config_callback
,11-22 14:23:35.791  5860  5883 I bt_btu  : btu_task pending for preload complete event
,11-22 14:23:35.791  5860  5883 I bt_btu_task: Bluetooth chip preload is complete
11-22 14:23:35.791  5860  5883 I bt_btu  : btu_task received preload complete event
,11-22 14:23:35.799  5860  5883 I         : BTE_InitTraceLevels -- TRC_HCI
,11-22 14:23:35.799  5860  5883 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-22 14:23:35.799  5860  5883 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-22 14:23:35.800  5860  5883 I         : BTE_InitTraceLevels -- TRC_AVDT
11-22 14:23:35.800  5860  5883 I         : BTE_InitTraceLevels -- TRC_AVRC
11-22 14:23:35.800  5860  5883 I         : BTE_InitTraceLevels -- TRC_A2D
,11-22 14:23:35.800  5860  5883 I         : BTE_InitTraceLevels -- TRC_BNEP
11-22 14:23:35.800  5860  5883 I         : BTE_InitTraceLevels -- TRC_BTM
11-22 14:23:35.800  5860  5883 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 14:23:35.800  5860  5883 I         : BTE_InitTraceLevels -- TRC_PAN
11-22 14:23:35.800  5860  5883 I         : BTE_InitTraceLevels -- TRC_SDP
11-22 14:23:35.801  5860  5883 I         : BTE_InitTraceLevels -- TRC_GATT
,11-22 14:23:35.801  5860  5883 I         : BTE_InitTraceLevels -- TRC_SMP
11-22 14:23:35.801  5860  5883 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-22 14:23:35.801  5860  5883 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 14:23:35.885  5860  5883 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3afd549
,11-22 14:23:35.885  5860  5883 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3afd549 
,11-22 14:23:35.912  5860  5876 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 14:23:35.913  5860  5876 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 14:23:35.914  5860  5876 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 14:23:35.916  5860  5876 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 14:23:35.919  5860  5876 D BluetoothAdapterProperties: Scan Mode:20
,11-22 14:23:35.919  5860  5876 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 14:23:35.919  5860  5876 D bt_hci  : do_postload posting postload work item
11-22 14:23:35.920  5860  5880 I bt_hci  : event_postload
11-22 14:23:35.920  5860  5880 I bt_vendor: sco_config_cb
11-22 14:23:35.920  5860  5880 I bt_hci  : sco_config_callback postload finished.
11-22 14:23:35.922  5860  5876 D bt_bte_conf: Device ID record 1 : primary
,11-22 14:23:35.922  5860  5876 D bt_bte_conf:   vendorId            = 000f
,11-22 14:23:35.922  5860  5876 D bt_bte_conf:   vendorIdSource      = 0001
11-22 14:23:35.922  5860  5876 D bt_bte_conf:   product             = 1200
11-22 14:23:35.922  5860  5876 D bt_bte_conf:   version             = 1436
,11-22 14:23:35.922  5860  5876 D bt_bte_conf:   clientExecutableURL = 
,11-22 14:23:35.922  5860  5876 D bt_bte_conf:   serviceDescription  = 
11-22 14:23:35.922  5860  5876 D bt_bte_conf:   documentationURL    = 
11-22 14:23:35.923  5860  5876 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-22 14:23:35.923  5860  5873 D bt_stack_manager: event_start_up_stack finished
11-22 14:23:35.924  5860  5872 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-22 14:23:35.924  5860  5872 D BluetoothAdapterProperties: Setting state to 15
,11-22 14:23:35.924  5860  5872 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 14:23:35.927  5860  5872 I BluetoothAdapterState: Entering BleOnState
11-22 14:23:35.929  5860  5880 I bt_vendor: low_power_mode_cb
,11-22 14:23:35.934  5860  5872 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-22 14:23:35.934  5860  5872 D BluetoothAdapterProperties: Setting state to 11
11-22 14:23:35.934  5860  5872 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-22 14:23:35.940  5860  5860 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
,11-22 14:23:35.942  5860  5860 D HeadsetService: Received start request. Starting profile...
,11-22 14:23:35.947  5860  5860 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-22 14:23:35.948  5860  5860 D HeadsetStateMachine: make
,11-22 14:23:35.953  5860  5872 I BluetoothAdapterState: Entering PendingCommandState
,11-22 14:23:35.957  5860  5860 D HeadsetStateMachine: max_hf_connections = 1
11-22 14:23:35.958  5860  5860 I bt_bluedroid: get_profile_interface handsfree
,11-22 14:23:35.958  5860  5876 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-22 14:23:35.959  5860  5876 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-22 14:23:35.962  5860  5860 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
,11-22 14:23:35.963  5860  5860 D A2dpService: Received start request. Starting profile...
11-22 14:23:35.963  5860  5860 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-22 14:23:35.963  5860  5860 I bt_bluedroid: get_profile_interface avrcp
,11-22 14:23:35.972  5860  5860 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-22 14:23:35.972  5860  5860 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-22 14:23:35.972  5860  5860 D A2dpStateMachine: make
,11-22 14:23:35.974  5860  5860 I bt_bluedroid: get_profile_interface a2dp
,11-22 14:23:35.974  5860  5876 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-22 14:23:35.977  5860  5891 D A2dpStateMachine: Enter Disconnected: -2
,11-22 14:23:35.977  5860  5860 I BluetoothHidServiceJni: classInitNative: succeeds
,11-22 14:23:35.978  5860  5860 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
,11-22 14:23:35.979  5860  5860 D HidService: Received start request. Starting profile...
11-22 14:23:35.979  5860  5860 I bt_bluedroid: get_profile_interface hidhost
11-22 14:23:35.979  5860  5860 D HidService: setHidService(): set to: null
11-22 14:23:35.979  5860  5876 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ade56d
11-22 14:23:35.980  5860  5876 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-22 14:23:35.981  5860  5860 I BluetoothHealthServiceJni: classInitNative: succeeds
11-22 14:23:35.981  5860  5860 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
,11-22 14:23:35.982  5860  5860 D HealthService: Received start request. Starting profile...
11-22 14:23:35.983  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 14:23:35.985  5860  5860 I bt_bluedroid: get_profile_interface health
11-22 14:23:35.985  5860  5860 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-22 14:23:35.986  5860  5860 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
11-22 14:23:35.986  5860  5860 D PanService: Received start request. Starting profile...
11-22 14:23:35.987  5860  5860 D BluetoothPanServiceJni: initializeNative(L110): pan
11-22 14:23:35.987  5860  5860 I bt_bluedroid: get_profile_interface pan
11-22 14:23:35.987  5860  5876 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-22 14:23:35.989  5860  5860 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
11-22 14:23:35.989  5860  5860 D BluetoothMapService: Received start request. Starting profile...
11-22 14:23:35.990  5860  5860 D BluetoothMapService: start()
,11-22 14:23:35.993  5860  5860 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-22 14:23:35.993  5860  5860 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-22 14:23:35.993  5860  5860 D BluetoothMapAppObserver: createReceiver()
11-22 14:23:35.995  5860  5860 D BluetoothMapAppObserver: initObservers()
11-22 14:23:35.995  5860  5860 D BluetoothMapAppObserver: getEnabledAccountItems()
11-22 14:23:36.001  5860  5860 V SapService: SapBinder()
11-22 14:23:36.002  5860  5860 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
11-22 14:23:36.002  5860  5860 D SapService: Received start request. Starting profile...
11-22 14:23:36.003  5860  5860 V SapService: start()
,11-22 14:23:36.006  5860  5860 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:36.006  5860  5860 V BluetoothAdapterState: isTurningOn()=true
,11-22 14:23:36.006  5860  5860 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:36.006  5860  5860 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:36.006  5860  5860 V BluetoothAdapterState: isTurningOff()=false
,11-22 14:23:36.007  5860  5860 V BluetoothAdapterState: isTurningOn()=true
11-22 14:23:36.007  5860  5860 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:36.007  5860  5889 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-22 14:23:36.007  5860  5860 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:36.007  5860  5860 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:36.007  5860  5860 V BluetoothAdapterState: isTurningOn()=true
11-22 14:23:36.007  5860  5860 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:36.007  5860  5860 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:23:36.008  5860  5860 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:36.008  5860  5860 V BluetoothAdapterState: isTurningOn()=true
,11-22 14:23:36.008  5860  5860 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:36.008  5860  5860 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:36.008  5860  5860 V BluetoothAdapterState: isTurningOff()=false
,11-22 14:23:36.008  5860  5860 V BluetoothAdapterState: isTurningOn()=true
11-22 14:23:36.008  5860  5860 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:36.009  5860  5860 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:36.009  5860  5860 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:36.009  5860  5860 V BluetoothAdapterState: isTurningOn()=true
11-22 14:23:36.009  5860  5860 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:36.009  5860  5860 V BluetoothAdapterState: isBleTurningOff()=false
11-22 14:23:36.010  5860  5860 V BluetoothAdapterState: isTurningOff()=false
11-22 14:23:36.010  5860  5860 V BluetoothAdapterState: isTurningOn()=true
11-22 14:23:36.010  5860  5860 V BluetoothAdapterState: isBleTurningOn()=false
11-22 14:23:36.010  5860  5860 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 14:23:36.010  5860  5872 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-22 14:23:36.010  5860  5872 D BluetoothAdapterProperties: ScanMode =  20
11-22 14:23:36.010  5860  5872 D BluetoothAdapterProperties: State =  11
11-22 14:23:36.011  5860  5872 D BluetoothAdapterProperties: Setting state to 12
11-22 14:23:36.011  5860  5872 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 14:23:36.011  5728  5741 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 14:23:36.011  5860  5872 I BluetoothAdapterState: Entering OnState
11-22 14:23:36.012  5860  5876 D BluetoothAdapterProperties: Scan Mode:21
11-22 14:23:36.012  5860  5876 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 14:23:36.013   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:23:36.013  3205  3218 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-22 14:23:36.015   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-22 14:23:36.016   931   931 D BluetoothA2dp: Proxy object connected
,11-22 14:23:36.016  3205  3217 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:23:36.017  3205  4039 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 14:23:36.017  3205  3205 D BluetoothInputDevice: Proxy object connected
11-22 14:23:36.017  3205  3205 D HidProfile: Bluetooth service connected
11-22 14:23:36.018  5728  5741 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:23:36.019  3205  3218 D BluetoothMap: onBluetoothStateChange: up=true
,11-22 14:23:36.020  3205  3217 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-22 14:23:36.020  5860  5860 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 14:23:36.021  5860  5860 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-22 14:23:36.022  3205  3205 D BluetoothA2dp: Proxy object connected
11-22 14:23:36.022  5728  5739 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 14:23:36.022  5728  5728 D BluetoothA2dp: Proxy object connected
11-22 14:23:36.022  5860  5860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 14:23:36.024  5728  5741 D BluetoothPan: onBluetoothStateChange on: true
11-22 14:23:36.025  5860  5860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 14:23:36.025  3205  3218 D BluetoothPan: onBluetoothStateChange on: true
,11-22 14:23:36.026  5860  5860 D ObexServerSockets: Succeed to create listening sockets 
11-22 14:23:36.026  5860  5860 D ObexServerSockets0: startAccept()
11-22 14:23:36.026  5860  5860 D ObexServerSockets0: prepareForNewConnect()
,11-22 14:23:36.027  5728  5739 D BluetoothMap: onBluetoothStateChange: up=true
,11-22 14:23:36.028   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-22 14:23:36.028  5860  5860 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-22 14:23:36.028  5860  5860 D BluetoothSdpJni: SDP Create record success - handle: 0
11-22 14:23:36.028   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:23:36.029  3842  3888 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 14:23:36.029  5860  5896 D ObexServerSockets0: Accepting socket connection...
11-22 14:23:36.030  5728  5741 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 14:23:36.030  5860  5897 D ObexServerSockets0: Accepting socket connection...
11-22 14:23:36.030  3205  3205 D BluetoothMap: Proxy object connected
11-22 14:23:36.030  3205  3205 D MapProfile: Bluetooth service connected
11-22 14:23:36.030  3205  3205 D BluetoothMap: getConnectedDevices()
,11-22 14:23:36.031  5728  5728 D BluetoothMap: Proxy object connected
11-22 14:23:36.031  5728  5728 D MapProfile: Bluetooth service connected
11-22 14:23:36.031  5728  5728 D BluetoothMap: getConnectedDevices()
11-22 14:23:36.032  3205  3205 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 14:23:36.032  3205  3205 D PanProfile: Bluetooth service connected
11-22 14:23:36.034   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
11-22 14:23:36.034  5860  5860 D BluetoothMapService: onReceive
11-22 14:23:36.034  5860  5860 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 14:23:36.034  5860  5860 D BluetoothMapService: STATE_ON
11-22 14:23:36.036  5728  5728 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 14:23:36.036  5728  5728 D PanProfile: Bluetooth service connected
11-22 14:23:36.036  5728  5728 D BluetoothInputDevice: Proxy object connected
11-22 14:23:36.036  5728  5728 D HidProfile: Bluetooth service connected
11-22 14:23:36.037  5860  5900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 14:23:36.040  5860  5900 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-22 14:23:36.040  5860  5900 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-22 14:23:36.044  5728  5728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 14:23:36.051  3637  3637 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 14:23:36.053  5728  5728 D DockEventReceiver: finishStartingService: stopping service
11-22 14:23:36.058  5728  5728 D BluetoothPbap: Proxy object connected
11-22 14:23:36.058  5728  5728 D PbapServerProfile: Bluetooth service connected
11-22 14:23:36.059  3205  3205 D BluetoothPbap: Proxy object connected
11-22 14:23:36.059  3205  3205 D PbapServerProfile: Bluetooth service connected
,11-22 14:23:36.064  5860  5860 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 14:23:36.064  5860  5860 D ObexServerSockets0: prepareForNewConnect()
,11-22 14:23:36.067  5860  5905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 14:23:36.081  5860  5909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 14:23:36.082  5860  5909 I BtOppRfcommListener: Accept thread started.
,11-22 14:23:36.115   931   931 D BluetoothHeadset: Proxy object connected
,11-22 14:23:36.115  3205  3217 D BluetoothHeadset: Proxy object connected
11-22 14:23:36.115  3205  3205 D HeadsetProfile: Bluetooth service connected
11-22 14:23:36.115  5728  5739 D BluetoothHeadset: Proxy object connected
11-22 14:23:36.116  3842  3862 D BluetoothHeadset: Proxy object connected
11-22 14:23:36.116   931   931 D BluetoothHeadset: Proxy object connected
,11-22 14:23:36.116   931   931 D BluetoothHeadset: Proxy object connected
11-22 14:23:36.117  3205  4039 D BluetoothHeadset: Proxy object connected
,11-22 14:23:36.118  5728  5728 D HeadsetProfile: Bluetooth service connected
11-22 14:23:36.118  3205  3205 D HeadsetProfile: Bluetooth service connected
,11-22 14:23:36.119  5728  5741 D BluetoothHeadset: Proxy object connected
,11-22 14:23:36.120  5728  5728 D HeadsetProfile: Bluetooth service connected
,11-22 14:23:36.129   931   948 D BluetoothHeadset: Proxy object connected
,11-22 14:23:36.129   931   948 D BluetoothHeadset: Proxy object connected
11-22 14:23:36.129  3842  4048 D BluetoothHeadset: Proxy object connected
,11-22 14:23:39.934  5662  5709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:23:39.934  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:23:39.934  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:23:39.934  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 14:23:39.934  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:23:39.934  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:23:39.934  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:23:39.934  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:23:39.934  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 14:23:39.939  5662  5709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 14:23:39.940  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:39.940  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7659de removed from the list
11-22 14:23:39.940  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:23:39.941  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 14:23:39.941  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7a17bf added. We now have 4 listener(s)
11-22 14:23:39.942  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:23:39.945   931  3893 D WifiService: setWifiEnabled: false pid=5662, uid=10077
,11-22 14:23:39.946   931  3893 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 14:23:40.897   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:41.898   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:42.899   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:43.900   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:44.901   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:23:44.955  5662  5709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 14:23:44.956   931   942 D WifiService: setWifiEnabled: true pid=5662, uid=10077
11-22 14:23:44.957   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 14:23:44.968   508   924 D SoftapController: Softap fwReload - Ok
,11-22 14:23:44.973   508   924 D CommandListener: Setting iface cfg
,11-22 14:23:44.974   508   924 D CommandListener: Trying to bring down wlan0
11-22 14:23:44.975   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-22 14:23:44.979   931  3036 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 14:23:45.647   931  3036 D wifi    : set interface wlan0 flags (UP)
,11-22 14:23:45.652   931  3036 I WifiHAL : Initializing wifi
11-22 14:23:45.652   931  3036 I WifiHAL : Creating socket
11-22 14:23:45.656   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-22 14:23:45.658   931  3036 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-22 14:23:45.658   931  3036 D wifi    : Did set static halHandle = 0x7f72291680
11-22 14:23:45.659   931  3036 D wifi    : halHandle = 0x7f72291680, mVM = 0x7f8e88d140, mCls = 0x201946
11-22 14:23:45.660   931  3036 D wifi    : array field set
,11-22 14:23:45.660   931  3036 I WifiNative-HAL: interface[0] = wlan0
11-22 14:23:45.663   931  5914 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547376141952
11-22 14:23:45.664   931  5914 D wifi    : waitForHalEvents called, vm = 0x7f8e88d140, obj = 0x201946, env = 0x7f83ddf6c0
,11-22 14:23:45.709  5915  5915 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 14:23:45.764   931  3036 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-22 14:23:45.766   931  3036 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-22 14:23:45.782  5915  5915 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 14:23:45.857  5915  5915 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 14:23:45.857  5915  5915 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 14:23:45.902   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 14:23:46.784   931  3036 D WifiConfigStore: Loading config and enabling all networks 
,11-22 14:23:46.834   931  3036 D WifiConfigStore: loaded 0 passpoint configs
,11-22 14:23:46.836   931  3036 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-22 14:23:46.837   931  3036 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-22 14:23:46.838   931  3036 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-22 14:23:46.838   931  3036 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-22 14:23:46.839   931  3036 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-22 14:23:46.840   931  3036 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-22 14:23:46.841   931  3036 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-22 14:23:46.841   931  3036 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-22 14:23:46.841   931  3036 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-22 14:23:46.841   931  3036 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-22 14:23:46.842   931  3036 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-22 14:23:46.842   931  3036 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-22 14:23:46.847   931  3036 D WifiNative-HAL: Setting external_sim to 1
,11-22 14:23:46.848   931  3036 D wifi    : setting dfs flag to true, 0x7f6fce0dc0
11-22 14:23:46.848  5065  5065 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 14:23:46.849   931  3036 D WifiStateMachine: Setting OUI to DA-A1-19
11-22 14:23:46.849   931  3036 D wifi    : setting scan oui 0x7f6fce0dc0
11-22 14:23:46.849   931  3036 D WifiHAL : Sending mac address OUI
,11-22 14:23:46.856   931  3036 E native  : do suspend false
,11-22 14:23:46.868   931  3036 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-22 14:23:46.868   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-22 14:23:46.868   931   931 D RttService: SCAN_AVAILABLE : 3
11-22 14:23:46.869   931  3145 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-22 14:23:46.870   508   924 D CommandListener: Setting iface cfg
,11-22 14:23:46.876   931  3025 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)'
11-22 14:23:46.877   931  3025 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 14:23:46.883   931  3025 D WifiNative-HAL: p2pGetDeviceAddress
11-22 14:23:46.883   931  3025 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-22 14:23:46.899   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=260830 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=24 mControllerEnergyUsed=91 }
,11-22 14:23:49.984  5662  5709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 14:23:49.984  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 14:23:49.984  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 14:23:49.984  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 14:23:49.984  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 14:23:49.984  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 14:23:49.984  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 14:23:49.984  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 14:23:49.984  5662  5709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 14:23:49.991  5662  5709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 14:23:49.992  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:49.992  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7a17bf removed from the list
,11-22 14:23:49.992  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 14:23:50.001  5662  5709 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-22 14:23:50.002  5662  5709 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-22 14:23:50.006  5662  5709 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7227cbf Bundle[{}]
,11-22 14:23:50.007  5662  5709 I io.jxcore.node.LifeCycleMonitor: start: OK
11-22 14:23:50.007  5662  5709 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-22 14:23:50.008  5662  5709 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-22 14:23:50.008  5662  5709 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-22 14:23:50.010  5662  5709 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-22 14:23:50.012  5662  5709 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-22 14:23:50.022  5662  5709 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-22 14:23:50.023  5662  5709 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-22 14:23:50.024  5662  5709 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
11-22 14:23:50.025   931  3036 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-22 14:23:50.027  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 14:23:50.027  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f27e8c added. We now have 3 listener(s)
11-22 14:23:50.028   931  3036 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-22 14:23:50.028   931  3036 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 14:23:50.031  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4",
11-22 14:23:50.032  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:23:50.032  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:23:50.032  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:23:50.032  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@716b9d5 added. We now have 4 listener(s)
11-22 14:23:50.032  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:23:50.033  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 14:23:50.034  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:23:50.035  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a35ea added. We now have 4 listener(s)
,11-22 14:23:50.036  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 14:23:50.037  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:23:50.037  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:23:50.037  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:23:50.037  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac270db added. We now have 5 listener(s)
11-22 14:23:50.037  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:23:50.037  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:23:50.037  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:23:50.037  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:23:50.037  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:23:50.038  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:23:50.038  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:23:50.038  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f27e8c removed from the list
11-22 14:23:50.038  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.038  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@716b9d5 removed from the list
11-22 14:23:50.038  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:23:50.038  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.038  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.039   931  3036 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
11-22 14:23:50.040  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.041  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.041  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.041  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:23:50.041  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:23:50.041  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.041  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@716b9d5 not in the list
11-22 14:23:50.041  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.041  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.043  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.043  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.043  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.043  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:23:50.043  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 14:23:50.043  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 14:23:50.043  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac270db removed from the list
11-22 14:23:50.043  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:23:50.043  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:23:50.043  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:23:50.043  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a35ea removed from the list
11-22 14:23:50.044  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:23:50.044  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78ef778 added. We now have 3 listener(s)
11-22 14:23:50.046  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:23:50.046  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:23:50.046  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:23:50.046  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:23:50.046  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6161e51 added. We now have 4 listener(s)
,11-22 14:23:50.046  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:23:50.047  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 14:23:50.047  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:23:50.048  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84dc6b6 added. We now have 4 listener(s)
11-22 14:23:50.049  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:23:50.049  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:23:50.049  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:23:50.049  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:23:50.049  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d3fb7 added. We now have 5 listener(s)
11-22 14:23:50.049  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:23:50.050  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:23:50.050  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-22 14:23:50.050  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 14:23:50.050  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:23:50.050  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 14:23:50.051  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 14:23:50.054  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 14:23:50.054  5662  5709 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 14:23:50.054  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 14:23:50.058  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.058  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 14:23:50.059  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 14:23:50.059  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 14:23:50.059  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 14:23:50.063  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.063  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 14:23:50.063  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 14:23:50.063  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 14:23:50.063  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 14:23:50.063  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.064  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:23:50.067  5860  5901 D BtGatt.GattService: registerClient() - UUID=56c2c4f3-8434-4e67-a760-1b8bf28dd378
11-22 14:23:50.068  5860  5876 D BtGatt.GattService: onClientRegistered() - UUID=56c2c4f3-8434-4e67-a760-1b8bf28dd378, clientIf=5
11-22 14:23:50.069  5662  5672 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-22 14:23:50.070  5860  5871 D BtGatt.GattService: start scan with filters
,11-22 14:23:50.074  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 14:23:50.075  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.075  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 14:23:50.075  5860  5879 D BtGatt.ScanManager: handling starting scan
,11-22 14:23:50.075  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.075  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 14:23:50.075  5662  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 14:23:50.075  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.075  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 14:23:50.075  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 14:23:50.075  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.075  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.075  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.076  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.076  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 14:23:50.076  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.077  5860  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e206d63
11-22 14:23:50.078   931  3036 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
11-22 14:23:50.078  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.079  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:23:50.079  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.079  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.079  5662  5709 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 14:23:50.079  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 14:23:50.079  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 14:23:50.079  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:23:50.079  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:23:50.079  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:23:50.079  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-22 14:23:50.080  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.082  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-22 14:23:50.082  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.082  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.082  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:23:50.083  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:23:50.083  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.083  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:23:50.083  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 14:23:50.083  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.083  5915  5915 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
11-22 14:23:50.083  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.083  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.083  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 14:23:50.083  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.084  5860  5876 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 14:23:50.084  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:23:50.084  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:23:50.085  5860  5879 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 14:23:50.085  5860  5871 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 14:23:50.085  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-22 14:23:50.089  5662  5709 D BluetoothAdapter: STATE_ON
,11-22 14:23:50.090  5860  5899 D BtGatt.GattService: stopScan() - queue size =1
11-22 14:23:50.091  5860  5888 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 14:23:50.091  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 14:23:50.091  5860  5876 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 14:23:50.091  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.091  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.091  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 14:23:50.091  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.091  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.091  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.091  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.091  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 14:23:50.092  5860  5879 D BtGatt.ScanManager: Starting BLE batch scan
,11-22 14:23:50.092  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.092  5860  5879 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 14:23:50.092  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.092  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.092  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 14:23:50.092  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 14:23:50.093  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 14:23:50.093  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.096  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.096  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:23:50.096  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.096  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.096  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:23:50.096  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:23:50.096  5662  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 14:23:50.096  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.096  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 14:23:50.097  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 14:23:50.097  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.097  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.097  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.097  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:23:50.097  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.097  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.100  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.100  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.100  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 14:23:50.101  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:23:50.101  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:23:50.101  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:23:50.101  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:23:50.101  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:23:50.101  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:23:50.101  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78ef778 removed from the list
11-22 14:23:50.101  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.101  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6161e51 removed from the list
11-22 14:23:50.101  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:23:50.102  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.102  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.103  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.103  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.103  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.103  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:23:50.103  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:23:50.103  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.103  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6161e51 not in the list
11-22 14:23:50.103  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.103  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.104  5860  5876 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 14:23:50.104  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:23:50.104  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.104  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.104  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.104  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:23:50.104  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:23:50.104  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.104  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d3fb7 removed from the list
11-22 14:23:50.104  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:23:50.104  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:23:50.104  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:23:50.104  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84dc6b6 removed from the list
11-22 14:23:50.105  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:23:50.105  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab53d90 added. We now have 3 listener(s)
11-22 14:23:50.107  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:23:50.107  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 14:23:50.107  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:23:50.107  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:23:50.107  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54d4689 added. We now have 4 listener(s)
11-22 14:23:50.107  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:23:50.107  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 14:23:50.108  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:23:50.108  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45af68e added. We now have 4 listener(s)
11-22 14:23:50.109  5860  5876 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 14:23:50.109  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.110  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:23:50.110  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:23:50.110  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:23:50.110  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 14:23:50.111  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae6eaf added. We now have 5 listener(s)
11-22 14:23:50.111  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:23:50.111  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 14:23:50.111  5860  5879 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:23:50.111  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:23:50.112  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 14:23:50.112  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 14:23:50.112  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:23:50.112  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 14:23:50.116  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 14:23:50.117  5860  5876 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 14:23:50.117  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.117  5860  5876 E BtGatt.ContextMap: Context not found for ID 5
,11-22 14:23:50.119  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 14:23:50.119  5662  5709 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 14:23:50.119  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 14:23:50.123  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.123  5860  5876 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 14:23:50.123  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 14:23:50.123  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.123  5860  5879 D BtGatt.ScanManager: stopping BLe Batch
,11-22 14:23:50.124  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 14:23:50.124  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 14:23:50.124  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 14:23:50.127  5860  5876 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 14:23:50.127  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.127  5860  5879 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 14:23:50.129  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.129  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 14:23:50.130  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 14:23:50.130  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 14:23:50.130  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 14:23:50.130  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.130  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:23:50.132  5860  5876 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 14:23:50.132  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:23:50.132  5860  5888 D BtGatt.GattService: registerClient() - UUID=c2d788c2-b39d-4b35-91e7-74d85fdba322
11-22 14:23:50.133  5860  5876 D BtGatt.GattService: onClientRegistered() - UUID=c2d788c2-b39d-4b35-91e7-74d85fdba322, clientIf=5
,11-22 14:23:50.133  5662  5672 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-22 14:23:50.133  5860  5871 D BtGatt.GattService: start scan with filters
11-22 14:23:50.135  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 14:23:50.135  5860  5879 D BtGatt.ScanManager: handling starting scan
,11-22 14:23:50.135  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.135  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 14:23:50.136  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.136  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 14:23:50.136  5662  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 14:23:50.136  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.136  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 14:23:50.136  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 14:23:50.136  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.136  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.136  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.136  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.137  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 14:23:50.137  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.139  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.139  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 14:23:50.139  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.139  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.139  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.139  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:23:50.139  5662  5709 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-22 14:23:50.139  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:23:50.139  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:23:50.139  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:23:50.139  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:23:50.139  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:23:50.139  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-22 14:23:50.139  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:23:50.140  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:23:50.140  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab53d90 removed from the list
11-22 14:23:50.140  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.140  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54d4689 removed from the list
11-22 14:23:50.140  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:23:50.140  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:23:50.140  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:23:50.140  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.140  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-22 14:23:50.140  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-22 14:23:50.140  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-22 14:23:50.140  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:23:50.140  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.141  5860  5876 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 14:23:50.141  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.141  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.141  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.141  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.141  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.141  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.141  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.141  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 14:23:50.141  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:23:50.141  5860  5879 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 14:23:50.141  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:23:50.141  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.141  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54d4689 not in the list
11-22 14:23:50.141  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:23:50.141  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.141  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:23:50.141  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 14:23:50.141  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.141  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.141  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.142  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 14:23:50.142  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.144  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:23:50.144  5860  5870 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 14:23:50.144  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 14:23:50.145  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:23:50.145  5860  5871 D BtGatt.GattService: stopScan() - queue size =1
,11-22 14:23:50.146  5860  5876 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 14:23:50.146  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.146  5860  5879 D BtGatt.ScanManager: Starting BLE batch scan
11-22 14:23:50.146  5860  5879 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 14:23:50.146  5860  5888 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 14:23:50.146  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 14:23:50.146  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.146  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 14:23:50.146  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.147  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.147  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.147  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.147  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-22 14:23:50.147  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.147  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.154  5860  5876 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 14:23:50.147  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.157  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.157  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 14:23:50.157  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-22 14:23:50.157  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 14:23:50.158  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.161  5860  5876 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-22 14:23:50.161  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.161  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.161  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:23:50.162  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.162  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.162  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:23:50.162  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 14:23:50.162  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.162  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae6eaf removed from the list
11-22 14:23:50.162  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:23:50.162  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:23:50.162  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:23:50.162  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:23:50.162  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:23:50.162  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45af68e removed from the list
11-22 14:23:50.162  5662  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 14:23:50.162  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.162  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-22 14:23:50.162  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 14:23:50.162  5860  5879 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:23:50.163  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.163  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.163  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.163  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:23:50.163  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.163  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:23:50.163  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.163  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46b2ea8 added. We now have 3 listener(s)
11-22 14:23:50.164  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.164  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-22 14:23:50.164  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.164  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:23:50.165  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:23:50.165  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:23:50.165  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:23:50.165  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ca3dc1 added. We now have 4 listener(s)
11-22 14:23:50.165  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 14:23:50.166  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 14:23:50.167  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:23:50.167  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4334966 added. We now have 4 listener(s)
,11-22 14:23:50.168  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 14:23:50.168  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:23:50.168  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:23:50.169  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:23:50.169  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51784a7 added. We now have 5 listener(s)
11-22 14:23:50.169  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:23:50.169  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:23:50.169  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-22 14:23:50.169  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 14:23:50.169  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 14:23:50.169  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 14:23:50.170  5860  5876 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 14:23:50.170  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.170  5860  5876 E BtGatt.ContextMap: Context not found for ID 5
11-22 14:23:50.171  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 14:23:50.174  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-22 14:23:50.175  5662  5709 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 14:23:50.175  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 14:23:50.176  5860  5876 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 14:23:50.176  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.176  5860  5879 D BtGatt.ScanManager: stopping BLe Batch
,11-22 14:23:50.181  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.181  5860  5876 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 14:23:50.181  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.181  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 14:23:50.181  5860  5879 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 14:23:50.182  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 14:23:50.182  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 14:23:50.182  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 14:23:50.186  5860  5876 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 14:23:50.186  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.187  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.187  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 14:23:50.187  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 14:23:50.187  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 14:23:50.187  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-22 14:23:50.187  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.188  5662  5709 D BluetoothAdapter: STATE_ON
,11-22 14:23:50.190  5860  5888 D BtGatt.GattService: registerClient() - UUID=536ec294-e070-456e-a9a0-8a17ce0b1494
,11-22 14:23:50.190  5860  5876 D BtGatt.GattService: onClientRegistered() - UUID=536ec294-e070-456e-a9a0-8a17ce0b1494, clientIf=5
11-22 14:23:50.191  5662  5673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 14:23:50.191  5860  5871 D BtGatt.GattService: start scan with filters
,11-22 14:23:50.193  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 14:23:50.193  5860  5879 D BtGatt.ScanManager: handling starting scan
11-22 14:23:50.193  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.193  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 14:23:50.193  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.193  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 14:23:50.194  5662  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 14:23:50.194  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.194  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 14:23:50.194  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 14:23:50.194  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.194  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.194  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-22 14:23:50.194  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.194  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 14:23:50.195  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.196  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.196  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 14:23:50.197  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.197  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.197  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.198  5860  5876 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 14:23:50.198  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:23:50.198  5860  5879 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 14:23:50.199  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 14:23:50.199  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:23:50.199  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 14:23:50.199  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:23:50.199  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:23:50.199  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:23:50.199  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:23:50.199  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:23:50.199  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46b2ea8 removed from the list
11-22 14:23:50.199  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.199  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ca3dc1 removed from the list
11-22 14:23:50.199  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:23:50.199  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-22 14:23:50.199  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:23:50.199  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.199  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-22 14:23:50.199  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-22 14:23:50.199  5662  5709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 14:23:50.200  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 14:23:50.200  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.201  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.201  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.201  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.201  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:23:50.201  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:23:50.201  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.201  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.201  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ca3dc1 not in the list
11-22 14:23:50.201  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.201  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.202  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 14:23:50.202  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 14:23:50.202  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.202  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 14:23:50.202  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 14:23:50.202  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.202  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.202  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.202  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 14:23:50.202  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.203  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:23:50.203  5860  5870 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 14:23:50.203  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 14:23:50.204  5662  5709 D BluetoothAdapter: STATE_ON
11-22 14:23:50.204  5860  5876 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 14:23:50.204  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.204  5860  5901 D BtGatt.GattService: stopScan() - queue size =1
11-22 14:23:50.204  5860  5879 D BtGatt.ScanManager: Starting BLE batch scan
11-22 14:23:50.204  5860  5879 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 14:23:50.205  5860  5899 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 14:23:50.205  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 14:23:50.205  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.205  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-22 14:23:50.205  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.205  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.205  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.205  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.205  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 14:23:50.205  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.205  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.206  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.206  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 14:23:50.206  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-22 14:23:50.206  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 14:23:50.207  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.207  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.208  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:23:50.208  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.208  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.208  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:23:50.208  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:23:50.208  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.208  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51784a7 removed from the list
11-22 14:23:50.208  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 14:23:50.208  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:23:50.208  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:23:50.208  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 14:23:50.208  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:23:50.208  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4334966 removed from the list
11-22 14:23:50.208  5662  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 14:23:50.208  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.208  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 14:23:50.208  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 14:23:50.208  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.208  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-22 14:23:50.208  5662  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.208  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 14:23:50.209  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.209  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:23:50.209  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.209  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9b2ac0 added. We now have 3 listener(s)
11-22 14:23:50.210  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 14:23:50.210  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:23:50.211  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:23:50.211  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:23:50.211  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-22 14:23:50.211  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-22 14:23:50.211  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@897e3f9 added. We now have 4 listener(s)
11-22 14:23:50.211  5662  5662 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 14:23:50.211  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:23:50.211  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 14:23:50.213  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 14:23:50.213  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb81f3e added. We now have 4 listener(s)
,11-22 14:23:50.214  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 14:23:50.214  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 14:23:50.214  5662  5709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 14:23:50.215  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 14:23:50.215  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ede619f added. We now have 5 listener(s)
11-22 14:23:50.215  5662  5709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 14:23:50.215  5662  5709 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 14:23:50.215  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 14:23:50.215  5662  5709 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 14:23:50.215  5860  5876 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 14:23:50.215  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:23:50.215  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.216  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 14:23:50.216  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:23:50.216  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9b2ac0 removed from the list
11-22 14:23:50.216  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.216  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@897e3f9 removed from the list
11-22 14:23:50.216  5662  5709 D io.jxcore.node.ConnectivityMonitor: stop
11-22 14:23:50.216  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.216  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.217  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.218  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.218  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.218  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:23:50.218  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:23:50.218  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.218  5662  5709 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@897e3f9 not in the list
11-22 14:23:50.218  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.218  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 14:23:50.219  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.220  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.220  5662  5709 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 14:23:50.220  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 14:23:50.220  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 14:23:50.220  5662  5709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 14:23:50.220  5662  5709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ede619f removed from the list
,11-22 14:23:50.220  5662  5709 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 14:23:50.220  5662  5709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 14:23:50.220  5662  5709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 14:23:50.220  5662  5709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb81f3e removed from the list
11-22 14:23:50.221  5860  5876 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 14:23:50.221  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:23:50.221  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-22 14:23:50.221  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-22 14:23:50.221  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-22 14:23:50.221  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:23:50.222  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-22 14:23:50.222  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-22 14:23:50.222  5860  5879 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 14:23:50.226  5860  5876 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 14:23:50.226  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.226  5860  5876 E BtGatt.ContextMap: Context not found for ID 5
,11-22 14:23:50.232  5860  5876 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 14:23:50.232  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.232  5860  5879 D BtGatt.ScanManager: stopping BLe Batch
,11-22 14:23:50.237  5860  5876 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 14:23:50.237  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 14:23:50.237  5860  5879 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 14:23:50.241  5860  5876 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 14:23:50.241  5860  5876 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 14:23:50.514  5915  5915 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-22 14:23:50.550  5915  5915 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
11-22 14:23:50.552  5915  5915 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-22 14:23:50.563   931  3036 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 14:23:50.564   931  3036 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 14:23:50.564   931  3038 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-22 14:23:50.579   931  3036 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 14:23:50.592   508   924 D CommandListener: Setting iface cfg
,11-22 14:23:50.598  5662  5662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 14:23:50.599   931  3036 D WifiStateMachine: Start Dhcp Watchdog 2
,11-22 14:23:50.604   931  5920 D DhcpClient: Receive thread started
,11-22 14:23:50.610   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:23:50.610   931  3036 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-22 14:23:50.610   931  3038 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-22 14:23:50.663  5662  5662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 14:23:50.690   931  3036 E native  : do suspend false
,11-22 14:23:50.707   931  5919 D DhcpClient: Broadcasting DHCPDISCOVER
,11-22 14:23:50.709  5662  5662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 14:23:50.723   931  5920 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172578, domain null
,11-22 14:23:50.724   931  5919 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172578 seconds
,11-22 14:23:50.726   931  5919 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-22 14:23:50.740   931  5920 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-22 14:23:50.740   931  5919 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-22 14:23:50.743   508   924 D CommandListener: Setting iface cfg
,11-22 14:23:50.748   931  3036 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-22 14:23:50.753   931  5919 D DhcpClient: Scheduling renewal in 86399s
,11-22 14:23:50.768   931  3036 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-22 14:23:50.770   931  3036 D WifiConfigStore: No blacklist allowed without epno enabled
,11-22 14:23:50.771   931  3038 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-22 14:23:50.774   931  3038 D ConnectivityService: Adding iface wlan0 to network 101
11-22 14:23:50.782   931  3036 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-22 14:23:50.817   931  3038 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-22 14:23:50.817   931  3038 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-22 14:23:50.819   931  3038 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-22 14:23:50.823   931  3038 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-22 14:23:50.828   931  3038 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-22 14:23:50.835   931  3038 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:23:50.839   931  3038 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-22 14:23:50.839   931  3038 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-22 14:23:50.839   931  3038 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-22 14:23:50.839   931  3038 D ConnectivityService:    accepting network in place of null
11-22 14:23:50.839   931  3036 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-22 14:23:50.839   931  3036 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 14:23:50.840   931  3038 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 14:23:50.847   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=264777, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:23:50.861   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 14:23:50.887   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 14:23:50.890   931  3038 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-22 14:23:50.890  3802  3934 W QCNEJ   : |CORE| network available: 101
11-22 14:23:50.890   931  3038 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 14:23:50.891   931  3038 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-22 14:23:50.893   931   948 D Tethering: MasterInitialState.processMessage what=3
,11-22 14:23:50.895  3802  3934 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-22 14:23:50.896  3802  3934 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-22 14:23:50.897  3802  3934 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-22 14:23:50.907  5090  5112 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-22 14:23:50.907  5090  5112 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 14:23:50.907  5090  5112 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-22 14:23:50.907  5090  5112 E SarControlService: no key has been found,reset the power
11-22 14:23:50.908  5090  5127 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 14:23:50.908  5090  5127 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 14:23:50.908  5090  5127 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 14:23:50.908  5115  5115 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 14:23:50.908  5115  5115 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-22 14:23:50.910  5090  5127 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-22 14:23:50.910  5090  5127 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 14:23:50.910  5090  5127 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 14:23:50.910  5115  5115 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 14:23:50.910  5115  5115 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 14:23:50.911  4006  4006 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-22 14:23:50.914  4022  4022 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-22 14:23:50.916  5115  5129 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e9f33a HexData = [00000000ec03000000000000ffffffff]
11-22 14:23:50.916  5115  5129 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 14:23:50.916  5115  5129 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-22 14:23:50.916  5115  5129 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e9f33a HexData = [00000000ed03000000000000ffffffff]
11-22 14:23:50.916  5115  5129 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 14:23:50.916  5115  5129 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-22 14:23:50.919  5115  5115 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 14:23:50.919  5090  5100 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-22 14:23:50.920  4022  4022 D SystemUpdateService: onCreate
,11-22 14:23:50.921  5115  5115 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 14:23:50.921  5090  5101 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-22 14:23:50.926   931  5917 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.46,2a00:1450:4001:81b::200e
,11-22 14:23:50.927  4022  4022 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 14:23:50.936  4022  4022 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-22 14:23:50.941  4022  5446 I iu.UploadsManager: num queued entries: 0
11-22 14:23:50.941  4022  5446 I iu.UploadsManager: num updated entries: 0
,11-22 14:23:50.942  4022  5446 I iu.SyncManager: NEXT; no task
,11-22 14:23:50.944  4022  5930 I SystemUpdateService: active receiver: enabled
,11-22 14:23:50.947  4022  4022 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-22 14:23:50.948  4022  4022 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 14:23:50.950  5767  5767 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 14:23:50.954  5767  5767 D SprintDMHelper: simOperator: 
11-22 14:23:50.954  5767  5767 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 14:23:50.978  4022  5930 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 14:23:50.982   931  5917 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Nov 2016 13:23:50 GMT], X-Android-Received-Millis=[1479821030981], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479821030956]}
,11-22 14:23:50.982   931  3038 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 14:23:50.982   931  3038 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-22 14:23:50.983   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-22 14:23:50.983   931  3038 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-22 14:23:50.990  4022  5930 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-22 14:23:50.990  4022  5930 I SystemUpdateService: now status is 0 (complete)
11-22 14:23:50.990  4022  5930 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 14:23:50.990  4022  5930 I SystemUpdateService: file has been verified
11-22 14:23:50.990  4022  5930 I SystemUpdateService: OTA package size = 21989297
,11-22 14:23:50.996  4022  5930 I SystemUpdateService: showing system update notification
,11-22 14:23:51.004   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 14:23:51.006  4022  4022 D SystemUpdateService: onDestroy
,11-22 14:23:51.057  5065  5935 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-22 14:23:51.892   931  3038 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-22 14:23:52.354  5662  5942 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 14:23:52.354  5662  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:23:53.164  5662  5942 W !!      : call onHalfStreamCopied
,11-22 14:23:53.164  5662  5942 I testCopyDataAndClose: closing input stream
,11-22 14:23:53.632   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:23:53.931  5662  5942 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 14:23:53.931  5662  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:23:53.932  5662  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 14:23:53.932  5662  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 14:23:53.932  5662  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 14:23:53.932  5662  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 14:23:53.932  5662  5942 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 14:23:53.932  5662  5942 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-22 14:23:53.932  5662  5942 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 14:23:53.932  5662  5942 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 14:23:53.932  5662  5942 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 14:23:56.661   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:23:58.371  5662  5943 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:23:58.371  5662  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:23:58.841   931  3038 D ConnectivityService: handlePromptUnvalidated 101
,11-22 14:23:59.681   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:24:00.371  5662  5709 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-22 14:24:00.371  5662  5709 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:24:00.372  5662  5709 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-22 14:24:00.430  5662  5943 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-22 14:24:00.430  5662  5943 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:24:00.430  5662  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-22 14:24:00.470  5662  5944 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 14:24:00.470  5662  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:24:00.903   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:24:01.903   931  3036 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,11-22 14:24:01.904   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:24:02.142  5662  5944 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 14:24:02.142  5662  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:24:02.142  5662  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 14:24:02.142  5662  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 14:24:02.142  5662  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-22 14:24:02.142  5662  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 14:24:02.142  5662  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 14:24:02.142  5662  5944 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 14:24:02.142  5662  5944 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-22 14:24:02.142  5662  5944 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 14:24:02.142  5662  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 14:24:02.713   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:24:02.905   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:24:03.907   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:24:04.908   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:24:05.909   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 14:24:06.377  5662  5945 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:24:06.377  5662  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 14:24:06.378  5662  5945 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:24:06.378  5662  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:24:06.378  5662  5945 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 14:24:06.378  5662  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 14:24:06.378  5662  5945 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 14:24:06.378  5662  5945 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 14:24:06.378  5662  5945 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 14:24:06.378  5662  5945 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 14:24:06.378  5662  5945 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 14:24:06.379  5662  5945 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:24:06.379  5662  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-22 14:24:06.380  5662  5709 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-22 14:24:06.383  5662  5946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:24:06.383  5662  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 14:24:06.384  5662  5946 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
,11-22 14:24:06.384  5662  5946 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:24:06.384  5662  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-22 14:24:06.384  5662  5946 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-22 14:24:06.385  5662  5946 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 14:24:06.385  5662  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-22 14:24:06.389  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-22 14:24:06.389  5662  5709 I jxcore-log: 
11-22 14:24:06.390  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-22 14:24:06.390  5662  5709 I jxcore-log: 
11-22 14:24:06.390  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-22 14:24:06.390  5662  5709 I jxcore-log: 
11-22 14:24:06.390  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-22 14:24:06.390  5662  5709 I jxcore-log: 
11-22 14:24:06.391  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG UnitTest_app: 'Total duration:  91961'
11-22 14:24:06.391  5662  5709 I jxcore-log: 
11-22 14:24:06.393  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-22 14:24:06.393  5662  5709 I jxcore-log: 
,11-22 14:24:06.398  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 14:24:06.398  5662  5709 I jxcore-log: 
11-22 14:24:06.399  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 14:24:06.399  5662  5709 I jxcore-log: 
11-22 14:24:06.400  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 14:24:06.400  5662  5709 I jxcore-log: 
11-22 14:24:06.400  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 14:24:06.400  5662  5709 I jxcore-log: 
11-22 14:24:06.400  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:24:06.400  5662  5709 I jxcore-log: 
11-22 14:24:06.400  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 14:24:06.400  5662  5709 I jxcore-log: 
11-22 14:24:06.401  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:24:06.401  5662  5709 I jxcore-log: 
11-22 14:24:06.401  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 14:24:06.401  5662  5709 I jxcore-log: 
,11-22 14:24:06.401  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 14:24:06.401  5662  5709 I jxcore-log: 
11-22 14:24:06.402  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 14:24:06.402  5662  5709 I jxcore-log: 
11-22 14:24:06.402  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 14:24:06.402  5662  5709 I jxcore-log: 
11-22 14:24:06.402  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:24:06.402  5662  5709 I jxcore-log: 
11-22 14:24:06.402  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 14:24:06.402  5662  5709 I jxcore-log: 
11-22 14:24:06.403  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:24:06.403  5662  5709 I jxcore-log: 
11-22 14:24:06.403  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 14:24:06.403  5662  5709 I jxcore-log: 
11-22 14:24:06.403  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:24:06.403  5662  5709 I jxcore-log: 
11-22 14:24:06.403  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 14:24:06.403  5662  5709 I jxcore-log: 
,11-22 14:24:06.403  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 14:24:06.403  5662  5709 I jxcore-log: 
11-22 14:24:06.404  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 14:24:06.404  5662  5709 I jxcore-log: 
11-22 14:24:06.404  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 14:24:06.404  5662  5709 I jxcore-log: 
11-22 14:24:06.404  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 14:24:06.404  5662  5709 I jxcore-log: 
11-22 14:24:06.405  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 14:24:06.405  5662  5709 I jxcore-log: 
,11-22 14:24:06.405  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 14:24:06.405  5662  5709 I jxcore-log: 
11-22 14:24:06.405  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 14:24:06.405  5662  5709 I jxcore-log: 
11-22 14:24:06.407  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-22 14:24:06.407  5662  5709 I jxcore-log: 
11-22 14:24:06.407  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 14:24:06.407  5662  5709 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-22 14:24:06.407  5662  5709 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 14:24:06.407  5662  5709 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,11-22 14:24:06.407  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 14:24:06.407  5662  5709 I jxcore-log: 
11-22 14:24:06.407  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:24:06.407  5662  5709 I jxcore-log: 
11-22 14:24:06.408  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 14:24:06.408  5662  5709 I jxcore-log: 
11-22 14:24:06.408  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:24:06.408  5662  5709 I jxcore-log: 
,11-22 14:24:06.408  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 14:24:06.408  5662  5709 I jxcore-log: 
11-22 14:24:06.408  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 14:24:06.408  5662  5709 I jxcore-log: 
11-22 14:24:06.414  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-22 14:24:06.414  5662  5709 I jxcore-log: 
,11-22 14:24:06.414  5662  5709 I jxcore-log: 2016-11-22 13:24:06 - WARN testUtils: 'myNameCallback not set!'
11-22 14:24:06.414  5662  5709 I jxcore-log: 
,11-22 14:24:06.422  5662  5662 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-22 14:24:08.526  5662  5709 I jxcore-log: 2016-11-22 13:24:08 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-22 14:24:08.526  5662  5709 I jxcore-log: 
,11-22 14:24:08.527  5662  5709 I jxcore-log: 2016-11-22 13:24:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-22 14:24:08.527  5662  5709 I jxcore-log: 
,11-22 14:24:08.886  5662  5709 I jxcore-log: 2016-11-22 13:24:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-22 14:24:08.886  5662  5709 I jxcore-log: 
,11-22 14:24:08.897  5662  5709 I jxcore-log: 2016-11-22 13:24:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-22 14:24:08.897  5662  5709 I jxcore-log: 
,11-22 14:24:09.980   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=283910, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:24:10.042  5662  5709 I jxcore-log: 2016-11-22 13:24:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-22 14:24:10.042  5662  5709 I jxcore-log: 
,11-22 14:24:10.241  5662  5709 I jxcore-log: 2016-11-22 13:24:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-22 14:24:10.241  5662  5709 I jxcore-log: 
,11-22 14:24:10.246  5662  5709 I jxcore-log: 2016-11-22 13:24:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-22 14:24:10.246  5662  5709 I jxcore-log: 
,11-22 14:24:10.251  5662  5709 I jxcore-log: 2016-11-22 13:24:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-22 14:24:10.251  5662  5709 I jxcore-log: 
,11-22 14:24:10.744  5662  5709 I jxcore-log: 2016-11-22 13:24:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-22 14:24:10.744  5662  5709 I jxcore-log: 
,11-22 14:24:10.790  5662  5709 I jxcore-log: 2016-11-22 13:24:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-22 14:24:10.790  5662  5709 I jxcore-log: 
,11-22 14:24:10.804  5662  5709 I jxcore-log: 2016-11-22 13:24:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-22 14:24:10.804  5662  5709 I jxcore-log: 
,11-22 14:24:10.808  5662  5709 I jxcore-log: 2016-11-22 13:24:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-22 14:24:10.808  5662  5709 I jxcore-log: 
,11-22 14:24:11.083  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-22 14:24:11.083  5662  5709 I jxcore-log: 
,11-22 14:24:11.215  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-22 14:24:11.215  5662  5709 I jxcore-log: 
,11-22 14:24:11.593  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-22 14:24:11.593  5662  5709 I jxcore-log: 
,11-22 14:24:11.601  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-22 14:24:11.601  5662  5709 I jxcore-log: 
,11-22 14:24:11.605  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-22 14:24:11.605  5662  5709 I jxcore-log: 
,11-22 14:24:11.611  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-22 14:24:11.611  5662  5709 I jxcore-log: 
,11-22 14:24:11.616  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-22 14:24:11.616  5662  5709 I jxcore-log: 
,11-22 14:24:11.644  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-22 14:24:11.644  5662  5709 I jxcore-log: 
,11-22 14:24:11.680  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-22 14:24:11.680  5662  5709 I jxcore-log: 
,11-22 14:24:11.687  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-22 14:24:11.687  5662  5709 I jxcore-log: 
,11-22 14:24:11.693  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-22 14:24:11.693  5662  5709 I jxcore-log: 
,11-22 14:24:11.709  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-22 14:24:11.709  5662  5709 I jxcore-log: 
,11-22 14:24:11.725  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-22 14:24:11.725  5662  5709 I jxcore-log: 
,11-22 14:24:11.731  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-22 14:24:11.731  5662  5709 I jxcore-log: 
,11-22 14:24:11.736  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-22 14:24:11.736  5662  5709 I jxcore-log: 
,11-22 14:24:11.750  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-22 14:24:11.750  5662  5709 I jxcore-log: 
,11-22 14:24:11.767  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-22 14:24:11.767  5662  5709 I jxcore-log: 
,11-22 14:24:11.782  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-22 14:24:11.782  5662  5709 I jxcore-log: 
,11-22 14:24:11.792  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-22 14:24:11.792  5662  5709 I jxcore-log: 
,11-22 14:24:11.805  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-22 14:24:11.805  5662  5709 I jxcore-log: 
,11-22 14:24:11.815  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-22 14:24:11.815  5662  5709 I jxcore-log: 
,11-22 14:24:11.829  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-22 14:24:11.829  5662  5709 I jxcore-log: 
,11-22 14:24:11.838  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-22 14:24:11.838  5662  5709 I jxcore-log: 
,11-22 14:24:11.845  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-22 14:24:11.845  5662  5709 I jxcore-log: 
,11-22 14:24:11.867  5662  5709 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-22 14:24:11.868  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO testUtils: 'BLE multiple advertisement supported'
11-22 14:24:11.868  5662  5709 I jxcore-log: 
,11-22 14:24:11.902  5662  5709 I jxcore-log: 2016-11-22 13:24:11 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-22 14:24:11.902  5662  5709 I jxcore-log: 
,11-22 14:24:12.170  5662  5709 I jxcore-log: 2016-11-22 13:24:12 - DEBUG CoordinatedClient: 'connected to the test server'
11-22 14:24:12.170  5662  5709 I jxcore-log: 
,11-22 14:24:16.933   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=290863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:24:20.846   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:24:23.880   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:24:25.910   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:24:26.911   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:24:27.912   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:24:28.913   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:24:29.914   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:24:30.706   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=304637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:24:30.821   931  3036 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:24:30.915   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 14:24:36.001   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:24:39.032   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:24:42.173   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=316104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:24:55.800   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=329730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:24:55.916   543   543 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 14:24:55.917   543   543 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 14:25:06.254   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:25:07.214   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=341144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:25:10.828   931  3036 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:25:10.918   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:11.920   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:12.320   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:25:12.921   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:13.923   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:14.924   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:15.925   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 14:25:20.840   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=354770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:25:20.926   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:21.928   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:22.929   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:23.931   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:24.433   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:25:24.932   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:25.933   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 14:25:27.454   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:25:30.829   931  3036 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:25:32.241   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=366171, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:25:35.935   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:36.937   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:37.938   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:38.939   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:39.941   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:40.942   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 14:25:45.624   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:25:46.440   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=380370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:25:51.672   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:25:54.698   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:25:55.943   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:56.944   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:57.732   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:25:57.827   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=391757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:25:57.946   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:58.947   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:25:59.949   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:26:00.763   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:26:00.950   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 14:26:06.822   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:26:10.834   931  3036 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:26:11.560   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=405490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:26:18.943   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:26:20.951   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:26:21.952   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:26:21.971   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:26:22.954   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:26:22.960   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=416890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:26:23.955   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:26:24.957   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:26:25.004   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:26:25.957   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 14:26:28.032   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:26:30.835   931  3036 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:26:34.083   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:26:36.573   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=430503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:26:40.138   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:26:47.987   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=441917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:26:49.212   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:26:50.839   931  3036 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 14:26:50.958   543   543 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 14:26:50.959   543   543 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 14:26:55.266   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:27:01.640   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=455570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 14:27:07.394   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:27:10.433   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:27:10.959   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:27:11.961   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:27:12.962   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:27:13.053   931  5918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=466984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 14:27:13.963   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:27:14.965   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:27:15.965   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 14:27:20.966   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:27:21.968   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:27:22.542   931  3038 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 14:27:22.969   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:27:23.861  5662  5709 I jxcore-log: 2016-11-22 13:27:23 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-22 14:27:23.861  5662  5709 I jxcore-log: 
,11-22 14:27:23.970   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:27:24.028  5662  5709 I jxcore-log: 2016-11-22 13:27:24 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 14:27:24.028  5662  5709 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 14:27:24.028  5662  5709 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 14:27:24.028  5662  5709 I jxcore-log: emit@events.js:82:1
11-22 14:27:24.028  5662  5709 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 14:27:24.028  5662  5709 I jxcore-log: emit@events.js:82:1''
11-22 14:27:24.028  5662  5709 I jxcore-log: 
,11-22 14:27:24.030  5662  5709 I jxcore-log: 2016-11-22 13:27:24 - DEBUG CoordinatedClient: 'test client failed'
11-22 14:27:24.030  5662  5709 I jxcore-log: 
,11-22 14:27:24.040  5662  5709 I jxcore-log: 2016-11-22 13:27:24 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 14:27:24.040  5662  5709 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 14:27:24.040  5662  5709 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 14:27:24.040  5662  5709 I jxcore-log: emit@events.js:82:1
11-22 14:27:24.040  5662  5709 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 14:27:24.040  5662  5709 I jxcore-log: emit@events.js:82:1''
11-22 14:27:24.040  5662  5709 I jxcore-log: 
,11-22 14:27:24.041  5662  5709 I jxcore-log: 2016-11-22 13:27:24 - DEBUG CoordinatedClient: 'test client failed'
11-22 14:27:24.041  5662  5709 I jxcore-log: 
,11-22 14:27:24.045  5662  5709 I jxcore-log: 2016-11-22 13:27:24 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 14:27:24.045  5662  5709 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 14:27:24.045  5662  5709 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 14:27:24.045  5662  5709 I jxcore-log: emit@events.js:82:1
11-22 14:27:24.045  5662  5709 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 14:27:24.045  5662  5709 I jxcore-log: emit@events.js:82:1''
11-22 14:27:24.045  5662  5709 I jxcore-log: 
,11-22 14:27:24.046  5662  5709 I jxcore-log: 2016-11-22 13:27:24 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-22 14:27:24.046  5662  5709 I jxcore-log: 
,11-22 14:27:24.511  5958  5958 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-22 14:27:24.517  5958  5958 D AndroidRuntime: CheckJNI is OFF
,11-22 14:27:24.550  5958  5958 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-22 14:27:24.587  5958  5958 I Radio-JNI: register_android_hardware_Radio DONE
,11-22 14:27:24.603  5958  5958 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-22 14:27:24.611   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-22 14:27:24.612   931   944 I ActivityManager: Killing 5662:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-22 14:27:24.715   931  3477 I WindowState: WIN DEATH: Window{367cf1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-22 14:27:24.715   931  3216 D GraphicsStats: Buffer count: 2
11-22 14:27:24.715   931  3037 D WifiService: Client connection lost with reason: 4
,11-22 14:27:24.730   931   944 W ActivityManager: Force removing ActivityRecord{b5c9740 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-22 14:27:24.759   931   954 I art     : Starting a blocking GC Explicit
,11-22 14:27:24.767   931  3476 W ActivityManager: Spurious death for ProcessRecord{77ae9cf 0:com.test.thalitest/u0a77}, curProc for 5662: null
,11-22 14:27:24.796  3755  3755 W Binder_7: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28365]" dev="sockfs" ino=28365 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 14:27:24.799  3755  3755 W Binder_7: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[28365]" dev="sockfs" ino=28365 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 14:27:24.802   931  3755 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5662 uid 10077
11-22 14:27:24.803  3718  3718 I Keyboard.Facilitator: onFinishInput()
,11-22 14:27:24.868   931   954 I art     : Explicit concurrent mark sweep GC freed 109208(7MB) AllocSpace objects, 59(1740KB) LOS objects, 33% free, 29MB/43MB, paused 1.979ms total 107.625ms
,11-22 14:27:24.875  4006  5973 I MicroRecognitionRnrImpl: Starting detection.
,11-22 14:27:24.879  4006  5974 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@bc23ace
,11-22 14:27:24.880   513  5976 I AudioFlinger: AudioFlinger's thread 0xf1e00000 ready to run
,11-22 14:27:24.883   513  3058 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-22 14:27:24.884  4006  5974 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@bc23ace
,11-22 14:27:24.891   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-22 14:27:24.893  5958  5958 I art     : System.exit called, status: 0
11-22 14:27:24.893  5958  5958 I AndroidRuntime: VM exiting with result code 0.
,11-22 14:27:24.895   513  5976 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-22 14:27:24.895   513  5976 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-22 14:27:24.895   513  5976 I ACDB-LOADER: ACDB AFE returned = -19
11-22 14:27:24.895   513  5976 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-22 14:27:24.895   513  5976 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-22 14:27:24.895   513  5976 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-22 14:27:24.898   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-22 14:27:24.905   513  5976 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-22 14:27:24.912  5860  5860 D BluetoothMapAppObserver: onReceive
,11-22 14:27:24.912  5860  5860 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-22 14:27:24.914  4156  4246 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-22 14:27:24.916  3718  3718 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-22 14:27:24.920   931  3002 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-22 14:27:24.935  3718  5980 I Keyboard.Facilitator.DecoderInitializer: run()
11-22 14:27:24.937  3461  5981 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-22 14:27:24.945  3718  5980 I Decoder : createOrResetDecoder
,11-22 14:27:24.965  3842  3842 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-22 14:27:24.973   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 14:27:24.981  3637  3637 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-22 14:27:24.981  3637  3637 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
11-22 14:27:24.987   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-22 14:27:24.986    21    21 W kworker/3:0: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 14:27:24.994  4006  4006 I HotwordWorkerImpl: onReady
,11-22 14:27:24.993    21    21 W kworker/3:0: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 14:27:25.004  3637  3637 I ConfigService: onCreate
,11-22 14:27:25.006  4022  5988 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-22 14:27:25.006  4022  5988 D AccountUtils: Clearing selected account for com.test.thalitest
,11-22 14:27:25.013    21    21 W kworker/3:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-22 14:27:25.021  4022  5988 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
11-22 14:27:25.029  4022  4022 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-22 14:27:25.029  4022  4022 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-22 14:27:25.037  3718  5980 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-22 14:27:25.038  4022  5988 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.,openInner(SQLiteDatabase.java:806)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-22 14:27:25.038  4022  5988 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-22 14:27:25.043  4022  5994, E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-22 14:27:25.043  4022  5994 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-22 14:27:25.044  4022  5994 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 14:27:25.046  4022  4022 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-22 14:27:25.046  4022  4022 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-22 14:27:25.046  4022  5994 W SQLiteOpenHelper: Opened metrics.db in read-only mode
11-22 14:27:25.046  4022  5994 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
11-22 14:27:25.046  4022  5994 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
11-22 14:27:25.047  3461  5981 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-22 14:27:25.047  4022  5994 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-22 14:27:25.047  4022  5994 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-22 14:27:25.048  4006  5997 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
--------- beginning of crash
11-22 14:27:25.048  3461  5981 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-22 14:27:25.048  3461  5981 E AndroidRuntime: Process: android.process.acore, PID: 3461
11-22 14:27:25.048  3461  5981 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 14:27:25.048  3461  5981 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 14:27:25.056  4022  5994 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-22 14:27:25.056  4022  5994 E AndroidRuntime: Process: com.google.android.gms, PID: 4022
11-22 14:27:25.056  4022  5994 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-22 14:27:25.056  4022  5994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 14:27:25.056  4022  5994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 14:27:25.056  4022  5994 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 14:27:25.056  4022  5994 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 14:27:25.056  4022  5994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 14:27:25.056  4022  5994 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
11-22 14:27:25.056  4022  5994 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-22 14:27:25.056  4022  5994 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 14:27:25.056  4022  5994 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 14:27:25.056  4022  5994 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 14:27:25.056  4022  5994 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 14:27:25.071   931  6000 E DropBoxManagerService: Can't write: system_app_crash
11-22 14:27:25.071   931  6000 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
11-22 14:27:25.071   931  6000 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 14:27:25.071   931  6000 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 14:27:25.071   931  6000 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 14:27:25.071   931  6000 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 14:27:25.071   931  6000 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 14:27:25.071   931  6000 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 14:27:25.071   931  6000 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 14:27:25.071   931  6000 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 14:27:25.071   931  6000 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 14:27:25.071   931  6000 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 14:27:25.071   931  6000 E DropBoxManagerService: 	... 5 more
11-22 14:27:25.073  3863  4516 E ReflectionEngine: Failed to save models
11-22 14:27:25.073  3863  4516 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 14:27:25.073  3863  4516 E ReflectionEngine: 	... 16 more
11-22 14:27:25.074   931  6001 E DropBoxManagerService: Can't write: system_app_crash
11-22 14:27:25.074   931  6001 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
11-22 14:27:25.074   931  6001 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 14:27:25.074   931  6001 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 14:27:25.074   931  6001 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 14:27:25.074   931  6001 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 14:27:25.074   931  6001 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 14:27:25.074   931  6001 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 14:27:25.074   931  6001 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 14:27:25.074   931  6001 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 14:27:25.074   931  6001 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 14:27:25.074   931  6001 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 14:27:25.074   931  6001 E DropBoxManagerService: 	... 5 more
11-22 14:27:25.077  4006  5997 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-22 14:27:25.089   414   414 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34999]" dev="sockfs" ino=34999 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 14:27:25.089   414   414 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34999]" dev="sockfs" ino=34999 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 14:27:25.096   762   762 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33911]" dev="sockfs" ino=33911 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 14:27:25.096   762   762 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33911]" dev="sockfs" ino=33911 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 14:27:25.100   931  6003 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-22 14:27:25.100  3718  5980 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-22 14:27:25.103  3718  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-22 14:27:25.103  3718  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-22 14:27:25.105  3718  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-22 14:27:25.105  3718  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-22 14:27:25.106  3718  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-22 14:27:25.106  3718  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-22 14:27:25.106  3718  5980 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-22 14:27:25.107  3718  5980 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-22 14:27:25.107  3718  5980 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-22 14:27:25.107  3718  5980 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-22 14:27:25.107  3718  5980 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-22 14:27:25.107  3718  5980 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-22 14:27:25.114   931  3755 I ActivityManager: Start proc 6004:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,11-22 14:27:25.138   931  3477 I ActivityManager: Start proc 6009:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-22 14:27:25.147  4022  5996 W BaseAppContext: Using Auth Proxy for data requests.
,11-22 14:27:25.150  4022  5996 W BaseAppContext: Using Auth Proxy for data requests.
,11-22 14:27:25.159   931   944 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{14bd14f u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{79d0029 4022 com.google.android.gms/10012/u0 remote:82f59b0}: process crashing
,11-22 14:27:25.165   931  4995 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/4022 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-22 14:27:25.221  4022  5993 W DriveInitializer: Awaiting to be initialized
,11-22 14:27:25.221  4022  6016 W DriveInitializer: Background init thread started
,11-22 14:27:25.400   384   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
