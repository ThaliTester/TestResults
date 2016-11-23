#### Test 950065924e01fb7_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of system
11-23 17:18:13.770   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
11-23 17:18:14.237  5631  5631 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-23 17:18:14.242  5631  5631 D AndroidRuntime: CheckJNI is OFF
11-23 17:18:14.270  5631  5631 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-23 17:18:14.314  5631  5631 I Radio-JNI: register_android_hardware_Radio DONE
11-23 17:18:14.329  5631  5631 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-23 17:18:14.335   930  3890 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-23 17:18:14.354  5631  5631 D AndroidRuntime: Shutting down VM
11-23 17:18:14.366  3998  4009 W SearchService: Abort, client detached.
11-23 17:18:14.375  3998  3998 I HotwordDetector: Closing mic
11-23 17:18:14.376  3998  4264 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e0e71c3
11-23 17:18:14.377  3998  4269 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-23 17:18:14.397   930   940 I ActivityManager: Start proc 5640:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-23 17:18:14.450   513  4271 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-23 17:18:14.452   513  4271 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-23 17:18:14.457   513  4271 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-23 17:18:14.457   513  4271 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-23 17:18:14.458   513  3031 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-23 17:18:14.460  3998  4265 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-23 17:18:14.460  3998  4268 I MicroRecognitionRnrImpl: Detection finished
11-23 17:18:14.503  5640  5640 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-23 17:18:14.523  5640  5640 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-23 17:18:14.546  5640  5640 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 9691-9710)
11-23 17:18:14.546  5640  5640 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-23 17:18:14.566  5640  5640 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c2e1909}
11-23 17:18:14.567  5640  5640 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-23 17:18:14.567  5640  5640 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-23 17:18:14.570  5640  5640 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-23 17:18:14.571  5640  5640 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-23 17:18:14.605  5640  5640 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-23 17:18:14.613  5640  5640 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-23 17:18:14.613  5640  5640 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-23 17:18:14.613  5640  5640 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 17:18:14.613  5640  5640 I Adreno  : Build Date                       : 12/06/15
11-23 17:18:14.613  5640  5640 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 17:18:14.613  5640  5640 I Adreno  : Local Branch                     : mybranch17112971
11-23 17:18:14.613  5640  5640 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 17:18:14.613  5640  5640 I Adreno  : Remote Branch                    : NONE
11-23 17:18:14.613  5640  5640 I Adreno  : Reconstruct Branch               : NOTHING
,11-23 17:18:14.655   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9e72013:true
,11-23 17:18:14.683  3946  3946 W Binder_5: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[27312]" dev="sockfs" ino=27312 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 17:18:14.683  3946  3946 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[27312]" dev="sockfs" ino=27312 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 17:18:14.695  5640  5640 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-23 17:18:14.704  5640  5640 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-23 17:18:14.729  3946  3946 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33028]" dev="sockfs" ino=33028 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 17:18:14.729  3946  3946 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33028]" dev="sockfs" ino=33028 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 17:18:14.732  5640  5677 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 17:18:14.733   940   940 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[27323]" dev="sockfs" ino=27323 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 17:18:14.733   940   940 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[27323]" dev="sockfs" ino=27323 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 17:18:14.736  5640  5664 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-23 17:18:14.771  5640  5677 I OpenGLRenderer: Initialized EGL, version 1.4
,11-23 17:18:14.856   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +479ms
,11-23 17:18:14.853   941   941 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33031]" dev="sockfs" ino=33031 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 17:18:14.856   941   941 W Binder_2: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33031]" dev="sockfs" ino=33031 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 17:18:14.856  3850  3850 W Binder_7: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33030]" dev="sockfs" ino=33030 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 17:18:14.856  3850  3850 W Binder_7: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33030]" dev="sockfs" ino=33030 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 17:18:14.860  3688  3688 I Keyboard.Facilitator: onFinishInput()
,11-23 17:18:14.888  5640  5640 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5640
,11-23 17:18:14.964  5640  5640 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-23 17:18:15.167  5640  5680 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -584578768
,11-23 17:18:15.173  5640  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-23 17:18:15.173  5640  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-23 17:18:15.173  5640  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-23 17:18:15.173  5640  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-23 17:18:15.173  5640  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-23 17:18:15.174  5640  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53c313d added. We now have 1 listener(s)
,11-23 17:18:15.195  5640  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-23 17:18:15.197  5640  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4",
11-23 17:18:15.198  5640  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 17:18:15.198  5640  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-23 17:18:15.201  5640  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@984c400 added. We now have 1 listener(s)
11-23 17:18:15.201  5640  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 17:18:15.212   930  3010 D WifiService: New client listening to asynchronous messages
,11-23 17:18:15.212   930  3890 I ActivityManager: Killing 5314:com.android.settings/1000 (adj 15): empty #17
11-23 17:18:15.213  5640  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 17:18:15.213  5640  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-23 17:18:15.214  5640  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-23 17:18:15.214  5640  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-23 17:18:15.214  5640  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-23 17:18:15.214  5640  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-23 17:18:15.214  5640  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-23 17:18:15.215  5640  5680 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-23 17:18:15.249   930  3890 I ActivityManager: Killing 5275:org.codeaurora.ims/1001 (adj 15): empty #18
,11-23 17:18:15.328  5640  5640 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-23 17:18:15.768  5640  5649 I art     : Background sticky concurrent mark sweep GC freed 76354(7MB) AllocSpace objects, 16(1076KB) LOS objects, 24% free, 24MB/32MB, paused 1.460ms total 370.346ms
,11-23 17:18:16.793   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 17:18:17.087  5640  5649 I art     : Background partial concurrent mark sweep GC freed 54697(6MB) AllocSpace objects, 2(1176KB) LOS objects, 37% free, 26MB/42MB, paused 1.815ms total 368.988ms
,11-23 17:18:18.693   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:18:19.155  5640  5687 W jxcore-log: Initializing JXcore engine
,11-23 17:18:19.155  5640  5687 W jxcore-log: JXcore engine is ready
,11-23 17:18:19.213  5687  5687 W Thread-58: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12478 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-23 17:18:19.213  5687  5687 W Thread-58: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14404]" dev="sockfs" ino=14404 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-23 17:18:19.213  5687  5687 W Thread-58: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-23 17:18:19.213  5687  5687 W Thread-58: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31342]" dev="sockfs" ino=31342 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-23 17:18:19.230  5640  5687 W jxcore-log: Starting JXcore engine
,11-23 17:18:19.296  5640  5687 W jxcore-log: Platform android
11-23 17:18:19.296  5640  5687 W jxcore-log: 
,11-23 17:18:19.296  5640  5687 W jxcore-log: Process ARCH arm
11-23 17:18:19.296  5640  5687 W jxcore-log: 
,11-23 17:18:19.482  5640  5687 I jxcore-log: JXcore Cordova bridge is ready!
11-23 17:18:19.482  5640  5687 I jxcore-log: 
11-23 17:18:19.482  5640  5687 W jxcore-log: JXcore engine is started
,11-23 17:18:19.497  5640  5680 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-23 17:18:19.502  5640  5640 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-23 17:18:19.694   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:18:20.695   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:18:21.696   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:18:22.697   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:18:23.698   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 17:18:24.479  3998  5689 W CronetSyncConnectionRcs: Upload content type not set.
,11-23 17:18:25.863   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 17:18:28.899   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 17:18:29.274  5640  5687 I jxcore-log: 2016-11-23 16:18:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-23 17:18:29.274  5640  5687 I jxcore-log: 
,11-23 17:18:29.275  5640  5687 I jxcore-log: 2016-11-23 16:18:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-23 17:18:29.275  5640  5687 I jxcore-log: 
,11-23 17:18:29.280  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-23 17:18:29.281  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 17:18:29.281  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:18:29.281  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:18:29.281  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 17:18:29.281  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 17:18:29.281  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 17:18:29.281  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 17:18:29.281  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 17:18:29.281  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 17:18:29.282  5640  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 17:18:29.285  5640  5687 I jxcore-log: 2016-11-23 16:18:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-23 17:18:29.285  5640  5687 I jxcore-log: 
11-23 17:18:29.286  5640  5687 I jxcore-log: 2016-11-23 16:18:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-23 17:18:29.286  5640  5687 I jxcore-log: 
,11-23 17:18:29.501   930  5401 D NetlinkSocketObserver: NeighborEvent{elapsedMs=174664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 17:18:29.536  5640  5687 I jxcore-log: 2016-11-23 16:18:29 - DEBUG UnitTest_app: 'Running unit tests'
11-23 17:18:29.536  5640  5687 I jxcore-log: 
,11-23 17:18:29.537  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 17:18:29.537  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab899dc added. We now have 2 listener(s)
,11-23 17:18:29.538  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 17:18:29.538  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 17:18:29.538  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 17:18:29.538  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:18:29.538  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba2bae5 added. We now have 2 listener(s)
,11-23 17:18:29.538  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 17:18:29.539  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 17:18:29.540  5640  5687 D executeNativeTests: Running unit tests
,11-23 17:18:29.577  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 17:18:29.577  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a added. We now have 3 listener(s)
,11-23 17:18:29.578  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 17:18:29.578  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 17:18:29.578  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 17:18:29.578  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:18:29.578  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b added. We now have 3 listener(s)
11-23 17:18:29.578  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 17:18:29.578  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 17:18:29.580  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 17:18:29.580  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 17:18:29.580  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 17:18:29.580  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 17:18:29.581  5640  5687 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-23 17:18:29.581  5640  5687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 17:18:29.581  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 17:18:29.581  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 17:18:29.581  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 17:18:29.581  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 17:18:29.581  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:29.581  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:29.582  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:29.582  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 17:18:29.582  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:29.582  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 17:18:29.582  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a removed from the list
11-23 17:18:29.582  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 17:18:29.582  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b removed from the list
11-23 17:18:29.582  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:29.582  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.582  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.583  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.583  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:29.583  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.583  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 17:18:29.583  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:29.583  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:29.583  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:29.584  5640  5687 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-23 17:18:29.584  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:29.584  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:29.584  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:29.585  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:29.585  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:29.585  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:29.585  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 17:18:29.585  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:29.585  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:29.585  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.585  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.585  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.585  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:29.585  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.585  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:29.585  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:29.585  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:29.585  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 17:18:29.588  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 17:18:29.589  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 17:18:29.589  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-23 17:18:29.589  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 17:18:29.589  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 17:18:29.589  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 17:18:29.589  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 17:18:29.589  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-23 17:18:29.589  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:29.589  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:29.589  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:29.589  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:29.589  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 17:18:29.589  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:29.589  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:29.589  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:29.589  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 17:18:29.589  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.589  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.590  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.590  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.590  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.590  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:29.590  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:29.590  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:29.590  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:29.590  5640  5687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 17:18:29.591  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 17:18:29.591  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 17:18:29.595  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 17:18:29.595  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:18:29.595  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:18:29.595  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 17:18:29.595  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 17:18:29.595  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 17:18:29.595  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 17:18:29.595  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 17:18:29.595  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 17:18:29.596  5640  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 17:18:29.597  5640  5687 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-23 17:18:29.597  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 17:18:29.597  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 17:18:29.597  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 17:18:29.597  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 17:18:29.597  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 17:18:29.599  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:18:29.600  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 17:18:29.600  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 17:18:29.600  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 17:18:29.603  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.603  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 17:18:29.604  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:18:29.604  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 17:18:29.605  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 17:18:29.605  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 17:18:29.606  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-23 17:18:29.607  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-23 17:18:29.607  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.607  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 17:18:29.607  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 17:18:29.607  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 17:18:29.607  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 17:18:29.607  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.608  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:18:29.610  4681  4914 D BtGatt.GattService: registerClient() - UUID=afa5dbed-3e28-4b02-9652-fd03cf66dd8f
11-23 17:18:29.611  4681  4756 D BtGatt.GattService: onClientRegistered() - UUID=afa5dbed-3e28-4b02-9652-fd03cf66dd8f, clientIf=5
11-23 17:18:29.615  5640  5651 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 17:18:29.616  4681  4912 D BtGatt.GattService: start scan with filters
11-23 17:18:29.623  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 17:18:29.623  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.623  4681  4759 D BtGatt.ScanManager: handling starting scan
11-23 17:18:29.623  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 17:18:29.623  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.623  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 17:18:29.623  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 17:18:29.624  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 17:18:29.624  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 17:18:29.624  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 17:18:29.624  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 17:18:29.624  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 17:18:29.624  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.624  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 17:18:29.624  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 17:18:29.625  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 17:18:29.625  4681  4759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
11-23 17:18:29.625  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.625  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.625  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:29.626  5640  5687 I io.jxcore.node.ConnectionHelper: start: OK
11-23 17:18:29.626  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 17:18:29.630  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 17:18:29.630  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 17:18:29.631  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 17:18:29.631  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 17:18:29.631  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 17:18:29.634  4681  4756 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 17:18:29.634  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:29.634  4681  4759 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 17:18:29.641  4681  4756 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 17:18:29.641  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:29.641  4681  4759 D BtGatt.ScanManager: Starting BLE batch scan
11-23 17:18:29.641  4681  4759 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 17:18:29.652  4681  4756 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 17:18:29.652  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:29.658  4681  4756 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 17:18:29.659  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:18:30.133  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-23 17:18:30.133  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 17:18:30.133  5640  5640 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 17:18:34.630  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 17:18:34.631  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:34.631  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-23 17:18:34.631  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 17:18:34.631  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-23 17:18:34.631  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 17:18:34.631  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 17:18:34.631  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 17:18:34.632  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.632  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 17:18:34.632  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 17:18:34.633  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.633  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.633  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:34.633  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 17:18:34.633  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.634  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:18:34.635  4681  4912 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 17:18:34.635  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 17:18:34.636  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:18:34.636  4681  4759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 17:18:34.637  4681  4695 D BtGatt.GattService: stopScan() - queue size =1
11-23 17:18:34.637  4681  4914 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 17:18:34.638  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 17:18:34.638  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:34.638  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 17:18:34.638  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.638  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.638  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.638  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.639  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 17:18:34.639  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.639  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.639  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.639  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 17:18:34.639  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 17:18:34.640  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 17:18:34.640  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.641  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.642  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:18:34.642  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.642  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:34.642  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:34.642  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 17:18:34.642  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 17:18:34.642  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:18:34.642  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:34.642  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:34.642  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:34.642  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:18:34.643  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Discove,ryManager@9585a5b not in the list
11-23 17:18:34.643  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:34.643  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 17:18:34.643  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 17:18:34.643  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 17:18:34.643  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 17:18:34.643  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 17:18:34.644  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-23 17:18:34.644  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-23 17:18:34.644  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-23 17:18:34.644  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:18:34.645  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 17:18:34.645  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 17:18:34.645  4681  4681 D BtGatt.ScanManager: awakened up at time 179808
,11-23 17:18:34.651  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 17:18:34.651  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 17:18:34.651  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 17:18:34.662  4681  4756 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-23 17:18:34.662  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:34.662  4681  4756 D BtGatt.GattService: current time is 179826408941
11-23 17:18:34.663  4681  4756 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -85, 72, 0, 27, 2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -84, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -94, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -88, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 17:18:34.664  4681  4756 D BtGatt.GattService: ScanRecord : [2, 1, 26, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
11-23 17:18:34.665  4681  4756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-23 17:18:34.665  4681  4756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 17:18:34.665  4681  4756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-23 17:18:34.671  4681  4756 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 17:18:34.671  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:34.671  4681  4759 D BtGatt.ScanManager: stopping BLe Batch
,11-23 17:18:34.676  4681  4756 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 17:18:34.676  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:34.676  4681  4759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 17:18:34.681  4681  4756 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 17:18:34.681  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:18:35.146  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 17:18:35.775   930  3009 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 17:18:37.983   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 17:18:39.646  5640  5687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 17:18:39.652  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 17:18:39.652  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 17:18:39.665  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 17:18:39.665  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:18:39.665  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:18:39.665  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 17:18:39.665  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 17:18:39.665  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 17:18:39.665  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 17:18:39.665  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 17:18:39.665  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 17:18:39.671  5640  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 17:18:39.671  5640  5687 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 17:18:39.672  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 17:18:39.672  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 17:18:39.672  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 17:18:39.672  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 17:18:39.672  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 17:18:39.675  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 17:18:39.676  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 17:18:39.677  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 17:18:39.677  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 17:18:39.678  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 17:18:39.681  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:39.681  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 17:18:39.682  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 17:18:39.682  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 17:18:39.682  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 17:18:39.685  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.685  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 17:18:39.685  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 17:18:39.685  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-23 17:18:39.686  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 17:18:39.686  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.687  5640  5687 D BluetoothAdapter: STATE_ON
,11-23 17:18:39.690  4681  4695 D BtGatt.GattService: registerClient() - UUID=f0c1e926-02ff-4f73-99dc-b05c8674d088
,11-23 17:18:39.690  4681  4756 D BtGatt.GattService: onClientRegistered() - UUID=f0c1e926-02ff-4f73-99dc-b05c8674d088, clientIf=5
11-23 17:18:39.691  5640  5651 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 17:18:39.691  4681  4914 D BtGatt.GattService: start scan with filters
,11-23 17:18:39.694  4681  4759 D BtGatt.ScanManager: handling starting scan
11-23 17:18:39.695  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 17:18:39.695  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.695  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 17:18:39.695  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:39.695  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-23 17:18:39.695  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-23 17:18:39.695  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.695  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 17:18:39.695  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 17:18:39.695  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.695  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.695  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.696  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.696  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 17:18:39.696  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.700  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.700  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 17:18:39.700  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.700  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.700  5640  5687 I io.jxcore.node.ConnectionHelper: start: OK
11-23 17:18:39.700  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.701  4681  4756 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 17:18:39.701  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:39.701  4681  4759 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 17:18:39.704  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.704  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.704  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.704  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 17:18:39.704  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:39.704  5640  5687 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 17:18:39.705  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:39.705  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 17:18:39.705  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 17:18:39.705  564,0  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 17:18:39.705  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:39.705  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 17:18:39.705  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 17:18:39.705  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.705  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 17:18:39.705  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 17:18:39.705  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.705  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.705  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.705  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 17:18:39.705  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.706  4681  4756 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 17:18:39.706  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:39.706  4681  4759 D BtGatt.ScanManager: Starting BLE batch scan
11-23 17:18:39.706  4681  4759 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 17:18:39.707  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:18:39.707  4681  4694 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 17:18:39.707  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-23 17:18:39.708  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:18:39.708  4681  4695 D BtGatt.GattService: stopScan() - queue size =1
11-23 17:18:39.709  4681  4694 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 17:18:39.710  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 17:18:39.710  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.710  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 17:18:39.710  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.710  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.710  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.710  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.710  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 17:18:39.710  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:39.710  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.710  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.710  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 17:18:39.710  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 17:18:39.711  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 17:18:39.711  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.712  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.712  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:18:39.712  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:39.712  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.712  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:39.712  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:18:39.712  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 17:18:39.712  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 17:18:39.712  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:18:39.712  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:39.713  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 17:18:39.713  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:39.713  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:39.713  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.713  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:39.713  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:39.713  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 17:18:39.713  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 17:18:39.714  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 17:18:39.714  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.714  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.714  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.714  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:18:39.714  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.714  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.715  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.715  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.715  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.715  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58,
11-23 17:18:39.716  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.717  4681  4756 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 17:18:39.717  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:39.717  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.717  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.717  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.717  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:39.717  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:39.717  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:39.717  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:39.718  5640  5687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 17:18:39.720  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 17:18:39.720  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 17:18:39.723  4681  4756 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 17:18:39.723  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:18:39.725  4681  4759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 17:18:39.726  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 17:18:39.726  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:18:39.726  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:18:39.726  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 17:18:39.726  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 17:18:39.726  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 17:18:39.726  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 17:18:39.726  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 17:18:39.726  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 17:18:39.729  4681  4756 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 17:18:39.729  5640  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 17:18:39.729  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:39.729  5640  5687 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 17:18:39.729  4681  4756 E BtGatt.ContextMap: Context not found for ID 5
,11-23 17:18:39.729  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 17:18:39.729  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 17:18:39.729  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 17:18:39.729  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 17:18:39.729  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 17:18:39.732  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 17:18:39.734  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 17:18:39.734  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:18:39.734  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 17:18:39.734  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 17:18:39.736  4681  4756 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 17:18:39.736  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:39.736  4681  4759 D BtGatt.ScanManager: stopping BLe Batch
,11-23 17:18:39.737  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:39.738  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 17:18:39.738  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 17:18:39.738  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-23 17:18:39.738  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 17:18:39.740  4681  4756 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 17:18:39.740  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:39.741  4681  4759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 17:18:39.741  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:39.742  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 17:18:39.742  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 17:18:39.742  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 17:18:39.742  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 17:18:39.742  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.742  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:18:39.745  4681  4756 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 17:18:39.745  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:18:39.747  4681  4695 D BtGatt.GattService: registerClient() - UUID=3bb0b89b-3e0b-451d-8493-4a77003cf57c
11-23 17:18:39.747  4681  4756 D BtGatt.GattService: onClientRegistered() - UUID=3bb0b89b-3e0b-451d-8493-4a77003cf57c, clientIf=5
,11-23 17:18:39.748  5640  5651 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 17:18:39.748  4681  4694 D BtGatt.GattService: start scan with filters
,11-23 17:18:39.751  4681  4759 D BtGatt.ScanManager: handling starting scan
11-23 17:18:39.751  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 17:18:39.751  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.751  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-23 17:18:39.751  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.751  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 17:18:39.751  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 17:18:39.751  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.752  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 17:18:39.752  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 17:18:39.752  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.752  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.752  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.752  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-23 17:18:39.753  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 17:18:39.753  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:39.756  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.756  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 17:18:39.756  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.756  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:39.756  5640  5687 I io.jxcore.node.ConnectionHelper: start: OK
11-23 17:18:39.756  4681  4756 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 17:18:39.756  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:18:39.756  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 17:18:39.757  4681  4759 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 17:18:39.759  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.759  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.759  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 17:18:39.759  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 17:18:39.762  4681  4756 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-23 17:18:39.762  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:39.762  4681  4759 D BtGatt.ScanManager: Starting BLE batch scan
11-23 17:18:39.762  4681  4759 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 17:18:39.770  4681  4756 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-23 17:18:39.770  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:18:39.775  4681  4756 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 17:18:39.775  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:18:40.260  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-23 17:18:40.260  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 17:18:40.261  5640  5640 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 17:18:41.009   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 17:18:41.020   930  3011 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,11-23 17:18:43.699   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:18:44.036   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-23 17:18:44.039   930  3011 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 53
,11-23 17:18:44.700   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:18:44.757  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 17:18:44.757  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:44.757  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 17:18:44.757  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 17:18:44.758  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 17:18:44.758  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:44.758  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 17:18:44.758  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 17:18:44.758  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.758  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 17:18:44.758  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 17:18:44.759  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.759  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.759  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.759  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 17:18:44.760  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.762  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:18:44.762  4681  4914 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 17:18:44.763  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 17:18:44.765  4681  4759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 17:18:44.766  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:18:44.767  4681  4695 D BtGatt.GattService: stopScan() - queue size =1
,11-23 17:18:44.769  4681  4694 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-23 17:18:44.770  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 17:18:44.770  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.770  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 17:18:44.770  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.770  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:44.771  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.771  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.771  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 17:18:44.771  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.771  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.772  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.772  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-23 17:18:44.772  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 17:18:44.772  4681  4681 D BtGatt.ScanManager: awakened up at time 189936
11-23 17:18:44.773  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 17:18:44.773  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.777  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.777  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:18:44.777  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.777  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:44.777  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:18:44.778  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:18:44.778  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 17:18:44.778  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 17:18:44.778  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 17:18:44.778  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 17:18:44.778  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 17:18:44.778  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 17:18:44.778  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 17:18:44.779  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:18:44.779  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 17:18:44.779  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 17:18:44.781  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 17:18:44.781  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 17:18:44.781  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 17:18:44.790  4681  4756 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-23 17:18:44.791  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:44.791  4681  4756 D BtGatt.GattService: current time is 189954708004
11-23 17:18:44.791  4681  4756 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -89, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -88, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -95, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -78, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -98, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 17:18:44.791  4681  4756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 17:18:44.792  4681  4756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-23 17:18:44.792  4681  4756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 17:18:44.793  4681  4756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 17:18:44.793  4681  4756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 17:18:44.793  4681  4756 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 17:18:44.793  4681  4756 E BtGatt.ContextMap: Context not found for ID 5
,11-23 17:18:44.799  4681  4756 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 17:18:44.799  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:44.800  4681  4759 D BtGatt.ScanManager: stopping BLe Batch
,11-23 17:18:44.805  4681  4756 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 17:18:44.805  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:18:44.805  4681  4759 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 17:18:44.810  4681  4756 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 17:18:44.810  4681  4756 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:18:45.280  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 17:18:45.280  5640  5640 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:45.280  5640  5640 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 17:18:45.701   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:18:46.034   930  5401 D NetlinkSocketObserver: NeighborEvent{elapsedMs=191197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 17:18:46.702   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:18:47.064   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-23 17:18:47.067   930  3011 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-23 17:18:47.703   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:18:48.704   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 17:18:49.779  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:49.779  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 17:18:49.779  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:49.780  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:49.780  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 17:18:49.780  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 17:18:49.780  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:49.781  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:49.781  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 17:18:49.781  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.781  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:49.781  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 17:18:49.785  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:49.786  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:49.788  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:49.788  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.789  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.789  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:49.789  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 17:18:49.789  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.789  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.790  5640  5687 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-23 17:18:49.792  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:49.792  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 17:18:49.792  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:49.793  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:49.793  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:49.793  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:49.793  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.793  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.794  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:49.794  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.794  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.796  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:49.797  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.797  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.797  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:49.797  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:49.797  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.797  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.799  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 17:18:49.799  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:49.799  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 17:18:49.799  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:49.799  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:49.799  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:49.799  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:49.799  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.799  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.799  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:49.800  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.800  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:49.801  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.801  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.801  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.801  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:49.801  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:49.801  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.801  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
,11-23 17:18:49.802  5640  5687 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-23 17:18:49.802  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:49.802  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:49.803  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:49.803  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:49.803  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 17:18:49.803  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:49.803  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.803  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.803  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:49.803  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.803  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:49.805  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.805  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.805  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.805  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:49.805  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:49.805  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.805  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
,11-23 17:18:49.806  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-23 17:18:49.806  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:49.806  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 17:18:49.806  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:49.806  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:49.807  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:49.807  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:49.807  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.807  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.807  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:49.807  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.807  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:49.808  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.808  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.808  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.808  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:49.809  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:49.809  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.809  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.810  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 17:18:49.810  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 17:18:49.810  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 17:18:49.810  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 17:18:49.810  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 17:18:49.810  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 17:18:49.810  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 17:18:49.810  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 17:18:49.810  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 17:18:49.811  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:49.811  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:49.811  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:49.811  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:49.811  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:49.811  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:49.811  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.811  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.811  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:49.811  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.811  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.813  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.814  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.814  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.814  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:49.814  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:49.814  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.814  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.815  5640  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 17:18:49.815  5640  5687 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 17:18:49.815  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 17:18:49.818  5640  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 17:18:49.818  5640  5687 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-23 17:18:49.818  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 17:18:49.819  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 17:18:49.820  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 17:18:49.820  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 17:18:49.820  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 17:18:49.820  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 17:18:49.820  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 17:18:49.820  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 17:18:49.820  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 17:18:49.820  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 17:18:49.820  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 17:18:49.820  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 17:18:49.820  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 17:18:49.820  5640  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-23 17:18:49.820  5640  5687 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 17:18:49.821  5640  5687 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-23 17:18:49.821  5640  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 17:18:49.821  5640  5687 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 17:18:49.821  5640  5687 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-23 17:18:49.821  5640  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 17:18:49.821  5640  5687 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 17:18:49.821  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-23 17:18:49.825  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-23 17:18:49.825  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-23 17:18:49.825  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-23 17:18:49.826  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-23 17:18:49.826  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-23 17:18:49.826  5640  5687 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-23 17:18:49.826  5640  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 17:18:49.827  5640  5687 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-23 17:18:49.827  5640  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 122)
11-23 17:18:49.827  5640  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-23 17:18:49.827  5640  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-23 17:18:49.827  5640  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-23 17:18:49.827  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:49.828  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:49.828  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:49.828  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:49.828  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:49.828  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-23 17:18:49.830  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:49.830  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.830  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.830  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:49.830  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.830  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.830  5640  5692 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-23 17:18:49.831  5640  5692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 17:18:49.831  5640  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 122
11-23 17:18:49.831  5640  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-23 17:18:49.831  5640  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 122)
11-23 17:18:49.832  5640  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 122)
11-23 17:18:49.832  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.832  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.832  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.832  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:49.832  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:49.832  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.832  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.833  4912  4912 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32033]" dev="sockfs" ino=32033 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 17:18:49.833  4912  4912 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32033]" dev="sockfs" ino=32033 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 17:18:49.833  5640  5687 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-23 17:18:49.834  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:49.834  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:49.834  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:49.834  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:49.834  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:49.834  5640  5692 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-23 17:18:49.834  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:49.834  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.834  5640  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-23 17:18:49.834  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.834  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:49.834  5640  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 122)
11-23 17:18:49.834  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.834  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.835  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.836  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.836  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.836  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:49.836  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:49.836  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.836  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.837  5640  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-23 17:18:49.837  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:49.837  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:49.837  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:49.837  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:49.837  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:49.837  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:49.837  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.837  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.837  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:49.838  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.838  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.838  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.839  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.839  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.839  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:49.839  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:49.839  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.839  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.840  5640  5687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-23 17:18:49.840  5640  5687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-23 17:18:49.840  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 17:18:49.840  5640  5687 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-23 17:18:49.840  5640  5687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 17:18:49.840  5640  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-23 17:18:49.840  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 17:18:49.840  5640  5687 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-23 17:18:49.840  5640  5687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 17:18:49.840  5640  5687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 17:18:49.840  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 17:18:49.840  5640  5687 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-23 17:18:49.840  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:49.840  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:49.840  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:49.841  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:49.841  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:49.841  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:49.841  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.841  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.841  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:49.841  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.841  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.842  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.842  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.842  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:49.842  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:49.842  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:49.842  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.842  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.843  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:49.843  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:49.843  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:49.843  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:49.843  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:49.843  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 17:18:50.094   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 17:18:54.844  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 17:18:54.844  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:54.845  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:54.845  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:54.845  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
,11-23 17:18:54.845  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:54.845  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:54.846  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 17:18:54.846  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:54.846  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:54.846  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:54.847  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 17:18:54.847  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:54.847  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:54.847  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.847  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:54.850  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.851  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.851  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:54.851  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:54.851  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:54.851  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:54.852  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
,11-23 17:18:54.856  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-23 17:18:54.857  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 17:18:54.857  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 17:18:54.863  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-23 17:18:54.866  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-23 17:18:54.866  5640  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-23 17:18:54.867  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-23 17:18:54.867  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-23 17:18:54.867  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-23 17:18:54.867  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 17:18:54.867  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-23 17:18:54.868  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:54.868  5640  5694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 17:18:54.868  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-23 17:18:54.868  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-23 17:18:54.868  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-23 17:18:54.868  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 17:18:54.869  4694  4694 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31405]" dev="sockfs" ino=31405 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 17:18:54.869  4694  4694 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31405]" dev="sockfs" ino=31405 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 17:18:54.869  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-23 17:18:54.869  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-23 17:18:54.869  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:54.869  5640  5640 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-23 17:18:54.869  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:54.869  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 17:18:54.869  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.869  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-23 17:18:54.869  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 17:18:54.870  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.870  5640  5694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-23 17:18:54.871  5640  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-23 17:18:54.871  5640  5694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-23 17:18:54.871  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:54.871  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:18:54.871  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.871  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.871  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:54.871  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:18:54.871  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 17:18:54.871  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:18:54.871  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:54.871  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:18:54.871  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:54.872  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:54.872  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 17:18:54.872  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
,11-23 17:18:54.872  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:54.872  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:54.872  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:54.872  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.872  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-23 17:18:54.872  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.872  5640  5640 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 17:18:54.874  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.874  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.874  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:54.874  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:54.874  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:54.874  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:54.874  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:54.876  5640  5687 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-23 17:18:54.877  5640  5687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 17:18:54.877  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-23 17:18:54.877  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 17:18:54.877  5640  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 17:18:54.877  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:18:54.878  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:54.878  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:54.878  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:54.878  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:54.878  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:54.878  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:54.878  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:54.878  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:54.878  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.879  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.881  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:54.881  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.881  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.881  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:54.881  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:18:54.881  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:54.881  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
,11-23 17:18:54.886  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 17:18:54.887  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:54.887  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:54.887  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:54.887  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:54.887  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:54.887  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:54.887  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
,11-23 17:18:54.887  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:54.887  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.888  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.889  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.890  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.890  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.890  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:54.890  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 17:18:54.890  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:54.890  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
,11-23 17:18:54.891  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 17:18:54.891  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:18:54.892  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:18:54.892  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:18:54.892  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:18:54.892  5640  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d07d56a not in the list
11-23 17:18:54.892  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:54.892  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
,11-23 17:18:54.892  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:18:54.892  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.892  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:54.893  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:18:54.893  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.893  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:18:54.893  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:18:54.894  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 17:18:54.894  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:18:54.894  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9585a5b not in the list
11-23 17:18:54.895  5640  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-23 17:18:54.895  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 17:18:54.895  5640  5687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-23 17:18:54.895  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 17:18:54.895  5640  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-23 17:18:54.895  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 17:18:54.897  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 17:18:54.897  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-23 17:18:54.897  5640  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-23 17:18:54.897  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 17:18:54.897  5640  5687 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-23 17:18:54.897  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 17:18:54.897  5640  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-23 17:18:54.898  5640  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-23 17:18:54.898  5640  5687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-23 17:18:54.898  5640  5687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-23 17:18:54.899  5640  5687 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-23 17:18:54.899  5640  5687 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-23 17:18:54.899  5640  5687 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-23 17:18:54.899  5640  5687 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-23 17:18:54.900  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:18:54.900  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d567a28 added. We now have 3 listener(s)
11-23 17:18:54.900  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 17:18:54.902  5640  5687 D BluetoothAdapter: enable(): BT is already enabled..!
,11-23 17:18:54.902   930  3890 D WifiService: setWifiEnabled: true pid=5640, uid=10077
11-23 17:18:54.902   930  3890 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 17:18:54.961  4681  4889 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-23 17:18:54.961  4681  4897 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-23 17:18:55.372  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 17:18:55.778   930  3009 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 17:18:56.121   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 17:18:59.908  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 17:18:59.909  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9fa6341 added. We now have 4 listener(s)
,11-23 17:18:59.909  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 17:18:59.921  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 17:18:59.922  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9fa6341 removed from the list
,11-23 17:18:59.922  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 17:18:59.924  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:18:59.924  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f2040e6 added. We now have 4 listener(s)
,11-23 17:18:59.924  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 17:18:59.929  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 17:18:59.929  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f2040e6 removed from the list
,11-23 17:18:59.929  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 17:18:59.930  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:18:59.931  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c65e627 added. We now have 4 listener(s)
11-23 17:18:59.931  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 17:18:59.934   930  3890 D WifiService: setWifiEnabled: false pid=5640, uid=10077
11-23 17:18:59.934   930  3890 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 17:18:59.940   930  3009 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-23 17:18:59.941   930  3009 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-23 17:18:59.941   930  3009 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 17:18:59.941   930  3009 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 17:18:59.950  4681  4752 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 17:18:59.951  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 17:18:59.951  4681  4752 D BluetoothAdapterProperties: Setting state to 13
11-23 17:18:59.951  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 17:18:59.951  4681  4752 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 17:18:59.952  4681  4752 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 17:18:59.952  4681  4752 I BluetoothAdapterState: Entering PendingCommandState
11-23 17:18:59.953  4681  4756 D BluetoothAdapterProperties: Scan Mode:20
11-23 17:18:59.954  4681  4752 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-23 17:18:59.956  4681  4681 D HeadsetService: Received stop request...Stopping profile...
,11-23 17:18:59.957   930  5402 D DhcpClient: Clearing IP address
11-23 17:18:59.958   508   912 D CommandListener: Clearing all IP addresses on wlan0
11-23 17:18:59.959  4681  4681 D A2dpService: Received stop request...Stopping profile...
11-23 17:18:59.959  4681  4907 D A2dpStateMachine: Exit Disconnected: -1
11-23 17:18:59.961  3163  3163 D BluetoothA2dp: Proxy object disconnected
11-23 17:18:59.961  3808  3832 D BluetoothHeadset: Proxy object disconnected
11-23 17:18:59.961  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 17:18:59.961  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 17:18:59.961  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:18:59.961  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:18:59.961  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 17:18:59.961  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 17:18:59.961  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 17:18:59.961  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 17:18:59.961  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 17:18:59.961  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 17:18:59.961  4681  4681 V BluetoothAdapterState: isTurningOff()=true
11-23 17:18:59.961  4681  4681 V BluetoothAdapterState: isTurningOn()=false
11-23 17:18:59.962  4681  4681 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 17:18:59.962  4681  4681 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:18:59.962  3163  3186 D BluetoothHeadset: Proxy object disconnected
11-23 17:18:59.962  3163  3163 D HeadsetProfile: Bluetooth service disconnected
11-23 17:18:59.962   930   930 D BluetoothHeadset: Proxy object disconnected
11-23 17:18:59.962   930   930 D BluetoothHeadset: Proxy object disconnected
11-23 17:18:59.962  4681  4681 D HidService: Received stop request...Stopping profile...
11-23 17:18:59.962  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 17:18:59.962   930   930 D BluetoothHeadset: Proxy object disconnected
11-23 17:18:59.962  4681  4681 D HidService: Stopping Bluetooth HidService
11-23 17:18:59.962  5640  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 17:18:59.962   930   930 D BluetoothA2dp: Proxy object disconnected
11-23 17:18:59.962  5640  5687 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-23 17:18:59.963  3163  3163 D BluetoothInputDevice: Proxy object disconnected
11-23 17:18:59.964  3163  3163 D HidProfile: Bluetooth service disconnected
11-23 17:18:59.965   508   912 D CommandListener: Setting iface cfg
11-23 17:18:59.966  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:18:59.966  4681  4681 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 17:18:59.967  4681  4681 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 17:18:59.967   930  5403 D DhcpClient: Receive thread stopped
11-23 17:18:59.968  4681  4681 D HealthService: Received stop request...Stopping profile...
,11-23 17:18:59.968  4681  4756 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 17:18:59.968  4681  4889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 17:18:59.969  4681  4889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 17:18:59.969  4681  4889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 17:18:59.969  4681  4756 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 17:18:59.970  4681  4681 V BluetoothAdapterState: isTurningOff()=true
11-23 17:18:59.970  4681  4681 V BluetoothAdapterState: isTurningOn()=false
11-23 17:18:59.970  4681  4681 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:18:59.970  4681  4681 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 17:18:59.971  4681  4756 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 17:18:59.971  4681  4889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 17:18:59.971  4681  4681 V BluetoothAdapterState: isTurningOff()=true
11-23 17:18:59.971  4681  4681 V BluetoothAdapterState: isTurningOn()=false
11-23 17:18:59.971  4681  4889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 17:18:59.971  4681  4681 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:18:59.971  4681  4681 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:18:59.971  4681  4889 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-23 17:18:59.971  4681  4889 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 17:18:59.971  4681  4889 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 17:18:59.972  4681  4681 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 17:18:59.972  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:18:59.972  4681  4889 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 17:18:59.972  4681  4681 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 17:18:59.972  4681  4756 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 17:18:59.972  4681  4681 D PanService: Received stop request...Stopping profile...
11-23 17:18:59.973  3163  3163 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-23 17:18:59.973  3163  3163 D PanProfile: Bluetooth service disconnected
11-23 17:18:59.974  4681  4681 D BluetoothMapService: Received stop request...Stopping profile...
11-23 17:18:59.974  4681  4681 D BluetoothMapService: stop()
11-23 17:18:59.975  4681  4681 D BluetoothMapAppObserver: deinitObservers()
11-23 17:18:59.975  4681  4681 D BluetoothMapAppObserver: removeReceiver()
11-23 17:18:59.976  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:18:59.976  3616  5456 V NativeCrypto: Read error: ssl=0x7f74c0f280: I/O error during system call, Connection timed out
11-23 17:18:59.976  4681  4681 V BluetoothAdapterState: isTurningOff()=true
11-23 17:18:59.976  4681  4681 V BluetoothAdapterState: isTurningOn()=false
11-23 17:18:59.976  4681  4681 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 17:18:59.976  4681  4681 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:18:59.977  4681  4681 D SapService: Received stop request...Stopping profile...
11-23 17:18:59.977  4681  4681 V SapService: stop()
,11-23 17:18:59.977  3616  5456 V NativeCrypto: SSL shutdown failed: ssl=0x7f74c0f280: I/O error during system call, Broken pipe
11-23 17:18:59.978  3163  3163 D BluetoothMap: Proxy object disconnected
11-23 17:18:59.978  3163  3163 D MapProfile: Bluetooth service disconnected
11-23 17:18:59.979  4681  4681 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 17:18:59.979  4681  4681 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 17:18:59.979   930  3240 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-23 17:18:59.979  4681  4681 V BluetoothAdapterState: isTurningOff()=true
11-23 17:18:59.980  4681  4681 V BluetoothAdapterState: isTurningOn()=false
11-23 17:18:59.980  4681  4681 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:18:59.980  4681  4681 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:18:59.980   930  5400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-23 17:18:59.980  4681  4681 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 17:18:59.980  4681  4681 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 17:18:59.981  4681  4681 D BluetoothMapService: MAP Service closeService in
11-23 17:18:59.981  4681  4681 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 17:18:59.981  4681  4681 D ObexServerSockets0: shutdown(block = true)
11-23 17:18:59.982  4681  4915 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-23 17:18:59.981  4681  4681 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 17:18:59.982  4681  4681 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 17:18:59.982  4681  4897 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-23 17:18:59.982  4681  4756 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 17:18:59.982  4681  4916 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 17:18:59.983  4681  4681 V BluetoothAdapterState: isTurningOff()=true
11-23 17:18:59.983  4681  4681 V BluetoothAdapterState: isTurningOn()=false
11-23 17:18:59.984  4681  4681 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:18:59.984  4681  4681 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:18:59.984  4681  4681 D BluetoothMapService: cleanup()
11-23 17:18:59.984  4681  4681 D BluetoothMapService: MAP Service closeService in
11-23 17:18:59.984   930  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 17:18:59.984   930  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-23 17:18:59.985  4681  4681 V BluetoothAdapterState: isTurningOff()=true
11-23 17:18:59.985  4681  4681 V BluetoothAdapterState: isTurningOn()=false
11-23 17:18:59.985  4681  4681 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:18:59.985  4681  4681 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:18:59.985  4681  4752 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 17:18:59.986  4681  4752 D BluetoothAdapterProperties: Setting state to 15
11-23 17:18:59.986  4681  4752 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 17:18:59.987  4681  4752 I BluetoothAdapterState: Entering BleOnState
11-23 17:18:59.987   534   534 E Parcel  : Reading a NULL string not supported here.
11-23 17:18:59.990   930  5400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-23 17:18:59.992   930  3011 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-23 17:18:59.993   930   930 D RttService: SCAN_AVAILABLE : 1
11-23 17:18:59.993  3778  3903 W QCNEJ   : |CORE| network lost: 100
,11-23 17:18:59.994   930  3116 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 17:18:59.994   930  3009 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-23 17:19:00.000   930  3009 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 17:19:00.001  3778  3903 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-23 17:19:00.003  4681  4681 I BtOppRfcommListener: stopping Accept Thread
11-23 17:19:00.003  4681  5336 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 17:19:00.004  4681  5336 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-23 17:19:00.006  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 17:19:00.006  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 17:19:00.006  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:19:00.006  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:19:00.006  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 17:19:00.006  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 17:19:00.006  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 17:19:00.006  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 17:19:00.006  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 17:19:00.006  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 17:19:00.007  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 17:19:00.007  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 17:19:00.015   930   943 I ActivityManager: Start proc 5705:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-23 17:19:00.016  3163  3185 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 17:19:00.017   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-23 17:19:00.017  3163  3185 D BluetoothMap: onBluetoothStateChange: up=false
11-23 17:19:00.018  3808  3835 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 17:19:00.018   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 17:19:00.019  3163  4015 D BluetoothPbap: onBluetoothStateChange: up=false
,11-23 17:19:00.020   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 17:19:00.020  3163  3186 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 17:19:00.021  3163  4015 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-23 17:19:00.022   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 17:19:00.022  3163  4015 D BluetoothPan: onBluetoothStateChange on: false
11-23 17:19:00.023  4681  4752 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 17:19:00.023  4681  4752 D BluetoothAdapterProperties: Setting state to 16
11-23 17:19:00.023  4681  4752 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 17:19:00.024  4681  4752 D BluetoothAdapterProperties: onBleDisable
11-23 17:19:00.024  4681  4752 I BluetoothAdapterState: Entering PendingCommandState
11-23 17:19:00.024  4681  4753 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 17:19:00.026  4681  4889 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 17:19:00.026  4681  4889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 17:19:00.026  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:19:00.027  4681  4756 D BluetoothAdapterProperties: Scan Mode:20
11-23 17:19:00.029  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 17:19:00.039   508   912 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 17:19:00.056  5705  5705 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-23 17:19:00.056  3616  5722 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-23 17:19:00.061   508   912 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 17:19:00.061   508   912 D CommandListener: Clearing all IP addresses on wlan0
,11-23 17:19:00.061   508   912 D TetherController: Setting IP forward enable = 0
,11-23 17:19:00.062   930  3011 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-23 17:19:00.063   930  3011 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 17:19:00.066   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-23 17:19:00.067   930  3009 D DhcpClient: doQuit
11-23 17:19:00.067   930  3009 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 17:19:00.068   930  5402 D DhcpClient: onQuitting
,11-23 17:19:00.070  3482  3482 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 17:19:00.070  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 17:19:00.071  5291  5291 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@480bffc and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-23 17:19:00.073  3998  3998 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-23 17:19:00.075  5063  5088 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 17:19:00.075  5063  5088 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 17:19:00.075  5063  5088 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 17:19:00.076  5063  5088 E SarControlService: no key has been found,reset the power
11-23 17:19:00.076  5063  5111 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 17:19:00.076  5063  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 17:19:00.076  5063  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-23 17:19:00.076  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-23 17:19:00.077  5101  5101 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-23 17:19:00.079  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 17:19:00.080  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 17:19:00.080  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:19:00.080  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:19:00.080  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 17:19:00.080  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 17:19:00.080  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 17:19:00.080  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 17:19:00.080  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 17:19:00.080  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 17:19:00.080  5063  5111 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 17:19:00.080  5063  5111 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 17:19:00.080  5063  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-23 17:19:00.080  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 17:19:00.080  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 17:19:00.081  5101  5101 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 17:19:00.081  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 17:19:00.083  5101  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6e330c2 HexData = [00000000ea03000000000000ffffffff]
11-23 17:19:00.083  5101  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 17:19:00.083  5101  5116 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-23 17:19:00.083  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 17:19:00.083  5063  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-23 17:19:00.087  5705  5705 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 17:19:00.091  3482  3482 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-23 17:19:00.091  5101  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6e330c2 HexData = [00000000eb03000000000000ffffffff]
11-23 17:19:00.091  5101  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-23 17:19:00.091  5101  5116 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-23 17:19:00.092  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 17:19:00.093  5063  5073 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 17:19:00.098   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6633141:true
11-23 17:19:00.099  3616  3616 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 17:19:00.099  3616  5718 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-23 17:19:00.101  3616  5718 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-23 17:19:00.104  3482  3482 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-23 17:19:00.106   508   905 W SocketClient: write error (Broken pipe)
11-23 17:19:00.106   508   905 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-23 17:19:00.106   508   905 W SocketListener: Error sending broadcast (Broken pipe)
,11-23 17:19:00.121  5705  5705 D LocalBluetoothProfileManager: Adding local MAP profile
11-23 17:19:00.123  5705  5705 D BluetoothMap: Create BluetoothMap proxy object
,11-23 17:19:00.129  5705  5705 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-23 17:19:00.131  3616  5722 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 17:19:00.134   508   912 E Netd    : netlink response contains error (No such file or directory)
,11-23 17:19:00.135   508   912 D TetherController: Setting IP forward enable = 0
11-23 17:19:00.135   930  3011 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-23 17:19:00.136   930  3011 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 17:19:00.137  5705  5705 D DockEventReceiver: finishStartingService: stopping service
,11-23 17:19:00.141  3616  5718 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,11-23 17:19:00.150  5705  5705 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 17:19:00.151  3482  3482 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 17:19:00.158  5705  5705 D DockEventReceiver: finishStartingService: stopping service
,11-23 17:19:00.159   930  3450 I ActivityManager: Killing 5431:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
11-23 17:19:00.161  3482  3482 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 17:19:00.177  3616  3616 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 17:19:00.188  4089  4089 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 17:19:00.190  4089  4089 D SystemUpdateService: onCreate
,11-23 17:19:00.193  4089  4089 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 17:19:00.200  4089  4089 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 17:19:00.204  4089  5428 I iu.UploadsManager: num queued entries: 0
,11-23 17:19:00.205  4089  5428 I iu.UploadsManager: num updated entries: 0
11-23 17:19:00.205  4089  5428 I iu.SyncManager: NEXT; no task
11-23 17:19:00.206  4089  5741 I SystemUpdateService: active receiver: enabled
,11-23 17:19:00.210  4089  4089 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-23 17:19:00.211  4089  4089 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 17:19:00.213  4089  5741 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 17:19:00.215  4089  5741 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 17:19:00.215  4089  5741 I SystemUpdateService: now status is 0 (complete)
11-23 17:19:00.215  4089  5741 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 17:19:00.215  4089  5741 I SystemUpdateService: file has been verified
,11-23 17:19:00.215  4089  5741 I SystemUpdateService: OTA package size = 21989297
,11-23 17:19:00.222   930  3190 I ActivityManager: Start proc 5743:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-23 17:19:00.225  4089  5741 I SystemUpdateService: showing system update notification
,11-23 17:19:00.231  4681  4756 I bt_hci  : shut_down
,11-23 17:19:00.234  4681  4760 I bt_vendor: low_power_mode_cb
,11-23 17:19:00.235  4681  4760 D bt_hwcfg: hw_epilog_process
,11-23 17:19:00.238  4681  4760 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 17:19:00.238  4681  4760 I bt_vendor: epilog_cb
11-23 17:19:00.238   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 17:19:00.238  4681  4760 I bt_hci  : epilog_finished_callback
,11-23 17:19:00.239  4089  4089 D SystemUpdateService: onDestroy
11-23 17:19:00.241  4681  4756 I bt_hci_h4: hal_close
11-23 17:19:00.241  4681  4756 I bt_userial_vendor: device fd = 54 close
,11-23 17:19:00.256  5743  5743 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-23 17:19:00.259  5743  5743 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 17:19:00.263  4478  4478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 17:19:00.263   930  3009 D wifi    : In wifi stop Hal
,11-23 17:19:00.263   930  3009 D wifi    : halHandle = 0x7f5e912900, mVM = 0x7f7af4d140, mCls = 0x100a02
11-23 17:19:00.263   930  3481 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 17:19:00.263   930  3481 D WifiHAL : Got a signal to exit!!!
11-23 17:19:00.263   930  3481 I WifiHAL : Exit wifi_event_loop
11-23 17:19:00.264   930  3009 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-23 17:19:00.264   930  3009 E WifiHAL : Event processing terminated
11-23 17:19:00.264   930  3009 D wifi    : In wifi cleaned up handler
11-23 17:19:00.264   930  3009 I WifiHAL : Internal cleanup completed
11-23 17:19:00.266  3983  4253 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 17:19:00.266  5743  5743 D SprintDMHelper: simOperator: 
,11-23 17:19:00.266  5743  5743 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-23 17:19:00.267  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 17:19:00.278  4478  5755 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-23 17:19:00.288   930  3481 D wifi    : set interface wlan0 flags (DOWN)
,11-23 17:19:00.288   930  3009 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 17:19:00.291   930  3240 I ActivityManager: Start proc 5756:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-23 17:19:00.292   930  3240 I ActivityManager: Killing 5291:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-23 17:19:00.328  5756  5756 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-23 17:19:00.335   930  3190 I ActivityManager: Killing 3919:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-23 17:19:00.354  4681  4753 D bt_stack_manager: event_shut_down_stack finished.
,11-23 17:19:00.354  4681  4752 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 17:19:00.356  4681  4752 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-23 17:19:00.356  4681  4681 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 17:19:00.356  4681  4681 D BtGatt.GattService: Received stop request...Stopping profile...
11-23 17:19:00.357  4681  4681 D BtGatt.GattService: stop()
11-23 17:19:00.357  4681  4681 D BtGatt.AdvertiseManager: advertise clients cleared
,11-23 17:19:00.359  4681  4681 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:00.359  4681  4681 V BluetoothAdapterState: isTurningOn()=false
11-23 17:19:00.359  4681  4681 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:00.359  4681  4681 V BluetoothAdapterState: isBleTurningOff()=true
11-23 17:19:00.359  4681  4752 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 17:19:00.359  4681  4752 D BluetoothAdapterProperties: Setting state to 10
11-23 17:19:00.359  4681  4752 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 17:19:00.360  4681  4752 I BluetoothAdapterState: Entering OffState
,11-23 17:19:00.361   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 17:19:00.367  4681  4681 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 17:19:00.367  4681  4681 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 17:19:00.367  4681  4681 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 17:19:00.368  4681  4753 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-23 17:19:00.379  4681  4753 D bt_stack_manager: event_clean_up_stack finished.
11-23 17:19:00.379  4681  4681 I art     : System.exit called, status: 0
11-23 17:19:00.379  4681  4681 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-23 17:19:00.402   930  5768 I ActivityManager: Process com.android.bluetooth (pid 4681) has died
,11-23 17:19:00.491   930   947 D Tethering: InitialState.processMessage what=4
,11-23 17:19:00.497   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 17:19:04.965   930  5768 D WifiService: setWifiEnabled: true pid=5640, uid=10077
,11-23 17:19:04.965   930  5768 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 17:19:04.975   508   912 D SoftapController: Softap fwReload - Ok
,11-23 17:19:04.978   508   912 D CommandListener: Setting iface cfg
,11-23 17:19:04.979   508   912 D CommandListener: Trying to bring down wlan0
11-23 17:19:04.980   508   912 D CommandListener: Clearing all IP addresses on wlan0
11-23 17:19:04.983   930  3009 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 17:19:05.572   930  3009 D wifi    : set interface wlan0 flags (UP)
,11-23 17:19:05.576   930  3009 I WifiHAL : Initializing wifi
,11-23 17:19:05.576   930  3009 I WifiHAL : Creating socket
,11-23 17:19:05.579   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 17:19:05.585   930  3009 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-23 17:19:05.585   930  3009 D wifi    : Did set static halHandle = 0x7f5e912900
11-23 17:19:05.585   930  3009 D wifi    : halHandle = 0x7f5e912900, mVM = 0x7f7af4d140, mCls = 0x101942
,11-23 17:19:05.585   930  3009 D wifi    : array field set
11-23 17:19:05.586   930  3009 I WifiNative-HAL: interface[0] = wlan0
,11-23 17:19:05.588   930  5776 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547047418112
11-23 17:19:05.588   930  5776 D wifi    : waitForHalEvents called, vm = 0x7f7af4d140, obj = 0x101942, env = 0x7f5ee1aec0
,11-23 17:19:05.671  5777  5777 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 17:19:05.689   930  3009 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 17:19:05.697  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 17:19:05.753  5777  5777 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 17:19:05.765  5777  5777 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 17:19:05.765  5777  5777 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 17:19:05.777   930  3009 D WifiConfigStore: Loading config and enabling all networks 
,11-23 17:19:05.780  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 17:19:05.780  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 17:19:05.780  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:19:05.780  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:19:05.780  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 17:19:05.780  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 17:19:05.780  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 17:19:05.780  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 17:19:05.780  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 17:19:05.780  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 17:19:05.780  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 17:19:05.780  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 17:19:05.794   930  3009 D WifiConfigStore: loaded 0 passpoint configs
,11-23 17:19:05.794   930  3009 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-23 17:19:05.795   930  3009 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-23 17:19:05.795   930  3009 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-23 17:19:05.795   930  3009 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-23 17:19:05.796   930  3009 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-23 17:19:05.796   930  3009 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-23 17:19:05.797   930  3009 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-23 17:19:05.797   930  3009 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-23 17:19:05.797   930  3009 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-23 17:19:05.797   930  3009 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-23 17:19:05.797   930  3009 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-23 17:19:05.797   930  3009 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-23 17:19:05.799   930  3009 D WifiNative-HAL: Setting external_sim to 1
,11-23 17:19:05.799   930  3009 D wifi    : setting dfs flag to true, 0x7f5dffeae0
11-23 17:19:05.799   930  3009 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 17:19:05.799  4478  4478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 17:19:05.799   930  3009 D wifi    : setting scan oui 0x7f5dffeae0
11-23 17:19:05.799   930  3009 D WifiHAL : Sending mac address OUI
,11-23 17:19:05.802   930  3009 E native  : do suspend false
,11-23 17:19:05.808   930  3009 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 17:19:05.809   930   930 D RttService: SCAN_AVAILABLE : 3
11-23 17:19:05.809   930  3116 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 17:19:05.812   508   912 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-23 17:19:05.813   508   912 D CommandListener: Setting iface cfg
,11-23 17:19:05.815   930  3008 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
11-23 17:19:05.816   930  3008 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 17:19:05.822   930  3008 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 17:19:05.826   930  3008 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-23 17:19:05.826   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=210989 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-23 17:19:08.858  5777  5777 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 17:19:08.864  5777  5777 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 17:19:08.944   930  3009 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 17:19:08.945   930  3009 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-23 17:19:08.945   930  3009 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 17:19:08.957   930  3009 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 17:19:08.994   930  3009 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 17:19:09.001  5777  5777 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 17:19:09.422  5777  5777 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 17:19:09.457  5777  5777 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 17:19:09.459  5777  5777 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 17:19:09.468   930  3009 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 17:19:09.468   930  3009 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 17:19:09.469   930  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 17:19:09.486   930  3009 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 17:19:09.501   508   912 D CommandListener: Setting iface cfg
,11-23 17:19:09.507   930  3009 D WifiStateMachine: Start Dhcp Watchdog 2
,11-23 17:19:09.512   930  5783 D DhcpClient: Receive thread started
,11-23 17:19:09.516   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-23 17:19:09.517   930  3009 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-23 17:19:09.517   930  3011 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-23 17:19:09.597   930  3009 E native  : do suspend false
,11-23 17:19:09.611   930  5782 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 17:19:09.624   930  5783 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172626, domain null
,11-23 17:19:09.625   930  5782 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172626 seconds
,11-23 17:19:09.627   930  5782 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-23 17:19:09.642   930  5783 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 17:19:09.643   930  5782 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-23 17:19:09.646   508   912 D CommandListener: Setting iface cfg
,11-23 17:19:09.651   930  3009 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 17:19:09.656   930  5782 D DhcpClient: Scheduling renewal in 86399s
,11-23 17:19:09.666   930  3009 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-23 17:19:09.668   930  3009 D WifiConfigStore: No blacklist allowed without epno enabled
11-23 17:19:09.670   930  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-23 17:19:09.672   930  3011 D ConnectivityService: Adding iface wlan0 to network 101
,11-23 17:19:09.683   930  3009 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 17:19:09.732   930  3011 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-23 17:19:09.733   930  3011 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-23 17:19:09.738   930  3011 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-23 17:19:09.741   930  3011 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-23 17:19:09.743   930  3011 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-23 17:19:09.751   930  3011 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 17:19:09.756   930  3011 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-23 17:19:09.756   930  3011 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-23 17:19:09.756   930  3011 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,11-23 17:19:09.756   930  3011 D ConnectivityService:    accepting network in place of null
11-23 17:19:09.756   930  3009 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 17:19:09.756   930  3009 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 17:19:09.757   930  3011 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 17:19:09.769   930  5781 D NetlinkSocketObserver: NeighborEvent{elapsedMs=214932, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 17:19:09.780   508   912 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 17:19:09.804   508   912 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 17:19:09.807   930  3011 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-23 17:19:09.807   930  3011 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 17:19:09.807  3778  3903 W QCNEJ   : |CORE| network available: 101
11-23 17:19:09.808   930  3011 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-23 17:19:09.809   930   947 D Tethering: MasterInitialState.processMessage what=3
11-23 17:19:09.810  3778  3903 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-23 17:19:09.811  3778  3903 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 17:19:09.812  3778  3903 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-23 17:19:09.814  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 17:19:09.814  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 17:19:09.814  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:19:09.814  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:19:09.814  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 17:19:09.814  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 17:19:09.814  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 17:19:09.814  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 17:19:09.814  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 17:19:09.814  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 17:19:09.814  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 17:19:09.814  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 17:19:09.823  5063  5088 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 17:19:09.824  5063  5088 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 17:19:09.824  5063  5088 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 17:19:09.824  5063  5088 E SarControlService: no key has been found,reset the power
11-23 17:19:09.824  5063  5111 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 17:19:09.824  5063  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 17:19:09.824  5063  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 17:19:09.825  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 17:19:09.825  5101  5101 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 17:19:09.827  5063  5111 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 17:19:09.827  5063  5111 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-23 17:19:09.827  5063  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 17:19:09.827  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 17:19:09.827  5101  5101 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 17:19:09.828  3998  3998 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-23 17:19:09.832  4089  4089 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 17:19:09.834  5101  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6e330c2 HexData = [00000000ec03000000000000ffffffff]
,11-23 17:19:09.834  5101  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 17:19:09.834  5101  5116 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-23 17:19:09.834  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 17:19:09.834  5063  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-23 17:19:09.835   930  5780 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:802::200e
,11-23 17:19:09.837  4089  4089 D SystemUpdateService: onCreate
,11-23 17:19:09.841  4089  4089 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 17:19:09.843  5101  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6e330c2 HexData = [00000000ed03000000000000ffffffff]
11-23 17:19:09.844  5101  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 17:19:09.844  5101  5116 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-23 17:19:09.844  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 17:19:09.844  5063  5073 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-23 17:19:09.849  4089  4089 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 17:19:09.857  4089  5428 I iu.UploadsManager: num queued entries: 0
,11-23 17:19:09.857  4089  5428 I iu.UploadsManager: num updated entries: 0
11-23 17:19:09.858  4089  5428 I iu.SyncManager: NEXT; no task
,11-23 17:19:09.861  4089  4089 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 17:19:09.862  4089  4089 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 17:19:09.864  5743  5743 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 17:19:09.868  5743  5743 D SprintDMHelper: simOperator: 
11-23 17:19:09.868  5743  5743 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 17:19:09.876  4089  5793 I SystemUpdateService: active receiver: enabled
,11-23 17:19:09.889   930  5780 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 16:19:09 GMT], X-Android-Received-Millis=[1479917949888], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479917949865]}
,11-23 17:19:09.890   930  3011 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 17:19:09.890   930  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-23 17:19:09.890   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 17:19:09.891   930  3011 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 17:19:09.898  4089  5793 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 17:19:09.903  4089  5793 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-23 17:19:09.903  4089  5793 I SystemUpdateService: now status is 0 (complete)
11-23 17:19:09.903  4089  5793 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 17:19:09.904  4089  5793 I SystemUpdateService: file has been verified
11-23 17:19:09.904  4089  5793 I SystemUpdateService: OTA package size = 21989297
,11-23 17:19:09.909  4089  5793 I SystemUpdateService: showing system update notification
,11-23 17:19:09.917   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 17:19:09.918  4089  4089 D SystemUpdateService: onDestroy
,11-23 17:19:09.975   930  3190 D WifiService: setWifiEnabled: false pid=5640, uid=10077
,11-23 17:19:09.975   930  3190 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-23 17:19:09.976   930  3009 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-23 17:19:09.976   930  3009 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-23 17:19:09.976   930  3009 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 17:19:09.976   930  3009 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 17:19:09.986   930  5782 D DhcpClient: Clearing IP address
11-23 17:19:09.987   508   912 D CommandListener: Clearing all IP addresses on wlan0
11-23 17:19:09.988   508   912 D CommandListener: Setting iface cfg
,11-23 17:19:09.994  3616  5803 V NativeCrypto: Read error: ssl=0x7f74bb9e00: I/O error during system call, Connection timed out
,11-23 17:19:09.995  3616  5803 V NativeCrypto: SSL shutdown failed: ssl=0x7f74bb9e00: I/O error during system call, Broken pipe
11-23 17:19:09.996  4478  5798 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
11-23 17:19:09.997   930  5783 D DhcpClient: Receive thread stopped
11-23 17:19:09.998   930  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 17:19:09.998   930  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-23 17:19:10.002   534   534 E Parcel  : Reading a NULL string not supported here.
11-23 17:19:10.007   930   930 D RttService: SCAN_AVAILABLE : 1
,11-23 17:19:10.007   930  3116 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 17:19:10.008   930  3011 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-23 17:19:10.008   930  3009 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-23 17:19:10.010  3778  3903 W QCNEJ   : |CORE| network lost: 101
11-23 17:19:10.011  3778  3903 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-23 17:19:10.012   930  3009 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
11-23 17:19:10.013  4478  5798 ,W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
11-23 17:19:10.013  4478  5798 W Babel_NetworkConnectionCheckingService: 	... 21 more
11-23 17:19:10.014  4478  5798 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-23 17:19:10.029   508   912 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 17:19:10.048   508   912 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-23 17:19:10.049   508   912 D CommandListener: Clearing all IP addresses on wlan0
11-23 17:19:10.049   930  3011 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-23 17:19:10.049   930  3011 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 17:19:10.051   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-23 17:19:10.054   930  3009 D DhcpClient: doQuit
,11-23 17:19:10.054   930  3009 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 17:19:10.054   930  5782 D DhcpClient: onQuitting
11-23 17:19:10.055  5777  5777 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 17:19:10.055  3998  3998 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-23 17:19:10.059  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 17:19:10.059  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 17:19:10.059  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:19:10.059  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:19:10.059  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 17:19:10.059  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 17:19:10.059  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 17:19:10.059  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 17:19:10.059  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 17:19:10.059  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 17:19:10.059  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 17:19:10.059  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 17:19:10.060  5063  5088 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 17:19:10.061  5063  5088 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 17:19:10.061  5063  5088 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 17:19:10.062  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:19:10.062  4089  4089 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 17:19:10.064  5777  5777 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-23 17:19:10.065  4089  4089 D SystemUpdateService: onCreate
11-23 17:19:10.061  5063  5088 E SarControlService: no key has been found,reset the power
11-23 17:19:10.066  5063  5111 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 17:19:10.066  5063  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 17:19:10.066  5063  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 17:19:10.066  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 17:19:10.066  5101  5101 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-23 17:19:10.068  5063  5111 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 17:19:10.068  5063  5111 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 17:19:10.068  5063  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 17:19:10.068  5777  5777 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-23 17:19:10.068  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 17:19:10.068  5101  5101 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 17:19:10.072  4089  4089 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-23 17:19:10.072  5101  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6e330c2 HexData = [00000000ee03000000000000ffffffff]
11-23 17:19:10.073  5101  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 17:19:10.073  5101  5116 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-23 17:19:10.073  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 17:19:10.073  5063  5073 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 17:19:10.074  5101  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6e330c2 HexData = [00000000ef03000000000000ffffffff]
11-23 17:19:10.074  5101  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 17:19:10.074  5101  5116 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-23 17:19:10.075  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 17:19:10.075  5063  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-23 17:19:10.081  4089  5812 I SystemUpdateService: active receiver: enabled
11-23 17:19:10.083  4089  4089 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 17:19:10.087  4089  5428 I iu.UploadsManager: num queued entries: 0
,11-23 17:19:10.088  4089  5428 I iu.UploadsManager: num updated entries: 0
11-23 17:19:10.088  4089  5428 I iu.SyncManager: NEXT; no task
,11-23 17:19:10.091  4089  4089 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 17:19:10.093  4089  4089 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 17:19:10.095  5743  5743 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-23 17:19:10.099  5743  5743 D SprintDMHelper: simOperator: 
11-23 17:19:10.099  5743  5743 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 17:19:10.106   508   912 E Netd    : netlink response contains error (No such file or directory)
,11-23 17:19:10.106  4089  5812 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-23 17:19:10.107   930  3011 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-23 17:19:10.109  4478  5816 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-23 17:19:10.110  5777  5777 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 17:19:10.114  4089  5812 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 17:19:10.114  4089  5812 I SystemUpdateService: now status is 0 (complete)
,11-23 17:19:10.116  4089  5812 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-23 17:19:10.116  4089  5812 I SystemUpdateService: file has been verified
11-23 17:19:10.119  4089  5812 I SystemUpdateService: OTA package size = 21989297
,11-23 17:19:10.127  5777  5777 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-23 17:19:10.127  4089  5812 I SystemUpdateService: showing system update notification
,11-23 17:19:10.135   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 17:19:10.136  4089  4089 D SystemUpdateService: onDestroy
,11-23 17:19:10.229   930  3009 D wifi    : In wifi stop Hal
,11-23 17:19:10.229   930  3009 D wifi    : halHandle = 0x7f5e912900, mVM = 0x7f7af4d140, mCls = 0x101942
,11-23 17:19:10.229   930  5776 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 17:19:10.229   930  5776 D WifiHAL : Got a signal to exit!!!
,11-23 17:19:10.229   930  5776 I WifiHAL : Exit wifi_event_loop
,11-23 17:19:10.230   930  3009 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-23 17:19:10.230   930  3009 E WifiHAL : Event processing terminated
11-23 17:19:10.230   930  3009 D wifi    : In wifi cleaned up handler
11-23 17:19:10.230   930  3009 I WifiHAL : Internal cleanup completed
11-23 17:19:10.231  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:19:10.231  4478  4478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 17:19:10.232  3983  4253 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 17:19:10.258   930  5776 D wifi    : set interface wlan0 flags (DOWN)
,11-23 17:19:10.259   930  3009 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 17:19:10.466   930   947 D Tethering: InitialState.processMessage what=4
,11-23 17:19:10.473   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 17:19:10.808   930  3011 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-23 17:19:13.705   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 17:19:13.705   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 17:19:14.861  3688  3887 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-23 17:19:14.861  3688  3887 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-23 17:19:14.889  3616  3616 I ConfigService: onCreate
,11-23 17:19:15.010   930   947 I ActivityManager: Start proc 5819:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 17:19:15.101  5819  5819 D AdapterServiceConfig: Adding HeadsetService
,11-23 17:19:15.101  5819  5819 D AdapterServiceConfig: Adding A2dpService
11-23 17:19:15.101  5819  5819 D AdapterServiceConfig: Adding HidService
11-23 17:19:15.101  5819  5819 D AdapterServiceConfig: Adding HealthService
11-23 17:19:15.101  5819  5819 D AdapterServiceConfig: Adding PanService
,11-23 17:19:15.102  5819  5819 D AdapterServiceConfig: Adding GattService
11-23 17:19:15.102  5819  5819 D AdapterServiceConfig: Adding BluetoothMapService
11-23 17:19:15.102  5819  5819 D AdapterServiceConfig: Adding SapService
,11-23 17:19:15.114   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af88992:true
,11-23 17:19:15.114  5819  5819 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 17:19:15.117  5819  5819 I bt_bluedroid: init
,11-23 17:19:15.117  5819  5831 I BluetoothAdapterState: Entering OffState
,11-23 17:19:15.119  5819  5832 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-23 17:19:15.119  5819  5832 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 17:19:15.119  5819  5832 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 17:19:15.119  5819  5832 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-23 17:19:15.119  5819  5819 I bt_bluedroid: get_profile_interface socket
11-23 17:19:15.121  5819  5819 I bt_bluedroid: get_profile_interface sdp
11-23 17:19:15.121  5819  5835 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-23 17:19:15.126  5819  5835 D BluetoothAdapterProperties: Name is: Nexus 6P
11-23 17:19:15.127  5819  5830 I bt_bluedroid: config_hci_snoop_log
,11-23 17:19:15.128   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 17:19:15.132  5819  5831 D BluetoothAdapterState: Current state: OFF, message: 0
,11-23 17:19:15.132  5819  5831 D BluetoothAdapterProperties: Setting state to 14
11-23 17:19:15.132  5819  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 17:19:15.134  5819  5831 D BluetoothBondStateMachine: make
,11-23 17:19:15.135  5819  5836 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 17:19:15.137  5819  5831 I BluetoothAdapterState: Entering PendingCommandState
,11-23 17:19:15.138  5819  5819 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 17:19:15.140  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
11-23 17:19:15.141  5819  5819 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 17:19:15.141  5819  5819 D BtGatt.GattService: Received start request. Starting profile...
,11-23 17:19:15.141  5819  5819 D BtGatt.GattService: start()
11-23 17:19:15.141  5819  5819 I bt_bluedroid: get_profile_interface gatt
11-23 17:19:15.143  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
11-23 17:19:15.143  5819  5819 D BtGatt.AdvertiseManager: advertise manager created
,11-23 17:19:15.147  5819  5819 V BluetoothAdapterState: isTurningOff()=false
,11-23 17:19:15.147  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-23 17:19:15.147  5819  5819 V BluetoothAdapterState: isBleTurningOn()=true
11-23 17:19:15.147  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:15.147  5819  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 17:19:15.148  5819  5831 I bt_bluedroid: bt_bluedroid
11-23 17:19:15.148  5819  5832 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-23 17:19:15.149  5819  5832 I bt_hci  : start_up
,11-23 17:19:15.153  5819  5832 I bt_vendor: alloc value 0xf4149871,
11-23 17:19:15.153  5819  5832 I bt_vendor: init
11-23 17:19:15.153  5819  5832 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 17:19:15.153  5819  5832 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 17:19:15.262  5819  5832 D bt_hci  : start_up starting async portion
,11-23 17:19:15.262  5819  5839 I bt_hci  : event_finish_startup
11-23 17:19:15.262  5819  5839 I bt_hci_h4: hal_open
11-23 17:19:15.262  5819  5839 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 17:19:15.265  5819  5839 I bt_userial_vendor: device fd = 54 open
,11-23 17:19:15.263  5840  5840 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 17:19:15.278  5819  5839 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 17:19:15.281  5819  5839 D bt_hwcfg: Chipset BCM4358A3
11-23 17:19:15.281  5819  5839 D bt_hwcfg: Target name = [BCM4358A3]
,11-23 17:19:15.282  5819  5839 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 17:19:15.662  5819  5839 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 17:19:15.663  5819  5839 D bt_hwcfg: Settlement delay -- 100 ms
,11-23 17:19:15.663  5819  5839 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 17:19:15.796  5819  5839 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-23 17:19:15.797  5819  5839 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-23 17:19:15.798  5819  5839 I bt_hwcfg: vendor lib fwcfg completed
11-23 17:19:15.798  5819  5839 I bt_vendor: firmware callback
11-23 17:19:15.798  5819  5839 I bt_hci  : firmware_config_callback
,11-23 17:19:15.806  5819  5842 I bt_btu  : btu_task pending for preload complete event
,11-23 17:19:15.806  5819  5842 I bt_btu_task: Bluetooth chip preload is complete
11-23 17:19:15.807  5819  5842 I bt_btu  : btu_task received preload complete event
,11-23 17:19:15.815  5819  5842 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 17:19:15.815  5819  5842 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-23 17:19:15.815  5819  5842 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 17:19:15.815  5819  5842 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 17:19:15.815  5819  5842 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-23 17:19:15.816  5819  5842 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 17:19:15.816  5819  5842 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-23 17:19:15.816  5819  5842 I         : BTE_InitTraceLevels -- TRC_BTM
,11-23 17:19:15.816  5819  5842 I         : BTE_InitTraceLevels -- TRC_GAP
11-23 17:19:15.816  5819  5842 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 17:19:15.816  5819  5842 I         : BTE_InitTraceLevels -- TRC_SDP
,11-23 17:19:15.817  5819  5842 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 17:19:15.817  5819  5842 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 17:19:15.817  5819  5842 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 17:19:15.817  5819  5842 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 17:19:15.897  5819  5842 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40c7549
,11-23 17:19:15.897  5819  5842 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40c7549 
,11-23 17:19:15.917  5819  5835 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 17:19:15.919  5819  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 17:19:15.919  5819  5835 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 17:19:15.922  5819  5835 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 17:19:15.925  5819  5835 D BluetoothAdapterProperties: Scan Mode:20
11-23 17:19:15.925  5819  5835 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 17:19:15.925  5819  5835 D bt_hci  : do_postload posting postload work item
11-23 17:19:15.925  5819  5839 I bt_hci  : event_postload
11-23 17:19:15.925  5819  5839 I bt_vendor: sco_config_cb
11-23 17:19:15.926  5819  5839 I bt_hci  : sco_config_callback postload finished.
11-23 17:19:15.928  5819  5835 D bt_bte_conf: Device ID record 1 : primary
11-23 17:19:15.929  5819  5835 D bt_bte_conf:   vendorId            = 000f
,11-23 17:19:15.929  5819  5835 D bt_bte_conf:   vendorIdSource      = 0001
11-23 17:19:15.929  5819  5835 D bt_bte_conf:   product             = 1200
11-23 17:19:15.929  5819  5835 D bt_bte_conf:   version             = 1436
11-23 17:19:15.929  5819  5835 D bt_bte_conf:   clientExecutableURL = 
11-23 17:19:15.929  5819  5835 D bt_bte_conf:   serviceDescription  = 
,11-23 17:19:15.929  5819  5835 D bt_bte_conf:   documentationURL    = 
11-23 17:19:15.929  5819  5835 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 17:19:15.930  5819  5832 D bt_stack_manager: event_start_up_stack finished
11-23 17:19:15.931  5819  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-23 17:19:15.931  5819  5831 D BluetoothAdapterProperties: Setting state to 15
11-23 17:19:15.931  5819  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 17:19:15.933  5819  5831 I BluetoothAdapterState: Entering BleOnState
11-23 17:19:15.932  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:19:15.937  5819  5831 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 17:19:15.937  5819  5831 D BluetoothAdapterProperties: Setting state to 11
,11-23 17:19:15.937  5819  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 17:19:15.938  5819  5839 I bt_vendor: low_power_mode_cb
,11-23 17:19:15.944  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
,11-23 17:19:15.945  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:19:15.945  5819  5819 D HeadsetService: Received start request. Starting profile...
,11-23 17:19:15.947  5819  5819 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 17:19:15.947  5819  5819 D HeadsetStateMachine: make
,11-23 17:19:15.957  5819  5831 I BluetoothAdapterState: Entering PendingCommandState
,11-23 17:19:15.959  5819  5819 D HeadsetStateMachine: max_hf_connections = 1
,11-23 17:19:15.959  5819  5819 I bt_bluedroid: get_profile_interface handsfree
11-23 17:19:15.959  5819  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-23 17:19:15.960  5819  5835 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 17:19:15.963  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
,11-23 17:19:15.964  5819  5819 D A2dpService: Received start request. Starting profile...
,11-23 17:19:15.964  5819  5819 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 17:19:15.965  5819  5819 I bt_bluedroid: get_profile_interface avrcp
,11-23 17:19:15.970  5819  5819 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-23 17:19:15.970  5819  5819 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 17:19:15.971  5819  5819 D A2dpStateMachine: make
,11-23 17:19:15.972  5819  5819 I bt_bluedroid: get_profile_interface a2dp
,11-23 17:19:15.972  5819  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-23 17:19:15.974  5819  5850 D A2dpStateMachine: Enter Disconnected: -2
,11-23 17:19:15.974  5819  5819 I BluetoothHidServiceJni: classInitNative: succeeds
,11-23 17:19:15.975  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
,11-23 17:19:15.976  5705  5705 D BluetoothInputDevice: Proxy object connected
11-23 17:19:15.977  5819  5819 D HidService: Received start request. Starting profile...
11-23 17:19:15.977  5819  5819 I bt_bluedroid: get_profile_interface hidhost
11-23 17:19:15.977  5819  5819 D HidService: setHidService(): set to: null
11-23 17:19:15.977  5705  5705 D HidProfile: Bluetooth service connected
11-23 17:19:15.978  5819  5819 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 17:19:15.978  5819  5835 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40a856d
,11-23 17:19:15.978  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
11-23 17:19:15.978  5819  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 17:19:15.979  5819  5819 D HealthService: Received start request. Starting profile...
,11-23 17:19:15.980  5819  5819 I bt_bluedroid: get_profile_interface health
11-23 17:19:15.982  5819  5819 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 17:19:15.983  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
11-23 17:19:15.984  3616  3616 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 17:19:15.984  5819  5819 D PanService: Received start request. Starting profile...
,11-23 17:19:15.984  5819  5819 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 17:19:15.984  5819  5819 I bt_bluedroid: get_profile_interface pan
11-23 17:19:15.985  5705  5705 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 17:19:15.985  5819  5835 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 17:19:15.985  5705  5705 D PanProfile: Bluetooth service connected
,11-23 17:19:15.989  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
,11-23 17:19:15.990  5819  5819 D BluetoothMapService: Received start request. Starting profile...
,11-23 17:19:15.990  5819  5819 D BluetoothMapService: start()
11-23 17:19:15.993  5819  5819 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-23 17:19:15.993  5819  5819 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 17:19:15.994  5819  5819 D BluetoothMapAppObserver: createReceiver()
11-23 17:19:15.995  5819  5819 D BluetoothMapAppObserver: initObservers()
11-23 17:19:15.995  5819  5819 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 17:19:16.000  5705  5705 D BluetoothMap: Proxy object connected
,11-23 17:19:16.000  5705  5705 D MapProfile: Bluetooth service connected
11-23 17:19:16.001  5705  5705 D BluetoothMap: getConnectedDevices()
11-23 17:19:16.003  5819  5819 V SapService: SapBinder()
11-23 17:19:16.003  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
,11-23 17:19:16.003  5819  5819 D SapService: Received start request. Starting profile...
11-23 17:19:16.003  5819  5819 V SapService: start()
11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isTurningOff()=false
,11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:16.005  5819  5848 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:16.005  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:16.006  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 17:19:16.006  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:16.006  5819  5819 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:16.006  5819  5819 V BluetoothAdapterState: isTurningOn()=true
,11-23 17:19:16.006  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 17:19:16.006  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:16.006  5819  5819 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:16.007  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:16.007  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:16.007  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:16.008  5819  5819 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:16.008  5819  5819 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:16.008  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:16.008  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 17:19:16.008  5819  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 17:19:16.008  5819  5831 D BluetoothAdapterProperties: ScanMode =  20
11-23 17:19:16.008  5819  5831 D BluetoothAdapterProperties: State =  11
11-23 17:19:16.008  5819  5831 D BluetoothAdapterProperties: Setting state to 12
11-23 17:19:16.008  5819  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 17:19:16.009  5705  5705 D BluetoothMap: Bluetooth is Not enabled
11-23 17:19:16.010  3163  3186 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 17:19:16.010  5819  5835 D BluetoothAdapterProperties: Scan Mode:21
11-23 17:19:16.010  5819  5835 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 17:19:16.010  5819  5831 I BluetoothAdapterState: Entering OnState
,11-23 17:19:16.010  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 17:19:16.012   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 17:19:16.012  3163  3163 D BluetoothInputDevice: Proxy object connected
11-23 17:19:16.012  3163  3163 D HidProfile: Bluetooth service connected
11-23 17:19:16.013  3163  3185 D BluetoothMap: onBluetoothStateChange: up=true
11-23 17:19:16.014   930   930 D BluetoothA2dp: Proxy object connected
11-23 17:19:16.015  3808  4026 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 17:19:16.016  5705  5716 D BluetoothMap: onBluetoothStateChange: up=true
11-23 17:19:16.016  3163  3163 D BluetoothMap: Proxy object connected
,11-23 17:19:16.016  3163  3163 D MapProfile: Bluetooth service connected
11-23 17:19:16.016  3163  3163 D BluetoothMap: getConnectedDevices()
11-23 17:19:16.016   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 17:19:16.016  3163  4015 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 17:19:16.017  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 17:19:16.017  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:19:16.017  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:19:16.017  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 17:19:16.017  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 17:19:16.017  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 17:19:16.017  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 17:19:16.017  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 17:19:16.017  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 17:19:16.018  5705  5717 D BluetoothPan: onBluetoothStateChange on: true
11-23 17:19:16.018   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 17:19:16.018  5705  5716 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 17:19:16.020  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 17:19:16.020  3163  3185 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 17:19:16.020  3163  3186 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 17:19:16.022  3163  3163 D BluetoothA2dp: Proxy object connected
11-23 17:19:16.022  5819  5819 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 17:19:16.022  5705  5717 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 17:19:16.022   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 17:19:16.022  3163  3185 D BluetoothPan: onBluetoothStateChange on: true
11-23 17:19:16.023  5819  5819 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 17:19:16.024  5819  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 17:19:16.024  3163  3163 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 17:19:16.024  3163  3163 D PanProfile: Bluetooth service connected
11-23 17:19:16.025   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,11-23 17:19:16.025  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-23 17:19:16.027  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 17:19:16.027  5819  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 17:19:16.028  5705  5705 D LocalBluetoothProfileManager: Adding local A2DP profile
11-23 17:19:16.029  5819  5819 D ObexServerSockets: Succeed to create listening sockets 
11-23 17:19:16.029  5819  5819 D ObexServerSockets0: startAccept()
11-23 17:19:16.029  5819  5819 D ObexServerSockets0: prepareForNewConnect()
,11-23 17:19:16.031  5819  5819 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-23 17:19:16.031  5819  5819 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 17:19:16.032  5819  5857 D ObexServerSockets0: Accepting socket connection...
11-23 17:19:16.032  5819  5858 D ObexServerSockets0: Accepting socket connection...
11-23 17:19:16.032  5819  5819 D BluetoothMapService: onReceive
11-23 17:19:16.032  5819  5819 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 17:19:16.032  5819  5819 D BluetoothMapService: STATE_ON
,11-23 17:19:16.033  5705  5705 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-23 17:19:16.034  5819  5859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 17:19:16.035  5819  5859 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 17:19:16.035  5819  5859 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 17:19:16.039  5705  5705 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 17:19:16.042  5705  5705 D BluetoothA2dp: Proxy object connected
,11-23 17:19:16.048  3616  3616 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 17:19:16.054  3163  3163 D BluetoothPbap: Proxy object connected
11-23 17:19:16.054  3163  3163 D PbapServerProfile: Bluetooth service connected
,11-23 17:19:16.057  5705  5705 D DockEventReceiver: finishStartingService: stopping service
11-23 17:19:16.058  5705  5705 D BluetoothPbap: Proxy object connected
11-23 17:19:16.058  5819  5819 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 17:19:16.059  5819  5819 D ObexServerSockets0: prepareForNewConnect()
11-23 17:19:16.059  5705  5705 D PbapServerProfile: Bluetooth service connected
,11-23 17:19:16.061  5819  5863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 17:19:16.073  5819  5867 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 17:19:16.074  5819  5867 I BtOppRfcommListener: Accept thread started.
,11-23 17:19:16.117  3808  3832 D BluetoothHeadset: Proxy object connected
,11-23 17:19:16.118  3163  3185 D BluetoothHeadset: Proxy object connected
11-23 17:19:16.118  3163  3163 D HeadsetProfile: Bluetooth service connected
11-23 17:19:16.118   930   930 D BluetoothHeadset: Proxy object connected
11-23 17:19:16.118   930   930 D BluetoothHeadset: Proxy object connected
11-23 17:19:16.118   930   930 D BluetoothHeadset: Proxy object connected
11-23 17:19:16.118   930   947 D BluetoothHeadset: Proxy object connected
11-23 17:19:16.121  3163  3186 D BluetoothHeadset: Proxy object connected
11-23 17:19:16.121  3163  3163 D HeadsetProfile: Bluetooth service connected
,11-23 17:19:16.123   930   947 D BluetoothHeadset: Proxy object connected
,11-23 17:19:16.136  5705  5717 D BluetoothHeadset: Proxy object connected
,11-23 17:19:16.137  5705  5705 D HeadsetProfile: Bluetooth service connected
,11-23 17:19:17.762   930  3011 D ConnectivityService: handlePromptUnvalidated 101
,11-23 17:19:19.920  3616  3616 I ConfigService: onDestroy
,11-23 17:19:19.989  5819  5831 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 17:19:19.990  5819  5831 D BluetoothAdapterProperties: Setting state to 13
11-23 17:19:19.990  5819  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 17:19:19.991  5819  5831 D BluetoothAdapterProperties: onBluetoothDisable()
,11-23 17:19:19.992  5819  5831 I BluetoothAdapterState: Entering PendingCommandState
,11-23 17:19:19.997  5819  5819 D BluetoothMapService: onReceive
,11-23 17:19:19.997  5819  5819 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 17:19:19.998  5819  5819 D BluetoothMapService: STATE_TURNING_OFF
11-23 17:19:19.998  5819  5819 D BluetoothMapService: MAP Service closeService in
11-23 17:19:19.998  5819  5819 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 17:19:19.998  5819  5819 D ObexServerSockets0: shutdown(block = true)
11-23 17:19:20.000  5819  5819 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 17:19:20.000  5819  5857 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-23 17:19:20.000  5819  5819 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-23 17:19:20.000  5819  5844 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-23 17:19:20.001  5819  5835 D BluetoothAdapterProperties: Scan Mode:20
,11-23 17:19:20.001  5819  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-23 17:19:20.002  5819  5858 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 17:19:20.007  5705  5705 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 17:19:20.009  5819  5819 I BtOppRfcommListener: stopping Accept Thread
11-23 17:19:20.009  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 17:19:20.009  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 17:19:20.009  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:19:20.009  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:19:20.009  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 17:19:20.009  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 17:19:20.009  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 17:19:20.009  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 17:19:20.009  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 17:19:20.009  5640  5640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 17:19:20.010  5819  5867 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 17:19:20.011  5640  5640 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 17:19:20.011  5640  5640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 17:19:20.014  5819  5867 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-23 17:19:20.016  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:19:20.020  5819  5819 D HeadsetService: Received stop request...Stopping profile...
11-23 17:19:20.021  5705  5705 D DockEventReceiver: finishStartingService: stopping service
11-23 17:19:20.022  3808  4050 D BluetoothHeadset: Proxy object disconnected
11-23 17:19:20.022  3163  4015 D BluetoothHeadset: Proxy object disconnected
11-23 17:19:20.022  5819  5819 D A2dpService: Received stop request...Stopping profile...
11-23 17:19:20.023   930   930 D BluetoothHeadset: Proxy object disconnected
11-23 17:19:20.023  5819  5850 D A2dpStateMachine: Exit Disconnected: -1
11-23 17:19:20.023   930   930 D BluetoothHeadset: Proxy object disconnected
11-23 17:19:20.023   930   930 D BluetoothHeadset: Proxy object disconnected
11-23 17:19:20.024  5705  5716 D BluetoothHeadset: Proxy object disconnected
,11-23 17:19:20.025   930   930 D BluetoothA2dp: Proxy object disconnected
11-23 17:19:20.025  5705  5705 D BluetoothA2dp: Proxy object disconnected
,11-23 17:19:20.026  5705  5705 D HeadsetProfile: Bluetooth service disconnected
11-23 17:19:20.027  5819  5819 D HidService: Received stop request...Stopping profile...
11-23 17:19:20.027  5819  5819 D HidService: Stopping Bluetooth HidService
,11-23 17:19:20.029  5705  5705 D BluetoothInputDevice: Proxy object disconnected
11-23 17:19:20.029  5705  5705 D HidProfile: Bluetooth service disconnected
11-23 17:19:20.031  3616  3616 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 17:19:20.032  5819  5819 D HealthService: Received stop request...Stopping profile...
,11-23 17:19:20.033  5819  5819 V BluetoothAdapterState: isTurningOff()=true
11-23 17:19:20.033  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-23 17:19:20.034  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:20.034  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 17:19:20.034  5819  5819 D PanService: Received stop request...Stopping profile...
11-23 17:19:20.037  5705  5705 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 17:19:20.037  5705  5705 D PanProfile: Bluetooth service disconnected
,11-23 17:19:20.037  5819  5819 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 17:19:20.037  5819  5819 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 17:19:20.037  5819  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 17:19:20.037  5819  5842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 17:19:20.037  5819  5842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 17:19:20.037  5819  5842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 17:19:20.037  3163  3163 D HeadsetProfile: Bluetooth service disconnected
11-23 17:19:20.038  3163  3163 D BluetoothA2dp: Proxy object disconnected
11-23 17:19:20.038  3163  3163 D BluetoothInputDevice: Proxy object disconnected
11-23 17:19:20.038  5819  5819 D BluetoothMapService: Received stop request...Stopping profile...
11-23 17:19:20.038  3163  3163 D HidProfile: Bluetooth service disconnected
11-23 17:19:20.038  5819  5819 D BluetoothMapService: stop()
11-23 17:19:20.038  5819  5835 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 17:19:20.038  3163  3163 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 17:19:20.038  3163  3163 D PanProfile: Bluetooth service disconnected
11-23 17:19:20.039  5819  5819 D BluetoothMapAppObserver: deinitObservers()
11-23 17:19:20.039  5819  5819 D BluetoothMapAppObserver: removeReceiver()
11-23 17:19:20.040  3163  3163 D BluetoothMap: Proxy object disconnected
11-23 17:19:20.040  3163  3163 D MapProfile: Bluetooth service disconnected
11-23 17:19:20.040  5705  5705 D BluetoothMap: Proxy object disconnected
11-23 17:19:20.040  5819  5819 V BluetoothAdapterState: isTurningOff()=true
11-23 17:19:20.041  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-23 17:19:20.041  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:20.041  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:20.041  5705  5705 D MapProfile: Bluetooth service disconnected
11-23 17:19:20.043  5819  5842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 17:19:20.043  5819  5842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 17:19:20.043  5819  5819 D SapService: Received stop request...Stopping profile...
11-23 17:19:20.043  5819  5819 V SapService: stop()
11-23 17:19:20.046  5819  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 17:19:20.046  5819  5842 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 17:19:20.046  5819  5842 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 17:19:20.046  5819  5842 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 17:19:20.046  5819  5842 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 17:19:20.047  5819  5819 V BluetoothAdapterState: isTurningOff()=true
11-23 17:19:20.047  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-23 17:19:20.047  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:20.047  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:20.048  3163  3163 D BluetoothPbap: Proxy object disconnected
11-23 17:19:20.048  3163  3163 D PbapServerProfile: Bluetooth service disconnected
11-23 17:19:20.048  5819  5819 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 17:19:20.048  5819  5819 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 17:19:20.048  5819  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 17:19:20.048  5819  5819 V BluetoothAdapterState: isTurningOff()=true
11-23 17:19:20.048  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-23 17:19:20.048  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:20.048  5819  5819 V BluetoothAdapterState: is,BleTurningOff()=false
11-23 17:19:20.049  5819  5819 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 17:19:20.049  5819  5835 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 17:19:20.049  5819  5819 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 17:19:20.050  5819  5819 V BluetoothAdapterState: isTurningOff()=true
11-23 17:19:20.050  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-23 17:19:20.050  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:20.050  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:20.050  5819  5819 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 17:19:20.050  5819  5819 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 17:19:20.051  5819  5819 D BluetoothMapService: MAP Service closeService in
11-23 17:19:20.051  5819  5819 V BluetoothAdapterState: isTurningOff()=true
11-23 17:19:20.051  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-23 17:19:20.051  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:20.051  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:20.052  5819  5819 D BluetoothMapService: cleanup()
11-23 17:19:20.052  5819  5819 D BluetoothMapService: MAP Service closeService in
11-23 17:19:20.052  5819  5819 V BluetoothAdapterState: isTurningOff()=true
11-23 17:19:20.052  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-23 17:19:20.052  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:20.052  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:20.052  5819  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 17:19:20.052  5819  5831 D BluetoothAdapterProperties: Setting state to 15
11-23 17:19:20.052  5819  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 17:19:20.053  5819  5831 I BluetoothAdapterState: Entering BleOnState
11-23 17:19:20.053  3163  3186 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 17:19:20.054  5705  5705 D BluetoothPbap: Proxy object disconnected
11-23 17:19:20.054  5705  5705 D PbapServerProfile: Bluetooth service disconnected
11-23 17:19:20.055   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 17:19:20.055  3163  4015 D BluetoothMap: onBluetoothStateChange: up=false
11-23 17:19:20.056  3808  3835 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 17:19:20.057  5705  5716 D BluetoothMap: onBluetoothStateChange: up=false
11-23 17:19:20.058   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 17:19:20.059  5705  5717 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 17:19:20.059  5705  5871 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 17:19:20.060  3163  4015 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 17:19:20.060  5705  5716 D BluetoothPan: onBluetoothStateChange on: false
11-23 17:19:20.061   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 17:19:20.061  5705  5717 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 17:19:20.061  3163  3186 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 17:19:20.062  3163  3185 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 17:19:20.062  5705  5871 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 17:19:20.063   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 17:19:20.063  3163  4015 D BluetoothPan: onBluetoothStateChange on: false
11-23 17:19:20.064  5819  5831 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 17:19:20.064  5819  5831 D BluetoothAdapterProperties: Setting state to 16
11-23 17:19:20.064  5819  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 17:19:20.065  5819  5831 D BluetoothAdapterProperties: onBleDisable
11-23 17:19:20.065  5819  5831 I BluetoothAdapterState: Entering PendingCommandState
11-23 17:19:20.065  5,819  5832 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 17:19:20.067  5819  5835 D BluetoothAdapterProperties: Scan Mode:20
11-23 17:19:20.067  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:19:20.069  5819  5842 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 17:19:20.069  5819  5842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 17:19:20.069  5640  5640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 17:19:20.070  5705  5705 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 17:19:20.078  3616  3616 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 17:19:20.078  5705  5705 D DockEventReceiver: finishStartingService: stopping service
,11-23 17:19:20.280  5819  5835 I bt_hci  : shut_down
,11-23 17:19:20.290  5819  5839 D bt_hwcfg: hw_epilog_process
,11-23 17:19:20.290  5819  5839 I bt_vendor: low_power_mode_cb
,11-23 17:19:20.293  5819  5839 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 17:19:20.293  5819  5839 I bt_vendor: epilog_cb
11-23 17:19:20.293  5819  5839 I bt_hci  : epilog_finished_callback
,11-23 17:19:20.296  5819  5835 I bt_hci_h4: hal_close
,11-23 17:19:20.297  5819  5835 I bt_userial_vendor: device fd = 54 close
,11-23 17:19:20.410  5819  5832 D bt_stack_manager: event_shut_down_stack finished.
,11-23 17:19:20.411  5819  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 17:19:20.416  5819  5831 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-23 17:19:20.416  5819  5819 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 17:19:20.417  5819  5819 D BtGatt.GattService: Received stop request...Stopping profile...
,11-23 17:19:20.417  5819  5819 D BtGatt.GattService: stop()
11-23 17:19:20.417  5819  5819 D BtGatt.AdvertiseManager: advertise clients cleared
,11-23 17:19:20.422  5819  5819 V BluetoothAdapterState: isTurningOff()=false
,11-23 17:19:20.422  5819  5819 V BluetoothAdapterState: isTurningOn()=false
11-23 17:19:20.422  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:20.422  5819  5819 V BluetoothAdapterState: isBleTurningOff()=true
11-23 17:19:20.422  5819  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 17:19:20.423  5819  5831 D BluetoothAdapterProperties: Setting state to 10
11-23 17:19:20.423  5819  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-23 17:19:20.424  5819  5831 I BluetoothAdapterState: Entering OffState
,11-23 17:19:20.425   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 17:19:20.439  5819  5819 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 17:19:20.441  5819  5819 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 17:19:20.441  5819  5819 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 17:19:20.442  5819  5832 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 17:19:20.451  5819  5819 I art     : System.exit called, status: 0
11-23 17:19:20.451  5819  5819 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 17:19:20.479   930  3860 I ActivityManager: Process com.android.bluetooth (pid 5819) has died
,11-23 17:19:23.707   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:24.708   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:24.987  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 17:19:24.988  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 17:19:24.993  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 17:19:24.993  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c65e627 removed from the list
11-23 17:19:24.993  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:19:24.996  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:19:24.996  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11f8572 added. We now have 4 listener(s)
,11-23 17:19:24.996  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 17:19:24.998  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:24.998  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11f8572 removed from the list
11-23 17:19:24.998  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 17:19:25.000  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 17:19:25.001  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d40bdc3 added. We now have 4 listener(s)
11-23 17:19:25.001  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 17:19:25.709   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:26.710   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:27.711   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:28.712   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 17:19:30.011  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 17:19:30.043   930   947 I ActivityManager: Start proc 5876:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 17:19:30.125  5876  5876 D AdapterServiceConfig: Adding HeadsetService
11-23 17:19:30.126  5876  5876 D AdapterServiceConfig: Adding A2dpService
11-23 17:19:30.126  5876  5876 D AdapterServiceConfig: Adding HidService
11-23 17:19:30.126  5876  5876 D AdapterServiceConfig: Adding HealthService
11-23 17:19:30.126  5876  5876 D AdapterServiceConfig: Adding PanService
11-23 17:19:30.126  5876  5876 D AdapterServiceConfig: Adding GattService
11-23 17:19:30.127  5876  5876 D AdapterServiceConfig: Adding BluetoothMapService
11-23 17:19:30.127  5876  5876 D AdapterServiceConfig: Adding SapService
,11-23 17:19:30.137   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4de8723:true
,11-23 17:19:30.138  5876  5876 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 17:19:30.141  5876  5876 I bt_bluedroid: init
,11-23 17:19:30.142  5876  5888 I BluetoothAdapterState: Entering OffState
,11-23 17:19:30.144  5876  5889 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 17:19:30.144  5876  5889 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 17:19:30.144  5876  5889 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 17:19:30.145  5876  5889 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-23 17:19:30.145  5876  5876 I bt_bluedroid: get_profile_interface socket
,11-23 17:19:30.147  5876  5892 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-23 17:19:30.148  5876  5876 I bt_bluedroid: get_profile_interface sdp
11-23 17:19:30.149  5876  5892 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 17:19:30.152  5876  5887 I bt_bluedroid: config_hci_snoop_log
,11-23 17:19:30.153   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-23 17:19:30.157  5876  5888 D BluetoothAdapterState: Current state: OFF, message: 0
11-23 17:19:30.157  5876  5888 D BluetoothAdapterProperties: Setting state to 14
,11-23 17:19:30.157  5876  5888 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-23 17:19:30.159  5876  5888 D BluetoothBondStateMachine: make
,11-23 17:19:30.161  5876  5893 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 17:19:30.165  5876  5888 I BluetoothAdapterState: Entering PendingCommandState
,11-23 17:19:30.166  5876  5876 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 17:19:30.168  5876  5876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
,11-23 17:19:30.169  5876  5876 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 17:19:30.169  5876  5876 D BtGatt.GattService: Received start request. Starting profile...
11-23 17:19:30.170  5876  5876 D BtGatt.GattService: start()
11-23 17:19:30.170  5876  5876 I bt_bluedroid: get_profile_interface gatt
,11-23 17:19:30.171  5876  5876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
,11-23 17:19:30.171  5876  5876 D BtGatt.AdvertiseManager: advertise manager created
,11-23 17:19:30.176  5876  5876 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:30.176  5876  5876 V BluetoothAdapterState: isTurningOn()=false
11-23 17:19:30.176  5876  5876 V BluetoothAdapterState: isBleTurningOn()=true
11-23 17:19:30.176  5876  5876 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 17:19:30.177  5876  5888 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 17:19:30.178  5876  5888 I bt_bluedroid: bt_bluedroid
11-23 17:19:30.178  5876  5889 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-23 17:19:30.178  5876  5889 I bt_hci  : start_up
,11-23 17:19:30.184  5876  5889 I bt_vendor: alloc value 0xf4149871
11-23 17:19:30.184  5876  5889 I bt_vendor: init
11-23 17:19:30.184  5876  5889 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 17:19:30.184  5876  5889 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 17:19:30.297  5876  5889 D bt_hci  : start_up starting async portion
,11-23 17:19:30.297  5876  5896 I bt_hci  : event_finish_startup
,11-23 17:19:30.298  5876  5896 I bt_hci_h4: hal_open
11-23 17:19:30.298  5876  5896 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 17:19:30.301  5876  5896 I bt_userial_vendor: device fd = 54 open
,11-23 17:19:30.299  5897  5897 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 17:19:30.318  5876  5896 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 17:19:30.322  5876  5896 D bt_hwcfg: Chipset BCM4358A3
,11-23 17:19:30.351  5876  5896 D bt_hwcfg: Target name = [BCM4358A3]
11-23 17:19:30.352  5876  5896 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 17:19:30.757  5876  5896 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 17:19:30.758  5876  5896 D bt_hwcfg: Settlement delay -- 100 ms
11-23 17:19:30.758  5876  5896 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 17:19:30.891  5876  5896 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 17:19:30.892  5876  5896 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-23 17:19:30.893  5876  5896 I bt_hwcfg: vendor lib fwcfg completed
,11-23 17:19:30.893  5876  5896 I bt_vendor: firmware callback
11-23 17:19:30.893  5876  5896 I bt_hci  : firmware_config_callback
,11-23 17:19:30.902  5876  5899 I bt_btu  : btu_task pending for preload complete event
,11-23 17:19:30.903  5876  5899 I bt_btu_task: Bluetooth chip preload is complete
11-23 17:19:30.903  5876  5899 I bt_btu  : btu_task received preload complete event
,11-23 17:19:30.910  5876  5899 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 17:19:30.910  5876  5899 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 17:19:30.910  5876  5899 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 17:19:30.911  5876  5899 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 17:19:30.911  5876  5899 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-23 17:19:30.911  5876  5899 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 17:19:30.911  5876  5899 I         : BTE_InitTraceLevels -- TRC_BNEP
11-23 17:19:30.911  5876  5899 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 17:19:30.911  5876  5899 I         : BTE_InitTraceLevels -- TRC_GAP
,11-23 17:19:30.911  5876  5899 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 17:19:30.911  5876  5899 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 17:19:30.911  5876  5899 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 17:19:30.912  5876  5899 I         : BTE_InitTraceLevels -- TRC_SMP
,11-23 17:19:30.912  5876  5899 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 17:19:30.912  5876  5899 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 17:19:30.995  5876  5899 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40c7549
,11-23 17:19:30.995  5876  5899 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40c7549 
,11-23 17:19:31.016  5876  5892 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 17:19:31.017  5876  5892 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 17:19:31.018  5876  5892 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 17:19:31.022  5876  5892 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 17:19:31.024  5876  5892 D BluetoothAdapterProperties: Scan Mode:20
11-23 17:19:31.025  5876  5892 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-23 17:19:31.025  5876  5892 D bt_hci  : do_postload posting postload work item
11-23 17:19:31.025  5876  5896 I bt_hci  : event_postload
,11-23 17:19:31.026  5876  5896 I bt_vendor: sco_config_cb
11-23 17:19:31.026  5876  5896 I bt_hci  : sco_config_callback postload finished.
,11-23 17:19:31.029  5876  5892 D bt_bte_conf: Device ID record 1 : primary
,11-23 17:19:31.029  5876  5892 D bt_bte_conf:   vendorId            = 000f
11-23 17:19:31.030  5876  5892 D bt_bte_conf:   vendorIdSource      = 0001
11-23 17:19:31.030  5876  5892 D bt_bte_conf:   product             = 1200
11-23 17:19:31.030  5876  5892 D bt_bte_conf:   version             = 1436
11-23 17:19:31.030  5876  5892 D bt_bte_conf:   clientExecutableURL = 
11-23 17:19:31.030  5876  5892 D bt_bte_conf:   serviceDescription  = 
11-23 17:19:31.030  5876  5892 D bt_bte_conf:   documentationURL    = 
11-23 17:19:31.030  5876  5892 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 17:19:31.030  5876  5889 D bt_stack_manager: event_start_up_stack finished
11-23 17:19:31.031  5876  5888 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-23 17:19:31.032  5876  5888 D BluetoothAdapterProperties: Setting state to 15
11-23 17:19:31.032  5876  5888 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 17:19:31.034  5876  5888 I BluetoothAdapterState: Entering BleOnState
11-23 17:19:31.035  5876  5896 I bt_vendor: low_power_mode_cb
,11-23 17:19:31.039  5876  5888 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-23 17:19:31.040  5876  5888 D BluetoothAdapterProperties: Setting state to 11
11-23 17:19:31.040  5876  5888 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 17:19:31.044  5876  5876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
11-23 17:19:31.045  5876  5876 D HeadsetService: Received start request. Starting profile...
11-23 17:19:31.049  5876  5876 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 17:19:31.050  5876  5876 D HeadsetStateMachine: make
,11-23 17:19:31.061  5876  5888 I BluetoothAdapterState: Entering PendingCommandState
,11-23 17:19:31.062  5876  5876 D HeadsetStateMachine: max_hf_connections = 1
,11-23 17:19:31.062  5876  5876 I bt_bluedroid: get_profile_interface handsfree
11-23 17:19:31.062  5876  5892 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 17:19:31.062  5876  5892 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
11-23 17:19:31.065  5876  5876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
11-23 17:19:31.066  5876  5876 D A2dpService: Received start request. Starting profile...
11-23 17:19:31.067  5876  5876 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 17:19:31.067  5876  5876 I bt_bluedroid: get_profile_interface avrcp
,11-23 17:19:31.077  5876  5876 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 17:19:31.077  5876  5876 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 17:19:31.077  5876  5876 D A2dpStateMachine: make
11-23 17:19:31.078  5876  5876 I bt_bluedroid: get_profile_interface a2dp
11-23 17:19:31.079  5876  5892 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-23 17:19:31.080  5876  5906 D A2dpStateMachine: Enter Disconnected: -2
,11-23 17:19:31.080  5876  5876 I BluetoothHidServiceJni: classInitNative: succeeds
11-23 17:19:31.081  5876  5876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
11-23 17:19:31.082  5876  5876 D HidService: Received start request. Starting profile...
,11-23 17:19:31.082  5876  5876 I bt_bluedroid: get_profile_interface hidhost
11-23 17:19:31.082  5876  5892 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40a856d
11-23 17:19:31.082  5876  5876 D HidService: setHidService(): set to: null
11-23 17:19:31.082  5876  5892 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 17:19:31.083  5876  5876 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 17:19:31.083  5876  5876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
11-23 17:19:31.084  5876  5876 D HealthService: Received start request. Starting profile...
,11-23 17:19:31.085  5876  5876 I bt_bluedroid: get_profile_interface health
11-23 17:19:31.087  5876  5876 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-23 17:19:31.088  5876  5876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
11-23 17:19:31.089  5876  5876 D PanService: Received start request. Starting profile...
11-23 17:19:31.089  5876  5876 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 17:19:31.089  5876  5876 I bt_bluedroid: get_profile_interface pan
,11-23 17:19:31.089  3616  3616 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 17:19:31.089  5876  5892 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 17:19:31.092  5876  5876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
11-23 17:19:31.093  5876  5876 D BluetoothMapService: Received start request. Starting profile...
11-23 17:19:31.093  5876  5876 D BluetoothMapService: start()
11-23 17:19:31.096  5876  5876 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-23 17:19:31.097  5876  5876 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-23 17:19:31.097  5876  5876 D BluetoothMapAppObserver: createReceiver()
11-23 17:19:31.099  5876  5876 D BluetoothMapAppObserver: initObservers()
11-23 17:19:31.099  5876  5876 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 17:19:31.105  5876  5876 V SapService: SapBinder()
,11-23 17:19:31.105  5876  5876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
11-23 17:19:31.106  5876  5876 D SapService: Received start request. Starting profile...
11-23 17:19:31.106  5876  5876 V SapService: start()
,11-23 17:19:31.107  5876  5876 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:31.107  5876  5876 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:31.108  5876  5904 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isTurningOff()=false
,11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:31.108  5876  5876 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:31.109  5876  5876 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:31.109  5876  5876 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:31.109  5876  5876 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:31.109  5876  5876 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 17:19:31.109  5876  5876 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:31.110  5876  5876 V BluetoothAdapterState: isTurningOff()=false
11-23 17:19:31.110  5876  5876 V BluetoothAdapterState: isTurningOn()=true
11-23 17:19:31.110  5876  5876 V BluetoothAdapterState: isBleTurningOn()=false
11-23 17:19:31.110  5876  5876 V BluetoothAdapterState: isBleTurningOff()=false
11-23 17:19:31.110  5876  5888 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 17:19:31.110  5876  5888 D BluetoothAdapterProperties: ScanMode =  20
11-23 17:19:31.110  5876  5888 D BluetoothAdapterProperties: State =  11
,11-23 17:19:31.111  5876  5892 D BluetoothAdapterProperties: Scan Mode:21
,11-23 17:19:31.111  5876  5888 D BluetoothAdapterProperties: Setting state to 12
11-23 17:19:31.111  5876  5888 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 17:19:31.111  5876  5892 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 17:19:31.112  5876  5888 I BluetoothAdapterState: Entering OnState
11-23 17:19:31.113  3163  4015 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-23 17:19:31.115   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 17:19:31.116  3163  3186 D BluetoothMap: onBluetoothStateChange: up=true
11-23 17:19:31.116  3163  3163 D BluetoothInputDevice: Proxy object connected
,11-23 17:19:31.116  3163  3163 D HidProfile: Bluetooth service connected
11-23 17:19:31.118  3808  3835 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 17:19:31.118   930   930 D BluetoothA2dp: Proxy object connected
,11-23 17:19:31.118  5705  5871 D BluetoothMap: onBluetoothStateChange: up=true
,11-23 17:19:31.120  3163  3163 D BluetoothMap: Proxy object connected
11-23 17:19:31.120  3163  3163 D MapProfile: Bluetooth service connected
11-23 17:19:31.121  3163  3163 D BluetoothMap: getConnectedDevices()
11-23 17:19:31.122   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 17:19:31.122  5705  5717 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 17:19:31.122  5705  5716 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 17:19:31.124  3163  3185 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 17:19:31.124  5876  5876 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 17:19:31.124  5705  5705 D BluetoothMap: Proxy object connected
11-23 17:19:31.124  5705  5705 D MapProfile: Bluetooth service connected
11-23 17:19:31.124  5705  5705 D BluetoothMap: getConnectedDevices()
11-23 17:19:31.125  5876  5876 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 17:19:31.126  5705  5705 D BluetoothA2dp: Proxy object connected
11-23 17:19:31.126  5876  5876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 17:19:31.127  5705  5716 D BluetoothPan: onBluetoothStateChange on: true
,11-23 17:19:31.129  5876  5876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 17:19:31.129   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 17:19:31.130  5705  5717 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 17:19:31.130  5876  5876 D ObexServerSockets: Succeed to create listening sockets 
11-23 17:19:31.130  5876  5876 D ObexServerSockets0: startAccept()
,11-23 17:19:31.130  5876  5876 D ObexServerSockets0: prepareForNewConnect()
,11-23 17:19:31.132  5876  5876 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 17:19:31.132  5876  5876 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-23 17:19:31.133  5876  5913 D ObexServerSockets0: Accepting socket connection...
,11-23 17:19:31.134  3163  3186 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 17:19:31.134  5876  5914 D ObexServerSockets0: Accepting socket connection...
,11-23 17:19:31.135  3163  4015 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 17:19:31.136  3163  3163 D BluetoothA2dp: Proxy object connected
11-23 17:19:31.137  5705  5716 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 17:19:31.139   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 17:19:31.139  3163  3186 D BluetoothPan: onBluetoothStateChange on: true
11-23 17:19:31.140  5705  5705 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 17:19:31.140  5705  5705 D PanProfile: Bluetooth service connected
,11-23 17:19:31.140  5705  5705 D BluetoothInputDevice: Proxy object connected
11-23 17:19:31.140  5705  5705 D HidProfile: Bluetooth service connected
11-23 17:19:31.141  3163  3163 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 17:19:31.141  3163  3163 D PanProfile: Bluetooth service connected
11-23 17:19:31.142   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,11-23 17:19:31.143  5876  5876 D BluetoothMapService: onReceive
11-23 17:19:31.143  5876  5876 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 17:19:31.143  5876  5876 D BluetoothMapService: STATE_ON
,11-23 17:19:31.145  5876  5915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 17:19:31.149  5876  5915 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 17:19:31.149  5876  5915 D BluetoothSdpJni: SDP Create record success - handle: 1
11-23 17:19:31.150  5705  5705 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 17:19:31.154  5705  5705 D DockEventReceiver: finishStartingService: stopping service
,11-23 17:19:31.156  3616  3616 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 17:19:31.162  5705  5705 D BluetoothPbap: Proxy object connected
,11-23 17:19:31.162  5705  5705 D PbapServerProfile: Bluetooth service connected
,11-23 17:19:31.169  5876  5920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 17:19:31.176  5876  5876 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 17:19:31.176  5876  5876 D ObexServerSockets0: prepareForNewConnect()
11-23 17:19:31.176  3163  3163 D BluetoothPbap: Proxy object connected
11-23 17:19:31.176  3163  3163 D PbapServerProfile: Bluetooth service connected
,11-23 17:19:31.182  5876  5924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 17:19:31.183  5876  5924 I BtOppRfcommListener: Accept thread started.
,11-23 17:19:31.219  3808  4026 D BluetoothHeadset: Proxy object connected
11-23 17:19:31.220  3163  4015 D BluetoothHeadset: Proxy object connected
,11-23 17:19:31.220  3163  3163 D HeadsetProfile: Bluetooth service connected
11-23 17:19:31.220   930   930 D BluetoothHeadset: Proxy object connected
11-23 17:19:31.220   930   930 D BluetoothHeadset: Proxy object connected
11-23 17:19:31.220   930   930 D BluetoothHeadset: Proxy object connected
,11-23 17:19:31.220  5705  5717 D BluetoothHeadset: Proxy object connected
11-23 17:19:31.221   930   947 D BluetoothHeadset: Proxy object connected
11-23 17:19:31.222  5705  5705 D HeadsetProfile: Bluetooth service connected
,11-23 17:19:31.223  5705  5716 D BluetoothHeadset: Proxy object connected
,11-23 17:19:31.223  5705  5705 D HeadsetProfile: Bluetooth service connected
,11-23 17:19:31.229   930   947 D BluetoothHeadset: Proxy object connected
,11-23 17:19:31.234  3163  3186 D BluetoothHeadset: Proxy object connected
,11-23 17:19:31.234  3163  3163 D HeadsetProfile: Bluetooth service connected
,11-23 17:19:31.239   930   947 D BluetoothHeadset: Proxy object connected
,11-23 17:19:33.713   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:34.714   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:35.026  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 17:19:35.026  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:19:35.026  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:19:35.026  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 17:19:35.026  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 17:19:35.026  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 17:19:35.026  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 17:19:35.026  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 17:19:35.026  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 17:19:35.032  5640  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 17:19:35.033  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:35.034  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d40bdc3 removed from the list
11-23 17:19:35.034  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:19:35.036  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:19:35.036  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6346640 added. We now have 4 listener(s)
11-23 17:19:35.036  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 17:19:35.041   930  3860 D WifiService: setWifiEnabled: false pid=5640, uid=10077
11-23 17:19:35.041   930  3860 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 17:19:35.715   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:36.716   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:37.717   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:38.718   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 17:19:40.052  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 17:19:40.053   930  3450 D WifiService: setWifiEnabled: true pid=5640, uid=10077
11-23 17:19:40.054   930  3450 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 17:19:40.062   508   912 D SoftapController: Softap fwReload - Ok
,11-23 17:19:40.067   508   912 D CommandListener: Setting iface cfg
,11-23 17:19:40.068   508   912 D CommandListener: Trying to bring down wlan0
11-23 17:19:40.069   508   912 D CommandListener: Clearing all IP addresses on wlan0
11-23 17:19:40.073   930  3009 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 17:19:40.735   930  3009 D wifi    : set interface wlan0 flags (UP)
,11-23 17:19:40.736   930  3009 I WifiHAL : Initializing wifi
,11-23 17:19:40.736   930  3009 I WifiHAL : Creating socket
11-23 17:19:40.742   930  3009 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-23 17:19:40.742   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-23 17:19:40.742   930  3009 D wifi    : Did set static halHandle = 0x7f5e912900
11-23 17:19:40.742   930  3009 D wifi    : halHandle = 0x7f5e912900, mVM = 0x7f7af4d140, mCls = 0x20189e
,11-23 17:19:40.742   930  3009 D wifi    : array field set
11-23 17:19:40.744   930  3009 I WifiNative-HAL: interface[0] = wlan0
,11-23 17:19:40.746   930  5930 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547047418112
11-23 17:19:40.746   930  5930 D wifi    : waitForHalEvents called, vm = 0x7f7af4d140, obj = 0x20189e, env = 0x7f638f7b40
,11-23 17:19:40.804  5931  5931 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 17:19:40.848   930  3009 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 17:19:40.875  5931  5931 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 17:19:40.930  5931  5931 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 17:19:40.930  5931  5931 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 17:19:40.955   930  3009 D WifiConfigStore: Loading config and enabling all networks 
,11-23 17:19:40.978   930  3009 D WifiConfigStore: loaded 0 passpoint configs
,11-23 17:19:40.980   930  3009 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-23 17:19:40.980   930  3009 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-23 17:19:40.981   930  3009 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-23 17:19:40.981   930  3009 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-23 17:19:40.982   930  3009 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-23 17:19:40.983   930  3009 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-23 17:19:40.983   930  3009 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-23 17:19:40.983   930  3009 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-23 17:19:40.983   930  3009 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-23 17:19:40.983   930  3009 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-23 17:19:40.983   930  3009 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-23 17:19:40.983   930  3009 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-23 17:19:40.988   930  3009 D WifiNative-HAL: Setting external_sim to 1
,11-23 17:19:40.988  4478  4478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 17:19:40.988   930  3009 D wifi    : setting dfs flag to true, 0x7f5dfe6ec0
11-23 17:19:40.989   930  3009 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 17:19:40.990   930  3009 D wifi    : setting scan oui 0x7f5dfe6ec0
11-23 17:19:40.990   930  3009 D WifiHAL : Sending mac address OUI
,11-23 17:19:40.994   930  3009 E native  : do suspend false
,11-23 17:19:41.006   930  3009 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 17:19:41.006   508   912 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-23 17:19:41.007   930   930 D RttService: SCAN_AVAILABLE : 3
11-23 17:19:41.007   930  3116 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-23 17:19:41.008   508   912 D CommandListener: Setting iface cfg
,11-23 17:19:41.009   930  3008 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
11-23 17:19:41.009   930  3008 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 17:19:41.025   930  3008 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 17:19:41.031   930  3008 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
11-23 17:19:41.031   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=246194 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-23 17:19:44.075  5931  5931 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 17:19:44.085  5931  5931 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 17:19:44.115   930  3009 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 17:19:44.116   930  3009 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 17:19:44.116   930  3009 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 17:19:44.132   930  3009 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 17:19:44.172   930  3009 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 17:19:44.179  5931  5931 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 17:19:44.618  5931  5931 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 17:19:44.657  5931  5931 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 17:19:44.658  5931  5931 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 17:19:44.668   930  3009 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 17:19:44.668   930  3009 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 17:19:44.669   930  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 17:19:44.688   930  3009 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 17:19:44.703   508   912 D CommandListener: Setting iface cfg
,11-23 17:19:44.710   930  3009 D WifiStateMachine: Start Dhcp Watchdog 3
,11-23 17:19:44.719   930  5936 D DhcpClient: Receive thread started
,11-23 17:19:44.724   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 17:19:44.724   930  3009 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-23 17:19:44.724   930  3011 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-23 17:19:44.815   930  3009 E native  : do suspend false
,11-23 17:19:44.837   930  5935 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 17:19:44.857   930  5936 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-23 17:19:44.858   930  5935 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-23 17:19:44.861   930  5935 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-23 17:19:44.885   930  5936 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 17:19:44.886   930  5935 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 17:19:44.890   508   912 D CommandListener: Setting iface cfg
11-23 17:19:44.894   930  3009 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 17:19:44.899   930  5935 D DhcpClient: Scheduling renewal in 86399s
,11-23 17:19:44.915   930  3009 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 17:19:44.917   930  3009 D WifiConfigStore: No blacklist allowed without epno enabled
,11-23 17:19:44.918   930  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-23 17:19:44.920   930  3011 D ConnectivityService: Adding iface wlan0 to network 102
,11-23 17:19:44.928   930  3009 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 17:19:44.967   930  3011 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-23 17:19:44.967   930  3011 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-23 17:19:44.969   930  3011 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
11-23 17:19:44.971   930  3011 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-23 17:19:44.972   930  3011 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-23 17:19:44.979   930  3011 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 17:19:44.983   930  3011 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-23 17:19:44.983   930  3011 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-23 17:19:44.984   930  3011 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-23 17:19:44.984   930  3011 D ConnectivityService:    accepting network in place of null
11-23 17:19:44.984   930  3009 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 17:19:44.984   930  3009 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 17:19:44.984   930  3011 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 17:19:45.007   508   912 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 17:19:45.018   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=250181, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 17:19:45.027   508   912 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 17:19:45.031   930  3011 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-23 17:19:45.031   930  3011 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 17:19:45.031  3778  3903 W QCNEJ   : |CORE| network available: 102
,11-23 17:19:45.032   930  3011 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-23 17:19:45.032   930   947 D Tethering: MasterInitialState.processMessage what=3
11-23 17:19:45.033  3778  3903 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 17:19:45.034  3778  3903 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 17:19:45.034  3778  3903 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 17:19:45.042  5063  5088 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 17:19:45.042  5063  5088 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 17:19:45.042  5063  5088 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 17:19:45.042  5063  5088 E SarControlService: no key has been found,reset the power
11-23 17:19:45.043  5063  5111 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 17:19:45.043  5063  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 17:19:45.043  5063  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 17:19:45.043  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 17:19:45.043  5101  5101 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-23 17:19:45.047  5063  5111 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-23 17:19:45.047  5063  5111 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 17:19:45.048  5063  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 17:19:45.048  4089  4089 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 17:19:45.050  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 17:19:45.050  5101  5101 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 17:19:45.053  5101  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6e330c2 HexData = [00000000f003000000000000ffffffff]
11-23 17:19:45.053  5101  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 17:19:45.053  5101  5116 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-23 17:19:45.053  5101  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6e330c2 HexData = [00000000f103000000000000ffffffff]
11-23 17:19:45.053  5101  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 17:19:45.053  5101  5116 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-23 17:19:45.054  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-23 17:19:45.054  5063  5073 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 17:19:45.054  5101  5101 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 17:19:45.054  5063  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 17:19:45.055  4089  4089 D SystemUpdateService: onCreate
11-23 17:19:45.048  3998  3998 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-23 17:19:45.060  4089  4089 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 17:19:45.068  5640  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 17:19:45.068  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 17:19:45.068  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 17:19:45.068  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 17:19:45.068  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 17:19:45.068  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 17:19:45.068  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 17:19:45.068  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 17:19:45.068  5640  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 17:19:45.070  5640  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 17:19:45.070  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.070  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6346640 removed from the list
,11-23 17:19:45.070  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 17:19:45.073  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-23 17:19:45.074  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-23 17:19:45.075  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@89971d4 Bundle[{}]
11-23 17:19:45.076  5640  5687 I io.jxcore.node.LifeCycleMonitor: start: OK
11-23 17:19:45.076  5640  5687 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-23 17:19:45.076  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-23 17:19:45.076  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-23 17:19:45.077  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-23 17:19:45.077  5640  5687 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-23 17:19:45.082  5640  5687 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
11-23 17:19:45.082  5640  5687 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-23 17:19:45.083  5640  5687 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
,11-23 17:19:45.084  4089  4089 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 17:19:45.084   930  5933 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:802::200e
11-23 17:19:45.086  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 17:19:45.086  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f73979 added. We now have 3 listener(s)
11-23 17:19:45.088  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 17:19:45.088  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 17:19:45.088  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 17:19:45.089  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:19:45.089  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95c86be added. We now have 4 listener(s)
11-23 17:19:45.089  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 17:19:45.089  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 17:19:45.091  4089  5428 I iu.UploadsManager: num queued entries: 0
,11-23 17:19:45.092  4089  5428 I iu.UploadsManager: num updated entries: 0
11-23 17:19:45.092  4089  5428 I iu.SyncManager: NEXT; no task
,11-23 17:19:45.093  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 17:19:45.093  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@419a66c added. We now have 4 listener(s)
,11-23 17:19:45.094  4089  5946 I SystemUpdateService: active receiver: enabled
11-23 17:19:45.094  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 17:19:45.095  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 17:19:45.095  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 17:19:45.095  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 17:19:45.095  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@328f435 added. We now have 5 listener(s)
11-23 17:19:45.095  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 17:19:45.095  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:19:45.095  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:19:45.095  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:19:45.095  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:19:45.096  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:19:45.096  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 17:19:45.096  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f73979 removed from the list
11-23 17:19:45.096  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.096  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95c86be removed from the list
,11-23 17:19:45.096  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:19:45.096  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.096  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.098  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.098  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.098  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.098  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:19:45.098  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 17:19:45.098  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.098  4089  4089 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-23 17:19:45.098  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95c86be not in the list
11-23 17:19:45.098  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.098  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.100  4089  4089 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-23 17:19:45.100  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.100  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.100  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.100  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:19:45.100  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:19:45.100  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.100  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@328f435 removed from the list
11-23 17:19:45.100  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:19:45.101  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:19:45.101  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-23 17:19:45.101  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@419a66c removed from the list
11-23 17:19:45.101  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 17:19:45.101  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d650ca added. We now have 3 listener(s)
,11-23 17:19:45.102  5743  5743 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-23 17:19:45.103  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 17:19:45.103  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 17:19:45.103  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 17:19:45.103  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:19:45.103  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61a223b added. We now have 4 listener(s)
11-23 17:19:45.104  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 17:19:45.104  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 17:19:45.105  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 17:19:45.105  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@430bd58 added. We now have 4 listener(s)
,11-23 17:19:45.106  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 17:19:45.106  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 17:19:45.106  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 17:19:45.106  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:19:45.106  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c819eb1 added. We now have 5 listener(s)
11-23 17:19:45.106  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 17:19:45.106  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 17:19:45.107  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 17:19:45.107  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 17:19:45.107  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 17:19:45.107  5743  5743 D SprintDMHelper: simOperator: 
11-23 17:19:45.107  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 17:19:45.107  5743  5743 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 17:19:45.112  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 17:19:45.116  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 17:19:45.116  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 17:19:45.116  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 17:19:45.119  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.119  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 17:19:45.120  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 17:19:45.120  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 17:19:45.120  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 17:19:45.120  4089  5946 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-23 17:19:45.123  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.123  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 17:19:45.123  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 17:19:45.123  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-23 17:19:45.123  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-23 17:19:45.123  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.124  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:19:45.126  5876  5912 D BtGatt.GattService: registerClient() - UUID=fb7d1c91-08e8-45e6-8ea1-2ca5366d0a32
11-23 17:19:45.127  5876  5892 D BtGatt.GattService: onClientRegistered() - UUID=fb7d1c91-08e8-45e6-8ea1-2ca5366d0a32, clientIf=5
11-23 17:19:45.128  5640  5650 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 17:19:45.128  5876  5911 D BtGatt.GattService: start scan with filters
,11-23 17:19:45.133  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 17:19:45.133  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.133  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 17:19:45.133  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.133  5876  5895 D BtGatt.ScanManager: handling starting scan
11-23 17:19:45.133  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 17:19:45.133  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 17:19:45.133  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-23 17:19:45.133  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 17:19:45.133  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 17:19:45.134  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.134  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.134  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.134  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.134  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 17:19:45.134  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.135  5876  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8ecb28
,11-23 17:19:45.137  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.137  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 17:19:45.137  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.137  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.137  5640  5687 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 17:19:45.137  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.137  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 17:19:45.137  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 17:19:45.137  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 17:19:45.137  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 17:19:45.137  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:19:45.137  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 17:19:45.139  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.139  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.139  4089  5946 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-23 17:19:45.139  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.139  4089  5946 I SystemUpdateService: now status is 0 (complete)
11-23 17:19:45.139  4089  5946 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-23 17:19:45.139  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 17:19:45.139  4089  5946 I SystemUpdateService: file has been verified
11-23 17:19:45.140  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 17:19:45.140  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.140  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 17:19:45.140  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 17:19:45.140  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.140  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.140  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.140  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-23 17:19:45.140  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.141  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:19:45.141  5876  5912 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 17:19:45.141  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-23 17:19:45.142  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:19:45.142  5876  5892 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 17:19:45.142  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.142  5876  5895 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 17:19:45.143  5876  5886 D BtGatt.GattService: stopScan() - queue size =1
11-23 17:19:45.143  4089  5946 I SystemUpdateService: OTA package size = 21989297
11-23 17:19:45.143  5876  5887 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 17:19:45.144  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 17:19:45.144  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.144  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 17:19:45.144  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.144  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.144  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.144  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.144  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 17:19:45.144  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.144  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.144  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.145  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 17:19:45.145  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 17:19:45.145  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 17:19:45.147  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.147  5876  5892 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 17:19:45.148  4089  5946 I SystemUpdateService: showing system update notification
11-23 17:19:45.148  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.148  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.148  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:19:45.148  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.148  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.148  5876  5895 D BtGatt.ScanManager: Starting BLE batch scan
11-23 17:19:45.148  5876  5895 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 17:19:45.148  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:19:45.149  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:19:45.149  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 17:19:45.149  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.149  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 17:19:45.149  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 17:19:45.149  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.149  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.149  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.149  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:19:45.149  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-23 17:19:45.150  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.150  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:19:45.150  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:19:45.150  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:19:45.150  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:19:45.150  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.150  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:19:45.150  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.151  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 17:19:45.151  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.151  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d650ca removed from the list
11-23 17:19:45.151  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.151  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61a223b removed from the list
,11-23 17:19:45.151  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:19:45.151  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.151  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.152  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.152  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.152  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.152  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:19:45.152  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:19:45.152  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 17:19:45.152  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61a223b not in the list
11-23 17:19:45.152  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.152  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.156   930  5933 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 16:19:45 GMT], X-Android-Received-Millis=[1479917985156], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479917985108]}
11-23 17:19:45.157   930  3011 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-23 17:19:45.157   930  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-23 17:19:45.157   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 17:19:45.158   930  3011 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-23 17:19:45.158  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.158  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.158  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.158  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:19:45.159  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:19:45.159  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.159  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c819eb1 removed from the list
11-23 17:19:45.159  5876  5892 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 17:19:45.159  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:19:45.159  4089  4089 D SystemUpdateService: onDestroy
11-23 17:19:45.159  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.159  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:19:45.159  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 17:19:45.159  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@430bd58 removed from the list
11-23 17:19:45.159   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 17:19:45.160  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 17:19:45.160  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5802f22 added. We now have 3 listener(s)
11-23 17:19:45.161  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 17:19:45.161  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-23 17:19:45.161  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 17:19:45.161  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:19:45.161  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3c9db3 added. We now have 4 listener(s)
11-23 17:19:45.161  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 17:19:45.162  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 17:19:45.163  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 17:19:45.164  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94ddf70 added. We now have 4 listener(s)
11-23 17:19:45.164  5876  5892 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 17:19:45.164  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.165  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 17:19:45.165  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 17:19:45.165  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 17:19:45.165  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:19:45.165  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc72e9 added. We now have 5 listener(s)
11-23 17:19:45.165  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 17:19:45.165  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 17:19:45.166  5876  5895 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 17:19:45.166  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 17:19:45.166  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 17:19:45.166  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 17:19:45.166  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 17:19:45.166  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 17:19:45.167  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 17:19:45.170  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 17:19:45.170  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 17:19:45.170  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 17:19:45.172  5876  5892 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 17:19:45.172  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.173  5876  5892 E BtGatt.ContextMap: Context not found for ID 5
,11-23 17:19:45.175  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.175  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 17:19:45.176  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 17:19:45.176  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 17:19:45.176  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 17:19:45.179  5876  5892 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 17:19:45.179  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.180  5876  5895 D BtGatt.ScanManager: stopping BLe Batch
,11-23 17:19:45.183  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.183  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 17:19:45.183  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 17:19:45.183  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 17:19:45.183  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 17:19:45.183  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.184  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:19:45.185  5876  5892 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 17:19:45.185  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:19:45.185  5876  5895 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 17:19:45.187  5876  5886 D BtGatt.GattService: registerClient() - UUID=0446b9d5-eea9-4dcf-b8af-32ed4f783ef7
,11-23 17:19:45.187  5876  5892 D BtGatt.GattService: onClientRegistered() - UUID=0446b9d5-eea9-4dcf-b8af-32ed4f783ef7, clientIf=5
11-23 17:19:45.188  5640  5651 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 17:19:45.188  5876  5887 D BtGatt.GattService: start scan with filters
,11-23 17:19:45.190  5876  5892 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 17:19:45.190  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:19:45.192  5876  5895 D BtGatt.ScanManager: handling starting scan
,11-23 17:19:45.192  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 17:19:45.192  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.192  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 17:19:45.192  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.192  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 17:19:45.193  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 17:19:45.193  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.193  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 17:19:45.193  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 17:19:45.193  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.193  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.193  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.193  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.193  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 17:19:45.193  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.196  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.196  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 17:19:45.196  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.196  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.197  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.197  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 17:19:45.197  5640  5687 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-23 17:19:45.197  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:19:45.197  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:19:45.197  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:19:45.197  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 17:19:45.197  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 17:19:45.197  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 17:19:45.197  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:19:45.197  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 17:19:45.197  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5802f22 removed from the list
11-23 17:19:45.197  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.197  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3c9db3 removed from the list
11-23 17:19:45.197  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 17:19:45.197  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 17:19:45.197  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 17:19:45.197  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.198  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 17:19:45.198  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 17:19:45.198  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 17:19:45.198  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 17:19:45.198  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.199  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.199  5876  5892 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 17:19:45.199  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.199  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.199  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.199  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 17:19:45.199  5876  5895 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 17:19:45.200  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.200  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.200  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.200  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:19:45.200  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:19:45.200  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.200  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3c9db3 not in the list
11-23 17:19:45.200  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 17:19:45.200  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.200  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 17:19:45.200  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 17:19:45.200  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.200  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.200  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.200  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 17:19:45.201  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.202  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:19:45.202  5876  5887 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 17:19:45.202  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 17:19:45.205  5876  5892 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 17:19:45.205  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:19:45.205  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.205  5876  5895 D BtGatt.ScanManager: Starting BLE batch scan
11-23 17:19:45.205  5876  5895 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 17:19:45.206  5876  5911 D BtGatt.GattService: stopScan() - queue size =1
11-23 17:19:45.206  5876  5886 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-23 17:19:45.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 17:19:45.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 17:19:45.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 17:19:45.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.207  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 17:19:45.207  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 17:19:45.208  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 17:19:45.208  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.209  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.209  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:19:45.209  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.209  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.209  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:19:45.209  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:19:45.209  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.210  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc72e9 removed from the list
11-23 17:19:45.209  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:19:45.210  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:19:45.210  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:19:45.210  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 17:19:45.210  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 17:19:45.210  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 17:19:45.210  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.210  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 17:19:45.210  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94ddf70 removed from the list
11-23 17:19:45.210  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 17:19:45.210  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.210  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.210  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.210  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:19:45.210  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.210  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 17:19:45.210  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 17:19:45.210  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0c807a added. We now have 3 listener(s)
11-23 17:19:45.211  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 17:19:45.211  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 17:19:45.212  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 17:19:45.212  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:19:45.212  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed4102b added. We now have 4 listener(s)
11-23 17:19:45.212  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 17:19:45.212  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 17:19:45.212  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-23 17:19:45.212  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.212  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.213  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 17:19:45.213  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97a2c88 added. We now have 4 listener(s)
11-23 17:19:45.214  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 17:19:45.214  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 17:19:45.214  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 17:19:45.214  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:19:45.214  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc69621 added. We now have 5 listener(s)
11-23 17:19:45.214  5876  5892 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 17:19:45.214  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 17:19:45.214  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.214  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 17:19:45.214  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 17:19:45.214  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-23 17:19:45.215  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 17:19:45.215  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 17:19:45.216  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 17:19:45.220  5876  5892 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 17:19:45.220  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:19:45.221  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 17:19:45.221  5640  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-23 17:19:45.221  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 17:19:45.222  5876  5895 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 17:19:45.226  5876  5892 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 17:19:45.226  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.226  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.226  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 17:19:45.226  5876  5892 E BtGatt.ContextMap: Context not found for ID 5
,11-23 17:19:45.227  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 17:19:45.227  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 17:19:45.227  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 17:19:45.232  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.232  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 17:19:45.232  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 17:19:45.232  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 17:19:45.232  5876  5892 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 17:19:45.232  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 17:19:45.232  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.232  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.232  5876  5895 D BtGatt.ScanManager: stopping BLe Batch
,11-23 17:19:45.233  5640  5687 D BluetoothAdapter: STATE_ON
,11-23 17:19:45.236  5876  5912 D BtGatt.GattService: registerClient() - UUID=54d9199a-5ec6-4d24-a677-d796085733b1
11-23 17:19:45.236  5876  5892 D BtGatt.GattService: onClientRegistered() - UUID=54d9199a-5ec6-4d24-a677-d796085733b1, clientIf=5
11-23 17:19:45.236  5640  5685 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 17:19:45.237  5876  5892 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 17:19:45.237  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.237  5876  5895 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 17:19:45.237  5876  5911 D BtGatt.GattService: start scan with filters
,11-23 17:19:45.242  5876  5892 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 17:19:45.242  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:19:45.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 17:19:45.243  5876  5895 D BtGatt.ScanManager: handling starting scan
11-23 17:19:45.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 17:19:45.243  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.244  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-23 17:19:45.244  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-23 17:19:45.244  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.244  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 17:19:45.244  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 17:19:45.244  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.244  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.244  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.245  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-23 17:19:45.246  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-23 17:19:45.246  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.248  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.248  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 17:19:45.248  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.248  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.249  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.249  5876  5892 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 17:19:45.249  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.250  5876  5895 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 17:19:45.251  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.251  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.251  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.251  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 17:19:45.251  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:19:45.252  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:19:45.252  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 17:19:45.252  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:19:45.252  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 17:19:45.252  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 17:19:45.252  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:19:45.252  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 17:19:45.252  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0c807a removed from the list
11-23 17:19:45.252  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.252  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed4102b removed from the list
11-23 17:19:45.252  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:19:45.252  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 17:19:45.252  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 17:19:45.252  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.252  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 17:19:45.252  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 17:19:45.252  5640  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 17:19:45.252  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 17:19:45.252  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.253  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.253  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.253  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.253  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:19:45.253  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:19:45.253  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.254  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed4102b not in the list
11-23 17:19:45.254  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 17:19:45.254  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.254  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 17:19:45.254  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 17:19:45.254  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.254  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.254  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.254  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 17:19:45.254  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.254  5876  5892 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 17:19:45.254  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.254  5876  5895 D BtGatt.ScanManager: Starting BLE batch scan
11-23 17:19:45.254  5876  5895 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 17:19:45.255  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:19:45.255  5876  5886 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 17:19:45.255  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 17:19:45.255  5640  5687 D BluetoothAdapter: STATE_ON
11-23 17:19:45.256  5876  5911 D BtGatt.GattService: stopScan() - queue size =1
,11-23 17:19:45.257  5876  5916 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 17:19:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 17:19:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 17:19:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 17:19:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.257  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 17:19:45.258  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 17:19:45.258  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 17:19:45.258  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.259  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.259  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:19:45.260  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.260  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.260  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:19:45.260  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:19:45.260  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 17:19:45.260  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:19:45.260  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc69621 removed from the list
11-23 17:19:45.261  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 17:19:45.261  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:19:45.261  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 17:19:45.261  5640  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 17:19:45.261  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.261  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 17:19:45.261  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 17:19:45.261  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-23 17:19:45.261  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97a2c88 removed from the list
11-23 17:19:45.261  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.261  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.261  5640  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.261  5640  5640 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 17:19:45.261  5640  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.261  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.261  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 17:19:45.262  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf6a4d2 added. We now have 3 listener(s)
11-23 17:19:45.262  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.262  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-23 17:19:45.262  5640  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 17:19:45.263  5876  5892 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 17:19:45.263  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.263  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 17:19:45.263  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 17:19:45.263  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 17:19:45.263  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 17:19:45.264  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa859a3 added. We now have 4 listener(s)
11-23 17:19:45.264  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 17:19:45.264  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 17:19:45.267  4478  5951 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-23 17:19:45.267  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 17:19:45.267  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1004a0 added. We now have 4 listener(s)
,11-23 17:19:45.269  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 17:19:45.269  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 17:19:45.269  5640  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 17:19:45.270  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 17:19:45.270  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fae859 added. We now have 5 listener(s)
11-23 17:19:45.270  5876  5892 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 17:19:45.270  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.270  5640  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 17:19:45.271  5640  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 17:19:45.271  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:19:45.271  5640  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 17:19:45.271  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:19:45.271  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 17:19:45.271  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 17:19:45.271  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf6a4d2 removed from the list
11-23 17:19:45.271  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.271  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa859a3 removed from the list
11-23 17:19:45.271  5640  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-23 17:19:45.272  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.272  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.272  5876  5895 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 17:19:45.276  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.276  5876  5892 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 17:19:45.277  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.277  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.277  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.277  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:19:45.277  5876  5892 E BtGatt.ContextMap: Context not found for ID 5
11-23 17:19:45.277  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:19:45.277  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.277  5640  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa859a3 not in the list
11-23 17:19:45.277  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.277  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-23 17:19:45.278  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.278  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.278  5640  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-23 17:19:45.278  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 17:19:45.278  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 17:19:45.278  5640  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 17:19:45.278  5640  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fae859 removed from the list
11-23 17:19:45.278  5640  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 17:19:45.278  5640  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 17:19:45.278  5640  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 17:19:45.279  5640  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1004a0 removed from the list
11-23 17:19:45.279  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-23 17:19:45.279  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-23 17:19:45.279  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-23 17:19:45.279  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 17:19:45.280  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-23 17:19:45.280  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-23 17:19:45.283  5876  5892 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 17:19:45.283  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.284  5876  5895 D BtGatt.ScanManager: stopping BLe Batch
,11-23 17:19:45.288  5876  5892 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 17:19:45.288  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 17:19:45.288  5876  5895 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 17:19:45.293  5876  5892 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 17:19:45.293  5876  5892 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 17:19:45.650  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 17:19:45.711  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 17:19:45.763  5640  5640 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 17:19:47.452  5640  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 17:19:47.452  5640  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 17:19:48.251  5640  5958 W !!      : call onHalfStreamCopied
,11-23 17:19:48.251  5640  5958 I testCopyDataAndClose: closing input stream
,11-23 17:19:48.721   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:49.021  5640  5958 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 17:19:49.021  5640  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 17:19:49.022  5640  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 17:19:49.022  5640  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 17:19:49.022  5640  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 17:19:49.022  5640  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 17:19:49.022  5640  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-23 17:19:49.022  5640  5958 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 17:19:49.022  5640  5958 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 17:19:49.022  5640  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 17:19:49.022  5640  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 17:19:49.722   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:50.723   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:51.724   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:52.726   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:19:52.989   930  3011 D ConnectivityService: handlePromptUnvalidated 102
,11-23 17:19:53.315  5640  5959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
11-23 17:19:53.315  5640  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 17:19:53.727   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 17:19:55.314  5640  5687 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 177. Connection data: Peer properties: [null null].
11-23 17:19:55.314  5640  5687 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 17:19:55.315  5640  5687 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 177, name: My test thread name)
,11-23 17:19:55.358  5640  5959 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-23 17:19:55.358  5640  5959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
11-23 17:19:55.358  5640  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-23 17:19:55.444  5640  5960 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 17:19:55.444  5640  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 17:19:56.027   930  3009 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,11-23 17:19:57.062  5640  5960 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 17:19:57.062  5640  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 17:19:57.062  5640  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 17:19:57.062  5640  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 17:19:57.062  5640  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 17:19:57.062  5640  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 17:19:57.062  5640  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 17:19:57.063  5640  5960 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 17:19:57.063  5640  5960 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 17:19:57.063  5640  5960 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 17:19:57.063  5640  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 17:20:01.265  5640  5961 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-23 17:20:01.265  5640  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 17:20:01.266  5640  5961 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 181, thread name: My test thread name). Connection data: Peer properties: [null null].
11-23 17:20:01.266  5640  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 17:20:01.266  5640  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 17:20:01.266  5640  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 17:20:01.266  5640  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 17:20:01.267  5640  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 17:20:01.267  5640  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 17:20:01.267  5640  5961 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 17:20:01.267  5640  5961 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 17:20:01.267  5640  5961 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-23 17:20:01.267  5640  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-23 17:20:01.269  5640  5687 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-23 17:20:01.272  5640  5962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-23 17:20:01.272  5640  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 17:20:01.274  5640  5962 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 185, thread name: My test thread name): Test exception.
,11-23 17:20:01.274  5640  5962 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-23 17:20:01.274  5640  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-23 17:20:01.274  5640  5962 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-23 17:20:01.274  5640  5962 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-23 17:20:01.274  5640  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-23 17:20:01.280  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-23 17:20:01.280  5640  5687 I jxcore-log: 
,11-23 17:20:01.280  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-23 17:20:01.280  5640  5687 I jxcore-log: 
11-23 17:20:01.280  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-23 17:20:01.280  5640  5687 I jxcore-log: 
11-23 17:20:01.281  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-23 17:20:01.281  5640  5687 I jxcore-log: 
11-23 17:20:01.281  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG UnitTest_app: 'Total duration:  91700'
11-23 17:20:01.281  5640  5687 I jxcore-log: 
,11-23 17:20:01.284  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-23 17:20:01.284  5640  5687 I jxcore-log: 
,11-23 17:20:01.288  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 17:20:01.288  5640  5687 I jxcore-log: 
,11-23 17:20:01.289  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 17:20:01.289  5640  5687 I jxcore-log: 
11-23 17:20:01.290  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 17:20:01.290  5640  5687 I jxcore-log: 
11-23 17:20:01.290  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 17:20:01.290  5640  5687 I jxcore-log: 
11-23 17:20:01.290  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 17:20:01.290  5640  5687 I jxcore-log: 
11-23 17:20:01.291  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 17:20:01.291  5640  5687 I jxcore-log: 
11-23 17:20:01.291  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 17:20:01.291  5640  5687 I jxcore-log: 
,11-23 17:20:01.291  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 17:20:01.291  5640  5687 I jxcore-log: 
11-23 17:20:01.291  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 17:20:01.291  5640  5687 I jxcore-log: 
11-23 17:20:01.292  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 17:20:01.292  5640  5687 I jxcore-log: 
11-23 17:20:01.292  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 17:20:01.292  5640  5687 I jxcore-log: 
11-23 17:20:01.292  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 17:20:01.292  5640  5687 I jxcore-log: 
11-23 17:20:01.292  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 17:20:01.292  5640  5687 I jxcore-log: 
11-23 17:20:01.292  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 17:20:01.292  5640  5687 I jxcore-log: 
11-23 17:20:01.293  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 17:20:01.293  5640  5687 I jxcore-log: 
,11-23 17:20:01.293  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 17:20:01.293  5640  5687 I jxcore-log: 
11-23 17:20:01.293  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 17:20:01.293  5640  5687 I jxcore-log: 
11-23 17:20:01.293  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 17:20:01.293  5640  5687 I jxcore-log: 
11-23 17:20:01.294  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 17:20:01.294  5640  5687 I jxcore-log: 
11-23 17:20:01.294  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 17:20:01.294  5640  5687 I jxcore-log: 
11-23 17:20:01.294  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 17:20:01.294  5640  5687 I jxcore-log: 
,11-23 17:20:01.294  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 17:20:01.294  5640  5687 I jxcore-log: 
11-23 17:20:01.295  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 17:20:01.295  5640  5687 I jxcore-log: 
11-23 17:20:01.295  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 17:20:01.295  5640  5687 I jxcore-log: 
11-23 17:20:01.297  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 17:20:01.297  5640  5687 I jxcore-log: 
11-23 17:20:01.297  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 17:20:01.297  5640  5687 I jxcore-log: 
11-23 17:20:01.297  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 17:20:01.297  5640  5687 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,11-23 17:20:01.297  5640  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 17:20:01.297  5640  5687 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-23 17:20:01.298  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 17:20:01.298  5640  5687 I jxcore-log: 
11-23 17:20:01.298  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 17:20:01.298  5640  5687 I jxcore-log: 
11-23 17:20:01.298  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 17:20:01.298  5640  5687 I jxcore-log: 
11-23 17:20:01.298  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 17:20:01.298  5640  5687 I jxcore-log: 
11-23 17:20:01.298  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 17:20:01.298  5640  5687 I jxcore-log: 
,11-23 17:20:01.299  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 17:20:01.299  5640  5687 I jxcore-log: 
,11-23 17:20:01.304  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-23 17:20:01.304  5640  5687 I jxcore-log: 
11-23 17:20:01.304  5640  5687 I jxcore-log: 2016-11-23 16:20:01 - WARN testUtils: 'myNameCallback not set!'
11-23 17:20:01.304  5640  5687 I jxcore-log: 
,11-23 17:20:01.311  5640  5640 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-23 17:20:03.388  5640  5687 I jxcore-log: 2016-11-23 16:20:03 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-23 17:20:03.388  5640  5687 I jxcore-log: 
,11-23 17:20:03.390  5640  5687 I jxcore-log: 2016-11-23 16:20:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-23 17:20:03.390  5640  5687 I jxcore-log: 
,11-23 17:20:03.742  5640  5687 I jxcore-log: 2016-11-23 16:20:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-23 17:20:03.742  5640  5687 I jxcore-log: 
,11-23 17:20:03.753  5640  5687 I jxcore-log: 2016-11-23 16:20:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-23 17:20:03.753  5640  5687 I jxcore-log: 
,11-23 17:20:04.884  5640  5687 I jxcore-log: 2016-11-23 16:20:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-23 17:20:04.884  5640  5687 I jxcore-log: 
,11-23 17:20:05.076  5640  5687 I jxcore-log: 2016-11-23 16:20:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-23 17:20:05.076  5640  5687 I jxcore-log: 
,11-23 17:20:05.082  5640  5687 I jxcore-log: 2016-11-23 16:20:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-23 17:20:05.082  5640  5687 I jxcore-log: 
,11-23 17:20:05.087  5640  5687 I jxcore-log: 2016-11-23 16:20:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-23 17:20:05.087  5640  5687 I jxcore-log: 
,11-23 17:20:05.578  5640  5687 I jxcore-log: 2016-11-23 16:20:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-23 17:20:05.578  5640  5687 I jxcore-log: 
,11-23 17:20:05.623  5640  5687 I jxcore-log: 2016-11-23 16:20:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-23 17:20:05.623  5640  5687 I jxcore-log: 
,11-23 17:20:05.637  5640  5687 I jxcore-log: 2016-11-23 16:20:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-23 17:20:05.637  5640  5687 I jxcore-log: 
,11-23 17:20:05.641  5640  5687 I jxcore-log: 2016-11-23 16:20:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-23 17:20:05.641  5640  5687 I jxcore-log: 
,11-23 17:20:05.917  5640  5687 I jxcore-log: 2016-11-23 16:20:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-23 17:20:05.917  5640  5687 I jxcore-log: 
,11-23 17:20:06.048  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-23 17:20:06.048  5640  5687 I jxcore-log: 
,11-23 17:20:06.421  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-23 17:20:06.421  5640  5687 I jxcore-log: 
,11-23 17:20:06.430  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-23 17:20:06.430  5640  5687 I jxcore-log: 
,11-23 17:20:06.434  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-23 17:20:06.434  5640  5687 I jxcore-log: 
,11-23 17:20:06.439  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-23 17:20:06.439  5640  5687 I jxcore-log: 
,11-23 17:20:06.444  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-23 17:20:06.444  5640  5687 I jxcore-log: 
,11-23 17:20:06.471  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-23 17:20:06.471  5640  5687 I jxcore-log: 
,11-23 17:20:06.507  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-23 17:20:06.507  5640  5687 I jxcore-log: 
,11-23 17:20:06.515  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-23 17:20:06.515  5640  5687 I jxcore-log: 
,11-23 17:20:06.521  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-23 17:20:06.521  5640  5687 I jxcore-log: 
,11-23 17:20:06.537  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-23 17:20:06.537  5640  5687 I jxcore-log: 
,11-23 17:20:06.552  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-23 17:20:06.552  5640  5687 I jxcore-log: 
,11-23 17:20:06.558  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-23 17:20:06.558  5640  5687 I jxcore-log: 
,11-23 17:20:06.564  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-23 17:20:06.564  5640  5687 I jxcore-log: 
,11-23 17:20:06.577  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-23 17:20:06.577  5640  5687 I jxcore-log: 
,11-23 17:20:06.594  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-23 17:20:06.594  5640  5687 I jxcore-log: 
,11-23 17:20:06.609  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-23 17:20:06.609  5640  5687 I jxcore-log: 
,11-23 17:20:06.619  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-23 17:20:06.619  5640  5687 I jxcore-log: 
,11-23 17:20:06.632  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-23 17:20:06.632  5640  5687 I jxcore-log: 
,11-23 17:20:06.642  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-23 17:20:06.642  5640  5687 I jxcore-log: 
,11-23 17:20:06.655  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-23 17:20:06.655  5640  5687 I jxcore-log: 
,11-23 17:20:06.665  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-23 17:20:06.665  5640  5687 I jxcore-log: 
,11-23 17:20:06.672  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-23 17:20:06.672  5640  5687 I jxcore-log: 
,11-23 17:20:06.694  5640  5687 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-23 17:20:06.695  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO testUtils: 'BLE multiple advertisement supported'
11-23 17:20:06.695  5640  5687 I jxcore-log: 
,11-23 17:20:06.729  5640  5687 I jxcore-log: 2016-11-23 16:20:06 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-23 17:20:06.729  5640  5687 I jxcore-log: 
,11-23 17:20:06.853   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272016, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 17:20:07.073  5640  5687 I jxcore-log: 2016-11-23 16:20:07 - DEBUG CoordinatedClient: 'connected to the test server'
11-23 17:20:07.073  5640  5687 I jxcore-log: 
,11-23 17:20:08.729   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:20:09.730   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:20:10.731   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:20:11.732   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:20:11.914   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=277077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 17:20:12.733   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:20:13.734   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 17:20:24.970   930  3009 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 17:20:28.274   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=293437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 17:20:33.735   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:20:34.736   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:20:35.738   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:20:36.740   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:20:36.994   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=302157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 17:20:37.741   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:20:38.742   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 17:20:45.226   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 17:20:48.252   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 17:20:53.340   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=318503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 17:21:02.021   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=327184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 17:21:03.743   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 17:21:03.743   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 17:21:04.976   930  3009 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 17:21:18.354   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=343517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 17:21:18.550   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 17:21:18.744   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:19.745   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:20.746   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:21.748   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:22.749   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:23.749   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 17:21:24.977   930  3009 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 17:21:27.047   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=352210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 17:21:27.640   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 17:21:28.751   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:29.752   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:30.754   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:31.755   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:32.756   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:33.757   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 17:21:43.367   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=368530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 17:21:43.758   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:44.760   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:45.761   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:46.763   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:47.764   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:21:48.765   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 17:21:52.074   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=377237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 17:22:03.767   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:22:04.768   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:22:04.982   930  3009 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 17:22:05.770   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:22:06.771   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:22:07.772   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:22:08.380   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=393543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 17:22:08.773   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 17:22:17.101   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=402264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 17:22:24.985   930  3009 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 17:22:28.774   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:22:29.776   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:22:30.777   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:22:31.778   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:22:32.780   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:22:33.447   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=418610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 17:22:33.781   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 17:22:42.127   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=427290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 17:22:44.987   930  3009 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 17:22:49.340   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 17:22:52.367   930  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 17:22:58.461   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=443624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 17:22:58.781   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 17:22:58.782   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 17:23:07.154   930  5934 D NetlinkSocketObserver: NeighborEvent{elapsedMs=452317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 17:23:18.783   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:23:19.295  5640  5687 I jxcore-log: 2016-11-23 16:23:19 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-23 17:23:19.295  5640  5687 I jxcore-log: 
,11-23 17:23:19.585  5640  5687 I jxcore-log: 2016-11-23 16:23:19 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 17:23:19.585  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 17:23:19.585  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 17:23:19.585  5640  5687 I jxcore-log: emit@events.js:82:1
11-23 17:23:19.585  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 17:23:19.585  5640  5687 I jxcore-log: emit@events.js:82:1''
11-23 17:23:19.585  5640  5687 I jxcore-log: 
,11-23 17:23:19.587  5640  5687 I jxcore-log: 2016-11-23 16:23:19 - DEBUG CoordinatedClient: 'test client failed'
11-23 17:23:19.587  5640  5687 I jxcore-log: 
,11-23 17:23:19.597  5640  5687 I jxcore-log: 2016-11-23 16:23:19 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 17:23:19.597  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 17:23:19.597  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 17:23:19.597  5640  5687 I jxcore-log: emit@events.js:82:1
11-23 17:23:19.597  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 17:23:19.597  5640  5687 I jxcore-log: emit@events.js:82:1''
11-23 17:23:19.597  5640  5687 I jxcore-log: 
,11-23 17:23:19.598  5640  5687 I jxcore-log: 2016-11-23 16:23:19 - DEBUG CoordinatedClient: 'test client failed'
11-23 17:23:19.598  5640  5687 I jxcore-log: 
,11-23 17:23:19.602  5640  5687 I jxcore-log: 2016-11-23 16:23:19 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 17:23:19.602  5640  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 17:23:19.602  5640  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 17:23:19.602  5640  5687 I jxcore-log: emit@events.js:82:1
11-23 17:23:19.602  5640  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 17:23:19.602  5640  5687 I jxcore-log: emit@events.js:82:1''
11-23 17:23:19.602  5640  5687 I jxcore-log: 
11-23 17:23:19.603  5640  5687 I jxcore-log: 2016-11-23 16:23:19 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-23 17:23:19.603  5640  5687 I jxcore-log: 
,11-23 17:23:19.784   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:23:20.195  5974  5974 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-23 17:23:20.217  5974  5974 D AndroidRuntime: CheckJNI is OFF
,11-23 17:23:20.245  5974  5974 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-23 17:23:20.283  5974  5974 I Radio-JNI: register_android_hardware_Radio DONE
,11-23 17:23:20.300  5974  5974 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-23 17:23:20.317   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-23 17:23:20.318   930   943 I ActivityManager: Killing 5640:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-23 17:23:20.440   930  3189 D GraphicsStats: Buffer count: 2
,11-23 17:23:20.440   930  3190 I WindowState: WIN DEATH: Window{ca83403 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-23 17:23:20.441   930  3010 D WifiService: Client connection lost with reason: 4
,11-23 17:23:20.448   930   943 W ActivityManager: Force removing ActivityRecord{251c908 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-23 17:23:20.460   930   953 I art     : Starting a blocking GC Explicit
,11-23 17:23:20.466   930  3450 W ActivityManager: Spurious death for ProcessRecord{38eae91 0:com.test.thalitest/u0a77}, curProc for 5640: null
,11-23 17:23:20.503  3190  3190 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28955]" dev="sockfs" ino=28955 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 17:23:20.504   930  3190 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5640 uid 10077
11-23 17:23:20.507  3688  3688 I Keyboard.Facilitator: onFinishInput()
,11-23 17:23:20.506  3190  3190 W Binder_4: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[28955]" dev="sockfs" ino=28955 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 17:23:20.529  3998  3998 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,11-23 17:23:20.562   930   953 I art     : Explicit concurrent mark sweep GC freed 103140(7MB) AllocSpace objects, 65(2044KB) LOS objects, 33% free, 29MB/44MB, paused 1.680ms total 101.468ms
,11-23 17:23:20.576  3998  5986 I MicroRecognitionRnrImpl: Starting detection.
,11-23 17:23:20.578  3998  5987 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@4dc761f
,11-23 17:23:20.581   513  5989 I AudioFlinger: AudioFlinger's thread 0xf1d40000 ready to run
,11-23 17:23:20.582   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
11-23 17:23:20.584   513  3031 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-23 17:23:20.585  5974  5974 I art     : System.exit called, status: 0
11-23 17:23:20.586  5974  5974 I AndroidRuntime: VM exiting with result code 0.
11-23 17:23:20.586  3998  5987 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@4dc761f
,11-23 17:23:20.593   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-23 17:23:20.596   513  5989 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-23 17:23:20.596   513  5989 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-23 17:23:20.596   513  5989 I ACDB-LOADER: ACDB AFE returned = -19
11-23 17:23:20.596   513  5989 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
,11-23 17:23:20.596   513  5989 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
,11-23 17:23:20.596   513  5989 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-23 17:23:20.607   513  5989 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-23 17:23:20.614  3688  3688 I Keyboard.Facilitator: resetDictionaries() : en_US
11-23 17:23:20.614  5876  5876 D BluetoothMapAppObserver: onReceive
11-23 17:23:20.614  5876  5876 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-23 17:23:20.617  3983  4219 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-23 17:23:20.625  3688  5993 I Keyboard.Facilitator.DecoderInitializer: run()
,11-23 17:23:20.628   930  2974 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-23 17:23:20.637  3688  5993 I Decoder : createOrResetDecoder
,11-23 17:23:20.658  3436  5997 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-23 17:23:20.669   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-23 17:23:20.678  3808  3808 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-23 17:23:20.679    29    29 W kworker/3:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 17:23:20.686    29    29 W kworker/3:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 17:23:20.689  3998  3998 I HotwordWorkerImpl: onReady
,11-23 17:23:20.692  3616  3616 I ConfigService: onCreate
,11-23 17:23:20.703    29    29 W kworker/3:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 17:23:20.707  3616  3616 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-23 17:23:20.708  3616  3616 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-23 17:23:20.709  3616  3616 E AndroidRuntime: FATAL EXCEPTION: main
11-23 17:23:20.709  3616  3616 E AndroidRuntime: Process: com.google.process.gapps, PID: 3616
11-23 17:23:20.709  3616  3616 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-23 17:23:20.709  3616  3616 E AndroidRuntime: 	... 8 more
11-23 17:23:20.711  3852  3960 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-23 17:23:20.713  3688  5993 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-23 17:23:20.725   930   941 I ActivityManager: Start proc 6004:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-23 17:23:20.725  3852  3960 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-23 17:23:20.725  3852  3960 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3852
11-23 17:23:20.725  3852  3960 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 17:23:20.725  3852  3960 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 17:23:20.725  3852  3960 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 17:23:20.725  3852  3960 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 17:23:20.725  3852  3960 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 17:23:20.725  3852  3960 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 17:23:20.725  3852  3960 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-23 17:23:20.725  3852  3960 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-23 17:23:20.725  3852  3960 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-23 17:23:20.725  3852  3960 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-23 17:23:20.725  3852  3960 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 17:23:20.725  3852  3960 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 17:23:20.749   404   404 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[14092]" dev="sockfs" ino=14092 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 17:23:20.749   404   404 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[14092]" dev="sockfs" ino=14092 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 17:23:20.754   930  6016 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 17:23:20.753   404   404 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[32412]" dev="sockfs" ino=32412 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 17:23:20.753   404   404 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32412]" dev="sockfs" ino=32412 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 17:23:20.766   930  3189 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-23 17:23:20.767  3688  5993 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-23 17:23:20.767   930  6018 E DropBoxManagerService: Can't write: system_app_crash
11-23 17:23:20.767   930  6018 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-23 17:23:20.767   930  6018 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 17:23:20.767   930  6018 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 17:23:20.767   930  6018 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 17:23:20.767   930  6018 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 17:23:20.767   930  6018 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 17:23:20.767   930  6018 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 17:23:20.767   930  6018 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 17:23:20.767   930  6018 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 17:23:20.767   930  6018 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 17:23:20.767   930  6018 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 17:23:20.767   930  6018 E DropBoxManagerService: 	... 5 more
,11-23 17:23:20.770  3998  4009 W SearchService: Abort, client detached.
,11-23 17:23:20.773  3998  3998 I HotwordDetector: Closing mic
11-23 17:23:20.773  3998  4264 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@4dc761f
11-23 17:23:20.773  3998  5987 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-23 17:23:20.775  3688  5993 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-23 17:23:20.775  3688  5993 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-23 17:23:20.779  3436  5997 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-23 17:23:20.780  3436  5997 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-23 17:23:20.780  3436  5997 E AndroidRuntime: Process: android.process.acore, PID: 3436
11-23 17:23:20.780  3436  5997 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 17:23:20.780  3436  5997 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 17:23:20.781  3436  3462 I Process : Sending signal. PID: 3436 SIG: 9
,11-23 17:23:20.785   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 17:23:20.795   930  6019 E DropBoxManagerService: Can't write: system_app_crash
11-23 17:23:20.795   930  6019 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-23 17:23:20.795   930  6019 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 17:23:20.795   930  6019 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 17:23:20.795   930  6019 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 17:23:20.795   930  6019 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 17:23:20.795   930  6019 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 17:23:20.795   930  6019 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 17:23:20.795   930  6019 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 17:23:20.795   930  6019 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 17:23:20.795   930  6019 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 17:23:20.795   930  6019 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 17:23:20.795   930  6019 E DropBoxManagerService: 	... 5 more
,11-23 17:23:20.825   930  3850 I ActivityManager: Process android.process.acore (pid 3436) has died
11-23 17:23:20.826   930  3850 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-23 17:23:20.848   513  5989 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-23 17:23:20.849   513  5989 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-23 17:23:20.854   513  5989 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-23 17:23:20.854   513  5989 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-23 17:23:20.854   513  3031 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-23 17:23:20.856  3998  4265 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-23 17:23:20.857  3998  5986 I MicroRecognitionRnrImpl: Detection finished
,11-23 17:23:21.076   381   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
