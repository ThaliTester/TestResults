#### Test 95813110567bbc2_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
,11-30 22:39:42.547   930  2936 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
11-30 22:39:43.006  5590  5590 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-30 22:39:43.012  5590  5590 D AndroidRuntime: CheckJNI is OFF
11-30 22:39:43.044  5590  5590 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-30 22:39:43.081  5590  5590 I Radio-JNI: register_android_hardware_Radio DONE
11-30 22:39:43.096  5590  5590 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-30 22:39:43.100   930  3401 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-30 22:39:43.116  5590  5590 D AndroidRuntime: Shutting down VM
11-30 22:39:43.131  3948  3960 W SearchService: Abort, client detached.
11-30 22:39:43.139  3948  3948 I HotwordDetector: Closing mic
11-30 22:39:43.139  3948  4189 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@68ef8df
11-30 22:39:43.140  3948  4210 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-30 22:39:43.153   930  3805 I ActivityManager: Start proc 5601:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-30 22:39:43.200   514  4212 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-30 22:39:43.201   514  4212 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-30 22:39:43.204   514  4212 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-30 22:39:43.204   514  4212 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-30 22:39:43.205   514  2984 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-30 22:39:43.206  3948  4207 I MicroRecognitionRnrImpl: Detection finished
11-30 22:39:43.206  3948  4197 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-30 22:39:43.244  5601  5601 I CordovaLog: Changing log level to DEBUG(3)
11-30 22:39:43.244  5601  5601 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-30 22:39:43.244  5601  5601 D CordovaActivity: CordovaActivity.onCreate()
11-30 22:39:43.251  5601  5601 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-30 22:39:43.277  5601  5601 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-30 22:39:43.346  5601  5601 I LibraryLoader: Time to load native libraries: 65 ms (timestamps 2121-2186)
11-30 22:39:43.346  5601  5601 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-30 22:39:43.380  5601  5601 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9001493}
,11-30 22:39:43.381  5601  5601 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-30 22:39:43.381  5601  5601 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-30 22:39:43.386  5601  5601 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-30 22:39:43.387  5601  5601 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-30 22:39:43.429  5601  5601 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-30 22:39:43.443  5601  5601 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-30 22:39:43.443  5601  5601 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-30 22:39:43.443  5601  5601 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-30 22:39:43.443  5601  5601 I Adreno  : Build Date                       : 12/06/15
11-30 22:39:43.443  5601  5601 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-30 22:39:43.443  5601  5601 I Adreno  : Local Branch                     : mybranch17112971
11-30 22:39:43.443  5601  5601 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-30 22:39:43.443  5601  5601 I Adreno  : Remote Branch                    : NONE
11-30 22:39:43.443  5601  5601 I Adreno  : Reconstruct Branch               : NOTHING
,11-30 22:39:43.486   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a83c579:true
,11-30 22:39:43.518  2928  2928 W Binder_5: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[22481]" dev="sockfs" ino=22481 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 22:39:43.518  2928  2928 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22481]" dev="sockfs" ino=22481 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 22:39:43.530  5601  5601 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-30 22:39:43.539  5601  5601 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-30 22:39:43.543  5601  5601 D PluginManager: init()
,11-30 22:39:43.546  5601  5601 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-30 22:39:43.561  5601  5601 D CordovaActivity: Started the activity.
,11-30 22:39:43.561  5601  5601 D CordovaActivity: Resumed the activity.
,11-30 22:39:43.561  2927  2927 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31375]" dev="sockfs" ino=31375 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 22:39:43.565  5601  5638 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-30 22:39:43.561  2927  2927 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31375]" dev="sockfs" ino=31375 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 22:39:43.564  3137  3137 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[22493]" dev="sockfs" ino=22493 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 22:39:43.569  5601  5625 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
11-30 22:39:43.564  3137  3137 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22493]" dev="sockfs" ino=22493 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 22:39:43.597  5601  5638 I OpenGLRenderer: Initialized EGL, version 1.4
,11-30 22:39:43.664  3805  3805 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33803]" dev="sockfs" ino=33803 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 22:39:43.669   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +536ms
,11-30 22:39:43.671  3649  3649 I Keyboard.Facilitator: onFinishInput()
,11-30 22:39:43.668  3805  3805 W Binder_8: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33803]" dev="sockfs" ino=33803 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-30 22:39:43.668  3137  3137 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33802]" dev="sockfs" ino=33802 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-30 22:39:43.668  3137  3137 W Binder_3: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33802]" dev="sockfs" ino=33802 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 22:39:43.683  5601  5601 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-30 22:39:43.698  5601  5601 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5601
,11-30 22:39:43.790  5601  5601 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-30 22:39:43.938   930  3805 I ActivityManager: Killing 5266:com.android.settings/1000 (adj 15): empty #17
,11-30 22:39:43.951  5601  5641 D jxcore_app_log: JniHelper::setJavaVM(0xf513c000), pthread_self() = -591918800
,11-30 22:39:43.956  5601  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-30 22:39:43.956  5601  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-30 22:39:43.956  5601  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-30 22:39:43.956  5601  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-30 22:39:43.956  5601  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-30 22:39:43.956  5601  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45189c1 added. We now have 1 listener(s)
,11-30 22:39:43.959  5601  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-30 22:39:43.959  5601  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-30 22:39:43.959   930  3805 I ActivityManager: Killing 5227:org.codeaurora.ims/1001 (adj 15): empty #18
11-30 22:39:43.960  5601  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-30 22:39:43.960  5601  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-30 22:39:43.962  5601  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9114954 added. We now have 1 listener(s)
11-30 22:39:43.963  5601  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-30 22:39:43.968   930  2947 D WifiService: New client listening to asynchronous messages
,11-30 22:39:43.969  5601  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-30 22:39:43.969  5601  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-30 22:39:43.969  5601  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-30 22:39:43.969  5601  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-30 22:39:43.969  5601  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-30 22:39:43.969  5601  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-30 22:39:43.969  5601  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-30 22:39:43.971  5601  5641 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-30 22:39:43.981  5601  5601 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-30 22:39:43.990  5601  5601 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
11-30 22:39:43.990  5601  5601 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-30 22:39:44.397  5601  5648 W jxcore-log: Initializing JXcore engine
,11-30 22:39:44.397  5601  5648 W jxcore-log: JXcore engine is ready
,11-30 22:39:44.424  5648  5648 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11979 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-30 22:39:44.424  5648  5648 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[16479]" dev="sockfs" ino=16479 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-30 22:39:44.424  5648  5648 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-30 22:39:44.424  5648  5648 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29679]" dev="sockfs" ino=29679 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-30 22:39:44.436  5601  5648 W jxcore-log: Starting JXcore engine
,11-30 22:39:44.492  5601  5648 W jxcore-log: Platform android
11-30 22:39:44.492  5601  5648 W jxcore-log: 
,11-30 22:39:44.492  5601  5648 W jxcore-log: Process ARCH arm
11-30 22:39:44.492  5601  5648 W jxcore-log: 
,11-30 22:39:44.640  5601  5648 I jxcore-log: JXcore Cordova bridge is ready!
11-30 22:39:44.640  5601  5648 I jxcore-log: 
,11-30 22:39:44.641  5601  5648 W jxcore-log: JXcore engine is started
11-30 22:39:44.647  5601  5641 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
11-30 22:39:44.653  5601  5601 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
11-30 22:39:44.653  5601  5601 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-30 22:39:44.861   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-30 22:39:50.624   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:39:50.909   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-30 22:39:51.625   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:39:52.626   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:39:52.787   930  5357 D NetlinkSocketObserver: NeighborEvent{elapsedMs=191627, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-30 22:39:53.238  3948  5649 W CronetSyncConnectionRcs: Upload content type not set.
,11-30 22:39:53.627   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:39:54.577  5601  5648 I jxcore-log: 2016-11-30 21:39:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-30 22:39:54.577  5601  5648 I jxcore-log: 
,11-30 22:39:54.579  5601  5648 I jxcore-log: 2016-11-30 21:39:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-30 22:39:54.579  5601  5648 I jxcore-log: 
,11-30 22:39:54.585  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-30 22:39:54.586  5601  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-30 22:39:54.586  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 22:39:54.586  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 22:39:54.586  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 22:39:54.586  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 22:39:54.586  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 22:39:54.586  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 22:39:54.586  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 22:39:54.586  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-30 22:39:54.587  5601  5648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 22:39:54.592  5601  5648 I jxcore-log: 2016-11-30 21:39:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-30 22:39:54.592  5601  5648 I jxcore-log: 
,11-30 22:39:54.593  5601  5648 I jxcore-log: 2016-11-30 21:39:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-30 22:39:54.593  5601  5648 I jxcore-log: 
,11-30 22:39:54.628   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:39:54.848  5601  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-30 22:39:54.848  5601  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25893e added. We now have 2 listener(s)
11-30 22:39:54.848  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 22:39:54.849  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 22:39:54.849  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 22:39:54.849  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-30 22:39:54.849  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c0839f added. We now have 2 listener(s)
11-30 22:39:54.849  5601  5648 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-30 22:39:54.850  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-30 22:39:54.851  5601  5648 D ExecuteNativeTests: Running unit tests
,11-30 22:39:54.851  5601  5648 D BluetoothAdapter: enable(): BT is already enabled..!
11-30 22:39:54.852   930  3401 D WifiService: setWifiEnabled: true pid=5601, uid=10077
11-30 22:39:54.852   930  3401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 22:39:55.629   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-30 22:39:58.267   930  5357 D NetlinkSocketObserver: NeighborEvent{elapsedMs=197107, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-30 22:39:59.995   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-30 22:40:02.550   930  2936 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 22:40:04.857  5601  5648 I com.test.thalitest.ThaliTestRunner: Running UT
,11-30 22:40:04.927  5601  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-30 22:40:04.927  5601  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28ca4d9 added. We now have 3 listener(s)
,11-30 22:40:04.928  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 22:40:04.928  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-30 22:40:04.928  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 22:40:04.929  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-30 22:40:04.929  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f27e9e added. We now have 3 listener(s)
,11-30 22:40:04.929  5601  5648 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-30 22:40:04.930  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-30 22:40:04.937  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-30 22:40:04.938  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-30 22:40:04.938  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 22:40:04.938  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 22:40:04.938  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-30 22:40:04.939  5601  5648 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-30 22:40:04.939  5601  5648 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-30 22:40:04.939  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-30 22:40:04.940  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 22:40:04.940  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 22:40:04.940  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 22:40:04.940  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-30 22:40:04.941  5601  5648 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-30 22:40:04.943  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-30 22:40:04.945  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-30 22:40:04.945  5601  5648 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 22:40:04.947  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-30 22:40:04.947  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-30 22:40:04.956  5601  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-30 22:40:04.956  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 22:40:04.956  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 22:40:04.956  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 22:40:04.956  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 22:40:04.956  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 22:40:04.956  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 22:40:04.956  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 22:40:04.956  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-30 22:40:04.957  5601  5648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 22:40:04.957  5601  5648 D io.jxcore.node.ConnectivityMonitor: start: OK
11-30 22:40:04.957  5601  5648 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-30 22:40:04.957  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,11-30 22:40:04.957  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:04.957  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:04.957  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:04.958  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 22:40:04.958  5601  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 22:40:04.958  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 22:40:04.958  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 22:40:04.958  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 22:40:04.959  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 22:40:04.959  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 22:40:04.959  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 22:40:04.960  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 22:40:04.960  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 22:40:04.960  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 22:40:04.960  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 22:40:04.960  5601  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 22:40:04.962  5601  5654 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 22:40:04.963  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-30 22:40:04.964  5601  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 22:40:04.965  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 22:40:04.965  5601  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 22:40:04.965  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-30 22:40:04.968  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:04.968  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 22:40:04.961  4854  4854 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[22512]" dev="sockfs" ino=22512 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 22:40:04.969  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-30 22:40:04.969  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 22:40:04.961  4854  4854 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[22512]" dev="sockfs" ino=22512 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 22:40:04.970  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 22:40:04.970  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 22:40:04.970  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
,11-30 22:40:04.971  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:04.972  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:04.972  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 22:40:04.972  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 22:40:04.972  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 22:40:04.972  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
,11-30 22:40:04.973  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:04.973  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:04.973  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:04.973  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 22:40:04.973  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:04.973  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:04.973  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:04.973  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:04.974  5601  5648 D BluetoothAdapter: STATE_ON
,11-30 22:40:04.977  4634  4854 D BtGatt.GattService: registerClient() - UUID=d54f5521-9ee8-4775-be90-3ba13e7161e1
,11-30 22:40:04.977  4634  4696 D BtGatt.GattService: onClientRegistered() - UUID=d54f5521-9ee8-4775-be90-3ba13e7161e1, clientIf=5
11-30 22:40:04.978  5601  5611 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-30 22:40:04.980  4634  4700 D BtGatt.AdvertiseManager: message : 0
,11-30 22:40:04.982  4634  4700 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 22:40:04.998  4634  4696 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 22:40:05.004  4634  4696 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 22:40:05.006  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.006  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:05.006  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 22:40:05.006  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.006  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.006  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.006  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.006  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.006  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 22:40:05.007  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 22:40:05.007  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:05.008  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.008  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.008  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.008  5601  5648 I io.jxcore.node.ConnectionHelper: start: OK
,11-30 22:40:05.009  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-30 22:40:05.009  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.009  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:05.009  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 22:40:05.009  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.010  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-30 22:40:05.010  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:05.010  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.010  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 22:40:05.010  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 22:40:05.010  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-30 22:40:05.010  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.010  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.011  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.011  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.013  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-30 22:40:05.013  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 22:40:05.013  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.013  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.014  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 22:40:05.510  5601  5655 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-30 22:40:05.512  5601  5648 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-30 22:40:05.512  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-30 22:40:05.513  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-30 22:40:05.514  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-30 22:40:05.514  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-30 22:40:05.515  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-30 22:40:05.515  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-30 22:40:05.515  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-30 22:40:05.515  5601  5601 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 22:40:05.515  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-30 22:40:05.516  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-30 22:40:05.516  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-30 22:40:05.516  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-30 22:40:05.516  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-30 22:40:05.517  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-30 22:40:05.517  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-30 22:40:05.517  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-30 22:40:05.517  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-30 22:40:05.518  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-30 22:40:05.518  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-30 22:40:05.518  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-30 22:40:05.518  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-30 22:40:05.519  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-30 22:40:05.520  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-30 22:40:05.520  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-30 22:40:05.520  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-30 22:40:05.520  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-30 22:40:05.521  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-30 22:40:05.521  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-30 22:40:05.521  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-30 22:40:05.521  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-30 22:40:05.522  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-30 22:40:05.522  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-30 22:40:05.522  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-30 22:40:05.523  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-30 22:40:05.523  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-30 22:40:05.524  5601  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-30 22:40:05.524  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 22:40:05.524  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 22:40:05.524  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 22:40:05.525  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-30 22:40:05.525  5601  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 22:40:05.525  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 22:40:05.525  5601  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 22:40:05.526  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 22:40:05.526  5601  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 22:40:05.526  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-30 22:40:05.526  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 22:40:05.526  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.527  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 22:40:05.527  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 22:40:05.527  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 22:40:05.528  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.528  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.528  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.529  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.532  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:05.533  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 22:40:05.535  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:05.535  5601  5648 D BluetoothLeScanner: could not find callback wrapper
11-30 22:40:05.535  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 22:40:05.535  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.536  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.536  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.536  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 22:40:05.536  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.538  4634  4700 D BtGatt.AdvertiseManager: message : 1
11-30 22:40:05.539  4634  4700 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 22:40:05.551  4634  4696 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-30 22:40:05.551  4634  4696 D BtGatt.GattService: Client app is not null!
,11-30 22:40:05.553  4634  4845 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-30 22:40:05.553  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-30 22:40:05.554  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.554  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 22:40:05.554  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.554  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:05.554  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.554  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 22:40:05.555  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 22:40:05.555  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 22:40:05.556  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:05.557  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.558  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 22:40:05.558  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.558  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.558  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-30 22:40:05.558  5601  5601 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 22:40:05.559  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-30 22:40:05.559  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 22:40:05.559  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 22:40:05.559  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 22:40:05.559  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:05.560  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.560  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-30 22:40:05.560  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 22:40:05.560  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.560  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.560  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.560  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 22:40:05.560  5601  5656 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,11-30 22:40:05.561  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.561  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.561  5601  5648 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 22:40:05.561  5601  5648 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-30 22:40:05.561  5601  5648 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-30 22:40:05.561  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-30 22:40:05.561  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:05.561  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.562  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.562  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 22:40:05.562  5601  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 22:40:05.562  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 22:40:05.562  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-30 22:40:05.563  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.563  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.563  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.563  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 22:40:05.564  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 22:40:05.565  5601  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-30 22:40:05.565  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 22:40:05.565  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 22:40:05.565  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 22:40:05.565  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 22:40:05.565  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 22:40:05.565  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 22:40:05.565  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 22:40:05.565  5601  5657 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 22:40:05.568  5601  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 22:40:05.564  4845  4845 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33828]" dev="sockfs" ino=33828 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 22:40:05.564  4845  4845 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33828]" dev="sockfs" ino=33828 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 22:40:05.570  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 22:40:05.570  5601  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 22:40:05.570  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-30 22:40:05.575  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.575  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 22:40:05.576  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-30 22:40:05.576  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 22:40:05.576  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
,11-30 22:40:05.579  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.579  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.579  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 22:40:05.579  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 22:40:05.579  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 22:40:05.579  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-30 22:40:05.579  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:05.580  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-30 22:40:05.580  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.580  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 22:40:05.580  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:05.580  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.580  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.580  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:05.581  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:05.586  4634  4648 D BtGatt.GattService: registerClient() - UUID=e3fd6ed6-cc5d-4bd1-a325-76ba9449757a
11-30 22:40:05.587  4634  4696 D BtGatt.GattService: onClientRegistered() - UUID=e3fd6ed6-cc5d-4bd1-a325-76ba9449757a, clientIf=5
,11-30 22:40:05.587  5601  5612 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-30 22:40:05.588  4634  4700 D BtGatt.AdvertiseManager: message : 0
,11-30 22:40:05.591  4634  4700 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 22:40:05.604  4634  4696 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 22:40:05.612  4634  4696 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 22:40:05.613  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.613  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.613  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-30 22:40:05.613  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.613  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.613  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.613  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.613  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.613  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-30 22:40:05.615  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 22:40:05.615  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:05.617  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:05.617  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.617  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:05.617  5601  5648 I io.jxcore.node.ConnectionHelper: start: OK
,11-30 22:40:05.617  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-30 22:40:05.618  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.618  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:05.618  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 22:40:05.618  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.618  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.618  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:05.618  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-30 22:40:05.618  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 22:40:05.618  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 22:40:05.618  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.618  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.619  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.619  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.619  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 22:40:05.622  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.622  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 22:40:05.622  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.622  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:05.622  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 22:40:06.062   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-30 22:40:06.119  5601  5658 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-30 22:40:06.121  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-30 22:40:06.121  5601  5648 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 22:40:06.121  5601  5648 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-30 22:40:06.121  5601  5648 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-30 22:40:06.122  5601  5648 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-30 22:40:06.122  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-30 22:40:06.122  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.122  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.123  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:06.123  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-30 22:40:06.123  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-30 22:40:06.123  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-30 22:40:06.123  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-30 22:40:06.123  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-30 22:40:06.123  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-30 22:40:06.123  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-30 22:40:06.123  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-30 22:40:06.123  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-30 22:40:06.123  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-30 22:40:06.123  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.124  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-30 22:40:06.124  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:06.124  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.125  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.128  4634  4700 D BtGatt.AdvertiseManager: message : 1
11-30 22:40:06.130  4634  4700 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 22:40:06.144  4634  4696 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-30 22:40:06.144  4634  4696 D BtGatt.GattService: Client app is not null!
,11-30 22:40:06.145  4634  4845 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-30 22:40:06.146  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 22:40:06.146  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:06.147  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-30 22:40:06.147  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:06.147  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.147  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:06.147  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 22:40:06.147  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.147  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.147  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.148  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-30 22:40:06.148  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,11-30 22:40:06.148  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 22:40:06.148  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
,11-30 22:40:06.148  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:06.148  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-30 22:40:06.149  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.149  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 22:40:06.149  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-30 22:40:06.149  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.149  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.149  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.150  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:06.154  4634  4845 D BtGatt.GattService: registerClient() - UUID=4607b1b3-89d3-41df-9c7a-4d137d574dad
11-30 22:40:06.155  4634  4696 D BtGatt.GattService: onClientRegistered() - UUID=4607b1b3-89d3-41df-9c7a-4d137d574dad, clientIf=5
11-30 22:40:06.155  5601  5611 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-30 22:40:06.157  4634  4700 D BtGatt.AdvertiseManager: message : 0
11-30 22:40:06.160  4634  4700 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 22:40:06.178  4634  4696 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 22:40:06.186  4634  4696 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 22:40:06.187  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:06.187  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.187  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 22:40:06.187  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.187  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.188  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.188  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.188  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:06.188  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.188  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 22:40:06.188  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.188  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 22:40:06.189  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-30 22:40:06.189  5601  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-30 22:40:06.189  5601  5648 I io.jxcore.node.ConnectionHelper: start: OK
11-30 22:40:06.189  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.189  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:06.189  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 22:40:06.189  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.189  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.190  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:06.190  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-30 22:40:06.190  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 22:40:06.190  5601  5659 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
11-30 22:40:06.190  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 22:40:06.190  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.190  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.190  5601  5648 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-30 22:40:06.190  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-30 22:40:06.190  5601  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-30 22:40:06.190  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 22:40:06.190  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 22:40:06.191  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 22:40:06.191  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-30 22:40:06.191  5601  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 22:40:06.191  5601  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-30 22:40:06.191  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 22:40:06.191  5601  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 22:40:06.191  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 22:40:06.191  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-30 22:40:06.192  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 22:40:06.192  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.192  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-30 22:40:06.192  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 22:40:06.192  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 22:40:06.192  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 22:40:06.192  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 22:40:06.192  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.192  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.192  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.192  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.194  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:06.194  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 22:40:06.195  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:06.195  5601  5648 D BluetoothLeScanner: could not find callback wrapper
11-30 22:40:06.195  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 22:40:06.195  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.195  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.195  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.195  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 22:40:06.195  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.196  4634  4700 D BtGatt.AdvertiseManager: message : 1
,11-30 22:40:06.197  4634  4700 D BtGatt.AdvertiseManager: stop advertise for client 5
11-30 22:40:06.205  4634  4696 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-30 22:40:06.205  4634  4696 D BtGatt.GattService: Client app is not null!
,11-30 22:40:06.206  4634  4648 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 22:40:06.206  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 22:40:06.206  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.207  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 22:40:06.207  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.207  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.207  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.207  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 22:40:06.207  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 22:40:06.208  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 22:40:06.208  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.209  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.209  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 22:40:06.209  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.209  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.210  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-30 22:40:06.210  5601  5601 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 22:40:06.210  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 22:40:06.210  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 22:40:06.210  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:06.210  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.210  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 22:40:06.210  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 22:40:06.210  5601  5660 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
11-30 22:40:06.211  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.211  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.211  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.211  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 22:40:06.211  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.211  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.213  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,11-30 22:40:06.213  5601  5648 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-30 22:40:06.214  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.214  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.214  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.216  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-30 22:40:06.216  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-30 22:40:06.217  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,11-30 22:40:06.217  5601  5648 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-30 22:40:06.219  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-30 22:40:06.219  5601  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-30 22:40:06.220  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-30 22:40:06.220  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-30 22:40:06.221  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 22:40:06.221  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 22:40:06.221  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 22:40:06.221  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-30 22:40:06.221  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 22:40:06.221  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 22:40:06.221  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 22:40:06.221  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-30 22:40:06.221  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 22:40:06.221  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 22:40:06.221  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 22:40:06.222  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
,11-30 22:40:06.223  5601  5648 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 22:40:06.223  5601  5648 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-30 22:40:06.224  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-30 22:40:06.227  5601  5648 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-30 22:40:06.227  5601  5648 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-30 22:40:06.227  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-30 22:40:06.227  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-30 22:40:06.227  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-30 22:40:06.227  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-30 22:40:06.227  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-30 22:40:06.227  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-30 22:40:06.227  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-30 22:40:06.227  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-30 22:40:06.228  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-30 22:40:06.229  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-30 22:40:06.229  5601  5648 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-30 22:40:06.229  5601  5648 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-30 22:40:06.229  5601  5648 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-30 22:40:06.230  5601  5648 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 22:40:06.230  5601  5648 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-30 22:40:06.230  5601  5648 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,11-30 22:40:06.230  5601  5648 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 22:40:06.231  5601  5648 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-30 22:40:06.231  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-30 22:40:06.236  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-30 22:40:06.237  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
11-30 22:40:06.237  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-30 22:40:06.238  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,11-30 22:40:06.238  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-30 22:40:06.238  5601  5648 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-30 22:40:06.239  5601  5648 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 22:40:06.239  5601  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 133)
11-30 22:40:06.239  5601  5648 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-30 22:40:06.239  5601  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-30 22:40:06.239  5601  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,11-30 22:40:06.239  5601  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
11-30 22:40:06.239  5601  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
11-30 22:40:06.239  5601  5661 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-30 22:40:06.239  5601  5661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 22:40:06.243  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,11-30 22:40:06.238  4648  4648 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33841]" dev="sockfs" ino=33841 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 22:40:06.243  5601  5648 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-30 22:40:06.238  4648  4648 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33841]" dev="sockfs" ino=33841 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-30 22:40:06.247  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,11-30 22:40:06.247  5601  5648 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-30 22:40:06.248  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-30 22:40:06.248  5601  5648 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-30 22:40:06.248  5601  5648 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-30 22:40:06.248  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-30 22:40:06.248  5601  5648 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-30 22:40:06.248  5601  5648 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-30 22:40:06.248  5601  5648 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-30 22:40:06.248  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-30 22:40:06.248  5601  5648 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-30 22:40:06.248  5601  5648 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-30 22:40:06.249  5601  5648 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-30 22:40:06.249  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-30 22:40:06.249  5601  5648 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-30 22:40:06.249  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-30 22:40:06.249  5601  5648 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 22:40:06.249  5601  5648 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-30 22:40:06.249  5601  5648 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-30 22:40:06.250  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,11-30 22:40:06.250  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.250  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.250  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.250  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 22:40:06.250  5601  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 22:40:06.250  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 22:40:06.250  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 22:40:06.251  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 22:40:06.251  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 22:40:06.251  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 22:40:06.252  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 22:40:06.252  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 22:40:06.252  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 22:40:06.252  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 22:40:06.252  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 22:40:06.252  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 22:40:06.252  5601  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-30 22:40:06.253  5601  5662 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 22:40:06.251  4647  4647 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31411]" dev="sockfs" ino=31411 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 22:40:06.254  4647  4647 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31411]" dev="sockfs" ino=31411 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-30 22:40:06.256  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-30 22:40:06.256  5601  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 22:40:06.256  5601  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 22:40:06.256  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-30 22:40:06.260  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.260  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 22:40:06.260  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 22:40:06.260  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 22:40:06.260  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
,11-30 22:40:06.262  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.262  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.262  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 22:40:06.262  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 22:40:06.262  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 22:40:06.262  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-30 22:40:06.262  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:06.262  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:06.262  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.262  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 22:40:06.263  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:06.263  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.263  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:06.264  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.264  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:06.267  4634  4845 D BtGatt.GattService: registerClient() - UUID=343823e7-eedf-45ff-8d94-380dea094db8
11-30 22:40:06.268  4634  4696 D BtGatt.GattService: onClientRegistered() - UUID=343823e7-eedf-45ff-8d94-380dea094db8, clientIf=5
11-30 22:40:06.268  5601  5611 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-30 22:40:06.270  4634  4700 D BtGatt.AdvertiseManager: message : 0
11-30 22:40:06.271  4634  4700 D BtGatt.AdvertiseManager: starting multi advertising
11-30 22:40:06.281  4634  4696 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-30 22:40:06.286  4634  4696 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-30 22:40:06.287  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 22:40:06.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.287  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 22:40:06.289  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 22:40:06.289  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.290  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.290  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.290  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.290  5601  5648 I io.jxcore.node.ConnectionHelper: start: OK
11-30 22:40:06.290  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 22:40:06.291  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.291  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:06.291  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 22:40:06.291  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.291  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.291  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:06.291  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.291  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 22:40:06.291  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 22:40:06.291  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.291  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.291  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.291  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.291  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.293  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.294  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 22:40:06.294  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.294  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.294  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 22:40:06.791  5601  5655 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
11-30 22:40:06.792  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-30 22:40:06.792  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 22:40:06.793  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 22:40:06.793  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 22:40:06.793  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-30 22:40:06.794  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 22:40:06.794  5601  5662 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 22:40:06.794  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 22:40:06.794  5601  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 22:40:06.794  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-30 22:40:06.794  5601  5662 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 22:40:06.794  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-30 22:40:06.795  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-30 22:40:06.796  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 22:40:06.796  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 22:40:06.796  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-30 22:40:06.798  5601  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28ca4d9 removed from the list
11-30 22:40:06.799  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-30 22:40:06.799  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 22:40:06.799  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.799  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 22:40:06.799  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 22:40:06.800  5601  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 133
,11-30 22:40:06.800  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.800  5601  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-30 22:40:06.800  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:06.800  5601  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 133)
11-30 22:40:06.800  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.800  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.801  5601  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 133)
11-30 22:40:06.801  5601  5661 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-30 22:40:06.801  4634  4842 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
,11-30 22:40:06.801  5601  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-30 22:40:06.801  5601  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 133)
11-30 22:40:06.803  5601  5648 D BluetoothAdapter: STATE_ON
,11-30 22:40:06.803  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-30 22:40:06.804  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:06.804  5601  5648 D BluetoothLeScanner: could not find callback wrapper
,11-30 22:40:06.805  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 22:40:06.805  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.805  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:06.805  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.805  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-30 22:40:06.806  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.807  4634  4700 D BtGatt.AdvertiseManager: message : 1
11-30 22:40:06.808  4634  4700 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 22:40:06.821  4634  4696 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-30 22:40:06.821  4634  4696 D BtGatt.GattService: Client app is not null!
,11-30 22:40:06.822  4634  4854 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-30 22:40:06.823  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 22:40:06.824  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.824  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-30 22:40:06.824  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.824  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.824  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.824  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 22:40:06.824  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 22:40:06.826  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 22:40:06.826  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.830  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.830  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 22:40:06.830  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.830  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:06.830  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f27e9e removed from the list
11-30 22:40:06.830  5601  5648 D io.jxcore.node.ConnectivityMonitor: stop
11-30 22:40:06.830  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 22:40:06.830  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 22:40:06.831  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 22:40:06.831  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:06.831  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.831  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 22:40:06.831  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-30 22:40:06.831  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.831  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.831  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.831  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 22:40:06.832  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.832  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 22:40:06.833  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.834  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:06.834  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-30 22:40:07.333  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-30 22:40:11.369  4634  4831 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-30 22:40:11.370  4634  4831 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,11-30 22:40:11.835  5601  5656 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,11-30 22:40:11.837  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-30 22:40:11.840  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-30 22:40:11.840  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-30 22:40:11.841  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-30 22:40:11.847  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-30 22:40:11.848  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 22:40:11.848  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 22:40:11.848  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-30 22:40:11.849  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-30 22:40:11.849  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-30 22:40:11.849  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-30 22:40:11.850  5601  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-30 22:40:11.851  5601  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 22:40:11.854  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-30 22:40:11.854  4854  4854 W Binder_4: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[30579]" dev="sockfs" ino=30579 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 22:40:11.857  5601  5648 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-30 22:40:11.858  5601  5648 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-30 22:40:11.858  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
11-30 22:40:11.854  4854  4854 W Binder_4: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[30579]" dev="sockfs" ino=30579 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 22:40:11.859  5601  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 22:40:11.859  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 22:40:11.859  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 22:40:11.861  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-30 22:40:11.869  5601  5648 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-30 22:40:11.870  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-30 22:40:11.870  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 22:40:11.870  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 22:40:11.870  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 22:40:11.870  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 22:40:11.870  5601  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-30 22:40:11.870  5601  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 22:40:11.870  5601  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 22:40:11.871  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 22:40:11.871  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 22:40:11.871  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-30 22:40:11.871  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 22:40:11.871  5601  5648 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28ca4d9 not in the list
11-30 22:40:11.871  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-30 22:40:11.871  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 22:40:11.871  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 22:40:11.871  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:11.872  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 22:40:11.872  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 22:40:11.872  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:11.873  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:11.874  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 22:40:11.874  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:11.874  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:11.874  5601  5648 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f27e9e not in the list
11-30 22:40:11.874  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 22:40:11.874  5601  5648 D io.jxcore.node.ConnectivityMonitor: stop
11-30 22:40:11.874  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-30 22:40:11.874  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 22:40:11.875  5601  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-30 22:40:11.876  5601  5648 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-30 22:40:11.876  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-30 22:40:11.876  5601  5648 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-30 22:40:11.876  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-30 22:40:11.876  5601  5648 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-30 22:40:11.876  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-30 22:40:11.877  5601  5648 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-30 22:40:11.878  5601  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-30 22:40:11.879  5601  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-30 22:40:11.879  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-30 22:40:11.880  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-30 22:40:11.880  5601  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-30 22:40:11.881  5601  5648 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-30 22:40:11.881  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-30 22:40:11.881  5601  5648 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-30 22:40:11.881  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-30 22:40:11.881  5601  5648 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-30 22:40:11.881  5601  5648 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-30 22:40:11.882  5601  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-30 22:40:11.882  5601  5648 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-30 22:40:11.882  5601  5648 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-30 22:40:11.882  5601  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-30 22:40:11.883  5601  5648 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-30 22:40:11.883  5601  5648 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-30 22:40:11.883  5601  5648 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-30 22:40:11.883  5601  5648 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-30 22:40:11.883  5601  5648 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-30 22:40:11.884  5601  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-30 22:40:11.884  5601  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@409657c added. We now have 3 listener(s)
,11-30 22:40:11.886  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 22:40:11.886  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-30 22:40:11.886  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 22:40:11.886  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-30 22:40:11.886  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed42e05 added. We now have 3 listener(s)
11-30 22:40:11.886  5601  5648 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-30 22:40:11.887  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-30 22:40:11.890  5601  5648 D BluetoothAdapter: enable(): BT is already enabled..!
,11-30 22:40:11.890   930  3401 D WifiService: setWifiEnabled: true pid=5601, uid=10077
11-30 22:40:11.890   930  3401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 22:40:11.893  5601  5648 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-30 22:40:11.896  5601  5648 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-30 22:40:11.898  5601  5648 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-30 22:40:11.898  5601  5648 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-30 22:40:11.904  5601  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 22:40:11.904  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 22:40:11.904  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 22:40:11.904  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 22:40:11.904  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 22:40:11.904  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 22:40:11.904  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 22:40:11.904  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 22:40:11.904  5601  5648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-30 22:40:11.907  5601  5648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 22:40:11.907  4634  4692 D BluetoothAdapterState: Current state: ON, message: 23
,11-30 22:40:11.907  4634  4692 D BluetoothAdapterProperties: Setting state to 13
11-30 22:40:11.907  4634  4692 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-30 22:40:11.908  4634  4692 D BluetoothAdapterProperties: onBluetoothDisable()
,11-30 22:40:11.909  4634  4692 I BluetoothAdapterState: Entering PendingCommandState
,11-30 22:40:11.910  4634  4696 D BluetoothAdapterProperties: Scan Mode:20
11-30 22:40:11.910  4634  4692 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-30 22:40:11.911  4634  4634 D BluetoothMapService: onReceive
11-30 22:40:11.911  4634  4634 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-30 22:40:11.911  4634  4634 D BluetoothMapService: STATE_TURNING_OFF
11-30 22:40:11.912  4634  4634 D BluetoothMapService: MAP Service closeService in
,11-30 22:40:11.912  4634  4634 D BluetoothMapMasInstance0: MAP Service shutdown
11-30 22:40:11.912  4634  4634 D ObexServerSockets0: shutdown(block = true)
11-30 22:40:11.913  4634  4634 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-30 22:40:11.913  4634  4634 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-30 22:40:11.913  4634  4842 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-30 22:40:11.913  4634  4859 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-30 22:40:11.913  4634  4858 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-30 22:40:11.914  4634  4634 I BtOppRfcommListener: stopping Accept Thread
11-30 22:40:11.914  4634  5289 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-30 22:40:11.915  4634  5289 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-30 22:40:11.930   930   943 I ActivityManager: Start proc 5667:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-30 22:40:11.932  4634  4634 D HeadsetService: Received stop request...Stopping profile...
11-30 22:40:11.934   930   930 D BluetoothHeadset: Proxy object disconnected
11-30 22:40:11.935  3104  3116 D BluetoothHeadset: Proxy object disconnected
11-30 22:40:11.935  3814  3829 D BluetoothHeadset: Proxy object disconnected
11-30 22:40:11.935   930   930 D BluetoothHeadset: Proxy object disconnected
11-30 22:40:11.935   930   930 D BluetoothHeadset: Proxy object disconnected
11-30 22:40:11.935  3104  3104 D HeadsetProfile: Bluetooth service disconnected
,11-30 22:40:11.936  4634  4634 D A2dpService: Received stop request...Stopping profile...
,11-30 22:40:11.937  4634  4847 D A2dpStateMachine: Exit Disconnected: -1
11-30 22:40:11.938   930   930 D BluetoothA2dp: Proxy object disconnected
11-30 22:40:11.938  3104  3104 D BluetoothA2dp: Proxy object disconnected
,11-30 22:40:11.938  4634  4634 V BluetoothAdapterState: isTurningOff()=true
11-30 22:40:11.938  4634  4634 V BluetoothAdapterState: isTurningOn()=false
11-30 22:40:11.938  4634  4634 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:11.938  4634  4634 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:11.939  4634  4634 D HidService: Received stop request...Stopping profile...
11-30 22:40:11.939  4634  4634 D HidService: Stopping Bluetooth HidService
11-30 22:40:11.940  3104  3104 D BluetoothInputDevice: Proxy object disconnected
11-30 22:40:11.940  3104  3104 D HidProfile: Bluetooth service disconnected
,11-30 22:40:11.942  4634  4634 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-30 22:40:11.943  4634  4634 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-30 22:40:11.943  4634  4696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-30 22:40:11.943  4634  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 22:40:11.944  4634  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 22:40:11.944  4634  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 22:40:11.944  4634  4634 D HealthService: Received stop request...Stopping profile...
11-30 22:40:11.944  4634  4696 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-30 22:40:11.945  4634  4634 D PanService: Received stop request...Stopping profile...
11-30 22:40:11.946  3104  3104 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-30 22:40:11.946  3104  3104 D PanProfile: Bluetooth service disconnected
11-30 22:40:11.949  4634  4634 D BluetoothMapService: Received stop request...Stopping profile...
11-30 22:40:11.949  4634  4634 D BluetoothMapService: stop()
11-30 22:40:11.949  4634  4634 D BluetoothMapAppObserver: deinitObservers()
11-30 22:40:11.949  4634  4634 D BluetoothMapAppObserver: removeReceiver()
11-30 22:40:11.951  4634  4634 V BluetoothAdapterState: isTurningOff()=true
11-30 22:40:11.951  3104  3104 D BluetoothMap: Proxy object disconnected
11-30 22:40:11.951  3104  3104 D MapProfile: Bluetooth service disconnected
11-30 22:40:11.951  4634  4634 V BluetoothAdapterState: isTurningOn()=false
11-30 22:40:11.951  4634  4634 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:11.951  4634  4634 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:11.952  4634  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 22:40:11.952  4634  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 22:40:11.953  4634  4696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-30 22:40:11.953  4634  4831 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-30 22:40:11.953  4634  4831 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-30 22:40:11.953  4634  4634 D SapService: Received stop request...Stopping profile...
11-30 22:40:11.953  4634  4831 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-30 22:40:11.953  4634  4634 V SapService: stop()
11-30 22:40:11.953  4634  4831 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-30 22:40:11.955  4634  4634 V BluetoothAdapterState: isTurningOff()=true
,11-30 22:40:11.955  4634  4634 V BluetoothAdapterState: isTurningOn()=false
11-30 22:40:11.955  4634  4634 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:11.955  4634  4634 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:11.955  4634  4634 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-30 22:40:11.955  4634  4634 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-30 22:40:11.956  4634  4696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-30 22:40:11.956  4634  4634 V BluetoothAdapterState: isTurningOff()=true
11-30 22:40:11.956  4634  4634 V BluetoothAdapterState: isTurningOn()=false
11-30 22:40:11.957  4634  4634 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:11.957  4634  4634 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:11.957  4634  4634 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-30 22:40:11.957  4634  4696 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-30 22:40:11.958  4634  4634 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-30 22:40:11.958  4634  4634 V BluetoothAdapterState: isTurningOff()=true
11-30 22:40:11.958  4634  4634 V BluetoothAdapterState: isTurningOn()=false
11-30 22:40:11.958  4634  4634 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:11.958  4634  4634 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:11.958  4634  4634 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-30 22:40:11.958  4634  4634 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-30 22:40:11.962  4634  4634 D BluetoothMapService: MAP Service closeService in
,11-30 22:40:11.962  4634  4634 V BluetoothAdapterState: isTurningOff()=true
11-30 22:40:11.962  4634  4634 V BluetoothAdapterState: isTurningOn()=false
11-30 22:40:11.962  4634  4634 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:11.962  4634  4634 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:11.962  4634  4634 D BluetoothMapService: cleanup()
11-30 22:40:11.962  4634  4634 D BluetoothMapService: MAP Service closeService in
11-30 22:40:11.962  4634  4634 V BluetoothAdapterState: isTurningOff()=true
11-30 22:40:11.962  4634  4634 V BluetoothAdapterState: isTurningOn()=false
11-30 22:40:11.962  4634  4634 V BluetoothAdapterState: isBleTurningOn()=false
,11-30 22:40:11.962  4634  4634 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:11.963  4634  4692 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-30 22:40:11.963  4634  4692 D BluetoothAdapterProperties: Setting state to 15
11-30 22:40:11.963  4634  4692 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-30 22:40:11.965  4634  4692 I BluetoothAdapterState: Entering BleOnState
,11-30 22:40:11.966   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-30 22:40:11.966  3104  3903 D BluetoothMap: onBluetoothStateChange: up=false
11-30 22:40:11.967   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 22:40:11.967  3104  3122 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-30 22:40:11.968   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 22:40:11.968  3814  4214 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 22:40:11.968  3104  3116 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 22:40:11.969   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 22:40:11.969  3104  3972 D BluetoothA2dp: onBluetoothStateChange: up=false
11-30 22:40:11.970  3104  3903 D BluetoothPan: onBluetoothStateChange on: false
11-30 22:40:11.970  3104  3122 D BluetoothPbap: onBluetoothStateChange: up=false
,11-30 22:40:11.971  4634  4692 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-30 22:40:11.972  4634  4692 D BluetoothAdapterProperties: Setting state to 16
11-30 22:40:11.972  4634  4692 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-30 22:40:11.972  4634  4692 D BluetoothAdapterProperties: onBleDisable
11-30 22:40:11.972  4634  4692 I BluetoothAdapterState: Entering PendingCommandState
11-30 22:40:11.973  4634  4693 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-30 22:40:11.974  4634  4696 D BluetoothAdapterProperties: Scan Mode:20
11-30 22:40:11.977  4634  4831 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-30 22:40:11.977  4634  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-30 22:40:11.980  5667  5667 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-30 22:40:11.995  5667  5667 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-30 22:40:12.001   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4c77fef:true
,11-30 22:40:12.001  3572  3572 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-30 22:40:12.016  5667  5667 D LocalBluetoothProfileManager: Adding local MAP profile
,11-30 22:40:12.018  5667  5667 D BluetoothMap: Create BluetoothMap proxy object
,11-30 22:40:12.024  5667  5667 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-30 22:40:12.030  5667  5667 D DockEventReceiver: finishStartingService: stopping service
,11-30 22:40:12.032  5667  5667 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-30 22:40:12.037  5667  5667 D DockEventReceiver: finishStartingService: stopping service
11-30 22:40:12.037  3572  3572 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-30 22:40:12.039   930  3831 I ActivityManager: Killing 5383:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-30 22:40:12.187  4634  4696 I bt_hci  : shut_down
,11-30 22:40:12.192  4634  4703 D bt_hwcfg: hw_epilog_process
,11-30 22:40:12.193  4634  4703 I bt_vendor: low_power_mode_cb
,11-30 22:40:12.195  4634  4703 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-30 22:40:12.195  4634  4703 I bt_vendor: epilog_cb
11-30 22:40:12.195  4634  4703 I bt_hci  : epilog_finished_callback
,11-30 22:40:12.197  4634  4696 I bt_hci_h4: hal_close
,11-30 22:40:12.198  4634  4696 I bt_userial_vendor: device fd = 54 close
,11-30 22:40:12.306  4634  4693 D bt_stack_manager: event_shut_down_stack finished.
11-30 22:40:12.307  4634  4692 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-30 22:40:12.310  4634  4634 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-30 22:40:12.310  4634  4692 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-30 22:40:12.311  4634  4634 D BtGatt.GattService: Received stop request...Stopping profile...
11-30 22:40:12.311  4634  4634 D BtGatt.GattService: stop()
,11-30 22:40:12.311  4634  4634 D BtGatt.AdvertiseManager: advertise clients cleared
11-30 22:40:12.314  4634  4634 V BluetoothAdapterState: isTurningOff()=false
11-30 22:40:12.314  4634  4634 V BluetoothAdapterState: isTurningOn()=false
11-30 22:40:12.314  4634  4634 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:12.314  4634  4634 V BluetoothAdapterState: isBleTurningOff()=true
11-30 22:40:12.314  4634  4692 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-30 22:40:12.315  4634  4692 D BluetoothAdapterProperties: Setting state to 10
11-30 22:40:12.315  4634  4692 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-30 22:40:12.316  4634  4692 I BluetoothAdapterState: Entering OffState
,11-30 22:40:12.317   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-30 22:40:12.330  4634  4634 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-30 22:40:12.330  4634  4634 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-30 22:40:12.330  4634  4634 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-30 22:40:12.331  4634  4693 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-30 22:40:12.335  4634  4634 I art     : System.exit called, status: 0
,11-30 22:40:12.335  4634  4634 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-30 22:40:12.360   930   941 I ActivityManager: Process com.android.bluetooth (pid 4634) has died
,11-30 22:40:12.375  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-30 22:40:12.408  5601  5665 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-30 22:40:12.408  5601  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 22:40:12.408  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 22:40:12.408  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 22:40:12.408  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 22:40:12.408  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-30 22:40:12.408  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 22:40:12.408  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 22:40:12.408  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 22:40:12.408  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-30 22:40:12.408  5601  5665 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-30 22:40:12.408  5601  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 22:40:12.412  5601  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-30 22:40:12.427   930   947 I ActivityManager: Start proc 5684:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-30 22:40:12.486  5684  5684 D AdapterServiceConfig: Adding HeadsetService
,11-30 22:40:12.486  5684  5684 D AdapterServiceConfig: Adding A2dpService
11-30 22:40:12.486  5684  5684 D AdapterServiceConfig: Adding HidService
11-30 22:40:12.486  5684  5684 D AdapterServiceConfig: Adding HealthService
11-30 22:40:12.487  5684  5684 D AdapterServiceConfig: Adding PanService
,11-30 22:40:12.487  5684  5684 D AdapterServiceConfig: Adding GattService
11-30 22:40:12.487  5684  5684 D AdapterServiceConfig: Adding BluetoothMapService
11-30 22:40:12.487  5684  5684 D AdapterServiceConfig: Adding SapService
,11-30 22:40:12.497   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cbf071:true
,11-30 22:40:12.497  5684  5684 D BluetoothAdapterState: make() - Creating AdapterState
,11-30 22:40:12.500  5684  5684 I bt_bluedroid: init
11-30 22:40:12.500  5684  5696 I BluetoothAdapterState: Entering OffState
,11-30 22:40:12.502  5684  5697 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-30 22:40:12.502  5684  5697 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-30 22:40:12.502  5684  5697 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-30 22:40:12.502  5684  5697 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-30 22:40:12.502  5684  5684 I bt_bluedroid: get_profile_interface socket
,11-30 22:40:12.504  5684  5684 I bt_bluedroid: get_profile_interface sdp
11-30 22:40:12.504  5684  5700 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-30 22:40:12.505  5684  5700 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-30 22:40:12.508  5684  5695 I bt_bluedroid: config_hci_snoop_log
11-30 22:40:12.509   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-30 22:40:12.514  5684  5696 D BluetoothAdapterState: Current state: OFF, message: 0
,11-30 22:40:12.514  5684  5696 D BluetoothAdapterProperties: Setting state to 14
11-30 22:40:12.514  5684  5696 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-30 22:40:12.515  5684  5696 D BluetoothBondStateMachine: make
,11-30 22:40:12.517  5684  5701 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-30 22:40:12.520  5684  5696 I BluetoothAdapterState: Entering PendingCommandState
,11-30 22:40:12.521  5684  5684 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-30 22:40:12.524  5684  5684 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c872da
,11-30 22:40:12.524  5684  5684 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-30 22:40:12.525  5684  5684 D BtGatt.GattService: Received start request. Starting profile...
11-30 22:40:12.525  5684  5684 D BtGatt.GattService: start()
11-30 22:40:12.525  5684  5684 I bt_bluedroid: get_profile_interface gatt
,11-30 22:40:12.526  5684  5684 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c872da
,11-30 22:40:12.527  5684  5684 D BtGatt.AdvertiseManager: advertise manager created
,11-30 22:40:12.531  5684  5684 V BluetoothAdapterState: isTurningOff()=false
11-30 22:40:12.531  5684  5684 V BluetoothAdapterState: isTurningOn()=false
11-30 22:40:12.531  5684  5684 V BluetoothAdapterState: isBleTurningOn()=true
11-30 22:40:12.531  5684  5684 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:12.532  5684  5696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-30 22:40:12.533  5684  5696 I bt_bluedroid: bt_bluedroid
,11-30 22:40:12.533  5684  5697 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-30 22:40:12.533  5684  5697 I bt_hci  : start_up
,11-30 22:40:12.539  5684  5697 I bt_vendor: alloc value 0xf3df9871
,11-30 22:40:12.540  5684  5697 I bt_vendor: init
,11-30 22:40:12.540  5684  5697 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-30 22:40:12.540  5684  5697 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-30 22:40:12.653  5684  5697 D bt_hci  : start_up starting async portion
,11-30 22:40:12.653  5684  5704 I bt_hci  : event_finish_startup
,11-30 22:40:12.654  5684  5704 I bt_hci_h4: hal_open
,11-30 22:40:12.654  5684  5704 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-30 22:40:12.654  5705  5705 W irq/448-msm_hs_: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 22:40:12.659  5684  5704 I bt_userial_vendor: device fd = 54 open
,11-30 22:40:12.673  5684  5704 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-30 22:40:12.676  5684  5704 D bt_hwcfg: Chipset BCM4358A3
,11-30 22:40:12.676  5684  5704 D bt_hwcfg: Target name = [BCM4358A3]
11-30 22:40:12.677  5684  5704 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-30 22:40:12.917  5684  5696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-30 22:40:13.074  5684  5704 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-30 22:40:13.074  5684  5704 D bt_hwcfg: Settlement delay -- 100 ms
,11-30 22:40:13.074  5684  5704 I bt_hwcfg: Setting fw settlement delay to 100 
,11-30 22:40:13.199  5684  5704 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-30 22:40:13.199  5684  5704 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-30 22:40:13.201  5684  5704 I bt_hwcfg: vendor lib fwcfg completed
11-30 22:40:13.201  5684  5704 I bt_vendor: firmware callback
,11-30 22:40:13.201  5684  5704 I bt_hci  : firmware_config_callback
,11-30 22:40:13.211  5684  5707 I bt_btu  : btu_task pending for preload complete event
,11-30 22:40:13.212  5684  5707 I bt_btu_task: Bluetooth chip preload is complete
11-30 22:40:13.212  5684  5707 I bt_btu  : btu_task received preload complete event
11-30 22:40:13.219  5684  5707 I         : BTE_InitTraceLevels -- TRC_HCI
,11-30 22:40:13.219  5684  5707 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-30 22:40:13.220  5684  5707 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-30 22:40:13.220  5684  5707 I         : BTE_InitTraceLevels -- TRC_AVDT
11-30 22:40:13.220  5684  5707 I         : BTE_InitTraceLevels -- TRC_AVRC
11-30 22:40:13.220  5684  5707 I         : BTE_InitTraceLevels -- TRC_A2D
11-30 22:40:13.220  5684  5707 I         : BTE_InitTraceLevels -- TRC_BNEP
11-30 22:40:13.220  5684  5707 I         : BTE_InitTraceLevels -- TRC_BTM
11-30 22:40:13.220  5684  5707 I         : BTE_InitTraceLevels -- TRC_GAP
11-30 22:40:13.220  5684  5707 I         : BTE_InitTraceLevels -- TRC_PAN
11-30 22:40:13.220  5684  5707 I         : BTE_InitTraceLevels -- TRC_SDP
11-30 22:40:13.221  5684  5707 I         : BTE_InitTraceLevels -- TRC_GATT
11-30 22:40:13.221  5684  5707 I         : BTE_InitTraceLevels -- TRC_SMP
11-30 22:40:13.221  5684  5707 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-30 22:40:13.221  5684  5707 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-30 22:40:13.308  5684  5707 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d77549
11-30 22:40:13.309  5684  5707 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d77549 
,11-30 22:40:13.331  5684  5700 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-30 22:40:13.332  5684  5700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-30 22:40:13.333  5684  5700 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-30 22:40:13.335  5684  5700 D BluetoothAdapterProperties: Name is: Nexus 6P
11-30 22:40:13.340  5684  5700 D BluetoothAdapterProperties: Scan Mode:20
11-30 22:40:13.340  5684  5700 D BluetoothAdapterProperties: Discoverable Timeout:120
11-30 22:40:13.340  5684  5700 D bt_hci  : do_postload posting postload work item
11-30 22:40:13.341  5684  5704 I bt_hci  : event_postload
11-30 22:40:13.341  5684  5704 I bt_vendor: sco_config_cb
11-30 22:40:13.341  5684  5704 I bt_hci  : sco_config_callback postload finished.
11-30 22:40:13.344  5684  5700 D bt_bte_conf: Device ID record 1 : primary
11-30 22:40:13.344  5684  5700 D bt_bte_conf:   vendorId            = 000f
11-30 22:40:13.344  5684  5700 D bt_bte_conf:   vendorIdSource      = 0001
11-30 22:40:13.344  5684  5700 D bt_bte_conf:   product             = 1200
11-30 22:40:13.344  5684  5700 D bt_bte_conf:   version             = 1436
11-30 22:40:13.344  5684  5700 D bt_bte_conf:   clientExecutableURL = 
11-30 22:40:13.344  5684  5700 D bt_bte_conf:   serviceDescription  = 
11-30 22:40:13.344  5684  5700 D bt_bte_conf:   documentationURL    = 
11-30 22:40:13.344  5684  5700 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-30 22:40:13.345  5684  5697 D bt_stack_manager: event_start_up_stack finished
11-30 22:40:13.346  5684  5696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-30 22:40:13.347  5684  5696 D BluetoothAdapterProperties: Setting state to 15
11-30 22:40:13.347  5684  5696 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-30 22:40:13.348  5684  5696 I BluetoothAdapterState: Entering BleOnState
11-30 22:40:13.350  5684  5704 I bt_vendor: low_power_mode_cb
11-30 22:40:13.355  5684  5696 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-30 22:40:13.356  5684  5696 D BluetoothAdapterProperties: Setting state to 11
11-30 22:40:13.356  5684  5696 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-30 22:40:13.364  5684  5684 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c872da
11-30 22:40:13.365  5684  5684 D HeadsetService: Received start request. Starting profile...
11-30 22:40:13.368  5684  5684 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-30 22:40:13.368  5684  5684 D HeadsetStateMachine: make
11-30 22:40:13.374  5684  5696 I BluetoothAdapterState: Entering PendingCommandState
,11-30 22:40:13.377  5684  5684 D HeadsetStateMachine: max_hf_connections = 1
,11-30 22:40:13.377  5684  5684 I bt_bluedroid: get_profile_interface handsfree
11-30 22:40:13.377  5684  5700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-30 22:40:13.377  5684  5700 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-30 22:40:13.382  5684  5684 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c872da
,11-30 22:40:13.382  5684  5684 D A2dpService: Received start request. Starting profile...
11-30 22:40:13.383  3572  3572 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-30 22:40:13.383  5684  5684 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-30 22:40:13.383  5684  5684 I bt_bluedroid: get_profile_interface avrcp
,11-30 22:40:13.389  5684  5684 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-30 22:40:13.389  5684  5684 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-30 22:40:13.389  5684  5684 D A2dpStateMachine: make
,11-30 22:40:13.391  5684  5684 I bt_bluedroid: get_profile_interface a2dp
,11-30 22:40:13.392  5684  5700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-30 22:40:13.392  5684  5714 D A2dpStateMachine: Enter Disconnected: -2
11-30 22:40:13.393  5684  5684 I BluetoothHidServiceJni: classInitNative: succeeds
11-30 22:40:13.394  5684  5684 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c872da
,11-30 22:40:13.395  5667  5667 D BluetoothInputDevice: Proxy object connected
,11-30 22:40:13.395  5684  5684 D HidService: Received start request. Starting profile...
11-30 22:40:13.395  5684  5684 I bt_bluedroid: get_profile_interface hidhost
11-30 22:40:13.395  5684  5700 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d5856d
11-30 22:40:13.395  5684  5700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-30 22:40:13.395  5684  5684 D HidService: setHidService(): set to: null
11-30 22:40:13.395  5667  5667 D HidProfile: Bluetooth service connected
11-30 22:40:13.396  5684  5684 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-30 22:40:13.397  5684  5684 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c872da
11-30 22:40:13.398  5684  5684 D HealthService: Received start request. Starting profile...
,11-30 22:40:13.399  5684  5684 I bt_bluedroid: get_profile_interface health
11-30 22:40:13.400  5684  5684 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-30 22:40:13.400  5684  5684 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c872da
11-30 22:40:13.401  5684  5684 D PanService: Received start request. Starting profile...
11-30 22:40:13.402  5684  5684 D BluetoothPanServiceJni: initializeNative(L110): pan
11-30 22:40:13.402  5684  5684 I bt_bluedroid: get_profile_interface pan
11-30 22:40:13.402  5667  5667 D BluetoothPan: BluetoothPAN Proxy object connected
11-30 22:40:13.402  5684  5700 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-30 22:40:13.403  5667  5667 D PanProfile: Bluetooth service connected
11-30 22:40:13.404  5684  5684 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c872da
11-30 22:40:13.405  5667  5667 D BluetoothMap: Proxy object connected
11-30 22:40:13.405  5684  5684 D BluetoothMapService: Received start request. Starting profile...
11-30 22:40:13.405  5684  5684 D BluetoothMapService: start()
11-30 22:40:13.405  5667  5667 D MapProfile: Bluetooth service connected
11-30 22:40:13.405  5667  5667 D BluetoothMap: getConnectedDevices()
11-30 22:40:13.406  5667  5667 D BluetoothMap: Bluetooth is Not enabled
,11-30 22:40:13.408  5684  5684 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-30 22:40:13.409  5684  5684 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-30 22:40:13.409  5684  5684 D BluetoothMapAppObserver: createReceiver()
,11-30 22:40:13.411  5684  5684 D BluetoothMapAppObserver: initObservers()
11-30 22:40:13.411  5684  5684 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-30 22:40:13.418  5684  5684 V SapService: SapBinder()
,11-30 22:40:13.418  5684  5696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
11-30 22:40:13.418  5684  5684 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c872da
11-30 22:40:13.419  5684  5684 D SapService: Received start request. Starting profile...
11-30 22:40:13.419  5684  5684 V SapService: start()
,11-30 22:40:13.422  5684  5684 V BluetoothAdapterState: isTurningOff()=false
11-30 22:40:13.422  5684  5684 V BluetoothAdapterState: isTurningOn()=true
,11-30 22:40:13.422  5684  5712 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-30 22:40:13.422  5684  5684 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:13.422  5684  5684 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:13.423  5684  5684 V BluetoothAdapterState: isTurningOff()=false
11-30 22:40:13.423  5684  5684 V BluetoothAdapterState: isTurningOn()=true
11-30 22:40:13.423  5684  5684 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:13.423  5684  5684 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:13.423  5684  5684 V BluetoothAdapterState: isTurningOff()=false
11-30 22:40:13.423  5684  5684 V BluetoothAdapterState: isTurningOn()=true
,11-30 22:40:13.424  5684  5684 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:13.424  5684  5684 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:13.424  5684  5684 V BluetoothAdapterState: isTurningOff()=false
11-30 22:40:13.424  5684  5684 V BluetoothAdapterState: isTurningOn()=true
11-30 22:40:13.424  5684  5684 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:13.424  5684  5684 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:13.424  5684  5684 V BluetoothAdapterState: isTurningOff()=false
,11-30 22:40:13.424  5684  5684 V BluetoothAdapterState: isTurningOn()=true
11-30 22:40:13.424  5684  5684 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:13.424  5684  5684 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:13.425  5684  5684 V BluetoothAdapterState: isTurningOff()=false
11-30 22:40:13.425  5684  5684 V BluetoothAdapterState: isTurningOn()=true
11-30 22:40:13.425  5684  5684 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:13.425  5684  5684 V BluetoothAdapterState: isBleTurningOff()=false
,11-30 22:40:13.426  5684  5684 V BluetoothAdapterState: isTurningOff()=false
,11-30 22:40:13.426  5684  5684 V BluetoothAdapterState: isTurningOn()=true
11-30 22:40:13.426  5684  5684 V BluetoothAdapterState: isBleTurningOn()=false
11-30 22:40:13.426  5684  5684 V BluetoothAdapterState: isBleTurningOff()=false
11-30 22:40:13.426  5684  5696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-30 22:40:13.426  5684  5696 D BluetoothAdapterProperties: ScanMode =  20
11-30 22:40:13.426  5684  5696 D BluetoothAdapterProperties: State =  11
11-30 22:40:13.427  5684  5696 D BluetoothAdapterProperties: Setting state to 12
11-30 22:40:13.427  5684  5696 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-30 22:40:13.427  5684  5696 I BluetoothAdapterState: Entering OnState
11-30 22:40:13.427   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-30 22:40:13.428  5684  5700 D BluetoothAdapterProperties: Scan Mode:21
,11-30 22:40:13.428  5684  5700 D BluetoothAdapterProperties: Discoverable Timeout:120
11-30 22:40:13.428  3104  3116 D BluetoothMap: onBluetoothStateChange: up=true
11-30 22:40:13.429   930   930 D BluetoothA2dp: Proxy object connected
,11-30 22:40:13.430  3104  3104 D BluetoothMap: Proxy object connected
,11-30 22:40:13.431  3104  3104 D MapProfile: Bluetooth service connected
11-30 22:40:13.431  3104  3104 D BluetoothMap: getConnectedDevices()
11-30 22:40:13.431  5667  5677 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-30 22:40:13.431   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 22:40:13.431  3104  3903 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-30 22:40:13.432   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-30 22:40:13.432  3104  3104 D BluetoothInputDevice: Proxy object connected
11-30 22:40:13.432  3104  3104 D HidProfile: Bluetooth service connected
,11-30 22:40:13.433  5667  5678 D BluetoothPan: onBluetoothStateChange on: true
11-30 22:40:13.433  5667  5677 D BluetoothPbap: onBluetoothStateChange: up=true
,11-30 22:40:13.434  3814  4214 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 22:40:13.434  3104  3972 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 22:40:13.435   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 22:40:13.435  3104  3116 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-30 22:40:13.436  3104  3104 D BluetoothA2dp: Proxy object connected
,11-30 22:40:13.436  3104  3122 D BluetoothPan: onBluetoothStateChange on: true
11-30 22:40:13.437  3104  3116 D BluetoothPbap: onBluetoothStateChange: up=true
11-30 22:40:13.437  5684  5684 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-30 22:40:13.438  3104  3104 D BluetoothPan: BluetoothPAN Proxy object connected
11-30 22:40:13.438  3104  3104 D PanProfile: Bluetooth service connected
11-30 22:40:13.438  5684  5684 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-30 22:40:13.439  5684  5684 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 22:40:13.440  5667  5678 D BluetoothMap: onBluetoothStateChange: up=true
,11-30 22:40:13.441   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-30 22:40:13.442  5684  5684 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 22:40:13.443  5667  5667 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-30 22:40:13.444  5684  5684 D ObexServerSockets: Succeed to create listening sockets 
11-30 22:40:13.444  5684  5684 D ObexServerSockets0: startAccept()
11-30 22:40:13.444  5684  5684 D ObexServerSockets0: prepareForNewConnect()
,11-30 22:40:13.446  5667  5667 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-30 22:40:13.447  5684  5684 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-30 22:40:13.447  5684  5684 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-30 22:40:13.448  5684  5684 D BluetoothMapService: onReceive
,11-30 22:40:13.448  5684  5684 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-30 22:40:13.448  5684  5684 D BluetoothMapService: STATE_ON
11-30 22:40:13.449  5684  5721 D ObexServerSockets0: Accepting socket connection...
11-30 22:40:13.449  5684  5722 D ObexServerSockets0: Accepting socket connection...
,11-30 22:40:13.453  5667  5667 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-30 22:40:13.453  5684  5723 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 22:40:13.455  5667  5667 D BluetoothA2dp: Proxy object connected
11-30 22:40:13.456  5684  5723 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-30 22:40:13.456  5684  5723 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-30 22:40:13.459  3572  3572 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-30 22:40:13.463  5667  5667 D DockEventReceiver: finishStartingService: stopping service
,11-30 22:40:13.469  3104  3104 D BluetoothPbap: Proxy object connected
11-30 22:40:13.469  5667  5667 D BluetoothPbap: Proxy object connected
11-30 22:40:13.469  3104  3104 D PbapServerProfile: Bluetooth service connected
,11-30 22:40:13.470  5667  5667 D PbapServerProfile: Bluetooth service connected
,11-30 22:40:13.473  5684  5684 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-30 22:40:13.473  5684  5684 D ObexServerSockets0: prepareForNewConnect()
,11-30 22:40:13.474  5684  5727 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 22:40:13.488  5684  5731 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 22:40:13.489  5684  5731 I BtOppRfcommListener: Accept thread started.
,11-30 22:40:13.532   930   930 D BluetoothHeadset: Proxy object connected
11-30 22:40:13.532   930   947 D BluetoothHeadset: Proxy object connected
11-30 22:40:13.532  3104  3903 D BluetoothHeadset: Proxy object connected
,11-30 22:40:13.532  3104  3104 D HeadsetProfile: Bluetooth service connected
,11-30 22:40:13.533  3814  3830 D BluetoothHeadset: Proxy object connected
11-30 22:40:13.534   930   930 D BluetoothHeadset: Proxy object connected
11-30 22:40:13.534   930   930 D BluetoothHeadset: Proxy object connected
11-30 22:40:13.535  3814  3971 D BluetoothHeadset: Proxy object connected
11-30 22:40:13.535  3104  3122 D BluetoothHeadset: Proxy object connected
11-30 22:40:13.535  3104  3104 D HeadsetProfile: Bluetooth service connected
11-30 22:40:13.536   930   947 D BluetoothHeadset: Proxy object connected
,11-30 22:40:13.549  5667  5678 D BluetoothHeadset: Proxy object connected
11-30 22:40:13.550  5667  5667 D HeadsetProfile: Bluetooth service connected
,11-30 22:40:13.931  5601  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 22:40:13.931  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 22:40:13.931  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 22:40:13.931  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 22:40:13.931  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 22:40:13.931  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 22:40:13.931  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 22:40:13.931  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 22:40:13.931  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-30 22:40:13.939  5601  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 22:40:13.941  5601  5648 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-30 22:40:13.944   930  3137 D WifiService: setWifiEnabled: false pid=5601, uid=10077
,11-30 22:40:13.944   930  3137 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 22:40:13.951   930  2936 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-30 22:40:13.950  5601  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-30 22:40:13.951   930  2936 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-30 22:40:13.952   930  2936 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-30 22:40:13.952   930  2936 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-30 22:40:13.970   930  5358 D DhcpClient: Clearing IP address
11-30 22:40:13.970   509   924 D CommandListener: Clearing all IP addresses on wlan0
,11-30 22:40:13.979   509   924 D CommandListener: Setting iface cfg
,11-30 22:40:13.984  3572  5411 V NativeCrypto: Read error: ssl=0x7f94590700: I/O error during system call, Connection timed out
,11-30 22:40:13.986  3572  5411 V NativeCrypto: SSL shutdown failed: ssl=0x7f94590700: I/O error during system call, Broken pipe
,11-30 22:40:13.988   930  3402 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-30 22:40:13.989   930  5356 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-30 22:40:13.991   930  5356 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-30 22:40:13.992   930  2950 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-30 22:40:13.992   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-30 22:40:13.994   930  2950 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-30 22:40:13.998   930  5359 D DhcpClient: Receive thread stopped
,11-30 22:40:13.999   930  2950 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-30 22:40:13.999   930  2950 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-30 22:40:14.004   535   535 E Parcel  : Reading a NULL string not supported here.
11-30 22:40:14.005   930   930 D RttService: SCAN_AVAILABLE : 1
11-30 22:40:14.005   930  3066 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-30 22:40:14.007   930  2950 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-30 22:40:14.010  3743  3880 W QCNEJ   : |CORE| network lost: 100
11-30 22:40:14.011  3743  3880 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-30 22:40:14.019   930  2936 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-30 22:40:14.026   930  2936 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-30 22:40:14.036   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 22:40:14.056   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 22:40:14.056   509   924 D CommandListener: Clearing all IP addresses on wlan0
11-30 22:40:14.056   509   924 D TetherController: Setting IP forward enable = 0
,11-30 22:40:14.058   930  2950 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-30 22:40:14.058   930  2950 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-30 22:40:14.060   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-30 22:40:14.062   930  2936 D DhcpClient: doQuit
,11-30 22:40:14.063   930  2936 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-30 22:40:14.063   930  5358 D DhcpClient: onQuitting
11-30 22:40:14.063  3427  3427 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-30 22:40:14.064  5242  5242 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@17b1aaf and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-30 22:40:14.066  3948  3948 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-30 22:40:14.079  5029  5052 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-30 22:40:14.079  5029  5052 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-30 22:40:14.079  5029  5052 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-30 22:40:14.081  3709  3709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-30 22:40:14.083  5029  5052 E SarControlService: no key has been found,reset the power
11-30 22:40:14.083  5029  5064 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-30 22:40:14.083  5029  5064 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-30 22:40:14.083  5029  5064 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-30 22:40:14.084  5054  5054 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 22:40:14.084  5054  5054 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-30 22:40:14.085  5029  5064 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-30 22:40:14.085  5029  5064 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-30 22:40:14.085  3427  3427 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-30 22:40:14.085  5029  5064 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-30 22:40:14.086  5054  5054 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 22:40:14.086  5054  5054 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-30 22:40:14.090  5054  5068 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4098cd HexData = [00000000ea03000000000000ffffffff]
,11-30 22:40:14.090  5054  5068 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 22:40:14.090  3427  3427 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-30 22:40:14.090  5054  5068 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,11-30 22:40:14.092   509   917 W SocketClient: write error (Broken pipe)
11-30 22:40:14.092  5054  5054 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 22:40:14.092   509   917 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-30 22:40:14.092   509   917 W SocketListener: Error sending broadcast (Broken pipe)
11-30 22:40:14.093  5029  5039 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-30 22:40:14.093  3709  3709 D SystemUpdateService: onCreate
11-30 22:40:14.098  5054  5068 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4098cd HexData = [00000000eb03000000000000ffffffff]
11-30 22:40:14.098  5054  5068 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-30 22:40:14.098  5054  5068 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-30 22:40:14.099  5054  5054 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 22:40:14.099  5029  5040 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-30 22:40:14.100  3709  3709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-30 22:40:14.105  3709  5750 I SystemUpdateService: active receiver: enabled
11-30 22:40:14.109  3709  3709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-30 22:40:14.114  3709  5380 I iu.UploadsManager: num queued entries: 0
,11-30 22:40:14.114  3709  5380 I iu.UploadsManager: num updated entries: 0
11-30 22:40:14.115  3709  5380 I iu.SyncManager: NEXT; no task
,11-30 22:40:14.116   509   924 E Netd    : netlink response contains error (No such file or directory)
,11-30 22:40:14.117   509   924 D TetherController: Setting IP forward enable = 0
11-30 22:40:14.117   930  2950 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-30 22:40:14.118  3709  3709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-30 22:40:14.120  3709  3709 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-30 22:40:14.122  3709  5750 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-30 22:40:14.123  3709  5750 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-30 22:40:14.124  3709  5750 I SystemUpdateService: now status is 0 (complete)
11-30 22:40:14.124  3709  5750 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-30 22:40:14.124  3709  5750 I SystemUpdateService: file has been verified
11-30 22:40:14.124  3709  5750 I SystemUpdateService: OTA package size = 21989297
11-30 22:40:14.125  3427  3427 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-30 22:40:14.130  3709  5750 I SystemUpdateService: showing system update notification
,11-30 22:40:14.131   930  3776 I ActivityManager: Start proc 5755:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-30 22:40:14.143   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-30 22:40:14.144  3427  3427 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-30 22:40:14.148  3709  3709 D SystemUpdateService: onDestroy
,11-30 22:40:14.170  5755  5755 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-30 22:40:14.173  5755  5755 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-30 22:40:14.179  5755  5755 D SprintDMHelper: simOperator: 
,11-30 22:40:14.179  5755  5755 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-30 22:40:14.191  4995  5767 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-30 22:40:14.196   930  3137 I ActivityManager: Killing 5242:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-30 22:40:14.225   930  3137 I ActivityManager: Start proc 5768:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-30 22:40:14.247  4995  4995 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-30 22:40:14.247   930  2936 D wifi    : In wifi stop Hal
,11-30 22:40:14.247   930  2936 D wifi    : halHandle = 0x7f92e51900, mVM = 0x7faf48d140, mCls = 0x100a02
11-30 22:40:14.247   930  3426 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-30 22:40:14.247   930  3426 D WifiHAL : Got a signal to exit!!!
11-30 22:40:14.247   930  3426 I WifiHAL : Exit wifi_event_loop
11-30 22:40:14.248   930  2936 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-30 22:40:14.248   930  2936 E WifiHAL : Event processing terminated
11-30 22:40:14.248   930  2936 D wifi    : In wifi cleaned up handler
11-30 22:40:14.248   930  2936 I WifiHAL : Internal cleanup completed
11-30 22:40:14.249  4026  4198 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-30 22:40:14.261  5768  5768 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-30 22:40:14.269   930  3401 I ActivityManager: Killing 3882:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-30 22:40:14.270   930  3426 D wifi    : set interface wlan0 flags (DOWN)
,11-30 22:40:14.271   930  2936 D WifiNative-HAL: HAL event thread stopped successfully
,11-30 22:40:14.459  5601  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 22:40:14.459  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 22:40:14.459  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 22:40:14.459  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-30 22:40:14.459  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 22:40:14.459  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-30 22:40:14.459  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-30 22:40:14.459  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-30 22:40:14.459  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-30 22:40:14.467  5601  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-30 22:40:14.471   930  3401 D WifiService: setWifiEnabled: true pid=5601, uid=10077
11-30 22:40:14.471   930  3401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 22:40:14.474  5601  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-30 22:40:14.478   509   924 D SoftapController: Softap fwReload - Ok
,11-30 22:40:14.481   930   947 D Tethering: InitialState.processMessage what=4
,11-30 22:40:14.483   509   924 D CommandListener: Setting iface cfg
,11-30 22:40:14.483   509   924 D CommandListener: Trying to bring down wlan0
,11-30 22:40:14.484   509   924 D CommandListener: Clearing all IP addresses on wlan0
,11-30 22:40:14.485   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-30 22:40:14.488   930  2936 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-30 22:40:14.977   930  3826 D WifiService: setWifiEnabled: true pid=5601, uid=10077
11-30 22:40:14.980   930  3826 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 22:40:15.101   930  2936 D wifi    : set interface wlan0 flags (UP)
11-30 22:40:15.103   930  2936 I WifiHAL : Initializing wifi
11-30 22:40:15.103   930  2936 I WifiHAL : Creating socket
,11-30 22:40:15.105   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-30 22:40:15.109   930  2936 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-30 22:40:15.109   930  2936 D wifi    : Did set static halHandle = 0x7f92e51900
,11-30 22:40:15.109   930  2936 D wifi    : halHandle = 0x7f92e51900, mVM = 0x7faf48d140, mCls = 0x2018ba
11-30 22:40:15.110   930  2936 D wifi    : array field set
11-30 22:40:15.110   930  2936 I WifiNative-HAL: interface[0] = wlan0
11-30 22:40:15.112   930  5784 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547925334272
11-30 22:40:15.112   930  5784 D wifi    : waitForHalEvents called, vm = 0x7faf48d140, obj = 0x2018ba, env = 0x7f9346a480
,11-30 22:40:15.115   930  2936 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-30 22:40:15.118   930  2936 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-30 22:40:15.192  5785  5785 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-30 22:40:15.260  5785  5785 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-30 22:40:15.274  5785  5785 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-30 22:40:15.275  5785  5785 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-30 22:40:15.485   930  3402 D WifiService: setWifiEnabled: true pid=5601, uid=10077
,11-30 22:40:15.485   930  3402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 22:40:15.988   930  3401 D WifiService: setWifiEnabled: true pid=5601, uid=10077
,11-30 22:40:15.989   930  3401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 22:40:16.130   930  2936 D WifiConfigStore: Loading config and enabling all networks 
,11-30 22:40:16.174   930  2936 D WifiConfigStore: loaded 0 passpoint configs
,11-30 22:40:16.175   930  2936 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-30 22:40:16.176   930  2936 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-30 22:40:16.177   930  2936 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-30 22:40:16.178   930  2936 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-30 22:40:16.179   930  2936 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-30 22:40:16.180   930  2936 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-30 22:40:16.181   930  2936 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-30 22:40:16.181   930  2936 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-30 22:40:16.181   930  2936 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-30 22:40:16.181   930  2936 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-30 22:40:16.181   930  2936 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-30 22:40:16.181   930  2936 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-30 22:40:16.186   930  2936 D WifiNative-HAL: Setting external_sim to 1
,11-30 22:40:16.186  4995  4995 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-30 22:40:16.186   930  2936 D wifi    : setting dfs flag to true, 0x7f93cca4a0
,11-30 22:40:16.188   930  2936 D WifiStateMachine: Setting OUI to DA-A1-19
11-30 22:40:16.188   930  2936 D wifi    : setting scan oui 0x7f93cca4a0
11-30 22:40:16.188   930  2936 D WifiHAL : Sending mac address OUI
,11-30 22:40:16.193   930  2936 E native  : do suspend false
,11-30 22:40:16.202   930  2936 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-30 22:40:16.202   509   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-30 22:40:16.203   930   930 D RttService: SCAN_AVAILABLE : 3
11-30 22:40:16.203   930  3066 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-30 22:40:16.204   509   924 D CommandListener: Setting iface cfg
,11-30 22:40:16.209   930  2935 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-30 22:40:16.209   930  2935 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-30 22:40:16.225   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=215065 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-30 22:40:16.225   930  2935 D WifiNative-HAL: p2pGetDeviceAddress
11-30 22:40:16.225   930  2935 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-30 22:40:16.501  5601  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 22:40:16.501  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 22:40:16.501  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 22:40:16.501  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 22:40:16.501  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 22:40:16.501  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-30 22:40:16.501  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-30 22:40:16.501  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-30 22:40:16.501  5601  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-30 22:40:16.508  5601  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-30 22:40:16.511  5601  5648 D BluetoothAdapter: enable(): BT is already enabled..!
,11-30 22:40:16.512   930  3137 D WifiService: setWifiEnabled: true pid=5601, uid=10077
,11-30 22:40:16.512   930  3137 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-30 22:40:16.513  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-30 22:40:16.514  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 22:40:16.514  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-30 22:40:16.514  5601  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@409657c removed from the list
,11-30 22:40:16.514  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-30 22:40:16.514  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed42e05 removed from the list
11-30 22:40:16.514  5601  5648 D io.jxcore.node.ConnectivityMonitor: stop
11-30 22:40:16.517  5601  5648 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-30 22:40:16.519  5601  5648 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-30 22:40:16.521  5601  5648 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-30 22:40:16.528  5601  5648 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-30 22:40:16.533  5601  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-30 22:40:16.537  5601  5648 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-30 22:40:16.538  5601  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-30 22:40:16.538  5601  5648 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-30 22:40:16.539  5601  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-30 22:40:16.541  5601  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-30 22:40:16.541  5601  5648 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6877401 Bundle[{}]
11-30 22:40:16.542  5601  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-30 22:40:16.542  5601  5648 I io.jxcore.node.LifeCycleMonitor: start: OK
11-30 22:40:16.542  5601  5648 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-30 22:40:16.543  5601  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-30 22:40:16.543  5601  5648 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-30 22:40:16.544  5601  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-30 22:40:16.544  5601  5648 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-30 22:40:16.544  5601  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-30 22:40:16.544  5601  5648 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-30 22:40:16.545  5601  5648 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-30 22:40:16.545  5601  5648 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-30 22:40:16.548  5601  5648 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-30 22:40:16.551  5601  5648 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-30 22:40:16.552  5601  5648 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-30 22:40:16.552  5601  5648 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-30 22:40:16.553  5601  5648 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-30 22:40:16.553  5601  5648 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
11-30 22:40:16.554  5601  5648 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-30 22:40:16.555  5601  5648 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,11-30 22:40:17.560  5601  5648 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-30 22:40:17.562  5601  5648 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-30 22:40:17.565  5601  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
11-30 22:40:17.568  5601  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-30 22:40:17.570  5601  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-30 22:40:17.571  5601  5648 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
11-30 22:40:17.573  5601  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,11-30 22:40:17.574  5601  5648 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-30 22:40:17.574  5601  5648 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
11-30 22:40:17.575  5601  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-30 22:40:17.577  5601  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-30 22:40:17.578  5601  5648 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-30 22:40:17.579  5601  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-30 22:40:17.580  5601  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bbf88b added. We now have 3 listener(s)
,11-30 22:40:17.582  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 22:40:17.582  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 22:40:17.582  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-30 22:40:17.582  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-30 22:40:17.583  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d455d68 added. We now have 3 listener(s)
11-30 22:40:17.583  5601  5648 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-30 22:40:17.584  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-30 22:40:17.592  5601  5648 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-30 22:40:17.593  5601  5648 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-30 22:40:17.594  5601  5648 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-30 22:40:17.594  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-30 22:40:17.594  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.594  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.594  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.594  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 22:40:17.594  5601  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 22:40:17.594  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-30 22:40:17.595  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 22:40:17.595  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-30 22:40:17.599  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 22:40:17.601  5601  5791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-30 22:40:17.601  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-30 22:40:17.601  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-30 22:40:17.601  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 22:40:17.602  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 22:40:17.602  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-30 22:40:17.602  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 22:40:17.602  5601  5791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 22:40:17.602  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 22:40:17.603  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 22:40:17.601  5719  5719 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[30680]" dev="sockfs" ino=30680 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 22:40:17.605  5601  5791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 22:40:17.601  5719  5719 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[30680]" dev="sockfs" ino=30680 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-30 22:40:17.608  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-30 22:40:17.608  5601  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 22:40:17.608  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-30 22:40:17.613  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:17.613  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 22:40:17.614  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 22:40:17.614  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 22:40:17.614  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-30 22:40:17.617  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.617  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.617  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 22:40:17.617  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,11-30 22:40:17.617  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 22:40:17.617  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-30 22:40:17.617  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:17.617  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:17.618  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:17.618  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-30 22:40:17.618  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:17.618  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.618  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.618  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:17.620  5601  5648 D BluetoothAdapter: STATE_ON
,11-30 22:40:17.625  5684  5719 D BtGatt.GattService: registerClient() - UUID=59aebc20-d6a8-4b11-9c8f-e2964e8ed823
,11-30 22:40:17.625  5684  5700 D BtGatt.GattService: onClientRegistered() - UUID=59aebc20-d6a8-4b11-9c8f-e2964e8ed823, clientIf=5
,11-30 22:40:17.626  5601  5612 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-30 22:40:17.629  5684  5702 D BtGatt.AdvertiseManager: message : 0
,11-30 22:40:17.631  5684  5702 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 22:40:17.642  5684  5700 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 22:40:17.648  5684  5700 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 22:40:17.649  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.649  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:17.649  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 22:40:17.649  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.649  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.650  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.650  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:17.650  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.650  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-30 22:40:17.652  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-30 22:40:17.652  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:17.654  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.654  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.654  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:17.654  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 22:40:17.654  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 22:40:17.654  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:17.654  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 22:40:17.654  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 22:40:17.655  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:17.655  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:17.655  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 22:40:17.655  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 22:40:17.655  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 22:40:17.655  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:17.655  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 22:40:17.655  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:17.655  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 22:40:17.655  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 22:40:17.658  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 22:40:17.658  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 22:40:17.658  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:17.658  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:17.659  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 22:40:18.159  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-30 22:40:18.160  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-30 22:40:18.160  5601  5601 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-30 22:40:19.381  5785  5785 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-30 22:40:19.387  5785  5785 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-30 22:40:19.391  5785  5785 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-30 22:40:19.445   930  2936 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-30 22:40:19.446   930  2936 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-30 22:40:19.447   930  2936 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-30 22:40:19.458   930  2936 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-30 22:40:19.489   930  2936 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-30 22:40:19.495  5785  5785 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-30 22:40:19.916  5785  5785 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-30 22:40:19.957  5785  5785 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-30 22:40:19.958  5785  5785 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-30 22:40:19.966   930  2936 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-30 22:40:19.966   930  2936 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-30 22:40:19.966   930  2950 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-30 22:40:19.983   930  2936 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-30 22:40:19.993   509   924 D CommandListener: Setting iface cfg
,11-30 22:40:19.998   930  2936 D WifiStateMachine: Start Dhcp Watchdog 2
,11-30 22:40:20.003   930  5796 D DhcpClient: Receive thread started
,11-30 22:40:20.008   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:40:20.008   930  2936 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-30 22:40:20.008   930  2950 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-30 22:40:20.088   930  2936 E native  : do suspend false
,11-30 22:40:20.098   930  5795 D DhcpClient: Broadcasting DHCPDISCOVER
,11-30 22:40:20.112   930  5796 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172622, domain null
,11-30 22:40:20.113   930  5795 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172622 seconds
,11-30 22:40:20.114   930  5795 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-30 22:40:20.127   930  5796 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-30 22:40:20.128   930  5795 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-30 22:40:20.130   509   924 D CommandListener: Setting iface cfg
,11-30 22:40:20.134   930  2936 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-30 22:40:20.139   930  5795 D DhcpClient: Scheduling renewal in 86399s
,11-30 22:40:20.148   930  2936 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-30 22:40:20.148   930  2936 D WifiConfigStore: No blacklist allowed without epno enabled
11-30 22:40:20.150   930  2950 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-30 22:40:20.151   930  2950 D ConnectivityService: Adding iface wlan0 to network 101
11-30 22:40:20.158   930  2936 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-30 22:40:20.203   930  2950 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-30 22:40:20.203   930  2950 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-30 22:40:20.205   930  2950 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-30 22:40:20.206   930  2950 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-30 22:40:20.208   930  2950 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-30 22:40:20.218   930  2950 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:40:20.222   930  2950 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-30 22:40:20.223   930  2950 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-30 22:40:20.223   930  2950 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-30 22:40:20.223   930  2936 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-30 22:40:20.223   930  2950 D ConnectivityService:    accepting network in place of null
11-30 22:40:20.223   930  2936 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-30 22:40:20.223   930  2950 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-30 22:40:20.236   930  5794 D NetlinkSocketObserver: NeighborEvent{elapsedMs=219077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-30 22:40:20.246   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 22:40:20.269   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 22:40:20.272   930  2950 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-30 22:40:20.272   930  2950 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-30 22:40:20.273  3743  3880 W QCNEJ   : |CORE| network available: 101
11-30 22:40:20.273   930  2950 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-30 22:40:20.275  3743  3880 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-30 22:40:20.277  3743  3880 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-30 22:40:20.277  3743  3880 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-30 22:40:20.278   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-30 22:40:20.288  5029  5052 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-30 22:40:20.288  5029  5052 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-30 22:40:20.289  5029  5052 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-30 22:40:20.289  5029  5052 E SarControlService: no key has been found,reset the power
11-30 22:40:20.289  5029  5064 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-30 22:40:20.289  5029  5064 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-30 22:40:20.289  5029  5064 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-30 22:40:20.290  5054  5054 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 22:40:20.290  5054  5054 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-30 22:40:20.291  5029  5064 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-30 22:40:20.291  5029  5064 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-30 22:40:20.291  5029  5064 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-30 22:40:20.291  5054  5054 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 22:40:20.292  5054  5054 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-30 22:40:20.295  3709  3709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-30 22:40:20.297  5054  5068 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4098cd HexData = [00000000ec03000000000000ffffffff]
,11-30 22:40:20.297  5054  5068 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 22:40:20.297  5054  5068 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-30 22:40:20.299  5054  5068 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4098cd HexData = [00000000ed03000000000000ffffffff]
11-30 22:40:20.299  5054  5068 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 22:40:20.299  5054  5068 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-30 22:40:20.300  5054  5054 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 22:40:20.300  5029  5039 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-30 22:40:20.300  5054  5054 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 22:40:20.300  5029  5040 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-30 22:40:20.301  3709  3709 D SystemUpdateService: onCreate
11-30 22:40:20.302  3948  3948 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-30 22:40:20.307   930  5793 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:814::200e
11-30 22:40:20.309  3709  3709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-30 22:40:20.320  3709  3709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-30 22:40:20.325  3709  5380 I iu.UploadsManager: num queued entries: 0
,11-30 22:40:20.325  3709  5380 I iu.UploadsManager: num updated entries: 0
11-30 22:40:20.327  3709  5806 I SystemUpdateService: active receiver: enabled
,11-30 22:40:20.330  3709  3709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-30 22:40:20.331  3709  3709 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-30 22:40:20.334  5755  5755 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-30 22:40:20.337  5755  5755 D SprintDMHelper: simOperator: 
11-30 22:40:20.337  5755  5755 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-30 22:40:20.361  3709  5380 I iu.SyncManager: NEXT; no task
,11-30 22:40:20.362  3709  5806 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-30 22:40:20.367   930  5793 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 30 Nov 2016 21:40:20 GMT], X-Android-Received-Millis=[1480542020367], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480542020339]}
,11-30 22:40:20.368   930  2950 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-30 22:40:20.368   930  2950 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-30 22:40:20.368   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:40:20.369   930  2950 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-30 22:40:20.378  3709  5806 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-30 22:40:20.378  3709  5806 I SystemUpdateService: now status is 0 (complete)
,11-30 22:40:20.378  3709  5806 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-30 22:40:20.378  3709  5806 I SystemUpdateService: file has been verified
11-30 22:40:20.379  3709  5806 I SystemUpdateService: OTA package size = 21989297
,11-30 22:40:20.384  3709  5806 I SystemUpdateService: showing system update notification
,11-30 22:40:20.394   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-30 22:40:20.398  3709  3709 D SystemUpdateService: onDestroy
,11-30 22:40:20.456  4995  5811 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-30 22:40:20.629   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-30 22:40:20.629   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-30 22:40:21.156  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-30 22:40:21.157  5601  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-30 22:40:21.157  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 22:40:21.157  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-30 22:40:21.157  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 22:40:21.158  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 22:40:21.158  5601  5791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 22:40:21.158  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-30 22:40:21.158  5601  5791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 22:40:21.158  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 22:40:21.158  5601  5791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-30 22:40:21.158  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-30 22:40:21.159  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 22:40:21.159  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-30 22:40:21.159  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.159  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 22:40:21.159  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 22:40:21.160  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:21.160  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.160  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.160  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.162  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:21.163  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 22:40:21.166  5601  5648 D BluetoothAdapter: STATE_ON
,11-30 22:40:21.166  5601  5648 D BluetoothLeScanner: could not find callback wrapper
11-30 22:40:21.166  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 22:40:21.167  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.167  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.167  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:21.167  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 22:40:21.167  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.170  5684  5702 D BtGatt.AdvertiseManager: message : 1
11-30 22:40:21.172  5684  5702 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 22:40:21.183  5684  5700 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-30 22:40:21.183  5684  5700 D BtGatt.GattService: Client app is not null!
,11-30 22:40:21.186  5684  5719 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-30 22:40:21.186  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-30 22:40:21.187  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.187  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 22:40:21.187  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.187  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:21.187  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.187  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 22:40:21.187  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 22:40:21.189  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-30 22:40:21.190  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.191  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:21.192  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 22:40:21.192  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:21.192  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.192  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-30 22:40:21.192  5601  5601 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 22:40:21.193  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 22:40:21.193  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 22:40:21.193  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 22:40:21.193  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 22:40:21.193  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:21.193  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.193  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 22:40:21.193  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 22:40:21.194  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.194  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.194  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.194  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 22:40:21.194  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.194  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.197  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.197  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.197  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.198  5601  5648 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-30 22:40:21.198  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 22:40:21.200  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 22:40:21.200  5601  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-30 22:40:21.200  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-30 22:40:21.200  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 22:40:21.200  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-30 22:40:21.202  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-30 22:40:21.206  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-30 22:40:21.207  5601  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 22:40:21.207  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-30 22:40:21.212  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:21.212  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 22:40:21.213  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-30 22:40:21.213  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 22:40:21.213  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-30 22:40:21.217  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-30 22:40:21.221  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-30 22:40:21.221  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.221  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-30 22:40:21.222  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-30 22:40:21.222  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-30 22:40:21.222  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-30 22:40:21.223  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:21.224  5601  5648 D BluetoothAdapter: STATE_ON
,11-30 22:40:21.227  5684  5695 D BtGatt.GattService: registerClient() - UUID=5566b0fb-ae22-4e3b-8d6e-a54345876221
11-30 22:40:21.228  5684  5700 D BtGatt.GattService: onClientRegistered() - UUID=5566b0fb-ae22-4e3b-8d6e-a54345876221, clientIf=5
,11-30 22:40:21.228  5601  5612 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-30 22:40:21.229  5684  5720 D BtGatt.GattService: start scan with filters
,11-30 22:40:21.233  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-30 22:40:21.234  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.234  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-30 22:40:21.233  5684  5703 D BtGatt.ScanManager: handling starting scan
11-30 22:40:21.234  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:21.235  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-30 22:40:21.235  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:21.235  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.235  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-30 22:40:21.235  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 22:40:21.236  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.236  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.236  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.236  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.237  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 22:40:21.237  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.237  5684  5703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5c872da
11-30 22:40:21.239  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.240  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-30 22:40:21.240  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.240  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:21.240  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 22:40:21.243  5684  5700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-30 22:40:21.243  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 22:40:21.243  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.243  5684  5703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-30 22:40:21.243  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.243  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:21.243  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-30 22:40:21.249  5684  5700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-30 22:40:21.249  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 22:40:21.249  5684  5703 D BtGatt.ScanManager: Starting BLE batch scan
11-30 22:40:21.250  5684  5703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-30 22:40:21.259  5684  5700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-30 22:40:21.259  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 22:40:21.264  5684  5700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-30 22:40:21.264  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 22:40:21.273   930  2950 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-30 22:40:21.744  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-30 22:40:21.745  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-30 22:40:21.745  5601  5601 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-30 22:40:22.551   930  2936 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 14 -> obsolete
,11-30 22:40:23.027   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:40:24.242  5601  5648 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
11-30 22:40:24.243  5601  5648 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-30 22:40:24.243  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-30 22:40:24.244  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:24.244  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.244  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.244  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-30 22:40:24.244  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-30 22:40:24.244  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-30 22:40:24.244  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-30 22:40:24.244  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-30 22:40:24.244  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-30 22:40:24.244  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-30 22:40:24.244  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-30 22:40:24.244  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-30 22:40:24.244  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:24.245  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-30 22:40:24.245  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.245  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:24.245  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 22:40:24.245  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 22:40:24.246  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:24.246  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.246  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:24.250  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:24.251  5684  5720 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-30 22:40:24.252  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-30 22:40:24.254  5684  5703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-30 22:40:24.254  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:24.255  5684  5719 D BtGatt.GattService: stopScan() - queue size =1
11-30 22:40:24.257  5684  5695 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 22:40:24.258  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-30 22:40:24.258  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.259  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-30 22:40:24.259  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.260  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 22:40:24.261  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.261  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.261  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-30 22:40:24.261  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-30 22:40:24.261  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-30 22:40:24.261  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-30 22:40:24.261  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.261  5684  5684 D BtGatt.ScanManager: awakened up at time 223102
11-30 22:40:24.262  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:24.266  5684  5720 D BtGatt.GattService: registerClient() - UUID=f8f88422-ca8d-4ec4-8778-6e40abe80855
11-30 22:40:24.267  5684  5700 D BtGatt.GattService: onClientRegistered() - UUID=f8f88422-ca8d-4ec4-8778-6e40abe80855, clientIf=5
,11-30 22:40:24.267  5601  5611 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-30 22:40:24.270  5684  5694 D BtGatt.GattService: start scan with filters
,11-30 22:40:24.274  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-30 22:40:24.274  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:24.274  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-30 22:40:24.274  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.275  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.275  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:24.275  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-30 22:40:24.275  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.275  5601  5648 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 22:40:24.275  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-30 22:40:24.275  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 22:40:24.275  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-30 22:40:24.275  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 22:40:24.275  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.275  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.276  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 22:40:24.276  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 22:40:24.276  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 22:40:24.276  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 22:40:24.276  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 22:40:24.277  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-30 22:40:24.277  5601  5819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 22:40:24.278  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 22:40:24.278  5601  5648 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-30 22:40:24.278  5684  5700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-30 22:40:24.278  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 22:40:24.279  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 22:40:24.279  5684  5700 D BtGatt.GattService: current time is 223119688580
11-30 22:40:24.279  5601  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 22:40:24.278  5719  5719 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33139]" dev="sockfs" ino=33139 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 22:40:24.278  5719  5719 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33139]" dev="sockfs" ino=33139 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 22:40:24.281  5684  5700 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -96, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -83, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -88, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -87, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-30 22:40:24.282  5684  5700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-30 22:40:24.283  5684  5700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
11-30 22:40:24.284  5684  5700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-30 22:40:24.284  5684  5700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-30 22:40:24.284  5684  5700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-30 22:40:24.284  5601  5819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 22:40:24.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.,le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.287  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 22:40:24.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 22:40:24.287  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-30 22:40:24.287  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-30 22:40:24.287  5601  5648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:24.287  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:24.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.287  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 22:40:24.288  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 22:40:24.288  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.288  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.288  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.288  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:24.289  5684  5700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-30 22:40:24.290  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 22:40:24.290  5684  5703 D BtGatt.ScanManager: stopping BLe Batch
11-30 22:40:24.292  5684  5695 D BtGatt.GattService: registerClient() - UUID=43d4cc6e-d6b8-4587-b256-7c87a4b730e2
11-30 22:40:24.293  5684  5700 D BtGatt.GattService: onClientRegistered() - UUID=43d4cc6e-d6b8-4587-b256-7c87a4b730e2, ,clientIf=6
11-30 22:40:24.293  5601  5612 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-30 22:40:24.294  5684  5702 D BtGatt.AdvertiseManager: message : 0
11-30 22:40:24.295  5684  5700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-30 22:40:24.295  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 22:40:24.296  5684  5703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-30 22:40:24.297  5684  5702 D BtGatt.AdvertiseManager: starting multi advertising
11-30 22:40:24.301  5684  5700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-30 22:40:24.301  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 22:40:24.304  5684  5703 D BtGatt.ScanManager: handling starting scan
11-30 22:40:24.309  5684  5700 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
11-30 22:40:24.314  5684  5700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-30 22:40:24.314  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 22:40:24.314  5684  5703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-30 22:40:24.318  5684  5700 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
11-30 22:40:24.318  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.319  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.319  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 22:40:24.319  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.319  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.319  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.319  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.319  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.319  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.319  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.319  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.320  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-30 22:40:24.320  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-30 22:40:24.320  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 22:40:24.321  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 22:40:24.321  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.322  5684  5700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-30 22:40:24.322  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 22:40:24.323  5684  5703 D BtGatt.ScanManager: Starting BLE batch scan
11-30 22:40:24.323  5684  5703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-30 22:40:24.323  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.324  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.324  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:24.324  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-30 22:40:24.324  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.324  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:24.324  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 22:40:24.324  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.324  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.324  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:24.325  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.325  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-30 22:40:24.325  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-30 22:40:24.325  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.325  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.325  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.325  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.325  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.327  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.327  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-30 22:40:24.327  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.328  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:24.328  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-30 22:40:24.331  5684  5700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-30 22:40:24.331  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 22:40:24.336  5684  5700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-30 22:40:24.336  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 22:40:24.829  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-30 22:40:24.829  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-30 22:40:24.829  5601  5601 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-30 22:40:26.054   930  2950 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 59
,11-30 22:40:27.327  5601  5648 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
11-30 22:40:27.328  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-30 22:40:27.328  5601  5648 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 22:40:27.328  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 22:40:27.328  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 22:40:27.329  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-30 22:40:27.329  5601  5819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 22:40:27.329  5601  5819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-30 22:40:27.329  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 22:40:27.329  5601  5819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-30 22:40:27.329  5601  5648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 22:40:27.330  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-30 22:40:27.330  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 22:40:27.330  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-30 22:40:27.330  5601  5648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bbf88b removed from the list
11-30 22:40:27.330  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-30 22:40:27.330  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 22:40:27.330  5601  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 22:40:27.331  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:27.331  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 22:40:27.331  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-30 22:40:27.331  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.331  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.332  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.332  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-30 22:40:27.333  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:27.336  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:27.337  5684  5719 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-30 22:40:27.337  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-30 22:40:27.338  5684  5703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-30 22:40:27.339  5601  5648 D BluetoothAdapter: STATE_ON
11-30 22:40:27.341  5684  5695 D BtGatt.GattService: stopScan() - queue size =1
11-30 22:40:27.343  5684  5694 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 22:40:27.343  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 22:40:27.344  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.344  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-30 22:40:27.344  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.344  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.345  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:27.345  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 22:40:27.345  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.347  5684  5702 D BtGatt.AdvertiseManager: message : 1
11-30 22:40:27.347  5684  5684 D BtGatt.ScanManager: awakened up at time 226188
,11-30 22:40:27.353  5684  5702 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-30 22:40:27.370  5684  5700 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-30 22:40:27.370  5684  5700 D BtGatt.GattService: Client app is not null!
,11-30 22:40:27.371  5684  5695 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-30 22:40:27.372  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 22:40:27.372  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.372  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-30 22:40:27.372  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:27.372  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.372  5601  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.372  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 22:40:27.373  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 22:40:27.373  5601  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 22:40:27.374  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 22:40:27.376  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.376  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 22:40:27.376  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.376  5601  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 22:40:27.377  5601  5648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d455d68 removed from the list
11-30 22:40:27.377  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 22:40:27.377  5601  5648 D io.jxcore.node.ConnectivityMonitor: stop
11-30 22:40:27.377  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-30 22:40:27.377  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:27.377  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 22:40:27.377  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 22:40:27.377  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-30 22:40:27.377  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:27.377  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 22:40:27.377  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-30 22:40:27.378  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 22:40:27.378  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 22:40:27.378  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 22:40:27.378  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 22:40:27.378  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 22:40:27.378  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 22:40:27.378  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 22:40:27.378  5601  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-30 22:40:27.378  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 22:40:27.378  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-30 22:40:27.378  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 22:40:27.379  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-30 22:40:27.379  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-30 22:40:27.379  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-30 22:40:27.379  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,11-30 22:40:27.380  5601  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-30 22:40:27.381  5601  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-30 22:40:27.382  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 22:40:27.382  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:27.382  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 22:40:27.383  5601  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,11-30 22:40:27.384  5684  5700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-30 22:40:27.384  5601  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-30 22:40:27.384  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 22:40:27.384  5684  5700 D BtGatt.GattService: current time is 226225151844
11-30 22:40:27.385  5601  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-30 22:40:27.386  5601  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-30 22:40:27.387  5601  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,11-30 22:40:27.386  5684  5700 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -83, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -83, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -82, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -85, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -82, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-30 22:40:27.388  5684  5700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-30 22:40:27.388  5684  5700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-30 22:40:27.388  5601  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,11-30 22:40:27.388  5684  5700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-30 22:40:27.389  5684  5700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-30 22:40:27.389  5684  5700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-30 22:40:27.389  5601  5648 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
11-30 22:40:27.389  5684  5700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-30 22:40:27.397  5684  5700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-30 22:40:27.397  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 22:40:27.398  5684  5703 D BtGatt.ScanManager: stopping BLe Batch
,11-30 22:40:27.404  5684  5700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-30 22:40:27.405  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 22:40:27.405  5684  5703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-30 22:40:27.411  5684  5700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-30 22:40:27.411  5684  5700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 22:40:27.879  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-30 22:40:28.225   930  2950 D ConnectivityService: handlePromptUnvalidated 101
,11-30 22:40:29.067   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:40:29.074   930  2950 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-30 22:40:29.394  5601  5648 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-30 22:40:29.526  5601  5821 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-30 22:40:29.526  5601  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 22:40:30.314  5601  5821 W !!      : call onHalfStreamCopied
,11-30 22:40:30.314  5601  5821 I testCopyDataAndClose: closing input stream
,11-30 22:40:30.630   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:31.084  5601  5821 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-30 22:40:31.084  5601  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 22:40:31.084  5601  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-30 22:40:31.084  5601  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 22:40:31.084  5601  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-30 22:40:31.084  5601  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-30 22:40:31.084  5601  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-30 22:40:31.084  5601  5821 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-30 22:40:31.084  5601  5821 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-30 22:40:31.085  5601  5821 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-30 22:40:31.085  5601  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-30 22:40:31.222   930  2936 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,11-30 22:40:31.631   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:32.633   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:33.634   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:34.635   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:35.462  5601  5648 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-30 22:40:35.540  5601  5822 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-30 22:40:35.540  5601  5822 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 22:40:35.635   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-30 22:40:37.166  5601  5822 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 193, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-30 22:40:37.166  5601  5822 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 22:40:37.166  5601  5822 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-30 22:40:37.166  5601  5822 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 22:40:37.166  5601  5822 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-30 22:40:37.166  5601  5822 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-30 22:40:37.166  5601  5822 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-30 22:40:37.166  5601  5822 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-30 22:40:37.166  5601  5822 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-30 22:40:37.166  5601  5822 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-30 22:40:37.166  5601  5822 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-30 22:40:38.145   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:40:40.637   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:41.167   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:40:41.289  5601  5648 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-30 22:40:41.292  5601  5823 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: My test thread name). Connection data: Peer properties: [null null].
11-30 22:40:41.292  5601  5823 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 22:40:41.292  5601  5823 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 195, thread name: My test thread name). Connection data: Peer properties: [null null].
11-30 22:40:41.292  5601  5823 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 22:40:41.292  5601  5823 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-30 22:40:41.292  5601  5823 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 22:40:41.293  5601  5823 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-30 22:40:41.293  5601  5823 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-30 22:40:41.293  5601  5823 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-30 22:40:41.293  5601  5823 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-30 22:40:41.294  5601  5823 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-30 22:40:41.294  5601  5823 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: My test thread name). Connection data: Peer properties: [null null].
11-30 22:40:41.294  5601  5823 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-30 22:40:41.295  5601  5648 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-30 22:40:41.296  5601  5648 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-30 22:40:41.297  5601  5648 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-30 22:40:41.299  5601  5824 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 199, name: My test thread name). Connection data: Peer properties: [null null].
11-30 22:40:41.299  5601  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 22:40:41.299  5601  5824 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 199, thread name: My test thread name): Test exception.
11-30 22:40:41.300  5601  5824 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 199, name: My test thread name). Connection data: Peer properties: [null null].
11-30 22:40:41.300  5601  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-30 22:40:41.300  5601  5824 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-30 22:40:41.300  5601  5824 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 199, name: My test thread name). Connection data: Peer properties: [null null].
11-30 22:40:41.300  5601  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-30 22:40:41.303  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG UnitTest_app: 'Running unit tests'
11-30 22:40:41.303  5601  5648 I jxcore-log: 
11-30 22:40:41.304  5601  5648 I jxcore-log: *Native tests were executed*
11-30 22:40:41.304  5601  5648 I jxcore-log: 
11-30 22:40:41.304  5601  5648 I jxcore-log: Total number of executed tests:  81
11-30 22:40:41.304  5601  5648 I jxcore-log: 
,11-30 22:40:41.304  5601  5648 I jxcore-log: Number of passed tests:  79
11-30 22:40:41.304  5601  5648 I jxcore-log: 
11-30 22:40:41.304  5601  5648 I jxcore-log: Number of failed tests:  0
11-30 22:40:41.304  5601  5648 I jxcore-log: 
11-30 22:40:41.304  5601  5648 I jxcore-log: Number of ignored tests:  2
11-30 22:40:41.304  5601  5648 I jxcore-log: 
11-30 22:40:41.304  5601  5648 I jxcore-log: Total duration:  36376
11-30 22:40:41.304  5601  5648 I jxcore-log: 
,11-30 22:40:41.306  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-30 22:40:41.306  5601  5648 I jxcore-log: 
11-30 22:40:41.310  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 22:40:41.310  5601  5648 I jxcore-log: 
11-30 22:40:41.310  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 22:40:41.310  5601  5648 I jxcore-log: 
11-30 22:40:41.311  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 22:40:41.311  5601  5648 I jxcore-log: 
11-30 22:40:41.312  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 22:40:41.312  5601  5648 I jxcore-log: 
,11-30 22:40:41.313  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 22:40:41.313  5601  5648 I jxcore-log: 
11-30 22:40:41.314  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 22:40:41.314  5601  5648 I jxcore-log: 
,11-30 22:40:41.314  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 22:40:41.314  5601  5648 I jxcore-log: 
11-30 22:40:41.314  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 22:40:41.314  5601  5648 I jxcore-log: 
11-30 22:40:41.314  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 22:40:41.314  5601  5648 I jxcore-log: 
11-30 22:40:41.315  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 22:40:41.315  5601  5648 I jxcore-log: 
11-30 22:40:41.315  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 22:40:41.315  5601  5648 I jxcore-log: 
,11-30 22:40:41.315  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 22:40:41.315  5601  5648 I jxcore-log: 
11-30 22:40:41.315  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 22:40:41.315  5601  5648 I jxcore-log: 
11-30 22:40:41.316  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-30 22:40:41.316  5601  5648 I jxcore-log: 
11-30 22:40:41.316  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 22:40:41.316  5601  5648 I jxcore-log: 
11-30 22:40:41.316  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 22:40:41.316  5601  5648 I jxcore-log: 
11-30 22:40:41.316  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 22:40:41.316  5601  5648 I jxcore-log: 
11-30 22:40:41.317  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-30 22:40:41.317  5601  5648 I jxcore-log: 
11-30 22:40:41.317  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 22:40:41.317  5601  5648 I jxcore-log: 
11-30 22:40:41.317  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 22:40:41.317  5601  5648 I jxcore-log: 
11-30 22:40:41.317  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 22:40:41.317  5601  5648 I jxcore-log: 
11-30 22:40:41.317  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 22:40:41.317  5601  5648 I jxcore-log: 
,11-30 22:40:41.318  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 22:40:41.318  5601  5648 I jxcore-log: 
11-30 22:40:41.318  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-30 22:40:41.318  5601  5648 I jxcore-log: 
11-30 22:40:41.318  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 22:40:41.318  5601  5648 I jxcore-log: 
11-30 22:40:41.318  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-30 22:40:41.318  5601  5648 I jxcore-log: 
11-30 22:40:41.319  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 22:40:41.319  5601  5648 I jxcore-log: 
11-30 22:40:41.319  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 22:40:41.319  5601  5648 I jxcore-log: 
,11-30 22:40:41.319  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 22:40:41.319  5601  5648 I jxcore-log: 
11-30 22:40:41.321  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 22:40:41.321  5601  5648 I jxcore-log: 
11-30 22:40:41.321  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-30 22:40:41.321  5601  5648 I jxcore-log: 
11-30 22:40:41.321  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 22:40:41.321  5601  5648 I jxcore-log: 
,11-30 22:40:41.322  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 22:40:41.322  5601  5648 I jxcore-log: 
11-30 22:40:41.322  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-30 22:40:41.322  5601  5648 I jxcore-log: 
11-30 22:40:41.322  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 22:40:41.322  5601  5648 I jxcore-log: 
11-30 22:40:41.322  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 22:40:41.322  5601  5648 I jxcore-log: 
11-30 22:40:41.322  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-30 22:40:41.322  5601  5648 I jxcore-log: 
11-30 22:40:41.323  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 22:40:41.323  5601  5648 I jxcore-log: 
,11-30 22:40:41.326  5601  5601 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-30 22:40:41.326  5601  5601 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-30 22:40:41.327  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-30 22:40:41.327  5601  5648 I jxcore-log: 
11-30 22:40:41.328  5601  5648 I jxcore-log: 2016-11-30 21:40:41 - WARN testUtils: 'myNameCallback not set!'
11-30 22:40:41.328  5601  5648 I jxcore-log: 
,11-30 22:40:41.638   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:42.639   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:43.461  5601  5648 I jxcore-log: 2016-11-30 21:40:43 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-30 22:40:43.461  5601  5648 I jxcore-log: 
,11-30 22:40:43.463  5601  5648 I jxcore-log: 2016-11-30 21:40:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-30 22:40:43.463  5601  5648 I jxcore-log: 
,11-30 22:40:43.641   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:43.672  3649  3854 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-30 22:40:43.672  3649  3854 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-30 22:40:43.707  3572  3572 I ConfigService: onCreate
,11-30 22:40:43.806  5601  5648 I jxcore-log: 2016-11-30 21:40:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-30 22:40:43.806  5601  5648 I jxcore-log: 
,11-30 22:40:43.816  5601  5648 I jxcore-log: 2016-11-30 21:40:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-30 22:40:43.816  5601  5648 I jxcore-log: 
,11-30 22:40:44.642   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:44.947  5601  5648 I jxcore-log: 2016-11-30 21:40:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-30 22:40:44.947  5601  5648 I jxcore-log: 
,11-30 22:40:45.117  5601  5648 I jxcore-log: 2016-11-30 21:40:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-30 22:40:45.117  5601  5648 I jxcore-log: 
,11-30 22:40:45.123  5601  5648 I jxcore-log: 2016-11-30 21:40:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-30 22:40:45.123  5601  5648 I jxcore-log: 
,11-30 22:40:45.135  5601  5648 I jxcore-log: 2016-11-30 21:40:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-30 22:40:45.135  5601  5648 I jxcore-log: 
,11-30 22:40:45.634  5601  5648 I jxcore-log: 2016-11-30 21:40:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-30 22:40:45.634  5601  5648 I jxcore-log: 
,11-30 22:40:45.643   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-30 22:40:45.680  5601  5648 I jxcore-log: 2016-11-30 21:40:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-30 22:40:45.680  5601  5648 I jxcore-log: 
,11-30 22:40:45.694  5601  5648 I jxcore-log: 2016-11-30 21:40:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-30 22:40:45.694  5601  5648 I jxcore-log: 
,11-30 22:40:45.698  5601  5648 I jxcore-log: 2016-11-30 21:40:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-30 22:40:45.698  5601  5648 I jxcore-log: 
,11-30 22:40:45.976  5601  5648 I jxcore-log: 2016-11-30 21:40:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-30 22:40:45.976  5601  5648 I jxcore-log: 
,11-30 22:40:46.105  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-30 22:40:46.105  5601  5648 I jxcore-log: 
,11-30 22:40:46.499  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-30 22:40:46.499  5601  5648 I jxcore-log: 
,11-30 22:40:46.506  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-30 22:40:46.506  5601  5648 I jxcore-log: 
,11-30 22:40:46.510  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-30 22:40:46.510  5601  5648 I jxcore-log: 
,11-30 22:40:46.514  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-30 22:40:46.514  5601  5648 I jxcore-log: 
,11-30 22:40:46.519  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-30 22:40:46.519  5601  5648 I jxcore-log: 
,11-30 22:40:46.561  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-30 22:40:46.561  5601  5648 I jxcore-log: 
,11-30 22:40:46.568  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-30 22:40:46.568  5601  5648 I jxcore-log: 
,11-30 22:40:46.592  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-30 22:40:46.592  5601  5648 I jxcore-log: 
,11-30 22:40:46.631  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-30 22:40:46.631  5601  5648 I jxcore-log: 
,11-30 22:40:46.648  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-30 22:40:46.648  5601  5648 I jxcore-log: 
,11-30 22:40:46.654  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-30 22:40:46.654  5601  5648 I jxcore-log: 
,11-30 22:40:46.670  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-30 22:40:46.670  5601  5648 I jxcore-log: 
,11-30 22:40:46.685  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-30 22:40:46.685  5601  5648 I jxcore-log: 
,11-30 22:40:46.692  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-30 22:40:46.692  5601  5648 I jxcore-log: 
,11-30 22:40:46.697  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-30 22:40:46.697  5601  5648 I jxcore-log: 
,11-30 22:40:46.710  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-30 22:40:46.710  5601  5648 I jxcore-log: 
,11-30 22:40:46.728  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-30 22:40:46.728  5601  5648 I jxcore-log: 
,11-30 22:40:46.742  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-30 22:40:46.742  5601  5648 I jxcore-log: 
,11-30 22:40:46.753  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-30 22:40:46.753  5601  5648 I jxcore-log: 
,11-30 22:40:46.766  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-30 22:40:46.766  5601  5648 I jxcore-log: 
,11-30 22:40:46.776  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-30 22:40:46.776  5601  5648 I jxcore-log: 
,11-30 22:40:46.790  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-30 22:40:46.790  5601  5648 I jxcore-log: 
,11-30 22:40:46.799  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-30 22:40:46.799  5601  5648 I jxcore-log: 
,11-30 22:40:46.806  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-30 22:40:46.806  5601  5648 I jxcore-log: 
,11-30 22:40:46.827  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-30 22:40:46.827  5601  5648 I jxcore-log: 
,11-30 22:40:46.834  5601  5648 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-30 22:40:46.835  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO testUtils: 'BLE multiple advertisement supported'
11-30 22:40:46.835  5601  5648 I jxcore-log: 
,11-30 22:40:46.865  5601  5648 I jxcore-log: 2016-11-30 21:40:46 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-30 22:40:46.865  5601  5648 I jxcore-log: 
,11-30 22:40:47.085  5601  5648 I jxcore-log: 2016-11-30 21:40:47 - DEBUG CoordinatedClient: 'connected to the test server'
11-30 22:40:47.085  5601  5648 I jxcore-log: 
,11-30 22:40:48.742  3572  3572 I ConfigService: onDestroy
,11-30 22:40:50.238   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:40:53.261   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:40:55.644   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:56.645   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:57.646   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:58.648   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:40:59.649   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:41:00.202   930  2936 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 22:41:00.650   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-30 22:41:02.354   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:41:05.387   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:41:15.652   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:41:16.653   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:41:17.655   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:41:18.656   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:41:19.657   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:41:20.516   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:41:20.658   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-30 22:41:23.541   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:41:40.208   930  2936 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 22:41:40.659   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:41:41.660   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:41:42.662   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:41:43.663   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:41:44.664   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:41:44.757   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:41:45.665   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-30 22:41:56.876   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:42:00.208   930  2936 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 22:42:10.665   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-30 22:42:10.666   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-30 22:42:25.667   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:26.669   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:27.122   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:42:27.670   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:28.672   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:29.673   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:30.155   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:42:30.674   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-30 22:42:35.675   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:36.677   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:37.679   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:38.680   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:39.681   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:40.212   930  2936 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 22:42:40.683   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-30 22:42:48.319   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:42:50.684   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:51.345   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:42:51.685   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:52.687   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:53.689   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:54.381   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:42:54.690   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:42:55.691   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-30 22:42:57.418   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:43:00.213   930  2936 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 22:43:06.499   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:43:09.537   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:43:10.692   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:43:11.694   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:43:12.695   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:43:13.697   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:43:14.698   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:43:15.699   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-30 22:43:20.215   930  2936 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 22:43:27.725   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:43:30.759   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:43:35.700   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:43:36.702   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:43:37.703   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:43:38.704   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:43:39.705   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:43:40.706   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-30 22:44:00.219   930  2936 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 22:44:05.707   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-30 22:44:05.707   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-30 22:44:20.221   930  2936 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 22:44:25.224   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:44:25.708   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:44:26.710   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:44:27.711   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:44:28.256   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:44:28.712   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:44:29.713   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:44:30.714   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-30 22:44:31.292   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:44:34.336   930  2950 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 22:44:35.715   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:44:36.717   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:44:37.718   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:44:38.720   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:44:39.721   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 22:44:40.225   930  2936 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 22:44:40.722   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-30 22:44:41.086  5601  5648 I jxcore-log: 2016-11-30 21:44:41 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-30 22:44:41.086  5601  5648 I jxcore-log: 
,11-30 22:44:41.414  5601  5648 I jxcore-log: 2016-11-30 21:44:41 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 22:44:41.414  5601  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 22:44:41.414  5601  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 22:44:41.414  5601  5648 I jxcore-log: emit@events.js:82:1
11-30 22:44:41.414  5601  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 22:44:41.414  5601  5648 I jxcore-log: emit@events.js:82:1''
11-30 22:44:41.414  5601  5648 I jxcore-log: 
,11-30 22:44:41.416  5601  5648 I jxcore-log: 2016-11-30 21:44:41 - DEBUG CoordinatedClient: 'test client failed'
11-30 22:44:41.416  5601  5648 I jxcore-log: 
,11-30 22:44:41.426  5601  5648 I jxcore-log: 2016-11-30 21:44:41 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 22:44:41.426  5601  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 22:44:41.426  5601  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 22:44:41.426  5601  5648 I jxcore-log: emit@events.js:82:1
11-30 22:44:41.426  5601  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 22:44:41.426  5601  5648 I jxcore-log: emit@events.js:82:1''
11-30 22:44:41.426  5601  5648 I jxcore-log: 
,11-30 22:44:41.427  5601  5648 I jxcore-log: 2016-11-30 21:44:41 - DEBUG CoordinatedClient: 'test client failed'
11-30 22:44:41.427  5601  5648 I jxcore-log: 
,11-30 22:44:41.432  5601  5648 I jxcore-log: 2016-11-30 21:44:41 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 22:44:41.432  5601  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 22:44:41.432  5601  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 22:44:41.432  5601  5648 I jxcore-log: emit@events.js:82:1
11-30 22:44:41.432  5601  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 22:44:41.432  5601  5648 I jxcore-log: emit@events.js:82:1''
11-30 22:44:41.432  5601  5648 I jxcore-log: 
,11-30 22:44:41.436  5601  5648 I jxcore-log: 2016-11-30 21:44:41 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-30 22:44:41.436  5601  5648 I jxcore-log: 
,11-30 22:44:41.440  5601  5648 I jxcore-log: 2016-11-30 21:44:41 - ERROR runTests: 'websocket error
11-30 22:44:41.440  5601  5648 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 22:44:41.440  5601  5648 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 22:44:41.440  5601  5648 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 22:44:41.440  5601  5648 I jxcore-log: emit@events.js:82:1
11-30 22:44:41.440  5601  5648 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 22:44:41.440  5601  5648 I jxcore-log: emit@events.js:82:1'
11-30 22:44:41.440  5601  5648 I jxcore-log: 
,11-30 22:44:42.018  5837  5837 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-30 22:44:42.023  5837  5837 D AndroidRuntime: CheckJNI is OFF
,11-30 22:44:42.051  5837  5837 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-30 22:44:42.083  5837  5837 I Radio-JNI: register_android_hardware_Radio DONE
,11-30 22:44:42.099  5837  5837 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-30 22:44:42.109   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-30 22:44:42.110   930   943 I ActivityManager: Killing 5601:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-30 22:44:42.212   930  3401 D GraphicsStats: Buffer count: 2
,11-30 22:44:42.212   930  2947 D WifiService: Client connection lost with reason: 4
,11-30 22:44:42.212   930  3185 I WindowState: WIN DEATH: Window{ca3fee9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-30 22:44:42.233   930   943 W ActivityManager: Force removing ActivityRecord{8defa36 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-30 22:44:42.255   930   953 I art     : Starting a blocking GC Explicit
,11-30 22:44:42.260   930  3826 W ActivityManager: Spurious death for ProcessRecord{d64894f 0:com.test.thalitest/u0a77}, curProc for 5601: null
,11-30 22:44:42.301   930  3831 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5601 uid 10077
,11-30 22:44:42.298  3831  3831 W Binder_A: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[28916]" dev="sockfs" ino=28916 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 22:44:42.298  3831  3831 W Binder_A: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[28916]" dev="sockfs" ino=28916 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 22:44:42.302  3649  3649 I Keyboard.Facilitator: onFinishInput()
,11-30 22:44:42.361   930   953 I art     : Explicit concurrent mark sweep GC freed 139866(9MB) AllocSpace objects, 75(2MB) LOS objects, 33% free, 29MB/44MB, paused 2.066ms total 106.018ms
,11-30 22:44:42.375  3948  5849 I MicroRecognitionRnrImpl: Starting detection.
,11-30 22:44:42.377  3948  5850 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@39f4df7
,11-30 22:44:42.379   514  5852 I AudioFlinger: AudioFlinger's thread 0xf2200000 ready to run
,11-30 22:44:42.383   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-30 22:44:42.385  5837  5837 I art     : System.exit called, status: 0
11-30 22:44:42.385  5837  5837 I AndroidRuntime: VM exiting with result code 0.
,11-30 22:44:42.395   514  2984 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-30 22:44:42.397  3948  5850 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@39f4df7
,11-30 22:44:42.403   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-30 22:44:42.407   514  5852 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-30 22:44:42.407   514  5852 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-30 22:44:42.407   514  5852 I ACDB-LOADER: ACDB AFE returned = -19
11-30 22:44:42.407   514  5852 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-30 22:44:42.407   514  5852 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-30 22:44:42.407   514  5852 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-30 22:44:42.411  3649  3649 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-30 22:44:42.414   930  2926 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-30 22:44:42.416   514  5852 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
11-30 22:44:42.418  5684  5684 D BluetoothMapAppObserver: onReceive
11-30 22:44:42.418  5684  5684 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-30 22:44:42.436  3649  5855 I Keyboard.Facilitator.DecoderInitializer: run()
,11-30 22:44:42.436  4026  4166 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-30 22:44:42.440  3649  5855 I Decoder : createOrResetDecoder
,11-30 22:44:42.467   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-30 22:44:42.470  3814  3814 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-30 22:44:42.477  3385  5859 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-30 22:44:42.480  3572  3572 I ConfigService: onCreate
,11-30 22:44:42.487  3572  3572 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-30 22:44:42.488  3572  3572 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-30 22:44:42.501  3649  5855 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-30 22:44:42.505  3948  3948 I HotwordWorkerImpl: onReady
,11-30 22:44:42.505  3709  5866 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-30 22:44:42.505  3709  5866 D AccountUtils: Clearing selected account for com.test.thalitest
,11-30 22:44:42.519  3709  5866 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-30 22:44:42.521   315   315 W kworker/1:2: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 22:44:42.536  3709  3709 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-30 22:44:42.536  3709  3709 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-30 22:44:42.544   315   315 W kworker/1:2: type=1400 audit(0.0:131): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-30 22:44:42.542  3709  3709 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-30 22:44:42.542  3709  3709 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-30 22:44:42.547  3709  5871 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
11-30 22:44:42.548  3709  5871 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
11-30 22:44:42.548  3709  5871 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
11-30 22:44:42.548  3948  5875 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
11-30 22:44:42.549  3709  5871 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
,11-30 22:44:42.555  3709  5871 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db, release reference: 1
,11-30 22:44:42.555  3709  5871 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 2
11-30 22:44:42.556  3709  5871 E SQLiteLog: (3850) statement aborts at 21: [DELETE FROM help_responses WHERE app_package_name="com.test.thalitest"] disk I/O error
11-30 22:44:42.556  3709  5871 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 1
--------- beginning of crash
11-30 22:44:42.557  3709  5871 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-30 22:44:42.557  3709  5871 E AndroidRuntime: Process: com.google.android.gms, PID: 3709
11-30 22:44:42.557  3709  5871 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-30 22:44:42.557  3709  5871 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-30 22:44:42.557  3709  5871 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-30 22:44:42.557  3709  5871 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-30 22:44:42.557  3709  5871 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-30 22:44:42.557  3709  5871 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-30 22:44:42.557  3709  5871 E AndroidRuntime: 	at com.google.android.gms.googlehelp.c.b.d(SourceFile:535)
11-30 22:44:42.557  3709  5871 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
11-30 22:44:42.557  3709  5871 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-30 22:44:42.557  3709  5871 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 22:44:42.557  3709  5871 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-30 22:44:42.557  3709  5871 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-30 22:44:42.561  3385  5859 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-30 22:44:42.558   315   315 W kworker/1:2: type=1400 audit(0.0:132): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 22:44:42.567  3385  5859 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-30 22:44:42.567  3385  5859 E AndroidRuntime: Process: android.process.acore, PID: 3385
11-30 22:44:42.567  3385  5859 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-30 22:44:42.567  3385  5859 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-30 22:44:42.567   930  5876 E DropBoxManagerService: Can't write: system_app_crash
11-30 22:44:42.567   930  5876 E DropBoxManagerService: java.io.IOException: Can't rename /data/system/dropbox/drop112.tmp to /data/system/dropbox/system_app_crash@1480542282567.txt
11-30 22:44:42.567   930  5876 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService$EntryFile.<init>(DropBoxManagerService.java:509)
11-30 22:44:42.567   930  5876 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.createEntry(DropBoxManagerService.java:690)
11-30 22:44:42.567   930  5876 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:245)
11-30 22:44:42.567   930  5876 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-30 22:44:42.567   930  5876 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
,11-30 22:44:42.569  3948  5875 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-30 22:44:42.571  2928  2928 W Binder_5: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[34875]" dev="sockfs" ino=34875 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 22:44:42.571  2928  2928 W Binder_5: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[34875]" dev="sockfs" ino=34875 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 22:44:42.574  2928  2928 W Binder_5: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[34877]" dev="sockfs" ino=34877 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 22:44:42.574  2928  2928 W Binder_5: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[34877]" dev="sockfs" ino=34877 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 22:44:42.576   930  5878 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-30 22:44:42.584  3832  4441 E ObservedEventLogger: Failed to write the stream file
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2439: open failed: EROFS (Read-only file system)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 22:44:42.584  3832  4441 E ObservedEventLogger: 	... 16 more
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: Failed to write the stream file
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2440: open failed: EROFS (Read-only file system)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at com.google.android.a,pps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 22:44:42.585  3832  4441 E ObservedEventLogger: 	... 16 more
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: Failed to write the stream file
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2441: open failed: EROFS (Read-only file system)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor,.java:269)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 22:44:42.586  3832  4441 E ObservedEventLogger: 	... 16 more
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: Failed to write the stream file
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2442: open failed: EROFS (Read-only file system)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 22:44:42.587  3832  4441 E ObservedEventLogger: 	... 16 more
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: Failed to write the stream file
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2443: open failed: EROFS (Read-only file system)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 22:44:42.588  3832  4441 E ObservedEventLogger: 	... 16 more
11-30 22:44:42.589   930  5881 E DropBoxManagerService: Can't write: system_app_crash
11-30 22:44:42.589   930  5881 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
11-30 22:44:42.589   930  5881 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 22:44:42.589   930  5881 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 22:44:42.589   930  5881 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-30 22:44:42.589   930  5881 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-30 22:44:42.589   930  5881 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-30 22:44:42.589   930  5881 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-30 22:44:42.589   930  5881 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 22:44:42.589   930  5881 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-30 22:44:42.589   930  5881 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 22:44:42.589   930  5881 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 22:44:42.589   930  5881 E DropBoxManagerService: 	... 5 more
11-30 22:44:42.590  3649  5855 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-30 22:44:42.593  3649  5855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-30 22:44:42.593  3649  5855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-30 22:44:42.596  3649  5855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-30 22:44:42.596  3649  5855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-30 22:44:42.597  3649  5855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-30 22:44:42.597  3649  5855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-30 22:44:42.598  3649  5855 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-30 22:44:42.598  3649  5855 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-30 22:44:42.598  3649  5855 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-30 22:44:42.599  3649  5855 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-30 22:44:42.599  3649  5855 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-30 22:44:42.599  3649  5855 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-30 22:44:42.609   930  3776 I ActivityManager: Start proc 5882:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,11-30 22:44:42.630   930  5878 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-30 22:44:42.630   930  5878 I Adreno  : Build Date                       : 12/06/15
11-30 22:44:42.630   930  5878 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-30 22:44:42.630   930  5878 I Adreno  : Local Branch                     : mybranch17112971
11-30 22:44:42.630   930  5878 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-30 22:44:42.630   930  5878 I Adreno  : Remote Branch                    : NONE
11-30 22:44:42.630   930  5878 I Adreno  : Reconstruct Branch               : NOTHING
11-30 22:44:42.631   930  3826 I ActivityManager: Start proc 5893:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-30 22:44:42.638  3709  5873 W BaseAppContext: Using Auth Proxy for data requests.
11-30 22:44:42.646  3709  5866 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
11-30 22:44:42.651  3709  5873 W BaseAppContext: Using Auth Proxy for data requests.
,11-30 22:44:42.661  3709  5906 I GMPM-SVC: App measurement is starting up
,11-30 22:44:42.666  3709  3709 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-30 22:44:42.668  3709  5906 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-30 22:44:42.668  3709  4890 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml.bak
11-30 22:44:42.669  3709  5906 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-30 22:44:42.672  3709  3709 I ConfigFetchService: service connected
,11-30 22:44:42.679  3709  5909 I PeopleContactsSync: CP2 sync disabled
11-30 22:44:42.680  3709  4215 I Icing   : doRemovePackageData com.test.thalitest
,11-30 22:44:42.682   930   943 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{33e88f4 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{8d9b406 3709 com.google.android.gms/10012/u0 remote:ef32ee1}: process crashing
,11-30 22:44:42.691   930  3402 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3709 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-30 22:44:42.743  3709  5870 W DriveInitializer: Awaiting to be initialized
,11-30 22:44:42.744  3709  5912 W DriveInitializer: Background init thread started
,11-30 22:44:42.944   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
